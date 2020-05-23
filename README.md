# Mapping_Earthquakes

## Project Overview
The following repository includes files for creating different maps using the Mapbox API with Leaflet styling.

The repo is organized into different folders for all the maps created, as follows:
| Folder | Map |
|------------|--------------------|
| Simple_Map | A basic map that shows the Continental US and the surrounding countries |
| Mapping_Single_Points | A basic map that plots a 300-pixel radius of Central Los Angeles |
| Mapping_Multiple_Points | A map that plots varying size circle markers with popup information about different cites|
| Mapping_Lines | A map that plots an airline route from SFO to John F. Kennedy International Airport (JFK) with two stops, Austin-Bergstrom International Airport (AUS) and Toronto Pearson International Airport (YYZ)|
| Mapping_GeoJSON_Points | A map that plots a single point (SFO) with a pop-up marker from GeoJSON data|
| Mapping_Multiple_GeoJSON_Points | A map that plots multiple points (airpots) with pop-up markers from GeoJSON data|
| Mapping_Multiple_Maps | The map that is contained in Mapping_Multiple_GeoJSON_Points with 2 different tile layers (*Street* and *Dark*)|
| Mapping_GeoJSON_Linestrings | A map that plots the nonstop flight routes from Toronto (YYZ) (geoJSON data) with 2 different tile layers (*Day Navigation* and *Night Navigation*)|
| Mapping_GeoJSON_Polygons | A map that plots Toronto neighbourhoods geoJSON data with 2 different tile layers (*Streets* and *Satellite Streets*) |
| Earthquakes_past7days | A map that plots earthquakes geoJSON data from the past 7 days as circle marker overlays, coloured and sized by magnitude with 2 different tile layers (*Streets* and *Satellite Streets*) and a legend for the earthquake data |
| Earthquake_Challenge | The map plotted in Earthquakes_past7days with additional geoJSON data for tectonic plates (plotted as an overlay) with 3 different tile layers (*Streets*, *Satellite* and *Light*) |

## Images of maps
Since and API key is required to view the actual maps, the following images show some of the maps created in this repo.

### Mapping_Multiple_Points
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/Cities.png)

### Mapping_Lines
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/SFOtoJFKviaAUSandYYZpng.png)

### Mapping_Multiple_Maps
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/Airports1.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/Airports2.png)

### Mapping_GeoJSON_Linestrings
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TorontoFlights1.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TorontoFlights2.png)

### Mapping_GeoJSON_Polygons
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TorontoNeighbourhoods1.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TorontoNeighbourhoods2.png)

### Earthquakes_past7days
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/Earthquakes1.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/Earthquakes2.png)

### Earthquake_Challenge
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TectonicPlates1.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TectonicPlates2.png)
![](https://github.com/karenbennis/Mapping_Earthquakes/blob/master/Images/TectonicPlates3.png)

## Resources
* Data Sources and APIs: 
    * majorAirports.json,
    * torontoRoutes.json,
    * torontoNeighborhoods.json,
    * https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson,
    * https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
    * Mapbox API
* Languages: JavaScript ES6+,  HTML5, CSS
* Libraries: Leaflet JavaScript
* Software: Visual Studio Code 1.43.0, Chrome 81.0.4044.138

## Recommendations
As a Toronto native, I'd be interested in plotting different maps with Toronto data, exploring more features that Leaflet has in the library; however, in terms of specific recommendations for further analysis, I would hesitate to make any for this particular data. To practice using different features in Leaflet, it might be recommended to update the current maps with different options the library provides.