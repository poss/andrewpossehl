# andrewpossehl.com

A lightweight personal website for designer Andrew Possehl.

[Visit andrewpossehl.com](https://andrewpossehl.com)

## Overview

- Responsive, accessible layout
- Light and dark themes with a saved browser preference
- Self-hosted typography and social-preview artwork
- No analytics, advertising, cookies, or third-party scripts
- No framework, package manager, or build step

## Local development

Serve the repository root with any static web server. For example:

```sh
python3 -m http.server 8000
```

Then open [localhost:8000](http://localhost:8000).

## Deployment

GitHub Pages publishes the root of the `master` branch to
[andrewpossehl.com](https://andrewpossehl.com). The custom domain is
configured in [`CNAME`](CNAME).

## Project structure

```text
.
├── assets/
│   ├── css/       Site styles
│   ├── fonts/     Self-hosted Space Grotesk font
│   └── img/       Favicons and social-preview artwork
├── 404.html       Custom not-found page
├── index.html     Main page
├── robots.txt     Search-engine crawling rules
└── sitemap.xml    Search-engine sitemap
```

Space Grotesk is distributed under the SIL Open Font License 1.1. See
[`assets/fonts/OFL.txt`](assets/fonts/OFL.txt).
