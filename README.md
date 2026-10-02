# The 2025 State of Open-Source AI: Interactive Guide

An interactive, single-page web guide that explores the state of open-source AI models — covering popular model families, their capabilities, licensing, benchmarks, and how they compare across different use cases.

## Features

- **Interactive model explorer** — browse and compare open-source AI models
- **Benchmark overviews** — key performance metrics at a glance
- **Licensing guide** — permissive vs. copyleft vs. research-only model licenses
- **Dark/light friendly design** — responsive layout for desktop and mobile
- **Zero dependencies at runtime** — fully client-side, loads instantly

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

## Quick Start

No build step required — open the site directly:

```bash
# Serve locally
npx serve .
# or
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project Structure

```
.
├── index.html    # The complete interactive guide (single file)
└── README.md     # This file
```

## Deploy Notes

Static site — deploy anywhere that serves static files:

- **GitHub Pages**: Settings → Pages → deploy from branch (root)
- **Netlify / Cloudflare Pages / Vercel**: drag-and-drop or connect the repo

## License

MIT — free to use and share.

---

**Built by [Girish Lade](https://github.com/girishlade111)** — more free tools at [ladestack.in](https://ladestack.in)
