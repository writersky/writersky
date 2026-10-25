# writersky

Static "site is closing" page for writersky.com, served as a Cloudflare Worker with static assets only.

Every page path (e.g. old `/story/123` links) serves `public/index.html` via `not_found_handling: "single-page-application"`.

```sh
npm install
npm run dev     # local preview via wrangler
npm run deploy  # publish to Cloudflare
```

## Status

This project is not maintained. It exists only to serve the closing notice for writersky.com. Issues and pull requests will not be reviewed.

## License

[MIT](LICENSE)
