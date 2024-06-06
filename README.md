# Fire_effects_on_veg_structure_using_lidar

The Creek Fire was a large wildfire that started in September 2020 in the Sierra National Forest, California and became one of the largest fires of the 2020 California wildfire season. This fire had burned into NEON's Soaproot Saddle (SOAP) site by mid-September, causing a high intensity burn over much of the site - standing trees became charcoal spires, shrubs and their root systems burned completely, the thick litter layer was incinerated, and the soil severely burned.

The NEON Airborne Observation Platform (AOP) conducted aerial surveys over SOAP in 2019 and 2021, a year before and after the Creek Fire. This exercise aims to study the effects of fire on vegetation structure by comparing the lidar-derived relative height percentiles before and after the fire. In addition to the discrete return data, this tutorial uses a Digital Terrain Model (DTM) to determine the relative height of the discrete returns with respect to the ground.

This Python tutorial is broken down into three parts:

Read the NEON discrete-return lidar data (DP1.30003.001) and visualize the 3D lidar point cloud.
Read the lidar-derived Digital Terrain Model (DP3.30024.001) in Python. Visualize the spatial extent of the lidar data used in this tutorial with that of the Creek Fire perimeter and the SOAP flight boundary.
Calculate and compare the relative height percentiles of the discrete returns before and after the 2020 Creek Fire.
