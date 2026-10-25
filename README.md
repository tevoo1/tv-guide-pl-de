# TV Guide PL / DE

A static TV guide using XMLTV data for Poland and Germany. It has a horizontal timeline, country buttons, day selection, channel search, and drag-and-drop channel ordering saved in the browser.

## Publish for free using GitHub Pages
1. Create a **public** GitHub repository, e.g. `tv-guide-pl-de`.
2. Upload `index.html` and `.github/workflows/update-and-deploy.yml`, preserving the folder structure.
3. In repository Settings → Pages, choose **GitHub Actions** as the deployment source.
4. Open Actions → **Update TV guide and deploy** → Run workflow.
5. When successful, open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

The workflow downloads the two XMLTV files daily at 04:17 UTC and deploys the site. It can also be run manually from Actions.

## Notes
- This is a TV guide only, not streaming.
- EPG data is third-party and its availability/coverage may change.
- Channel order is saved separately per country in the current browser/device.
- Large XML files can take time to parse on older phones.
