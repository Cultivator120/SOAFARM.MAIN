# SOA Farm Website

Website for SOA Farm, a piggery and farm produce business in Oshele, Ogun State, Nigeria.
Products are sold in batches, and customers are sent to the farm's Telegram group for sale updates.

## Project structure

```
soa-farm/
├── index.html            Page content
├── css/
│   └── style.css         All styles, colors and light/dark themes
├── js/
│   └── main.js           Small script (footer year)
├── assets/
│   └── images/
│       ├── logo.png      Full logo
│       ├── logo-mark.png Logo symbol only (header, footer)
│       └── favicon.png   Browser tab icon
├── .nojekyll             Tells GitHub Pages to serve files as they are
└── README.md
```

## Run locally

Open `index.html` in a browser. No build step or installation is needed.

## Publish on GitHub Pages

1. Create a public repository and upload everything in this folder (keep the folders).
2. Go to Settings > Pages.
3. Set Source to "Deploy from a branch", choose `main` and `/ (root)`, then Save.
4. The site appears at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Common edits

| To change | Edit |
| --- | --- |
| Text, products, phone number | `index.html` |
| Telegram group link | Search `t.me/` in `index.html` (3 places) |
| Colors | Variables at the top of `css/style.css` |
| Logo | Replace the files in `assets/images/` (keep the same names) |

## Contact

Phone: +234 805 986 3488
