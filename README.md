<a href='https://ko-fi.com/rubenmach' target='_blank'><img height='42' style='border:0px;height:42px;' src='https://storage.ko-fi.com/cdn/kofi3.png?v=3' alt='Buy Me a Coffee at ko-fi.com' /></a>

# Iconsax for Svelte

This is an icon library for Svelte based on [iconsax](https://iconsax.io/). These icons are adapted to inherit the colors and sizes, you can use it as if it were a letter font.

## Install the library

```bash
# create a new project in the current directory
npm i isaxvelte@latest
```

## Basic usage

```html
<script lang="ts">
	import { Isax } from 'isaxvelte';
</script>

<p><Isax name="user" type="twotone" /> Isax</p>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
```

```html
<script lang="ts">
	import { Bold, Broken, Bulk, Linear, Outline, Twotone } from 'isaxvelte';
</script>

<p><Bold name="home" /> Home</p>
<p><Broken name="home" /> Home</p>
<p><Bulk name="home" /> Home</p>
<p><Linear name="home" /> Home</p>
<p><Outline name="home" /> Home</p>
<p><Twotone name="home" /> Home</p>

<style>
	p {
		color: red;
		font-size: 45px;
	}
</style>
```

## More examples

```html
<script lang="ts">
	import { Isax, Bold, Broken, Bulk, Linear, Outline, Twotone } from 'isaxvelte';
	let name = 'user';
</script>

<p><Isax {name} type="twotone" size="2em" axis_y="0.5em" axis_x="0.5em" /> Isax</p>
<button on:click="{()" ="">(name == 'user' ? (name = 'home') : (name = 'user'))}>Click</button>

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
```

## Propiedades del componente Isax

| Prop     | Type                                                |          | Note                                         |
| -------- | --------------------------------------------------- | -------- | -------------------------------------------- |
| `name`   | `string`                                            | required | name of the icon                             |
| `type`   | `linear` `outline` `twoTone` `bulk` `broken` `bold` | requered | icons styles                                 |
| `size`   | `string`                                            | optional | size="24em", size="24px", size="24rem, etc." |
| `axis_x` | `string`                                            | optional | axis_x="24em", axis_x="24px", etc."          |
| `axis_y` | `string`                                            | optional | axis_x="24em", axis_x="24px", etc."          |

## Propiedades de los componentes Bold, Broken, Bulk, Linear, Outline, Twotone

| Prop     | Type     |          | Note                                         |
| -------- | -------- | -------- | -------------------------------------------- |
| `name`   | `string` | required | name of the icon                             |
| `size`   | `string` | optional | size="24em", size="24px", size="24rem, etc." |
| `axis_x` | `string` | optional | axis_x="24em", axis_x="24px", etc."          |
| `axis_y` | `string` | optional | axis_x="24em", axis_x="24px", etc."          |

## Icon list

Isaxvelte cubre toda la lista de iconos de [iconsax](https://iconsax.io/).



<table>
  <thead>
    <tr>
      <th>Name Icon</th>
      <th>Linear</th>
      <th>Bold</th>
      <th>Broken</th>
      <th>Bulk</th>
      <th>Outline</th>
      <th>Twotone</th>
    </tr>
  </thead>
  <tbody><tr>
      <td>aave</td>
      <td><img src="src/lib/svg/linear/aave.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/aave.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/aave.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/aave.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/aave.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/aave.svg" height="60px"></td>
    </tr><tr>
      <td>activity</td>
      <td><img src="src/lib/svg/linear/activity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/activity.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/activity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/activity.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/activity.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/activity.svg" height="60px"></td>
    </tr><tr>
      <td>addcircle</td>
      <td><img src="src/lib/svg/linear/addcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/addcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/addcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/addcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/addcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/addcircle.svg" height="60px"></td>
    </tr><tr>
      <td>addsquare</td>
      <td><img src="src/lib/svg/linear/addsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/addsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/addsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/addsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/addsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/addsquare.svg" height="60px"></td>
    </tr><tr>
      <td>add</td>
      <td><img src="src/lib/svg/linear/add.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/add.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/add.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/add.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/add.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/add.svg" height="60px"></td>
    </tr><tr>
      <td>additem</td>
      <td><img src="src/lib/svg/linear/additem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/additem.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/additem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/additem.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/additem.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/additem.svg" height="60px"></td>
    </tr><tr>
      <td>airdrop</td>
      <td><img src="src/lib/svg/linear/airdrop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/airdrop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/airdrop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/airdrop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/airdrop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/airdrop.svg" height="60px"></td>
    </tr><tr>
      <td>airplanesquare</td>
      <td><img src="src/lib/svg/linear/airplanesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/airplanesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/airplanesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/airplanesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/airplanesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/airplanesquare.svg" height="60px"></td>
    </tr><tr>
      <td>airplane</td>
      <td><img src="src/lib/svg/linear/airplane.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/airplane.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/airplane.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/airplane.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/airplane.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/airplane.svg" height="60px"></td>
    </tr><tr>
      <td>airpod</td>
      <td><img src="src/lib/svg/linear/airpod.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/airpod.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/airpod.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/airpod.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/airpod.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/airpod.svg" height="60px"></td>
    </tr><tr>
      <td>airpods</td>
      <td><img src="src/lib/svg/linear/airpods.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/airpods.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/airpods.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/airpods.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/airpods.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/airpods.svg" height="60px"></td>
    </tr><tr>
      <td>alarm</td>
      <td><img src="src/lib/svg/linear/alarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alarm.svg" height="60px"></td>
    </tr><tr>
      <td>alignbottom</td>
      <td><img src="src/lib/svg/linear/alignbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alignbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alignbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alignbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alignbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alignbottom.svg" height="60px"></td>
    </tr><tr>
      <td>alignhorizontally</td>
      <td><img src="src/lib/svg/linear/alignhorizontally.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alignhorizontally.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alignhorizontally.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alignhorizontally.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alignhorizontally.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alignhorizontally.svg" height="60px"></td>
    </tr><tr>
      <td>alignleft</td>
      <td><img src="src/lib/svg/linear/alignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alignleft.svg" height="60px"></td>
    </tr><tr>
      <td>alignright</td>
      <td><img src="src/lib/svg/linear/alignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alignright.svg" height="60px"></td>
    </tr><tr>
      <td>aligntop</td>
      <td><img src="src/lib/svg/linear/aligntop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/aligntop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/aligntop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/aligntop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/aligntop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/aligntop.svg" height="60px"></td>
    </tr><tr>
      <td>alignvertically</td>
      <td><img src="src/lib/svg/linear/alignvertically.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/alignvertically.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/alignvertically.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/alignvertically.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/alignvertically.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/alignvertically.svg" height="60px"></td>
    </tr><tr>
      <td>android</td>
      <td><img src="src/lib/svg/linear/android.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/android.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/android.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/android.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/android.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/android.svg" height="60px"></td>
    </tr><tr>
      <td>ankr</td>
      <td><img src="src/lib/svg/linear/ankr.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ankr.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ankr.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ankr.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ankr.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ankr.svg" height="60px"></td>
    </tr><tr>
      <td>apple</td>
      <td><img src="src/lib/svg/linear/apple.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/apple.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/apple.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/apple.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/apple.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/apple.svg" height="60px"></td>
    </tr><tr>
      <td>aquarius</td>
      <td><img src="src/lib/svg/linear/aquarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/aquarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/aquarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/aquarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/aquarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/aquarius.svg" height="60px"></td>
    </tr><tr>
      <td>archive1</td>
      <td><img src="src/lib/svg/linear/archive1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archive1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archive1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archive1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archive1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archive1.svg" height="60px"></td>
    </tr><tr>
      <td>archive2</td>
      <td><img src="src/lib/svg/linear/archive2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archive2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archive2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archive2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archive2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archive2.svg" height="60px"></td>
    </tr><tr>
      <td>archiveadd</td>
      <td><img src="src/lib/svg/linear/archiveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archiveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archiveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archiveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archiveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archiveadd.svg" height="60px"></td>
    </tr><tr>
      <td>archivebook</td>
      <td><img src="src/lib/svg/linear/archivebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archivebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archivebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archivebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archivebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archivebook.svg" height="60px"></td>
    </tr><tr>
      <td>archiveminus</td>
      <td><img src="src/lib/svg/linear/archiveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archiveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archiveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archiveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archiveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archiveminus.svg" height="60px"></td>
    </tr><tr>
      <td>archiveslash</td>
      <td><img src="src/lib/svg/linear/archiveslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archiveslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archiveslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archiveslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archiveslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archiveslash.svg" height="60px"></td>
    </tr><tr>
      <td>archivetick</td>
      <td><img src="src/lib/svg/linear/archivetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archivetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archivetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archivetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archivetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archivetick.svg" height="60px"></td>
    </tr><tr>
      <td>archive</td>
      <td><img src="src/lib/svg/linear/archive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/archive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/archive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/archive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/archive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/archive.svg" height="60px"></td>
    </tr><tr>
      <td>arrangecircle2</td>
      <td><img src="src/lib/svg/linear/arrangecircle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrangecircle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrangecircle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrangecircle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrangecircle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrangecircle2.svg" height="60px"></td>
    </tr><tr>
      <td>arrangecircle</td>
      <td><img src="src/lib/svg/linear/arrangecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrangecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrangecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrangecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrangecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrangecircle.svg" height="60px"></td>
    </tr><tr>
      <td>arrangesquare2</td>
      <td><img src="src/lib/svg/linear/arrangesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrangesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrangesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrangesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrangesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrangesquare2.svg" height="60px"></td>
    </tr><tr>
      <td>arrangesquare</td>
      <td><img src="src/lib/svg/linear/arrangesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrangesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrangesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrangesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrangesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrangesquare.svg" height="60px"></td>
    </tr><tr>
      <td>arrow2</td>
      <td><img src="src/lib/svg/linear/arrow2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrow2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrow2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrow2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrow2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrow2.svg" height="60px"></td>
    </tr><tr>
      <td>arrow3</td>
      <td><img src="src/lib/svg/linear/arrow3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrow3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrow3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrow3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrow3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrow3.svg" height="60px"></td>
    </tr><tr>
      <td>arrowbottom</td>
      <td><img src="src/lib/svg/linear/arrowbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowbottom.svg" height="60px"></td>
    </tr><tr>
      <td>arrowcircledown</td>
      <td><img src="src/lib/svg/linear/arrowcircledown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowcircledown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowcircledown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowcircledown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowcircledown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowcircledown.svg" height="60px"></td>
    </tr><tr>
      <td>arrowcircleleft</td>
      <td><img src="src/lib/svg/linear/arrowcircleleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowcircleleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowcircleleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowcircleleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowcircleleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowcircleleft.svg" height="60px"></td>
    </tr><tr>
      <td>arrowcircleright</td>
      <td><img src="src/lib/svg/linear/arrowcircleright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowcircleright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowcircleright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowcircleright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowcircleright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowcircleright.svg" height="60px"></td>
    </tr><tr>
      <td>arrowcircleup</td>
      <td><img src="src/lib/svg/linear/arrowcircleup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowcircleup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowcircleup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowcircleup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowcircleup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowcircleup.svg" height="60px"></td>
    </tr><tr>
      <td>arrowdown1</td>
      <td><img src="src/lib/svg/linear/arrowdown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowdown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowdown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowdown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowdown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowdown1.svg" height="60px"></td>
    </tr><tr>
      <td>arrowdown2</td>
      <td><img src="src/lib/svg/linear/arrowdown2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowdown2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowdown2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowdown2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowdown2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowdown2.svg" height="60px"></td>
    </tr><tr>
      <td>arrowdown</td>
      <td><img src="src/lib/svg/linear/arrowdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowdown.svg" height="60px"></td>
    </tr><tr>
      <td>arrowleft1</td>
      <td><img src="src/lib/svg/linear/arrowleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowleft1.svg" height="60px"></td>
    </tr><tr>
      <td>arrowleft2</td>
      <td><img src="src/lib/svg/linear/arrowleft2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowleft2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowleft2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowleft2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowleft2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowleft2.svg" height="60px"></td>
    </tr><tr>
      <td>arrowleft3</td>
      <td><img src="src/lib/svg/linear/arrowleft3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowleft3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowleft3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowleft3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowleft3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowleft3.svg" height="60px"></td>
    </tr><tr>
      <td>arrowleft</td>
      <td><img src="src/lib/svg/linear/arrowleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowleft.svg" height="60px"></td>
    </tr><tr>
      <td>arrowright1</td>
      <td><img src="src/lib/svg/linear/arrowright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowright1.svg" height="60px"></td>
    </tr><tr>
      <td>arrowright2</td>
      <td><img src="src/lib/svg/linear/arrowright2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowright2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowright2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowright2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowright2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowright2.svg" height="60px"></td>
    </tr><tr>
      <td>arrowright3</td>
      <td><img src="src/lib/svg/linear/arrowright3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowright3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowright3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowright3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowright3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowright3.svg" height="60px"></td>
    </tr><tr>
      <td>arrowright</td>
      <td><img src="src/lib/svg/linear/arrowright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowright.svg" height="60px"></td>
    </tr><tr>
      <td>arrowsquaredown</td>
      <td><img src="src/lib/svg/linear/arrowsquaredown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowsquaredown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowsquaredown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowsquaredown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowsquaredown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowsquaredown.svg" height="60px"></td>
    </tr><tr>
      <td>arrowsquareleft</td>
      <td><img src="src/lib/svg/linear/arrowsquareleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowsquareleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowsquareleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowsquareleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowsquareleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowsquareleft.svg" height="60px"></td>
    </tr><tr>
      <td>arrowsquareright</td>
      <td><img src="src/lib/svg/linear/arrowsquareright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowsquareright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowsquareright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowsquareright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowsquareright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowsquareright.svg" height="60px"></td>
    </tr><tr>
      <td>arrowsquareup</td>
      <td><img src="src/lib/svg/linear/arrowsquareup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowsquareup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowsquareup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowsquareup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowsquareup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowsquareup.svg" height="60px"></td>
    </tr><tr>
      <td>arrowsquare</td>
      <td><img src="src/lib/svg/linear/arrowsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowsquare.svg" height="60px"></td>
    </tr><tr>
      <td>arrowswaphorizontal</td>
      <td><img src="src/lib/svg/linear/arrowswaphorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowswaphorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowswaphorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowswaphorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowswaphorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowswaphorizontal.svg" height="60px"></td>
    </tr><tr>
      <td>arrowswap</td>
      <td><img src="src/lib/svg/linear/arrowswap.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowswap.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowswap.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowswap.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowswap.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowswap.svg" height="60px"></td>
    </tr><tr>
      <td>arrowup1</td>
      <td><img src="src/lib/svg/linear/arrowup1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowup1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowup1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowup1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowup1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowup1.svg" height="60px"></td>
    </tr><tr>
      <td>arrowup2</td>
      <td><img src="src/lib/svg/linear/arrowup2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowup2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowup2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowup2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowup2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowup2.svg" height="60px"></td>
    </tr><tr>
      <td>arrowup3</td>
      <td><img src="src/lib/svg/linear/arrowup3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowup3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowup3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowup3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowup3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowup3.svg" height="60px"></td>
    </tr><tr>
      <td>arrowup</td>
      <td><img src="src/lib/svg/linear/arrowup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrowup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrowup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrowup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrowup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrowup.svg" height="60px"></td>
    </tr><tr>
      <td>arrow</td>
      <td><img src="src/lib/svg/linear/arrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/arrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/arrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/arrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/arrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/arrow.svg" height="60px"></td>
    </tr><tr>
      <td>attachcircle</td>
      <td><img src="src/lib/svg/linear/attachcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/attachcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/attachcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/attachcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/attachcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/attachcircle.svg" height="60px"></td>
    </tr><tr>
      <td>attachsquare</td>
      <td><img src="src/lib/svg/linear/attachsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/attachsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/attachsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/attachsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/attachsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/attachsquare.svg" height="60px"></td>
    </tr><tr>
      <td>audiosquare</td>
      <td><img src="src/lib/svg/linear/audiosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/audiosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/audiosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/audiosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/audiosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/audiosquare.svg" height="60px"></td>
    </tr><tr>
      <td>augur</td>
      <td><img src="src/lib/svg/linear/augur.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/augur.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/augur.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/augur.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/augur.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/augur.svg" height="60px"></td>
    </tr><tr>
      <td>autobrightness</td>
      <td><img src="src/lib/svg/linear/autobrightness.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/autobrightness.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/autobrightness.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/autobrightness.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/autobrightness.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/autobrightness.svg" height="60px"></td>
    </tr><tr>
      <td>autonio</td>
      <td><img src="src/lib/svg/linear/autonio.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/autonio.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/autonio.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/autonio.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/autonio.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/autonio.svg" height="60px"></td>
    </tr><tr>
      <td>avalanche</td>
      <td><img src="src/lib/svg/linear/avalanche.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/avalanche.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/avalanche.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/avalanche.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/avalanche.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/avalanche.svg" height="60px"></td>
    </tr><tr>
      <td>award</td>
      <td><img src="src/lib/svg/linear/award.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/award.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/award.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/award.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/award.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/award.svg" height="60px"></td>
    </tr><tr>
      <td>backsquare</td>
      <td><img src="src/lib/svg/linear/backsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backsquare.svg" height="60px"></td>
    </tr><tr>
      <td>backward10seconds</td>
      <td><img src="src/lib/svg/linear/backward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backward10seconds.svg" height="60px"></td>
    </tr><tr>
      <td>backward15seconds</td>
      <td><img src="src/lib/svg/linear/backward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backward15seconds.svg" height="60px"></td>
    </tr><tr>
      <td>backward5seconds</td>
      <td><img src="src/lib/svg/linear/backward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backward5seconds.svg" height="60px"></td>
    </tr><tr>
      <td>backwarditem</td>
      <td><img src="src/lib/svg/linear/backwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backwarditem.svg" height="60px"></td>
    </tr><tr>
      <td>backward</td>
      <td><img src="src/lib/svg/linear/backward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/backward.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/backward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/backward.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/backward.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/backward.svg" height="60px"></td>
    </tr><tr>
      <td>bag2</td>
      <td><img src="src/lib/svg/linear/bag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bag2.svg" height="60px"></td>
    </tr><tr>
      <td>bagcross1</td>
      <td><img src="src/lib/svg/linear/bagcross1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bagcross1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bagcross1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bagcross1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bagcross1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bagcross1.svg" height="60px"></td>
    </tr><tr>
      <td>bagcross</td>
      <td><img src="src/lib/svg/linear/bagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bagcross.svg" height="60px"></td>
    </tr><tr>
      <td>baghappy</td>
      <td><img src="src/lib/svg/linear/baghappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/baghappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/baghappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/baghappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/baghappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/baghappy.svg" height="60px"></td>
    </tr><tr>
      <td>bagtick2</td>
      <td><img src="src/lib/svg/linear/bagtick2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bagtick2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bagtick2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bagtick2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bagtick2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bagtick2.svg" height="60px"></td>
    </tr><tr>
      <td>bagtick</td>
      <td><img src="src/lib/svg/linear/bagtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bagtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bagtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bagtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bagtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bagtick.svg" height="60px"></td>
    </tr><tr>
      <td>bagtimer</td>
      <td><img src="src/lib/svg/linear/bagtimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bagtimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bagtimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bagtimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bagtimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bagtimer.svg" height="60px"></td>
    </tr><tr>
      <td>bag</td>
      <td><img src="src/lib/svg/linear/bag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bag.svg" height="60px"></td>
    </tr><tr>
      <td>bank</td>
      <td><img src="src/lib/svg/linear/bank.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bank.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bank.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bank.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bank.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bank.svg" height="60px"></td>
    </tr><tr>
      <td>barcode</td>
      <td><img src="src/lib/svg/linear/barcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/barcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/barcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/barcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/barcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/barcode.svg" height="60px"></td>
    </tr><tr>
      <td>battery3full</td>
      <td><img src="src/lib/svg/linear/battery3full.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/battery3full.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/battery3full.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/battery3full.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/battery3full.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/battery3full.svg" height="60px"></td>
    </tr><tr>
      <td>batterycharging</td>
      <td><img src="src/lib/svg/linear/batterycharging.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/batterycharging.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/batterycharging.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/batterycharging.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/batterycharging.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/batterycharging.svg" height="60px"></td>
    </tr><tr>
      <td>batterydisable</td>
      <td><img src="src/lib/svg/linear/batterydisable.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/batterydisable.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/batterydisable.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/batterydisable.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/batterydisable.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/batterydisable.svg" height="60px"></td>
    </tr><tr>
      <td>batteryempty1</td>
      <td><img src="src/lib/svg/linear/batteryempty1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/batteryempty1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/batteryempty1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/batteryempty1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/batteryempty1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/batteryempty1.svg" height="60px"></td>
    </tr><tr>
      <td>batteryempty</td>
      <td><img src="src/lib/svg/linear/batteryempty.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/batteryempty.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/batteryempty.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/batteryempty.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/batteryempty.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/batteryempty.svg" height="60px"></td>
    </tr><tr>
      <td>batteryfull</td>
      <td><img src="src/lib/svg/linear/batteryfull.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/batteryfull.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/batteryfull.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/batteryfull.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/batteryfull.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/batteryfull.svg" height="60px"></td>
    </tr><tr>
      <td>be</td>
      <td><img src="src/lib/svg/linear/be.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/be.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/be.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/be.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/be.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/be.svg" height="60px"></td>
    </tr><tr>
      <td>bezier</td>
      <td><img src="src/lib/svg/linear/bezier.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bezier.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bezier.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bezier.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bezier.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bezier.svg" height="60px"></td>
    </tr><tr>
      <td>bill</td>
      <td><img src="src/lib/svg/linear/bill.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bill.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bill.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bill.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bill.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bill.svg" height="60px"></td>
    </tr><tr>
      <td>binancecoin</td>
      <td><img src="src/lib/svg/linear/binancecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/binancecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/binancecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/binancecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/binancecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/binancecoin.svg" height="60px"></td>
    </tr><tr>
      <td>binanceusd</td>
      <td><img src="src/lib/svg/linear/binanceusd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/binanceusd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/binanceusd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/binanceusd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/binanceusd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/binanceusd.svg" height="60px"></td>
    </tr><tr>
      <td>bitcoin</td>
      <td><img src="src/lib/svg/linear/bitcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bitcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bitcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bitcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bitcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bitcoin.svg" height="60px"></td>
    </tr><tr>
      <td>bitcoincard</td>
      <td><img src="src/lib/svg/linear/bitcoincard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bitcoincard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bitcoincard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bitcoincard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bitcoincard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bitcoincard.svg" height="60px"></td>
    </tr><tr>
      <td>bitcoinconvert</td>
      <td><img src="src/lib/svg/linear/bitcoinconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bitcoinconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bitcoinconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bitcoinconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bitcoinconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bitcoinconvert.svg" height="60px"></td>
    </tr><tr>
      <td>bitcoinrefresh</td>
      <td><img src="src/lib/svg/linear/bitcoinrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bitcoinrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bitcoinrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bitcoinrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bitcoinrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bitcoinrefresh.svg" height="60px"></td>
    </tr><tr>
      <td>blend2</td>
      <td><img src="src/lib/svg/linear/blend2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/blend2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/blend2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/blend2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/blend2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/blend2.svg" height="60px"></td>
    </tr><tr>
      <td>blend</td>
      <td><img src="src/lib/svg/linear/blend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/blend.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/blend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/blend.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/blend.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/blend.svg" height="60px"></td>
    </tr><tr>
      <td>blogger</td>
      <td><img src="src/lib/svg/linear/blogger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/blogger.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/blogger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/blogger.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/blogger.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/blogger.svg" height="60px"></td>
    </tr><tr>
      <td>bluetooth2</td>
      <td><img src="src/lib/svg/linear/bluetooth2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bluetooth2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bluetooth2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bluetooth2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bluetooth2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bluetooth2.svg" height="60px"></td>
    </tr><tr>
      <td>bluetoothcircle</td>
      <td><img src="src/lib/svg/linear/bluetoothcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bluetoothcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bluetoothcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bluetoothcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bluetoothcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bluetoothcircle.svg" height="60px"></td>
    </tr><tr>
      <td>bluetoothrectangle</td>
      <td><img src="src/lib/svg/linear/bluetoothrectangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bluetoothrectangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bluetoothrectangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bluetoothrectangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bluetoothrectangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bluetoothrectangle.svg" height="60px"></td>
    </tr><tr>
      <td>bluetooth</td>
      <td><img src="src/lib/svg/linear/bluetooth.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bluetooth.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bluetooth.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bluetooth.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bluetooth.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bluetooth.svg" height="60px"></td>
    </tr><tr>
      <td>blur</td>
      <td><img src="src/lib/svg/linear/blur.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/blur.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/blur.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/blur.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/blur.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/blur.svg" height="60px"></td>
    </tr><tr>
      <td>book1</td>
      <td><img src="src/lib/svg/linear/book1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/book1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/book1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/book1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/book1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/book1.svg" height="60px"></td>
    </tr><tr>
      <td>booksaved</td>
      <td><img src="src/lib/svg/linear/booksaved.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/booksaved.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/booksaved.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/booksaved.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/booksaved.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/booksaved.svg" height="60px"></td>
    </tr><tr>
      <td>booksquare</td>
      <td><img src="src/lib/svg/linear/booksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/booksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/booksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/booksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/booksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/booksquare.svg" height="60px"></td>
    </tr><tr>
      <td>book</td>
      <td><img src="src/lib/svg/linear/book.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/book.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/book.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/book.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/book.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/book.svg" height="60px"></td>
    </tr><tr>
      <td>bookmark2</td>
      <td><img src="src/lib/svg/linear/bookmark2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bookmark2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bookmark2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bookmark2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bookmark2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bookmark2.svg" height="60px"></td>
    </tr><tr>
      <td>bookmark</td>
      <td><img src="src/lib/svg/linear/bookmark.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bookmark.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bookmark.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bookmark.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bookmark.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bookmark.svg" height="60px"></td>
    </tr><tr>
      <td>bootstrap</td>
      <td><img src="src/lib/svg/linear/bootstrap.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bootstrap.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bootstrap.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bootstrap.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bootstrap.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bootstrap.svg" height="60px"></td>
    </tr><tr>
      <td>box1</td>
      <td><img src="src/lib/svg/linear/box1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/box1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/box1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/box1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/box1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/box1.svg" height="60px"></td>
    </tr><tr>
      <td>box2</td>
      <td><img src="src/lib/svg/linear/box2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/box2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/box2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/box2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/box2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/box2.svg" height="60px"></td>
    </tr><tr>
      <td>boxadd</td>
      <td><img src="src/lib/svg/linear/boxadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/boxadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/boxadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/boxadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/boxadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/boxadd.svg" height="60px"></td>
    </tr><tr>
      <td>boxremove</td>
      <td><img src="src/lib/svg/linear/boxremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/boxremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/boxremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/boxremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/boxremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/boxremove.svg" height="60px"></td>
    </tr><tr>
      <td>boxsearch</td>
      <td><img src="src/lib/svg/linear/boxsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/boxsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/boxsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/boxsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/boxsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/boxsearch.svg" height="60px"></td>
    </tr><tr>
      <td>boxtick</td>
      <td><img src="src/lib/svg/linear/boxtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/boxtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/boxtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/boxtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/boxtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/boxtick.svg" height="60px"></td>
    </tr><tr>
      <td>boxtime</td>
      <td><img src="src/lib/svg/linear/boxtime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/boxtime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/boxtime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/boxtime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/boxtime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/boxtime.svg" height="60px"></td>
    </tr><tr>
      <td>box</td>
      <td><img src="src/lib/svg/linear/box.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/box.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/box.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/box.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/box.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/box.svg" height="60px"></td>
    </tr><tr>
      <td>briefcase</td>
      <td><img src="src/lib/svg/linear/briefcase.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/briefcase.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/briefcase.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/briefcase.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/briefcase.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/briefcase.svg" height="60px"></td>
    </tr><tr>
      <td>brifecasecross</td>
      <td><img src="src/lib/svg/linear/brifecasecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brifecasecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brifecasecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brifecasecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brifecasecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brifecasecross.svg" height="60px"></td>
    </tr><tr>
      <td>brifecasetick</td>
      <td><img src="src/lib/svg/linear/brifecasetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brifecasetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brifecasetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brifecasetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brifecasetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brifecasetick.svg" height="60px"></td>
    </tr><tr>
      <td>brifecasetimer</td>
      <td><img src="src/lib/svg/linear/brifecasetimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brifecasetimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brifecasetimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brifecasetimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brifecasetimer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brifecasetimer.svg" height="60px"></td>
    </tr><tr>
      <td>broom</td>
      <td><img src="src/lib/svg/linear/broom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/broom.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/broom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/broom.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/broom.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/broom.svg" height="60px"></td>
    </tr><tr>
      <td>brush1</td>
      <td><img src="src/lib/svg/linear/brush1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brush1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brush1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brush1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brush1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brush1.svg" height="60px"></td>
    </tr><tr>
      <td>brush2</td>
      <td><img src="src/lib/svg/linear/brush2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brush2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brush2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brush2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brush2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brush2.svg" height="60px"></td>
    </tr><tr>
      <td>brush3</td>
      <td><img src="src/lib/svg/linear/brush3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brush3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brush3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brush3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brush3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brush3.svg" height="60px"></td>
    </tr><tr>
      <td>brush4</td>
      <td><img src="src/lib/svg/linear/brush4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brush4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brush4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brush4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brush4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brush4.svg" height="60px"></td>
    </tr><tr>
      <td>brush</td>
      <td><img src="src/lib/svg/linear/brush.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/brush.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/brush.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/brush.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/brush.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/brush.svg" height="60px"></td>
    </tr><tr>
      <td>bubble</td>
      <td><img src="src/lib/svg/linear/bubble.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bubble.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bubble.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bubble.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bubble.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bubble.svg" height="60px"></td>
    </tr><tr>
      <td>bucketcircle</td>
      <td><img src="src/lib/svg/linear/bucketcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bucketcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bucketcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bucketcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bucketcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bucketcircle.svg" height="60px"></td>
    </tr><tr>
      <td>bucketsquare</td>
      <td><img src="src/lib/svg/linear/bucketsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bucketsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bucketsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bucketsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bucketsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bucketsquare.svg" height="60px"></td>
    </tr><tr>
      <td>bucket</td>
      <td><img src="src/lib/svg/linear/bucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bucket.svg" height="60px"></td>
    </tr><tr>
      <td>building3</td>
      <td><img src="src/lib/svg/linear/building3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/building3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/building3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/building3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/building3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/building3.svg" height="60px"></td>
    </tr><tr>
      <td>building4</td>
      <td><img src="src/lib/svg/linear/building4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/building4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/building4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/building4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/building4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/building4.svg" height="60px"></td>
    </tr><tr>
      <td>building</td>
      <td><img src="src/lib/svg/linear/building.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/building.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/building.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/building.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/building.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/building.svg" height="60px"></td>
    </tr><tr>
      <td>buildings2</td>
      <td><img src="src/lib/svg/linear/buildings2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/buildings2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/buildings2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/buildings2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/buildings2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/buildings2.svg" height="60px"></td>
    </tr><tr>
      <td>buildings</td>
      <td><img src="src/lib/svg/linear/buildings.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/buildings.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/buildings.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/buildings.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/buildings.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/buildings.svg" height="60px"></td>
    </tr><tr>
      <td>buliding</td>
      <td><img src="src/lib/svg/linear/buliding.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/buliding.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/buliding.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/buliding.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/buliding.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/buliding.svg" height="60px"></td>
    </tr><tr>
      <td>bus</td>
      <td><img src="src/lib/svg/linear/bus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/bus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/bus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/bus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/bus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/bus.svg" height="60px"></td>
    </tr><tr>
      <td>buycrypto</td>
      <td><img src="src/lib/svg/linear/buycrypto.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/buycrypto.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/buycrypto.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/buycrypto.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/buycrypto.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/buycrypto.svg" height="60px"></td>
    </tr><tr>
      <td>cake</td>
      <td><img src="src/lib/svg/linear/cake.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cake.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cake.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cake.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cake.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cake.svg" height="60px"></td>
    </tr><tr>
      <td>calculator</td>
      <td><img src="src/lib/svg/linear/calculator.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calculator.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calculator.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calculator.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calculator.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calculator.svg" height="60px"></td>
    </tr><tr>
      <td>calendar1</td>
      <td><img src="src/lib/svg/linear/calendar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendar1.svg" height="60px"></td>
    </tr><tr>
      <td>calendar2</td>
      <td><img src="src/lib/svg/linear/calendar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendar2.svg" height="60px"></td>
    </tr><tr>
      <td>calendaradd</td>
      <td><img src="src/lib/svg/linear/calendaradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendaradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendaradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendaradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendaradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendaradd.svg" height="60px"></td>
    </tr><tr>
      <td>calendarcircle</td>
      <td><img src="src/lib/svg/linear/calendarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendarcircle.svg" height="60px"></td>
    </tr><tr>
      <td>calendaredit</td>
      <td><img src="src/lib/svg/linear/calendaredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendaredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendaredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendaredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendaredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendaredit.svg" height="60px"></td>
    </tr><tr>
      <td>calendarremove</td>
      <td><img src="src/lib/svg/linear/calendarremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendarremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendarremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendarremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendarremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendarremove.svg" height="60px"></td>
    </tr><tr>
      <td>calendarsearch</td>
      <td><img src="src/lib/svg/linear/calendarsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendarsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendarsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendarsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendarsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendarsearch.svg" height="60px"></td>
    </tr><tr>
      <td>calendartick</td>
      <td><img src="src/lib/svg/linear/calendartick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendartick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendartick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendartick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendartick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendartick.svg" height="60px"></td>
    </tr><tr>
      <td>calendar</td>
      <td><img src="src/lib/svg/linear/calendar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calendar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calendar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calendar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calendar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calendar.svg" height="60px"></td>
    </tr><tr>
      <td>calladd</td>
      <td><img src="src/lib/svg/linear/calladd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calladd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calladd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calladd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calladd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calladd.svg" height="60px"></td>
    </tr><tr>
      <td>callcalling</td>
      <td><img src="src/lib/svg/linear/callcalling.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callcalling.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callcalling.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callcalling.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callcalling.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callcalling.svg" height="60px"></td>
    </tr><tr>
      <td>callincoming</td>
      <td><img src="src/lib/svg/linear/callincoming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callincoming.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callincoming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callincoming.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callincoming.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callincoming.svg" height="60px"></td>
    </tr><tr>
      <td>callminus</td>
      <td><img src="src/lib/svg/linear/callminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callminus.svg" height="60px"></td>
    </tr><tr>
      <td>calloutgoing</td>
      <td><img src="src/lib/svg/linear/calloutgoing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/calloutgoing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/calloutgoing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/calloutgoing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/calloutgoing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/calloutgoing.svg" height="60px"></td>
    </tr><tr>
      <td>callreceived</td>
      <td><img src="src/lib/svg/linear/callreceived.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callreceived.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callreceived.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callreceived.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callreceived.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callreceived.svg" height="60px"></td>
    </tr><tr>
      <td>callremove</td>
      <td><img src="src/lib/svg/linear/callremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callremove.svg" height="60px"></td>
    </tr><tr>
      <td>callslash</td>
      <td><img src="src/lib/svg/linear/callslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/callslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/callslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/callslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/callslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/callslash.svg" height="60px"></td>
    </tr><tr>
      <td>call</td>
      <td><img src="src/lib/svg/linear/call.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/call.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/call.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/call.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/call.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/call.svg" height="60px"></td>
    </tr><tr>
      <td>cameraslash</td>
      <td><img src="src/lib/svg/linear/cameraslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cameraslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cameraslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cameraslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cameraslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cameraslash.svg" height="60px"></td>
    </tr><tr>
      <td>camera</td>
      <td><img src="src/lib/svg/linear/camera.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/camera.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/camera.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/camera.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/camera.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/camera.svg" height="60px"></td>
    </tr><tr>
      <td>candle2</td>
      <td><img src="src/lib/svg/linear/candle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/candle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/candle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/candle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/candle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/candle2.svg" height="60px"></td>
    </tr><tr>
      <td>candle</td>
      <td><img src="src/lib/svg/linear/candle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/candle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/candle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/candle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/candle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/candle.svg" height="60px"></td>
    </tr><tr>
      <td>car</td>
      <td><img src="src/lib/svg/linear/car.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/car.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/car.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/car.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/car.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/car.svg" height="60px"></td>
    </tr><tr>
      <td>cardadd</td>
      <td><img src="src/lib/svg/linear/cardadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardadd.svg" height="60px"></td>
    </tr><tr>
      <td>cardcoin</td>
      <td><img src="src/lib/svg/linear/cardcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardcoin.svg" height="60px"></td>
    </tr><tr>
      <td>cardedit</td>
      <td><img src="src/lib/svg/linear/cardedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardedit.svg" height="60px"></td>
    </tr><tr>
      <td>cardpos</td>
      <td><img src="src/lib/svg/linear/cardpos.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardpos.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardpos.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardpos.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardpos.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardpos.svg" height="60px"></td>
    </tr><tr>
      <td>cardreceive</td>
      <td><img src="src/lib/svg/linear/cardreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardreceive.svg" height="60px"></td>
    </tr><tr>
      <td>cardremove1</td>
      <td><img src="src/lib/svg/linear/cardremove1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardremove1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardremove1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardremove1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardremove1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardremove1.svg" height="60px"></td>
    </tr><tr>
      <td>cardremove</td>
      <td><img src="src/lib/svg/linear/cardremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardremove.svg" height="60px"></td>
    </tr><tr>
      <td>cardsend</td>
      <td><img src="src/lib/svg/linear/cardsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardsend.svg" height="60px"></td>
    </tr><tr>
      <td>cardslash</td>
      <td><img src="src/lib/svg/linear/cardslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardslash.svg" height="60px"></td>
    </tr><tr>
      <td>cardtick1</td>
      <td><img src="src/lib/svg/linear/cardtick1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardtick1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardtick1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardtick1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardtick1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardtick1.svg" height="60px"></td>
    </tr><tr>
      <td>cardtick</td>
      <td><img src="src/lib/svg/linear/cardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardtick.svg" height="60px"></td>
    </tr><tr>
      <td>card</td>
      <td><img src="src/lib/svg/linear/card.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/card.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/card.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/card.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/card.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/card.svg" height="60px"></td>
    </tr><tr>
      <td>cardano</td>
      <td><img src="src/lib/svg/linear/cardano.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cardano.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cardano.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cardano.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cardano.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cardano.svg" height="60px"></td>
    </tr><tr>
      <td>cards</td>
      <td><img src="src/lib/svg/linear/cards.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cards.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cards.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cards.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cards.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cards.svg" height="60px"></td>
    </tr><tr>
      <td>category2</td>
      <td><img src="src/lib/svg/linear/category2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/category2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/category2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/category2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/category2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/category2.svg" height="60px"></td>
    </tr><tr>
      <td>category</td>
      <td><img src="src/lib/svg/linear/category.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/category.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/category.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/category.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/category.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/category.svg" height="60px"></td>
    </tr><tr>
      <td>cd</td>
      <td><img src="src/lib/svg/linear/cd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cd.svg" height="60px"></td>
    </tr><tr>
      <td>celo</td>
      <td><img src="src/lib/svg/linear/celo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/celo.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/celo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/celo.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/celo.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/celo.svg" height="60px"></td>
    </tr><tr>
      <td>celsius</td>
      <td><img src="src/lib/svg/linear/celsius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/celsius.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/celsius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/celsius.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/celsius.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/celsius.svg" height="60px"></td>
    </tr><tr>
      <td>chainlink</td>
      <td><img src="src/lib/svg/linear/chainlink.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chainlink.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chainlink.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chainlink.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chainlink.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chainlink.svg" height="60px"></td>
    </tr><tr>
      <td>chart1</td>
      <td><img src="src/lib/svg/linear/chart1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chart1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chart1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chart1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chart1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chart1.svg" height="60px"></td>
    </tr><tr>
      <td>chart2</td>
      <td><img src="src/lib/svg/linear/chart2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chart2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chart2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chart2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chart2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chart2.svg" height="60px"></td>
    </tr><tr>
      <td>chart21</td>
      <td><img src="src/lib/svg/linear/chart21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chart21.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chart21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chart21.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chart21.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chart21.svg" height="60px"></td>
    </tr><tr>
      <td>chart3</td>
      <td><img src="src/lib/svg/linear/chart3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chart3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chart3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chart3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chart3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chart3.svg" height="60px"></td>
    </tr><tr>
      <td>chartfail</td>
      <td><img src="src/lib/svg/linear/chartfail.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chartfail.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chartfail.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chartfail.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chartfail.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chartfail.svg" height="60px"></td>
    </tr><tr>
      <td>chartsquare</td>
      <td><img src="src/lib/svg/linear/chartsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chartsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chartsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chartsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chartsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chartsquare.svg" height="60px"></td>
    </tr><tr>
      <td>chartsuccess</td>
      <td><img src="src/lib/svg/linear/chartsuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chartsuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chartsuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chartsuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chartsuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chartsuccess.svg" height="60px"></td>
    </tr><tr>
      <td>chart</td>
      <td><img src="src/lib/svg/linear/chart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chart.svg" height="60px"></td>
    </tr><tr>
      <td>check</td>
      <td><img src="src/lib/svg/linear/check.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/check.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/check.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/check.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/check.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/check.svg" height="60px"></td>
    </tr><tr>
      <td>chrome</td>
      <td><img src="src/lib/svg/linear/chrome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/chrome.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/chrome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/chrome.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/chrome.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/chrome.svg" height="60px"></td>
    </tr><tr>
      <td>civic</td>
      <td><img src="src/lib/svg/linear/civic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/civic.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/civic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/civic.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/civic.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/civic.svg" height="60px"></td>
    </tr><tr>
      <td>clipboardclose</td>
      <td><img src="src/lib/svg/linear/clipboardclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboardclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboardclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboardclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboardclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboardclose.svg" height="60px"></td>
    </tr><tr>
      <td>clipboardexport</td>
      <td><img src="src/lib/svg/linear/clipboardexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboardexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboardexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboardexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboardexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboardexport.svg" height="60px"></td>
    </tr><tr>
      <td>clipboardimport</td>
      <td><img src="src/lib/svg/linear/clipboardimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboardimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboardimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboardimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboardimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboardimport.svg" height="60px"></td>
    </tr><tr>
      <td>clipboardtext</td>
      <td><img src="src/lib/svg/linear/clipboardtext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboardtext.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboardtext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboardtext.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboardtext.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboardtext.svg" height="60px"></td>
    </tr><tr>
      <td>clipboardtick</td>
      <td><img src="src/lib/svg/linear/clipboardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboardtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboardtick.svg" height="60px"></td>
    </tr><tr>
      <td>clipboard</td>
      <td><img src="src/lib/svg/linear/clipboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clipboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clipboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clipboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clipboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clipboard.svg" height="60px"></td>
    </tr><tr>
      <td>clock1</td>
      <td><img src="src/lib/svg/linear/clock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clock1.svg" height="60px"></td>
    </tr><tr>
      <td>clock</td>
      <td><img src="src/lib/svg/linear/clock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clock.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clock.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clock.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clock.svg" height="60px"></td>
    </tr><tr>
      <td>closecircle</td>
      <td><img src="src/lib/svg/linear/closecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/closecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/closecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/closecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/closecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/closecircle.svg" height="60px"></td>
    </tr><tr>
      <td>closesquare</td>
      <td><img src="src/lib/svg/linear/closesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/closesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/closesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/closesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/closesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/closesquare.svg" height="60px"></td>
    </tr><tr>
      <td>cloudadd</td>
      <td><img src="src/lib/svg/linear/cloudadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudadd.svg" height="60px"></td>
    </tr><tr>
      <td>cloudchange</td>
      <td><img src="src/lib/svg/linear/cloudchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudchange.svg" height="60px"></td>
    </tr><tr>
      <td>cloudconnection</td>
      <td><img src="src/lib/svg/linear/cloudconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudconnection.svg" height="60px"></td>
    </tr><tr>
      <td>cloudcross</td>
      <td><img src="src/lib/svg/linear/cloudcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudcross.svg" height="60px"></td>
    </tr><tr>
      <td>clouddrizzle</td>
      <td><img src="src/lib/svg/linear/clouddrizzle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/clouddrizzle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/clouddrizzle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/clouddrizzle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/clouddrizzle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/clouddrizzle.svg" height="60px"></td>
    </tr><tr>
      <td>cloudfog</td>
      <td><img src="src/lib/svg/linear/cloudfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudfog.svg" height="60px"></td>
    </tr><tr>
      <td>cloudlightning</td>
      <td><img src="src/lib/svg/linear/cloudlightning.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudlightning.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudlightning.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudlightning.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudlightning.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudlightning.svg" height="60px"></td>
    </tr><tr>
      <td>cloudminus</td>
      <td><img src="src/lib/svg/linear/cloudminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudminus.svg" height="60px"></td>
    </tr><tr>
      <td>cloudnotif</td>
      <td><img src="src/lib/svg/linear/cloudnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudnotif.svg" height="60px"></td>
    </tr><tr>
      <td>cloudplus</td>
      <td><img src="src/lib/svg/linear/cloudplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudplus.svg" height="60px"></td>
    </tr><tr>
      <td>cloudremove</td>
      <td><img src="src/lib/svg/linear/cloudremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudremove.svg" height="60px"></td>
    </tr><tr>
      <td>cloudsnow</td>
      <td><img src="src/lib/svg/linear/cloudsnow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudsnow.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudsnow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudsnow.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudsnow.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudsnow.svg" height="60px"></td>
    </tr><tr>
      <td>cloudsunny</td>
      <td><img src="src/lib/svg/linear/cloudsunny.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloudsunny.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloudsunny.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloudsunny.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloudsunny.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloudsunny.svg" height="60px"></td>
    </tr><tr>
      <td>cloud</td>
      <td><img src="src/lib/svg/linear/cloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cloud.svg" height="60px"></td>
    </tr><tr>
      <td>code1</td>
      <td><img src="src/lib/svg/linear/code1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/code1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/code1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/code1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/code1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/code1.svg" height="60px"></td>
    </tr><tr>
      <td>codecircle</td>
      <td><img src="src/lib/svg/linear/codecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/codecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/codecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/codecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/codecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/codecircle.svg" height="60px"></td>
    </tr><tr>
      <td>code</td>
      <td><img src="src/lib/svg/linear/code.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/code.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/code.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/code.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/code.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/code.svg" height="60px"></td>
    </tr><tr>
      <td>coffee</td>
      <td><img src="src/lib/svg/linear/coffee.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/coffee.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/coffee.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/coffee.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/coffee.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/coffee.svg" height="60px"></td>
    </tr><tr>
      <td>coin1</td>
      <td><img src="src/lib/svg/linear/coin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/coin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/coin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/coin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/coin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/coin1.svg" height="60px"></td>
    </tr><tr>
      <td>coin</td>
      <td><img src="src/lib/svg/linear/coin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/coin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/coin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/coin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/coin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/coin.svg" height="60px"></td>
    </tr><tr>
      <td>colorswatch</td>
      <td><img src="src/lib/svg/linear/colorswatch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/colorswatch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/colorswatch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/colorswatch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/colorswatch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/colorswatch.svg" height="60px"></td>
    </tr><tr>
      <td>colorfilter</td>
      <td><img src="src/lib/svg/linear/colorfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/colorfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/colorfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/colorfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/colorfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/colorfilter.svg" height="60px"></td>
    </tr><tr>
      <td>colorssquare</td>
      <td><img src="src/lib/svg/linear/colorssquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/colorssquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/colorssquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/colorssquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/colorssquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/colorssquare.svg" height="60px"></td>
    </tr><tr>
      <td>commandsquare</td>
      <td><img src="src/lib/svg/linear/commandsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/commandsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/commandsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/commandsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/commandsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/commandsquare.svg" height="60px"></td>
    </tr><tr>
      <td>command</td>
      <td><img src="src/lib/svg/linear/command.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/command.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/command.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/command.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/command.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/command.svg" height="60px"></td>
    </tr><tr>
      <td>component</td>
      <td><img src="src/lib/svg/linear/component.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/component.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/component.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/component.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/component.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/component.svg" height="60px"></td>
    </tr><tr>
      <td>computing</td>
      <td><img src="src/lib/svg/linear/computing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/computing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/computing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/computing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/computing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/computing.svg" height="60px"></td>
    </tr><tr>
      <td>convert3dcube</td>
      <td><img src="src/lib/svg/linear/convert3dcube.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/convert3dcube.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/convert3dcube.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/convert3dcube.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/convert3dcube.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/convert3dcube.svg" height="60px"></td>
    </tr><tr>
      <td>convertcard</td>
      <td><img src="src/lib/svg/linear/convertcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/convertcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/convertcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/convertcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/convertcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/convertcard.svg" height="60px"></td>
    </tr><tr>
      <td>convert</td>
      <td><img src="src/lib/svg/linear/convert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/convert.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/convert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/convert.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/convert.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/convert.svg" height="60px"></td>
    </tr><tr>
      <td>convertshape2</td>
      <td><img src="src/lib/svg/linear/convertshape2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/convertshape2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/convertshape2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/convertshape2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/convertshape2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/convertshape2.svg" height="60px"></td>
    </tr><tr>
      <td>convertshape</td>
      <td><img src="src/lib/svg/linear/convertshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/convertshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/convertshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/convertshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/convertshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/convertshape.svg" height="60px"></td>
    </tr><tr>
      <td>copysuccess</td>
      <td><img src="src/lib/svg/linear/copysuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/copysuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/copysuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/copysuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/copysuccess.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/copysuccess.svg" height="60px"></td>
    </tr><tr>
      <td>copy</td>
      <td><img src="src/lib/svg/linear/copy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/copy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/copy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/copy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/copy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/copy.svg" height="60px"></td>
    </tr><tr>
      <td>copyright</td>
      <td><img src="src/lib/svg/linear/copyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/copyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/copyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/copyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/copyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/copyright.svg" height="60px"></td>
    </tr><tr>
      <td>courthouse</td>
      <td><img src="src/lib/svg/linear/courthouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/courthouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/courthouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/courthouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/courthouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/courthouse.svg" height="60px"></td>
    </tr><tr>
      <td>cpucharge</td>
      <td><img src="src/lib/svg/linear/cpucharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cpucharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cpucharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cpucharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cpucharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cpucharge.svg" height="60px"></td>
    </tr><tr>
      <td>cpusetting</td>
      <td><img src="src/lib/svg/linear/cpusetting.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cpusetting.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cpusetting.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cpusetting.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cpusetting.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cpusetting.svg" height="60px"></td>
    </tr><tr>
      <td>cpu</td>
      <td><img src="src/lib/svg/linear/cpu.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cpu.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cpu.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cpu.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cpu.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cpu.svg" height="60px"></td>
    </tr><tr>
      <td>creativecommons</td>
      <td><img src="src/lib/svg/linear/creativecommons.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/creativecommons.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/creativecommons.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/creativecommons.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/creativecommons.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/creativecommons.svg" height="60px"></td>
    </tr><tr>
      <td>crop</td>
      <td><img src="src/lib/svg/linear/crop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/crop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/crop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/crop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/crop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/crop.svg" height="60px"></td>
    </tr><tr>
      <td>crown1</td>
      <td><img src="src/lib/svg/linear/crown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/crown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/crown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/crown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/crown1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/crown1.svg" height="60px"></td>
    </tr><tr>
      <td>crown</td>
      <td><img src="src/lib/svg/linear/crown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/crown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/crown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/crown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/crown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/crown.svg" height="60px"></td>
    </tr><tr>
      <td>css3</td>
      <td><img src="src/lib/svg/linear/css3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/css3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/css3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/css3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/css3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/css3.svg" height="60px"></td>
    </tr><tr>
      <td>cubescan3d</td>
      <td><img src="src/lib/svg/linear/cubescan3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cubescan3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cubescan3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cubescan3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cubescan3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cubescan3d.svg" height="60px"></td>
    </tr><tr>
      <td>cube3d</td>
      <td><img src="src/lib/svg/linear/cube3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cube3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cube3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cube3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cube3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cube3d.svg" height="60px"></td>
    </tr><tr>
      <td>cup</td>
      <td><img src="src/lib/svg/linear/cup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/cup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/cup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/cup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/cup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/cup.svg" height="60px"></td>
    </tr><tr>
      <td>dai</td>
      <td><img src="src/lib/svg/linear/dai.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dai.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dai.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dai.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dai.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dai.svg" height="60px"></td>
    </tr><tr>
      <td>danger</td>
      <td><img src="src/lib/svg/linear/danger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/danger.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/danger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/danger.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/danger.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/danger.svg" height="60px"></td>
    </tr><tr>
      <td>dash</td>
      <td><img src="src/lib/svg/linear/dash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dash.svg" height="60px"></td>
    </tr><tr>
      <td>data2</td>
      <td><img src="src/lib/svg/linear/data2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/data2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/data2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/data2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/data2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/data2.svg" height="60px"></td>
    </tr><tr>
      <td>data</td>
      <td><img src="src/lib/svg/linear/data.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/data.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/data.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/data.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/data.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/data.svg" height="60px"></td>
    </tr><tr>
      <td>decred</td>
      <td><img src="src/lib/svg/linear/decred.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/decred.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/decred.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/decred.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/decred.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/decred.svg" height="60px"></td>
    </tr><tr>
      <td>dent</td>
      <td><img src="src/lib/svg/linear/dent.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dent.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dent.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dent.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dent.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dent.svg" height="60px"></td>
    </tr><tr>
      <td>designtools</td>
      <td><img src="src/lib/svg/linear/designtools.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/designtools.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/designtools.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/designtools.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/designtools.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/designtools.svg" height="60px"></td>
    </tr><tr>
      <td>devicemessage</td>
      <td><img src="src/lib/svg/linear/devicemessage.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/devicemessage.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/devicemessage.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/devicemessage.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/devicemessage.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/devicemessage.svg" height="60px"></td>
    </tr><tr>
      <td>devices</td>
      <td><img src="src/lib/svg/linear/devices.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/devices.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/devices.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/devices.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/devices.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/devices.svg" height="60px"></td>
    </tr><tr>
      <td>diagram</td>
      <td><img src="src/lib/svg/linear/diagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/diagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/diagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/diagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/diagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/diagram.svg" height="60px"></td>
    </tr><tr>
      <td>diamonds</td>
      <td><img src="src/lib/svg/linear/diamonds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/diamonds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/diamonds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/diamonds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/diamonds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/diamonds.svg" height="60px"></td>
    </tr><tr>
      <td>directdown</td>
      <td><img src="src/lib/svg/linear/directdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directdown.svg" height="60px"></td>
    </tr><tr>
      <td>directinbox</td>
      <td><img src="src/lib/svg/linear/directinbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directinbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directinbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directinbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directinbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directinbox.svg" height="60px"></td>
    </tr><tr>
      <td>directleft</td>
      <td><img src="src/lib/svg/linear/directleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directleft.svg" height="60px"></td>
    </tr><tr>
      <td>directnormal</td>
      <td><img src="src/lib/svg/linear/directnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directnormal.svg" height="60px"></td>
    </tr><tr>
      <td>directnotification</td>
      <td><img src="src/lib/svg/linear/directnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directnotification.svg" height="60px"></td>
    </tr><tr>
      <td>directright</td>
      <td><img src="src/lib/svg/linear/directright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directright.svg" height="60px"></td>
    </tr><tr>
      <td>directsend</td>
      <td><img src="src/lib/svg/linear/directsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directsend.svg" height="60px"></td>
    </tr><tr>
      <td>directup</td>
      <td><img src="src/lib/svg/linear/directup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directup.svg" height="60px"></td>
    </tr><tr>
      <td>direct</td>
      <td><img src="src/lib/svg/linear/direct.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/direct.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/direct.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/direct.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/direct.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/direct.svg" height="60px"></td>
    </tr><tr>
      <td>directboxdefault</td>
      <td><img src="src/lib/svg/linear/directboxdefault.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directboxdefault.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directboxdefault.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directboxdefault.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directboxdefault.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directboxdefault.svg" height="60px"></td>
    </tr><tr>
      <td>directboxnotif</td>
      <td><img src="src/lib/svg/linear/directboxnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directboxnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directboxnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directboxnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directboxnotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directboxnotif.svg" height="60px"></td>
    </tr><tr>
      <td>directboxreceive</td>
      <td><img src="src/lib/svg/linear/directboxreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directboxreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directboxreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directboxreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directboxreceive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directboxreceive.svg" height="60px"></td>
    </tr><tr>
      <td>directboxsend</td>
      <td><img src="src/lib/svg/linear/directboxsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/directboxsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/directboxsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/directboxsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/directboxsend.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/directboxsend.svg" height="60px"></td>
    </tr><tr>
      <td>discountcircle</td>
      <td><img src="src/lib/svg/linear/discountcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/discountcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/discountcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/discountcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/discountcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/discountcircle.svg" height="60px"></td>
    </tr><tr>
      <td>discountshape</td>
      <td><img src="src/lib/svg/linear/discountshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/discountshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/discountshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/discountshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/discountshape.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/discountshape.svg" height="60px"></td>
    </tr><tr>
      <td>discover1</td>
      <td><img src="src/lib/svg/linear/discover1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/discover1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/discover1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/discover1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/discover1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/discover1.svg" height="60px"></td>
    </tr><tr>
      <td>discover</td>
      <td><img src="src/lib/svg/linear/discover.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/discover.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/discover.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/discover.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/discover.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/discover.svg" height="60px"></td>
    </tr><tr>
      <td>dislike</td>
      <td><img src="src/lib/svg/linear/dislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dislike.svg" height="60px"></td>
    </tr><tr>
      <td>document1</td>
      <td><img src="src/lib/svg/linear/document1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/document1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/document1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/document1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/document1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/document1.svg" height="60px"></td>
    </tr><tr>
      <td>documentcloud</td>
      <td><img src="src/lib/svg/linear/documentcloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentcloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentcloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentcloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentcloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentcloud.svg" height="60px"></td>
    </tr><tr>
      <td>documentcode2</td>
      <td><img src="src/lib/svg/linear/documentcode2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentcode2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentcode2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentcode2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentcode2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentcode2.svg" height="60px"></td>
    </tr><tr>
      <td>documentcode</td>
      <td><img src="src/lib/svg/linear/documentcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentcode.svg" height="60px"></td>
    </tr><tr>
      <td>documentcopy</td>
      <td><img src="src/lib/svg/linear/documentcopy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentcopy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentcopy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentcopy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentcopy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentcopy.svg" height="60px"></td>
    </tr><tr>
      <td>documentdownload</td>
      <td><img src="src/lib/svg/linear/documentdownload.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentdownload.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentdownload.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentdownload.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentdownload.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentdownload.svg" height="60px"></td>
    </tr><tr>
      <td>documentfavorite</td>
      <td><img src="src/lib/svg/linear/documentfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentfavorite.svg" height="60px"></td>
    </tr><tr>
      <td>documentfilter</td>
      <td><img src="src/lib/svg/linear/documentfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentfilter.svg" height="60px"></td>
    </tr><tr>
      <td>documentforward</td>
      <td><img src="src/lib/svg/linear/documentforward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentforward.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentforward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentforward.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentforward.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentforward.svg" height="60px"></td>
    </tr><tr>
      <td>documentlike</td>
      <td><img src="src/lib/svg/linear/documentlike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentlike.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentlike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentlike.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentlike.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentlike.svg" height="60px"></td>
    </tr><tr>
      <td>documentnormal</td>
      <td><img src="src/lib/svg/linear/documentnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentnormal.svg" height="60px"></td>
    </tr><tr>
      <td>documentprevious</td>
      <td><img src="src/lib/svg/linear/documentprevious.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentprevious.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentprevious.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentprevious.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentprevious.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentprevious.svg" height="60px"></td>
    </tr><tr>
      <td>documentsketch</td>
      <td><img src="src/lib/svg/linear/documentsketch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentsketch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentsketch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentsketch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentsketch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentsketch.svg" height="60px"></td>
    </tr><tr>
      <td>documenttext1</td>
      <td><img src="src/lib/svg/linear/documenttext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documenttext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documenttext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documenttext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documenttext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documenttext1.svg" height="60px"></td>
    </tr><tr>
      <td>documenttext</td>
      <td><img src="src/lib/svg/linear/documenttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documenttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documenttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documenttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documenttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documenttext.svg" height="60px"></td>
    </tr><tr>
      <td>documentupload</td>
      <td><img src="src/lib/svg/linear/documentupload.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/documentupload.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/documentupload.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/documentupload.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/documentupload.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/documentupload.svg" height="60px"></td>
    </tr><tr>
      <td>document</td>
      <td><img src="src/lib/svg/linear/document.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/document.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/document.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/document.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/document.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/document.svg" height="60px"></td>
    </tr><tr>
      <td>dollarcircle</td>
      <td><img src="src/lib/svg/linear/dollarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dollarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dollarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dollarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dollarcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dollarcircle.svg" height="60px"></td>
    </tr><tr>
      <td>dollarsquare</td>
      <td><img src="src/lib/svg/linear/dollarsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dollarsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dollarsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dollarsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dollarsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dollarsquare.svg" height="60px"></td>
    </tr><tr>
      <td>dribbble</td>
      <td><img src="src/lib/svg/linear/dribbble.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dribbble.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dribbble.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dribbble.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dribbble.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dribbble.svg" height="60px"></td>
    </tr><tr>
      <td>driver2</td>
      <td><img src="src/lib/svg/linear/driver2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/driver2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/driver2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/driver2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/driver2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/driver2.svg" height="60px"></td>
    </tr><tr>
      <td>driverrefresh</td>
      <td><img src="src/lib/svg/linear/driverrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/driverrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/driverrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/driverrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/driverrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/driverrefresh.svg" height="60px"></td>
    </tr><tr>
      <td>driver</td>
      <td><img src="src/lib/svg/linear/driver.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/driver.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/driver.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/driver.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/driver.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/driver.svg" height="60px"></td>
    </tr><tr>
      <td>driving</td>
      <td><img src="src/lib/svg/linear/driving.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/driving.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/driving.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/driving.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/driving.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/driving.svg" height="60px"></td>
    </tr><tr>
      <td>drop</td>
      <td><img src="src/lib/svg/linear/drop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/drop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/drop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/drop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/drop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/drop.svg" height="60px"></td>
    </tr><tr>
      <td>dropbox</td>
      <td><img src="src/lib/svg/linear/dropbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/dropbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/dropbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/dropbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/dropbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/dropbox.svg" height="60px"></td>
    </tr><tr>
      <td>edit2</td>
      <td><img src="src/lib/svg/linear/edit2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/edit2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/edit2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/edit2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/edit2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/edit2.svg" height="60px"></td>
    </tr><tr>
      <td>edit</td>
      <td><img src="src/lib/svg/linear/edit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/edit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/edit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/edit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/edit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/edit.svg" height="60px"></td>
    </tr><tr>
      <td>educare</td>
      <td><img src="src/lib/svg/linear/educare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/educare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/educare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/educare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/educare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/educare.svg" height="60px"></td>
    </tr><tr>
      <td>electricity</td>
      <td><img src="src/lib/svg/linear/electricity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/electricity.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/electricity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/electricity.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/electricity.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/electricity.svg" height="60px"></td>
    </tr><tr>
      <td>element1</td>
      <td><img src="src/lib/svg/linear/element1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/element1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/element1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/element1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/element1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/element1.svg" height="60px"></td>
    </tr><tr>
      <td>element2</td>
      <td><img src="src/lib/svg/linear/element2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/element2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/element2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/element2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/element2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/element2.svg" height="60px"></td>
    </tr><tr>
      <td>element3</td>
      <td><img src="src/lib/svg/linear/element3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/element3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/element3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/element3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/element3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/element3.svg" height="60px"></td>
    </tr><tr>
      <td>element4</td>
      <td><img src="src/lib/svg/linear/element4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/element4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/element4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/element4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/element4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/element4.svg" height="60px"></td>
    </tr><tr>
      <td>elementequal</td>
      <td><img src="src/lib/svg/linear/elementequal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/elementequal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/elementequal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/elementequal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/elementequal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/elementequal.svg" height="60px"></td>
    </tr><tr>
      <td>elementplus</td>
      <td><img src="src/lib/svg/linear/elementplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/elementplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/elementplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/elementplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/elementplus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/elementplus.svg" height="60px"></td>
    </tr><tr>
      <td>emercoin</td>
      <td><img src="src/lib/svg/linear/emercoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emercoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emercoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emercoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emercoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emercoin.svg" height="60px"></td>
    </tr><tr>
      <td>emojihappy</td>
      <td><img src="src/lib/svg/linear/emojihappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emojihappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emojihappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emojihappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emojihappy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emojihappy.svg" height="60px"></td>
    </tr><tr>
      <td>emojinormal</td>
      <td><img src="src/lib/svg/linear/emojinormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emojinormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emojinormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emojinormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emojinormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emojinormal.svg" height="60px"></td>
    </tr><tr>
      <td>emojisad</td>
      <td><img src="src/lib/svg/linear/emojisad.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emojisad.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emojisad.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emojisad.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emojisad.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emojisad.svg" height="60px"></td>
    </tr><tr>
      <td>emptywalletadd</td>
      <td><img src="src/lib/svg/linear/emptywalletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywalletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywalletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywalletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywalletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywalletadd.svg" height="60px"></td>
    </tr><tr>
      <td>emptywalletchange</td>
      <td><img src="src/lib/svg/linear/emptywalletchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywalletchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywalletchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywalletchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywalletchange.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywalletchange.svg" height="60px"></td>
    </tr><tr>
      <td>emptywalletremove</td>
      <td><img src="src/lib/svg/linear/emptywalletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywalletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywalletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywalletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywalletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywalletremove.svg" height="60px"></td>
    </tr><tr>
      <td>emptywallettick</td>
      <td><img src="src/lib/svg/linear/emptywallettick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywallettick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywallettick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywallettick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywallettick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywallettick.svg" height="60px"></td>
    </tr><tr>
      <td>emptywallettime</td>
      <td><img src="src/lib/svg/linear/emptywallettime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywallettime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywallettime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywallettime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywallettime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywallettime.svg" height="60px"></td>
    </tr><tr>
      <td>emptywallet</td>
      <td><img src="src/lib/svg/linear/emptywallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/emptywallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/emptywallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/emptywallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/emptywallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/emptywallet.svg" height="60px"></td>
    </tr><tr>
      <td>enjincoin</td>
      <td><img src="src/lib/svg/linear/enjincoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/enjincoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/enjincoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/enjincoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/enjincoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/enjincoin.svg" height="60px"></td>
    </tr><tr>
      <td>eos</td>
      <td><img src="src/lib/svg/linear/eos.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/eos.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/eos.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/eos.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/eos.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/eos.svg" height="60px"></td>
    </tr><tr>
      <td>eraser1</td>
      <td><img src="src/lib/svg/linear/eraser1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/eraser1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/eraser1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/eraser1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/eraser1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/eraser1.svg" height="60px"></td>
    </tr><tr>
      <td>eraser</td>
      <td><img src="src/lib/svg/linear/eraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/eraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/eraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/eraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/eraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/eraser.svg" height="60px"></td>
    </tr><tr>
      <td>ethereum</td>
      <td><img src="src/lib/svg/linear/ethereum.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ethereum.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ethereum.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ethereum.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ethereum.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ethereum.svg" height="60px"></td>
    </tr><tr>
      <td>ethereumclassic</td>
      <td><img src="src/lib/svg/linear/ethereumclassic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ethereumclassic.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ethereumclassic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ethereumclassic.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ethereumclassic.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ethereumclassic.svg" height="60px"></td>
    </tr><tr>
      <td>export1</td>
      <td><img src="src/lib/svg/linear/export1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/export1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/export1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/export1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/export1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/export1.svg" height="60px"></td>
    </tr><tr>
      <td>export2</td>
      <td><img src="src/lib/svg/linear/export2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/export2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/export2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/export2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/export2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/export2.svg" height="60px"></td>
    </tr><tr>
      <td>export3</td>
      <td><img src="src/lib/svg/linear/export3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/export3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/export3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/export3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/export3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/export3.svg" height="60px"></td>
    </tr><tr>
      <td>export</td>
      <td><img src="src/lib/svg/linear/export.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/export.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/export.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/export.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/export.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/export.svg" height="60px"></td>
    </tr><tr>
      <td>externaldrive</td>
      <td><img src="src/lib/svg/linear/externaldrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/externaldrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/externaldrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/externaldrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/externaldrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/externaldrive.svg" height="60px"></td>
    </tr><tr>
      <td>eyeslash</td>
      <td><img src="src/lib/svg/linear/eyeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/eyeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/eyeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/eyeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/eyeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/eyeslash.svg" height="60px"></td>
    </tr><tr>
      <td>eye</td>
      <td><img src="src/lib/svg/linear/eye.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/eye.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/eye.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/eye.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/eye.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/eye.svg" height="60px"></td>
    </tr><tr>
      <td>facebook</td>
      <td><img src="src/lib/svg/linear/facebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/facebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/facebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/facebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/facebook.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/facebook.svg" height="60px"></td>
    </tr><tr>
      <td>fatrows</td>
      <td><img src="src/lib/svg/linear/fatrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/fatrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/fatrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/fatrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/fatrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/fatrows.svg" height="60px"></td>
    </tr><tr>
      <td>favoritechart</td>
      <td><img src="src/lib/svg/linear/favoritechart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/favoritechart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/favoritechart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/favoritechart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/favoritechart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/favoritechart.svg" height="60px"></td>
    </tr><tr>
      <td>figma1</td>
      <td><img src="src/lib/svg/linear/figma1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/figma1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/figma1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/figma1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/figma1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/figma1.svg" height="60px"></td>
    </tr><tr>
      <td>figma</td>
      <td><img src="src/lib/svg/linear/figma.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/figma.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/figma.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/figma.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/figma.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/figma.svg" height="60px"></td>
    </tr><tr>
      <td>filteradd</td>
      <td><img src="src/lib/svg/linear/filteradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filteradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filteradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filteradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filteradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filteradd.svg" height="60px"></td>
    </tr><tr>
      <td>filteredit</td>
      <td><img src="src/lib/svg/linear/filteredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filteredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filteredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filteredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filteredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filteredit.svg" height="60px"></td>
    </tr><tr>
      <td>filterremove</td>
      <td><img src="src/lib/svg/linear/filterremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filterremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filterremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filterremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filterremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filterremove.svg" height="60px"></td>
    </tr><tr>
      <td>filtersearch</td>
      <td><img src="src/lib/svg/linear/filtersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filtersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filtersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filtersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filtersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filtersearch.svg" height="60px"></td>
    </tr><tr>
      <td>filtersquare</td>
      <td><img src="src/lib/svg/linear/filtersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filtersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filtersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filtersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filtersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filtersquare.svg" height="60px"></td>
    </tr><tr>
      <td>filtertick</td>
      <td><img src="src/lib/svg/linear/filtertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filtertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filtertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filtertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filtertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filtertick.svg" height="60px"></td>
    </tr><tr>
      <td>filter</td>
      <td><img src="src/lib/svg/linear/filter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/filter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/filter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/filter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/filter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/filter.svg" height="60px"></td>
    </tr><tr>
      <td>fingercricle</td>
      <td><img src="src/lib/svg/linear/fingercricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/fingercricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/fingercricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/fingercricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/fingercricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/fingercricle.svg" height="60px"></td>
    </tr><tr>
      <td>fingerscan</td>
      <td><img src="src/lib/svg/linear/fingerscan.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/fingerscan.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/fingerscan.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/fingerscan.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/fingerscan.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/fingerscan.svg" height="60px"></td>
    </tr><tr>
      <td>firstline</td>
      <td><img src="src/lib/svg/linear/firstline.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/firstline.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/firstline.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/firstline.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/firstline.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/firstline.svg" height="60px"></td>
    </tr><tr>
      <td>flag2</td>
      <td><img src="src/lib/svg/linear/flag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flag2.svg" height="60px"></td>
    </tr><tr>
      <td>flag</td>
      <td><img src="src/lib/svg/linear/flag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flag.svg" height="60px"></td>
    </tr><tr>
      <td>flash1</td>
      <td><img src="src/lib/svg/linear/flash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flash1.svg" height="60px"></td>
    </tr><tr>
      <td>flashcircle1</td>
      <td><img src="src/lib/svg/linear/flashcircle1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flashcircle1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flashcircle1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flashcircle1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flashcircle1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flashcircle1.svg" height="60px"></td>
    </tr><tr>
      <td>flashcircle</td>
      <td><img src="src/lib/svg/linear/flashcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flashcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flashcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flashcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flashcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flashcircle.svg" height="60px"></td>
    </tr><tr>
      <td>flashslash</td>
      <td><img src="src/lib/svg/linear/flashslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flashslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flashslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flashslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flashslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flashslash.svg" height="60px"></td>
    </tr><tr>
      <td>flash</td>
      <td><img src="src/lib/svg/linear/flash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/flash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/flash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/flash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/flash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/flash.svg" height="60px"></td>
    </tr><tr>
      <td>folder2</td>
      <td><img src="src/lib/svg/linear/folder2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folder2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folder2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folder2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folder2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folder2.svg" height="60px"></td>
    </tr><tr>
      <td>folderadd</td>
      <td><img src="src/lib/svg/linear/folderadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folderadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folderadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folderadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folderadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folderadd.svg" height="60px"></td>
    </tr><tr>
      <td>foldercloud</td>
      <td><img src="src/lib/svg/linear/foldercloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/foldercloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/foldercloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/foldercloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/foldercloud.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/foldercloud.svg" height="60px"></td>
    </tr><tr>
      <td>folderconnection</td>
      <td><img src="src/lib/svg/linear/folderconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folderconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folderconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folderconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folderconnection.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folderconnection.svg" height="60px"></td>
    </tr><tr>
      <td>foldercross</td>
      <td><img src="src/lib/svg/linear/foldercross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/foldercross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/foldercross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/foldercross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/foldercross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/foldercross.svg" height="60px"></td>
    </tr><tr>
      <td>folderfavorite</td>
      <td><img src="src/lib/svg/linear/folderfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folderfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folderfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folderfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folderfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folderfavorite.svg" height="60px"></td>
    </tr><tr>
      <td>folderminus</td>
      <td><img src="src/lib/svg/linear/folderminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folderminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folderminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folderminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folderminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folderminus.svg" height="60px"></td>
    </tr><tr>
      <td>folderopen</td>
      <td><img src="src/lib/svg/linear/folderopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folderopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folderopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folderopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folderopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folderopen.svg" height="60px"></td>
    </tr><tr>
      <td>folder</td>
      <td><img src="src/lib/svg/linear/folder.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/folder.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/folder.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/folder.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/folder.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/folder.svg" height="60px"></td>
    </tr><tr>
      <td>forbidden2</td>
      <td><img src="src/lib/svg/linear/forbidden2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forbidden2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forbidden2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forbidden2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forbidden2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forbidden2.svg" height="60px"></td>
    </tr><tr>
      <td>forbidden</td>
      <td><img src="src/lib/svg/linear/forbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forbidden.svg" height="60px"></td>
    </tr><tr>
      <td>formatcircle</td>
      <td><img src="src/lib/svg/linear/formatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/formatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/formatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/formatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/formatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/formatcircle.svg" height="60px"></td>
    </tr><tr>
      <td>formatsquare</td>
      <td><img src="src/lib/svg/linear/formatsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/formatsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/formatsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/formatsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/formatsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/formatsquare.svg" height="60px"></td>
    </tr><tr>
      <td>forward10seconds</td>
      <td><img src="src/lib/svg/linear/forward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forward10seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forward10seconds.svg" height="60px"></td>
    </tr><tr>
      <td>forward15seconds</td>
      <td><img src="src/lib/svg/linear/forward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forward15seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forward15seconds.svg" height="60px"></td>
    </tr><tr>
      <td>forward5seconds</td>
      <td><img src="src/lib/svg/linear/forward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forward5seconds.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forward5seconds.svg" height="60px"></td>
    </tr><tr>
      <td>forwarditem</td>
      <td><img src="src/lib/svg/linear/forwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forwarditem.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forwarditem.svg" height="60px"></td>
    </tr><tr>
      <td>forwardsquare</td>
      <td><img src="src/lib/svg/linear/forwardsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forwardsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forwardsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forwardsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forwardsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forwardsquare.svg" height="60px"></td>
    </tr><tr>
      <td>forward</td>
      <td><img src="src/lib/svg/linear/forward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/forward.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/forward.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/forward.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/forward.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/forward.svg" height="60px"></td>
    </tr><tr>
      <td>framer</td>
      <td><img src="src/lib/svg/linear/framer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/framer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/framer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/framer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/framer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/framer.svg" height="60px"></td>
    </tr><tr>
      <td>ftxtoken</td>
      <td><img src="src/lib/svg/linear/ftxtoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ftxtoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ftxtoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ftxtoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ftxtoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ftxtoken.svg" height="60px"></td>
    </tr><tr>
      <td>galleryadd</td>
      <td><img src="src/lib/svg/linear/galleryadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryadd.svg" height="60px"></td>
    </tr><tr>
      <td>galleryedit</td>
      <td><img src="src/lib/svg/linear/galleryedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryedit.svg" height="60px"></td>
    </tr><tr>
      <td>galleryexport</td>
      <td><img src="src/lib/svg/linear/galleryexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryexport.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryexport.svg" height="60px"></td>
    </tr><tr>
      <td>galleryfavorite</td>
      <td><img src="src/lib/svg/linear/galleryfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryfavorite.svg" height="60px"></td>
    </tr><tr>
      <td>galleryimport</td>
      <td><img src="src/lib/svg/linear/galleryimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryimport.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryimport.svg" height="60px"></td>
    </tr><tr>
      <td>galleryremove</td>
      <td><img src="src/lib/svg/linear/galleryremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryremove.svg" height="60px"></td>
    </tr><tr>
      <td>galleryslash</td>
      <td><img src="src/lib/svg/linear/galleryslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/galleryslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/galleryslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/galleryslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/galleryslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/galleryslash.svg" height="60px"></td>
    </tr><tr>
      <td>gallerytick</td>
      <td><img src="src/lib/svg/linear/gallerytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gallerytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gallerytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gallerytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gallerytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gallerytick.svg" height="60px"></td>
    </tr><tr>
      <td>gallery</td>
      <td><img src="src/lib/svg/linear/gallery.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gallery.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gallery.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gallery.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gallery.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gallery.svg" height="60px"></td>
    </tr><tr>
      <td>game</td>
      <td><img src="src/lib/svg/linear/game.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/game.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/game.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/game.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/game.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/game.svg" height="60px"></td>
    </tr><tr>
      <td>gameboy</td>
      <td><img src="src/lib/svg/linear/gameboy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gameboy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gameboy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gameboy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gameboy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gameboy.svg" height="60px"></td>
    </tr><tr>
      <td>gasstation</td>
      <td><img src="src/lib/svg/linear/gasstation.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gasstation.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gasstation.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gasstation.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gasstation.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gasstation.svg" height="60px"></td>
    </tr><tr>
      <td>gemini2</td>
      <td><img src="src/lib/svg/linear/gemini2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gemini2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gemini2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gemini2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gemini2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gemini2.svg" height="60px"></td>
    </tr><tr>
      <td>gemini</td>
      <td><img src="src/lib/svg/linear/gemini.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gemini.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gemini.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gemini.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gemini.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gemini.svg" height="60px"></td>
    </tr><tr>
      <td>ghost</td>
      <td><img src="src/lib/svg/linear/ghost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ghost.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ghost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ghost.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ghost.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ghost.svg" height="60px"></td>
    </tr><tr>
      <td>gift</td>
      <td><img src="src/lib/svg/linear/gift.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gift.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gift.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gift.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gift.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gift.svg" height="60px"></td>
    </tr><tr>
      <td>glass1</td>
      <td><img src="src/lib/svg/linear/glass1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/glass1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/glass1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/glass1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/glass1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/glass1.svg" height="60px"></td>
    </tr><tr>
      <td>glass</td>
      <td><img src="src/lib/svg/linear/glass.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/glass.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/glass.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/glass.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/glass.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/glass.svg" height="60px"></td>
    </tr><tr>
      <td>globaledit</td>
      <td><img src="src/lib/svg/linear/globaledit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/globaledit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/globaledit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/globaledit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/globaledit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/globaledit.svg" height="60px"></td>
    </tr><tr>
      <td>globalrefresh</td>
      <td><img src="src/lib/svg/linear/globalrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/globalrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/globalrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/globalrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/globalrefresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/globalrefresh.svg" height="60px"></td>
    </tr><tr>
      <td>globalsearch</td>
      <td><img src="src/lib/svg/linear/globalsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/globalsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/globalsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/globalsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/globalsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/globalsearch.svg" height="60px"></td>
    </tr><tr>
      <td>global</td>
      <td><img src="src/lib/svg/linear/global.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/global.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/global.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/global.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/global.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/global.svg" height="60px"></td>
    </tr><tr>
      <td>googledrive</td>
      <td><img src="src/lib/svg/linear/googledrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/googledrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/googledrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/googledrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/googledrive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/googledrive.svg" height="60px"></td>
    </tr><tr>
      <td>googleplay</td>
      <td><img src="src/lib/svg/linear/googleplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/googleplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/googleplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/googleplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/googleplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/googleplay.svg" height="60px"></td>
    </tr><tr>
      <td>google</td>
      <td><img src="src/lib/svg/linear/google.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/google.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/google.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/google.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/google.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/google.svg" height="60px"></td>
    </tr><tr>
      <td>gpsslash</td>
      <td><img src="src/lib/svg/linear/gpsslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gpsslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gpsslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gpsslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gpsslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gpsslash.svg" height="60px"></td>
    </tr><tr>
      <td>gps</td>
      <td><img src="src/lib/svg/linear/gps.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gps.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gps.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gps.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gps.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gps.svg" height="60px"></td>
    </tr><tr>
      <td>grammerly</td>
      <td><img src="src/lib/svg/linear/grammerly.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grammerly.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grammerly.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grammerly.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grammerly.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grammerly.svg" height="60px"></td>
    </tr><tr>
      <td>graph</td>
      <td><img src="src/lib/svg/linear/graph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/graph.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/graph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/graph.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/graph.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/graph.svg" height="60px"></td>
    </tr><tr>
      <td>grid1</td>
      <td><img src="src/lib/svg/linear/grid1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid1.svg" height="60px"></td>
    </tr><tr>
      <td>grid2</td>
      <td><img src="src/lib/svg/linear/grid2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid2.svg" height="60px"></td>
    </tr><tr>
      <td>grid3</td>
      <td><img src="src/lib/svg/linear/grid3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid3.svg" height="60px"></td>
    </tr><tr>
      <td>grid4</td>
      <td><img src="src/lib/svg/linear/grid4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid4.svg" height="60px"></td>
    </tr><tr>
      <td>grid5</td>
      <td><img src="src/lib/svg/linear/grid5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid5.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid5.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid5.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid5.svg" height="60px"></td>
    </tr><tr>
      <td>grid6</td>
      <td><img src="src/lib/svg/linear/grid6.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid6.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid6.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid6.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid6.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid6.svg" height="60px"></td>
    </tr><tr>
      <td>grid7</td>
      <td><img src="src/lib/svg/linear/grid7.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid7.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid7.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid7.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid7.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid7.svg" height="60px"></td>
    </tr><tr>
      <td>grid8</td>
      <td><img src="src/lib/svg/linear/grid8.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid8.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid8.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid8.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid8.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid8.svg" height="60px"></td>
    </tr><tr>
      <td>grid9</td>
      <td><img src="src/lib/svg/linear/grid9.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grid9.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grid9.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grid9.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grid9.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grid9.svg" height="60px"></td>
    </tr><tr>
      <td>gridedit</td>
      <td><img src="src/lib/svg/linear/gridedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gridedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gridedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gridedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gridedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gridedit.svg" height="60px"></td>
    </tr><tr>
      <td>grideraser</td>
      <td><img src="src/lib/svg/linear/grideraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/grideraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/grideraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/grideraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/grideraser.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/grideraser.svg" height="60px"></td>
    </tr><tr>
      <td>gridlock</td>
      <td><img src="src/lib/svg/linear/gridlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/gridlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/gridlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/gridlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/gridlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/gridlock.svg" height="60px"></td>
    </tr><tr>
      <td>group</td>
      <td><img src="src/lib/svg/linear/group.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/group.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/group.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/group.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/group.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/group.svg" height="60px"></td>
    </tr><tr>
      <td>happyemoji</td>
      <td><img src="src/lib/svg/linear/happyemoji.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/happyemoji.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/happyemoji.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/happyemoji.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/happyemoji.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/happyemoji.svg" height="60px"></td>
    </tr><tr>
      <td>harmony</td>
      <td><img src="src/lib/svg/linear/harmony.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/harmony.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/harmony.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/harmony.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/harmony.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/harmony.svg" height="60px"></td>
    </tr><tr>
      <td>hashtag1</td>
      <td><img src="src/lib/svg/linear/hashtag1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hashtag1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hashtag1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hashtag1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hashtag1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hashtag1.svg" height="60px"></td>
    </tr><tr>
      <td>hashtagdown</td>
      <td><img src="src/lib/svg/linear/hashtagdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hashtagdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hashtagdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hashtagdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hashtagdown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hashtagdown.svg" height="60px"></td>
    </tr><tr>
      <td>hashtagup</td>
      <td><img src="src/lib/svg/linear/hashtagup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hashtagup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hashtagup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hashtagup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hashtagup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hashtagup.svg" height="60px"></td>
    </tr><tr>
      <td>hashtag</td>
      <td><img src="src/lib/svg/linear/hashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hashtag.svg" height="60px"></td>
    </tr><tr>
      <td>headphone</td>
      <td><img src="src/lib/svg/linear/headphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/headphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/headphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/headphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/headphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/headphone.svg" height="60px"></td>
    </tr><tr>
      <td>headphones</td>
      <td><img src="src/lib/svg/linear/headphones.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/headphones.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/headphones.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/headphones.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/headphones.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/headphones.svg" height="60px"></td>
    </tr><tr>
      <td>health</td>
      <td><img src="src/lib/svg/linear/health.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/health.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/health.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/health.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/health.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/health.svg" height="60px"></td>
    </tr><tr>
      <td>heartadd</td>
      <td><img src="src/lib/svg/linear/heartadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartadd.svg" height="60px"></td>
    </tr><tr>
      <td>heartcircle</td>
      <td><img src="src/lib/svg/linear/heartcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartcircle.svg" height="60px"></td>
    </tr><tr>
      <td>heartedit</td>
      <td><img src="src/lib/svg/linear/heartedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartedit.svg" height="60px"></td>
    </tr><tr>
      <td>heartremove</td>
      <td><img src="src/lib/svg/linear/heartremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartremove.svg" height="60px"></td>
    </tr><tr>
      <td>heartsearch</td>
      <td><img src="src/lib/svg/linear/heartsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartsearch.svg" height="60px"></td>
    </tr><tr>
      <td>heartslash</td>
      <td><img src="src/lib/svg/linear/heartslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heartslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heartslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heartslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heartslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heartslash.svg" height="60px"></td>
    </tr><tr>
      <td>hearttick</td>
      <td><img src="src/lib/svg/linear/hearttick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hearttick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hearttick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hearttick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hearttick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hearttick.svg" height="60px"></td>
    </tr><tr>
      <td>heart</td>
      <td><img src="src/lib/svg/linear/heart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/heart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/heart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/heart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/heart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/heart.svg" height="60px"></td>
    </tr><tr>
      <td>hederahashgraph</td>
      <td><img src="src/lib/svg/linear/hederahashgraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hederahashgraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hederahashgraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hederahashgraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hederahashgraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hederahashgraph.svg" height="60px"></td>
    </tr><tr>
      <td>hex</td>
      <td><img src="src/lib/svg/linear/hex.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hex.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hex.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hex.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hex.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hex.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchy2</td>
      <td><img src="src/lib/svg/linear/hierarchy2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchy2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchy2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchy2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchy2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchy2.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchy3</td>
      <td><img src="src/lib/svg/linear/hierarchy3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchy3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchy3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchy3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchy3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchy3.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchysquare2</td>
      <td><img src="src/lib/svg/linear/hierarchysquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchysquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchysquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchysquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchysquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchysquare2.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchysquare3</td>
      <td><img src="src/lib/svg/linear/hierarchysquare3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchysquare3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchysquare3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchysquare3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchysquare3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchysquare3.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchysquare</td>
      <td><img src="src/lib/svg/linear/hierarchysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchysquare.svg" height="60px"></td>
    </tr><tr>
      <td>hierarchy</td>
      <td><img src="src/lib/svg/linear/hierarchy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hierarchy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hierarchy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hierarchy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hierarchy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hierarchy.svg" height="60px"></td>
    </tr><tr>
      <td>history</td>
      <td><img src="src/lib/svg/linear/history.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/history.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/history.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/history.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/history.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/history.svg" height="60px"></td>
    </tr><tr>
      <td>home1</td>
      <td><img src="src/lib/svg/linear/home1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/home1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/home1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/home1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/home1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/home1.svg" height="60px"></td>
    </tr><tr>
      <td>home2</td>
      <td><img src="src/lib/svg/linear/home2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/home2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/home2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/home2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/home2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/home2.svg" height="60px"></td>
    </tr><tr>
      <td>homehashtag</td>
      <td><img src="src/lib/svg/linear/homehashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/homehashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/homehashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/homehashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/homehashtag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/homehashtag.svg" height="60px"></td>
    </tr><tr>
      <td>hometrenddown</td>
      <td><img src="src/lib/svg/linear/hometrenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hometrenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hometrenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hometrenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hometrenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hometrenddown.svg" height="60px"></td>
    </tr><tr>
      <td>hometrendup</td>
      <td><img src="src/lib/svg/linear/hometrendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hometrendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hometrendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hometrendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hometrendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hometrendup.svg" height="60px"></td>
    </tr><tr>
      <td>homewifi</td>
      <td><img src="src/lib/svg/linear/homewifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/homewifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/homewifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/homewifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/homewifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/homewifi.svg" height="60px"></td>
    </tr><tr>
      <td>home</td>
      <td><img src="src/lib/svg/linear/home.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/home.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/home.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/home.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/home.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/home.svg" height="60px"></td>
    </tr><tr>
      <td>hospital</td>
      <td><img src="src/lib/svg/linear/hospital.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/hospital.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/hospital.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/hospital.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/hospital.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/hospital.svg" height="60px"></td>
    </tr><tr>
      <td>house2</td>
      <td><img src="src/lib/svg/linear/house2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/house2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/house2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/house2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/house2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/house2.svg" height="60px"></td>
    </tr><tr>
      <td>house</td>
      <td><img src="src/lib/svg/linear/house.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/house.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/house.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/house.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/house.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/house.svg" height="60px"></td>
    </tr><tr>
      <td>html5</td>
      <td><img src="src/lib/svg/linear/html5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/html5.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/html5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/html5.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/html5.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/html5.svg" height="60px"></td>
    </tr><tr>
      <td>huobitoken</td>
      <td><img src="src/lib/svg/linear/huobitoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/huobitoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/huobitoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/huobitoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/huobitoken.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/huobitoken.svg" height="60px"></td>
    </tr><tr>
      <td>icon</td>
      <td><img src="src/lib/svg/linear/icon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/icon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/icon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/icon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/icon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/icon.svg" height="60px"></td>
    </tr><tr>
      <td>illustrator</td>
      <td><img src="src/lib/svg/linear/illustrator.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/illustrator.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/illustrator.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/illustrator.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/illustrator.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/illustrator.svg" height="60px"></td>
    </tr><tr>
      <td>image</td>
      <td><img src="src/lib/svg/linear/image.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/image.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/image.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/image.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/image.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/image.svg" height="60px"></td>
    </tr><tr>
      <td>import1</td>
      <td><img src="src/lib/svg/linear/import1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/import1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/import1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/import1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/import1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/import1.svg" height="60px"></td>
    </tr><tr>
      <td>import2</td>
      <td><img src="src/lib/svg/linear/import2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/import2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/import2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/import2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/import2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/import2.svg" height="60px"></td>
    </tr><tr>
      <td>import3</td>
      <td><img src="src/lib/svg/linear/import3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/import3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/import3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/import3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/import3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/import3.svg" height="60px"></td>
    </tr><tr>
      <td>import</td>
      <td><img src="src/lib/svg/linear/import.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/import.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/import.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/import.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/import.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/import.svg" height="60px"></td>
    </tr><tr>
      <td>infocircle</td>
      <td><img src="src/lib/svg/linear/infocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/infocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/infocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/infocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/infocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/infocircle.svg" height="60px"></td>
    </tr><tr>
      <td>information</td>
      <td><img src="src/lib/svg/linear/information.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/information.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/information.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/information.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/information.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/information.svg" height="60px"></td>
    </tr><tr>
      <td>instagram</td>
      <td><img src="src/lib/svg/linear/instagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/instagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/instagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/instagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/instagram.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/instagram.svg" height="60px"></td>
    </tr><tr>
      <td>iost</td>
      <td><img src="src/lib/svg/linear/iost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/iost.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/iost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/iost.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/iost.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/iost.svg" height="60px"></td>
    </tr><tr>
      <td>javascript</td>
      <td><img src="src/lib/svg/linear/javascript.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/javascript.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/javascript.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/javascript.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/javascript.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/javascript.svg" height="60px"></td>
    </tr><tr>
      <td>js</td>
      <td><img src="src/lib/svg/linear/js.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/js.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/js.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/js.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/js.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/js.svg" height="60px"></td>
    </tr><tr>
      <td>judge</td>
      <td><img src="src/lib/svg/linear/judge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/judge.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/judge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/judge.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/judge.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/judge.svg" height="60px"></td>
    </tr><tr>
      <td>kanban</td>
      <td><img src="src/lib/svg/linear/kanban.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/kanban.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/kanban.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/kanban.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/kanban.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/kanban.svg" height="60px"></td>
    </tr><tr>
      <td>keysquare</td>
      <td><img src="src/lib/svg/linear/keysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/keysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/keysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/keysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/keysquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/keysquare.svg" height="60px"></td>
    </tr><tr>
      <td>key</td>
      <td><img src="src/lib/svg/linear/key.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/key.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/key.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/key.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/key.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/key.svg" height="60px"></td>
    </tr><tr>
      <td>keyboardopen</td>
      <td><img src="src/lib/svg/linear/keyboardopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/keyboardopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/keyboardopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/keyboardopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/keyboardopen.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/keyboardopen.svg" height="60px"></td>
    </tr><tr>
      <td>keyboard</td>
      <td><img src="src/lib/svg/linear/keyboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/keyboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/keyboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/keyboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/keyboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/keyboard.svg" height="60px"></td>
    </tr><tr>
      <td>kybernetwork</td>
      <td><img src="src/lib/svg/linear/kybernetwork.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/kybernetwork.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/kybernetwork.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/kybernetwork.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/kybernetwork.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/kybernetwork.svg" height="60px"></td>
    </tr><tr>
      <td>lamp1</td>
      <td><img src="src/lib/svg/linear/lamp1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lamp1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lamp1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lamp1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lamp1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lamp1.svg" height="60px"></td>
    </tr><tr>
      <td>lampcharge</td>
      <td><img src="src/lib/svg/linear/lampcharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lampcharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lampcharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lampcharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lampcharge.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lampcharge.svg" height="60px"></td>
    </tr><tr>
      <td>lampon</td>
      <td><img src="src/lib/svg/linear/lampon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lampon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lampon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lampon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lampon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lampon.svg" height="60px"></td>
    </tr><tr>
      <td>lampslash</td>
      <td><img src="src/lib/svg/linear/lampslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lampslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lampslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lampslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lampslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lampslash.svg" height="60px"></td>
    </tr><tr>
      <td>lamp</td>
      <td><img src="src/lib/svg/linear/lamp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lamp.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lamp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lamp.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lamp.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lamp.svg" height="60px"></td>
    </tr><tr>
      <td>languagecircle</td>
      <td><img src="src/lib/svg/linear/languagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/languagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/languagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/languagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/languagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/languagecircle.svg" height="60px"></td>
    </tr><tr>
      <td>languagesquare</td>
      <td><img src="src/lib/svg/linear/languagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/languagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/languagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/languagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/languagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/languagesquare.svg" height="60px"></td>
    </tr><tr>
      <td>layer</td>
      <td><img src="src/lib/svg/linear/layer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/layer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/layer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/layer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/layer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/layer.svg" height="60px"></td>
    </tr><tr>
      <td>level</td>
      <td><img src="src/lib/svg/linear/level.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/level.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/level.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/level.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/level.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/level.svg" height="60px"></td>
    </tr><tr>
      <td>lifebuoy</td>
      <td><img src="src/lib/svg/linear/lifebuoy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lifebuoy.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lifebuoy.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lifebuoy.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lifebuoy.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lifebuoy.svg" height="60px"></td>
    </tr><tr>
      <td>like1</td>
      <td><img src="src/lib/svg/linear/like1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/like1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/like1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/like1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/like1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/like1.svg" height="60px"></td>
    </tr><tr>
      <td>likedislike</td>
      <td><img src="src/lib/svg/linear/likedislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/likedislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/likedislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/likedislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/likedislike.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/likedislike.svg" height="60px"></td>
    </tr><tr>
      <td>likeshapes</td>
      <td><img src="src/lib/svg/linear/likeshapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/likeshapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/likeshapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/likeshapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/likeshapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/likeshapes.svg" height="60px"></td>
    </tr><tr>
      <td>liketag</td>
      <td><img src="src/lib/svg/linear/liketag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/liketag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/liketag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/liketag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/liketag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/liketag.svg" height="60px"></td>
    </tr><tr>
      <td>like</td>
      <td><img src="src/lib/svg/linear/like.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/like.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/like.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/like.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/like.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/like.svg" height="60px"></td>
    </tr><tr>
      <td>link1</td>
      <td><img src="src/lib/svg/linear/link1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/link1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/link1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/link1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/link1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/link1.svg" height="60px"></td>
    </tr><tr>
      <td>link2</td>
      <td><img src="src/lib/svg/linear/link2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/link2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/link2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/link2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/link2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/link2.svg" height="60px"></td>
    </tr><tr>
      <td>link21</td>
      <td><img src="src/lib/svg/linear/link21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/link21.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/link21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/link21.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/link21.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/link21.svg" height="60px"></td>
    </tr><tr>
      <td>linkcircle</td>
      <td><img src="src/lib/svg/linear/linkcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/linkcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/linkcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/linkcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/linkcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/linkcircle.svg" height="60px"></td>
    </tr><tr>
      <td>linksquare</td>
      <td><img src="src/lib/svg/linear/linksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/linksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/linksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/linksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/linksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/linksquare.svg" height="60px"></td>
    </tr><tr>
      <td>link</td>
      <td><img src="src/lib/svg/linear/link.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/link.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/link.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/link.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/link.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/link.svg" height="60px"></td>
    </tr><tr>
      <td>litecoin</td>
      <td><img src="src/lib/svg/linear/litecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/litecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/litecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/litecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/litecoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/litecoin.svg" height="60px"></td>
    </tr><tr>
      <td>locationadd</td>
      <td><img src="src/lib/svg/linear/locationadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/locationadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/locationadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/locationadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/locationadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/locationadd.svg" height="60px"></td>
    </tr><tr>
      <td>locationcross</td>
      <td><img src="src/lib/svg/linear/locationcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/locationcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/locationcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/locationcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/locationcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/locationcross.svg" height="60px"></td>
    </tr><tr>
      <td>locationminus</td>
      <td><img src="src/lib/svg/linear/locationminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/locationminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/locationminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/locationminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/locationminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/locationminus.svg" height="60px"></td>
    </tr><tr>
      <td>locationslash</td>
      <td><img src="src/lib/svg/linear/locationslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/locationslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/locationslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/locationslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/locationslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/locationslash.svg" height="60px"></td>
    </tr><tr>
      <td>locationtick</td>
      <td><img src="src/lib/svg/linear/locationtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/locationtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/locationtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/locationtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/locationtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/locationtick.svg" height="60px"></td>
    </tr><tr>
      <td>location</td>
      <td><img src="src/lib/svg/linear/location.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/location.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/location.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/location.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/location.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/location.svg" height="60px"></td>
    </tr><tr>
      <td>lock1</td>
      <td><img src="src/lib/svg/linear/lock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lock1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lock1.svg" height="60px"></td>
    </tr><tr>
      <td>lockcircle</td>
      <td><img src="src/lib/svg/linear/lockcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lockcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lockcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lockcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lockcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lockcircle.svg" height="60px"></td>
    </tr><tr>
      <td>lockslash</td>
      <td><img src="src/lib/svg/linear/lockslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lockslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lockslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lockslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lockslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lockslash.svg" height="60px"></td>
    </tr><tr>
      <td>lock</td>
      <td><img src="src/lib/svg/linear/lock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lock.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lock.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lock.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lock.svg" height="60px"></td>
    </tr><tr>
      <td>login1</td>
      <td><img src="src/lib/svg/linear/login1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/login1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/login1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/login1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/login1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/login1.svg" height="60px"></td>
    </tr><tr>
      <td>login</td>
      <td><img src="src/lib/svg/linear/login.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/login.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/login.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/login.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/login.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/login.svg" height="60px"></td>
    </tr><tr>
      <td>logout1</td>
      <td><img src="src/lib/svg/linear/logout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/logout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/logout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/logout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/logout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/logout1.svg" height="60px"></td>
    </tr><tr>
      <td>logout</td>
      <td><img src="src/lib/svg/linear/logout.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/logout.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/logout.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/logout.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/logout.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/logout.svg" height="60px"></td>
    </tr><tr>
      <td>lovely</td>
      <td><img src="src/lib/svg/linear/lovely.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/lovely.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/lovely.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/lovely.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/lovely.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/lovely.svg" height="60px"></td>
    </tr><tr>
      <td>magicstar</td>
      <td><img src="src/lib/svg/linear/magicstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/magicstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/magicstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/magicstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/magicstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/magicstar.svg" height="60px"></td>
    </tr><tr>
      <td>magicpen</td>
      <td><img src="src/lib/svg/linear/magicpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/magicpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/magicpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/magicpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/magicpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/magicpen.svg" height="60px"></td>
    </tr><tr>
      <td>maincomponent</td>
      <td><img src="src/lib/svg/linear/maincomponent.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maincomponent.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maincomponent.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maincomponent.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maincomponent.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maincomponent.svg" height="60px"></td>
    </tr><tr>
      <td>maker</td>
      <td><img src="src/lib/svg/linear/maker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maker.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maker.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maker.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maker.svg" height="60px"></td>
    </tr><tr>
      <td>man</td>
      <td><img src="src/lib/svg/linear/man.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/man.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/man.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/man.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/man.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/man.svg" height="60px"></td>
    </tr><tr>
      <td>map1</td>
      <td><img src="src/lib/svg/linear/map1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/map1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/map1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/map1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/map1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/map1.svg" height="60px"></td>
    </tr><tr>
      <td>map</td>
      <td><img src="src/lib/svg/linear/map.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/map.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/map.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/map.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/map.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/map.svg" height="60px"></td>
    </tr><tr>
      <td>mask1</td>
      <td><img src="src/lib/svg/linear/mask1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mask1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mask1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mask1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mask1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mask1.svg" height="60px"></td>
    </tr><tr>
      <td>mask2</td>
      <td><img src="src/lib/svg/linear/mask2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mask2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mask2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mask2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mask2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mask2.svg" height="60px"></td>
    </tr><tr>
      <td>mask</td>
      <td><img src="src/lib/svg/linear/mask.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mask.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mask.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mask.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mask.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mask.svg" height="60px"></td>
    </tr><tr>
      <td>math</td>
      <td><img src="src/lib/svg/linear/math.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/math.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/math.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/math.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/math.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/math.svg" height="60px"></td>
    </tr><tr>
      <td>maximize1</td>
      <td><img src="src/lib/svg/linear/maximize1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize1.svg" height="60px"></td>
    </tr><tr>
      <td>maximize2</td>
      <td><img src="src/lib/svg/linear/maximize2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize2.svg" height="60px"></td>
    </tr><tr>
      <td>maximize3</td>
      <td><img src="src/lib/svg/linear/maximize3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize3.svg" height="60px"></td>
    </tr><tr>
      <td>maximize4</td>
      <td><img src="src/lib/svg/linear/maximize4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize4.svg" height="60px"></td>
    </tr><tr>
      <td>maximize5</td>
      <td><img src="src/lib/svg/linear/maximize5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize5.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize5.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize5.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize5.svg" height="60px"></td>
    </tr><tr>
      <td>maximizecircle</td>
      <td><img src="src/lib/svg/linear/maximizecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximizecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximizecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximizecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximizecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximizecircle.svg" height="60px"></td>
    </tr><tr>
      <td>maximize</td>
      <td><img src="src/lib/svg/linear/maximize.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/maximize.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/maximize.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/maximize.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/maximize.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/maximize.svg" height="60px"></td>
    </tr><tr>
      <td>medalstar</td>
      <td><img src="src/lib/svg/linear/medalstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/medalstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/medalstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/medalstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/medalstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/medalstar.svg" height="60px"></td>
    </tr><tr>
      <td>medal</td>
      <td><img src="src/lib/svg/linear/medal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/medal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/medal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/medal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/medal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/medal.svg" height="60px"></td>
    </tr><tr>
      <td>menu1</td>
      <td><img src="src/lib/svg/linear/menu1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/menu1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/menu1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/menu1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/menu1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/menu1.svg" height="60px"></td>
    </tr><tr>
      <td>menuboard</td>
      <td><img src="src/lib/svg/linear/menuboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/menuboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/menuboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/menuboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/menuboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/menuboard.svg" height="60px"></td>
    </tr><tr>
      <td>menu</td>
      <td><img src="src/lib/svg/linear/menu.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/menu.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/menu.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/menu.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/menu.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/menu.svg" height="60px"></td>
    </tr><tr>
      <td>message2</td>
      <td><img src="src/lib/svg/linear/message2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/message2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/message2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/message2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/message2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/message2.svg" height="60px"></td>
    </tr><tr>
      <td>messageadd1</td>
      <td><img src="src/lib/svg/linear/messageadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageadd1.svg" height="60px"></td>
    </tr><tr>
      <td>messageadd</td>
      <td><img src="src/lib/svg/linear/messageadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageadd.svg" height="60px"></td>
    </tr><tr>
      <td>messagecircle</td>
      <td><img src="src/lib/svg/linear/messagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagecircle.svg" height="60px"></td>
    </tr><tr>
      <td>messageedit</td>
      <td><img src="src/lib/svg/linear/messageedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageedit.svg" height="60px"></td>
    </tr><tr>
      <td>messagefavorite</td>
      <td><img src="src/lib/svg/linear/messagefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagefavorite.svg" height="60px"></td>
    </tr><tr>
      <td>messageminus</td>
      <td><img src="src/lib/svg/linear/messageminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageminus.svg" height="60px"></td>
    </tr><tr>
      <td>messagenotif</td>
      <td><img src="src/lib/svg/linear/messagenotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagenotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagenotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagenotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagenotif.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagenotif.svg" height="60px"></td>
    </tr><tr>
      <td>messageprogramming</td>
      <td><img src="src/lib/svg/linear/messageprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageprogramming.svg" height="60px"></td>
    </tr><tr>
      <td>messagequestion</td>
      <td><img src="src/lib/svg/linear/messagequestion.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagequestion.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagequestion.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagequestion.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagequestion.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagequestion.svg" height="60px"></td>
    </tr><tr>
      <td>messageremove</td>
      <td><img src="src/lib/svg/linear/messageremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messageremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messageremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messageremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messageremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messageremove.svg" height="60px"></td>
    </tr><tr>
      <td>messagesearch</td>
      <td><img src="src/lib/svg/linear/messagesearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagesearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagesearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagesearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagesearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagesearch.svg" height="60px"></td>
    </tr><tr>
      <td>messagesquare</td>
      <td><img src="src/lib/svg/linear/messagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagesquare.svg" height="60px"></td>
    </tr><tr>
      <td>messagetext1</td>
      <td><img src="src/lib/svg/linear/messagetext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagetext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagetext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagetext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagetext1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagetext1.svg" height="60px"></td>
    </tr><tr>
      <td>messagetext</td>
      <td><img src="src/lib/svg/linear/messagetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagetext.svg" height="60px"></td>
    </tr><tr>
      <td>messagetick</td>
      <td><img src="src/lib/svg/linear/messagetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagetick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagetick.svg" height="60px"></td>
    </tr><tr>
      <td>messagetime</td>
      <td><img src="src/lib/svg/linear/messagetime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messagetime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messagetime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messagetime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messagetime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messagetime.svg" height="60px"></td>
    </tr><tr>
      <td>message</td>
      <td><img src="src/lib/svg/linear/message.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/message.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/message.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/message.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/message.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/message.svg" height="60px"></td>
    </tr><tr>
      <td>messages1</td>
      <td><img src="src/lib/svg/linear/messages1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messages1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messages1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messages1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messages1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messages1.svg" height="60px"></td>
    </tr><tr>
      <td>messages2</td>
      <td><img src="src/lib/svg/linear/messages2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messages2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messages2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messages2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messages2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messages2.svg" height="60px"></td>
    </tr><tr>
      <td>messages3</td>
      <td><img src="src/lib/svg/linear/messages3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messages3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messages3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messages3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messages3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messages3.svg" height="60px"></td>
    </tr><tr>
      <td>messages</td>
      <td><img src="src/lib/svg/linear/messages.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messages.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messages.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messages.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messages.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messages.svg" height="60px"></td>
    </tr><tr>
      <td>messenger</td>
      <td><img src="src/lib/svg/linear/messenger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/messenger.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/messenger.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/messenger.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/messenger.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/messenger.svg" height="60px"></td>
    </tr><tr>
      <td>microphone2</td>
      <td><img src="src/lib/svg/linear/microphone2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/microphone2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/microphone2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/microphone2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/microphone2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/microphone2.svg" height="60px"></td>
    </tr><tr>
      <td>microphoneslash1</td>
      <td><img src="src/lib/svg/linear/microphoneslash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/microphoneslash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/microphoneslash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/microphoneslash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/microphoneslash1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/microphoneslash1.svg" height="60px"></td>
    </tr><tr>
      <td>microphoneslash</td>
      <td><img src="src/lib/svg/linear/microphoneslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/microphoneslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/microphoneslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/microphoneslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/microphoneslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/microphoneslash.svg" height="60px"></td>
    </tr><tr>
      <td>microphone</td>
      <td><img src="src/lib/svg/linear/microphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/microphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/microphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/microphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/microphone.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/microphone.svg" height="60px"></td>
    </tr><tr>
      <td>microscope</td>
      <td><img src="src/lib/svg/linear/microscope.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/microscope.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/microscope.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/microscope.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/microscope.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/microscope.svg" height="60px"></td>
    </tr><tr>
      <td>milk</td>
      <td><img src="src/lib/svg/linear/milk.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/milk.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/milk.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/milk.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/milk.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/milk.svg" height="60px"></td>
    </tr><tr>
      <td>minimusicsqaure</td>
      <td><img src="src/lib/svg/linear/minimusicsqaure.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/minimusicsqaure.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/minimusicsqaure.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/minimusicsqaure.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/minimusicsqaure.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/minimusicsqaure.svg" height="60px"></td>
    </tr><tr>
      <td>minuscirlce</td>
      <td><img src="src/lib/svg/linear/minuscirlce.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/minuscirlce.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/minuscirlce.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/minuscirlce.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/minuscirlce.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/minuscirlce.svg" height="60px"></td>
    </tr><tr>
      <td>minussquare</td>
      <td><img src="src/lib/svg/linear/minussquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/minussquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/minussquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/minussquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/minussquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/minussquare.svg" height="60px"></td>
    </tr><tr>
      <td>minus</td>
      <td><img src="src/lib/svg/linear/minus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/minus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/minus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/minus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/minus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/minus.svg" height="60px"></td>
    </tr><tr>
      <td>mirror</td>
      <td><img src="src/lib/svg/linear/mirror.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mirror.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mirror.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mirror.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mirror.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mirror.svg" height="60px"></td>
    </tr><tr>
      <td>mirroringscreen</td>
      <td><img src="src/lib/svg/linear/mirroringscreen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mirroringscreen.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mirroringscreen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mirroringscreen.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mirroringscreen.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mirroringscreen.svg" height="60px"></td>
    </tr><tr>
      <td>mobileprogramming</td>
      <td><img src="src/lib/svg/linear/mobileprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mobileprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mobileprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mobileprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mobileprogramming.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mobileprogramming.svg" height="60px"></td>
    </tr><tr>
      <td>mobile</td>
      <td><img src="src/lib/svg/linear/mobile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mobile.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mobile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mobile.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mobile.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mobile.svg" height="60px"></td>
    </tr><tr>
      <td>monero</td>
      <td><img src="src/lib/svg/linear/monero.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/monero.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/monero.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/monero.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/monero.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/monero.svg" height="60px"></td>
    </tr><tr>
      <td>money2</td>
      <td><img src="src/lib/svg/linear/money2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/money2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/money2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/money2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/money2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/money2.svg" height="60px"></td>
    </tr><tr>
      <td>money3</td>
      <td><img src="src/lib/svg/linear/money3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/money3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/money3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/money3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/money3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/money3.svg" height="60px"></td>
    </tr><tr>
      <td>money4</td>
      <td><img src="src/lib/svg/linear/money4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/money4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/money4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/money4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/money4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/money4.svg" height="60px"></td>
    </tr><tr>
      <td>moneyadd</td>
      <td><img src="src/lib/svg/linear/moneyadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneyadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneyadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneyadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneyadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneyadd.svg" height="60px"></td>
    </tr><tr>
      <td>moneychange</td>
      <td><img src="src/lib/svg/linear/moneychange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneychange.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneychange.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneychange.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneychange.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneychange.svg" height="60px"></td>
    </tr><tr>
      <td>moneyforbidden</td>
      <td><img src="src/lib/svg/linear/moneyforbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneyforbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneyforbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneyforbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneyforbidden.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneyforbidden.svg" height="60px"></td>
    </tr><tr>
      <td>moneyrecive</td>
      <td><img src="src/lib/svg/linear/moneyrecive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneyrecive.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneyrecive.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneyrecive.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneyrecive.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneyrecive.svg" height="60px"></td>
    </tr><tr>
      <td>moneyremove</td>
      <td><img src="src/lib/svg/linear/moneyremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneyremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneyremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneyremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneyremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneyremove.svg" height="60px"></td>
    </tr><tr>
      <td>moneysend</td>
      <td><img src="src/lib/svg/linear/moneysend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneysend.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneysend.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneysend.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneysend.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneysend.svg" height="60px"></td>
    </tr><tr>
      <td>moneytick</td>
      <td><img src="src/lib/svg/linear/moneytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneytick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneytick.svg" height="60px"></td>
    </tr><tr>
      <td>moneytime</td>
      <td><img src="src/lib/svg/linear/moneytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneytime.svg" height="60px"></td>
    </tr><tr>
      <td>money</td>
      <td><img src="src/lib/svg/linear/money.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/money.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/money.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/money.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/money.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/money.svg" height="60px"></td>
    </tr><tr>
      <td>moneys</td>
      <td><img src="src/lib/svg/linear/moneys.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moneys.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moneys.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moneys.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moneys.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moneys.svg" height="60px"></td>
    </tr><tr>
      <td>monitormobbile</td>
      <td><img src="src/lib/svg/linear/monitormobbile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/monitormobbile.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/monitormobbile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/monitormobbile.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/monitormobbile.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/monitormobbile.svg" height="60px"></td>
    </tr><tr>
      <td>monitorrecorder</td>
      <td><img src="src/lib/svg/linear/monitorrecorder.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/monitorrecorder.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/monitorrecorder.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/monitorrecorder.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/monitorrecorder.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/monitorrecorder.svg" height="60px"></td>
    </tr><tr>
      <td>monitor</td>
      <td><img src="src/lib/svg/linear/monitor.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/monitor.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/monitor.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/monitor.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/monitor.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/monitor.svg" height="60px"></td>
    </tr><tr>
      <td>moon</td>
      <td><img src="src/lib/svg/linear/moon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moon.svg" height="60px"></td>
    </tr><tr>
      <td>more2</td>
      <td><img src="src/lib/svg/linear/more2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/more2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/more2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/more2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/more2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/more2.svg" height="60px"></td>
    </tr><tr>
      <td>morecircle</td>
      <td><img src="src/lib/svg/linear/morecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/morecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/morecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/morecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/morecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/morecircle.svg" height="60px"></td>
    </tr><tr>
      <td>moresquare</td>
      <td><img src="src/lib/svg/linear/moresquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/moresquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/moresquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/moresquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/moresquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/moresquare.svg" height="60px"></td>
    </tr><tr>
      <td>more</td>
      <td><img src="src/lib/svg/linear/more.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/more.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/more.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/more.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/more.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/more.svg" height="60px"></td>
    </tr><tr>
      <td>mouse1</td>
      <td><img src="src/lib/svg/linear/mouse1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mouse1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mouse1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mouse1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mouse1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mouse1.svg" height="60px"></td>
    </tr><tr>
      <td>mousecircle</td>
      <td><img src="src/lib/svg/linear/mousecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mousecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mousecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mousecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mousecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mousecircle.svg" height="60px"></td>
    </tr><tr>
      <td>mousesquare</td>
      <td><img src="src/lib/svg/linear/mousesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mousesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mousesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mousesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mousesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mousesquare.svg" height="60px"></td>
    </tr><tr>
      <td>mouse</td>
      <td><img src="src/lib/svg/linear/mouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/mouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/mouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/mouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/mouse.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/mouse.svg" height="60px"></td>
    </tr><tr>
      <td>musiccircle</td>
      <td><img src="src/lib/svg/linear/musiccircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musiccircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musiccircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musiccircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musiccircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musiccircle.svg" height="60px"></td>
    </tr><tr>
      <td>musicdashboard</td>
      <td><img src="src/lib/svg/linear/musicdashboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicdashboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicdashboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicdashboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicdashboard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicdashboard.svg" height="60px"></td>
    </tr><tr>
      <td>musicfilter</td>
      <td><img src="src/lib/svg/linear/musicfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicfilter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicfilter.svg" height="60px"></td>
    </tr><tr>
      <td>musiclibrary2</td>
      <td><img src="src/lib/svg/linear/musiclibrary2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musiclibrary2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musiclibrary2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musiclibrary2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musiclibrary2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musiclibrary2.svg" height="60px"></td>
    </tr><tr>
      <td>musicplay</td>
      <td><img src="src/lib/svg/linear/musicplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicplay.svg" height="60px"></td>
    </tr><tr>
      <td>musicplaylist</td>
      <td><img src="src/lib/svg/linear/musicplaylist.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicplaylist.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicplaylist.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicplaylist.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicplaylist.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicplaylist.svg" height="60px"></td>
    </tr><tr>
      <td>musicsquareadd</td>
      <td><img src="src/lib/svg/linear/musicsquareadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicsquareadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicsquareadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicsquareadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicsquareadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicsquareadd.svg" height="60px"></td>
    </tr><tr>
      <td>musicsquareremove</td>
      <td><img src="src/lib/svg/linear/musicsquareremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicsquareremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicsquareremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicsquareremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicsquareremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicsquareremove.svg" height="60px"></td>
    </tr><tr>
      <td>musicsquaresearch</td>
      <td><img src="src/lib/svg/linear/musicsquaresearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicsquaresearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicsquaresearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicsquaresearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicsquaresearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicsquaresearch.svg" height="60px"></td>
    </tr><tr>
      <td>musicsquare</td>
      <td><img src="src/lib/svg/linear/musicsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicsquare.svg" height="60px"></td>
    </tr><tr>
      <td>music</td>
      <td><img src="src/lib/svg/linear/music.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/music.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/music.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/music.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/music.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/music.svg" height="60px"></td>
    </tr><tr>
      <td>musicnote</td>
      <td><img src="src/lib/svg/linear/musicnote.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/musicnote.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/musicnote.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/musicnote.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/musicnote.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/musicnote.svg" height="60px"></td>
    </tr><tr>
      <td>nebulas</td>
      <td><img src="src/lib/svg/linear/nebulas.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/nebulas.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/nebulas.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/nebulas.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/nebulas.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/nebulas.svg" height="60px"></td>
    </tr><tr>
      <td>nem</td>
      <td><img src="src/lib/svg/linear/nem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/nem.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/nem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/nem.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/nem.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/nem.svg" height="60px"></td>
    </tr><tr>
      <td>nexo</td>
      <td><img src="src/lib/svg/linear/nexo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/nexo.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/nexo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/nexo.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/nexo.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/nexo.svg" height="60px"></td>
    </tr><tr>
      <td>next</td>
      <td><img src="src/lib/svg/linear/next.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/next.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/next.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/next.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/next.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/next.svg" height="60px"></td>
    </tr><tr>
      <td>note1</td>
      <td><img src="src/lib/svg/linear/note1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/note1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/note1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/note1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/note1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/note1.svg" height="60px"></td>
    </tr><tr>
      <td>note2</td>
      <td><img src="src/lib/svg/linear/note2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/note2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/note2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/note2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/note2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/note2.svg" height="60px"></td>
    </tr><tr>
      <td>note3</td>
      <td><img src="src/lib/svg/linear/note3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/note3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/note3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/note3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/note3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/note3.svg" height="60px"></td>
    </tr><tr>
      <td>noteadd</td>
      <td><img src="src/lib/svg/linear/noteadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/noteadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/noteadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/noteadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/noteadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/noteadd.svg" height="60px"></td>
    </tr><tr>
      <td>notefavorite</td>
      <td><img src="src/lib/svg/linear/notefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notefavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notefavorite.svg" height="60px"></td>
    </tr><tr>
      <td>noteremove</td>
      <td><img src="src/lib/svg/linear/noteremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/noteremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/noteremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/noteremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/noteremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/noteremove.svg" height="60px"></td>
    </tr><tr>
      <td>notesquare</td>
      <td><img src="src/lib/svg/linear/notesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notesquare.svg" height="60px"></td>
    </tr><tr>
      <td>notetext</td>
      <td><img src="src/lib/svg/linear/notetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notetext.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notetext.svg" height="60px"></td>
    </tr><tr>
      <td>note</td>
      <td><img src="src/lib/svg/linear/note.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/note.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/note.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/note.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/note.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/note.svg" height="60px"></td>
    </tr><tr>
      <td>notification1</td>
      <td><img src="src/lib/svg/linear/notification1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notification1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notification1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notification1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notification1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notification1.svg" height="60px"></td>
    </tr><tr>
      <td>notificationbing</td>
      <td><img src="src/lib/svg/linear/notificationbing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notificationbing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notificationbing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notificationbing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notificationbing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notificationbing.svg" height="60px"></td>
    </tr><tr>
      <td>notificationcircle</td>
      <td><img src="src/lib/svg/linear/notificationcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notificationcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notificationcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notificationcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notificationcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notificationcircle.svg" height="60px"></td>
    </tr><tr>
      <td>notificationfavorite</td>
      <td><img src="src/lib/svg/linear/notificationfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notificationfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notificationfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notificationfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notificationfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notificationfavorite.svg" height="60px"></td>
    </tr><tr>
      <td>notificationstatus</td>
      <td><img src="src/lib/svg/linear/notificationstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notificationstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notificationstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notificationstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notificationstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notificationstatus.svg" height="60px"></td>
    </tr><tr>
      <td>notification</td>
      <td><img src="src/lib/svg/linear/notification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/notification.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/notification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/notification.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/notification.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/notification.svg" height="60px"></td>
    </tr><tr>
      <td>oceanprotocol</td>
      <td><img src="src/lib/svg/linear/oceanprotocol.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/oceanprotocol.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/oceanprotocol.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/oceanprotocol.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/oceanprotocol.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/oceanprotocol.svg" height="60px"></td>
    </tr><tr>
      <td>okb</td>
      <td><img src="src/lib/svg/linear/okb.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/okb.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/okb.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/okb.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/okb.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/okb.svg" height="60px"></td>
    </tr><tr>
      <td>omegacircle</td>
      <td><img src="src/lib/svg/linear/omegacircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/omegacircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/omegacircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/omegacircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/omegacircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/omegacircle.svg" height="60px"></td>
    </tr><tr>
      <td>omegasquare</td>
      <td><img src="src/lib/svg/linear/omegasquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/omegasquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/omegasquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/omegasquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/omegasquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/omegasquare.svg" height="60px"></td>
    </tr><tr>
      <td>ontology</td>
      <td><img src="src/lib/svg/linear/ontology.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ontology.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ontology.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ontology.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ontology.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ontology.svg" height="60px"></td>
    </tr><tr>
      <td>paintbucket</td>
      <td><img src="src/lib/svg/linear/paintbucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/paintbucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/paintbucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/paintbucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/paintbucket.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/paintbucket.svg" height="60px"></td>
    </tr><tr>
      <td>paperclip2</td>
      <td><img src="src/lib/svg/linear/paperclip2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/paperclip2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/paperclip2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/paperclip2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/paperclip2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/paperclip2.svg" height="60px"></td>
    </tr><tr>
      <td>paperclip</td>
      <td><img src="src/lib/svg/linear/paperclip.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/paperclip.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/paperclip.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/paperclip.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/paperclip.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/paperclip.svg" height="60px"></td>
    </tr><tr>
      <td>passwordcheck</td>
      <td><img src="src/lib/svg/linear/passwordcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/passwordcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/passwordcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/passwordcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/passwordcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/passwordcheck.svg" height="60px"></td>
    </tr><tr>
      <td>path2</td>
      <td><img src="src/lib/svg/linear/path2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/path2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/path2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/path2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/path2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/path2.svg" height="60px"></td>
    </tr><tr>
      <td>pathsquare</td>
      <td><img src="src/lib/svg/linear/pathsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pathsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pathsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pathsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pathsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pathsquare.svg" height="60px"></td>
    </tr><tr>
      <td>path</td>
      <td><img src="src/lib/svg/linear/path.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/path.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/path.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/path.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/path.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/path.svg" height="60px"></td>
    </tr><tr>
      <td>pausecircle</td>
      <td><img src="src/lib/svg/linear/pausecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pausecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pausecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pausecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pausecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pausecircle.svg" height="60px"></td>
    </tr><tr>
      <td>pause</td>
      <td><img src="src/lib/svg/linear/pause.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pause.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pause.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pause.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pause.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pause.svg" height="60px"></td>
    </tr><tr>
      <td>paypal</td>
      <td><img src="src/lib/svg/linear/paypal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/paypal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/paypal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/paypal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/paypal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/paypal.svg" height="60px"></td>
    </tr><tr>
      <td>penadd</td>
      <td><img src="src/lib/svg/linear/penadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/penadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/penadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/penadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/penadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/penadd.svg" height="60px"></td>
    </tr><tr>
      <td>penclose</td>
      <td><img src="src/lib/svg/linear/penclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/penclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/penclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/penclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/penclose.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/penclose.svg" height="60px"></td>
    </tr><tr>
      <td>penremove</td>
      <td><img src="src/lib/svg/linear/penremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/penremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/penremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/penremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/penremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/penremove.svg" height="60px"></td>
    </tr><tr>
      <td>pentool2</td>
      <td><img src="src/lib/svg/linear/pentool2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pentool2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pentool2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pentool2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pentool2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pentool2.svg" height="60px"></td>
    </tr><tr>
      <td>pentool</td>
      <td><img src="src/lib/svg/linear/pentool.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pentool.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pentool.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pentool.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pentool.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pentool.svg" height="60px"></td>
    </tr><tr>
      <td>people</td>
      <td><img src="src/lib/svg/linear/people.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/people.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/people.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/people.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/people.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/people.svg" height="60px"></td>
    </tr><tr>
      <td>percentagecircle</td>
      <td><img src="src/lib/svg/linear/percentagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/percentagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/percentagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/percentagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/percentagecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/percentagecircle.svg" height="60px"></td>
    </tr><tr>
      <td>percentagesquare</td>
      <td><img src="src/lib/svg/linear/percentagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/percentagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/percentagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/percentagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/percentagesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/percentagesquare.svg" height="60px"></td>
    </tr><tr>
      <td>personalcard</td>
      <td><img src="src/lib/svg/linear/personalcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/personalcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/personalcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/personalcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/personalcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/personalcard.svg" height="60px"></td>
    </tr><tr>
      <td>pet</td>
      <td><img src="src/lib/svg/linear/pet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pet.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pet.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pet.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pet.svg" height="60px"></td>
    </tr><tr>
      <td>pharagraphspacing</td>
      <td><img src="src/lib/svg/linear/pharagraphspacing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pharagraphspacing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pharagraphspacing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pharagraphspacing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pharagraphspacing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pharagraphspacing.svg" height="60px"></td>
    </tr><tr>
      <td>photoshop</td>
      <td><img src="src/lib/svg/linear/photoshop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/photoshop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/photoshop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/photoshop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/photoshop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/photoshop.svg" height="60px"></td>
    </tr><tr>
      <td>pictureframe</td>
      <td><img src="src/lib/svg/linear/pictureframe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/pictureframe.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/pictureframe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/pictureframe.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/pictureframe.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/pictureframe.svg" height="60px"></td>
    </tr><tr>
      <td>playadd</td>
      <td><img src="src/lib/svg/linear/playadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/playadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/playadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/playadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/playadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/playadd.svg" height="60px"></td>
    </tr><tr>
      <td>playcircle</td>
      <td><img src="src/lib/svg/linear/playcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/playcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/playcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/playcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/playcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/playcircle.svg" height="60px"></td>
    </tr><tr>
      <td>playcricle</td>
      <td><img src="src/lib/svg/linear/playcricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/playcricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/playcricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/playcricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/playcricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/playcricle.svg" height="60px"></td>
    </tr><tr>
      <td>playremove</td>
      <td><img src="src/lib/svg/linear/playremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/playremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/playremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/playremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/playremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/playremove.svg" height="60px"></td>
    </tr><tr>
      <td>play</td>
      <td><img src="src/lib/svg/linear/play.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/play.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/play.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/play.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/play.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/play.svg" height="60px"></td>
    </tr><tr>
      <td>point</td>
      <td><img src="src/lib/svg/linear/point.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/point.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/point.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/point.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/point.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/point.svg" height="60px"></td>
    </tr><tr>
      <td>polkadot</td>
      <td><img src="src/lib/svg/linear/polkadot.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/polkadot.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/polkadot.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/polkadot.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/polkadot.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/polkadot.svg" height="60px"></td>
    </tr><tr>
      <td>polygon</td>
      <td><img src="src/lib/svg/linear/polygon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/polygon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/polygon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/polygon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/polygon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/polygon.svg" height="60px"></td>
    </tr><tr>
      <td>polyswarm</td>
      <td><img src="src/lib/svg/linear/polyswarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/polyswarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/polyswarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/polyswarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/polyswarm.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/polyswarm.svg" height="60px"></td>
    </tr><tr>
      <td>presentionchart</td>
      <td><img src="src/lib/svg/linear/presentionchart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/presentionchart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/presentionchart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/presentionchart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/presentionchart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/presentionchart.svg" height="60px"></td>
    </tr><tr>
      <td>previous</td>
      <td><img src="src/lib/svg/linear/previous.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/previous.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/previous.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/previous.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/previous.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/previous.svg" height="60px"></td>
    </tr><tr>
      <td>printerslash</td>
      <td><img src="src/lib/svg/linear/printerslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/printerslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/printerslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/printerslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/printerslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/printerslash.svg" height="60px"></td>
    </tr><tr>
      <td>printer</td>
      <td><img src="src/lib/svg/linear/printer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/printer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/printer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/printer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/printer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/printer.svg" height="60px"></td>
    </tr><tr>
      <td>profile2user</td>
      <td><img src="src/lib/svg/linear/profile2user.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profile2user.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profile2user.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profile2user.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profile2user.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profile2user.svg" height="60px"></td>
    </tr><tr>
      <td>profileadd</td>
      <td><img src="src/lib/svg/linear/profileadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profileadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profileadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profileadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profileadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profileadd.svg" height="60px"></td>
    </tr><tr>
      <td>profilecircle</td>
      <td><img src="src/lib/svg/linear/profilecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profilecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profilecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profilecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profilecircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profilecircle.svg" height="60px"></td>
    </tr><tr>
      <td>profiledelete</td>
      <td><img src="src/lib/svg/linear/profiledelete.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profiledelete.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profiledelete.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profiledelete.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profiledelete.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profiledelete.svg" height="60px"></td>
    </tr><tr>
      <td>profileremove</td>
      <td><img src="src/lib/svg/linear/profileremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profileremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profileremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profileremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profileremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profileremove.svg" height="60px"></td>
    </tr><tr>
      <td>profiletick</td>
      <td><img src="src/lib/svg/linear/profiletick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profiletick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profiletick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profiletick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profiletick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profiletick.svg" height="60px"></td>
    </tr><tr>
      <td>profile</td>
      <td><img src="src/lib/svg/linear/profile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/profile.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/profile.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/profile.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/profile.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/profile.svg" height="60px"></td>
    </tr><tr>
      <td>programmingarrow</td>
      <td><img src="src/lib/svg/linear/programmingarrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/programmingarrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/programmingarrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/programmingarrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/programmingarrow.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/programmingarrow.svg" height="60px"></td>
    </tr><tr>
      <td>programmingarrows</td>
      <td><img src="src/lib/svg/linear/programmingarrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/programmingarrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/programmingarrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/programmingarrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/programmingarrows.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/programmingarrows.svg" height="60px"></td>
    </tr><tr>
      <td>python</td>
      <td><img src="src/lib/svg/linear/python.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/python.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/python.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/python.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/python.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/python.svg" height="60px"></td>
    </tr><tr>
      <td>quant</td>
      <td><img src="src/lib/svg/linear/quant.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quant.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quant.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quant.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quant.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quant.svg" height="60px"></td>
    </tr><tr>
      <td>quotedowncircle</td>
      <td><img src="src/lib/svg/linear/quotedowncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quotedowncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quotedowncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quotedowncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quotedowncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quotedowncircle.svg" height="60px"></td>
    </tr><tr>
      <td>quotedownsquare</td>
      <td><img src="src/lib/svg/linear/quotedownsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quotedownsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quotedownsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quotedownsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quotedownsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quotedownsquare.svg" height="60px"></td>
    </tr><tr>
      <td>quotedown</td>
      <td><img src="src/lib/svg/linear/quotedown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quotedown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quotedown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quotedown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quotedown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quotedown.svg" height="60px"></td>
    </tr><tr>
      <td>quoteupcircle</td>
      <td><img src="src/lib/svg/linear/quoteupcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quoteupcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quoteupcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quoteupcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quoteupcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quoteupcircle.svg" height="60px"></td>
    </tr><tr>
      <td>quoteupsquare</td>
      <td><img src="src/lib/svg/linear/quoteupsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quoteupsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quoteupsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quoteupsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quoteupsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quoteupsquare.svg" height="60px"></td>
    </tr><tr>
      <td>quoteup</td>
      <td><img src="src/lib/svg/linear/quoteup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/quoteup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/quoteup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/quoteup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/quoteup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/quoteup.svg" height="60px"></td>
    </tr><tr>
      <td>radar1</td>
      <td><img src="src/lib/svg/linear/radar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/radar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/radar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/radar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/radar1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/radar1.svg" height="60px"></td>
    </tr><tr>
      <td>radar2</td>
      <td><img src="src/lib/svg/linear/radar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/radar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/radar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/radar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/radar2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/radar2.svg" height="60px"></td>
    </tr><tr>
      <td>radar</td>
      <td><img src="src/lib/svg/linear/radar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/radar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/radar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/radar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/radar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/radar.svg" height="60px"></td>
    </tr><tr>
      <td>radio</td>
      <td><img src="src/lib/svg/linear/radio.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/radio.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/radio.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/radio.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/radio.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/radio.svg" height="60px"></td>
    </tr><tr>
      <td>ram2</td>
      <td><img src="src/lib/svg/linear/ram2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ram2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ram2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ram2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ram2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ram2.svg" height="60px"></td>
    </tr><tr>
      <td>ram</td>
      <td><img src="src/lib/svg/linear/ram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ram.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ram.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ram.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ram.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ram.svg" height="60px"></td>
    </tr><tr>
      <td>ranking1</td>
      <td><img src="src/lib/svg/linear/ranking1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ranking1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ranking1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ranking1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ranking1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ranking1.svg" height="60px"></td>
    </tr><tr>
      <td>ranking</td>
      <td><img src="src/lib/svg/linear/ranking.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ranking.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ranking.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ranking.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ranking.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ranking.svg" height="60px"></td>
    </tr><tr>
      <td>receipt1</td>
      <td><img src="src/lib/svg/linear/receipt1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receipt1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receipt1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receipt1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receipt1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receipt1.svg" height="60px"></td>
    </tr><tr>
      <td>receipt21</td>
      <td><img src="src/lib/svg/linear/receipt21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receipt21.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receipt21.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receipt21.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receipt21.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receipt21.svg" height="60px"></td>
    </tr><tr>
      <td>receipt2</td>
      <td><img src="src/lib/svg/linear/receipt2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receipt2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receipt2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receipt2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receipt2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receipt2.svg" height="60px"></td>
    </tr><tr>
      <td>receiptadd</td>
      <td><img src="src/lib/svg/linear/receiptadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptadd.svg" height="60px"></td>
    </tr><tr>
      <td>receiptdiscount</td>
      <td><img src="src/lib/svg/linear/receiptdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptdiscount.svg" height="60px"></td>
    </tr><tr>
      <td>receiptdisscount</td>
      <td><img src="src/lib/svg/linear/receiptdisscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptdisscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptdisscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptdisscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptdisscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptdisscount.svg" height="60px"></td>
    </tr><tr>
      <td>receiptedit</td>
      <td><img src="src/lib/svg/linear/receiptedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptedit.svg" height="60px"></td>
    </tr><tr>
      <td>receiptitem</td>
      <td><img src="src/lib/svg/linear/receiptitem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptitem.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptitem.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptitem.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptitem.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptitem.svg" height="60px"></td>
    </tr><tr>
      <td>receiptminus</td>
      <td><img src="src/lib/svg/linear/receiptminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptminus.svg" height="60px"></td>
    </tr><tr>
      <td>receiptsearch</td>
      <td><img src="src/lib/svg/linear/receiptsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptsearch.svg" height="60px"></td>
    </tr><tr>
      <td>receiptsquare</td>
      <td><img src="src/lib/svg/linear/receiptsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receiptsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receiptsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receiptsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receiptsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receiptsquare.svg" height="60px"></td>
    </tr><tr>
      <td>receipttext</td>
      <td><img src="src/lib/svg/linear/receipttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receipttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receipttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receipttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receipttext.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receipttext.svg" height="60px"></td>
    </tr><tr>
      <td>receipt</td>
      <td><img src="src/lib/svg/linear/receipt.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receipt.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receipt.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receipt.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receipt.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receipt.svg" height="60px"></td>
    </tr><tr>
      <td>receivesquare2</td>
      <td><img src="src/lib/svg/linear/receivesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receivesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receivesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receivesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receivesquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receivesquare2.svg" height="60px"></td>
    </tr><tr>
      <td>receivesquare</td>
      <td><img src="src/lib/svg/linear/receivesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/receivesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/receivesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/receivesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/receivesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/receivesquare.svg" height="60px"></td>
    </tr><tr>
      <td>received</td>
      <td><img src="src/lib/svg/linear/received.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/received.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/received.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/received.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/received.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/received.svg" height="60px"></td>
    </tr><tr>
      <td>recordcircle</td>
      <td><img src="src/lib/svg/linear/recordcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/recordcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/recordcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/recordcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/recordcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/recordcircle.svg" height="60px"></td>
    </tr><tr>
      <td>record</td>
      <td><img src="src/lib/svg/linear/record.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/record.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/record.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/record.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/record.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/record.svg" height="60px"></td>
    </tr><tr>
      <td>recoveryconvert</td>
      <td><img src="src/lib/svg/linear/recoveryconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/recoveryconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/recoveryconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/recoveryconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/recoveryconvert.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/recoveryconvert.svg" height="60px"></td>
    </tr><tr>
      <td>redo</td>
      <td><img src="src/lib/svg/linear/redo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/redo.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/redo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/redo.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/redo.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/redo.svg" height="60px"></td>
    </tr><tr>
      <td>refresh2</td>
      <td><img src="src/lib/svg/linear/refresh2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refresh2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refresh2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refresh2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refresh2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refresh2.svg" height="60px"></td>
    </tr><tr>
      <td>refreshcircle</td>
      <td><img src="src/lib/svg/linear/refreshcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refreshcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refreshcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refreshcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refreshcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refreshcircle.svg" height="60px"></td>
    </tr><tr>
      <td>refreshleftsquare</td>
      <td><img src="src/lib/svg/linear/refreshleftsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refreshleftsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refreshleftsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refreshleftsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refreshleftsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refreshleftsquare.svg" height="60px"></td>
    </tr><tr>
      <td>refreshrightsquare</td>
      <td><img src="src/lib/svg/linear/refreshrightsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refreshrightsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refreshrightsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refreshrightsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refreshrightsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refreshrightsquare.svg" height="60px"></td>
    </tr><tr>
      <td>refreshsquare2</td>
      <td><img src="src/lib/svg/linear/refreshsquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refreshsquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refreshsquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refreshsquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refreshsquare2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refreshsquare2.svg" height="60px"></td>
    </tr><tr>
      <td>refresh</td>
      <td><img src="src/lib/svg/linear/refresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/refresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/refresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/refresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/refresh.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/refresh.svg" height="60px"></td>
    </tr><tr>
      <td>repeatcircle</td>
      <td><img src="src/lib/svg/linear/repeatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/repeatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/repeatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/repeatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/repeatcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/repeatcircle.svg" height="60px"></td>
    </tr><tr>
      <td>repeat</td>
      <td><img src="src/lib/svg/linear/repeat.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/repeat.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/repeat.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/repeat.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/repeat.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/repeat.svg" height="60px"></td>
    </tr><tr>
      <td>repeatemusic</td>
      <td><img src="src/lib/svg/linear/repeatemusic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/repeatemusic.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/repeatemusic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/repeatemusic.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/repeatemusic.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/repeatemusic.svg" height="60px"></td>
    </tr><tr>
      <td>repeateone</td>
      <td><img src="src/lib/svg/linear/repeateone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/repeateone.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/repeateone.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/repeateone.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/repeateone.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/repeateone.svg" height="60px"></td>
    </tr><tr>
      <td>reserve</td>
      <td><img src="src/lib/svg/linear/reserve.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/reserve.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/reserve.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/reserve.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/reserve.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/reserve.svg" height="60px"></td>
    </tr><tr>
      <td>rotate3d</td>
      <td><img src="src/lib/svg/linear/rotate3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rotate3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rotate3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rotate3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rotate3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rotate3d.svg" height="60px"></td>
    </tr><tr>
      <td>rotateleft1</td>
      <td><img src="src/lib/svg/linear/rotateleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rotateleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rotateleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rotateleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rotateleft1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rotateleft1.svg" height="60px"></td>
    </tr><tr>
      <td>rotateleft</td>
      <td><img src="src/lib/svg/linear/rotateleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rotateleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rotateleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rotateleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rotateleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rotateleft.svg" height="60px"></td>
    </tr><tr>
      <td>rotateright1</td>
      <td><img src="src/lib/svg/linear/rotateright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rotateright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rotateright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rotateright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rotateright1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rotateright1.svg" height="60px"></td>
    </tr><tr>
      <td>rotateright</td>
      <td><img src="src/lib/svg/linear/rotateright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rotateright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rotateright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rotateright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rotateright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rotateright.svg" height="60px"></td>
    </tr><tr>
      <td>routesquare</td>
      <td><img src="src/lib/svg/linear/routesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/routesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/routesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/routesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/routesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/routesquare.svg" height="60px"></td>
    </tr><tr>
      <td>routing2</td>
      <td><img src="src/lib/svg/linear/routing2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/routing2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/routing2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/routing2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/routing2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/routing2.svg" height="60px"></td>
    </tr><tr>
      <td>routing</td>
      <td><img src="src/lib/svg/linear/routing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/routing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/routing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/routing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/routing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/routing.svg" height="60px"></td>
    </tr><tr>
      <td>rowhorizontal</td>
      <td><img src="src/lib/svg/linear/rowhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rowhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rowhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rowhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rowhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rowhorizontal.svg" height="60px"></td>
    </tr><tr>
      <td>rowvertical</td>
      <td><img src="src/lib/svg/linear/rowvertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rowvertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rowvertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rowvertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rowvertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rowvertical.svg" height="60px"></td>
    </tr><tr>
      <td>rulerpen</td>
      <td><img src="src/lib/svg/linear/rulerpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/rulerpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/rulerpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/rulerpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/rulerpen.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/rulerpen.svg" height="60px"></td>
    </tr><tr>
      <td>ruler</td>
      <td><img src="src/lib/svg/linear/ruler.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ruler.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ruler.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ruler.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ruler.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ruler.svg" height="60px"></td>
    </tr><tr>
      <td>safehome</td>
      <td><img src="src/lib/svg/linear/safehome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/safehome.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/safehome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/safehome.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/safehome.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/safehome.svg" height="60px"></td>
    </tr><tr>
      <td>sagittarius</td>
      <td><img src="src/lib/svg/linear/sagittarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sagittarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sagittarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sagittarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sagittarius.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sagittarius.svg" height="60px"></td>
    </tr><tr>
      <td>save2</td>
      <td><img src="src/lib/svg/linear/save2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/save2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/save2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/save2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/save2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/save2.svg" height="60px"></td>
    </tr><tr>
      <td>saveadd</td>
      <td><img src="src/lib/svg/linear/saveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/saveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/saveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/saveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/saveadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/saveadd.svg" height="60px"></td>
    </tr><tr>
      <td>saveminus</td>
      <td><img src="src/lib/svg/linear/saveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/saveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/saveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/saveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/saveminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/saveminus.svg" height="60px"></td>
    </tr><tr>
      <td>saveremove</td>
      <td><img src="src/lib/svg/linear/saveremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/saveremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/saveremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/saveremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/saveremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/saveremove.svg" height="60px"></td>
    </tr><tr>
      <td>scanbarcode</td>
      <td><img src="src/lib/svg/linear/scanbarcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scanbarcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scanbarcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scanbarcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scanbarcode.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scanbarcode.svg" height="60px"></td>
    </tr><tr>
      <td>scan</td>
      <td><img src="src/lib/svg/linear/scan.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scan.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scan.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scan.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scan.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scan.svg" height="60px"></td>
    </tr><tr>
      <td>scanner</td>
      <td><img src="src/lib/svg/linear/scanner.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scanner.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scanner.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scanner.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scanner.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scanner.svg" height="60px"></td>
    </tr><tr>
      <td>scanning</td>
      <td><img src="src/lib/svg/linear/scanning.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scanning.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scanning.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scanning.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scanning.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scanning.svg" height="60px"></td>
    </tr><tr>
      <td>scissor1</td>
      <td><img src="src/lib/svg/linear/scissor1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scissor1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scissor1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scissor1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scissor1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scissor1.svg" height="60px"></td>
    </tr><tr>
      <td>scissor</td>
      <td><img src="src/lib/svg/linear/scissor.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scissor.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scissor.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scissor.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scissor.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scissor.svg" height="60px"></td>
    </tr><tr>
      <td>screenmirroring</td>
      <td><img src="src/lib/svg/linear/screenmirroring.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/screenmirroring.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/screenmirroring.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/screenmirroring.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/screenmirroring.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/screenmirroring.svg" height="60px"></td>
    </tr><tr>
      <td>scroll</td>
      <td><img src="src/lib/svg/linear/scroll.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/scroll.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/scroll.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/scroll.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/scroll.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/scroll.svg" height="60px"></td>
    </tr><tr>
      <td>searchfavorite1</td>
      <td><img src="src/lib/svg/linear/searchfavorite1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchfavorite1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchfavorite1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchfavorite1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchfavorite1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchfavorite1.svg" height="60px"></td>
    </tr><tr>
      <td>searchfavorite</td>
      <td><img src="src/lib/svg/linear/searchfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchfavorite.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchfavorite.svg" height="60px"></td>
    </tr><tr>
      <td>searchnormal1</td>
      <td><img src="src/lib/svg/linear/searchnormal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchnormal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchnormal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchnormal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchnormal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchnormal1.svg" height="60px"></td>
    </tr><tr>
      <td>searchnormal</td>
      <td><img src="src/lib/svg/linear/searchnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchnormal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchnormal.svg" height="60px"></td>
    </tr><tr>
      <td>searchstatus1</td>
      <td><img src="src/lib/svg/linear/searchstatus1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchstatus1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchstatus1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchstatus1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchstatus1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchstatus1.svg" height="60px"></td>
    </tr><tr>
      <td>searchstatus</td>
      <td><img src="src/lib/svg/linear/searchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchstatus.svg" height="60px"></td>
    </tr><tr>
      <td>searchzoomin1</td>
      <td><img src="src/lib/svg/linear/searchzoomin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchzoomin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchzoomin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchzoomin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchzoomin1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchzoomin1.svg" height="60px"></td>
    </tr><tr>
      <td>searchzoomin</td>
      <td><img src="src/lib/svg/linear/searchzoomin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchzoomin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchzoomin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchzoomin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchzoomin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchzoomin.svg" height="60px"></td>
    </tr><tr>
      <td>searchzoomout1</td>
      <td><img src="src/lib/svg/linear/searchzoomout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchzoomout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchzoomout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchzoomout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchzoomout1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchzoomout1.svg" height="60px"></td>
    </tr><tr>
      <td>searchzoomout</td>
      <td><img src="src/lib/svg/linear/searchzoomout.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/searchzoomout.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/searchzoomout.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/searchzoomout.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/searchzoomout.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/searchzoomout.svg" height="60px"></td>
    </tr><tr>
      <td>securitycard</td>
      <td><img src="src/lib/svg/linear/securitycard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/securitycard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/securitycard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/securitycard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/securitycard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/securitycard.svg" height="60px"></td>
    </tr><tr>
      <td>securitysafe</td>
      <td><img src="src/lib/svg/linear/securitysafe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/securitysafe.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/securitysafe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/securitysafe.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/securitysafe.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/securitysafe.svg" height="60px"></td>
    </tr><tr>
      <td>securitytime</td>
      <td><img src="src/lib/svg/linear/securitytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/securitytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/securitytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/securitytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/securitytime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/securitytime.svg" height="60px"></td>
    </tr><tr>
      <td>securityuser</td>
      <td><img src="src/lib/svg/linear/securityuser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/securityuser.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/securityuser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/securityuser.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/securityuser.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/securityuser.svg" height="60px"></td>
    </tr><tr>
      <td>security</td>
      <td><img src="src/lib/svg/linear/security.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/security.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/security.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/security.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/security.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/security.svg" height="60px"></td>
    </tr><tr>
      <td>send1</td>
      <td><img src="src/lib/svg/linear/send1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/send1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/send1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/send1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/send1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/send1.svg" height="60px"></td>
    </tr><tr>
      <td>send2</td>
      <td><img src="src/lib/svg/linear/send2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/send2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/send2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/send2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/send2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/send2.svg" height="60px"></td>
    </tr><tr>
      <td>sendsqaure2</td>
      <td><img src="src/lib/svg/linear/sendsqaure2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sendsqaure2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sendsqaure2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sendsqaure2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sendsqaure2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sendsqaure2.svg" height="60px"></td>
    </tr><tr>
      <td>sendsquare</td>
      <td><img src="src/lib/svg/linear/sendsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sendsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sendsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sendsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sendsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sendsquare.svg" height="60px"></td>
    </tr><tr>
      <td>send</td>
      <td><img src="src/lib/svg/linear/send.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/send.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/send.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/send.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/send.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/send.svg" height="60px"></td>
    </tr><tr>
      <td>setting2</td>
      <td><img src="src/lib/svg/linear/setting2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/setting2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/setting2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/setting2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/setting2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/setting2.svg" height="60px"></td>
    </tr><tr>
      <td>setting3</td>
      <td><img src="src/lib/svg/linear/setting3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/setting3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/setting3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/setting3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/setting3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/setting3.svg" height="60px"></td>
    </tr><tr>
      <td>setting4</td>
      <td><img src="src/lib/svg/linear/setting4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/setting4.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/setting4.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/setting4.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/setting4.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/setting4.svg" height="60px"></td>
    </tr><tr>
      <td>setting5</td>
      <td><img src="src/lib/svg/linear/setting5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/setting5.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/setting5.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/setting5.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/setting5.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/setting5.svg" height="60px"></td>
    </tr><tr>
      <td>setting</td>
      <td><img src="src/lib/svg/linear/setting.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/setting.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/setting.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/setting.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/setting.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/setting.svg" height="60px"></td>
    </tr><tr>
      <td>settings</td>
      <td><img src="src/lib/svg/linear/settings.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/settings.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/settings.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/settings.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/settings.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/settings.svg" height="60px"></td>
    </tr><tr>
      <td>shapes1</td>
      <td><img src="src/lib/svg/linear/shapes1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shapes1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shapes1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shapes1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shapes1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shapes1.svg" height="60px"></td>
    </tr><tr>
      <td>shapes</td>
      <td><img src="src/lib/svg/linear/shapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shapes.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shapes.svg" height="60px"></td>
    </tr><tr>
      <td>share</td>
      <td><img src="src/lib/svg/linear/share.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/share.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/share.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/share.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/share.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/share.svg" height="60px"></td>
    </tr><tr>
      <td>shieldcross</td>
      <td><img src="src/lib/svg/linear/shieldcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shieldcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shieldcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shieldcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shieldcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shieldcross.svg" height="60px"></td>
    </tr><tr>
      <td>shieldsearch</td>
      <td><img src="src/lib/svg/linear/shieldsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shieldsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shieldsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shieldsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shieldsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shieldsearch.svg" height="60px"></td>
    </tr><tr>
      <td>shieldsecurity</td>
      <td><img src="src/lib/svg/linear/shieldsecurity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shieldsecurity.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shieldsecurity.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shieldsecurity.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shieldsecurity.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shieldsecurity.svg" height="60px"></td>
    </tr><tr>
      <td>shieldslash</td>
      <td><img src="src/lib/svg/linear/shieldslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shieldslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shieldslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shieldslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shieldslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shieldslash.svg" height="60px"></td>
    </tr><tr>
      <td>shieldtick</td>
      <td><img src="src/lib/svg/linear/shieldtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shieldtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shieldtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shieldtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shieldtick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shieldtick.svg" height="60px"></td>
    </tr><tr>
      <td>shield</td>
      <td><img src="src/lib/svg/linear/shield.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shield.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shield.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shield.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shield.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shield.svg" height="60px"></td>
    </tr><tr>
      <td>ship</td>
      <td><img src="src/lib/svg/linear/ship.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ship.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ship.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ship.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ship.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ship.svg" height="60px"></td>
    </tr><tr>
      <td>shopadd</td>
      <td><img src="src/lib/svg/linear/shopadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shopadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shopadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shopadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shopadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shopadd.svg" height="60px"></td>
    </tr><tr>
      <td>shopremove</td>
      <td><img src="src/lib/svg/linear/shopremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shopremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shopremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shopremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shopremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shopremove.svg" height="60px"></td>
    </tr><tr>
      <td>shop</td>
      <td><img src="src/lib/svg/linear/shop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shop.svg" height="60px"></td>
    </tr><tr>
      <td>shoppingbag</td>
      <td><img src="src/lib/svg/linear/shoppingbag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shoppingbag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shoppingbag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shoppingbag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shoppingbag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shoppingbag.svg" height="60px"></td>
    </tr><tr>
      <td>shoppingcart</td>
      <td><img src="src/lib/svg/linear/shoppingcart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shoppingcart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shoppingcart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shoppingcart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shoppingcart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shoppingcart.svg" height="60px"></td>
    </tr><tr>
      <td>shuffle</td>
      <td><img src="src/lib/svg/linear/shuffle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/shuffle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/shuffle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/shuffle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/shuffle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/shuffle.svg" height="60px"></td>
    </tr><tr>
      <td>siacoin</td>
      <td><img src="src/lib/svg/linear/siacoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/siacoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/siacoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/siacoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/siacoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/siacoin.svg" height="60px"></td>
    </tr><tr>
      <td>sidebarbottom</td>
      <td><img src="src/lib/svg/linear/sidebarbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sidebarbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sidebarbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sidebarbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sidebarbottom.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sidebarbottom.svg" height="60px"></td>
    </tr><tr>
      <td>sidebarleft</td>
      <td><img src="src/lib/svg/linear/sidebarleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sidebarleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sidebarleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sidebarleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sidebarleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sidebarleft.svg" height="60px"></td>
    </tr><tr>
      <td>sidebarright</td>
      <td><img src="src/lib/svg/linear/sidebarright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sidebarright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sidebarright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sidebarright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sidebarright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sidebarright.svg" height="60px"></td>
    </tr><tr>
      <td>sidebartop</td>
      <td><img src="src/lib/svg/linear/sidebartop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sidebartop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sidebartop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sidebartop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sidebartop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sidebartop.svg" height="60px"></td>
    </tr><tr>
      <td>signpost</td>
      <td><img src="src/lib/svg/linear/signpost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/signpost.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/signpost.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/signpost.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/signpost.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/signpost.svg" height="60px"></td>
    </tr><tr>
      <td>simcard1</td>
      <td><img src="src/lib/svg/linear/simcard1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/simcard1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/simcard1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/simcard1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/simcard1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/simcard1.svg" height="60px"></td>
    </tr><tr>
      <td>simcard2</td>
      <td><img src="src/lib/svg/linear/simcard2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/simcard2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/simcard2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/simcard2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/simcard2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/simcard2.svg" height="60px"></td>
    </tr><tr>
      <td>simcard</td>
      <td><img src="src/lib/svg/linear/simcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/simcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/simcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/simcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/simcard.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/simcard.svg" height="60px"></td>
    </tr><tr>
      <td>size</td>
      <td><img src="src/lib/svg/linear/size.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/size.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/size.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/size.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/size.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/size.svg" height="60px"></td>
    </tr><tr>
      <td>slack</td>
      <td><img src="src/lib/svg/linear/slack.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/slack.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/slack.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/slack.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/slack.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/slack.svg" height="60px"></td>
    </tr><tr>
      <td>slash</td>
      <td><img src="src/lib/svg/linear/slash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/slash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/slash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/slash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/slash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/slash.svg" height="60px"></td>
    </tr><tr>
      <td>sliderhorizontal1</td>
      <td><img src="src/lib/svg/linear/sliderhorizontal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sliderhorizontal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sliderhorizontal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sliderhorizontal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sliderhorizontal1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sliderhorizontal1.svg" height="60px"></td>
    </tr><tr>
      <td>sliderhorizontal</td>
      <td><img src="src/lib/svg/linear/sliderhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sliderhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sliderhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sliderhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sliderhorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sliderhorizontal.svg" height="60px"></td>
    </tr><tr>
      <td>slidervertical1</td>
      <td><img src="src/lib/svg/linear/slidervertical1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/slidervertical1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/slidervertical1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/slidervertical1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/slidervertical1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/slidervertical1.svg" height="60px"></td>
    </tr><tr>
      <td>slidervertical</td>
      <td><img src="src/lib/svg/linear/slidervertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/slidervertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/slidervertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/slidervertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/slidervertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/slidervertical.svg" height="60px"></td>
    </tr><tr>
      <td>slider</td>
      <td><img src="src/lib/svg/linear/slider.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/slider.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/slider.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/slider.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/slider.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/slider.svg" height="60px"></td>
    </tr><tr>
      <td>smallcaps</td>
      <td><img src="src/lib/svg/linear/smallcaps.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smallcaps.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smallcaps.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smallcaps.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smallcaps.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smallcaps.svg" height="60px"></td>
    </tr><tr>
      <td>smartcar</td>
      <td><img src="src/lib/svg/linear/smartcar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smartcar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smartcar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smartcar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smartcar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smartcar.svg" height="60px"></td>
    </tr><tr>
      <td>smarthome</td>
      <td><img src="src/lib/svg/linear/smarthome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smarthome.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smarthome.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smarthome.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smarthome.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smarthome.svg" height="60px"></td>
    </tr><tr>
      <td>smileys</td>
      <td><img src="src/lib/svg/linear/smileys.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smileys.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smileys.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smileys.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smileys.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smileys.svg" height="60px"></td>
    </tr><tr>
      <td>smsedit</td>
      <td><img src="src/lib/svg/linear/smsedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smsedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smsedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smsedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smsedit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smsedit.svg" height="60px"></td>
    </tr><tr>
      <td>smsnotification</td>
      <td><img src="src/lib/svg/linear/smsnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smsnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smsnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smsnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smsnotification.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smsnotification.svg" height="60px"></td>
    </tr><tr>
      <td>smssearch</td>
      <td><img src="src/lib/svg/linear/smssearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smssearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smssearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smssearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smssearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smssearch.svg" height="60px"></td>
    </tr><tr>
      <td>smsstar</td>
      <td><img src="src/lib/svg/linear/smsstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smsstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smsstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smsstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smsstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smsstar.svg" height="60px"></td>
    </tr><tr>
      <td>smstracking</td>
      <td><img src="src/lib/svg/linear/smstracking.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/smstracking.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/smstracking.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/smstracking.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/smstracking.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/smstracking.svg" height="60px"></td>
    </tr><tr>
      <td>sms</td>
      <td><img src="src/lib/svg/linear/sms.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sms.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sms.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sms.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sms.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sms.svg" height="60px"></td>
    </tr><tr>
      <td>snapchat</td>
      <td><img src="src/lib/svg/linear/snapchat.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/snapchat.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/snapchat.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/snapchat.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/snapchat.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/snapchat.svg" height="60px"></td>
    </tr><tr>
      <td>solana</td>
      <td><img src="src/lib/svg/linear/solana.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/solana.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/solana.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/solana.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/solana.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/solana.svg" height="60px"></td>
    </tr><tr>
      <td>sort</td>
      <td><img src="src/lib/svg/linear/sort.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sort.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sort.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sort.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sort.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sort.svg" height="60px"></td>
    </tr><tr>
      <td>sound</td>
      <td><img src="src/lib/svg/linear/sound.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sound.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sound.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sound.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sound.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sound.svg" height="60px"></td>
    </tr><tr>
      <td>speaker</td>
      <td><img src="src/lib/svg/linear/speaker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/speaker.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/speaker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/speaker.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/speaker.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/speaker.svg" height="60px"></td>
    </tr><tr>
      <td>speedometer</td>
      <td><img src="src/lib/svg/linear/speedometer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/speedometer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/speedometer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/speedometer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/speedometer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/speedometer.svg" height="60px"></td>
    </tr><tr>
      <td>spotify</td>
      <td><img src="src/lib/svg/linear/spotify.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/spotify.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/spotify.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/spotify.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/spotify.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/spotify.svg" height="60px"></td>
    </tr><tr>
      <td>square3d</td>
      <td><img src="src/lib/svg/linear/square3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/square3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/square3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/square3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/square3d.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/square3d.svg" height="60px"></td>
    </tr><tr>
      <td>squares3</td>
      <td><img src="src/lib/svg/linear/squares3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/squares3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/squares3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/squares3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/squares3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/squares3.svg" height="60px"></td>
    </tr><tr>
      <td>stacks</td>
      <td><img src="src/lib/svg/linear/stacks.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/stacks.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/stacks.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/stacks.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/stacks.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/stacks.svg" height="60px"></td>
    </tr><tr>
      <td>star1</td>
      <td><img src="src/lib/svg/linear/star1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/star1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/star1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/star1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/star1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/star1.svg" height="60px"></td>
    </tr><tr>
      <td>starslash</td>
      <td><img src="src/lib/svg/linear/starslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/starslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/starslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/starslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/starslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/starslash.svg" height="60px"></td>
    </tr><tr>
      <td>star</td>
      <td><img src="src/lib/svg/linear/star.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/star.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/star.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/star.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/star.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/star.svg" height="60px"></td>
    </tr><tr>
      <td>statusup</td>
      <td><img src="src/lib/svg/linear/statusup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/statusup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/statusup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/statusup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/statusup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/statusup.svg" height="60px"></td>
    </tr><tr>
      <td>status</td>
      <td><img src="src/lib/svg/linear/status.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/status.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/status.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/status.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/status.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/status.svg" height="60px"></td>
    </tr><tr>
      <td>stellar</td>
      <td><img src="src/lib/svg/linear/stellar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/stellar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/stellar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/stellar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/stellar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/stellar.svg" height="60px"></td>
    </tr><tr>
      <td>sticker</td>
      <td><img src="src/lib/svg/linear/sticker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sticker.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sticker.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sticker.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sticker.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sticker.svg" height="60px"></td>
    </tr><tr>
      <td>stickynote</td>
      <td><img src="src/lib/svg/linear/stickynote.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/stickynote.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/stickynote.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/stickynote.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/stickynote.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/stickynote.svg" height="60px"></td>
    </tr><tr>
      <td>stopcircle</td>
      <td><img src="src/lib/svg/linear/stopcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/stopcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/stopcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/stopcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/stopcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/stopcircle.svg" height="60px"></td>
    </tr><tr>
      <td>stop</td>
      <td><img src="src/lib/svg/linear/stop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/stop.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/stop.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/stop.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/stop.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/stop.svg" height="60px"></td>
    </tr><tr>
      <td>story</td>
      <td><img src="src/lib/svg/linear/story.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/story.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/story.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/story.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/story.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/story.svg" height="60px"></td>
    </tr><tr>
      <td>strongbox2</td>
      <td><img src="src/lib/svg/linear/strongbox2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/strongbox2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/strongbox2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/strongbox2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/strongbox2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/strongbox2.svg" height="60px"></td>
    </tr><tr>
      <td>strongbox</td>
      <td><img src="src/lib/svg/linear/strongbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/strongbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/strongbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/strongbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/strongbox.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/strongbox.svg" height="60px"></td>
    </tr><tr>
      <td>subtitle</td>
      <td><img src="src/lib/svg/linear/subtitle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/subtitle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/subtitle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/subtitle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/subtitle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/subtitle.svg" height="60px"></td>
    </tr><tr>
      <td>sun1</td>
      <td><img src="src/lib/svg/linear/sun1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sun1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sun1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sun1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sun1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sun1.svg" height="60px"></td>
    </tr><tr>
      <td>sunfog</td>
      <td><img src="src/lib/svg/linear/sunfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sunfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sunfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sunfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sunfog.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sunfog.svg" height="60px"></td>
    </tr><tr>
      <td>sun</td>
      <td><img src="src/lib/svg/linear/sun.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/sun.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/sun.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/sun.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/sun.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/sun.svg" height="60px"></td>
    </tr><tr>
      <td>support24</td>
      <td><img src="src/lib/svg/linear/support24.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/support24.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/support24.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/support24.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/support24.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/support24.svg" height="60px"></td>
    </tr><tr>
      <td>tag2</td>
      <td><img src="src/lib/svg/linear/tag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tag2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tag2.svg" height="60px"></td>
    </tr><tr>
      <td>tagcross</td>
      <td><img src="src/lib/svg/linear/tagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tagcross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tagcross.svg" height="60px"></td>
    </tr><tr>
      <td>tagright</td>
      <td><img src="src/lib/svg/linear/tagright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tagright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tagright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tagright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tagright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tagright.svg" height="60px"></td>
    </tr><tr>
      <td>taguser</td>
      <td><img src="src/lib/svg/linear/taguser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/taguser.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/taguser.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/taguser.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/taguser.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/taguser.svg" height="60px"></td>
    </tr><tr>
      <td>tag</td>
      <td><img src="src/lib/svg/linear/tag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tag.svg" height="60px"></td>
    </tr><tr>
      <td>tasksquare</td>
      <td><img src="src/lib/svg/linear/tasksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tasksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tasksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tasksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tasksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tasksquare.svg" height="60px"></td>
    </tr><tr>
      <td>task</td>
      <td><img src="src/lib/svg/linear/task.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/task.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/task.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/task.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/task.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/task.svg" height="60px"></td>
    </tr><tr>
      <td>teacher</td>
      <td><img src="src/lib/svg/linear/teacher.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/teacher.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/teacher.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/teacher.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/teacher.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/teacher.svg" height="60px"></td>
    </tr><tr>
      <td>tenx</td>
      <td><img src="src/lib/svg/linear/tenx.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tenx.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tenx.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tenx.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tenx.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tenx.svg" height="60px"></td>
    </tr><tr>
      <td>tether</td>
      <td><img src="src/lib/svg/linear/tether.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tether.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tether.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tether.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tether.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tether.svg" height="60px"></td>
    </tr><tr>
      <td>textblock</td>
      <td><img src="src/lib/svg/linear/textblock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textblock.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textblock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textblock.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textblock.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textblock.svg" height="60px"></td>
    </tr><tr>
      <td>textbold</td>
      <td><img src="src/lib/svg/linear/textbold.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textbold.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textbold.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textbold.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textbold.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textbold.svg" height="60px"></td>
    </tr><tr>
      <td>textitalic</td>
      <td><img src="src/lib/svg/linear/textitalic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textitalic.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textitalic.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textitalic.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textitalic.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textitalic.svg" height="60px"></td>
    </tr><tr>
      <td>textunderline</td>
      <td><img src="src/lib/svg/linear/textunderline.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textunderline.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textunderline.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textunderline.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textunderline.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textunderline.svg" height="60px"></td>
    </tr><tr>
      <td>text</td>
      <td><img src="src/lib/svg/linear/text.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/text.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/text.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/text.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/text.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/text.svg" height="60px"></td>
    </tr><tr>
      <td>textaligncenter</td>
      <td><img src="src/lib/svg/linear/textaligncenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textaligncenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textaligncenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textaligncenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textaligncenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textaligncenter.svg" height="60px"></td>
    </tr><tr>
      <td>textalignjustifycenter</td>
      <td><img src="src/lib/svg/linear/textalignjustifycenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textalignjustifycenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textalignjustifycenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textalignjustifycenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textalignjustifycenter.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textalignjustifycenter.svg" height="60px"></td>
    </tr><tr>
      <td>textalignjustifyleft</td>
      <td><img src="src/lib/svg/linear/textalignjustifyleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textalignjustifyleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textalignjustifyleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textalignjustifyleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textalignjustifyleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textalignjustifyleft.svg" height="60px"></td>
    </tr><tr>
      <td>textalignjustifyright</td>
      <td><img src="src/lib/svg/linear/textalignjustifyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textalignjustifyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textalignjustifyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textalignjustifyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textalignjustifyright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textalignjustifyright.svg" height="60px"></td>
    </tr><tr>
      <td>textalignleft</td>
      <td><img src="src/lib/svg/linear/textalignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textalignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textalignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textalignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textalignleft.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textalignleft.svg" height="60px"></td>
    </tr><tr>
      <td>textalignright</td>
      <td><img src="src/lib/svg/linear/textalignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/textalignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/textalignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/textalignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/textalignright.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/textalignright.svg" height="60px"></td>
    </tr><tr>
      <td>thegraph</td>
      <td><img src="src/lib/svg/linear/thegraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/thegraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/thegraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/thegraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/thegraph.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/thegraph.svg" height="60px"></td>
    </tr><tr>
      <td>theta</td>
      <td><img src="src/lib/svg/linear/theta.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/theta.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/theta.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/theta.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/theta.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/theta.svg" height="60px"></td>
    </tr><tr>
      <td>thorchain</td>
      <td><img src="src/lib/svg/linear/thorchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/thorchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/thorchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/thorchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/thorchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/thorchain.svg" height="60px"></td>
    </tr><tr>
      <td>tickcircle</td>
      <td><img src="src/lib/svg/linear/tickcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tickcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tickcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tickcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tickcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tickcircle.svg" height="60px"></td>
    </tr><tr>
      <td>ticksquare</td>
      <td><img src="src/lib/svg/linear/ticksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticksquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticksquare.svg" height="60px"></td>
    </tr><tr>
      <td>ticket2</td>
      <td><img src="src/lib/svg/linear/ticket2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticket2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticket2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticket2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticket2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticket2.svg" height="60px"></td>
    </tr><tr>
      <td>ticketdiscount</td>
      <td><img src="src/lib/svg/linear/ticketdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticketdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticketdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticketdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticketdiscount.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticketdiscount.svg" height="60px"></td>
    </tr><tr>
      <td>ticketexpired</td>
      <td><img src="src/lib/svg/linear/ticketexpired.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticketexpired.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticketexpired.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticketexpired.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticketexpired.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticketexpired.svg" height="60px"></td>
    </tr><tr>
      <td>ticketstar</td>
      <td><img src="src/lib/svg/linear/ticketstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticketstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticketstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticketstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticketstar.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticketstar.svg" height="60px"></td>
    </tr><tr>
      <td>ticket</td>
      <td><img src="src/lib/svg/linear/ticket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ticket.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ticket.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ticket.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ticket.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ticket.svg" height="60px"></td>
    </tr><tr>
      <td>timer1</td>
      <td><img src="src/lib/svg/linear/timer1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/timer1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/timer1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/timer1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/timer1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/timer1.svg" height="60px"></td>
    </tr><tr>
      <td>timerpause</td>
      <td><img src="src/lib/svg/linear/timerpause.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/timerpause.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/timerpause.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/timerpause.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/timerpause.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/timerpause.svg" height="60px"></td>
    </tr><tr>
      <td>timerstart</td>
      <td><img src="src/lib/svg/linear/timerstart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/timerstart.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/timerstart.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/timerstart.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/timerstart.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/timerstart.svg" height="60px"></td>
    </tr><tr>
      <td>timer</td>
      <td><img src="src/lib/svg/linear/timer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/timer.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/timer.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/timer.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/timer.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/timer.svg" height="60px"></td>
    </tr><tr>
      <td>toggleoffcircle</td>
      <td><img src="src/lib/svg/linear/toggleoffcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/toggleoffcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/toggleoffcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/toggleoffcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/toggleoffcircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/toggleoffcircle.svg" height="60px"></td>
    </tr><tr>
      <td>toggleoff</td>
      <td><img src="src/lib/svg/linear/toggleoff.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/toggleoff.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/toggleoff.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/toggleoff.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/toggleoff.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/toggleoff.svg" height="60px"></td>
    </tr><tr>
      <td>toggleoncircle</td>
      <td><img src="src/lib/svg/linear/toggleoncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/toggleoncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/toggleoncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/toggleoncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/toggleoncircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/toggleoncircle.svg" height="60px"></td>
    </tr><tr>
      <td>toggleon</td>
      <td><img src="src/lib/svg/linear/toggleon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/toggleon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/toggleon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/toggleon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/toggleon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/toggleon.svg" height="60px"></td>
    </tr><tr>
      <td>trade</td>
      <td><img src="src/lib/svg/linear/trade.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trade.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trade.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trade.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trade.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trade.svg" height="60px"></td>
    </tr><tr>
      <td>transactionminus</td>
      <td><img src="src/lib/svg/linear/transactionminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/transactionminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/transactionminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/transactionminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/transactionminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/transactionminus.svg" height="60px"></td>
    </tr><tr>
      <td>translate</td>
      <td><img src="src/lib/svg/linear/translate.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/translate.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/translate.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/translate.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/translate.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/translate.svg" height="60px"></td>
    </tr><tr>
      <td>trash</td>
      <td><img src="src/lib/svg/linear/trash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trash.svg" height="60px"></td>
    </tr><tr>
      <td>tree</td>
      <td><img src="src/lib/svg/linear/tree.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/tree.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/tree.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/tree.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/tree.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/tree.svg" height="60px"></td>
    </tr><tr>
      <td>trello</td>
      <td><img src="src/lib/svg/linear/trello.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trello.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trello.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trello.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trello.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trello.svg" height="60px"></td>
    </tr><tr>
      <td>trenddown</td>
      <td><img src="src/lib/svg/linear/trenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trenddown.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trenddown.svg" height="60px"></td>
    </tr><tr>
      <td>trendup</td>
      <td><img src="src/lib/svg/linear/trendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trendup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trendup.svg" height="60px"></td>
    </tr><tr>
      <td>triangle2</td>
      <td><img src="src/lib/svg/linear/triangle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/triangle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/triangle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/triangle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/triangle2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/triangle2.svg" height="60px"></td>
    </tr><tr>
      <td>triangle</td>
      <td><img src="src/lib/svg/linear/triangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/triangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/triangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/triangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/triangle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/triangle.svg" height="60px"></td>
    </tr><tr>
      <td>trontron</td>
      <td><img src="src/lib/svg/linear/trontron.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trontron.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trontron.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trontron.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trontron.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trontron.svg" height="60px"></td>
    </tr><tr>
      <td>truckfast</td>
      <td><img src="src/lib/svg/linear/truckfast.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/truckfast.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/truckfast.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/truckfast.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/truckfast.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/truckfast.svg" height="60px"></td>
    </tr><tr>
      <td>truckremove</td>
      <td><img src="src/lib/svg/linear/truckremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/truckremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/truckremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/truckremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/truckremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/truckremove.svg" height="60px"></td>
    </tr><tr>
      <td>trucktick</td>
      <td><img src="src/lib/svg/linear/trucktick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trucktick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trucktick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trucktick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trucktick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trucktick.svg" height="60px"></td>
    </tr><tr>
      <td>trucktime</td>
      <td><img src="src/lib/svg/linear/trucktime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trucktime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trucktime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trucktime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trucktime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trucktime.svg" height="60px"></td>
    </tr><tr>
      <td>truck</td>
      <td><img src="src/lib/svg/linear/truck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/truck.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/truck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/truck.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/truck.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/truck.svg" height="60px"></td>
    </tr><tr>
      <td>trushsquare</td>
      <td><img src="src/lib/svg/linear/trushsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/trushsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/trushsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/trushsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/trushsquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/trushsquare.svg" height="60px"></td>
    </tr><tr>
      <td>twitch</td>
      <td><img src="src/lib/svg/linear/twitch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/twitch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/twitch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/twitch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/twitch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/twitch.svg" height="60px"></td>
    </tr><tr>
      <td>ui8</td>
      <td><img src="src/lib/svg/linear/ui8.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/ui8.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/ui8.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/ui8.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/ui8.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/ui8.svg" height="60px"></td>
    </tr><tr>
      <td>undo</td>
      <td><img src="src/lib/svg/linear/undo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/undo.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/undo.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/undo.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/undo.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/undo.svg" height="60px"></td>
    </tr><tr>
      <td>unlimited</td>
      <td><img src="src/lib/svg/linear/unlimited.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/unlimited.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/unlimited.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/unlimited.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/unlimited.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/unlimited.svg" height="60px"></td>
    </tr><tr>
      <td>unlock</td>
      <td><img src="src/lib/svg/linear/unlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/unlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/unlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/unlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/unlock.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/unlock.svg" height="60px"></td>
    </tr><tr>
      <td>usdcoin</td>
      <td><img src="src/lib/svg/linear/usdcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usdcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usdcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usdcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usdcoin.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usdcoin.svg" height="60px"></td>
    </tr><tr>
      <td>useradd</td>
      <td><img src="src/lib/svg/linear/useradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/useradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/useradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/useradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/useradd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/useradd.svg" height="60px"></td>
    </tr><tr>
      <td>usercirlceadd</td>
      <td><img src="src/lib/svg/linear/usercirlceadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usercirlceadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usercirlceadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usercirlceadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usercirlceadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usercirlceadd.svg" height="60px"></td>
    </tr><tr>
      <td>useredit</td>
      <td><img src="src/lib/svg/linear/useredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/useredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/useredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/useredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/useredit.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/useredit.svg" height="60px"></td>
    </tr><tr>
      <td>userminus</td>
      <td><img src="src/lib/svg/linear/userminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/userminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/userminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/userminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/userminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/userminus.svg" height="60px"></td>
    </tr><tr>
      <td>useroctagon</td>
      <td><img src="src/lib/svg/linear/useroctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/useroctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/useroctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/useroctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/useroctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/useroctagon.svg" height="60px"></td>
    </tr><tr>
      <td>userremove</td>
      <td><img src="src/lib/svg/linear/userremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/userremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/userremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/userremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/userremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/userremove.svg" height="60px"></td>
    </tr><tr>
      <td>usersearch</td>
      <td><img src="src/lib/svg/linear/usersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usersearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usersearch.svg" height="60px"></td>
    </tr><tr>
      <td>usersquare</td>
      <td><img src="src/lib/svg/linear/usersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usersquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usersquare.svg" height="60px"></td>
    </tr><tr>
      <td>usertag</td>
      <td><img src="src/lib/svg/linear/usertag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usertag.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usertag.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usertag.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usertag.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usertag.svg" height="60px"></td>
    </tr><tr>
      <td>usertick</td>
      <td><img src="src/lib/svg/linear/usertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/usertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/usertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/usertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/usertick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/usertick.svg" height="60px"></td>
    </tr><tr>
      <td>user</td>
      <td><img src="src/lib/svg/linear/user.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/user.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/user.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/user.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/user.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/user.svg" height="60px"></td>
    </tr><tr>
      <td>velas</td>
      <td><img src="src/lib/svg/linear/velas.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/velas.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/velas.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/velas.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/velas.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/velas.svg" height="60px"></td>
    </tr><tr>
      <td>verify</td>
      <td><img src="src/lib/svg/linear/verify.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/verify.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/verify.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/verify.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/verify.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/verify.svg" height="60px"></td>
    </tr><tr>
      <td>vibe</td>
      <td><img src="src/lib/svg/linear/vibe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/vibe.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/vibe.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/vibe.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/vibe.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/vibe.svg" height="60px"></td>
    </tr><tr>
      <td>videoadd</td>
      <td><img src="src/lib/svg/linear/videoadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videoadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videoadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videoadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videoadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videoadd.svg" height="60px"></td>
    </tr><tr>
      <td>videocircle</td>
      <td><img src="src/lib/svg/linear/videocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videocircle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videocircle.svg" height="60px"></td>
    </tr><tr>
      <td>videohorizontal</td>
      <td><img src="src/lib/svg/linear/videohorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videohorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videohorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videohorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videohorizontal.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videohorizontal.svg" height="60px"></td>
    </tr><tr>
      <td>videooctagon</td>
      <td><img src="src/lib/svg/linear/videooctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videooctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videooctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videooctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videooctagon.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videooctagon.svg" height="60px"></td>
    </tr><tr>
      <td>videoplay</td>
      <td><img src="src/lib/svg/linear/videoplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videoplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videoplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videoplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videoplay.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videoplay.svg" height="60px"></td>
    </tr><tr>
      <td>videoremove</td>
      <td><img src="src/lib/svg/linear/videoremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videoremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videoremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videoremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videoremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videoremove.svg" height="60px"></td>
    </tr><tr>
      <td>videoslash</td>
      <td><img src="src/lib/svg/linear/videoslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videoslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videoslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videoslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videoslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videoslash.svg" height="60px"></td>
    </tr><tr>
      <td>videosquare</td>
      <td><img src="src/lib/svg/linear/videosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videosquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videosquare.svg" height="60px"></td>
    </tr><tr>
      <td>videotick</td>
      <td><img src="src/lib/svg/linear/videotick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videotick.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videotick.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videotick.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videotick.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videotick.svg" height="60px"></td>
    </tr><tr>
      <td>videotime</td>
      <td><img src="src/lib/svg/linear/videotime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videotime.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videotime.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videotime.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videotime.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videotime.svg" height="60px"></td>
    </tr><tr>
      <td>videovertical</td>
      <td><img src="src/lib/svg/linear/videovertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/videovertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/videovertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/videovertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/videovertical.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/videovertical.svg" height="60px"></td>
    </tr><tr>
      <td>video</td>
      <td><img src="src/lib/svg/linear/video.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/video.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/video.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/video.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/video.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/video.svg" height="60px"></td>
    </tr><tr>
      <td>voicecricle</td>
      <td><img src="src/lib/svg/linear/voicecricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/voicecricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/voicecricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/voicecricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/voicecricle.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/voicecricle.svg" height="60px"></td>
    </tr><tr>
      <td>voicesquare</td>
      <td><img src="src/lib/svg/linear/voicesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/voicesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/voicesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/voicesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/voicesquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/voicesquare.svg" height="60px"></td>
    </tr><tr>
      <td>volumecross</td>
      <td><img src="src/lib/svg/linear/volumecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumecross.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumecross.svg" height="60px"></td>
    </tr><tr>
      <td>volumehigh</td>
      <td><img src="src/lib/svg/linear/volumehigh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumehigh.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumehigh.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumehigh.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumehigh.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumehigh.svg" height="60px"></td>
    </tr><tr>
      <td>volumelow1</td>
      <td><img src="src/lib/svg/linear/volumelow1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumelow1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumelow1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumelow1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumelow1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumelow1.svg" height="60px"></td>
    </tr><tr>
      <td>volumelow</td>
      <td><img src="src/lib/svg/linear/volumelow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumelow.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumelow.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumelow.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumelow.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumelow.svg" height="60px"></td>
    </tr><tr>
      <td>volumemute</td>
      <td><img src="src/lib/svg/linear/volumemute.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumemute.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumemute.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumemute.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumemute.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumemute.svg" height="60px"></td>
    </tr><tr>
      <td>volumeslash</td>
      <td><img src="src/lib/svg/linear/volumeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumeslash.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumeslash.svg" height="60px"></td>
    </tr><tr>
      <td>volumeup</td>
      <td><img src="src/lib/svg/linear/volumeup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volumeup.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volumeup.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volumeup.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volumeup.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volumeup.svg" height="60px"></td>
    </tr><tr>
      <td>volume</td>
      <td><img src="src/lib/svg/linear/volume.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/volume.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/volume.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/volume.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/volume.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/volume.svg" height="60px"></td>
    </tr><tr>
      <td>vuesax</td>
      <td><img src="src/lib/svg/linear/vuesax.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/vuesax.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/vuesax.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/vuesax.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/vuesax.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/vuesax.svg" height="60px"></td>
    </tr><tr>
      <td>wallet1</td>
      <td><img src="src/lib/svg/linear/wallet1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wallet1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wallet1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wallet1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wallet1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wallet1.svg" height="60px"></td>
    </tr><tr>
      <td>wallet2</td>
      <td><img src="src/lib/svg/linear/wallet2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wallet2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wallet2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wallet2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wallet2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wallet2.svg" height="60px"></td>
    </tr><tr>
      <td>wallet3</td>
      <td><img src="src/lib/svg/linear/wallet3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wallet3.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wallet3.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wallet3.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wallet3.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wallet3.svg" height="60px"></td>
    </tr><tr>
      <td>walletadd1</td>
      <td><img src="src/lib/svg/linear/walletadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletadd1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletadd1.svg" height="60px"></td>
    </tr><tr>
      <td>walletadd</td>
      <td><img src="src/lib/svg/linear/walletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletadd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletadd.svg" height="60px"></td>
    </tr><tr>
      <td>walletcheck</td>
      <td><img src="src/lib/svg/linear/walletcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletcheck.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletcheck.svg" height="60px"></td>
    </tr><tr>
      <td>walletminus</td>
      <td><img src="src/lib/svg/linear/walletminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletminus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletminus.svg" height="60px"></td>
    </tr><tr>
      <td>walletmoney</td>
      <td><img src="src/lib/svg/linear/walletmoney.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletmoney.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletmoney.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletmoney.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletmoney.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletmoney.svg" height="60px"></td>
    </tr><tr>
      <td>walletremove</td>
      <td><img src="src/lib/svg/linear/walletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletremove.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletremove.svg" height="60px"></td>
    </tr><tr>
      <td>walletsearch</td>
      <td><img src="src/lib/svg/linear/walletsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/walletsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/walletsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/walletsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/walletsearch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/walletsearch.svg" height="60px"></td>
    </tr><tr>
      <td>wallet</td>
      <td><img src="src/lib/svg/linear/wallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wallet.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wallet.svg" height="60px"></td>
    </tr><tr>
      <td>wanchain1</td>
      <td><img src="src/lib/svg/linear/wanchain1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wanchain1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wanchain1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wanchain1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wanchain1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wanchain1.svg" height="60px"></td>
    </tr><tr>
      <td>wanchain</td>
      <td><img src="src/lib/svg/linear/wanchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wanchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wanchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wanchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wanchain.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wanchain.svg" height="60px"></td>
    </tr><tr>
      <td>warning2</td>
      <td><img src="src/lib/svg/linear/warning2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/warning2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/warning2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/warning2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/warning2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/warning2.svg" height="60px"></td>
    </tr><tr>
      <td>watchstatus</td>
      <td><img src="src/lib/svg/linear/watchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/watchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/watchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/watchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/watchstatus.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/watchstatus.svg" height="60px"></td>
    </tr><tr>
      <td>watch</td>
      <td><img src="src/lib/svg/linear/watch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/watch.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/watch.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/watch.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/watch.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/watch.svg" height="60px"></td>
    </tr><tr>
      <td>weight1</td>
      <td><img src="src/lib/svg/linear/weight1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/weight1.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/weight1.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/weight1.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/weight1.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/weight1.svg" height="60px"></td>
    </tr><tr>
      <td>weight</td>
      <td><img src="src/lib/svg/linear/weight.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/weight.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/weight.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/weight.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/weight.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/weight.svg" height="60px"></td>
    </tr><tr>
      <td>whatsapp</td>
      <td><img src="src/lib/svg/linear/whatsapp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/whatsapp.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/whatsapp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/whatsapp.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/whatsapp.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/whatsapp.svg" height="60px"></td>
    </tr><tr>
      <td>wifisquare</td>
      <td><img src="src/lib/svg/linear/wifisquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wifisquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wifisquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wifisquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wifisquare.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wifisquare.svg" height="60px"></td>
    </tr><tr>
      <td>wifi</td>
      <td><img src="src/lib/svg/linear/wifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wifi.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wifi.svg" height="60px"></td>
    </tr><tr>
      <td>wind2</td>
      <td><img src="src/lib/svg/linear/wind2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wind2.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wind2.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wind2.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wind2.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wind2.svg" height="60px"></td>
    </tr><tr>
      <td>wind</td>
      <td><img src="src/lib/svg/linear/wind.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wind.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wind.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wind.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wind.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wind.svg" height="60px"></td>
    </tr><tr>
      <td>windows</td>
      <td><img src="src/lib/svg/linear/windows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/windows.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/windows.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/windows.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/windows.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/windows.svg" height="60px"></td>
    </tr><tr>
      <td>wing</td>
      <td><img src="src/lib/svg/linear/wing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/wing.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/wing.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/wing.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/wing.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/wing.svg" height="60px"></td>
    </tr><tr>
      <td>woman</td>
      <td><img src="src/lib/svg/linear/woman.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/woman.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/woman.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/woman.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/woman.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/woman.svg" height="60px"></td>
    </tr><tr>
      <td>xd</td>
      <td><img src="src/lib/svg/linear/xd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/xd.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/xd.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/xd.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/xd.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/xd.svg" height="60px"></td>
    </tr><tr>
      <td>xiaomi</td>
      <td><img src="src/lib/svg/linear/xiaomi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/xiaomi.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/xiaomi.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/xiaomi.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/xiaomi.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/xiaomi.svg" height="60px"></td>
    </tr><tr>
      <td>xrp</td>
      <td><img src="src/lib/svg/linear/xrp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/xrp.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/xrp.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/xrp.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/xrp.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/xrp.svg" height="60px"></td>
    </tr><tr>
      <td>youtube</td>
      <td><img src="src/lib/svg/linear/youtube.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/youtube.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/youtube.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/youtube.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/youtube.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/youtube.svg" height="60px"></td>
    </tr><tr>
      <td>zel</td>
      <td><img src="src/lib/svg/linear/zel.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/zel.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/zel.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/zel.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/zel.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/zel.svg" height="60px"></td>
    </tr><tr>
      <td>zoom</td>
      <td><img src="src/lib/svg/linear/zoom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bold/zoom.svg" height="60px"></td>
      <td><img src="src/lib/svg/broken/zoom.svg" height="60px"></td>
      <td><img src="src/lib/svg/bulk/zoom.svg" height="60px"></td>
      <td><img src="src/lib/svg/outline/zoom.svg" height="60px"></td>
      <td><img src="src/lib/svg/twotone/zoom.svg" height="60px"></td>
    </tr></tbody>
</table>

## License

[MIT](LICENSE)
