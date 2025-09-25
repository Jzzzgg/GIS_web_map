# GIS_web_map
📌 Overview

This project demonstrates how to combine urban Point of Interest (POI) data with population datasets to create an interactive geospatial visualization. The goal is to showcase how spatial data can be integrated, analyzed, and presented using Python and WebGIS tools.

🔧 Tech Stack

Python: geopandas, shapely, matplotlib, folium

Database: PostGIS for spatial queries

WebGIS: Leaflet.js for interactive mapping

Backend: Flask (simple API to serve GeoJSON)

📊 Features

Load and process POI datasets (e.g., schools, hospitals, restaurants).

Integrate population density data from census shapefiles.

Perform spatial joins: link POIs with population statistics by district.

Visualize results on an interactive map with layers and tooltips.

Provide a simple web interface to explore the data.

🚀 Example Use Cases

Urban planning: Identify underserved regions lacking healthcare or schools.

Business intelligence: Find high-population areas with fewer restaurants.

Public policy: Support data-driven decision-making for city development.

📂 Deliverables

Python scripts for spatial data preprocessing.

PostgreSQL/PostGIS setup scripts for spatial queries.

A simple Flask API serving processed GeoJSON.

An interactive Leaflet web map for visualization.
