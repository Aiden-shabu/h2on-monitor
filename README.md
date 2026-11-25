# H2On System Monitor

Web dashboard for the H2On microturbine backup power system (UT Tyler EENG 4115/4125 Senior Design, Team 1).

- **Simulation mode**: simplified model fitted to the full-size Simulink results (Chapters 5 and 6).
- **Field mode**: replays a CSV test log now; the live controller connection is added in Senior Design II.

Open the site: `https://<your-github-id>.github.io/h2on-monitor/`

Files: `index.html` (the whole app), `manifest.json` and `sw.js` (install as an app, open offline), `icon-192.png`, `icon-512.png`.
When you upload a new `index.html`, also change `CACHE` in `sw.js` (for example `h2on-v4`) so phones get the update.
