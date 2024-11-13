# IndeGo BikeShare Analysis Project

**By:** Michael Harkness

## Project Overview

The IndeGo BikeShare project analyzes the usage patterns of Philadelphia's public bike-sharing program, IndeGo. This program provides residents and visitors with an eco-friendly transportation option that promotes accessibility and mobility throughout the city. The goal of this project is to gain insights into station usage, peak times, and seasonal trends in bike-sharing usage.

## Data Source

The data used in this project comes from the IndeGo BikeShare program and represents bike trip data for the year 2023. Key data points include:
- Trip ID
- Duration of the trip
- Start and end times
- Start and end station locations (latitude, longitude)
- Passholder types
- Bike and trip route categories

## Project Goals

1. **Identify Popular and Least Popular Stations:** Determine which stations have the highest and lowest usage.
2. **Analyze Geographic Patterns:** Visualize bike station locations and usage density across Philadelphia to understand popular areas for bike usage.
3. **Examine Usage by Time of Day and Season:** Explore trends in bike usage during different times of day and seasons, highlighting commuter patterns and recreational usage.
4. **Cluster Analysis of Trips:** Group trips based on their characteristics to find patterns in ride type and seasonality.

## Dashboard

An interactive Tableau dashboard has been created to visualize the results of the analysis. Key views in the dashboard include:
- **Map of Starting Stations:** Each dot represents a starting station, with color intensity showing the number of rides originating from that station.
- **Popular Stations:** Visualization of the most popular stations.
- **Seasonal and Time-Based Trends:** Charts showing bike usage patterns during different times of the day and across seasons.
- **Clustered Trip Analysis:** Insights from clustering trips into categories such as commuter, recreational, and seasonal usage patterns.

You can view the dashboard on [Tableau Public](https://public.tableau.com/app/profile/michael.harkness3226/viz/6_7Dashboard-MichaelHarkness/IndeGoBikeShare?publish=yes).

## Key Insights

- **Center City, University City, and Art Museum** areas show high bike usage, indicating popular areas for both commuting and recreational trips.
- **Morning and Evening Commute Peaks:** There are clear peaks in bike usage during commuting hours (8am and 5pm).
- **Seasonal Variation:** Summer and Fall months show the highest bike usage.

## Project Structure

- **notebooks/**: Jupyter notebooks used for data processing, exploration, and analysis.
- **scripts/**: Python scripts for data cleaning, transformation, and visualization.
- **dashboard/**: Tableau workbook files for creating the visualizations in the dashboard.
- **README.md**: This file, providing an overview of the project.
- **data/**: Data files available upon request, as they exceed GitHub's 100MB file limit.
