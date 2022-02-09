# Surfs Up Analysis

## Overview

The purpose of the analysis is to learn how to utilize SQLite, SQLAlchemy, and Flask.

Below is a list of dependencies used: 

![image](https://user-images.githubusercontent.com/90485451/153123247-b6611dcc-bdc0-49e0-91a2-e42f10638e82.png)


### Purpose

The purpose of this project is to analyze precipitation levels and weather that supports the idea that Oahu is the best place to open a surf shop since the weather is most favorable for surfing. We were given 12 months of data to work with starting with June 23, 2017. W. Avy wants to have more information about temperature trends (June - December) before opening his surf shop.

## Results

The first thing that was looked at in this analysis was the precipitation for a one year timefrrame, in order to get an idea of what the year looks like. Precipitation from August 23, 2016 - August 23, 2017 were plotted and a table was created to show some calculations using df.describe(). The plot below shows that Oahu was mostly sunny and experience low precipitation.

![image](https://user-images.githubusercontent.com/90485451/153285369-f66cb3eb-ad0f-4522-a1dd-b0be0a743378.png)

    
 ### Comparing June and December weather statistics
 
 Below is a summary of statistics calculated with June and December weather data.
 
    
   ![image](https://user-images.githubusercontent.com/90485451/153123328-c259c63a-8877-4186-a55a-cd36a7a871f2.png)    ![image](https://user-images.githubusercontent.com/90485451/153123393-62b6be7f-ce18-48e0-83d7-ef7a353a3fcf.png)


    - There was only a slight difference in mean temperatures between June with 74 degrees celsius and December with 71 degree Celsius.
    - Min and Max temperatures were also very similar.
    - The weather doesn't seem to change as the months go by which is a benefit for surfers and surf shops.
    - Comparing these numbers with the December 2016 - June 2017 precipitation plot - the amount of rain also seems to be the lowest.
    

## Summary

The weather and precipitation between the months of June and December are favorable for opening a surf shop. Additional statistics is always helpful. Below are some suggestions:

    - Using df.describe() to get summary statistics for precipitation between June and December of 2017
    - It would also be helpful to see a multi line plot of each sets of data: June precipitation/December precipitation vs June weather/December weather.
