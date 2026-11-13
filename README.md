# Dominic Oduor | Cybersecurity & IT Portfolio — Version 1

Responsive, static GitHub Pages portfolio. Built from the user's existing Data Analyst site using a new lightweight HTML/CSS/JS interface. The four analytics project links and selected image assets were preserved from the previous repository.

## What's included

- `index.html` — responsive homepage with About, Projects, Experience, Skills, Credentials and Contact.
- `projects/*.html` — five cybersecurity case study pages (client engagement and academic labs clearly distinguished).
- `assets/css/styles.css` — responsive layout, light/dark design, keyboard focus states, reduced-motion support.
- `assets/js/main.js` — accessible mobile navigation, color theme toggle, project filtering, reading-progress bar.
- `assets/images/` — custom vector art and optimized graphics reused from the prior analytics portfolio.
- `favicon.svg`, `.nojekyll`, `robots.txt`, `sitemap.xml` — static hosting and discoverability files.

No backend, build step, external font downloads, analytics tracking, or paid services are needed. Works at the existing project Pages URL.

## Preview locally

Open `index.html` in a modern browser. For a more accurate test, in this folder run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to the existing GitHub Pages repository

1. **Back up** the existing repository or create a branch before replacing files.
2. Unzip this package. Copy **the contents of this folder**, not the parent folder, into the root of the GitHub repository that publishes `https://dommid.github.io/DominicOduor.github.io/`.
3. In GitHub, commit/push the updated files to the branch configured under **Settings → Pages** (commonly `main`, root `/`).
4. Confirm that `index.html`, `assets/`, `projects/` and `.nojekyll` are at repository root, not inside a nested folder.
5. Open `https://dommid.github.io/DominicOduor.github.io/` and test the mobile menu, themes, category filters, case study links, LinkedIn/GitHub references, contact email and analytics links.
6. Recheck the GitHub Pages source branch/folder under Settings → Pages if changes don't appear.

**Do not delete** the old site's original assets until you've retained a backup. The packaged site does not rely on the old Massively template's CSS, JS or fonts.

## Important review items before public release

- **Hivo**: Public case study intentionally excludes sensitive endpoints, client findings, user accounts, confidential reports and test screenshots. Request permission before publishing any substantive client evidence.
- **Lab evidence**: Technical descriptions are factual high-level summaries; replace general text with verified sanitized screenshots, specific commands/configuration excerpts, investigation notes, risk matrices and measured results as artifacts become available.
- **Employment**: Verify the displayed job titles/dates, particularly Lisa Care (Dec 2025–present), AUTOPAY (Oct 2021–present), Smart Data (Jan 2021–Feb 2026), against current professional records.
- **Resume**: The main CTA is deliberately **Request résumé** by email. A public résumé file is not automatically embedded because an uploaded document may contain personal phone/address information. After approving a web-safe résumé, add it under `assets/docs/` and change the CTA link accordingly.
- **Social preview**: A simple SVG preview is supplied; some platforms prefer PNG. Export a 1200×630 PNG later for consistent rich previews.
- **Credentials**: No expired certifications are represented as active. Add only verifiable badges/credential URLs.
- **Links**: Original analytics project destinations are preserved from the uploaded repository but should be clicked and verified online before release.
- **Security**: No JavaScript dependencies, third-party trackers, contact form, exposed API keys, or intrusive live demos.

## Phase 2: evidence enrichment

Build approved, technically richer pages for Hivo (safe methodology only), Wazuh/TheHive investigation, pfSense/Snort, attack simulation, and Windows security. Add diagrams and screenshots only from sanitized, shareable environments. Then add verified portfolio/resume links to LinkedIn and Indeed.
