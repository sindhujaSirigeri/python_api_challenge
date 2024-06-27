# Python API Challenge Summary

## Background

Explore the relationship between weather variables and latitude using Python requests, APIs, and JSON traversals. The goal was to analyze over 500 cities across different latitudes to understand how weather changes as we approach the equator.

## Setup

1.  Created a repository named `python-api-challenge`.
2.  Cloned the repository locally and organized files into a directory structure.
3.  Implemented a `.gitignore` file to protect API keys from exposure on GitHub.

## Part 1: WeatherPy

### Requirement 1: Visualize Weather Variables

Used OpenWeatherMap API and citipy library to gather weather data for cities generated randomly across the globe. Created scatter plots to visualize:

-   Latitude vs. Temperature
-   Latitude vs. Humidity
-   Latitude vs. Cloudiness
-   Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression

Performed linear regression analysis on weather variables for both Northern and Southern Hemispheres. Plotted scatter plots with regression lines to analyze relationships between latitude and weather variables.

## Part 2: VacationPy

Utilized Geoapify API and geoViews library to plan vacation destinations based on weather preferences derived from WeatherPy data. Created maps to display cities meeting specified weather conditions:

-   Low temperature range
-   Low wind speed
-   Clear skies

Generated a DataFrame (`hotel_df`) to display hotels near selected cities, enhancing map interactivity with hotel information.

## Skills Acquired

-   Python requests and API integration
-   Data visualization with scatter plots and maps
-   JSON data handling and traversal
-   Linear regression analysis
-   Geographic plotting and mapping techniques

