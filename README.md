# Heroicons for Svelte

Beautiful hand-crafted SVG icons, by the makers of Tailwind CSS, packaged for Svelte.

## Usage

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

The 24x24 outline icons can be imported from `herocions-svelte/24/outline`, the 24x24 solid icons
can be imported from `herocions-svelte/24/solid`, and the 20x20 solid icons can be imported from
`herocions-svelte/20/solid`.

Icons use an upper camel case naming convention and are always suffixed with the word `Icon`.

## License

Copyright 2023 Travis Horn

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the “Software”), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute,
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT
NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES
OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.