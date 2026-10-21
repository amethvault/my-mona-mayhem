🌐 English | [Español](README.es.md) | [Português (Brasil)](README.pt_BR.md) | [한국어](README.ko.md)

# 🎮 Mona Mayhem

### Your GitHub contributions. One arcade showdown.

Mona Mayhem is an Astro starter for a retro arcade-style arena where two GitHub profiles go head-to-head on their contribution activity.

![Mona Mayhem Screenshot](https://github.com/user-attachments/assets/5eca79e2-cb9f-4e93-aa0d-23666ebde3b7)

*The contribution battle arena*

> **Project status:** This is a starting point for the app. The homepage and contribution API are scaffolded; the API currently returns `501 Not Implemented`.

## Get started

You'll need [Node.js](https://nodejs.org/) and npm.

```sh
git clone <your-repository-url>
cd my-mona-mayhem
npm ci
npm run dev
```

Open the local URL printed by Astro (usually `http://localhost:4321`).

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the app for production |
| `npm run preview` | Preview the production build locally |

## Built with Astro

- **Astro 6** for a fast, server-rendered web app.
- **Node.js standalone adapter** for running the app and API routes on a Node host.
- A retro arcade visual direction, with GitHub contribution data as the basis for the showdown.

## Astro notes

- Keep pages and components server-first; add client-side JavaScript only where interactivity needs it.
- Keep API and other server-only logic in `src/pages/api/`. This project uses Astro's server output and Node adapter, so deploy it to a host that supports Node.js.
- Run `npm run build` before deploying, then use `npm run preview` to check the built app locally.

## License

MIT
