# GeniusScout — Launch Site + App

Playfully academic 15‑minute talent screen.

## What’s inside
- **/index.html** — branding launch page
- **/app/** — the working GeniusScout web app (static, no backend)
- **/assets/** — logo, wordmark, favicon, social image
- **LICENSE** — MIT
- **.nojekyll** — prevents Jekyll processing on GitHub Pages

## One‑click deploy on GitHub Pages
1. Create a new repo on GitHub (e.g., `geniusscout`).
2. Upload these files (drag‑and‑drop the zip contents into the repo).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:
   - **Source:** *Deploy from a branch*
   - **Branch:** *main* (or *master*) and folder `/ (root)` → **Save**
5. Wait for the green check. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

### Custom domain (optional)
1. In your DNS, create a CNAME pointing your domain (e.g., `genius.example.com`) to `username.github.io`.
2. In **Settings → Pages**, set your custom domain and enable HTTPS.
3. Add a `CNAME` file at the repo root containing just your domain (no protocol).

### Local preview
Open `index.html` directly in a browser. The app lives under `/app/` and also works locally.

### Editing the corridor data (Right‑On‑Track) — not applicable here
This project is only GeniusScout. Data is embedded in the app.

---

Built 2025-09-28.
