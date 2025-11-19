Mehul Sharma — Gamma-style Portfolio (Static + React CDN)

Contents:
- index.html           : Gamma-like static site (fonts/images via /assets). Includes Font Awesome (replace kit id), AOS, GSAP, dark mode toggle, Power BI iframe placeholder.
- styles.css           : Styling and dark mode variables.
- assets/*             : Placeholder images for profile & projects.
- react-version.html   : Minimal React single-file using CDN links (easy starter).
- deploy/              : Instructions below.

How to use:
1. Unzip and inspect files.
2. Replace placeholders:
   - Edit index.html to update email, links, Power BI iframe src.
   - Replace profile image in assets/.
   - Replace Font Awesome kit script with your kit or use CDN classes.
3. To run locally, open index.html in your browser.

GitHub Pages:
- Create a new repository (e.g., mehul-portfolio).
- Push these files to the repo root or /docs.
- In GitHub > Settings > Pages, select branch (main) and folder (root or /docs).
- Your site will publish at https://<username>.github.io/<repo>.

Power BI Embed:
- If you have a Power BI report, use 'Publish to web' link or proper embed token/iframe. Replace iframe src in index.html.

React/Next.js:
- For a full React or Next.js version, recommend initializing with Vite or Next.js and moving components into src/.
- I can convert this to a Next.js project structure if you want—tell me 'convert to Next.js full project' and I'll produce the files.

Notes:
- This package is self-contained and works offline (except external CDNs: AOS, GSAP, FontAwesome kit).
- If you want me to push to GitHub Pages for you, provide repo access or do the steps locally — I can give exact git commands.

