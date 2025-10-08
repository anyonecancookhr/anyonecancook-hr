# Anyone Can Cook HR - Website (GitHub Pages)

This is a small, static website intended for the HR team to list job openings and accept applications via email.

## Files & Structure
- `index.html` — Home / About Us / Brands
- `careers.html` — Careers page (loads `jobs.json` dynamically)
- `apply.html` — Apply page (opens email to hrpurpleoven2@gmail.com)
- `style.css` — Stylesheet (purple + lavender theme)
- `jobs.json` — Job listings (edit this to update job postings)
- `logo.png` — Placeholder main logo
- `favicon.png` — Small icon for browser tab
- `brands/` — Folder for brand logos (placeholders included)
- `posters/` — Folder for job poster images (placeholders included)

## How to publish (GitHub Pages)
1. Create a new public repository on GitHub (e.g. `anyonecancook-hr`).
2. Upload the contents of this folder to the repository root (do not upload the zip file itself).
3. In the repo, go to **Settings → Pages** and choose branch `main` (or `master`) and root (`/`), then save.
4. Wait 1–2 minutes and your site will be live at: `https://<your-username>.github.io/<repo-name>`

## How to edit job postings
- Open `jobs.json` in a text editor and modify or add objects. Each job object should have:
  - `title`, `location`, `poster`, `description`, `requirements` (array), `apply_email`
- Commit the changes to GitHub — your site will update automatically.

## Logos and Posters
- Replace files in `brands/` with your real logos (same filenames), and upload posters to `posters/`.
- If you want different filenames, update `jobs.json` and the HTML accordingly.

## Support
If you want, I can walk you step-by-step through uploading to GitHub Pages and updating the JSON after you download the zip.
