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
  - Max Temperature
  - mean Temperature
  - Min Temperature
  - Max Dew Point
  - Mean Dew Point
  - Min Dew Point
  - Max Humidity
  - Mean Humidity
  - Min Humidity

## Project Workflow

### Data Cleaning
We started by handling inconsistencies and missing values in our dataset before using it for modeling. In addition, we identified the columns and features suitable for our model while eliminating any redundancies.

### Exploratory Data Analysis (EDA)
EDA helped understand feature distributions and relationships with loan status, thus informing model choice and guiding feature engineering.

### Feature Engineering


### Modeling



## Findings and Conclusions
