# Participant WhatsApp Group Join — ZIET Mumbai

Static GitHub Pages app that reads participant names and school names from the live Google Sheet and lets a participant select their record before opening the official WhatsApp group invitation.

- **Google Sheet:** https://docs.google.com/spreadsheets/d/1Uuqoz2KFpTcw9d2HI02fLmFPopTaLnKWwZ9aR-uYCeY/edit?usp=sharing
- **WhatsApp group:** https://chat.whatsapp.com/BOwiFDvQ6ZP0PQF9THPdxM
- **Live data:** Google Sheets Visualization endpoint; participant rows are not hard-coded.
- **Expected Pages URL:** https://taprimaryzietmumbai-kjrd.github.io/Participant-WhatsApp-Group-Join/

## Data requirements
The sheet must be shared as **Anyone with the link — Viewer** if participants are to be read without signing in. Avoid publicly exposing sensitive data. The first row should contain a heading such as `Participant Name`, `Name`, `Teacher Name`, or `Full Name`; a school column is detected from headings such as `School`, `KV Name`, `Kendriya Vidyalaya`, `Institution`, or `Vidyalaya Name`.

## GitHub Pages
In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. Wait for the deployment to finish before opening the expected URL.

## Verification
The app source was committed to the `main` branch. End-to-end verification requires the sheet to be publicly readable and GitHub Pages to be enabled and finish deploying.
