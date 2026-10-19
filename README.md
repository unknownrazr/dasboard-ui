# Template Designs

A privately stored UI replica of a project dashboard, adapted for local template exploration.

## Run locally

From the repository root, start a static server:

```bash
python -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

The root `index.html` is the main entry point. The additional `fernly/` entry and the `fonts/` folder are kept to preserve the supplied project structure and asset references.

## Contents

- `index.html` — root entry point
- `fernly/index.html` — secondary entry point
- `fernly/assets/` — compiled JavaScript and CSS
- `fernly/favicon.png` — favicon asset
- `fonts/` — font stylesheet and font files

## Notes

- This is a static front-end demo; no backend service is included.
- The original creator/copyright notice has been retained in the HTML.
- The supplied archive references a `LICENSE.md`, but that file was not included. No license file or license terms have been inferred.
- This repository is intended to remain private unless the owner separately verifies the rights to redistribute the included source and assets.
