# Gaming Arena

Gaming Arena is a lightweight directory of third-party gaming and casino-style platform pages. The site is published with GitHub Pages and is designed to be clean, simple, and easy to browse.

Live site: https://safdarapk.github.io/my-games-site/

## Overview

- Responsive homepage with a brand-focused layout
- Directory of game and casino-style platform cards
- Dedicated detail pages in the `games/` folder
- Simple category filtering on the main page
- GitHub Pages compatible static website

## Repository structure

```text
my-games-site/
├── index.html
├── logo.svg
├── favicon.svg
├── sitemap.xml
├── README.md
├── games/
│   ├── y999.html
│   ├── winpkr.html
│   ├── royal-x.html
│   ├── jj77.html
│   ├── ct777.html
│   ├── x99.html
│   ├── m999.html
│   ├── zs777.html
│   ├── zs999.html
│   └── z7.html
└── .github/workflows/
```

## Local preview

This is a static site, so no install step is required. You can open `index.html` directly in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## How to add a new platform

1. Create a new page under `games/` such as `games/example.html`.
2. Add a matching card to `index.html`.
3. Use either `data-category="games"` or `data-category="casino"` for the filter to work.
4. Update the sitemap and README if needed.

## Important notice

This site is an independent directory and not the operator of the platforms it lists. Some third-party services may involve gambling or real-money play. Only adults should participate where legal. Check local laws, eligibility rules, and provider terms before visiting or using any service.

## License

No license is currently specified for this repository.
