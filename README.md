# WDD 331R Practice Site
**Student:** Kameron Meeker
**Semester:** Spring 2026
**Live Site:** [View Site](https://mee20004.github.io/WDD331R-AdvancedCSS-PracticeCite/)

## About
This repository is my Practice Site for WDD 331R: Advanced CSS.
Each week I add new pages and styles as I work through the course
assignments. The site deploys automatically to GitHub Pages on
every push to main.

The site supports light, dark, and system themes with a persistent
theme toggle. Shared color tokens live in `css/tokens/colors.css`, and
typography tokens live in `css/tokens/variables.css`. Typography uses a
major-third modular scale (ratio 1.25) with fluid `clamp()` steps from
320px to 1280px, semantic role tokens for body/headings/captions, and
self-hosted Source Sans 3 with `font-display: swap`. The Unit 2 page
uses `unit-2/css/tokens/colors.css`.

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
- [Unit 2: Design Tokens & Components](unit-2/index.html)
- [Unit 3: Visual Effects](unit-3/visual-effects/index.html)
- [Unit 4: Grid Layouts - Editorial](unit-4/grid-layouts/editorial.html)
- [Unit 4: Grid Layouts - Cards (Subgrid)](unit-4/grid-layouts/cards.html)
- [Unit 4: Container Queries](unit-4/advanced/container-demo.html)
- [Unit 4: Sticky Positioning](unit-4/advanced/sticky-demo.html)


## Folder Structure
```
README.md
css/
  base/
  fonts.css
  components/
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
