# Cric-Board-Angular-App

AngularJS (1.x) cricket scoreboard application that lets users start and track a live cricket match score.

## Tech Stack
- AngularJS 1.x (angular-ui-router)
- Angular Material
- jQuery 2.0.3
- Underscore.js / moment.js
- All dependencies vendored under `lib/` — no build system

## Project Structure
```
Cric-Board-Angular-App/
  src/
    app.js / app.module.js / app.router.js
    controllers/     # start and play controllers
    directives/      # score.board.directive.js
    factories/       # cric.board.factory.js
    services/
    partials/        # HTML templates
    index.html       # Entry point
  lib/               # Vendored JS/CSS libraries
```

## Development
No package manager needed — all dependencies are pre-vendored. Serve with any static server:
```bash
npx serve src
# or
python3 -m http.server 8080 --directory src
```

## Key Notes
- Plain AngularJS 1.x app — no build/compile step required.
- Routing is handled by `angular-ui-router` configured in `app.router.js`.
