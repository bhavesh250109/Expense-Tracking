# Obsidian Expense Tracker (Android PWA)

## Files
- `index.html`: the app
- `manifest.webmanifest`: installable app metadata
- `sw.js`: offline app-shell cache
- `icon-192.png`, `icon-512.png`: home-screen icons

## Install on Android
A Progressive Web App must be served from HTTPS (or localhost) to be installable. It cannot be installed directly by opening the HTML file from Downloads.

1. Upload the contents of this folder to an HTTPS static host (for example, a GitHub Pages site or Netlify site).
2. Open the resulting HTTPS URL in Chrome on Android.
3. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.
4. Confirm. The Obsidian icon will appear on your home screen.

## Storage and reliability
Expenses and budget preferences are stored in the browser's local storage on that device. The app shell is cached for offline opening after the first successful visit. Do not clear Chrome site data if you want to keep your entries. Browser/device failure or clearing site data can erase local records. For important records, periodically export/backup your data (a backup/export feature can be added in a next version). This version does not sync between devices and does not connect to bank accounts.

## Use
- Add expenses with amount, description, category, and date.
- Change the month in Overview/History/Calendar/Insights.
- Set your monthly spending budget.
- Filter transaction history by category.
- View calendar dates and category statistics.
