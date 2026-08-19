# CoolBreeze — Brand Guide

One easy document with everything about how CoolBreeze looks and sounds.
Plain English only. Updated whenever we change something.

---

## 1. Identity & positioning

**CoolBreeze is a smart cooling dashboard for building owners and AI data
centre operators in India. While other apps just show reports and numbers,
CoolBreeze tells you exactly what to do — one tap applies the saving — and
links live weather to your cooling so you're never cooling when you don't
need to. Our promise: less electricity, never less comfort.**

| Question | Our answer |
|---|---|
| What it does | Watches a building's cooling 24/7, suggests exactly when to ease off, applies it with one tap |
| Who it's for | Owners/managers of commercial buildings and AI data centres in India |
| What's different | Other apps show reports; we tell you what to do + connect weather to cooling |
| The promise | Less electricity, never less comfort |
| The name | CoolBreeze — kept (decided after a full name hunt!) |

## 2. Tone of voice

**Sound like:** a calm, confident, friendly expert — a helpful mentor.
Simple words, short sentences, no jargon. Inspired by helpful tech
reviewers on YouTube.

| Say this ✅ | Not this ❌ |
|---|---|
| "One tap. Lower bill." | "Utilise our platform to optimise operational expenditure." |
| "Real weather for your real city." | "Leverage robust meteorological datasets." |
| "Try the demo — it takes 60 seconds." | "Engage with our comprehensive free trial." |
| "Watch the bill fall." | "Monitor cost trajectories quarterly." |

## 3. Colours & visual style

**Look:** clean, natural, calm — like fresh air in a building. Inspired by
Mamaearth: soft white space, friendly rounded shapes, greens doing the
talking, black for strength.

| Colour | Plain-English name | Where it lives |
|---|---|---|
| `#0E3B2E` | Deep Forest | Headlines, logo, dark backgrounds |
| `#1E6F50` | Leaf Green | Hero colour, buttons, chart bars |
| `#3DA35D` | Fresh Mint | Highlights, accents, "saving" parts |
| `#131313` | Rich Black | Body text, borders |
| `#F4FAF6` | Soft White | Backgrounds — clean and airy |
| `#A8CBB8` | Misty Sage | Soft lines, quiet details |

Extra shades we use: `#174F3A` (darker button), `#4A6658` (quiet text),
`#D9EBE0` (light green on dark), `#E4F4EA` (pale green boxes),
`#B45309` (gentle warning, not scary red).

**Lettering:** round, friendly, bold headlines; simple clean body text.

## 4. Marketing words & pictures

**One action everywhere: "Open the free demo building — see what you'd save."**

### WhatsApp message — `brand/whatsapp-message.txt`
```
Hi! 👋 Meet CoolBreeze — the smart cooling dashboard for buildings.

It watches your cooling 24/7 and tells you exactly when to ease off, so the
electricity bill drops without the building ever getting hot. Live weather
for your city + savings in rupees every day.

Open the free demo building and see what you'd save — 60 seconds, no sign-up:
yn8610.github.io/coolbreeze
```

### Instagram post — `brand/instagram-post.svg` (square, 1080×1080)
- Message: "Your cooling is on 24/7. It only needs to run when it's hot."
- Picture: a sun over a cloud, a green arrow falling onto a stack of ₹ coins.
- Button: "Tap once · Save every month" + the link.
- Action: open the demo.

### Instagram story — `brand/instagram-story.svg` (full screen, 1080×1920)
- Message: "How much is your building paying to stay cool?"
- Picture: a thermometer — full level (waste) turning mint green (saving).
- Button: "Try the demo building · Free · 60 seconds" + the link.
- Action: open the demo.

### Flyer A5 — `brand/flyer-a5.svg` (print, 148×210 mm)
- Message: "Cool less. Save more."
- Dots: one tap applies the savings · live weather for your city ·
  savings in rupees every day.
- Button: "Try the free demo" + the link.
- Action: open the demo.

### Poster A4 — `brand/poster-a4.svg` (print, 210×297 mm)
- Message: "Is your cooling working when it shouldn't be?"
- Picture: seven bars falling after "one tap" (leaf green → fresh mint).
- Chips: 24-hour watch · 1 tap to save · 0 loss of comfort.
- Button: "Try the free demo building" + the link.
- Action: open the demo.

All words inside pictures were spelling-checked before saving. ✅

## 5. Logo

**The logo is the owner's design** (a big fan-swirl "C" with the wordmark and
a small text line) — used exactly as designed. We made a few versions of it
for different places:

| File | What it is | When to use |
|---|---|---|
| `brand/logo-primary.svg` | The full logo, black | Light backgrounds: login page, flyers, posters |
| `brand/logo-white.svg` | The full logo, white | Dark backgrounds: app header, stories |
| `brand/logo-mark.svg` | Swirl + wordmark, black | Marketing pictures on light backgrounds |
| `brand/logo-mark-white.svg` | Swirl + wordmark, white | Marketing pictures on dark backgrounds |
| `brand/logo-simple.svg` | The fan-swirl symbol alone, green | Browser tab icon (favicon), tiny stamp places |
| `WhatsApp-Image-...svg` (project root) | The original file you sent | Keep it safe as the master copy |

The wordmark and text inside the logo come from the owner's artwork and are
used unedited.

**Ready-to-share PNG copies** live in `brand/png/` (same designs, perfect
for WhatsApp, email, printing):

| PNG | Size | Best for |
|---|---|---|
| `logo-primary.png` | 1600×800, clear background | Light places |
| `logo-white.png` | 1184×323, clear background | Dark places |
| `logo-mark.png` / `logo-mark-white.png` | 1184×323, clear background | Pictures on light / dark |
| `logo-simple.png` | 614×614, clear background | Small stamps, avatars |
| `instagram-post.png` | 1080×1080 | Feed post, WhatsApp |
| `instagram-story.png` | 1080×1920 | Story, status |
| `flyer-a5.png` | 1748×2480 (A5 @ 300dpi) | Print |
| `poster-a4.png` | 2480×3508 (A4 @ 300dpi) | Print |

## 6. The website wears the brand too

- Login page: the real logo (black) on the card, tagline underneath.
- Dashboard header: the white version of the logo on the deep-green bar.
- Browser tab icon (favicon): the green fan-swirl symbol.
- Marketing pictures (post, story, flyer, poster) all use the real logo:
  the mark in black on light, white on dark.
- The app itself: `index.html`, `dashboard.html`, `style.css`.

## 7. Where things live

- Pictures + WhatsApp text: the `brand/` folder.
- This guide: `docs/brand-guide.md` (linked from `PRD.md`).
- Live website: https://yn8610.github.io/coolbreeze/