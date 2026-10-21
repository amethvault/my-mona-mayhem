# Project Overview

Mona Mayhem is an Astro 6 application for comparing GitHub contribution activity. App routes live in `src/pages/`; the dynamic contributions endpoint is under `src/pages/api/`.

# Build and Development

- `npm ci` installs the locked dependencies.
- `npm run dev` starts the local Astro server (default: `http://localhost:4321`).
- `npm run build` creates a production build.
- `npm run preview` serves the production build locally.
- Use Node.js 22, matching the development container.

# Astro Conventions

- Follow Astro's file-based routing: use `.astro` files for pages and typed `APIRoute` handlers for API endpoints.
- TypeScript extends Astro's strict configuration; preserve strict typing.
- The app uses `output: 'server'` with the Node standalone adapter. Keep server-only routes non-prerendered. Static hosting requires changing the adapter/output and deployment workflow; do not assume the existing Pages workflow deploys the app.
- No test, lint, or typecheck scripts are currently configured. Run `npm run build` to validate app changes.

# References

- [README](README.md): project stack, prerequisites, and deployment notes.
- [Static documentation site](docs/index.html): entry point for the published docs.