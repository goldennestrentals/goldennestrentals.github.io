# GoldenNest Rentals

Whole houses for rent across the United States. A static website (`index.html` + `img/`) hosted on GitHub Pages.

## Editing the site

All settings are at the top of the script in `index.html`:

- `LISTINGS`: the houses (address, city, state, rent, beds, baths, size, type, amenities, move-in date `avail`).
  Houses marked `example:true` are labelled as examples, and viewings and payments are switched off for them.
  Leave `example` out for real houses.
- `PHOTOS`: the main (front) photo of each house. `EXTRA_PHOTOS`: more labelled views (Back, Side, Kitchen…).
- `LOCS`: map position (latitude, longitude) of each house.
- `DETAILS`: facts and features shown on each house page (heating, parking, lease, pets, neighborhood…).
- `PAYMENTS`: application fee, deposit and optional checkout links.
- `CHAT`: tawk.to live chat IDs and the WhatsApp number used for chat, viewing requests and the application fee.
- `REGIONS`: which states belong to each region, and the region tile text.

## Other files

- `brand/`: the logo (full logo in dark and white, square profile picture, icon as PNG and SVG).
- The map uses Leaflet with OpenStreetMap tiles; nearby places come from OpenStreetMap (Overpass).
- Example house photos are from Unsplash (free license).
