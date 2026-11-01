# Qloudex website

The static website for [Qloudex](https://qloudex.tech/), an early-stage AI &
Cloud Engineering Studio. GitHub Pages serves the site directly from the
repository root.

## Structure

- `index.html` contains the site markup, CSS, and JavaScript.
- `404.html` is the custom not-found page.
- `favicon.svg`, `apple-touch-icon.png`, and `brand/` contain brand assets.
- `og-image.svg` is the editable 1200×630 social preview source.
- `og-image.png` is the raster social preview referenced by page metadata.
- `CNAME`, `robots.txt`, and `sitemap.xml` preserve the custom-domain setup.

## Preview locally

```bash
python3 -m http.server 8080
```

Open <http://127.0.0.1:8080/>. Test the page at 360, 768, 1024, and desktop
widths, including keyboard navigation and reduced-motion mode.

## Contact behavior

“Discuss a Project” links open the visitor's default email application with a
draft addressed to `hello@qloudex.tech`. The website does not submit a form or
claim that delivery succeeded. Verify inbox delivery separately before treating
the address as an operational lead channel.

## Deployment safety

The production domain is `qloudex.tech`. Do not delete or change `CNAME`, DNS,
or GitHub Pages settings as part of ordinary content work. Review a branch
preview and merge through the normal pull-request process.

## Social preview

After editing `og-image.svg`, export it to `og-image.png` at exactly
1200×630. Confirm the PNG before merging because social platforms use that file.

## Links

- Website: <https://qloudex.tech/>
- GitHub: <https://github.com/Qloudex>
- Contact: `hello@qloudex.tech`
