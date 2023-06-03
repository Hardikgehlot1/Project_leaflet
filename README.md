# leaflet-challenge
The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this project, i am developing visualization using USGS data that will show all the data on the map using Leaflet.
The data is available every hour on ugsc site. 
 1. Data resources = https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
The data can be found for past hours, past day , week and month. In this project, I am using data from past 7 days.
The follwing is the steps, i have used to make visualization.
  From UGSC website, I am copying a link to json life containing past 7 days earthquake data. 
  Using visual basics, I am coding javascript to achive the goal.
  ## First step
  frist step is to import data using D3.js in the javascript file.
  The provided url to D3.js is the link to jason file from the UGSC website.
  ## Second step
  creating a map functction myMaps using L.map and specifying a center and zoom. 
 
