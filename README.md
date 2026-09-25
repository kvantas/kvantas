# kvantas

Personal website of Konstantinos Vantas, built with [Hugo](https://gohugo.io) (v0.165+) and a small custom theme that lives in this repo (`layouts/`, `assets/`). No theme submodule, Node or Go modules are needed.

## Local preview

```bash
hugo server
```

Then open http://localhost:1313.

## Adding content

- **Publication**: add `content/publication/<name>.md` (copy an existing file, e.g. `tgis_2025.md`). The type is set with `publication_types = ["N"]`, where `N` is an index into `params.publication_types` in `hugo.toml` (2 = journal article, 1 = conference paper, 6 = book chapter, 7 = thesis, 8 = software). Set `selected = true` to show it on the home page. Put PDFs in `static/pdf/` and link them as `url_pdf = "/pdf/<file>.pdf"`.
- **Talk**: add `content/talk/<name>.md` with `time_start`, `event`, `location` and optional `url_slides`.
- **Bio, interests and education**: edit `content/home/about.md`.
- **Name, contact details and social links**: edit `[params]` in `hugo.toml`.

## Deploy

Netlify builds the site with `hugo --gc --minify` (see `netlify.toml`).
