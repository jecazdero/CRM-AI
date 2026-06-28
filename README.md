# CRM-AI

A static CRM AI Bot prototype built as a polished UI demo. This project covers Sugar AI project from the Loom video (https://www.loom.com/share/6a2be2209a534e36b397872de361a1b2). The project is served from `index.html` and includes visual CRM dashboard components, AI chat widget functionality, and branded sidebar navigation.

## Features

- Fully static HTML/CSS prototype
- Custom AI chat widget UI
- CRM-style dashboard layout
- Static assets stored under `AI_elements/`
- Configured for Netlify deployment via `netlify.toml`

## Run locally

From the project root, run a local static server. For example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub repository

This project is published privately at:

- https://github.com/jecazdero/CRM-AI

## Deployment

The project can be deployed as a static site. The included `netlify.toml` file publishes the root directory and applies security headers for all routes.

## Notes

- No build step is required.
- Keep `AI_elements/` alongside `index.html` so image assets load correctly.
