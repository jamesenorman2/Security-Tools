# Security Tools

Landing page (`index.html`) that showcases and links to:

| Tool              | Link                                      |
|-------------------|-------------------------------------------|
| Blast Calculator  | https://blast-tool-one.vercel.app         |
| VDA-Tool          | https://vda-tool.vercel.app               |
| Door Configurator | https://door-configurator-beta.vercel.app |
| Project Tracker   | OneDrive team folder (link to be added)   |

Styled to match Project Tracker. Works from phone to 4K, light and dark.

## Editing
- **Text, links, features:** the `TOOLS` config near the bottom of `index.html`.
- **Screenshots:** add images to `screenshots/` (see `screenshots/README.md`).
- **Project Tracker link:** in OneDrive, right-click the team folder (or `AECOM-Security.html`)
  → Share → set to "People in your organization" → *Copy link*, and paste it as the tracker's `url`.

## Deploying
Vercel project `security-tools`, connected to this repo: every push to the production branch
redeploys. Static files, no build step.
