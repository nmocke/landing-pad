# Landing Pad — SA Refugee Playbook

A privacy-safe, offline-capable mobile web app: a Day 1 to Year 5 resettlement
playbook with local estimates, a food map, cost trackers, and a green-card to
citizenship guide (PR / I-485, citizenship / N-400, family reunification /
I-730, legal red flags, and SA consulate / DIRCO contacts).

## Files
- `index.html` — the app (open this). The iPhone and Android copies are byte-identical.
- `manifest.webmanifest`, `sw.js`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` — home-screen install + offline support.

## Put it on GitHub (free hosting)
1. Create a new public repo, e.g. `landing-pad`.
2. Upload every file in this folder (keep them together).
3. Repo → Settings → Pages → Source: `main` branch, `/root` → Save.
4. Wait ~1 minute, then open `https://<your-username>.github.io/landing-pad/`.

## Add to an iPhone / Android home screen
- Open the Pages URL in Safari (iPhone) or Chrome (Android).
- iPhone: Share → Add to Home Screen. Android: menu → Add to Home screen / Install app.
- It then opens full-screen with the "LP" icon, and works offline after the first load.

## Does it remember what I tick?
Yes. Both the 17 activity checks and the new tracked actions (I-485, I-730, N-400,
DIRCO, CRS Legal) are saved on the device with localStorage. They persist across
reloads and app restarts on the same browser/device. Clearing browser data, or the
in-app "Clear data" button, resets them. Ticks do not sync between different devices.
