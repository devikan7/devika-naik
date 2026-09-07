# devika-naik

Personal site for Devika Naik — a single static page (`index.html`).
Published with GitHub Pages at https://devika.nyc (custom domain in `CNAME`,
HTTPS enforced).

## Writing

Entries in the Writing section link out to Medium
(`devika-naik.medium.com`) and open in a new tab. To add one, drop a `<p>`
into that section of `index.html`:

```html
<p>Article Title -
<a href="https://devika-naik.medium.com/..." target="_blank" rel="noopener noreferrer">Read it</a></p>
```

Use a plain hyphen before "Read it", not an em dash.

## SEO

`index.html` carries a canonical URL, OpenGraph + Twitter Card tags, and
`Person` JSON-LD. `robots.txt` points crawlers at `sitemap.xml` (the home
page only). Social/share image is `images/devika.jpg`. To get into Google,
verify the domain in Google Search Console and submit
`https://devika.nyc/sitemap.xml`.
