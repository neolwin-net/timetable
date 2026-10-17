# Master Schedule + OneDrive quick link

This update keeps the four-week timetable and adds a responsive OneDrive shortcut section with a modern dark interface.

## Before publishing

Open `index.html` and find the comment:

`<!-- Replace the URL with your actual OneDrive sharing link. -->`

Replace `https://onedrive.live.com/` in the `href` of the `Open OneDrive` button with your actual OneDrive sharing URL.

## Deploy to the existing `neolwin-net/schedule` repository

1. Download and extract this ZIP.
2. In your repository, replace `index.html`, `style.css`, and `app.js` with the versions in this folder.
3. Keep `IBT.png` and `CNAME` in the repository; they are not included in this package because they do not need changing.
4. Commit the changes to the repository's publishing branch (`master`, as currently shown in the repository).
5. Wait for GitHub Pages to rebuild, then visit https://neolwin-net.github.io/schedule/.

No build process or backend is required.

## Included

- Existing four-week schedule data and week tabs
- Search across lessons, rooms, types, and days
- Dark theme by default, with a working light/dark toggle
- New OneDrive shortcut card
- Responsive desktop and mobile layout
