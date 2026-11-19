# Tamanna Ghosh: Digital CV

Static portfolio site: plain HTML, CSS and JavaScript with no build step. It is ready for GitHub Pages.

## Pages
- `index.html`: home (about, approach, experience, skills, certifications, education, insights)
- `experience.html`: agency-led client accounts and the lead-to-revenue funnel
- `case-studies.html`: brand case studies
- `404.html`: not-found page (GitHub Pages serves it automatically)

## Styles
- `styles.css`: base components and the Soft Crimson color tokens (light and dark)
- `ui.css`: the "Editorial Crimson" UI layer (serif headings, pill navigation, footer). Remove its `<link>` to roll back.

## Deploy to GitHub Pages
1. Create a public repository named `<username>.github.io` (or any name, for a project site).
2. Upload **the contents of this folder** to the repository root. `index.html` must sit at the top level, not inside a subfolder.
3. Open **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then **main** / **(root)**, and save.
4. The site goes live at `https://<username>.github.io/` (or `https://<username>.github.io/<repo>/`) within a minute or two.

All paths are relative, so the site works at both the root and project-site URLs. `.nojekyll` tells GitHub to serve the files as they are.

## Local preview
Any static server works, for example: `npx serve .`
