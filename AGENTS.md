# AGENTS.md — Li Chen's Resume Site

## Key facts

- Pure static HTML. No build system, no package manager, no tests.
- Deployed to [transcendent-longma-d9820d](https://transcendent-longma-d9820d.netlify.app) on Netlify (auto-deploys on push).
- Also served at [li-ch.github.io/resume](https://li-ch.github.io/resume) and [drchen.li](https://drchen.li).
- Google Analytics tag (`G-6BD5F6RD19`) is embedded in `index.html` and `recruit-chn.html`.

## Generated files

**`paper_list.html`** is auto-generated — **do not edit directly**. Regenerate from `papers.bib`:
```
bibtex2html -r papers.bib
```
(`papers.bib` is the source of truth for the full publication list; it lives locally, not in the repo.)

## Site structure

| File | Purpose |
|------|---------|
| `index.html` | Main profile page (445+ lines, inlined CSS) |
| `paper_list.html` | Full publication list (generated from `papers.bib`) |
| `citations.txt` | Manually curated bibtex subset |
| `recruit-chn.html` | Chinese-language Ph.D. recruitment page |
| `static/img/li.png` | Chinese character avatar |
| `favicon.ico` | Favicon |

## Editing conventions

- News items in `index.html` follow format: `[YYYY-MM-DD] Description!` — keep exclamation marks and dates consistent.
- CSS is inlined in each file; no external stylesheets.
- Links use `./` relative paths. Do not introduce absolute paths.
