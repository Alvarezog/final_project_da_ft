# final_project_da_ft

## Introduction

This is a project that uses hte criminality data from Mexico City and creates clusters to identify the optimal number of "clusters" for a drone swarm first response sistem. For more information about the concept of this system please see the following presentation:

https://www.slideshare.net/OscarAlvarez186/red-seguridad-drones

## Workflow

1 - `Data_exploration.ipynb` - This notebook goes through the structure of the database providing information about which data is relevant to this analysis.
2 - `Data_cleaning.ipynb` - Clean the data and prepare it for the clustering algorithms.
3 - `Clustering_kmeans.ipynb` - Cluster the data using kmeans algorithm.
4 - `Clustering_kmedians.ipynb` - Cluster the data using kmedians algorithm.
5 - `Clustering_fcm.ipynb` - Cluster the data using fuzzy c means algorithm.
6 - `Nearby_search_police_stations.ipynb` - Uses google maps api nearby seach module to locate police stations.
7 - `Centroid_adjustment_and_calculations.ipynb` - Adjust the centroids to the closer police station, calculates response times and plots the results.
8 - `Plotting_Folium.ipynb` - Plots the location of each centroid(drone base) on a map.