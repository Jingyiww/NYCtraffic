# NYC_Traffic

This repository contains two projects: commute.zip and bus_route.zip.

The commute.zip includes a Python script and the corresponding dataset that visualizes the commuting data of New York City residents in 2021, allowing users to view the commuting flow between different neighborhoods on a map.

The bus_route.zip contains a Python script and the corresponding dataset that visualizes the bus data of New York City in 2022, enabling users to see the changes in bus ridership throughout different time periods of a day.

## Commute:

Dataset:

Dataset download link: https://lehd.ces.census.gov/data/ (included in commute.zip, and named as ny_od_main_JT00_2021.csv.gz）

There are other datasets in the file: uszips.csv (zipcode and corresponding geographic information), 2020_Neighborhood_Tabulation_Areas__NTAs__20240728 (Neighborhood boundary geographic information).

Script Overview:

1. Load the dataset of the year 2021.
2. Group the  dataset to calculate the total number of commuters between each neighborhoods.
3. Create an HTML file to visualize the number of commuters between neighborhoods on the map.


## Bus_route:

Dataset:

Dataset download link: https://data.ny.gov/Transportation/MTA-Bus-Hourly-Ridership-Beginning-February-2022/kv7t-n8in/about_data (included in commute.zip, and named as MTA_Bus_Hourly_Ridership__Beginning_February_2022_20240831)

There are other datasets in the file: gtfs_m（Bus route geographic data）

Script Overview:

1. Load the dataset of the year 2022.
2. Group the data by time and bus routes, and compute the average ridership for each hour.
3. Create an HTML file to visualize the ridership of each bus route on the map.


## Run the script：

Download the data in the zip file and run the Python script directly.
