# Saar LiDAR Explorer – Daten (Teil 2)

Second static data repository of the [Saar LiDAR Explorer](https://open-kirrberg.github.io/saar-lidar-explorer/) (code: https://github.com/Open-Kirrberg/saar-lidar-explorer), served at https://open-kirrberg.github.io/saar-lidar-data-2/. Split from [Teil 1](https://open-kirrberg.github.io/saar-lidar-data/) to stay below the GitHub Pages site limit (1 GB).

> **Schauen, nicht graben.** Terrain data and models, not finds. No digging, no metal detecting; sites are protected (SDschG Saarland, DSchG RLP).

## Contents

| Path | What |
|---|---|
| `overall/xyz/<layer>/{z}/{x}/{y}.png` | Leaflet (EPSG:3857) tiles of the relief layers and historic maps up to zoom 17 (the app overzooms beyond). Referenced from `https://open-kirrberg.github.io/saar-lidar-data/overall/manifest.json`. |
| `print/<series>/` | 3D-printable terrain tiles: `index.json`, `<id>.3mf` (Bambu Studio / any slicer), `<id>.png` preview, `layout.png`, `keys/` (bowtie connector), `printer/` (Bambu Studio printer preset). STL tile meshes are not published (3MF only). |

- `print/detail-2300/` – Detail 1:2300: 6 3MF-Kacheln
- `print/saarpfalz-9200/` – Saarpfalz 1:9200: 13 3MF-Kacheln

## Licences and attribution

Code: MIT (code repository). **Data keep their own licences:** Geobasisdaten Saarland (LVGL-SL) and Rheinland-Pfalz (GeoBasis-DE/LVermGeoRP) under **Datenlizenz Deutschland – Namensnennung – 2.0** (dl-de/by-2-0, https://www.govdata.de/dl-de/by-2-0), processed („Daten bearbeitet“). Print tiles are terrain models derived from the DGM1 (same licence) — a model, not a finding.

- © GeoBasis-DE/LVGL-SL (2026), dl-de/by-2-0, Daten bearbeitet (Historische Karten)
- © GeoBasis-DE/LVGL-SL (2026), dl-de/by-2-0, Daten bearbeitet
- © GeoBasis-DE/LVermGeoRP (2022), dl-de/by-2-0, www.lvermgeo.rlp.de, Daten bearbeitet
