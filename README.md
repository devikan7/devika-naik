# devika-naik

Personal site for Devika Naik. Single static page (`index.html`) plus essays
under `writing/`. Published with GitHub Pages at https://devikanaik.com
(custom domain set in `CNAME`; HTTPS enforced).

## Adding an article

1. Copy `writing/_template.html` to `writing/your-slug.html`.
2. Fill in the title, description, and body — the template lists every
   available block.
3. Fill in the SEO block at the top (SLUG / TITLE / DESCRIPTION / date).
4. Link it from the Writing section of `index.html`.
5. Add the new URL to `sitemap.xml`.

Every article shares one stylesheet, `writing/article.css`. Editing that file
restyles all articles at once; individual article files carry no `<style>` tag.

## SEO

Each page carries its own canonical URL, OpenGraph + Twitter Card tags, and
JSON-LD (`Person` on the home page, `BlogPosting` on articles). `robots.txt`
points crawlers at `sitemap.xml`. Social/share image is `images/devika.jpg`.
To get pages into Google, verify the domain in Google Search Console and
submit `https://devikanaik.com/sitemap.xml`.
