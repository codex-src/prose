# @zaydek/prose

`@zaydek/prose` is a stylesheet for prose. Contributions are welcome as issues and or pull requests.

To get started, simply run this command:

```bash
yarn add @zaydek/prose
# or npm i @zaydek/prose
```

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

## Supported HTML

`@zaydek/prose` currently supports:

- [x] `<h1-h6>`
- [x] `<p>`
- [x] `<pre>`
- [x] `<ul>`
- [x] `<ol>`
- [x] `<em>`
- [x] `<strong>`
- [x] `<code>`
- [x] `<a>`
- [x] `<small>`

**Note:** `@zaydek/prose` does not bundle a CSS reset. Personally, I recommend [normalize.css](https://github.com/necolas/normalize.css) or [modern-normalize.css](https://github.com/sindresorhus/modern-normalize).

## License

Licensed as [MIT](./LICENSE).
