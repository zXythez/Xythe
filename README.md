# Xythe • Neon Lab (Static Site)

This is a dead-simple static site you can host forever for free.

## How to use (long-term, easy)
1. Create a GitHub repo (name it `xythe-site`).
2. Upload these files (`index.html`, `netlify.toml`, `README.md`).
3. In Netlify: New site from Git → pick your repo.
   - **Build command**: *(leave empty)*
   - **Publish directory**: `/` (root)
4. Netlify gives you a live URL. Change the site name in settings or add a custom domain later.

### Edit content
- Replace the YouTube IDs inside the three `<iframe>` tags.
- Change text in `index.html` as you like.
- Commit & push. Netlify auto-updates.

## Optional: GitHub Pages instead of Netlify
- In the repo: Settings → Pages → Deploy from branch → `main` → `/ (root)`.
