Lt. Prakash Roy Library — Zero-cost static website starter

Included:
- Responsive Hindi/English book-library landing page
- Main categories and section buttons
- Browser-local demo admin panel for adding books/categories
- JSON export/import backup
- Free-book PDF URL support

Important prototype limitations:
- Admin edits are stored only in the current browser's Local Storage. They do not sync across devices or users.
- Admin Panel is not protected by a real login. Do not treat this demo as production admin.
- Premium purchase button is a demo only; no payment processor is connected.
- Do not upload paid PDFs to public file links. Paid access needs a backend, user accounts, purchase verification, and protected file delivery.

Deploy free (Cloudflare Pages):
1. Create a GitHub account and a new repository (e.g. lt-prakash-roy-library).
2. Upload index.html and README.txt to the repository root.
3. In Cloudflare, open Pages > Create a project > Connect to Git.
4. Select the repository. Framework preset: None. Build command: leave empty. Output directory: / (or root, depending UI).
5. Deploy. Cloudflare will provide a free *.pages.dev address.

Keep a JSON backup using Admin Panel > Backup Export before clearing browser storage or changing devices.
