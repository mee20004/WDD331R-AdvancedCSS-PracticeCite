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
the Unit 2 page uses `unit-2/css/tokens/colors.css`.

## Pages

- [Home](index.html)
- [Unit 1: Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Unit 2: Design Tokens & Components](unit-2/index.html)
- [Unit 3: Visual Effects](unit-3/visual-effects/index.html)
- [Unit 4: Grid Layouts - Editorial](unit-4/grid-layouts/editorial.html)
- [Unit 4: Grid Layouts - Cards](unit-4/grid-layouts/cards.html)


## Folder Structure
```
README.md
css/
  base/
  components/
  layout/
  tokens/
  utilities/
  main.css
dist/
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
```

## Build Tool
PostCSS

## How to Build
1. `npm install`
2. `npm run build:css`
