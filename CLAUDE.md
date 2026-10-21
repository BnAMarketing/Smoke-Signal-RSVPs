# Smoke Signal RSVPs — public image host for the Smoke Signals invitation

This note is loaded into context whenever Claude Code works in this folder. Read it first.

## What this folder is for
Images for the B&A **Smoke Signals** event (Nov 4 2026, Huntsville), served by GitHub Pages
(public repo `BnAMarketing/Smoke-Signal-RSVPs`) so invite emails and pages can link to them.
The app itself — RSVP page, back office, Apps Script backend — lives in `BnAMarketing/B-A-Smoke-Signals-Event-`.

## What's here
- `smoke-signals-invite.gif` / `.png` — animated + still invite (the email's "Envelope image link")
- `smoke-signals-card-front.png`, `smoke-signals-card-back.png` — printed card art
- `ba-logo-white.png`, `insignia.png` — marks

## Good to know
- **File names are URLs.** Renaming or moving a file breaks every email and the Sheet's Settings tab that points at it. Replace in place with the same name instead.
- Pushing to `main` publishes immediately. Ask before pushing.
- Keep images web-sized (email clients choke on multi-MB GIFs; the invite GIF is ~0.9 MB).
- Brand: `anthropic-skills:ba-brand-kit`.
