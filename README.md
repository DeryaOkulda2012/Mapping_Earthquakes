# Mapping_Earthquakes

## Purpose

The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks

To complete this project, we use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

## Approach

The approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

The earthquake map is created with two different maps and the earthquake overlay. Now the earthquake data will be shown in relation to the tectonic plates’ location on the earth, and all the earthquakes with a magnitude greater than 4.5 is shown on the map. There is also a third map showing the night, and all earthquakes in the last seven (7) days.

!["Photo_Gallery/Earthquake_Map.png"](Photo_Gallery/Earthquake_Map.png)

Same earthquake map overlay with a Satellite Map

!["Photo_Gallery/Earthquake_Map_Satellite.png"](Photo_Gallery/Earthquake_Map_Satellite.png)

Same earthquake map overlay with a Night Map

!["Photo_Gallery/Earthquake_Map_Night.png"](Photo_Gallery/Earthquake_Map_Night.png)
