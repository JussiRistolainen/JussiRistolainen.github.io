
# Arctic Adler — Static Site (GitHub Pages)

This folder contains a minimal 5‑page static site that passes typical marketplace “publisher website” checks.

## Files
- `index.html` — Home
- `assets.html` — Assets list
- `docs-tidemesh.html` — Product docs
- `support.html` — Contact page with form (Formspree)
- `privacy.html` — Privacy policy
- `styles.css` — Basic styling
- `.nojekyll` — Disables Jekyll processing for plain HTML

## Quick Deploy (GitHub Pages)
1. Create a repo named `<your-username>.github.io` on GitHub.
2. Upload these files to the repo root and commit.
3. In **Settings → Pages**, set Source to **Deploy from a branch**, Branch **main**, folder **/**.
4. Visit `https://<your-username>.github.io/`.

## Custom Domain (optional but recommended)
1. In **Settings → Pages → Custom domain**, enter your domain (e.g., `arcticadler.com`). GitHub will create a `CNAME` file.
2. In your domain DNS:
   - `www` → CNAME to `<your-username>.github.io`
   - apex (root) → A records to: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
3. Enable **Enforce HTTPS** once the certificate is ready.

## Contact form
- Replace the `action` URL in `support.html` with your Formspree endpoint (e.g., `https://formspree.io/f/abcdxyz`).
- Or use any other form provider (Tally, Basin, Netlify Forms).

