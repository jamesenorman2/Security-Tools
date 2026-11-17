# Security Tools

Landing page (`index.html`) that showcases and links to:

| Tool              | Link                                      |
|-------------------|-------------------------------------------|
| Blast Calculator  | https://blast-tool-one.vercel.app         |
| VDA-Tool          | https://vda-tool.vercel.app               |
| Door Configurator | https://door-configurator-beta.vercel.app |
| Project Tracker   | Invite only (no public link)              |

Pure black, monochrome design with each tool's own app icon. Works from phone to 4K.

## Editing
- **Text, links, features:** the `TOOLS` config near the bottom of `index.html`.
- **Screenshots:** add images to `screenshots/` (see `screenshots/README.md`).
- **App icons:** `icons/apps/`, copied from each tool's repo.

## Deploying
Vercel project `security-tools`, connected to this repo: every push to the production branch
redeploys. Static files, no build step.
