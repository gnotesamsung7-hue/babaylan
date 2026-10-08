# Babaylan: Rise of the Bakunawa

A turn-based strategy game drawn from Philippine mythology. Return from Kasamaan as a reborn
babaylan, rebuild your barangay, call the creatures of the old tales, and wake the Bakunawa
to swallow the moon before a rival does.

- `www/index.html` - the game (what goes inside the APK)
- `docs/index.html` - same game, for playing in a browser via GitHub Pages
- `.github/workflows/build-apk.yml` - builds the APK on every push to `main`

When you change the game, copy the new file into both `www/` and `docs/`.

## Getting the APK
1. Push this folder to a new GitHub repo named `babaylan` (GitHub Desktop works well).
2. Open the repo's **Actions** tab and wait for "Build Android APK" to go green (about 5 minutes).
3. Open the run, download **babaylan-debug-apk**, unzip it, and install `app-debug.apk` on your phone.

## Play in the browser
Settings > Pages > Deploy from branch > `main` / `docs`.
