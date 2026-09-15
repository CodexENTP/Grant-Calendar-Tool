# Codex Analytics — Office Hero Pack: Grant Calendar Tool V1

A static, client-side GitHub Pages application for building grant calendars and exporting print-ready Excel workbooks.

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this ZIP **to the repository root** (index.html, styles.css, app.js, README.md).
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)`, then Save.
7. GitHub will provide the Pages URL after deployment completes.

## V1 features
- Fiscal Year defaults to July–June; configurable start month.
- Monday-start calendar layouts.
- Calendar Year, Fiscal Year, and Jan–Dec Excel tabs.
- Grant-focused default categories plus custom categories/colors.
- Optional U.S. federal holidays.
- Excel bulk-import template and duplicate review.
- Tentative Site Visit windows that can later be assigned one exact date or cancelled.
- Event-level Outlook `.ics` creation with prefilled event data.
- Calendar preview and annual-detail density warning.
- Excel print areas/page setup.
- Local JSON Save/Open Project.
- Clipboard Tool sample-data export.
- All processing occurs in the browser.

## Dependency
Excel import/export uses ExcelJS 4.4.0 loaded from jsDelivr. An internet connection is required when loading the app unless ExcelJS is later bundled locally.
