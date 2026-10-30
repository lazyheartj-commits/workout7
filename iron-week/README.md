# Iron Week Log

A 7-day weightlifting log for tracking sets, reps and weight. It includes a 30-45 minute program with no back squats or deadlifts. It runs in any browser, can be installed on your phone's home screen, and works offline once it has loaded.

## Put it on GitHub Pages (free)

1. Sign in at github.com and click **New repository**. Name it something like `iron-week`, make it **Public**, and click **Create repository**.
2. On the new repo page, click **uploading an existing file**. Drag in every file from this folder (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`), then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then click **Save**.
4. Wait a minute or two, then refresh the page. Your app link appears at the top, for example `https://YOUR-USERNAME.github.io/iron-week/`.

## Install it on your phone

- **iPhone (Safari):** open the link, tap Share, then tap **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the ⋮ menu, then tap **Install app** or **Add to Home screen**.

## Notes

- Your logs are saved on the device and browser you use. They don't sync between devices.
- To change the program, edit the `PLAN` list near the top of the `<script>` in `index.html`. Each exercise is `["Name", sets, "reps"]`.
- After editing the program, change `ironweek-v3` to a new number such as `ironweek-v4` so the app loads the new plan. This also clears the old log. If an update doesn't show up, change `CACHE` in `sw.js` too.
