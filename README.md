# Zùsto Café — premium prototype

Static website: no framework and no runtime dependencies.

## Local preview
Open `index.html` directly, or run any static server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Vercel
This repository is deployed as a static site. `vercel.json` uses a lightweight copy build that collects the HTML, CSS, JavaScript, text and XML files into `public/` so Vercel does not try to auto-detect Vite or another framework.

Production target: `https://zustocafe.vercel.app`.
