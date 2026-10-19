# Template Designs

A private, static project-management workspace demo with dashboard, tasks, calendar, analytics, team, settings, and help views.

## Run locally

From the repository root, start a static server:

```bash
python -m http.server 8080
```

Then open http://localhost:8080 in your browser.

## Project structure

- `index.html` — main entry point
- `assets/` — compiled JavaScript and CSS
- `favicon.png` — custom project icon
- `fonts/` — bundled font stylesheet and font files

## Notes

- Static front end; no backend service is included.
- The project uses local browser storage for certain preferences.
- The source archive referenced a license file that was not included, so this repository does not claim license terms. Keep it private unless redistribution rights for all included source and assets have been verified.
