# SPEI Data Download and Extraction Guide

This repository provides scripts and instructions for downloading SPEI (Standardized Precipitation-Evapotranspiration Index) climate data for 12, 24, and 48 months and efficiently extracting 3,016 data points from the NetCDF files.
Downloading SPEI Data
Follow the steps below to download the SPEI data for 12, 24, and 48 months:

Access the SPEI Database:

Visit the official SPEI website  https://spei.csic.es/spei_database/#map_name=spei48#map_position=1463.
Select Data Parameters:

Choose the SPEI index for 12, 24, and 48 months.
Select the geographical region and time period as per your requirement.
Download the data in NetCDF format.
Download:

Save the downloaded NetCDF files in a directory of your choice, e.g., data/.

Extracting Data from NetCDF Files
Use the script provided in this repository to extract 3,016 data points efficiently from the NetCDF files. The extraction process uses the xarray library to handle large NetCDF files.

Steps to Extract Data:
Prepare a list of coordinates: Create a list of tuples containing the latitude and longitude of the 3,016 points you want to extract.
Run the script:
Modify the script with the correct file paths and coordinates.
Run the script to extract the data.
