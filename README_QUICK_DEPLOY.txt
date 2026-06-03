HOVEL IDEAS LANDING SITE
========================

This folder contains a one-page static website.

FILES:
- index.html : the whole site, including styling
- hovelideas_qr.png : QR code pointing to https://hovelideas.com
- hovelideas_qr.svg : same QR code as SVG
- README_QUICK_DEPLOY.txt : this file

FASTEST WAY TO VIEW:
1. Unzip the folder.
2. Double-click index.html.
3. It will open in your browser.

FASTEST VERCEL DEPLOY:
1. Put this folder into a new GitHub repo called hovel-ideas-landing.
2. In Vercel, click Add New Project.
3. Import the GitHub repo.
4. Framework preset: Other.
5. Build command: leave blank.
6. Output directory: leave blank.
7. Deploy.

DOMAIN:
Once it is deployed, point hovelideas.com to the Vercel project from Vercel Project Settings > Domains.

EDITING TEXT:
Open index.html in VS Code.
Search for the words you want to change.
Save.
Push to GitHub.
Vercel should redeploy.

CURRENT CONTACT:
thomas.mitchell@hovelideas.com

NOTE:
No database. No login. No Supabase needed for this first landing page.
This is intentionally simple, fast, and hard to break.
