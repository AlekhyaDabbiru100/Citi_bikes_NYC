# Citi Bike Usage Across NYC (2023)

## Overview
This project analyzes **Citi Bike trip data across New York City for the full year of 2023**. The goal is to understand how people use the bike-share system across time, rider type, bike type, and geography. Citi Bike, operated by Lyft, is one of the largest bike-share systems in the United States, serving areas including Manhattan, Brooklyn, Queens, the Bronx, and Jersey City.

This analysis uses **trip-level ride history data from all 12 months of 2023**, merged into a single dataset to explore citywide cycling patterns.

## Project Questions
This project focuses on three main questions:

1. **What words appear most often in NYC bike station and trip data?**
2. **When do New Yorkers ride the most, and how do bike type, rider type, and distance influence ride patterns?**
3. **How does geography shape where and how often people ride?**

These questions were chosen to better understand **where people ride, when they ride, and how trip behavior changes across different types of users and locations**.

## Dataset
The dataset consists of **Citi Bike trip history records from all 12 months of 2023** combined into one unified table.

Example fields include:
- Ride ID
- Rideable type
- Rider status
- Start station
- End station
- Duration
- Distance
- Date/time

This year-long dataset makes it possible to study seasonal, geographic, and behavioral trends across the full Citi Bike network.

## Analysis Highlights

### 1. Station Word Cloud
A word cloud was created from station names to identify the most common location-related terms in the system.

Some of the most frequent words include:
- **Broadway**
- **Park**
- **Washington**

This helps reveal the streets, neighborhoods, and landmarks that appear most often in station names, highlighting where stations are concentrated.

### 2. Ride Characteristics
The project compares ride behavior across:
- **Bike type** (classic vs. electric)
- **Rider type** (member vs. casual)

Key patterns include:
- **E-bikes support longer and faster trips**
- **Casual riders go farther on electric bikes than on classic bikes**
- **Members appear to benefit most from the speed advantage of e-bikes**
- This may suggest that **e-bikes are especially useful for commute-style or time-sensitive trips**

### 3. Interactive Geographic View
An interactive map was used to visualize:
- Ride starting and ending patterns
- Hotspots across the city
- Differences by bike type, rider type, duration, and month

The map supports both detailed point views and clustered views, making it easier to compare neighborhoods and identify areas of heavier usage.

## Key Findings
The project finds that Citi Bike ridership shows strong:
- **Seasonal variation**, with higher usage in warmer months
- **Geographic variation**, especially in dense areas like **Manhattan and Brooklyn**
- **Behavioral differences** between rider groups

In general:
- **Members** tend to take **shorter, more frequent trips**
- **Casual riders** appear more associated with longer or recreational use

## Future Directions
Possible next steps for the project include adding external data sources such as:
- **Weather data** (temperature, precipitation, wind)
- **Subway disruptions**
- **Major city events** such as street closures, concerts, or parades

These additions could improve the explanation of seasonal changes and unusual ridership patterns.
