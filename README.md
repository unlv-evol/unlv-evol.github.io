# unlv-evol.github.io
Repository containing the public website for the Software Evolution Lab (EVOL) at UNLV.

## Editing content

- Main pages are authored as Markdown source files: `index.md`, `join.md`, `news.md`, and `publications.md`.
- Project pages are in `_projects/*.md`.
- Team profile pages are in `_team_members/*.md`.
- Publications are in `_publications/<year>/*.md`.
- News items are in `_news/<year>.md`.
- Shared page structure is in `_layouts/evol.html` and `_includes/*.html`.

Note: Markdown files can include raw HTML. Many pages currently use HTML blocks inside `.md` files so the existing design stays unchanged while remaining editable as Markdown source.

## Local build

Run:

bundle exec jekyll build
