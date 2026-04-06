# puget-land-advisor
Puget Land & Development Advisors
Static website for Puget Land & Development Advisors, a Pacific Northwest real estate development and land use consulting firm based in Everett, WA.
Built as a portfolio project demonstrating static site development, GitHub Pages hosting, and clean frontend design.
---
Live Site
https://jtoddwelch.github.io/puget-land-advisors
---
About the Project
This is a single-page static website built with plain HTML and CSS — no frameworks, no dependencies, no build tools. Just one file you can open in any browser.
Design goals:
Pacific Northwest aesthetic using a forest green palette
Clean typographic layout with Playfair Display and Source Sans 3
Fully responsive down to mobile
Fast load — no JavaScript required
---
Pages / Sections
Section	Description
Hero	Tagline, intro copy, illustrated WA State map
Stats	Key credibility numbers
Services	Six service areas with descriptions
Regions	Counties and project types served
Team	Three team member profiles
Contact	Office info and inquiry form
---
Tech Stack
Layer	Choice
Markup	HTML5
Styling	CSS3 with custom properties
Fonts	Google Fonts (Playfair Display, Source Sans 3)
Hosting	GitHub Pages
Build tools	None
---
Local Development
No install needed. Just open the file:
```bash
git clone https://github.com/jtoddwelch/puget-land-advisors.git
cd puget-land-advisors
open index.html
```
Or use VS Code Live Server for auto-reload during edits.
---
Deployment
Hosted via GitHub Pages from the `main` branch root.
To deploy updates:
```bash
git add .
git commit -m "update: describe your change"
git push origin main
```
GitHub Pages rebuilds automatically on every push.
---
Custom Domain (Optional)
To connect a custom domain like `pugetlandadvisors.com`:
Buy the domain (Namecheap, Google Domains, etc.)
In repo Settings → Pages → Custom domain, enter your domain
Add a `CNAME` file to the repo root containing just: `pugetlandadvisors.com`
Point your DNS A records to GitHub's IPs:
```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
---
Project Author
Jeremy Todd Welch
Strategic Infrastructure Leader | Navy Veteran | Azure Engineer
GitHub: github.com/jtoddwelch
LinkedIn: linkedin.com/in/jtoddwelch
Web: jtoddwelch.com
---
Part of my Azure Learning Lab portfolio. See azure-learning for cloud infrastructure work.
