# timspurfan.github.io

Personal website source for `theandysmith.com` (GitHub Pages / Jekyll).

## What Is In This Repo

- Jekyll source content (`_posts`, `_layouts`, `_includes`, pages, assets)
- Generated build output is intentionally ignored (`_site/`, caches)

## Local Setup

Prerequisites:

- Ruby + Bundler
- Git

From repo root:

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open:

- <http://127.0.0.1:4000>

## Build (No Local Server)

```bash
bundle exec jekyll build
```

This writes static output to `_site/`.

## Typical Content Edits

- New post: add markdown file under `_posts/` with date-prefixed filename.
- Edit homepage: `index.html`.
- Edit navigation/sidebar: `_includes/sidebar.html`.
- Edit styling: `stylesheets/styles.css`.

## Notes

- `_site/` and caches are ignored so only source is versioned.
- If Bundler reports missing gems, run `bundle install` again.
