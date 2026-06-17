# rishi.my

Small Jekyll site for `rishi.my`, edited either through Pages CMS or directly as Markdown.

## Content

- `_data/home.yml` controls the editable homepage content
- `_thought/*.md` renders at `/thought/:name/`
- `_life/*.md` renders at `/life/:name/`
- `_matter/*.md` renders at `/matter/:name/`
- uploaded media lives in `media/`

The homepage supports editable intro text and one image.
Each thought/life entry supports `title`, `date`, and Markdown body content. Matter entries also support a project link.

## Editing

- no-code: visit `/admin/` and open Pages CMS
- manual: edit Markdown files in `_thought`, `_life`, or `_matter`

## Local

```sh
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
bundle config set path vendor/bundle
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.
