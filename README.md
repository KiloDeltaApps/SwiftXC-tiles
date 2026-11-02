# SwiftXC map tiles

1°×1° vector map tiles (`tiles/N52E005.vector.gz`, SRTM naming) for the SwiftXC soaring app.
Coverage: Benelux and western Germany (lat 49–53 N, lon 2–9 E; 40 tiles, about 31 MB).

The app downloads them from the tile selector. Default source:

    https://raw.githubusercontent.com/KiloDeltaApps/SwiftXC-tiles/main/tiles

Contents: coastlines, borders, water, forests, roads, railways, power lines (Natural Earth),
airfields, helipads and typed obstacles (OpenAIP), streams, rivers, canals, village outlines
and village names (OpenStreetMap, ODbL © OpenStreetMap contributors).

They are generated from the SwiftXC repo with `scripts/enrich_tiles_openaip.py` and `scripts/osm_layers.py`.
