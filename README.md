# Riverdale Math Team website

Plain HTML + one CSS file. No build step, no frameworks — edit a file, push, done. 

## Files

| File | Page |
|---|---|
| `index.html` | Home (about, meetings, how to join, people, news) |
| `competitions.html` | Upcoming competitions table |
| `formulas.html` | AMC 10/12 formula sheet (math is rendered by MathJax) |
| `videos.html` | Fun videos |
| `problem-sets.html` | Past problem sets — PDFs go in `problem-sets/` |
| `wins.html` | Past wins photo gallery — images go in `images/wins/` |
| `style.css` | All the styling for every page |

Every page has a comment near the top of its content explaining how to add rows / photos / videos.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `riverdale-math-team`). Make it **public**.
2. Upload everything in this folder to the repository (on github.com: **Add file → Upload files**, then drag in all the files and folders).
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, and click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/riverdale-math-team/`.

To update the site later, edit a file on github.com (pencil icon) and commit — the live site refreshes within a minute or two.

## Common edits

- **New news item:** `index.html`, the `<ul class="news">` list. Newest at the top.
- **Competition date confirmed:** in `competitions.html`, remove the `<span class="est">…</span>` around the date so it's no longer italic.
- **Deadline passed:** wrap it in `<span class="passed">…</span>`.
- **"Last updated" date:** in the footer of each page.
