# Android App Modification & Data Extraction

**Jeff** — independent developer, Nigeria

**Contact:** jeph600@gmail.com · @kryptoeweb3

**Availability:** 3–4 hrs/day, remote · paid in USD

I modify Android apps and turn their data into something usable — a panel inside the app,
a clean spreadsheet, a chart.

---

## Selected work

### 1. In-app computed summary for a sports-statistics app

**Base:** consumer match-statistics Android app.

**Built:** a daily computed summary generated from the app's own internal dataset and
rendered inside the existing interface.

**How:** decompiled with apktool and jadx; mapped the internal data model; added a parsing
layer; injected a new view into the existing layout; rebuilt and signed.

**Tools:** apktool, jadx, smali/baksmali, Python, apksigner

**Demo:** https://youtube.com/shorts/YjSsxAFKsEI

### 2. Custom scoring model inside a live-score client

**Base:** SofaScore Android client.

**Built:** extracted the client's live match-data feed and ran a custom scoring model over
it, with the output displayed as an in-app panel.

**How:** reverse engineered the client's data layer, identified the feed structure, wrote the
scorer, integrated it into the app's rendering path.

**Tools:** jadx, smali, Python, apktool

**Demo:** https://youtube.com/shorts/Ehd1Ogr7Hdg

---

## Services

| Service | What you get |
|---|---|
| **Data extraction** | App → clean spreadsheet or dashboard. One-off or scheduled. |
| **App modification** | Features, panels, fixes, rebuilds — for apps you own. |
| **Automation** | Scripts that collect, transform or publish data on a schedule. |

**Process:** you send the app or the requirement → I send a free sample → fixed price agreed
→ delivery, with one free revision.

**Scope:** all work is done on my own devices, on apps I use. I don't distribute modified
builds of third-party apps, and I don't take work that involves bypassing payment, licensing
or another person's account.

---

*Open to freelance work and one-off builds. Remote, worldwide.*
