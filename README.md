<div align="center">

# Bikeshare Network Project: SF Bay Area

</div></div> 

## Project Overview

This project leverages machine learning to predict loan payment statuses accurately. By doing so, it offers lending institutions enhanced risk assessment, decision-making processes, and the potential to minimize financial losses.

## Dataset

The dataset comes from **kaggle**, which is the world's largest data science community. 
This dataset contains information about the location of bike stations, including the coordinates of the stations and the available number of docks. The dataset also includes the status of each bike station, including the number of available bikes and docks at a specific time. It can be used to analyze station accessibility and demand. The individual bike trips data could help us understand commuting patterns and trip durations. The weather data provides temperature and humidity
information for specific zip codes on a specific day.

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

weather.csv : Data about the weather on a specific day for certain zip codes
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
