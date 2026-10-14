# Street Explorer — city data

Map data for the Street Explorer app. To start exploring a city, the app downloads its
**city pack** from here once; after that it works offline in that city.

- `cities.json` — the list of available cities (name, area, download size, pack version)
- `packs/<city>-v<version>.json` — a city pack: every walkable street, food spot and sight,
  and the neighbourhoods with what there is to discover in each

Packs are generated from OpenStreetMap by the app's build script and published here.
Old pack versions are kept so installed apps never break.

## Data licence

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available
under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
The city packs are derived databases and are released under the same licence.
