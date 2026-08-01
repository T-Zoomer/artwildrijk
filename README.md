# Art Wildrijk

Static single-page site (HTML + Tailwind CSS via CDN, no build step), based on the
[Art Wildrijk event page](https://www.landschapnoordholland.nl/activiteiten/evenementen/art-wildrijk)
on landschapnoordholland.nl.

## Develop

Just open `index.html` in a browser, or serve it locally:

```
python3 -m http.server 8000
```

## Deploy (GitHub Pages)

1. Push to `main`.
2. In the repo on GitHub: **Settings → Pages → Source** → select branch `main`, folder `/ (root)`.
3. The site will be published at `https://t-zoomer.github.io/artwildrijk/`.

## Notes

- Images are currently hotlinked from landschapnoordholland.nl (event photos). These are the
  photographer's copyrighted assets — swap them for your own images before using this beyond a
  personal/local template.
