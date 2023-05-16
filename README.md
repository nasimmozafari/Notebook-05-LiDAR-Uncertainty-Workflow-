## LiDAR vs Insitu Tree Height Comparison
This repository contains code and data for comparing tree height measurements obtained from LiDAR (Light Detection and Ranging) data with field measurements (insitu) of tree heights. 
The goal is to assess the accuracy and reliability of LiDAR-derived tree height values compared to ground-based measurements.

# Environment Requirements
How to install your environment?
[Start with instructions for installing the earth-analytics-python] (https://www.earthdatascience.org/workshops/setup-earth-analytics-python/)

# Data Resource
The LiDAR data used in this project can be obtained from the "spatial-vector-lidar" dataset available in the earthpy library. 
Specifically, the data for the SJER (San Joaquin Experimental Range) and SOAP (Site for Atmospheric Observatory Purposes) field sites were used.
The insitu field data is available in the form of a CSV file containing vegetation structure measurements collected at the SJER site.

# Analysis
The analysis involved comparing maximum and mean tree height measurements derived from the LiDAR canopy height model with corresponding maximum and mean tree heights obtained from the insitu field measurements.

Scatterplots were created for each field site, with regression lines and 1:1 lines to assess the agreement between LiDAR and insitu measurements. 
The x-axis represents the LiDAR-derived tree height values, while the y-axis represents the insitu field measurements.

# Citations:
NEON - National Ecological Observatory Network. Accessed 05, 12, 2023. https://www.neonscience.org/

Project Contacts @Nasim Mozafari Amiri
Acknowledgements This project was inspired by Dr. Elsa Culler, CU Boulder Earth Lab
License: This project is under the MIT License.
