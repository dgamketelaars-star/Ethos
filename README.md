# Visual Grading Builder V2

Mobile-first, single-file GitHub Pages app for visual grading.

## Deploy
Upload `index.html` to the root of your existing GitHub repository (replace the old version). In **Settings → Pages**, publish from the main branch/root folder. No build tools or API keys needed.

## Features
- Eight grading modes, with shared and task-specific observation blocks.
- A–G ranking with up/down controls, scores, per-output feedback and missing-answer indicators.
- Short English bullet generation with optional location, target, reference comparison and effect.
- Manual text editing and custom bullets.
- Local browser autosave, JSON backup export/import, and mailto email handoff.
- Offline-compatible after the page has loaded if the browser retains the page; no service worker included.

## Important
- The phone and laptop **do not share localStorage**. Use email, clipboard, or JSON backup to transfer work.
- `mailto:` opens your installed mail app. Long drafts may exceed email-app URL limits; use Copy as a fallback.
- Rankings are manually ordered; scores are independent and can tie. The app warns about duplicate scores.
- New task clears the current local task. Export a backup before starting another.
- The app does not connect to Feather or send any information automatically.
