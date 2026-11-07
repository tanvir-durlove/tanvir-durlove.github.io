# NextGen Tool — tanvir-durlove.github.io

Portfolio site for NextGen Tool Android apps, hosted on GitHub Pages at
https://tanvir-durlove.github.io/

## Design

Light-only design system. No dark theme, no auto-dark mode.
One shared stylesheet (`assets/css/main.css`) and one shared script
(`assets/js/main.js`) serve every page; each app page only sets its accent
colour with a body class (`accent-green`, `accent-coral`, `accent-orange`).

## Pages

- `/` — portfolio home (Battery Forensics, Nudgy, One Word A Day)
- `/battery-forensics.html` — Battery Forensics landing
- `/privacy.html` — Battery Forensics Privacy Policy & Terms
- `/nudgy/` — Nudgy landing
- `/nudgy/privacy-policy.html` — Nudgy Privacy Policy
- `/nudgy/delete-account.html` — Nudgy account deletion (web)
- `/nudgy/join/` — Nudgy group-invite fallback page (canonical; `/nudgy/join.html` redirects here)
- `/one-word-a-day/` — One Word A Day landing
- `/one-word-a-day/privacy-policy.html` — One Word A Day Privacy Policy

## Do not move or rename

- `app-ads.txt` — AdMob authorization, must stay at the domain root.
  One line covers every app under publisher `pub-7794111343358988`.
- `.well-known/assetlinks.json` — Android App Links for Nudgy deep links.
- The privacy-policy URLs above — they are the URLs entered in Play Console.
  Restyle them, never rename them.

## Editing

All pages are plain static HTML/CSS/JS, no build step. Keep new pages on the
shared stylesheet so the design stays consistent.
