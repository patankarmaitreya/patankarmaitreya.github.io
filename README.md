# patankarmaitreya.github.io

Personal portfolio website, live at [patankarmaitreya.github.io](https://patankarmaitreya.github.io).

## Structure

```
.
├── index.html          # Landing page
├── pages/              # Additional pages (about, projects, etc.)
├── assets/
│   ├── css/style.css   # Styles
│   ├── js/main.js      # Scripts
│   └── images/         # Images and icons
└── .gitignore
```

## Local development

No build step — open `index.html` directly in a browser, or use any static file server:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deployment

Hosted via [GitHub Pages](https://pages.github.com) from the `main` branch root.
