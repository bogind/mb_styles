# MapBox (and MapLibre) GL JS styles

Basic style JSON files using the MapBox GL JS style specification.   
While the MapBox GL JS style specification is open source, I am building the styles using the spec from the [**MapLibre GL JS Style Spec**](https://maplibre.org/maplibre-style-spec/) which is also open source and might differ from what is used in MapBox.  
This means, that there can be some differences in the styles between the two libraries, mostly from developments originating **after** MapLibre GL JS was forked from the MapBox GL JS library.

## Styles

- [**Basic Style**](https://bogind.github.io/mb_styles/styles/base_osm_yiles.json) - A basic style using OpenStreetMap **raster** tiles.
- [**OSM Vector Style for QGIS**](https://bogind.github.io/mb_styles/styles/openstreetmap_desktop.json) - A style using OpenStreetMap **vector** tiles from [https://vector.openstreetmap.org/shortbread_v1](https://vector.openstreetmap.org/shortbread_v1/{z}/{x}/{y}.mvt), an edit of [https://maps.gishub.org/styles/openstreetmap.json](https://maps.gishub.org/styles/openstreetmap.json) changing the font name to those compatible with a regular install of [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans).
- [**OSM Vector Style**](https://bogind.github.io/mb_styles/styles/openstreetmap.json) - A style using OpenStreetMap **vector** tiles from [https://vector.openstreetmap.org/shortbread_v1](https://vector.openstreetmap.org/shortbread_v1/{z}/{x}/{y}.mvt), a copy of [https://maps.gishub.org/styles/openstreetmap.json](https://maps.gishub.org/styles/openstreetmap.json).