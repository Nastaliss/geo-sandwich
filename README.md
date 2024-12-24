# Geo Sandwich

Generate a layered physical map from geographical data that you can cut / 3d print.
This will create a combination of svg and stl shapes from maps.

## Getting started

### From gpkg
Convert your gpkg database to shapes using
```
ogr2ogr -f GeoJSON out.json U2018_CLC2018_V2020_20u1.gpkg
```
