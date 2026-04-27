# Cricket Scoreboard

An AngularJS single-page application for tracking cricket match scores in real time.

## Tech Stack

- AngularJS
- HTML5 / CSS3
- JavaScript (ES5)

## Prerequisites

- [Node.js](https://nodejs.org/) v14+ (for a local HTTP server)

## Getting Started

### Option 1 — Live Server (recommended)

If you have VS Code, install the **Live Server** extension and click **"Go Live"** from `index.html`.

### Option 2 — npx serve

```bash
cd cricket-scoreboard
npx serve .
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 3 — Python HTTP server

```bash
cd cricket-scoreboard
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

## Project Structure

```
cricket-scoreboard/
├── index.html          # Entry point
├── app.js              # App bootstrap
├── app.module.js       # Angular module definition
├── app.router.js       # Client-side routing
├── controllers/        # Angular controllers
├── directives/         # Custom directives
├── factories/          # Shared factories/services
├── services/           # Business logic services
├── partials/           # HTML partials/views
├── modules/            # Feature modules
├── css/                # Stylesheets
├── js/                 # JavaScript utilities
└── lib/                # Third-party libraries
```
