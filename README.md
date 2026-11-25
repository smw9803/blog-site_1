[README.md](https://github.com/user-attachments/files/35406572/README.md)
# blog-site_1# Your blog: setup guide

A plain HTML/CSS blog with no build step and no JavaScript. It loads fast and is easy for search engines to read.

## 1. Fill in the placeholders

The site name is already set to "Billable to Free". Find and replace across all files:

- `Your Name` with your name (used in post metadata)
- `example.com.au` with your real domain (appears in canonical links, `sitemap.xml` and `robots.txt`)

Then replace each `[bracketed]` line in `about.html` and the three posts with your own writing, and delete the grey "Draft template" box on each post. Update the post dates to match when you publish.

## 2. Host it for free

Any of these work with the folder as-is:

- **GitHub Pages**: push the folder to a repository and enable Pages.
- **Netlify** or **Cloudflare Pages**: drag and drop the folder.

Then connect your domain in the host's settings. A `.com.au` domain requires an Australian presence (such as an ABN) and is sold by registrars like VentraIP or Crazy Domains; check current prices.

## 3. Get found in search

- Add the site to **Google Search Console** and submit `https://yourdomain/sitemap.xml`.
- Give each post a clear, specific title and a one-sentence description (the `<title>` and `<meta name="description">` tags).
- Publish consistently. Search traffic builds slowly, usually over months.
- Link your posts to each other where relevant.

## 4. Add a new post

1. Copy any file in `posts/` and rename it (use lowercase words with hyphens).
2. Update the title, description, canonical link, date and body.
3. Add it to the list on `index.html` and as a new `<url>` in `sitemap.xml`.

## Before you publish

Keep content to your own experience and general information. Don't mention clients or your firm, and check your employment contract for social media and conflict clauses. Not financial or legal advice.
