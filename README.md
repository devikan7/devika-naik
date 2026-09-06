# devika-naik

Personal site for Devika Naik. Single static page (`index.html`) plus essays
under `writing/`. Published with GitHub Pages at https://devikanaik.com
(custom domain set in `CNAME`; HTTPS enforced).

## Adding an article

1. Copy `writing/_template.html` to `writing/your-slug.html`.
2. Fill in the title, description, and body — the template lists every
   available block.
3. Link it from the Writing section of `index.html`.

Every article shares one stylesheet, `writing/article.css`. Editing that file
restyles all articles at once; individual article files carry no `<style>` tag.
