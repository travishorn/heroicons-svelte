# Heroicons for Svelte

<p align="center">
	Beautiful hand-crafted SVG icons, by the makers of Tailwind CSS, packaged for Svelte.
</p>

<p align="center">
  <a href="https://heroicons.com"><strong>Browse at Heroicons.com &rarr;</strong></a>
</p>

<p align="center">
	<a href="https://github.com/travishorn/heroicons-svelte/tags"><img src="https://img.shields.io/npm/v/heroicons-svelte" alt="Latest Tag"></a>
	<a href="https://github.com/travishorn/heroicons-svelte/blob/master/LICENSE"><img
	src="https://img.shields.io/npm/l/heroicons-svelte" alt="License"></a>
</p>

## Basic Usage

First, install `heroicons-svelte` from npm:

```sh
npm install heroicons-svelte
```

Now each icon can be imported individually as a Svelte component:

```svelte
<script>
	import { BeakerIcon } from 'heroicons-svelte/24/solid';
</script>

<BeakerIcon class="h-6 w-6 text-blue-500" />
```

The 24x24 outline icons can be imported from `heroicons-svelte/24/outline`, the 24x24 solid icons
can be imported from `heroicons-svelte/24/solid`, and the 20x20 solid icons can be imported from
`heroicons-svelte/20/solid`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

Both icon styles are preconfigured to be stylable by setting the `color` CSS property, either
manually or using utility classes like `text-gray-500` in a framework like [Tailwind
CSS](https://tailwindcss.com/).

[Browse the full list of icon names on UNPKG →](https://unpkg.com/browse/heroicons-svelte/dist/24/outline/)

## License

This library is MIT licensed.
