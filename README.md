# Linh Love Quiz ♡

A responsive nine-question Vietnamese questionnaire with a welcome screen and an admin dashboard.

## Setup
- Open `index.html` using a static server or GitHub Pages.
- For cross-device submissions, create a Supabase project, run `supabase-schema.sql`, then set the project URL and anon key in `supabase-config.js`.
- Create an admin user in Supabase Authentication. Sign in at `admin.html`.
- Never put a Supabase service-role key in frontend code.

Without Supabase, answers are stored only in the current browser's localStorage and cannot be viewed from another device.

## GitHub Pages
Repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
