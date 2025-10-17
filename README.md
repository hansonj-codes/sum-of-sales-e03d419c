# Sales Summary 374959384

This is a single-page website suitable for deployment on GitHub Pages. It reads data.csv (included in the repository attachments), sums the `sales` column, and displays the total on the page. The page loads Bootstrap 5 from jsDelivr.

Setup & Deployment
- Push this repository to GitHub.
- Enable GitHub Pages in repository settings (use the main branch root).
- The site will be available at https://<your-username>.github.io/<repo-name>/

Usage
- The page automatically fetches `data.csv` on load and displays the summed sales value in the `#total-sales` element.
- Click "Reload" to re-fetch and re-calculate.

Notes
- The CSV parser assumes a simple comma-separated file with a header row containing a `sales` column.
- Bootstrap CSS and JS are loaded from jsDelivr.

Commit
See the commit_message file for the commit message included with this change.