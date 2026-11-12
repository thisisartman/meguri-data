# Meguri data

Region packs for Meguri, a collecting app for Japanese manhole cards, station stamps, Ekitag, dam cards and museum stamps. The app downloads these files from this repository's latest release, one prefecture at a time.

Each release has:
- `index.json`: every pack, with its prefecture, type, item count, size and SHA-256 checksum.
- `JP-<code>-<type>.csv.gz`: the catalogue for one prefecture and type, as a gzip CSV.
- `JP-<code>-map.pmtiles`: an offline map of one prefecture.

## Sources and licences

- Catalogue: compiled from public pages of prefectures, cities, the Ministry of Land, Infrastructure, Transport and Tourism (dam cards), JR East and the GKP manhole card listings. Each row's `source_url` names its source.
- Station positions: © OpenStreetMap contributors, ODbL.
- Maps: Protomaps basemap built from OpenStreetMap, © OpenStreetMap contributors, ODbL.
