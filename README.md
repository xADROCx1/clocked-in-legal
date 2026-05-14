# Clocked In — Legal

Public-facing privacy policy and terms of service for the **Clocked In** mobile app, required for App Store and Google Play submission.

## Files
- [`index.html`](index.html) — Landing page linking to both documents
- [`privacy.html`](privacy.html) — Privacy Policy
- [`terms.html`](terms.html) — Terms of Service

## Hosting (GitHub Pages)
This folder is designed to be served as a standalone GitHub Pages site.

When pushed to a public repo (e.g. `clocked-in-legal`):
1. Repo → Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. URLs:
   - `https://<github-user>.github.io/clocked-in-legal/`
   - `https://<github-user>.github.io/clocked-in-legal/privacy.html`
   - `https://<github-user>.github.io/clocked-in-legal/terms.html`

These are the URLs you'll paste into:
- App Store Connect → App Privacy → Privacy Policy URL
- Google Play Console → Store presence → Main store listing → Privacy Policy
- In-app Settings → Privacy Policy / Terms of Service links

## Updating
Edit the HTML files directly, change the "Last updated" date at the top, commit, and push. GitHub Pages redeploys in ~30 seconds.
