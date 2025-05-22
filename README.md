# Weather and Vacation Analysis with Python APIs
**Creator**: Angelina Murdock  
**Date**: February 2025

## Overview 
This project uses ***Python**, **APIs**, and data visualization tools to analyze weather patterns across hundreds of cities and assist in vacation planning. By retrieving real-time weather data from the OpenWeatherMap API and integrating **Geoapify** for location-based services, this project explores relationships between weather variables and geographic coordinates, then narrows down ideal vacation spots based on personalized climate criteria.

## Table of contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Resources](#resources)

## Features
**WeatherPy:**
- Collected and analyzed weather data to create scatter plots for latitude vs. temperature, humidity, cloudiness, and wind speed.
- Computed linear regression for each weather variable by hemisphere to reveal trends, such as temperature decreasing with distance from the equator.

**VacationPy:**
- Used filtered weather data to identify ideal vacation cities.
- Mapped selected cities and nearby hotels using the Geoapify API with hvplot for interactive visualizations.

## Installation
### Requirements
- Python 3.7 or later
- Jupyter Notebook
- Pandas, Matplotlib, NumPy, SciPy, Citipy, Requests, hvPlot, GeoViews

### Setup
1. Clone or download the repository from GitHub:
    ``` bash
    git clone https://github.com/Angelinamurdock/python-api-challenge.git
    ```
2. Create an `api_keys.py` file in the project directory and add your API keys in this format:
    ```
    # OpenWeatherMap API Key  
    weather_api_key = "YOUR_OPENWEATHERMAP_API_KEY"  

    # Geoapify API Key  
    geoapify_key = "YOUR_GEOAPIFY_API_KEY"  
    ```
3. **Important:** Do not share your API keys publicly. Add api_keys.py to your .gitignore file to keep them private.
4. Open the Jupyter Notebooks `VacationPy_final.ipynb` and `WeatherPy_final.ipynb` in your preferred environment. 
5. Run all cells in sequence to reproduce the analysis and visualizations.

## Resources
- **DU Bootcamp Module 6:** Used challenge files and class materials from the bootcamp.
- **ChatGPT:** Assisted with code explanations and debugging.