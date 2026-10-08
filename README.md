# Images

Drop your photos here. Until a file exists, the site shows a styled gold
placeholder instead — nothing breaks, so you can add products before photos.

Paths are set in `src/data/catalog.js` (categories + products) and
`src/data/content.js` (hero, about, payment logos).

```
hero/
  hero.jpg            → home page hero (wide, 2000×1200 or larger)
  categories.jpg      → banner behind the Categories page header

categories/           → one per category, portrait works best (1200×1500)
  horse-bits.jpg
  stirrups.jpg
  bridles-headstalls.jpg
  saddles.jpg
  spurs.jpg
  girths-leathers.jpg
  farrier-grooming.jpg
  buckles-fittings.jpg

products/             → one per product, SQUARE (1200×1200), file name matches
                        the `image` path in catalog.js

about/
  workshop.jpg        → home page about section (portrait)
  workshop-wide.jpg   → About page header (wide)
  detail.jpg          → About page detail shot (portrait)

payments/             → transparent PNG logos, roughly 200×60
  mcb-islamic.png
  western-union.png
  moneygram.png
```

Tip: compress before uploading (TinyPNG or Squoosh). Aim under ~250 KB each.
