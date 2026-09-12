# USUS Website

A single-page site for USUS (أُسُسْ) — interior design studio.

## Files
- `index.html` — all page content
- `styles.css` — all styling (colors, type, layout)
- `assets/` — logo and placeholder project graphics (swap these for real photos later)

## Publish it for free on GitHub Pages

1. **Create a GitHub account** at github.com if you don't have one.
2. **Create a new repository.**
   - Click the "+" in the top right → "New repository."
   - Name it `usus-website` (any name works).
   - Set it to Public.
   - Click "Create repository."
3. **Upload these files.**
   - On the new repo's page, click "uploading an existing file."
   - Drag in `index.html`, `styles.css`, `README.md`, and the whole `assets` folder.
   - Click "Commit changes."
4. **Turn on GitHub Pages.**
   - Go to the repo's "Settings" tab → "Pages" (left sidebar).
   - Under "Source," choose the `main` branch and `/ (root)` folder.
   - Click "Save."
   - GitHub will give you a live link, usually `https://<your-username>.github.io/usus-website/`, live within a minute or two.
5. **Connect your own domain (ususdesign.com).**
   - Still in Settings → Pages, enter `ususdesign.com` under "Custom domain" and save.
   - GitHub shows you DNS records to add. Log in to wherever you bought the domain and add those records (usually A records pointing to GitHub's IPs, plus a CNAME for `www`).
   - This step can take a few hours to propagate.

## Before this is truly done
- Swap the placeholder line-art SVGs in `assets/` for real project photos (Salman, Belman, Abdelkhalek renders).
- Replace the placeholder email and phone number in the Contact section of `index.html` with your real ones.
- Test the logo at small sizes (favicon) — this was flagged earlier and still hasn't been checked.
