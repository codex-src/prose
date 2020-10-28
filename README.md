# Prose

Prose adds opinionated styling for prose.

## Get Started

To get started, simply run this command:

```bash
yarn add @zaydek/prose
# or npm i @zaydek/prose
```

Prose is a CSS dependency. Once you import `@zaydek/prose`, simply add the `prose` class to an element, preferably an `<article>`.

```jsx
import "@zaydek/prose"

export default function Prose() {
	return (
		<article class="prose">
			<h1>Hello, world!</h1>
			<p>
				Thanks for trying <code>prose</code>!
			</p>
		</article>
	)
}
```

## License

Licensed as [MIT](./LICENSE).
