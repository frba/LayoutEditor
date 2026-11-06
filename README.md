# Concordia Genome Foundry — 2D/3D Lab Layout & Schematic Studio

Interactive 2D CAD floor plan editor and real-time 3D architectural cutaway schematic renderer for the **Concordia Genome Foundry** (`15.0m × 24.0m`).

## 💻 Running Locally
You can open `index.html` directly in any modern browser, or serve it via a local HTTP server:

```bash
python3 -m http.server 8000
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

## 🚀 Live GitHub Pages App
Once GitHub Pages is enabled on your repository, open:
`https://frba.github.io/LayoutEditor/` (or `https://<your-github-username>.github.io/<repo-name>/`)

## ✨ Features Baked into Default State
- **Ground-Truth Architectural Floor Plan (`15.0m × 24.0m`)**:
  - **Main Automation Lab (`X = 4.5m–15.0m`)**: Houses **QPiX 420**, **inSPIRE**, **MAESTRO**, **Biomek i7**, **Cell Sorter**, **Opentrons OT-2**, perimeter **EnSight** & **Cytation 5** plate readers, utility sink, **-20°C / -80°C** freezers, and general lab islands.
  - **Internal Storage & Offices (`X = 4.5m–15.0m, Y = 18.5m–24.0m`)**: Two Storage rooms and two Staff Offices enclosed with solid drywall partitions and wood vision-lite doors inside the south end of the Main Automation Lab.
  - **West Enclosed Suite (`X = 0.0m–4.5m`)**: Separated by a continuous dividing wall at `X = 4.5m` (`1.05m` knee-wall + upper black-mullion windows along `Y = 0–18.5m`), housing the **Hamilton Microlab VANTAGE** suite and the **Mammalian Cell Culture Room** separated by a framed glass door at `Y = 8.5m`.
- **36 Official GenomeFoundry.ca 3D Instrument Models**:
  - Browse, preview in 360° 3D, and place any instrument from `https://genomefoundry.ca/instrumentation.html`.
- **2D SVG / PNG & High-Resolution 3D Cutaway Schematic Photo Export**.
