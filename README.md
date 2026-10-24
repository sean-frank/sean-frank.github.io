# Sean Frank

Personal site for Sean Frank. GitHub Pages builds it with the native Jekyll environment (github-pages gem, whitelisted plugins only). No Actions workflow is required.

## Local build

```bash
bundle install
JEKYLL_ENV=production bundle exec jekyll build
```

## Placeholders

- Résumé links point at `/resume.pdf`. Add the file as `resume.pdf` in the repo root.
- Certifications live in `_data/certifications.yml`. The section stays hidden while that list is empty.
- Projects live in `_data/projects.yml`. An empty list shows an empty state.
- In a post, put the title in front matter and start the body at a second-level heading so the page keeps a single `h1`.
