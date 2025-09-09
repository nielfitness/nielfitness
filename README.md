# nielfitness — static site

Deploy to **GitHub Pages** (Deploy from branch):

1. Create a repo (e.g. `nielfitness`) and push these files:
   - `index.html`
   - `images/` (contains `progress_before.jpg`, `progress_after.jpg`)
   - `.nojekyll`
2. Repo → **Settings** → **Pages** →
   - *Build and deployment*: **Deploy from a branch**
   - *Branch*: `main` — `/ (root)`
   - Save
3. Open the URL GitHub shows (something like `https://<username>.github.io/nielfitness/`).

Custom domain (optional):
- `www.example.com` → CNAME to `<username>.github.io.`
- Apex `example.com` → A to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`

Then add the custom domain under **Settings → Pages**, and enable **Enforce HTTPS**.
