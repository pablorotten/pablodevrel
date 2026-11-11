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
- `CNAME` - custom domain (pablodevrel.com)

Articles are teaser cards (`.card` in `styles.css`) in the timeline that link
out to dev.to. To add one, copy an existing `.card` block in `index.html` and
swap the cover URL, kicker text and title.

Website assets only. The job-search workspace and private material live in a
separate private repo.
