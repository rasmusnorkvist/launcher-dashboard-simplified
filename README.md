# Project Dashboard (simplified)

A static, public version of the internal Project Dashboard. Same look as the
full dashboard in `../launcher-dashboard`, but with no server, no process
management, and nothing local — just a page that links out to Builder Matrix.

Meant to be pushed to GitHub and served with GitHub Pages.

## Deploy

1. Push this folder's contents to a GitHub repo (root of the repo, or a
   `docs/` folder — either works).
2. In the repo's Settings → Pages, set the source to that branch/folder.
3. GitHub gives you a `https://<user>.github.io/<repo>/` URL.

## Editing

It's just `index.html` + `dashboard.css`. To change or add a linked project,
edit the `.card` block in `index.html` directly.
