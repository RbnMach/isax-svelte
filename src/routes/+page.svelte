<script lang="ts">
	import { Isax, Bold, Bulk, Linear, Outline, Twotone } from "$lib/index.js";
	
	let name = 'user';
</script>

<p><Isax {name} type="twotone" size="2em" axis_y="0.5em" axis_x="0.5em" /> Isax</p>

<p><Bold name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Bulk name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Linear name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Outline name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Twotone name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>

<button on:click={() => (name == 'user' ? (name = 'home') : (name = 'user'))}>Click</button>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
