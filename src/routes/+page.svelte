<script lang="ts">
	import { Isax } from '$lib/index.js';

	let name = 'user';
</script>

<p><Isax {name} type="bold" /></p>

<button on:click={() => (name == 'user'? name = 'home': name = 'user')}>Button</button>

<style>
	p{
		color: red;
		font-size: 2em;
	}
</style>