# Feels Like Weather — GitHub Pages package

This folder is ready to upload to a GitHub repository and publish with GitHub Pages.

## What is inside

- `index.html` — the app entry file GitHub Pages expects for a static site
- `apple-touch-icon.png` — icon for Add to Home Screen on iPhone

## Fastest setup on GitHub

1. Go to GitHub and create a **new public repository**.
2. Open the new repository.
3. Click **Add file** → **Upload files**.
4. Upload `index.html` and `apple-touch-icon.png` from this folder.
5. Click **Commit changes**.
6. In the repository, go to **Settings**.
7. In the left sidebar, click **Pages**.
8. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
9. Click **Save**.
10. Wait about 1–3 minutes.
11. Your site should appear at:
   - `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## After it is live on iPhone

1. Open the GitHub Pages link in **Safari** on your iPhone.
2. Test location access.
3. Tap **Share** in Safari.
4. Choose **Add to Home Screen**.

## Notes

- GitHub Pages serves the site over **HTTPS**, which helps browser geolocation work properly.
- If location permission is denied, the app falls back to Stavanger as the default location and still lets you search for a city.
