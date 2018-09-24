# A look at Open Data

## Common GIS data formats:

QGIS can be used to import a variety of formats in PostGIS, including Shapefiles, KML and GeoJSON.

- Shapefile: a popular geospatial vector data format for geographic information system (GIS) software. It is developed and regulated by Esri as a (mostly) open specification for data interoperability among Esri and other GIS software products.
- KML: Keyhole Markup Language is an XML notation for expressing geographic annotation and visualization within Internet-based, two-dimensional maps and three-dimensional Earth browsers.
- GeoJSON:  a format for encoding a variety of geographic data structures.


## Open Data Sources
- Ireland's Open Data Portal: [https://data.gov.ie/](https://data.gov.ie/)
- Irish Spatial Data Exchange: [http://isde.ie](http://isde.ie)
- Census 2016 Open Data: [http://census2016.geohive.ie/](http://census2016.geohive.ie/)
- European Data Portal: [https://www.europeandataportal.eu](https://www.europeandataportal.eu)
- 2600+ Open Data sources: [https://www.opendatasoft.com/a-comprehensive-list-of-all-open-data-portals-around-the-world/](https://www.opendatasoft.com/a-comprehensive-list-of-all-open-data-portals-around-the-world/)


## Interesting datasets:

1. [Landslide / Geohazards data, from GSI](https://www.gsi.ie/en-ie/data-and-maps/Pages/Geohazards.aspx)
2. [Railway stations](https://data.gov.ie/dataset/railway-stations-osi-national-250k-map-of-ireland)
3. [Railway lines](https://data.gov.ie/dataset/rail-network-osi-national-250k-map-of-ireland)
4. [Railway road intersections](https://data.gov.ie/dataset/road-rail-intersections-osi-national-250k-map-of-ireland)
5. [Built up areas](https://data.gov.ie/dataset/built-up-areas-osi-national-250k-map-of-ireland)
6. [Settlements](https://data.gov.ie/dataset/settlements-ungeneralised-osi-national-statistical-boundaries)
7. [Population](https://data.gov.ie/dataset/centres-of-population-osi-national-placenames-gazetteer)
8. [Groundwater vulnerability](https://data.gov.ie/dataset/gsi-groundwater-vulnerability)
9. [Dublin development plans](https://data.gov.ie/dataset/development-plans-dublin-city)

## Downloading data:

```bash
# Download the data:
wget http://spatial.dcenr.gov.ie/GSI_DOWNLOAD/Landslide_Susceptibility_Map_Ireland.zip

# Unzip the data:
unzip Landslide_Susceptibility_Map_Ireland.zip
```
