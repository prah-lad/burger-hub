# Burger Hub Eibar — Website

Official website for **Burger Hub**, smash burger restaurant in Eibar, Gipuzkoa (Spain).

Built with plain HTML, CSS and JavaScript — no build step, no dependencies. Works out of the box on GitHub Pages.

## Structure

```
index.html      — the whole site (single page, in Spanish)
css/style.css   — styles (dark theme, brand red/orange)
js/main.js      — mobile menu + scroll animations
assets/         — optimized WebP images (burgers + logo)
favicon.svg     — browser tab icon
```

## How to launch on GitHub Pages (free hosting)

1. Create a new repository on [github.com/new](https://github.com/new) — name it e.g. `burger-hub`, keep it **Public**, and do NOT add a README.
2. In Terminal, run:

   ```bash
   cd "/Users/prahlad/Documents/Projects/burger-hub-website"
   git remote add origin https://github.com/YOUR_USERNAME/burger-hub.git
   git push -u origin main
   ```

3. On GitHub, open the repo → **Settings** → **Pages** → under "Branch" choose `main` and `/ (root)` → **Save**.
4. After ~1 minute your site is live at `https://YOUR_USERNAME.github.io/burger-hub/`

### Custom domain (optional)

If you buy a domain like `burgerhub.eus` or `burgerhubeibar.com`, add it in **Settings → Pages → Custom domain** and point the domain's DNS to GitHub Pages.

## Updating the menu

All menu items and prices are in `index.html` — search for the burger name and edit the text/price directly, then commit and push. The site updates automatically.
