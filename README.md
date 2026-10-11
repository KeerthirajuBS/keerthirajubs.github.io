# Keerthiraju BS — Future Portfolio

A responsive portfolio built with HTML, CSS, and vanilla JavaScript. Includes animated visual mockups, pointer effects, scroll reveals, keyboard-accessible project case-study dialogs, responsive navigation, reduced-motion support, SEO metadata, Person structured data, robots.txt, sitemap.xml, and a social preview graphic.

## Personal profile

- Name: Keerthiraju BS
- GitHub: https://github.com/KeerthirajuBS
- LinkedIn: https://www.linkedin.com/in/keerthiraju-b-s-b1a40b295/
- Email: keerthirajubs12@gmail.com

## Run locally

No build tools are required. Open `index.html` in a browser, or run a local server from this directory:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Before deployment: one required SEO step

The final public website URL is not known yet, so the package intentionally does not set a fake canonical URL. After publishing, update all of these with your exact public HTTPS URL:

1. Add `<link rel="canonical" href="https://YOUR-PUBLISHED-DOMAIN/">` in `index.html` inside `<head>`.
2. Add the deployed homepage URL to the Person JSON-LD as its `url` field.
3. Replace `https://YOUR-PUBLISHED-DOMAIN/` in `sitemap.xml`.
4. Replace the example comment in `robots.txt` with `Sitemap: https://YOUR-PUBLISHED-DOMAIN/sitemap.xml`.
5. If desired, make the Open Graph image URL absolute for your deployed domain.

All profile links and the email contact action have already been personalized. GitHub links currently point to your profile, not to invented project repositories. Update each project's link only after the corresponding repository exists.

## Publish with GitHub Pages

1. Create a new public repository in your GitHub account, for example `keerthiraju-portfolio`.
2. Upload the **contents** of this folder to the repository root and commit.
3. Open repository **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for the published HTTPS URL. For a project site, it is commonly `https://KeerthirajuBS.github.io/REPOSITORY-NAME/`; use the exact URL GitHub Pages displays.
6. Complete the SEO URL updates above and commit again.
7. Check all links, modal content, mobile layout, and page source on the live URL.

You can also deploy this folder with Netlify by using its manual deploy workflow or by connecting the GitHub repository.

## Google indexing checklist

1. Open Google Search Console: https://search.google.com/search-console/about
2. Add the deployed site as a URL-prefix property (or verify a custom domain using DNS).
3. Complete Google's ownership verification.
4. Submit the live `sitemap.xml` URL in Sitemaps.
5. Use URL Inspection to test the homepage and request indexing.
6. Link to the portfolio from your public LinkedIn, GitHub profile README, and real project repositories.

Google indexing and ranking are not guaranteed and can take time. The website must be publicly deployed before Google can crawl it.

## Accuracy note

Project detail panels intentionally distinguish learning work and proposed roadmap items from completed functionality. The Knowledge Base is labeled as a proposed concept; verify each project's current implementation and update descriptions before presenting features as completed.
