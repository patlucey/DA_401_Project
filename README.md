# DA_401_Project
# About the Author
Email: lucey_p1@denison.edu

Current senior at Denison University 
# Project Question
How is the migration of Canadian Geese and Red Throated Loons affected by urbanization in different cities?

## Description 
Will look into the connection of bird migration and how it is impacted by different levels of urbanization in various cities. Also, it will take into account factors like noise pollution. 
## Features

- Displays visualization of bird migration trends in various cities 
- Uses sf and gbalraster to display visuals
- Includes Validated Linear Regression models that equate the Latitudinal position of each different species in regards to the Urbanization level, Date and Longitude of each different bird.

## Data Description / Key variables
To access these files in R-Studio they require the use of the sf and terra packages to access the .tif files. In order to access the CSV files use the readr package that comes with R.
Raster data files:
- rasterwgs84.tif
- noise2.tif
- rastergoodes.tif


CSV files:
- duck_data.csv
- goose.csv

Key Variables(Raster data):
Latitude: Coordinate point for the latitudinal location of the point in the map.
Longitude: Coordinate point for the longitudinal location of the in the map.
Urban_prob: The associated value for urbanizational proability 

Key Variables(Migration data):
Latitude: Coordinate point for the latitudinal location of the point in the map.
Longitude: Coordinate point for the longitudinal location of the in the map.
Date: Date of recording
individual-local-identifier: The tag for each different tracked bird
sensor-type: States what type of sensor was used



