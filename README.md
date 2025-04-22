# dynamic-navigation-and-immersive-mapping-enhancing-route-optimization-with-AI

This project is a full-featured web-based indoor navigation system built using Mapbox GL JS, allowing users to:

Interact with a beautiful custom-styled map

Use custom waypoints for navigation

Search for locations

View directions between selected waypoints

Toggle 3D map view

Utilize current location

✨ Features
✅ Custom Mapbox style

📍 Clickable markers with automatic shortest path calculation

🔍 Searchable location input fields

📡 Use current geolocation as start point

🧭 Sidebar-ready layout for responsive data display

🧱 3D building toggle button

📂 Supports GeoJSON loading for dynamic waypoint rendering

📁 Folder Structure


├── index.html              # Main application file
├── leaflet-sidebar.css     # Sidebar CSS (optional)
├── stylem.css              # Custom styles
├── map.geojson             # GeoJSON file for route waypoints
🚀 Getting Started
Prerequisites
A free Mapbox access token

A local server (use Live Server extension in VSCode or Python SimpleHTTPServer)

Setup
Clone this repository:
```
git clone https://github.com/your-username/mapbox-indoor-wayfinding.git
```
Replace the Mapbox Access Token in index.html:
```
mapboxgl.accessToken = 'YOUR_MAPBOX_ACCESS_TOKEN';
```
Add your map.geojson file in the root or desired path:
```
fetch('path/to/your/map.geojson')
```
Launch it with a local server:
```
npx serve
# or
python3 -m http.server
```
📸 Screenshots

🔍 Searchable UI	🧭 3D View	📍 Custom Waypoints
💡 Customization
Update your custom style URL:
```
style: 'mapbox://styles/YOUR_USERNAME/YOUR_STYLE_ID'
```
To use your own markers and route points, modify or replace the customGeojson and map.geojson logic.

🧑‍💻 Tech Stack
HTML + CSS

JavaScript (Vanilla)

Mapbox GL JS v2 & v3

GeoJSON (for routing)

Optional Leaflet Sidebar

🙌 Acknowledgements
Thanks to Mapbox for the awesome tools.

Shoutout to the project contributors and testers.
