# Digital Atelier

Minimal Jekyll hello-world version.

## How it works

- `index.html` points to the homepage layout.
- `_layouts/home.html` renders the homepage.
- `_layouts/trace.html` renders each trace.
- `_traces/` contains Markdown files that become pages automatically.
- `assets/css/styles.css` contains the small amount of styling.

## Add a new trace

1. Copy `TRACE_TEMPLATE.md` into `_traces/` with a new filename.
2. Set only `title` and `tags` in front matter.
3. Write the body in Markdown.
4. Publish when ready.

## Local preview

Only needed if you want to run Jekyll on your Mac:

```bash
bundle install
bundle exec jekyll serve
```

If you do not want a local Jekyll install, GitHub Pages can build it after you
push.
