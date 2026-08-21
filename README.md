# SciToolKG Reference Catalog

GitHub Pages site: canonical citations, agent-framework associations, and verified recent-usage anchors for the [SciToolAgent](https://github.com/HICAI-ZJU/SciToolAgent) tool catalog.

## Local preview

```
gem install bundler jekyll
bundle exec jekyll serve
```

Or just push to GitHub — Pages builds `jekyll-theme-cayman` automatically, no local build needed.

## Structure

- `index.md` — landing page
- `agent-frameworks.md`, `benchmarks.md`, `chemistry-tools.md`, `materials-tools.md`, `biology-tools.md` — canonical reference tables
- `recent-usage.md` — verified 2025–2026 usage/benchmark anchors

Entries the source research could not verify (no resolvable paper or repo) are listed as exclusions at the top of each affected page rather than included.
