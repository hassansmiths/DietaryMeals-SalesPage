# Dietary Meals sales page

Static site, no build step.

1. Open config.js and paste your order form link into ORDER_URL. Every buy button uses it.
2. To change the cover, replace img/cover.jpg (and img/cover-og.jpg for social sharing previews) with the same file names.
3. Deploy: push this folder to a new GitHub repo, then in Vercel choose Add New > Project > Import.
   Framework preset: Other. Leave Build Command and Output Directory empty.
   Or with the CLI: npm i -g vercel, then run `vercel --prod` in this folder.
