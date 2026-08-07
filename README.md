# Boat Vendor Dashboard — Modular Build

This version keeps the same working dashboard but separates the large file into:

- `index.html` — page structure
- `css/styles.css` — dashboard styling
- `js/app.js` — current application logic

This is the safe first refactor. It preserves the existing Supabase, roles, live sync, vendors,
yachts, availability, bookings, and notifications behavior before we split `app.js` further
into feature-specific files.

## Upload to GitHub

1. Keep your existing live dashboard available as a backup.
2. Unzip this project.
3. In the `boat-vendor-dashboard` GitHub repository, replace the existing files with:
   - `index.html`
   - the `css` folder
   - the `js` folder
4. Commit the changes.
5. Wait for Vercel to redeploy.
6. Test sign-in, live sync, vendor save, availability save, booking save, and Team Access.

Do not upload the ZIP itself as the website root; upload the files and folders inside it.
