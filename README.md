# Calgary Permits Explorer

## Overview
Calgary Permits Explorer is an interactive web application that allows users to explore building permits in Calgary. The map displays building permit data retrieved from the Open Calgary API and provides filtering options for a focused view. This application utilizes Leaflet.js, Mapbox, and MarkerCluster to visualize permit locations with detailed popups when markers are clicked.

## Features
* **Interactive Map:** View building permits as markers on an interactive map of Calgary.
* **Date Filter:** Filter permits by selecting a start and end date.
* **Marker Clustering:** Groups nearby permits into clusters for better visualization and performance.
* **Permit Information Popup:** Displays permit details, including issued date, work class group, contractor name, community name, and address.
* **Traffic Incident Layer:** Toggle Mapbox traffic incidents by quadrant.
* **Accident Description Layer:** Toggle accident descriptions using Mapbox layers.
* **Reset Function:** Clear filters and remove displayed permit data.
* **Clickable Map:** Displays latitude and longitude of clicked locations.

## Technologies Used
* **Leaflet.js:** Open-source JavaScript library for interactive maps.
* **Mapbox:** Provides map layers for additional traffic incident data.
* **MarkerCluster:** Leaflet plugin to cluster markers for better performance.
* **GeoJSON:** Data format used for representing building permit data.
* **HTML, CSS, JavaScript:** Used for structuring, styling, and scripting the front-end.
* **Open Calgary API:** Provides real-time permit data in GeoJSON format.

## Installation
To run this project locally:
1. Clone the repository:
   ```sh
   git clone https://github.com/NishathRuksana/Project-3_NishathRuksana
   ```
2. Open `index.html` in a web browser.
3. Optionally, host the files on a web server for public access.

## How to Use
1. **Filter by Date:** Use the date input fields to select a start and end date to filter permits.
2. **View Permit Details:** Click on a permit marker to see details in a popup.
3. **Toggle Map Layers:** Use buttons to toggle traffic incidents and accident descriptions.
4. **Reset Filters:** Click the "Reset" button to clear filters and show all permits.
5. **Click on Map:** Click anywhere on the map to display coordinates in a popup.

## Acknowledgements
* **Leaflet.js** - For providing an interactive mapping library.
* **Mapbox** - For supplying traffic and accident data layers.
* **MarkerCluster** - For optimizing marker display and performance.
* **OpenStreetMap** - For offering free, editable map tile layers.
* **Open Calgary API** - For providing building permit data.

This project was developed as part of an academic assignment for ENGO651 Lab 3 & Lab 4.