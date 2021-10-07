# Mapping Earthquakes

## Overview
A non-profit organization who's mission is to report data-backed stories about disasters around the world has provided the opportunity to work with their data to build data visualizations with interactive features. The project involves using JavaScript and APIs to visually tell a story about earthquakes around the world. 

## Resources
Data Sources:
- majorAirports.json
- torontoNeighborhoods.json
- torontoRoutes.json
- https://earthquake.usgs.gov/data/data.php#eq
- https://github.com/fraxen/tectonicplates

Software:
- MapBox APIs
- Leaflet 
- D3

## Summary
MapBox, a company that providees custom maps for websites and applications, supplies APIs that will be used to create interactive maps. Using these APIs in combination with the Leaflet JavaScript library, enables easy and highly customizable map creation. The earthquake data was collected from the U.S. Geological Survey website containing data from earthquakes worldwide over the past week. This data was extracted and loaded as a GeoJSON file, a type of JSON data specifically designed to hold geographical information. The final map contained the earthquake data represented as circular markers with their size and color corresponding to the magnitude of the earthquake. Each marker also has a popup that displays the magnitude and location of the earthquake. The map also contains multiple viewing layers (i.e. satellite, street) and the ability to toggle visibility of the earthquake data.

![Earthquakes_with_Legend](https://user-images.githubusercontent.com/32782443/72224779-00b9c400-3533-11ea-8689-54fac8bf5fa0.png)

## Challenge Overview
It would be interesting to see the relationship between the geographical location of the earthquakes and the fault lines of tectonic plates. Visualizing both the fault lines and earthquake data on the same map will give a clear sense of their correlation. 

## Challenge Summary
Tectonic plate data was collected from a GitHub user who uploaded a GeoJSON file contining the boundaries of tectonic plates around the world. Adding this data as another layer to the earthquake map allows the user to toggle visibility of the fault lines and earthquake data. There are also three viewing layers available; street view, satellite view, and light view. 

![Earthquakes_with_Tectonic_Plates](https://user-images.githubusercontent.com/32782443/72224879-fc41db00-3533-11ea-87f7-b48095475d4f.png)

