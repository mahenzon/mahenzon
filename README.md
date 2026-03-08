# mahenzon-landing

Landing page for mahenzon.ru (GitHub Pages).

## Local development

**Run a local server** to preview the site in the browser:

```bash
npm run serve
```

Then open http://localhost:8000

## Before deploying / before committing

**Build the CSS** so that `assets/css/tailwind.css` is up to date (Tailwind is built from `index.html` and `input.css`):

```bash
npm run build:css
```

Then commit the updated `assets/css/tailwind.css` and push. If you change HTML classes or `input.css`, run this before deploying.
