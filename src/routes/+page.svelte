<script lang="ts">
	import { Isax, Bold, Broken, Bulk, Linear, Outline, Twotone } from '$lib/index.js';

	let name = 'user';
	let type = 'bold';
</script>

<p><Isax {name} type="{type}" size="2em" axis_y="0.5em" axis_x="0.5em" /> Isax</p>
<button on:click={() => (name == 'user' ? (name = 'home') : (name = 'user'))}>Cambiar name</button>
<button on:click={() => (type == 'bold' ? (type = 'linear') : (type = 'bold'))}>Cambiar tipo</button>

<p><Bold name="home" size="2em" axis_y="0.5em" axis_x="0.5em" /> Home</p>
<p><Broken name="home" size="35px" axis_y="0.5px" axis_x="-1px" /> Home</p>
<p><Bulk name="home" size="35px" axis_y="0.5px" axis_x="-1px" /> Home</p>
<p><Linear name="home" size="4rem" axis_y="-0.5rem" axis_x="0.5rem" /> Home</p>
<p><Outline name="home" size="25pt" axis_y="3pt" axis_x="0.5pt" /> Home</p>
<p><Twotone name="home" size="8%" axis_y="5px" axis_x="0.5px" /> Home</p>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
