# Learn with Jeevan — GitHub Pages website

Static, responsive, bilingual English/German tutoring and project-mentorship site. It uses original CSS/canvas visuals, no stock images, no third-party runtime scripts, no analytics and no backend.

## Included

- Academic Excellence and Future Skills / Project Mentorship pathways.
- Maths, Science, Logic and Confidence interactive popups with keyboard, Escape-key and reduced-motion support.
- Credentials and certifications section with explicit verification-pending labels.
- Portfolio cards linked to public GitHub repositories verified during the build.
- English/German switch, responsive mobile navigation and email-based inquiry fallback.
- Draft Impressum and Datenschutz pages that clearly identify owner completion requirements.
- GitHub Actions workflow for the repository-subpath-safe GitHub Pages deployment.

## Before public operation

1. Confirm the public contact email and whether it should be used for inquiries.
2. Complete and legally review `legal.html` and `privacy.html` with the provider's legal name, serviceable address, disclosures and privacy details.
3. Verify the listed professional credentials, add issuer links or credential URLs, and proofread German copy with a fluent speaker.
4. Confirm teaching scope, service availability and any residence-permit or self-employment requirements.
5. Add an authorized portrait only if one is available; the current visual is intentionally a placeholder.

## Local QA

Serve the folder with any static server, for example `python -m http.server 4173`, then open `http://localhost:4173/`. All paths are relative so the site works at `/Learn-with-Jeevan/` on GitHub Pages.

## Deployment

Push to `main`. `.github/workflows/pages.yml` uploads the repository root and deploys it with GitHub Pages. In the repository settings, set Pages → Build and deployment → Source to **GitHub Actions** if it is not already configured.

