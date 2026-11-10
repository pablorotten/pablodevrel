# Pablo's CV website

Source code deployed on GitHub Pages at pablodevrel.com.

- Live site: https://pablodevrel.com
- DevRel resume page: https://pablodevrel.com/devrel
- Engineer resume page: https://pablodevrel.com/dev

Structure:

- `index.html`, `styles.css` - root CV site
- `dev/` - engineer resume page
- `devrel/` - DevRel resume page
- `images/` - site images
- `articles/` - generated article teasers, iframed in the timeline cards
- `scripts/` - `fetch-article.mjs`, rebuilds an article teaser
- `CNAME` - custom domain (pablodevrel.com)

Article previews are generated because dev.to sends
`Content-Security-Policy: frame-ancestors https://dev.to` and cannot be framed
directly. The teaser is a fixed size card that links out to dev.to. Refresh it
after editing the post:

```sh
node scripts/fetch-article.mjs
node scripts/fetch-article.mjs <slug-or-id> articles/<name>-preview.html
```

Website assets only. The job-search workspace and private material live in a
separate private repo.
