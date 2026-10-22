# Put Tino's Guest House live on GitHub Pages

Time needed: about 5 minutes. Cost: free. No coding needed.

## What you need
- A free GitHub account (github.com/signup)
- The file **index.html** (do not rename it)

## Steps (browser only)
1. Sign in at github.com and tap **+** (top right), then **New repository**.
2. Repository name: `tinos-guesthouse-kariba`
3. Set it to **Public** (needed for free hosting). Tap **Create repository**.
4. On the new repo page, tap **uploading an existing file**.
5. Add `index.html`, then tap **Commit changes**. It must sit at the top level, not inside a folder.
6. Go to **Settings**, then **Pages** in the left menu.
7. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, Folder to **/ (root)**, then **Save**.
8. Wait 1 to 3 minutes and refresh the Pages screen. Your live link appears at the top:

   `https://YOUR-USERNAME.github.io/tinos-guesthouse-kariba/`

## Check before sending to the client
- Open the link on a phone and test both booking forms.
- Tap the WhatsApp and Call buttons.
- Confirm the phone numbers and email are still correct.
- Remove "Demo prototype" from the footer when the site goes final.

## Updating the site later
Open the repo, tap `index.html`, tap the pencil icon or **Add file > Upload files** to replace it, then **Commit changes**. The live site refreshes in a minute or two.

## Custom domain (after the client signs)
1. Buy a domain, for example tinosguesthousekariba.com or a .co.zw.
2. In **Settings > Pages**, enter it under **Custom domain** and save.
3. At your domain registrar, add the DNS records GitHub lists on that screen (see GitHub's "Managing a custom domain for your GitHub Pages site" help page).
4. Tick **Enforce HTTPS** once it becomes available.

## Troubleshooting
- **404 error:** `index.html` is probably inside a folder or misspelled. It must be at the repo root.
- **Pages option greyed out:** the repo is private. Change it to Public in Settings.
- **Old version showing:** wait a couple of minutes and hard-refresh the page.
