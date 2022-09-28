# Mapping_Earthquakes

## Purpose

Is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Results
1. Add Tectonic Plate Data

Tectonic plate date is added as the second layer group and to the overlay object.
d3.json() callback is working and passes the tectonic plate date to the geoJSON().  The geoJSON adds color (blue) and width to tectonic plate lines.  Tectonic layer group variable is added to the map.

2. Major Earthquake Data

Major earthquake data is added as a thrid layer group and to the overlay object.
d3.json() callback is working and passes the major earthquake data (with set color and diameter) to the geoJSON() layer.  The geoJSON layer creates a circle for each major earthquake and adds a popup for each circle to display the magnitude and location of the earthquake.  Major earthquake layer group variable is added to the map.

3. Additional Map

Third layer is created, dark.  The dark layer is added to the overly object.  All earthquake data and tectonic plate data are displayed on all maps of the webpage.

## Website
[Website](https://nkinsler.github.io/Mapping_Earthquakes/Earthquake_Challenge/index.html)
