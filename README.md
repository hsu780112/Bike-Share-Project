<div align="center">

# Bikeshare Network Project: SF Bay Area

</div></div> 

## Project Overview
This project utilizes machine learning to enhance the efficiency and accessibility of the bike share system in the SF Bay Area. By predicting usage patterns for specific time periods, we can optimize bike availability through strategic redistribution, ensuring they are accessible where and when they are most needed. This approach aims to improve the user experience and promote increased bike share usage.


## Dataset

The dataset comes from **kaggle**, which is the world's largest data science community. 
This dataset contains information about the location of bike stations, including the coordinates of the stations and the available number of docks. The dataset also includes the status of each bike station, including the number of available bikes and docks at a specific time. It can be used to analyze station accessibility and demand. The individual bike trips data could help us understand commuting patterns and trip durations. The weather data provides temperature and humidity
information for the area on a specific day.

Reference: https://www.kaggle.com/datasets/benhamner/sf-bay-area-bike-share/code

station.csv : Contains data that represents a station where users can pickup or return bikes.
  - ID
  - Latitude
  - longitude
  - Dock Number
  - City
  - Installation Date

status.csv : data about the number of bikes and docks available for given station and minute.
  - Station ID
  - Number of Available Bikes
  - Number of Available Dock
  - Recorded TIme

trips.csv : Data about individual bike trips
  - ID
  - Duration
  - Start Date
  - Start Station Name
  - Start Station ID
  - End Date
  - End Station ID
  - End Station Name
  - Bike ID

weather.csv : Data about the weather on a specific day for the area
  - Date
  - Max_temperature_f                    
  - Mean_temperature_f                   
  - Min_temperature_f                    
  - Max_dew_point_f                     
  - Mean_dew_point_f                    
  - Min_dew_point_f                     
  - Max_humidity                        
  - Mean_humidity                       
  - Min_humidity                        
  - Max_sea_level_pressure_inches        
  - Mean_sea_level_pressure_inches       
  - Min_sea_level_pressure_inches       
  - Max_visibility_miles                
  - Mean_visibility_miles               
  - Min_visibility_miles                
  - Max_wind_Speed_mph                   
  - Mean_wind_speed_mph                 
  - Max_gust_speed_mph                 
  - Precipitation_inches                 
  - Cloud_cover                          
  - Events                            
  - Wind_dir_degrees                     
  - Zip_code     

## Project Workflow

### Data Cleaning
We began by addressing inconsistencies and missing values in our dataset to ensure its suitability for modeling purposes. Furthermore, we identified relevant columns and features for our model, eliminating redundancies. We also created new columns and categorized the results to facilitate our analysis.

### Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) was instrumental in our understanding of the main characteristics of the data, particularly its distribution. Through EDA, we were able to uncover patterns and relationships related to bike station usage status. These insights informed our choice of models and guided our feature engineering process.

### Feature Engineering
We applied one-hot encoding to the existing data, converting categorical variables into a format that is more conducive to machine learning algorithms.


### Modeling
Logistics Regression


## Findings and Conclusions
(under construction)
