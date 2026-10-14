# StrideAtlas — Sports Shoe Guide Website

A mobile-first, static website with 500 sports-shoe articles, internal related-article links, a home page, searchable/filterable article library, human-readable sitemap, and XML sitemap. It is designed for GitHub Pages and does not require a backend, database, API key, or build step.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `strideatlas-sports-shoes`).
2. Upload the contents of this folder to the repository root (not the ZIP itself).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Once Pages publishes the site, update the placeholder `YOUR-GITHUB-USERNAME.github.io/YOUR-REPO` in `sitemap.xml`, `robots.txt`, and each article's canonical URL to your real published base URL. Commit the changes.

## Contents
- `index.html` — home page with search, category filters, and pagination
- `articles/` — 500 standalone article pages
- `sitemap.html` — reader-friendly sitemap with all articles
- `sitemap.xml` — XML sitemap for search engines
- `robots.txt` — crawler instructions
- `assets/style.css` — responsive dark UI
- `assets/app.js` and `assets/articles-data.js` — client-side article search/filtering

## Images and editorial note
Article images are loaded from Unsplash image URLs, so visitors need an internet connection to see them. The generated copy is educational starter content and should be reviewed and fact-checked before publication, especially any claims you later add about medical outcomes, product testing, or named brands. The articles intentionally avoid fabricated product reviews and medical promises.

## Important SEO note
GitHub Pages is static hosting. This site has no server-side search or CMS; the article search runs in the browser. Internal article links and both sitemap formats are included. Search indexing is not guaranteed, and a sitemap does not guarantee rankings.
