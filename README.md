# WheatOmics Homepage

The official homepage for [WheatOmics 2.0](https://doi.org/10.1016/j.molp.2021.10.006) — an AI agent-powered wheat pan-omics platform integrating genomes, transcriptomes, variants, and other multi-omics resources for wheat functional genomics and breeding.

This repository hosts the static frontend page for the WheatOmics 2.0 homepage.

## Overview

- Single-page, dependency-free static HTML (no build step required)
- Responsive layout with a Ken Burns hero background
- No external runtime dependencies — all styles and scripts are inline in `index.html`

## Project Structure

```
.
├── index.html          # Main homepage (single file)
├── home.png            # Hero section background image
├── footer-plot.png     # Footer data-overview plot
├── Logo.png            # Full logo
├── Logo-small.png      # Small logo (navigation brand mark)
├── Logo-square.png     # Square logo
└── README.md
```

## Usage

The page is fully static. Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

Then visit <http://localhost:8000>.

## Deployment

The site can be hosted on any static hosting service (GitHub Pages, Netlify, Vercel, Nginx, etc.). No build or configuration is required — deploy the files as-is.

## Citation

If you use WheatOmics in your publication, please cite:

> Ma, S. et al. WheatOmics: a platform combining multiple omics data to accelerate functional genomics studies in wheat. *Mol. Plant* **14**, 1965–1968 (2021). <https://doi.org/10.1016/j.molp.2021.10.006>

## License

[Apache License 2.0](LICENSE) © 2026 WheatOmics

## Author

Jiwen Zhao — <https://github.com/CropCoder>
