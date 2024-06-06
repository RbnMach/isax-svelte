<script lang="ts">
	import Bold from '$lib/Bold.svelte';
	import Broken from '$lib/Broken.svelte';
	import Bulk from '$lib/Bulk.svelte';
	import Linear from '$lib/Linear.svelte';
	import Outline from '$lib/Outline.svelte';
	import Twotone from '$lib/Twotone.svelte';

	export let type: 'bold' | 'broken' | 'bulk' | 'linear' | 'outline' | 'twotone';
	export let name: string;
	export let size = '1em';
	export let axis_y = '0.13em';
	export let axis_x = '0';
</script>

{#if type === 'bold'}
	<Bold {name} {size} {axis_y} {axis_x} />
{/if}

{#if type === 'broken'}
	<Broken {name} {size} {axis_y} {axis_x} />
{/if}

{#if type === 'bulk'}
	<Bulk {name} {size} {axis_y} {axis_x} />
{/if}

{#if type === 'linear'}
	<Linear {name} {size} {axis_y} {axis_x} />
{/if}

{#if type === 'outline'}
	<Outline {name} {size} {axis_y} {axis_x} />
{/if}

{#if type === 'twotone'}
	<Twotone {name} {size} {axis_y} {axis_x} />
{/if}
