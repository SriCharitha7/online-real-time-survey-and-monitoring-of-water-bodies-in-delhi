# online-real-time-survey-and-monitoring-of-water-bodies-in-delhi
This project utilizes Google Earth Engine (GEE) to monitor, analyze, and visualize the water bodies across Delhi, India in near real-time using satellite imagery and geospatial analysis.

Objective:
To detect, map, and monitor the spatio-temporal changes in the water bodies of Delhi using remote sensing data and cloud-based processing capabilities provided by Google Earth Engine.

Tools & Technologies:
Google Earth Engine (GEE) – for satellite data access, image processing, and visualization

JavaScript API – used in GEE Code Editor for scripting

NDWI (Normalized Difference Water Index) – to identify water pixels

Python / Jupyter (Optional) – for data export, analysis or visualization (if used)

GeoJSON / Shapefiles – for region of interest (Delhi)

Features:
Real-time visualization of water bodies

Change detection over time (seasonal or annual)

Area calculation of water spread

Easy integration with charts/maps for insights

Custom region analysis (within Delhi)

Area of Study:
Delhi, India – covering rivers, lakes, ponds, and other visible water bodies.

Methodology:
Data Acquisition – Accessing satellite images from GEE

Preprocessing – Cloud masking, filtering by date and region

Water Detection – Using NDWI thresholding

Visualization – Display on interactive maps (Map.addLayer)

Temporal Analysis – Comparing multi-date images for trends

Outputs:
Time-series maps of water body changes

NDWI composite images

Area statistics of water presence over time

