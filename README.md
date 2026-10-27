# Abdul Rehman — Portfolio Website

A responsive, single-page professional portfolio built with plain HTML, CSS and JavaScript. No build dependencies are required.

## Deploy with GitHub + Vercel

1. Create a new GitHub repository, for example `abdul-rehman-portfolio`.
2. Upload **the contents of this folder** to the repository root (`index.html`, `styles.css`, `script.js`, `assets/`, etc.).
3. In Vercel, select **Add New → Project → Import Git Repository**.
4. Select your repository. Set **Framework Preset** to **Other** and leave the build command blank. The output directory can remain the root (`.`).
5. Click **Deploy**. Future GitHub updates will automatically redeploy when the repository is connected.

To test locally, double-click `index.html`, or from this folder run `python -m http.server 8000` and open `http://localhost:8000`.

## Update details

- Text, KPIs, service descriptions and external contact links: `index.html`
- Theme, layout, typography and mobile breakpoints: `styles.css`
- Navigation menu: `script.js`
- Portrait: replace `assets/abdul-rehman.jpg` with your own professional high-resolution photo (keep the same file name, or update the image path in HTML).

## Notes on source data

The portfolio text, KPI figures, roles, and contact details are taken from the supplied 11-page PDF. The graphic styled as a marketing dashboard is **an illustration**, not a screenshot or evidence from a live Meta Ads account. Its chart trajectory is decorative. The PDF only supplied an email username without a domain, so no email address is linked. The photo is a cropped image from the uploaded PDF and would benefit from replacement with the original high-resolution portrait.

No tracking, cookie banners, back-end infrastructure or third-party analytics are installed. Google Fonts are loaded from Google's font CDN; the system font falls back if unavailable.
