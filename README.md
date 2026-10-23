# Michael A. Morrison — personal website

Static portfolio hosted at <https://mamorri.github.io/> with GitHub Pages.

## Preview locally

From the repository root, run `python -m http.server 8001 --bind 127.0.0.1`, then open <http://127.0.0.1:8001/>.

No build step, package installation, or third-party scripts are required for the main page. Content and navigation work without JavaScript.

## Update content

- `index.html`: profile, projects, experience, skills, education, and contact links.
- `assets/css/index.css`: responsive layout and styling.
- `assets/docs/michael-morrison-resume.pdf`: downloadable résumé; replace this file to keep its public URL stable.
- `assets/js/index.js`: current year in the footer.
- `sites/home.html`: earlier portfolio, retained with its original project URLs.

The current content and PDF reflect the résumé approved on October 22, 2026. Keep role dates, leadership statements, contact details, and the résumé in sync when making future updates.

Deploy by publishing this repository through its existing GitHub Pages configuration.
