# Jilin Hu Personal Website

This repository contains the source for the personal academic website of Jilin Hu, Full Professor at the School of Data Science and Engineering, East China Normal University.

The site is built with [Jekyll](https://jekyllrb.com/) and customized from the al-folio academic theme.

## Main Content

- Homepage biography: `_pages/about.md`
- Publications: `_pages/publications.md`
- Teaching and students: `_pages/students.md`
- Scientific service: `_pages/service.md`
- News: `_news/`
- Bibliography data: `_bibliography/`
- Images and PDFs: `assets/`

## Local Development

Install Ruby dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Build the static site:

```bash
bundle exec jekyll build
```

Docker Compose is also available and exposes the site on port `8080`.
