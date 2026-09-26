# Web Socket Practice Scaffold

An early client/server JavaScript exercise. Despite the repository name, the current published files do not implement WebSockets or messaging: `server/index.js` logs a greeting and `web/src/main.js` logs a number.

## Run the starter

Use Node.js 22.12+ and npm:

```sh
npm install --prefix server
npm install --prefix web
```

Run the frontend with:

```sh
npm run dev --prefix web
```

Open Vite's printed URL and the browser developer console. In another terminal, `npm run dev --prefix server` runs the Node script in watch mode. It does not start an HTTP or WebSocket listener.

## Layout

- `server/` — Node.js ES-module starter.
- `web/` — vanilla JavaScript/Vite frontend.

Use `npm run build --prefix web` and `npm run preview --prefix web` to build and preview the frontend. There is no root package script, environment configuration, or automated test suite.
