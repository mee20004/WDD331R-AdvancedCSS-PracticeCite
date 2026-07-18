# WDD 331R Practice Site
**Student:** Kameron Meeker
**Semester:** Spring 2026
**Live Site:** [View Site](https://mee20004.github.io/WDD331R-AdvancedCSS-PracticeCite/)

## About
This repository is my frontend portfolio for WDD 331R: Advanced CSS.
The homepage introduces my work, features stronger projects, and lists
all coursework in unit order so every assignment stays reachable. Assignment
pages share a small Home bar and footer. The site deploys automatically to
GitHub Pages on every push to main.

The site supports light, dark, and system themes with a persistent
theme toggle. Shared color tokens live in `css/tokens/colors.css`, and
typography tokens live in `css/tokens/variables.css`. Typography uses a
major-third modular scale (ratio 1.25) with fluid `clamp()` steps from
320px to 1280px, semantic role tokens for body/headings/captions, and
self-hosted Source Sans 3 with `font-display: swap`. The Unit 2 page
uses `unit-2/css/tokens/colors.css`. Unit 2 also demonstrates an
accessible inline Lucide SVG sprite (`<symbol>` / `<use>`) with shared
icon styles in `css/components/icons.css`. Portfolio layout styles live in
`css/components/portfolio.css`.

## Typography

- **Scale ratio:** major third (1.25)
- **Scale steps:** `--font-size-xs` through `--font-size-3xl` in `css/tokens/variables.css`
- **Fluid range:** 320px–1280px viewport for `--font-size-lg` and above
- **Semantic roles:** `--font-size-body`, `--font-size-caption`, `--font-size-heading-sm`, `--font-size-heading-md`, `--font-size-heading-lg`, `--font-size-display`
- **Web font:** Source Sans 3 (self-hosted in `fonts/`, loaded via `css/fonts.css`)
- **Font display:** `swap`

## Pages

- [Home](index.html)
- [Unit 1: Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Unit 2: Design Tokens & Components](unit-2/index.html) (featured)
- [Unit 3: Visual Effects](unit-3/visual-effects/index.html) (featured)
- [Unit 4: Grid Layouts - Editorial](unit-4/grid-layouts/editorial.html)
- [Unit 4: Grid Layouts - Cards (Subgrid)](unit-4/grid-layouts/cards.html) (featured)
- [Unit 4: Container Queries](unit-4/advanced/container-demo.html) (featured)
- [Unit 4: Sticky Positioning](unit-4/advanced/sticky-demo.html)

## Folder Structure
```
README.md
css/
  base/
  fonts.css
  components/
    icons.css
    portfolio.css
  layout/
  tokens/
  utilities/
  main.css
dist/
fonts/
index.html
js/
  theme-preference.js
unit-1/
  custom-properties/
unit-2/
  css/
  index.html
unit-3/
  visual-effects/
unit-4/
  grid-layouts/
    editorial.html
    editorial.css
    cards.html
    cards.css
  advanced/
    container-demo.html
    container-demo.css
    sticky-demo.html
    sticky-demo.css
```

## Build Tool
PostCSS

## How to Build
1. `npm install`
2. `npm run build:css`
