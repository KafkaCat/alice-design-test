# alice-design-test

Test repo for sharing Alice design docs via GitHub Pages + giscus comments.

Live site: https://kafkacat.github.io/alice-design-test/

## Setup

- HTML files served via GitHub Pages (Settings → Pages → Source: `main` branch root)
- Comments via [giscus](https://giscus.app) backed by GitHub Discussions
- `data-mapping="pathname"` → each HTML path gets its own discussion thread

## Adding a new design doc

1. Create directory under `design-research/<topic>/` and place `index.html`
2. Append the giscus `<script>` block from any existing doc to the new HTML
3. Add a card entry to root `index.html`
4. `git push` — GitHub Pages auto-deploys
