# Jensen Deng Personal Website — V1.0

Official site: https://jensendeng.com/

## Features
- Tech / Academic theme toggle and separate avatars
- English / Chinese toggle, persisted in the browser
- About, Research (short summaries), Publications (empty until verified), Projects (personal website), Education timeline, Beyond Research, Contact
- Awards section retained in source but hidden until there are verified awards
- Custom domain via GitHub Pages, with relative static files and no third-party font requests
- Basic SEO: canonical, description, Open Graph, robots.txt and sitemap.xml

## Deployment
Replace all root-level files and the `assets` folder in the public GitHub repository `SeattleVermilion/SeattleVermilion.github.io`. Keep `index.html` in the repository root. After commit, verify the GitHub Actions Pages deployment status. The existing `jensendeng.com` DNS setup does not need changes.

## Important
The birth date, personal preferences and email addresses on this site are publicly viewable. Remove them from `index.html`/`script.js` before publishing if you do not want that information public. The research descriptions are summaries, not academic publications. The PDF report and group slides have not been uploaded.

## Validation
Static structural and JavaScript syntax checks passed. Live-site performance across networks, search-engine indexing and cross-browser appearance require external testing after deployment.
