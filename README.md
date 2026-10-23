# jorgecmoura.github.io

Personal site and blog of Jorge Moura, software engineer. Built with
[Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima)
theme, hosted on [GitHub Pages](https://pages.github.com/).

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000) in your browser.
Jekyll will rebuild automatically as you edit files (use `--livereload` for
automatic browser refresh).

## Adding a blog post

Add a new markdown file to `_posts/` named `YYYY-MM-DD-title.md` with front
matter similar to the existing `_posts/2026-10-23-hello-world.md` example.

## Publishing

This repo is configured to build with the `github-pages` gem, which mirrors
GitHub Pages' hosted build environment. Just push to the `main` branch —
GitHub Pages automatically builds and deploys the site, no CI configuration
needed.
