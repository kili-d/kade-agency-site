# KADE — Digital Agency Website

A simple, responsive example website for a fictional Amsterdam-based digital agency.

## Run locally

```bash
python3 -m http.server 4173
```

Then open [http://127.0.0.1:4173](http://127.0.0.1:4173).

## Deploy with Coolify

Use the `Dockerfile` build pack and expose internal port `80`. The container
serves the site with Nginx, so no start command or host port mapping is needed.

## Stack

- Semantic HTML
- Modern CSS
- Vanilla JavaScript
- No build step or dependencies
