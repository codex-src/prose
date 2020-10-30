# @zaydek/prose

`@zaydek/prose` is a stylesheet for prose. Contributions are welcome as issues and or pull requests.

To get started, simply run this command:

```bash
yarn add @zaydek/prose
# or npm i @zaydek/prose
```

Then add `class="prose"` to get started!

**Usage:**

```tsx
import "@zaydek/prose"

function Component() {
	return (
		<article className="prose">
			<h1 id="hello-world">
				<a href="#hello-world">Hello, world!</a>
			</h1>
			<p>
				Thanks for trying <code>prose</code>!
			</p>
		</article>
	)
}
```

**Note:** `@zaydek/prose` does not bundle a CSS reset.

## License

Licensed as [MIT](./LICENSE).
