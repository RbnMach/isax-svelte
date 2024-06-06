<script lang="ts">
	import { Isax, Bulk } from "$lib/index.js";
	
	let name = 'user';
</script>

<p><Isax {name} type="twotone" /> Isax</p>

<p><Bulk name="home" /> Home</p>

<button on:click={() => (name == 'user' ? (name = 'home') : (name = 'user'))}>Click</button>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
