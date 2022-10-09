# leaflet-challenge

# Background
The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

# Task
Visualize an earthquake data set

1. The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visited the USGS GeoJSON Feed page and picked the data set to visualize: 'All Earthquakes from the Past 7 Days'. I retrieved a JSON representation of that data. I used the URL of this JSON to pull in the data for my visualization.

2. I created a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

My data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

I included popups that provide additional information about the earthquake when a marker is clicked.

I created a legend that will provide context for your map data.


