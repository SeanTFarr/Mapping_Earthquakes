<img src='images\Mapping_Earthquakes_banner (1).png'>

# Overview of the Project
The purpose of this project is to create an interactive webpage to display the differences between the magnitudes of earthquakes aroung the globe for the past 7 days as well as the proximity to the Earth's techtonic plates. URL's from the USGS website were utilized to retrieve GeoJSON data on the coordinates and magnitudes of the earthquakes and a URL from a Github account was used to pull GeoJSON data on the location of the techtonic plates to add to the visualization. 

## Resources used to complete the project:
- Javascript and D3.js library to retrieve coordinates and magnitudes from the GeoJSON data
- Mapbox provides custom maps through an API
- Leaflet library to plot the data on the maps
- HTML to display project in browser
- CSS for styling on the HTML

# Results
The end result is a map that displays the eaarthquake activity around the globe during the past 7 days.

<img src="images\Leaflet_Basic_Map.png">

## How it works:

This icon sits at the top right corner and opens up when the cursor hovers over it to display the options from the map style and the map layers.

<img src="images\layers_no_hover.png">

<img src="images\layers_options.png">

The legend sits at the lower right hand corner and displays the information on the colors based on the magnitude of the earthquake(represented by colored circles).

<img src="images\legend.png">

By clicking on the circles, the user can see the magnitude and location to the registered earthquake displayed in a popup.

<img src="images\popup_marker.png">

# The Maps and Layers:

Upon opening it up, the Street Map is displayed with all layers selected
<img src="images\streets.png">

By selecting the Satellite Map, the map displays a satellite image map that contains a full range of geographic information as well as the street information

<img src="images\satellite.png">

By selecting the Dark Map, the user is provided a geographic context while highlighting the data

<img src="images\dark.png">

To see only the major earthquakes, the user only needs to deselect the Earthquakes and they will get all major earthquakes(greater that a magnitude of 4.5)

<img src="images\major_eq_wth_techt.png">

Or to see the earthquakes without the techtonic plate lines, the user can deselect the Techtonic Plates checkbox and they will see a clean display of the data

<img src="images\no_techtonic.png">