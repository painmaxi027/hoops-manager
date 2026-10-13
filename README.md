# Hoops Manager — GitHub Pages build

Static, browser-based live-coaching basketball management prototype. No build step or server required.

## Run locally
Open `index.html` in a modern browser. Save data uses this browser's localStorage.

## GitHub Pages
1. Create a **public** repository named `hoops-manager` in your GitHub account.
2. Add `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. After GitHub Pages reports deployment success, open the published site URL shown in Settings → Pages.

## Saves and backups
- Autosaves to localStorage in the current browser profile.
- Keeps up to five recent local snapshots where browser storage permits.
- Use **Export backup** to download a JSON save before clearing site data or changing devices.
- Use **Import backup** to restore a previously exported JSON. Import replaces the active local season after confirmation.
- This is local-only storage, not cloud sync. A public website does not mean your local season is automatically backed up online.

## Current prototype scope and limitations
Included: coaching presets, defensive schemes (man-to-man, 2–3, 3–2, 1–3–1, switch), pick-and-roll coverage, pressure, tempo and shot profile, lineups/substitutions, player-specific defensive assignments, energy/foul tracking, timeouts, possession simulation, box score, standings, results, local autosave, JSON import/export.

Not yet production-realistic: fictional teams and players only; simplified possession model; no true NBA rules, salary cap, contracts, trades, draft, full playbook diagrams, synchronized multi-device cloud saves, or verified current NBA 2026–27 roster data. Coaching settings influence simulation heuristically and are not a validated basketball engine. Test in-browser before treating it as a stable release.

Independent fan-made project; not affiliated with or endorsed by the NBA or 2K.
