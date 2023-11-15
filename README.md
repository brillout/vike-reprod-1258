Run `pnpm run dev` then go to http://localhost:3000/some/base-url/ and observe how Vike removes the trailing shlash (redirets the URL to `http://localhost:3000/some/base-url`) which makes Vite return this error HTML:

```html
The server is configured with a public base URL of /some/base-url/ - did you mean to visit <a href="/some/base-url/">/some/base-url/</a> instead?
```
