[![bookdown](https://github.com/bbest/gh-actions-demo/actions/workflows/bookdown.yaml/badge.svg)](https://github.com/bbest/gh-actions-demo/actions/workflows/bookdown.yaml)

[![netlify](https://api.netlify.com/api/v1/badges/9dd79e81-90a8-40d9-858a-7592ed314e55/deploy-status)](https://app.netlify.com/sites/gh-actions-demo/deploys)

This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

You can find the preview of this example at https://bookdown.org/yihui/bookdown-demo/.

## Github Action, Netlify Deploy

* [Deploy your bookdown project to Netlify with Github Actions | Emil Hvitfeldt](https://www.hvitfeldt.me/blog/bookdown-netlify-github-actions/)
  - [x] Login to Netlify.com, link to Github repo
  - [x] Get variables in Netlify → store as Github repo Secret:
    - [x] `API ID` → `NETLIFY_SITE_ID`
    - [x] `Personal Access Token` → `NETLIFY_AUTH_TOKEN`
  - [x] Get badge in Netlify → add to README.md
  - [x] Run the following in RStudio:
    - [x] `usethis::use_github_action("bookdown.yaml")`
    - [x] `renv::snapshot()`
  - [x] git commit, push



