# razeineldin.github.io

Personal academic website of **Dr.-Ing. Ramy A. Zeineldin**, Assistant Professor of Computer Science and Engineering at Menoufia University.

🌐 **https://razeineldin.github.io**

Built with [Hugo](https://gohugo.io) and the [Hugo Blox](https://hugoblox.com) Academic CV template. Every push to `main` is built and deployed to GitHub Pages by [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## Where to edit

| What | File |
| --- | --- |
| Name, bio, education, work, awards, skills, links | `content/authors/admin/_index.md` |
| Profile photo | `content/authors/admin/avatar.jpg` |
| Homepage sections | `content/_index.md` |
| Publications (one folder per paper) | `content/publications/<slug>/index.md` + `cite.bib` |
| Projects, Teaching, Service, Experience pages | `content/projects/_index.md`, `content/teaching.md`, `content/service.md`, `content/experience.md` |
| CV download | `static/uploads/resume.pdf` |
| Site title, menu, SEO | `config/_default/hugo.yaml`, `menus.yaml`, `params.yaml` |

To feature a paper on the homepage, set `featured: true` in its `index.md`.

Front matter is YAML: keep indentation consistent, and quote values that contain `:` or start with `[`, `*` or `@`. If the site stops updating, open the **Actions** tab; a failed "Deploy website to GitHub Pages" run shows the line that broke.

## Run locally

Requires Hugo extended, Go and Node.js (see `hugoblox.yaml` for the Hugo version).

```bash
pnpm install
hugo server
```
