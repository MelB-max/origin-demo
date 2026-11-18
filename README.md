# ORIGIN · new starter portal (demo)

**Live demo:** https://melb-max.github.io/origin-demo/ · click **New starter** or **Manager** on the sign-in card. No sign-up, nothing is sent anywhere.

ORIGIN is an onboarding portal: a guided path through gated training modules, with progress, quizzes, daily check-ins and a dashboard for the people running the training. This repo is a **static demo of the interface and navigation**. It's dressed as "Halcyon", a made-up marketing agency: the company, people, training content and numbers are all fictional, and the backend is replaced by canned data in the browser.

## What to look at
- **Landing:** a midnight "garden" that leans towards your cursor, a one-time-code sign-in, monthly stats.
- **Home:** a living vine. Each leaf is a module; leaves grow as you finish material and the flower blooms when you're done.
- **Modules:** each opens at 80% of the one before. Flip cards, a step-through flow, an "on-brand or off-brand?" sorting game, discipline tabs, quizzes, stickers and confetti.
- **Daily check-in:** a streak flame, backfill for missed days, and a lock that keeps the portal closed until today's check-in is in.
- **Manager dashboard:** cohort progress against schedule, who's falling behind, starter-form analytics, pitch-call scorer calibration, attendance, tip analytics and access control.
- **Themes:** light, dark and four palettes; tinted pages per module.

## Built with
Plain HTML, CSS and JavaScript (no framework). In production it runs as a static site on Cloudflare with a Google Apps Script backend: email one-time codes, signed session tokens, Google Sheets as the database.
