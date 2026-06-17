# rishi.my

Small Jekyll site for `rishi.my`, edited either through Pages CMS or directly as Markdown.

## Content

- `_thought/*.md` renders at `/thought/:name/`
- `_life/*.md` renders at `/life/:name/`
- `_matter/*.md` renders at `/matter/:name/`
- uploaded media lives in `media/`

Each entry supports `title`, `date`, optional `summary`, optional `link`, optional media fields, and Markdown body content.

## Editing

- no-code: visit `/admin/` and open Pages CMS
- manual: edit Markdown files in `_thought`, `_life`, or `_matter`

## Local

```sh
jekyll build
jekyll serve
```
