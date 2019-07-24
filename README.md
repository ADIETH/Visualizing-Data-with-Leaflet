# Visualizing-Data-with-Leaflet

## Background

![1-Logo](Images/1-Logo.png)


The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.



###  Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

 visualize an earthquake data set.

1. **Get your data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. I will be using the URL of this JSON to pull in the data for My visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from  data set based on their longitude and latitude.

   *  data markers  reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes  appear larger   and darker in color.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that have provide context for your map data.

  


###  More Data 

![5-Advanced](Images/5-Advanced.png)


* Plot a second data set on our map.

* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

* Add layer controls to our map.



