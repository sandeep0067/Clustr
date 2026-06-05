# Clustr

Clustr is a Vite + React frontend for a skill exchange landing experience.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

The production files are generated in `dist`.

## Cloudflare Pages

Use these settings when importing the GitHub repository into Cloudflare Pages:

```txt
Framework preset: Vite
Build command: npm run build
Build output directory: dist
Node.js version: 22.12.0
```

Optional environment variables:

```txt
VITE_CLUSTR_URL=https://clustr-6kk9.onrender.com
VITE_API_URL=https://your-api.example.com
```

If `VITE_CLUSTR_URL` is not set, login and signup actions use `https://clustr-6kk9.onrender.com`.

The app is a single-page landing page and does not require a `_redirects` fallback for Cloudflare Workers/Pages deployment.
