# Mapping_Earthquakes
## Overview

This project's goal was to use the Leaflet library and a Mapbox API to generate maps tracking earthquake data around the world. The data about earthquakes that have occured over the past seven days was taken from the United States Geological Survey (USGS)'s publicly available JSON files provided on their website. I was able to generate a webpage that displays a street view map upon loading, and two additional map layers that the user can toggle between. There are also three optional layers for lines depicting major fault lines, circle markers for all earthquakes in the past 7 days, and a seperate layer of circle markers for a subset of all earthquakes which have a magnitude over 4.5 on the Richter scale.

### Resources
- Data:
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
    - https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
    - https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
- Software: Visual Studio Code 1.70.1, Google Chrome 106.0.5249.103