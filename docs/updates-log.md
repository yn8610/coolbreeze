# Updates Log

Every change, in date order. Newest at the top.

## 2026-08-12 — Version 2: live weather + multiple buildings

- **Live weather:** the dashboard now connects to Open-Meteo (a free weather
  service — no key, no credit card). Each building's city shows the current
  temperature and a 5-day forecast, plus a smart suggestion — e.g. "cool
  night ahead, ease off overnight" with an estimated saving.
  Weather is refetched at most every 30 minutes per building.
- **Multiple buildings:** owners can add any number of buildings (name, city,
  size, monthly bill), switch between them, and remove them. Each building
  keeps its own energy history, savings and alerts.
- Old accounts from Version 1 are automatically upgraded to the buildings list.

## 2026-08-12 — First version of the app built

- Created the log-in / create-account page (`index.html`).
- Created the dashboard (`dashboard.html`) with:
  - Scoreboard: current cooling energy, savings today, green/red status.
  - Weekly energy bar chart (no libraries needed, just CSS).
  - Bill + building size inputs with a clearly-labelled savings estimate.
  - The big green "Apply smart cooling" button that drops the next bar.
  - Alerts feed (email/text alerts are a later version).
- Made the look and feel (`style.css`).
- Data is saved in the browser (localStorage) — free, no credit card.
- Every new account gets a demo building with sample data + welcome alert.

## What's next (later versions)

- Accounts and data on a real shared system (backend).
- Live smart-meter connections replacing the estimate with real measurements.
- Automatic email and text alerts.
- Free publishing on GitHub Pages so anyone can open the link.
