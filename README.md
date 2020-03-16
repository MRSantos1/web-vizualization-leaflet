# Web Data Visualization of Eathquakes using Leaflet

Data markers reflect the magnitude of the earthquake in their size and color. 

Earthquakes with higher magnitudes appear larger and darker in color.

Popups provide additional information about the earthquake when a marker is clicked.Legends provide context for map data.

------

## Summary:

The United States Geological Survey (USGS) (https://www.usgs.gov/) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

Here, I build a set of tools that will allow visualization of USGS earthquake data. USGS collects a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

The ability to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

First, we will visualize an earthquake data set.

The steps are describe below.

1. **Dataset guidelines**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. 
   
   When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

    - Data markers reflects the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

    - Popups provide additional information about the earthquake when a marker is clicked.
    
    - Legend provide more context for the map data.
    
    - The final visualization looks something like the map above.

- - -

### Advanced Visualization:

![5-Advanced](Images/5-Advanced.png)

Here I plot a second data set on the map to illustrate the relationship between tectonic plates and seismic activity.

To this, You will need to pull in a second data set and visualize it along side your original set of data. 

Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

- - -

#### Contact:
<b>E-mail: </b> robertomsreis@gmail.com
 
<b>Twitter: </b> @robertomsreis

