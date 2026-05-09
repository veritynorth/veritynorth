# verity-north-website

A clean, mobile-responsive one-page author website for Verity North. Built with plain HTML and CSS so it can be hosted for free on GitHub Pages.

## Files
- `index.html` — page structure, copy, navigation, and SEO metadata
- `style.css` — visual styling and responsive layout
- `script.js` — optional lightweight JavaScript placeholder
- `robots.txt` and `sitemap.xml` — search engine crawling/indexing support

## 1) Replace placeholder book cover images
1. Put your cover file in the project root as `franklin-cover.jpg`.
2. The featured section automatically uses it.
3. If the file is missing, an elegant text placeholder is shown automatically.
4. To add a real cover for **Sun King Drama Queen**, replace the `.mini-cover` block in `index.html` with an `<img>` element.

## 2) Update Amazon / Facebook links
1. Open `index.html`.
2. Find each `href="#"` in the book and follow sections.
3. Replace with real links (Amazon, publisher page, Facebook, etc.).
4. Keep the existing HTML comments as guideposts.

## 3) Publish on GitHub Pages
1. Push this repo to GitHub.
2. In your repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch), root folder `/`
4. Save.
5. Your site will publish at:
   `https://USERNAME.github.io/verity-north-website/`
6. Replace `USERNAME` in `index.html` (canonical URL + OG/Twitter/JSON-LD URLs) and in `sitemap.xml`.

## 4) Edit text
1. Open `index.html` in any text editor.
2. Edit headings, paragraphs, and button text directly.
3. Keep one `<h1>` only for SEO clarity.
4. Save and refresh your browser.

## Notes
- No frameworks.
- No paid dependencies.
- Fast-loading and easy to maintain.
