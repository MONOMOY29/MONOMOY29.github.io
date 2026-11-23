[README.md](https://github.com/user-attachments/files/35282307/README.md)
# Monomoy Dikshit — Portfolio

A responsive, recruiter-oriented portfolio site with a restrained green terminal aesthetic.

## Files
- `index.html` — layout, styling, animations and rendering.
- `profile.js` — the single source of truth for all profile content.
- `UPDATE.md` — how to maintain and publish the site.

## Run locally
Open `index.html` in a browser. If your browser restricts local scripts, run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a repository named `MONOMOY29.github.io` (or use an existing one).
2. Upload `index.html`, `profile.js`, and this documentation to the repository root.
3. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/ (root)`.
4. Wait for the Pages deployment and open `https://monomoy29.github.io`.

## Important
Before public release, review the `profile.js` content, especially dates, proof links, current status and the unconfirmed items in `UPDATE.md`. Do not publish private contact details unless you intend them to be public.
