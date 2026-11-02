# Yalla Plan — Canada places (review data)

Read-only data used by the Places Review app. One file per province/territory in `provinces/`, plus `index.json`.

Each place has `status`:
- `live` — already in the Yalla Plan explore feed (`id` is the production id)
- `new` — candidate found in open data, waiting for professional review

Sources and licences:
- Places with photos: [Wikidata](https://www.wikidata.org) (CC0); photos hosted on [Wikimedia Commons](https://commons.wikimedia.org) under their own free licences.
- Restaurants, cafés, bars, spas: © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, ODbL.
