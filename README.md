# Citi_Bike_Saftey
An analysis of Citi Bike ridership trends and NYC bike accident data


## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Resources](#resources)

## General info
This project uses data from Citi Bike and the NYC's Vision Zero crash data to examine Citi Bike's impact upon NYC bike saftey and overall trends in both data sets. CSV data was combined using Python's glob module, loaded into and cleaned with pandas. The uszipcode module was used to reverse geocode zip codes from accident and Citi Bike stations lat/lng data. These cleaned datasets were loaded into Tableau for analysis and visualization. The final visualization and analysis is available on https://public.tableau.com/views/Bikes_15794530482770/Story1?:retry=yes&:display_count=y&:origin=viz_share_link

Note that the csv's for the Trip_Data files and "Motor_Vehicle_Collisions" were not uploaded to Git Hub remote given the large file size. 
Citi Bike Trip Data: https://s3.amazonaws.com/tripdata/index.html
NYC Crash Data: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95

## Technologies

### Languages Used

* Python

### Data Extraction, Cleaning and Reverse Geo-coding

* Jupyter notebook - version 4.1
* Python - version 3.7.3
* Pandas - version 0.23.4
* Numpy - version 1.15.4
* Glob 
* uszipcode - version 0.2.4 

### Data Rendering and Visualization

* Tableau Public - version 2019.4

## Resources

*[Citi Bike Data] (https://www.citibikenyc.com/system-data)
*[NYC Crash Data] (https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
*[Tableau Public] (https://public.tableau.com/en-us/s/download)
*[Tableau Visualizations] (https://public.tableau.com/views/Bikes_15794530482770/Story1?:retry=yes&:display_count=y&:origin=viz_share_link)
