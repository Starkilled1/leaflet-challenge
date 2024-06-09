# leaflet-challenge

## Background

The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Project Overview

This repository contains the code for visualizing earthquake data provided by the USGS. The visualization is done using the Leaflet library, which allows us to create interactive maps that display earthquake data in a meaningful way. The data markers on the map reflect the magnitude and depth of the earthquakes, with larger markers representing higher magnitudes and darker colors representing greater depths.

## Directory Structure

- **static/js**
  - This directory contains the JavaScript files that include all the logic for creating the Leaflet map and adding earthquake data to it.
  
  - `logic.js`: This file fetches earthquake data from the USGS GeoJSON feed, processes the data, and uses Leaflet to create a map with markers that represent the earthquake locations, magnitudes, and depths.

- **static/css**
  - This directory contains the CSS files that style various elements of the project.
  
  - `style.css`: This file includes styles for the map and the legend, ensuring that the visualization is both functional and visually appealing.

## Getting Started

To get started with this project, open the `index.html` file in your web browser to view the earthquake visualization map.

## Usage

- The map displays earthquake data from the past 7 days, fetched from the USGS GeoJSON feed.
- Each marker on the map represents an earthquake, with the size of the marker corresponding to the earthquake's magnitude and the color corresponding to its depth.
- Clicking on a marker will display a popup with additional information about the earthquake, including its location, magnitude, and depth.

## USGS GeoJSON Feed

The earthquake data used in this project is fetched from the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). This page provides a variety of earthquake data in GeoJSON format, updated every 5 minutes.

## Acknowledgements

- The Leaflet library for providing a powerful tool for creating interactive maps.
- The USGS for providing the earthquake data and for their continued efforts in monitoring and studying natural hazards.