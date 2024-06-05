<script lang="ts">
	import { fade } from 'svelte/transition';

	export let name: string;
	export let type: 'bold' | 'broken' | 'bulk' | 'linear' | 'outline' | 'twotone';
	export let size = '1em';
	export let axis_y = '0.15em';
	export let axis_x = '0';

	// let svgContent = "";

	// // Función para cargar el icono
	// async function loadIcon() {	
	// 	svgContent = (await import(`./svg/${type}/${name}.svg?raw`)).default;
	// 	try {
	// 		svgContent = (await import(`./svg/${type}/${name}.svg?raw`)).default;
	// 	} catch (error) {
	// 		svgContent = (await import(`./svg/load-error.svg?raw`)).default;
	// 	}
	// }
	// // Si cambia el name recarga el icono
	// // $: if (name) loadIcon();

	// loadIcon();

		let svgContent = "./svg/bold/user.svg?raw";
</script>

{#key name}
	<span
		in:fade={{ delay: 100, duration: 300 }}
		style="width: {size}; height: {size}; top: {axis_y}; left: {axis_x};"
	>
	{@html svgContent}
	</span>
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
