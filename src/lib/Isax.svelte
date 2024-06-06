<script lang="ts">
	import { fade } from 'svelte/transition';

	const svgError = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
								<circle cx="11.5" cy="11.5" r="11.5" opacity="0.2" fill="currentColor">
								</circle>
								<circle cx="11.5" cy="11.5" r="0" fill="currentColor">
									<animate attributeName="r" calcMode="spline" dur="1.2s" values="0;11"
										keySplines=".52,.6,.25,.99" repeatCount="indefinite" />
									<animate attributeName="opacity" calcMode="spline" dur="1.2s" values="1;0"
										keySplines=".52,.6,.25,.99" repeatCount="indefinite" />
								</circle>
							</svg>`;

	export let name: string;
	export let type: 'bold' | 'broken' | 'bulk' | 'linear' | 'outline' | 'twotone';
	export let size = '1em';
	export let axis_y = '0.15em';
	export let axis_x = '0';

	// Función para cargar el SVG
	async function loadSvg() {
		try {
			// Determinar la ruta del SVG basado en `type` y `name`
			const module = await import(`./svg/${type}/${name}.svg?raw`);
			return module.default;
		} catch (error) {
			console.error('Error loading SVG:', error);
			throw error;
		}
	}
</script>

{#key name}
	{#await loadSvg()}
		<span
			in:fade={{ delay: 100, duration: 300 }}
			style="width: {size}; height: {size}; top: {axis_y}; left: {axis_x};"
		>
			{@html svgError}
		</span>
	{:then svg}
		<span
			in:fade={{ delay: 100, duration: 300 }}
			style="width: {size}; height: {size}; top: {axis_y}; left: {axis_x};"
		>
			{@html svg}
		</span>
	{:catch}
		<span
			in:fade={{ delay: 100, duration: 300 }}
			style="width: {size}; height: {size}; top: {axis_y}; left: {axis_x};"
		>
			{@html svgError}
		</span>
	{/await}
{/key}

<style>
	span {
		display: inline-block;
		stroke-width: 0;
		stroke: currentColor;
		fill: currentColor;
		position: relative;
	}
</style>
