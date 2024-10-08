# Svelte Unist

Transform [Unist](https://github.com/syntax-tree/unist) into Svelte components.

## Installing

Add the `@accuser/svelte-unist` package dependency to your [Svelte](https://svelte.dev) / [SvelteKit](https://kit.svelte.dev) project:

```sh
npm install --save-dev @accuser/svelte-unist
```

## Usage

### Markdown AST

```svelte
<script>
	import { Unist } from '@accuser/svelte-unist';

	const ast = { type: 'root', children: [{ type: 'text', value: 'Hello, World!' }] };
</script>

<Unist {ast} />
```

## Test

```sh
npm test
```

## License

[MIT](LICENSE)

## Copyright

Copyrigth &copy; 2024 [Matthew Gibbons](https://github.com/accuser)