# Ziyu Li's website

The site has four Markdown pages:

- `_pages/about.md`: front page (`/`).
- `_pages/presentations.md`: presentations (`/presentations/`).
- `_pages/research.md`: research (`/research/`).
- `_pages/cv.md`: curriculum vitae (`/cv/`).

Edit headings, text, and links directly in these files. Entries are listed manually;
there are no collections, category generators, or map automation.

## Shared settings and files

- `_config.yml`: site settings and author profile.
- `_data/navigation.yml`: navigation links.
- `files/`: linked PDFs and BibTeX downloads.
- `images/`: profile photo and site icons.
- `_layouts/`, `_includes/`, `_sass/`, and `assets/`: shared theme, styles, and scripts.
- `_data/ui-text.yml`: text labels used by the theme.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`. Restart Jekyll after editing `_config.yml`.

The site uses the AcademicPages theme, based on Minimal Mistakes. See `LICENSE`.

The browser uses `assets/js/main.min.js`. If you change the JavaScript sources,
run `npm install` and `npm run build:js` to rebuild it.
