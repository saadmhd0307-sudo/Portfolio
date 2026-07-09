# Saad Al Awadhi — Portfolio Website

A professional portfolio built with [Quarto](https://quarto.org) and **R (ggplot2)**, published via GitHub Pages.

## Pages
- **Home** (`index.qmd`) — profile, education, skills, achievements
- **Projects** (`projects.qmd`) — case studies with ggplot2 visualizations
- **Dashboard** (`dashboard.qmd`) — Quarto dashboard of venture metrics
- **Presentation** (`presentation.qmd`) — Reveal.js slides

## Requirements
- [Quarto](https://quarto.org/docs/get-started/) (bundled with recent RStudio)
- R with the `ggplot2` package:
  ```r
  install.packages("ggplot2")
  ```

## Build in RStudio
1. Open any `.qmd` file and click **Render**, or
2. In the RStudio **Terminal** tab, from the project folder (the one with `_quarto.yml`):
   ```
   quarto preview      # live preview with auto-reload
   quarto render       # build final site into /docs
   ```

## Publishing (GitHub Pages)
1. Push this repo to GitHub.
2. Repo **Settings -> Pages -> Build and deployment -> Source: Deploy from a branch**.
3. Branch: `main`, folder: `/docs`. Save.
4. Site goes live at `https://YOURUSERNAME.github.io/REPONAME/`.

## Before you publish — replace these placeholders
- `_quarto.yml`: `site-url`, LinkedIn URL, email, `google-analytics` ID
- `files/Saad_Al_Awadhi_Resume.pdf`: drop in your real resume PDF
