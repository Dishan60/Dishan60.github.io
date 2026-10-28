# Dishan Majumder — Portfolio

Personal portfolio website, hosted on GitHub Pages and edited through [Pages CMS](https://app.pagescms.org).

## Updating the website (no coding needed)

1. Go to **https://app.pagescms.org** and click **Sign in with GitHub**.
2. Open this repository from the list.
3. Pick a section in the left sidebar — *Profile & contact*, *Experience*, *Education*, *Publications & projects*, *Skills*, *Leadership & activities*, *References* or *Research interests*.
4. Edit the form and click **Save**.
5. Wait about a minute, then refresh the website. The change is live.

Tips:

- **New job / degree / project:** click **Add an entry** in the relevant list. Lists can be reordered by dragging. Put the newest item first.
- **Bold text:** wrap words in `**double asterisks**` in fields that mention it.
- **New CV:** in *Profile & contact → CV (PDF)*, upload the new PDF and save. Both "Download CV" buttons update automatically.
- **New photo:** in *Profile & contact → Profile photo*, upload a portrait (4:5 shape, under 500 KB) and save. Also update *Small square photo* so the menu bar and browser tab match.
- **Hide a section:** remove all of its entries (e.g. delete every reference to hide *References*).
- **Undo a mistake:** every save is recorded in the repository's history on GitHub, so any change can be reverted.

## One-time setup

1. **Create the repository** on GitHub named `<your-username>.github.io` (Public), then upload/push these files to the `main` branch.
2. **Turn on GitHub Pages:** repository *Settings → Pages → Build and deployment → Source: Deploy from a branch*, branch `main`, folder `/ (root)`. The site will be at `https://<your-username>.github.io`.
3. **Connect Pages CMS:** sign in at https://app.pagescms.org with GitHub and install the Pages CMS app on this repository when asked.

## How it works

| What | Where |
| --- | --- |
| All website text | `_data/*.yml` (one file per section) |
| Page template | `index.html` (built by GitHub Pages' Jekyll) |
| Styles / scripts | `css/styles.css`, `js/main.js` |
| Photos | `assets/img/` |
| CV PDF | `assets/files/` |
| Admin forms | `.pages.yml` |
| Icons for research interests | `_includes/icons/` |
