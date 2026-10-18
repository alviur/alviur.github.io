# alviur.github.io

Personal academic website of Alexandra Gomez-Villa. Plain HTML and CSS, no build step.

## Files

- `index.html` — all content: Bio, Research interests, News, Publications, Teaching
- `style.css` — design
- `assets/photo.jpg` — your portrait (add it; initials show until it exists)
- `.nojekyll` — tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages (one time, ~5 minutes)

1. On GitHub, create a new **public** repository named exactly `alviur.github.io`.
2. Upload every file in this folder (drag and drop on the repo page, or with git):
   ```bash
   git init
   git add .
   git commit -m "Personal website"
   git branch -M main
   git remote add origin https://github.com/alviur/alviur.github.io.git
   git push -u origin main
   ```
3. In the repo, open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute the site is live at **https://alviur.github.io**.

Then point your Google Site to the new address (or add a link on it) so old links still help people find you.

## Editing

- **News:** add a new `<li>` at the top of the `<ul class="news">` list. The first six show by default; update the "Show all 18 items" text if the count changes.
- **Publications:** copy an existing `<li class="pub">` in the right group (Conferences, Journals, Workshops and others) and change the venue, year, title, authors and link. Wrap your own name in `<b>…</b>`. Update the count next to the group heading.
- **Teaching:** add a `<li>` to the `<ul class="courses">` list.

You can edit any file directly on github.com (pencil icon); the site updates within a minute of saving.

## Custom domain (optional)

If you own a domain, add a file named `CNAME` containing just the domain (e.g. `gomezvilla.com`), then follow GitHub's instructions under Settings → Pages → Custom domain.
