# Bible Typing Trainer — GitHub setup (10 minutes, once)

You will do two things on GitHub:

1. **Host the app** (GitHub Pages) → one web address that works on every laptop, desktop and iPad.
2. **Sync your progress** (a private Gist) → your chapters, streak and place follow you everywhere.

---

## Part 1 — Host the app (GitHub Pages)

1. Sign in at github.com → click **+** (top right) → **New repository**.
2. Name it `bible-typing`. Choose **Public** (Pages is free for public repos).
   *Your progress is NOT stored here — only the app files. It is safe to be public.*
3. Click **uploading an existing file** on the next screen and drag in these 6 files:
   - `bible-typing-trainer.html`
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

   Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. Wait about a minute. Your address will be:

   `https://YOUR-USERNAME.github.io/bible-typing/`

   Bookmark it on every device.

**iPad / iPhone:** open the address in Safari → Share → **Add to Home Screen**.
**Chrome / Edge (laptops):** click the install icon in the address bar, or use **Library → Install app**.
After the first visit the app also opens **offline** (handy on flights).

---

## Part 2 — Turn on sync (once per device)

1. Open the app → **Library** tab → **Sync across devices**.
2. Click **Create a token on GitHub**. The page opens pre-filled — only **gist** is ticked.
   Set *Expiration* to **No expiration** and click **Generate token**. Copy it (starts with `ghp_`).
3. Paste it into the app and press **Connect**.

That's it. On the **first** device this creates a private gist called
"Bible Typing Trainer sync". On every **other** device, the same three steps find that gist,
download your progress, and (if you imported your Bible with the ⚡ button) download the
Bible automatically too.

Tip: make the token once, save it in your password manager, and paste it on each device.

### When does it sync?
- when you open the app
- a few seconds after you finish a chapter or press Save & Stop
- when you switch away from the tab (so your place follows you to the next device)
- when you press the green ⟳ button in the header

### Before your first sync
On your main device, make sure your Bible was imported with the **⚡ Berean Standard Bible**
button (Library tab). That records where the Bible came from, so other devices can fetch it
by themselves. If you imported it from a file earlier, just click the button once — your
progress carries over automatically.

---

## Good to know
- **Nothing is overwritten.** Devices merge: a chapter completed anywhere counts everywhere.
- **Your token stays in that browser only.** It is never saved in the gist, your repo, or your backup file.
- **Lost a device?** Go to github.com/settings/tokens and delete the token — that device can no longer sync.
- **Also keep a backup.** Library → *Export all data* now and then (the app reminds you weekly).
- Not synced on purpose: theme/font (each device can look different) and the Analysis counters.
