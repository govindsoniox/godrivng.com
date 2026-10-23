# GoDrivng

Website for GoDrivng driving school, built as a plain static site (no build step) for GitHub Pages.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Home page: lessons, how booking works, contact |
| `terms.html` | Terms and Conditions page |
| `styles.css` | Shared styling |

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `godrivng`).
2. Upload these files to the root of the repository (or `git add . && git commit && git push`).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or so, your site will be live at `https://<your-username>.github.io/<repo-name>/`.

Tip: if you name the repository `<your-username>.github.io`, the site is served from `https://<your-username>.github.io/` instead.

## Before you go live

- In `index.html`, replace the contact placeholders (phone, email, area covered).
- Check the business name spelling ("GoDrivng") everywhere; search and replace if you want to change it.
- Optionally add a custom domain under **Settings → Pages → Custom domain**.
