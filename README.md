# Life Hub — mobile setup (GitHub Pages)

Your personal dashboard, hosted free so you can open it on your phone.

## One-time setup (5 minutes)

1. Go to **github.com** and sign in (or create a free account).
2. Click **+ → New repository**.
   - Name: `life-hub`
   - Set it to **Public** (required for free Pages) — the PIN screen protects the app itself.
3. On the new repo page click **uploading an existing file** and drag in the two files from this folder:
   - `index.html`
   - `life-hub-data.js`
   Then click **Commit changes**.
4. Go to **Settings → Pages** (left sidebar).
   - Under "Branch" pick **main**, folder **/ (root)**, click **Save**.
5. Wait ~1 minute. Your app is live at:
   `https://YOUR-USERNAME.github.io/life-hub/`
6. Open that link on your phone → **Share → Add to Home Screen** and it behaves like an app.

## Your PIN

**4721** — ask Claude to change it any time (it's baked into index.html as a hash).

## Updating data

When Claude syncs your dashboard, he refreshes `life-hub-data.js`.
To update the live site: open your repo → click `life-hub-data.js` → pencil icon →
paste the new contents → Commit. (Or re-upload the file the same way as step 3.)

## Notes

- Data you log on your phone stays in that phone's browser; data logged on PC stays on PC.
  The synced numbers (steps, sleep, meals, pay) come baked into `life-hub-data.js` on every device.
- The PIN deters casual visitors; it's not bank-grade security. Keep the link to yourself.
