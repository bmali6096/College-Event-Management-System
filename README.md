# CampusConnect — College Event Management System (Browser Demo)

## Run it
1. Download and extract this ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. No installation, server, React build, Python, or MySQL is required for this demo.

## Features
- Dashboard with event counts
- Browse events and search/filter by category
- Student registration form with duplicate email prevention per event
- My Registrations page and cancel registration
- Admin panel to add, publish/close, and delete events
- Registration list and CSV export
- Browser localStorage keeps demo records on this device/browser

## Important limitations
This is a browser-only prototype intended for demonstration and college project screenshots. It does not use a real backend, database, or secure login. Data is saved in localStorage in the current browser only. The Admin Panel is not protected by authentication. Use dummy data only.

For a production/full-stack project, connect a React frontend to a Python Flask API and a MySQL database, add secure authentication and server-side authorization, validate all requests on the backend, and configure HTTPS.

## For GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. In repository Settings → Pages, select deployment from the `main` branch and `/ (root)`.
4. Save and wait for GitHub Pages to publish the site.
5. Use the generated Pages URL to open it in a browser.
