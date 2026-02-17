# Local hot-reload dev server

Quick steps to run the site with hot reload:

1. Install dev dependency:

```bash
npm install
```

2. Start the hot-reload server:

```bash
npm run start
```

The server will serve the current folder on port `3000` and auto-reload when files change.

Alternative (no install):

```bash
npx live-server --port=3000 --open=./index.html --watch=.
```
