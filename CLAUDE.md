# Security Tools (landing page)

- Static site: `index.html` + `screenshots/`. No build step.
- **Always merge finished work to `main` and push.** `main` is the Vercel production branch
  (project `security-tools`, team `jamesenorman2s-projects`); every push to it redeploys.
- Content lives in the `TOOLS` config in `index.html`.
- Look: a serious scientific instrument. Pure black (#000), always dark, monochrome, hairline
  borders, 4px radius, IBM Plex Sans + IBM Plex Mono. No gradients, glows or colour accents.
  Layout follows Project Tracker (sidebar + panels).
- Icons: the site icon is a white-outline toolbox on black (`icon.svg`). Each tool shows its own
  app icon from `icons/apps/` (copied from that app's repo: Blast `icons/icon.svg`, VDA
  `icons/icon.svg`, Door `src/app/favicon.ico`, Project Tracker `index.html` favicon). Re-copy when
  an app's icon changes.
- Project Tracker has no link: it is invite-only, with company data stored on the company server.
- Check layouts at phone (390px), 1366, 1920 and 3840 widths with no horizontal scroll.
