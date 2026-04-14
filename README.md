# puget-land-advisor
Puget Land & Development Advisors
Static website for Puget Land & Development Advisors, a Pacific Northwest real estate development and land use consulting firm based in Everett, WA.
Built as a portfolio project demonstrating static site development, Azure Static Web Apps hosting, and clean frontend design.
---
Live Site
https://black-rock-0e65d2c1e1.azurestaticapps.net
---
About the Project
This is a single-page static website built with plain HTML and CSS — no frameworks, no dependencies, no build tools. Just one file you can open in any browser.
Design goals:
Pacific Northwest aesthetic using a forest green palette
Clean typographic layout with Playfair Display and Source Sans 3
Fully responsive down to mobile
Fast load — no JavaScript required
---
Tech Stack
Layer	Choice
Markup	HTML5
Styling	CSS3 with custom properties
Fonts	Google Fonts (Playfair Display, Source Sans 3)
Hosting	Azure Static Web Apps (Free tier)
CI/CD	GitHub Actions
Build tools	None
---
Local Development
No install needed. Just open the file in a browser, or use VS Code Live Server for auto-reload during edits.
---
Deployment
Hosted via Azure Static Web Apps, deployed automatically on every push to main via GitHub Actions.

First-time Azure setup:
1. Create an Azure Static Web App in the Azure Portal
2. Copy the deployment token from: Azure Portal → your Static Web App → Settings → Deployment token
3. Add it to GitHub: repo Settings → Secrets and variables → Actions → New repository secret
   - Name: AZURE_STATIC_WEB_APPS_API_TOKEN
   - Value: (paste the token)

Deploying updates:
git add .
git commit -m "update: describe your change"
git push origin main

GitHub Actions rebuilds and redeploys automatically.
---
Custom Domain (Optional)
To connect a custom domain like pugetlandadvisors.com:
1. Buy the domain (Namecheap, Google Domains, etc.)
2. In Azure Portal → your Static Web App → Custom domains → Add
3. Follow the DNS verification steps Azure provides
4. Azure auto-provisions and renews the SSL certificate
---
Project Author
Jeremy Todd Welch
Strategic Infrastructure Leader | Navy Veteran | Azure Engineer
GitHub: github.com/jtoddwelch
LinkedIn: linkedin.com/in/jtoddwelch
Web: jtoddwelch.com
---
Part of my Azure Learning Lab portfolio. See azure-learning for cloud infrastructure work.
---
Phase 1 complete — April 12, 2026. Site live at https://swa-pugetland-prod.azurestaticapps.net

