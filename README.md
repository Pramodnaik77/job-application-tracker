# Job Application Tracker 

A zero-backend personal job application tracker.
(https://pramodnaik77.github.io/job-application-tracker/)
## Features
- Applications: company, role, job link, date applied, status, location, work type, salary, source, follow-up date, notes
- Statuses: Wishlist, Applied, OA, Screening, Interview, Offer, Rejected, Withdrawn
- Applied defaults to today's date for new applications
- Dashboard stats and pipeline
- Interview conversion, offer rate, applications/week and follow-up metrics
- Search, status/source filters, sorting
- Edit/delete
- CSV export and JSON backup/import
- Local browser storage; no server/database required

## GitHub Pages hosting
1. Create a GitHub repository.
2. Upload `index.html` and this README.
3. Go to Settings -> Pages.
4. Under Build and deployment choose "Deploy from a branch".
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will provide the public URL.

## Important
This version stores data in the browser's localStorage. Keep JSON backups if the tracker contains important data. Cloud sync across devices is not included yet.
