# Updates Log

Every change, in date order. Newest at the top.

## 2026-08-12 — Version 3: weather fixes + all Indian cities

- **City drop-down:** the building form and the weather card now use a
  drop-down of 138+ Indian cities (grouped by region), so weather always
  matches a real city.
- **Weather updates instantly** when you change a city, plus a
  "↻ Refresh weather" button. Auto-refresh every 10 minutes instead of 30.
- Fixed a bug where switching buildings quickly could show the wrong city's
  weather (the fetch now checks which building is active before showing).
- Every city name was tested against the free weather service — two needed
  different spellings (Shivamogga, Davangere).

## 2026-08-12 — Published to the internet (GitHub Pages)

- The app is now live and free at **https://yn8610.github.io/coolbreeze/** .
- Created the GitHub account, the `coolbreeze` repository, pushed the code,
  and switched on GitHub Pages hosting.
- A "token" (secret code) lets the builder push updates from this computer —
  it lasts 90 days, then we renew it together.

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
