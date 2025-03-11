**Calgary Permits Explorer**

This is an interactive web application that allows users to explore building permits in Calgary. The map displays building permit data, which can be filtered by date range for a more focused view. The application uses Leaflet.js and MarkerCluster to visualize permit locations, providing a detailed popup with permit information when clicked.

**Features**

- Interactive Map: View building permits as markers on an interactive map of Calgary.
- Date Filter: Filter permits by start and end date to narrow down the results.
- Marker Clustering: Group permits into clusters for easier navigation and a cleaner map interface.
- Popup Information: Click on any permit marker to see details like issued date, work class group, contractor name, community name, and original address.
- Reset Function: Clear the date filter and remove any displayed permit data.


**Technologies Used**

- Leaflet.js: A popular open-source JavaScript library for creating interactive maps.
- MarkerCluster: A Leaflet plugin that clusters nearby markers together for better performance and presentation.
- GeoJSON: Used to represent building permit data in a simple, accessible format.
- HTML, CSS, JavaScript: Used for building the front-end user interface and map interactions.

**Installation**

To run this project locally, follow these steps:

1. Clone the repository:
    git clone https://github.com/NishathRuksana/Project-3_NishathRuksana
2. Open index.html in your preferred browser to view the application.
3. Optionally, host the files on a web server for public access.

**How to Use**

1. Filtering by Date: Use the date input fields at the top-right corner to select a start and end date for the building permits you want to view.
2. View Permit Details: Click on any of the permit markers on the map to see detailed information about that permit in a popup.
3. Reset Filters: Press the "Reset" button to clear the date filters and view all available permits.

**License**

This project is created for academic purposes as part of the ENGO651 – Lab 3 Assignment.

**Acknowledgements**

- Leaflet.js: For providing an easy-to-use map library for interactive maps.
- MarkerCluster: For offering an efficient solution to display clustered markers.
- OpenStreetMap: For providing free, editable maps used as the tile layer in this application.

