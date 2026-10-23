# Dolce Vita Community Portal – Interactive Prototype (VitaTech, SADL05C Phase 4)

A static website: `index.html` and `react.js` (bundled, so it doesn't load React from a CDN), plus `vercel.json`. No build step is needed.

## Deploy to Vercel – option A: Vercel CLI (fastest)
1. Install Node.js (https://nodejs.org) if you don't have it.
2. Open a terminal in this folder (`dolce-vita-prototype`).
3. Run: `npx vercel` and log in when asked. Accept the defaults (framework: Other, no build command, output directory `.`).
4. Run: `npx vercel --prod` to get your production link, e.g. `https://dolce-vita-prototype.vercel.app`.

## Deploy to Vercel – option B: GitHub
1. Create a new GitHub repository and upload the three files in this folder (`index.html`, `react.js`, `vercel.json`) to its root.
2. On vercel.com: Add New → Project → Import that repository.
3. Framework preset: **Other**. Leave Build Command and Output Directory empty. Click Deploy.

## Test accounts
- Resident: `maria.santos` / `resident123`
- Admin: `admin` / `admin123`
- Pending applicant: `liza.navarro` / `resident123`
- Rejected applicant: `grace.lim` / `resident123`

All data is fictional sample data that resets on page reload. Payments, emails, OCR and exports are simulated.
