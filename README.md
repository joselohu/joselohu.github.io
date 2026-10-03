# joselohu.github.io

My portfolio site: https://joselohu.github.io

A single static page with no build step and no dependencies.

```
index.html              Content and structure
assets/css/styles.css   Design tokens, layout, light and dark themes
assets/js/main.js       Theme toggle, mobile menu, reveal on scroll
assets/favicon.svg
```

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Edit it

- Text and projects live in `index.html`. Each project is one `<article class="project">`.
- Colours, spacing and fonts are CSS variables at the top of `styles.css`. The dark theme overrides the same variables.
- The site follows the visitor's system theme until they use the toggle; the choice is then remembered in the browser.
