# StairSplit Support Website

Lightweight static support and privacy pages for the StairSplit iPhone app. The site has no build step, JavaScript, analytics, cookies, or external asset dependencies.

## Files

- `index.html` — app setup, workout, history, settings, and support contact guidance
- `privacy.html` — privacy policy for the iOS app
- `style.css` — responsive navy and blue site styles

## Before publishing

The support address is [stairsplitsupport@gmail.com](mailto:stairsplitsupport@gmail.com). The app is described as a $2.99 one-time App Store purchase.

The privacy page reflects the current iOS app implementation reviewed for this site: workouts and settings are saved in local app storage; the app code has no network, analytics, or advertising integrations. Review the policy again if app data handling changes.

## Deploy with GitHub Pages

1. Push this repository’s `main` branch to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for the Pages deployment to finish. GitHub will show the public site URL in **Settings → Pages**.

Both pages are served from the repository root, so `index.html` is the homepage and `privacy.html` is available at `/privacy.html`.
