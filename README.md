# Budget Tracker

A simple budget tracker. Switch a bill on when you pay it and the date is filled in for you.
Everything is saved on your own device. Nothing is sent anywhere.

The first time someone opens it, they see an **example budget** with made-up names and amounts, with some bills already ticked off.
They can play with it, tap **Edit items** to make it their own, or tap **start with a blank budget**.
If someone already has budgets saved, the example is added to their list once, so they can pick it from the dropdown. **Manage → Add an example budget** brings it back if it has been deleted.

## What you see

- **Status strip:** budget selector, month, today's date, and a health light. Green means all clear. Amber means a bill is due within 3 days or everyday spending is over budget. Red means a bill is overdue.
- **Month summary and donuts:** bills paid, money in, and everyday spending at a glance.
- **Schedule:** the month's due dates by week.
- **Planned vs actual spending:** six months ending with the month shown.
- It follows the phone's light or dark setting.

## Put it online with GitHub Pages (free)

1. On github.com, create a new repository (for example `budget-tracker`). Make it **Public**.
2. Upload these files to it: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the page shows your address, `https://YOUR-USERNAME.github.io/budget-tracker/`.

## Install it on an iPhone

1. Open the address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new icon.

## Sharing a budget

- **To share:** tap **Share**, then **Share setup** (items and amounts only) or **Share with paid history**. Send the link by message, Notes or AirDrop.
- **To receive:** copy the link, open Budget Tracker from the home screen, and tap **Import**. It reads the copied link and asks you to confirm.
  If the link isn't picked up automatically, paste it into the box and tap **Import**.

On iPhone, tapping a link opens Safari, which keeps its own storage separate from the home-screen app. So copy the link rather than tapping it.
The data is inside the link and is never sent to GitHub. Anyone who has the link can read the budget, so delete the message afterwards.

## Several budgets

Use the selector at the top. **Manage** creates, renames and deletes budgets. Each is separate.
**Manage → Backup files** saves a budget to a file or restores one from a file, if you want a file copy.

## Notes

- Data lives in the browser on that device and is not encrypted. A different phone or browser starts with the example until you Import.
- Updating the app: re-upload `index.html`. If a change doesn't appear, close and reopen the app.
