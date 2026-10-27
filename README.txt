# Habittick — Personal Habit Tracker

## Included
- Premium, minimal, mobile-first interface with dark/light themes
- Add, edit, delete and complete habits
- **Completion time shown on the right** when a habit is marked complete (for example, `✓ 2:35 PM`)
- Completion timestamps saved locally and retained in daily history
- Daily completion percentage, streaks, weekly goals and analytics
- 50% and 100% daily completion celebrations
- Calendar history, per-habit stats, JSON export and restore
- Offline app shell through a service worker (HTTPS hosting and one initial online load required)

## Publish free on GitHub Pages from an iPhone
1. Open https://github.com/ and sign in.
2. Create a new public repository named **habittick**.
3. Upload these five files to the repository root: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, and `apple-touch-icon.png`.
4. Open repository **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for deployment and open the URL shown in Settings → Pages.
7. On iPhone, open the published site in Safari → Share → Add to Home Screen.

## Data and privacy
Habittick stores habits and completion times in this browser on this device. It does not automatically sync across devices. Export a JSON backup regularly from Settings. Do not put API keys or secrets in a public repository.
