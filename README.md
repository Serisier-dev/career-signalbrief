# RoleSignal

Static prototype for curated career briefs.

## Live URLs

- Site: `https://serisier-dev.github.io/career-signalbrief/`
- Role-specific feedback page: `https://serisier-dev.github.io/career-signalbrief/feedback/`

## Files

- `index.html` - landing page
- `sample-report.html` - example report/prototype
- `feedback.html` - older general feedback page retained for compatibility
- `feedback/index.html` - current role-specific feedback app
- `style-guide.html` - design/style reference
- `assets/styles.css` - shared styles

## Current feedback behavior

- Role links should use `/feedback/?t=...` with the trailing slash.
- The form submits to the Hermes backend over HTTPS.
- The submit target is a hidden iframe so the user stays on the RoleSignal page.
- Do not expose raw `http://165.227.36.81:8765` actions in public HTML.

## Related local workspace

Scraper, ranking, feedback backend, logs, and Jamie preferences live at:

`/home/hermes/career-scraper`

Start with:

- `/home/hermes/career-scraper/docs/WORKING_STATE.md`
- `/home/hermes/career-scraper/docs/CHANGELOG.md`
- `/home/hermes/career-scraper/workspaces/jamie/preferences-log.md`
