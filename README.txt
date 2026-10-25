SIX SHORT UPANISHADS - installable app (PWA)

An installable app must be served from a web address (https). Put this whole folder online once, then install it from your phone. Free options:

OPTION 1 - Netlify Drop (easiest, no account needed to try)
  1. Go to app.netlify.com/drop
  2. Drag this folder (the one containing index.html) onto the page
  3. Open the web address it gives you on your phone

OPTION 2 - GitHub Pages
  1. Create a repository and upload all files in this folder
  2. Settings > Pages > Deploy from branch > main > root
  3. Open https://<your-username>.github.io/<repo>/ on your phone

OPTION 3 - Cloudflare Pages, Vercel or any static host also work.

INSTALL ON YOUR PHONE
  Android (Chrome): open the address > menu (three dots) > Install app / Add to Home screen
  iPhone (Safari): open the address > Share > Add to Home Screen

After the first visit it works fully offline. Fonts are built in. Reading progress and bookmarks are saved on the device.

TO UPDATE LATER: upload the new files and change CACHE = 'upanishads-v1' in sw.js to 'upanishads-v2' so phones fetch the new version.
