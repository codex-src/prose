# @zaydek/prose

Prose is a stylesheet for prose. Contributions are welcome as issues and or pull requests.

To get started, simply run this command:

```bash
yarn add @zaydek/prose
# or npm i @zaydek/prose
```

**Usage:**

<!-- prettier-ignore -->
```tsx
import "@zaydek/prose/dist/reset.css"
import "@zaydek/prose"

function Component() {
	return (
		<article className="prose">
			<h1 id="hello-world"><a href="#hello-world">Hello, world!</a></h1>
			<p>Thanks for trying <code>prose</code>!</p>
		</article>
	)
}
```

**Usage: (CDN)**

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Hello, world!</title>
		<link rel="stylesheet" href="https://unpkg.com/@zaydek/prose/dist/reset.css" />
		<link rel="stylesheet" href="https://unpkg.com/@zaydek/prose/dist/index.css" />
	</head>
	<body>
		<article class="prose">
			<h1 id="hello-world"><a href="#hello-world">Hello, world!</a></h1>
			<p>Thanks for trying <code>prose</code>!</p>
		</article>
	</body>
</html>
```

## Supported HTML

Prose currently supports:

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

**Note:** Prose does not bundle a CSS reset. I recommend [normalize.css](https://github.com/necolas/normalize.css) or [modern-normalize.css](https://github.com/sindresorhus/modern-normalize).

## License

Licensed as [MIT](./LICENSE).
