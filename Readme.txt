

 *** Understanding drivers of Singapore HDB Resale Price ***


This project was done for a Singapore Proptech that was looking to understand the influence of various factors on Singapore HDB Resale Price. The factors that were explored for this project ranged from static housing data like the numbers of floors in the high rise, location of HDB etc. to CPI rates, distance from amenities and infrastructure points like primary schools, hawker centres and MRT stations. 

Multiple datasets were used for this project. Most were sourced from publicly available government databased. To calculate distance from amenities, custom datasets were built using the GoogleMaps API. 

The files and folders used in this projectare as follows:

- HDB Resale Price Drivers.ipynb: This is the main script which contains code for data pre-processing, statistical analysis and machine learning models.

- Lat-Long Extraction.ipynb: This was the script used to extract geo-spatial data for the various amenities from GoogleMaps API.

- resale-flat-prices (Folder): This folder contains the primary file which has Resale prices for various HDB flats.

- consumer-price-index-base-year-2014-100-monthly.csv: Contains CPI data

- hawker_centre_location.csv: Contains geo-spatial data (latitudes and longitudes) for hawker centres.

- hdb_blocks_location.csv: Contains geo-spatial data (latitudes and longitudes) for hdb blocks.  

- hdb-property-information.csv: Contains static housing information about various HDB's.

- mrt_location.csv: Contains geo-spatial data (latitudes and longitudes) for mrt stations.

- primary_schools_data.csv: Contains geo-spatial data (latitudes and longitudes) for primary schools.
