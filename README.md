# GeoMapping-Visualizing-Data-with-Leaflet

Earthquake-Visualization (Level 1):
I created a map using Leaflet that plots all of the earthquakes and faultlines based on their longitude and latitude to find the relationship between tectonic plates and seismic activity.
>Per Level 1 of the Instructions below, the map image(s) shows the earthquake data over the last 7 days.  Color and size of the circles correspond to the magnitude of the earthquake.  Click the circles for additional information (such as date, time:EST, proximity to nearby town/metro area, magnitude of the earthquake and the number of people who reported feeling it). The deeper the color red in the circle, the greater size in magnitude of the earthquake measured (see "largestearthquake.png" in the image folder for the largest earthquake measured during the week reviewed).  In addtion, per Level 2 of the Instructions, a tectonic plates filter was created for the image page (although no additional analysis was performed). Map format was enhanced by using a mapbox.com/api.

Background

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

Before You Begin
Create a new repository for this project called leaflet-challenge. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: Leaflet-Step-1 and Leaflet-Step-2.

This homeworks utilizes both html and Javascript so be sure to add all the necessary files. These will be the main files to run for analysis.

Push the above changes to GitHub or GitLab.

Your Task
Level 1: Basic Visualization
2-BasicMap

Your first task is to visualize an earthquake data set.

Get your data set

3-Data

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

4-JSON

Import & Visualize the Data

Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

Include popups that provide additional information about the earthquake when a marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the map above.

Level 2: More Data (Optional)

5-Advanced
The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it along side your original set of data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.

In this step we are going to..
Plot a second data set on our map.
Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.
Add layer controls to our map.

