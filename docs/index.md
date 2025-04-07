---
layout: default
title: Home
nav_order: 1
---

# 📘 Project Documentation

Welcome! This is the internal developer documentation for the project. Here you'll find everything from system architecture to deployment guides and workflows.

This documentation site is built using [Jekyll](https://jekyllrb.com/) with the [Just the Docs](https://just-the-docs.github.io/just-the-docs/) theme.

## 🔧 Prerequisites

To run and develop the documentation locally, you'll need:

- Ruby
- Bundler

## 🚀 Running the Site Locally

Navigate into the `/docs` folder, and run:

```bash
bundle install
bundle exec jekyll serve --livereload
```

Once it's running, open your browser at:
http://localhost:4000/test_docs/

## 📝 Adding New Pages

Create a new Markdown file (.md) inside the `docs/pages/` directory.

Add front matter at the top of the file:

```markdown
---
layout: default
title: New Page Title
---
```

## 🚀 Deploying to GitHub Pages

The site is deployed automatically using GitHub Actions.
Make sure your changes are pushed to the correct branch (e.g., master) and GitHub will handle the deployment.

## 📁 Project Structure

`pages/` – additional Markdown pages

`_config.yml` – Jekyll configuration

`_layouts/`, `_includes/` – custom layout templates if needed

`_site/` – auto-generated output (should not be committed)
