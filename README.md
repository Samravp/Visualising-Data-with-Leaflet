# Visualising Data with Leaflet

## Background

![1-Logo](Images/1-Logo.png)

The United States Geological Survey, or USGS for short is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

In this project I visualised USGS's earthquake data. USGS collects a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. My goal is to visualise their data and allow them to better educate the public and other government organisations (and hopefully secure more funding..) on issues facing our planet.


### Basic Visualisation

![2-BasicMap](Images/2-BasicMap.png)


1. **Get the data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and picked a data set to visualise, a JSON representation of that data. I used the URL of this JSON to pull in the data for the visualisation.

   ![4-JSON](Images/4-JSON.png)

2. **Importing & Visualising the Data**

   I created a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * The data markers reflect the magnitude of the earthquake in their size and colour. Earthquakes with higher magnitudes should appear larger and darker in colour.

   * Include popups that provides additional information about the earthquake when a marker is clicked.

   * Creates a legend that will provide context for the data.

   * The visualisation looks like the map above.
