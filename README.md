# ORIGIN · training induction portal (demo)

**Live demo:** https://melb-max.github.io/origin-demo/ · click **Trainee** or **Manager** on the sign-in card. No sign-up, nothing is sent anywhere.

ORIGIN is the portal new sales joiners use from day one: a guided path through five training modules, with progress, quizzes, daily check-ins and a dashboard for the training team. This repo is a **static demo** of the interface. The company ("Kestrel Academy"), people and numbers are made up, and the backend is replaced by canned data in the browser.

## What to look at
- **Landing:** a midnight "garden" that leans towards your cursor, a one-time-code sign-in, live monthly stats.
- **Home:** a living vine. Each leaf is a module; leaves grow as you finish material and the flower blooms when you're done.
- **Modules:** Onboarding → Product → Sales → Soft skills → Mock calls. Each opens at 80% of the one before. Flip cards, a call-flow stepper, a "would you send this?" sorting game, quizzes, stickers and confetti.
- **Daily check-in:** a streak flame, backfill for missed days, and a lock that keeps the portal closed until today's check-in is in.
- **Manager dashboard:** live batch progress vs schedule, at-risk trainees, induction form analytics, mock-call scorer calibration, attendance, tip analytics and access control.
- **Themes:** light, dark and four palettes; tinted pages per module.

## Built with
Plain HTML, CSS and JavaScript (no framework). In production it runs as a static site on Cloudflare with a Google Apps Script backend: email one-time codes, signed session tokens, Google Sheets as the database.
