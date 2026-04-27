# Improvement Plan: Cric-Board-Angular-App

## Overview
Built on AngularJS 1.x (circa 2014–2016), which reached end-of-life in December 2021. All vendored dependencies are outdated. No tests exist.

## Improvements

### Modernization (High Priority)
- Migrate from AngularJS 1.x to Angular 17+ (or React/Vue if preferred) — AngularJS is EOL and no longer receives security patches
- Replace vendored `lib/` dependencies with npm packages managed by a package.json
- Replace `angular-ui-router` with the modern Angular Router
- Replace Angular Material 1.x with Angular Material 17+

### Testing
- Add unit tests for controllers (`cric-board-start-controller`, `cric-board-play-controller`) and factories
- Add e2e tests for the main scoring flow using Playwright or Cypress

### Code Quality
- Convert to TypeScript after migration to modern Angular
- Break the monolithic factory into smaller, focused services
- Add ESLint / strict TypeScript checks

### Features
- Add match history / scoreboard persistence (localStorage or a backend)
- Add support for different cricket formats (T20, ODI, Test)
- Make the UI responsive/mobile-friendly

### DevOps
- Add a `package.json` with npm scripts (`start`, `build`, `test`)
- Add GitHub Actions CI to run tests on every PR
