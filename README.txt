Uday's Solitaire - deploy on Vercel

Option A - Vercel CLI (fastest)
  1. Install Node.js from nodejs.org
  2. In a terminal:  npm i -g vercel
  3. cd into this folder (the one with index.html) and run:  vercel --prod
  4. Log in, accept the defaults (no framework, no build command). You get a https://...vercel.app link.

Option B - GitHub
  1. Create a GitHub repo and upload these files at the top level.
  2. On vercel.com: Add New > Project > import the repo > Deploy (no settings needed).

On iPhone: open the link in Safari > Share > Add to Home Screen.
When you update the game, change VERSION in sw.js (e.g. "v2") and redeploy.
Saved games live on each phone, tied to the website address.
