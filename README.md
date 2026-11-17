# Casa Ocho: direct-booking homepage concepts

Four static homepage mockups for a direct-booking website for a 2 bedroom home in Little Havana, Miami
(currently listed on Airbnb), plus a gallery page that links them. Each concept is a single homepage with a
working demo booking widget (calendar, guest count, price quote, "book direct" savings). Nothing is sent or charged.

| Path | Concept |
| --- | --- |
| `index.html` | Gallery of all four concepts |
| `deco/` | 1 · Deco Postcard: South Beach Art Deco, pastel, booking card as a vintage hotel postcard |
| `calle-ocho/` | 2 · Calle Ocho: Little Havana heritage, Cuban tile patterns, EN/ES switch, neighborhood first |
| `neon/` | 3 · Neon Nights: Miami after dark, neon accents, sticky app-style booking panel |
| `palm-house/` | 4 · Palm House: tropical boutique hotel, editorial chapters, slim booking bar |

## Notes

- Photos, rating (4.99 from 106 reviews), category scores, rooms and amenities come from the Airbnb listing.
- Rates ($185 weeknights, $225 Fri and Sat, $95 cleaning, 13% taxes), policies, contact details and review quotes
  are samples. Text in `[brackets]` marks content the owner still needs to supply.
- "Casa Ocho" is a working name.
- Pages carry `noindex`. Fonts load from Google Fonts; everything else is inline.

## Viewing

Plain HTML, no build step. Open `index.html`, or serve the folder with `python -m http.server 8000`.
Published with GitHub Pages from the `main` branch root (`.nojekyll` keeps folders served as-is).
