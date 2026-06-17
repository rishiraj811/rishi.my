# rishi.my

Small Jekyll site for `rishi.my`, edited either through Pages CMS or directly as Markdown.

## Content

- `_thought/*.md` renders at `/thought/:name/`
- `_life/*.md` renders at `/life/:name/`
- `_matter/*.md` renders at `/matter/:name/`
- uploaded media lives in `media/`

Each thought/life entry supports `title`, `date`, and Markdown body content. Matter entries also support a project link.

## Editing

- no-code: visit `/admin/` and open Pages CMS
- manual: edit Markdown files in `_thought`, `_life`, or `_matter`

## Local

```sh
jekyll build
jekyll serve
```
