# Put Lunacy Depths on your iPhone for free

Total cost: $0. Time: about 15 minutes. Everything is done in a web browser on your Windows PC, then on your iPhone.

## 1. Make a free GitHub account
Go to https://github.com and sign up.

## 2. Create a home for the game
1. Click **+** (top right) → **New repository**.
2. Name it `lunacy`.
3. Choose **Public**. Free hosting only works for public repositories.
4. Click **Create repository**.

## 3. Upload the game files
1. On the new repository page, click **uploading an existing file**.
2. Unzip `lunacy-app.zip` on your PC. Drag in everything inside the folder: `index.html`, `sw.js`, `manifest.webmanifest` and the four `.png` icons. You don't need to upload this guide.
3. Click **Commit changes**.

## 4. Turn on free hosting
1. In the repository go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/ (root)**, then click **Save**.
4. Wait 1 to 2 minutes and refresh the page. Your game's link appears at the top:
   `https://YOUR-USERNAME.github.io/lunacy/`

## 5. Install it on your iPhone
1. Open the link in **Safari**. It must be Safari, not Chrome.
2. Tap the **Share** button (the square with an arrow).
3. Scroll down, tap **Add to Home Screen**, then **Add**.

Lunacy now has its own icon, opens full screen, and works without internet.

## 6. Bring your current progress over
Your progress in the Claude link and in the installed app are stored separately, so copy it across once:

1. In the **Claude link** version: tap your profile circle → **Settings** → **Copy backup code**.
2. In the **installed app**: profile → **Settings** → **Restore from code**. Paste the code, then tap **Restore this save** twice.

Copy a fresh backup code every now and then and keep it in your Notes app. If your iPhone ever clears the app's storage, the backup gets you straight back.

## 7. Updating the game later
When I send you a new version:

1. In your `lunacy` repository, click **Add file → Upload files** and drag in the new `index.html` and `sw.js`.
2. Click **Commit changes**.
3. Close and reopen the app on your phone. It picks up the update the next time it has internet.

(Each new `sw.js` I send has a new version number inside. That number is what tells phones to download the update.)

## 8. Testers
Post your link in a **#testers** channel on Discord. Anyone with an iPhone or Android phone can install it the same way. On Android, open the link in Chrome and tap **Install app** or **Add to Home screen**.

## When you're ready for the real stores
| Store | Cost | Notes |
|---|---|---|
| Google Play | $25 one time | Can be built on Windows. New personal accounts must run a 14-day closed test with at least 12 testers, and your Discord testers can cover that. |
| Apple App Store | $99 a year | Building the app needs a Mac. A cloud build service can do this without one. |

The game files stay the same, and they get wrapped into store apps when you're ready.
