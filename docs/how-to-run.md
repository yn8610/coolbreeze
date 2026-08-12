# How to Run the App

Plain-English guide. Updated whenever something changes.

## Right now (this week)

The app lives in this folder. To try it:

1. Double-click **index.html** — it opens in your web browser.
2. Click **Create account**, pick a username and password, and press the button.
3. You arrive at the dashboard with a **demo building** full of sample data.
4. Click the big green **"Apply smart cooling"** button and watch the graph bar drop and the status turn green.

No installs. No credit card. Everything is free.

## What's inside this folder

| File | What it is |
|---|---|
| `index.html` | Log in / create account page |
| `dashboard.html` | The main dashboard (buildings, weather, scoreboard, graph, savings, apply button) |
| `style.css` | The look of the app (colours, fonts, layout) |
| `docs/` | All our guides, led by `PRD.md` |

## Things to try in the dashboard

- **Add a building** with the "＋ Add building" button — give it a city, and
  it fetches that city's live weather automatically.
- **Switch buildings** by clicking the chips at the top.
- **Weather:** needs an internet connection. If it can't load, you'll see a
  friendly message — the rest of the app still works.

## Important: where data lives (for now)

Your accounts and demo-building data are saved **inside your own browser**
(technically called "localStorage"). That means:

- Logging in and using the app works perfectly on this computer.
- If you open it on a different computer, you'll need a new account there.
- Clearing your browser data removes the saved accounts.
- A real shared system (accounts + data on the internet) comes in a later
  version. That's when email/text alerts also become possible.

## How to share your project

The easiest free way to put it on the internet:

1. Make a free account at **GitHub** (github.com).
2. Create a repository (a folder on the internet) and upload these files.
3. Turn on **GitHub Pages** in Settings — you get a free website link
   (like `yourname.github.io/coolbreeze`) to send to friends and teachers.

We'll do this together when you're ready — it's step-by-step and free.
