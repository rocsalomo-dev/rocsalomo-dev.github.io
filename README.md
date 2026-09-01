# Roc Salomo — AI Engineer Portfolio

My personal portfolio showcasing AI engineering projects — autonomous agents, data pipelines and LLM systems that ship to production.

**Live:** *(deploy with GitHub Pages / Vercel / Netlify)*

## Design

"Dark technical" — a near-black, blue-tinted base with a single teal accent (`#2DD4BF`) and an amber metric color (`#F59E0B`). Typography: Space Grotesk (display), Inter (body), JetBrains Mono (code/metrics).

## Structure

```
index.html   — single page: hero → positioning → projects → skills → contact
styles.css   — design system (CSS variables for the full palette)
script.js     — scroll-reveal (IntersectionObserver)
```

No build step, no dependencies. Open `index.html` or serve with any static server.

## Projects

| Project | Category | Status |
|---|---|---|
| **GravelRadar** | AI agent / workflow · AI + data engineering | 🟢 LIVE — [thegravelradar.com](https://thegravelradar.com) |
| RAG application | RAG | upcoming |
| Bike catalog | data pipeline | upcoming |

## Run locally

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

GitHub Pages (Settings → Pages → deploy from `main` / root), or drag-and-drop to Netlify/Vercel.
