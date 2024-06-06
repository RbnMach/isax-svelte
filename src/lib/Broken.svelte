<script lang="ts">
	import * as SVGs from '$lib/svg-broken.js';
	import svgError from '$lib/svg/error.svg?raw';

	type SVG = typeof SVGs;
	interface SVGIndex {
		[key: string]: SVG[keyof SVG];
	}
	const SVGsIndex: SVGIndex = SVGs as SVGIndex;

	import { fade } from 'svelte/transition';

	export let name: keyof SVGIndex;
	export let size = '1em';
	export let axis_y = '0.13em';
	export let axis_x = '0';
</script>

{#key name}
	<span
		in:fade={{ delay: 100, duration: 300 }}
		style="width: {size}; height: {size}; top: {axis_y}; left: {axis_x};"
	>
		{#if SVGsIndex[name]}
			{@html SVGsIndex[name]}
		{:else}
			{@html svgError}
		{/if}
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
