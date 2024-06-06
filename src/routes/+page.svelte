<script lang="ts">
	import { Isax, Bold, Bulk, Linear, Outline, Twotone } from "$lib/index.js";
	
	let name = 'user';
</script>

<p><Isax {name} type="twotone" size="2em" axis_y="0.5em" axis_x="0.5em" /> Isax</p>
<button on:click={() => (name == 'user' ? (name = 'home') : (name = 'user'))}>Click</button>

<p><Bold name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<!-- <p><Bulk name="home" size="15px" axis_y="12px" axis_x="1px" /> Home</p>
<p><Linear name="home" size="2rem" axis_y="5rem" axis_x="5rem" /> Home</p>
<p><Outline name="home" size="1%" axis_y="4%" axis_x="2%" /> Home</p>
<p><Twotone name="home" size="2pt" axis_y="3pt" axis_x="1pt" /> Home</p> -->

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
