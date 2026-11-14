# Cultural Institutions and Median Income by Census Tract in Philadelphia County (2024)
**by Blythe Crady**
**Published November 2026**

## About This Map
This bivariate web map visualizes the spatial relationship between cultural institutions, specifically museums and art galleries, and median income data by census tract. It uses a white to blue color ramp with 5 classes and the natural breaks classification method. Tracts with no income data are shaded gray. Hovering over an icon or tract displays more detailed information. The basemap is provided by Esri and the map utilizes the [Leaflet](https://leafletjs.com/) library. 

## Data Sources
* Museum and Gallery Point Data: OpenStreetMap contributors, downloaded with [Overpass Turbo](https://overpass-turbo.eu/)
* Median household income: U.S. Census Bureau, American Community Survey 5-Year Estimates 2020-2024, table B19013
* Census tract boundaries: U.S. Census Bureau cartographic boundary files, Philadelphia County
* Basemap: Esri World Dark Gray
* Icons: [Font Awesome](https://fontawesome.com/)

## How This Map Was Made
* Collected data from listed sources
* Used arcGIS pro to Join Census tract shapefile with census median income data
* Used arcGIS pro to clip data from OSM to shapefile boundary
* Used arcGIS pro to calculate the natural breaks feature classification
* Used geojson.io to convert the output of the previous steps to geojson files
* Built the web map with HTML, CSS and JavaScript using Leaflet
