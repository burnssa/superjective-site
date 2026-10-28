# superjective.ai

The site at [superjective.ai](https://superjective.ai): a record of what Superjective built between 2024 and 2026, after the product closed in October 2026.

Plain HTML and CSS, no build step, no JavaScript, no analytics. Every push to `main` deploys to GitHub Pages through `.github/workflows/pages.yml`.

```
index.html            front page
terms/  privacy/  sms-policy/   the policies that applied while the service ran, kept as a record
cupel/                redirects to amlbench.com (the project's current name)
404.html              served for any path that no longer exists (old app routes, result links)
assets/               stylesheet, logo files, Open Graph card, favicons
CNAME                 custom domain for Pages
```

To change the site, edit the HTML and push. There is nothing to install.
