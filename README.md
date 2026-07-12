# Scrygent Landing Page

A standalone, framework-free marketing landing page for [Scrygent](https://github.com/mohamadmeri/scrygent), a strictly typed compiler engine for data analysis.

This repository contains a single `index.html` file (with inline CSS and vanilla JS) designed for zero-build-step deployment on Cloudflare Pages.

## Links

* **[Live Demo](#)** *(Replace with your deployed Streamlit URL)*
* **[Main Engineering Repository](https://github.com/mohamadmeri/scrygent)** (Core compiler, LangGraph orchestration, and deterministic tool suite)
* **[Architecture Document](https://github.com/mohamadmeri/scrygent/blob/main/docs/ARCHITECTURE.md)**

## Deployment

This site requires no build process or dependencies. It is designed to be deployed directly via Cloudflare Pages.

1. Push this repository to GitHub.
2. In the Cloudflare Dashboard, navigate to **Workers & Pages** > **Create** > **Pages** > **Connect to Git**.
3. Select this repository.
4. Set the **Framework preset** to `None`.
5. Leave the **Build command** blank.
6. Set the **Build output directory** to `/` (the repository root).
7. Click **Deploy**.

## Design Notes

The page utilizes a warm, paper-like light theme contrasted with a dark, interactive "obsidian mirror" in the hero section. This mirror uses a CSS `mask-image` driven by vanilla JavaScript to reveal the compiled JSON Intermediate Representation (IR) beneath the chaotic "fog" of raw data. 

This interaction visually reinforces Scrygent's core value proposition: deterministic, mathematically verified truth hidden beneath unstructured inputs.
