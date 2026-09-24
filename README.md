# Limbu Health Buddy

A personal fat-loss app that runs in your phone's browser. Limbu, a small lemon, hops onto whatever you tap and guides you through the day.

**What's inside**

- **Today** – a time-wise plan for the day (water, pre-workout, gym, every meal, walk, sleep) with tick boxes and a daily score. Water, steps and sleep tracking.
- **Meals** – a different menu for every day of the week (veg, egg or non-veg), with calories, protein and what to skip at each time.
- **Workout** – a 7-day gym plan. Tick each set, write the weight you lifted, and see what to lift next time.
- **Body** – a muscle map. Tap a muscle to see which exercises work it most, or tap an exercise to see every muscle it works.
- **Progress** – weight and waist check-ins, a trend chart against the plan pace, goal date, and the two phases (fat loss, then build muscle).
- **Ask Limbu** – tap Limbu for quick answers about food, hunger, parties, protein, sweets, sleep, workouts and belly fat.

---

## Put it on GitHub Pages (free)

You need a free GitHub account.

1. Sign in at **github.com**.
2. Tap **+** (top right) → **New repository**.
3. Name it `limbu` (any name works). Keep it **Public**. Tap **Create repository**.
4. On the new repository page tap **uploading an existing file**.
5. Select these 5 files from this folder and upload them together:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
6. Tap **Commit changes**.
7. Go to **Settings** → **Pages**.
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**, **Branch** to `main` and folder to `/ (root)`. Tap **Save**.
9. Wait 1–2 minutes and refresh the page. Your app link appears at the top, for example:
   `https://YOUR-USERNAME.github.io/limbu/`

Only `index.html` is required for the app to work. The other 4 files make it installable and let it open without internet.

## Install it on your phone

- **Android (Chrome):** open your app link, then tap **Install app** on the Today screen, or the browser menu **⋮** → **Add to Home screen**.
- **iPhone (Safari):** open your app link, tap **Share** → **Add to Home Screen**.

It then opens like a normal app, full screen, with the Limbu icon.

## First-time setup

Tap the person icon (top right) and fill in your name, age, height, start weight, goal weight, diet, wake-up time and gym time. Tap **Save**. Your calories, protein, menu and schedule adjust to these numbers.

**Moving from the Claude version:** open the settings, tap **Restore backup**, and pick the `limbu-backup-….json` file. Everything you saved comes back.

## Your data

- Everything you enter is saved **only in your phone's browser**. Nothing is sent anywhere, and nothing is stored on GitHub.
- Clearing the browser's data, or changing phones, removes it. So open settings and tap **Download backup** once a week.
- **Never upload a backup file to GitHub.** A public repository can be seen by anyone.
- The app code itself is public on GitHub, but it contains none of your personal data.

## Updating the app later

1. Upload the new `index.html` to the same repository (it replaces the old one).
2. Open `sw.js`, change `limbu-v2` to `limbu-v3` (next number each time), and upload it too.
3. Open the app twice. The second time shows the new version.

## Good to know

- The smart AI chat answers work only in the Claude version of this app. The GitHub version uses Limbu's built-in tips, which cover the common questions.
- Calories and protein are close estimates for normal home portions.
- This is general food and fitness guidance, not medical advice. If you have a health condition, check with a doctor before starting.
