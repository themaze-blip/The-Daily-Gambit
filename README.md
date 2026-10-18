# The Daily Gambit

Small moves. Bigger you. A habit-tracking chess game you can install on your computer and phone.

## Put it on GitHub (once)
1. Create a new repository on github.com (for example `daily-gambit`). Public is fine, because GitHub Pages is free for public repos.
2. Upload everything in this folder (keep the `vendor` and `icons` folders and the `.nojekyll` file), then commit.
3. Go to **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute your app is live at `https://YOUR-NAME.github.io/daily-gambit/`.

## Install it
- **Computer (Chrome or Edge):** open the link, click the install icon in the address bar.
- **Android (Chrome):** menu, then **Install app** or **Add to Home screen**.
- **iPhone (Safari):** Share button, then **Add to Home Screen**.

It works offline after the first visit.

## Keep phone and computer in sync
1. On GitHub go to **Settings > Developer settings > Personal access tokens > Tokens (classic)** and create one with **only the `gist` permission**.
2. In the app open **Settings > Sync with GitHub**, paste the token and press **Connect**. Do the same on each device.
3. The app saves your game, history and board style to a private gist called "The Daily Gambit sync". Changes are pushed a couple of seconds after you make them and pulled when you open the app (and every 45 seconds). The newest change wins.

The token is stored only in that device's browser. Treat it like a password.

## Updating
Upload a new `index.html` to the repo. Installed apps pick it up the next time they are opened online.
