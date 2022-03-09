# Creating_typical_weather_data_from_EUROCORDEX
A set of scripts to download yearly weather data from EUROCORDEX website for any location in EUROPE, and Transforming yearly data into a typical year 

# Downloading and Creating Typical weather file from EURO-CORDEX climate data repository is explained in three steps using three ipynp files here.

 1- A function to transform rlat/rlon to lat/lon and vice versa: this step is necessary because some of EURO-CORDEX files are projected on rlat/rlon coordinates system 
 
 2- Using the transformed coordinate, find the closest grid point in NETCDF file to the target coordinate location and extract climate variables for each year 
 
 3- After downloading 20 to 30 years of weather data, they are assumbled to generate a typical weather file 
 
 Each step is processed in one of the ipynp scripts 
