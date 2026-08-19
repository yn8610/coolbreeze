# PRD.md — Master Guide (Smart Cooling Dashboard)

This is the master guide for our project. It always shows the latest decisions.
Other guides are linked below. Any time we change a decision, this file gets
updated right away.

## The Idea (Stage 1 — Done)

Building owners and AI data centre operators in India are trying to cool their
facilities efficiently, but cooling systems often run continuously without
adapting to real-life conditions. This wastes electricity and causes carbon
emissions.

**Our product:** A smart cooling dashboard that watches energy usage in real
time and automatically adjusts cooling to cut the electricity bill without
making the building uncomfortably hot.

## Decisions

| Decision | Choice | Status |
|---|---|---|
| Target users | Commercial building owners and AI data centre operators in India — starting with medium-sized buildings | ✅ Decided |
| Most important thing | See real-time cooling energy usage + automatic adjustments that cut the bill without making the building too hot | ✅ Decided |
| Does it need to SAVE information? | Yes — accounts, sensor readings, and energy history | ✅ Decided |
| How users use it | Website dashboard (any computer or phone, no installs) + automatic email/text alerts | ✅ Decided |
| First screen | Scoreboard: current energy use, savings today, green/red status for smart vs wasteful cooling, one-tap weekly graph | ✅ Decided |
| Auto vs manual | Suggest savings first with a big "Apply" button; full auto-mode is an option owners can switch on later | ✅ Decided |
| Data source | Works with a simple web form first (owner types in their monthly bill); live smart-meter connections come later | ✅ Decided |
| New owner experience | Every new account gets a "demo building" with realistic sample data + a one-minute guided tour | ✅ Decided |
| How savings are calculated | Simple formula using bill amount + building size, compared to similar buildings, clearly labeled "estimate"; replaced by real measurements when live data arrives | ✅ Decided |
| Success goal | Log in, see a demo building's energy + savings, click a button and watch the bill go down | ✅ Decided |
| Tech plan (builder's choice) | Plain website (HTML/CSS/JS), no installs, data saved in the browser for now, free hosting later | ✅ Decided |
| Live weather | Connects to Open-Meteo (free weather service, no key or card) — current temperature + 5-day forecast, from a drop-down of 138+ tested Indian cities; updates instantly on city change, auto-refreshes every 10 minutes even while the page is open (real weather data changes at most every 15 minutes), manual refresh button | ✅ Decided |
| Multiple buildings | Owners can add many buildings (name, city, size, monthly bill) and switch between them; each building keeps its own energy history, savings and alerts | ✅ Decided |
| Publishing | Live on GitHub Pages (free) at https://yn8610.github.io/coolbreeze/ — edits are uploaded automatically, link never changes | ✅ Decided |
| Brand name | CoolBreeze (kept after a name-search) | ✅ Decided |
| Brand look & voice | Greens + blacks, Mamaearth-style: clean, natural, calm, friendly expert voice; tagline "Less electricity · Never less comfort"; full kit in docs/brand-guide.md | ✅ Decided |

## Why it must save information

- Building owners need **accounts** to log in safely.
- **Sensor readings** (temperature, cooling on/off) must be recorded so the
  system can adapt automatically.
- **Energy history** must be stored so owners can see how much money and
  carbon they saved over time.

## Guides (other docs)

- [How to Run the App](how-to-run.md) — how to open and share the app
- [Glossary](glossary.md) — every term in one short line
- [Updates Log](updates-log.md) — everything we change, in date order
- [Brand Guide](brand-guide.md) — the look, voice, colours, marketing words and pictures
- [Brand Guide](brand-guide.md) — the look, voice, colours, marketing words and pictures

## How to use this document

- Plain English only. No jargon without a one-line explanation.
- Every decision we make gets added to the table above the same day.