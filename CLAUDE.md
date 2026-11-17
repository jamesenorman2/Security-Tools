# Security Tools (landing page)

- Static site: `index.html` + `screenshots/`. No build step.
- **Always merge finished work to `main` and push.** `main` is the Vercel production branch
  (project `security-tools`, team `jamesenorman2s-projects`); every push to it redeploys.
- Content lives in the `TOOLS` config in `index.html`.
- Look: a serious scientific instrument in colour. Pure black (#000), always dark, hairline borders,
  4px radius, IBM Plex Sans + IBM Plex Mono. Each tool has its own accent colour (`colors` in TOOLS:
  Risk & Threat violet, Blast red, VDA blue, Door teal, Tracker amber) used on its card, section, buttons, figures and
  drawn preview; page accent is blue/violet. James preferred colour over a black-and-white look.
  Layout follows Project Tracker (sidebar + panels), with a top bar level with the sidebar logo row.
- Icons: the site icon is a white-outline toolbox on black (`icon.svg`). Each tool shows its own
  app icon from `icons/apps/` (copied from that app's repo: Risk & Threat `icons/favicon.svg`,
  Blast `icons/icon.svg`, VDA
  `icons/icon.svg`, Door `src/app/favicon.ico`, Project Tracker `index.html` favicon). Re-copy when
  an app's icon changes.
- Project Tracker has no link: it is not meant to be online. It is an offline, totally secure app
  that runs from the AECOM server, invite-only.
- Check layouts at phone (390px), 1366, 1920 and 3840 widths with no horizontal scroll.
