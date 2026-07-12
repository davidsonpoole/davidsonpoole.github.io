# My Blog

A minimal GitHub Pages blog. No build tools — GitHub Pages runs Jekyll
automatically, so posts are just Markdown files.

## Writing a new post

Add a file to `_posts/` named `YYYY-MM-DD-title.md`:

```
---
layout: post
title: "My Post Title"
---
Your post content in **Markdown** goes here.
```

Push to `main` and GitHub Pages rebuilds the site automatically.

## Publishing

1. Push this repo to GitHub.
2. In the repo settings, go to **Pages** and set the source to the `main`
   branch (root folder).
3. Your site will be live at `https://<username>.github.io/<repo>/`.

If the repo is named `<username>.github.io`, the site will be at
`https://<username>.github.io/` instead, and you should remove the
`baseurl` line in `_config.yml` (it's already empty by default).

## Local preview (optional)

If you have Ruby installed:

```
gem install bundler jekyll
jekyll serve
```

Then visit `http://localhost:4000`.
