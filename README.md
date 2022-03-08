# Valencia Bikeway

Behold a modest proposal to add a two-way protected cycletrack on the east side of Valencia St and converting the west lane to alternating one-way traffic, with lots of 10-minute loading zones for food pickup and commercial delivery, as well as accessible blue-zone parking alongside lots of parklets and more human-friendly space.

https://streetmix.net/burritojustice/6/valencia-st-15th-19th

![streetmix](images/valencia-st-15th-19th.png)

Zoomable map: marching ants indicate direction of travel. There are increasing levels of road detail and parklets visible as you zoom in.

https://burritojustice.github.io/valencia_bikeway/#18/37.75774/-122.42144

![screenshot](images/one-way.gif)

## Assumptions and Questions:

- The alternating one-way patterns along the blocks is farily arbitrary.
- 14th to 19th is the narrowest part of Valencia, and raises some of the biggest question on how to allocate space after a two-way cyclepath.
- What does traffic looks like north of 14th and south of 24th? The streets are wide enough to have two way traffic and a protected two-way cyclepath.
- Assuming loading islands for school drop-off at Synergy and Buena Vista-Horace Mann. These could be used for general parking outside of school loading hours as is done along 14th. 
- Muni has a few lines to consider - 27 (24th to CC), 12 (26th to CC), 55 (16th-15th, which I believe is non-revenue). There's also need for counterflow SFPD access along 18th.

## Sources

tangram.js, Tilezen, 2019 curblines from [data.sf.gov](https://data.sfgov.org/City-Infrastructure/City-curbs-and-islands/4s5e-m4gv). 

https://data.sfgov.org/City-Infrastructure/City-curbs-and-islands/4s5e-m4gv

There is no data available for Shared Spaces on data.sfgov.org, just a published map, but I liberated it for the purpose of this exercise.

[Shared Spaces GeoJSON](https://services.arcgis.com/Zs2aNLFN00jrS4gG/arcgis/rest/services/shared_spaces_data/FeatureServer/0/query?f=geojson&where=1%3D1&returnGeometry=true&spatialRel=esriSpatialRelIntersects&outFields=*&maxRecordCountFactor=4&outSR=4326&resultOffset=0&resultRecordCount=8000&cacheHint=true&quantizationParameters=%7B%22mode%22%3A%22view%22%2C%22originPosition%22%3A%22upperLeft%22%2C%22tolerance%22%3A1.0583354500041853%2C%22extent%22%3A%7B%22xmin%22%3A-13638852.978948362%2C%22ymin%22%3A-1436598.6699333906%2C%22xmax%22%3A-8621695.126715293%2C%22ymax%22%3A5983364.401551564%2C%22spatialReference%22%3A%7B%22wkid%22%3A4326%2C%22latestWkid%22%3A4326%7D%7D%7D) (reformatted to 4326)
