# My Day — Time Tracker

A simple, mobile-first web app to plan your day, reserve the time you've already
committed, and instantly see how much free time you have left.

- **Reserve time** — block out commitments (work, gym, meals…) with start/end times and colors.
- **See what's left** — free gaps between your blocks are calculated automatically.
- **Timeline view** — a clean visual of your day with a live "now" line.
- **Per-day** — swipe between days; each day keeps its own plan.
- **Offline + private** — everything is stored locally on your device (no account, no server).

## Run locally
Just open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 4321
# then visit http://localhost:4321
```

## Deploy (GitHub Pages)
See the deploy steps in the chat, or: push this folder to a GitHub repo →
Settings → Pages → deploy from `main` / root. Your app will be live at
`https://<username>.github.io/<repo>/`.

## Add to iPhone home screen
Open the live URL in Safari → Share → **Add to Home Screen**. It launches
full-screen like a native app.
