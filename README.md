# Tailwind Login Form

A modern and responsive login form created using HTML, CSS, and Tailwind CSS.

The compiled stylesheet is included. Open the repository-root `index.html` to
view the form; it links to `src/output.css` and is the entry point GitHub Pages
uses when publishing from the repository root. The original `src/index.html`
is also available for local preview.

For a GitHub Pages project site, the live URL follows this pattern:
`https://<owner>.github.io/<repository>/`.

## Setup

Install the project dependencies:

```sh
npm install
```

## Build CSS

Compile the Tailwind input stylesheet to `src/output.css`:

```sh
npm run build
```

To rebuild automatically when source files change, run:

```sh
npm run watch
```

Open `index.html` in a browser to view the page. After changing Tailwind
classes or styles, run `npm run build` to regenerate the compiled stylesheet.
