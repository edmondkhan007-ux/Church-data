# ChurchCare — GitHub Pages Edition

A luxury campus-ministry attendance, shepherding, visitor, birthday, and member-care web app.

## Main features

- Church members and dedicated visitors registry
- Records who invited each visitor
- Shepherds and members assigned under them
- Attendance tracking and history
- Automatic Active / Inactive / New classification based on attendance
- Birthday tracking
- Campus-ministry lifecycle statuses: Current, Completed school, Transferred, Left ministry, and Archived
- Member-care alerts with responsible shepherd information
- CSV exports and full JSON backup / restore
- Delete-all-data danger zone protected by two confirmation prompts

## Publish on GitHub Pages

1. Sign in to GitHub and create a new repository, for example `churchcare`.
2. Upload all files from this folder to the **root of the repository**. Make sure `index.html` is not inside another folder.
3. Open the repository's **Settings**.
4. Open **Pages** under **Code and automation**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then save.
7. GitHub will publish the site at an address similar to:
   `https://YOUR-USERNAME.github.io/churchcare/`

## Important data note

This version stores data in the browser using `localStorage`.

That means:

- Data entered on one device/browser is not automatically shared with another device.
- Clearing the browser's site data can remove locally stored ChurchCare records.
- Use **Backup Data** regularly.
- For shared multi-device ministry use, connect the app to an online database such as Supabase or Firebase.

## Recommended campus-ministry workflow

When a student completes school, use the **Completed school** status rather than permanent deletion. This removes the person from current operational lists while preserving historical attendance and ministry records.
