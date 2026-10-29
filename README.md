# Healthcare Analytics Learning Website

A static GitHub Pages website. Upload all files and the `data/` directory to the root of a repository. In GitHub Settings → Pages, choose Deploy from a branch, `main`, root (or use an existing Pages Actions workflow). Visit `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## Pages
- index.html — homepage
- excel.html, sql.html — original tutorials
- python.html, ai.html, visualization.html, statistics.html, healthcare.html, use-cases.html — new draft tutorials
- practice.html — data downloads and exercise hub
- sql-practice.html — SQLite SQL lab, real execution and result checks
- excel-practice.html, python-practice.html, statistics-practice.html, ai-practice.html, visualization-practice.html — interactive starters

## Notes
- CSV files are synthetic. No real patient information is included.
- SQL uses sql.js 1.13.0 via Cloudflare CDN; Python uses Pyodide 0.27.7 via jsDelivr CDN. Internet is required to load those runtimes.
- All exercises run client-side. There is no backend or user account.
- Serve the site through GitHub Pages or `python -m http.server 8000` (opening HTML with file:// blocks CSV loading).
- SQL answer checks compare the returned rows and columns against a reference result; they are not a full semantic SQL grader.
- The Python exercise runs arbitrary user-entered Python in browser sandbox. Do not add secrets to client-side code.
- This is draft educational content for review.
