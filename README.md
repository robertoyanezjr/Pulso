# Pulso

Personal daily macro-tracking coach: send Claude a photo of what you're eating, get a calorie/macro estimate, and stay on target toward a fat-loss goal while preserving muscle.

See [`coach/SETUP_GUIDE.md`](coach/SETUP_GUIDE.md) to set it up — takes about 10 minutes.

- [`coach/PROFILE.md`](coach/PROFILE.md) — stats, targets, coaching style (edit this first)
- [`coach/CLAUDE_PROJECT_INSTRUCTIONS.md`](coach/CLAUDE_PROJECT_INSTRUCTIONS.md) — paste into a Claude Project
- [`coach/SETUP_GUIDE.md`](coach/SETUP_GUIDE.md) — step-by-step walkthrough
- [`coach/Pulso-Macro-Tracker.xlsx`](coach/Pulso-Macro-Tracker.xlsx) — persistent daily/weekly log (the chat itself doesn't remember past days)
- [`webapp/pulso-panel.html`](webapp/pulso-panel.html) — the "SENARA Health Read" dashboard, published as a Claude Artifact. Single self-contained HTML file, no build step. A full developer handoff package (architecture, functional requirements, data model, design system, screenshots, and a `REPLICATION_BRIEF.md` for another coding agent) was generated alongside this file — ask for it if you need it again.
