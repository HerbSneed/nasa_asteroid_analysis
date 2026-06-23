# NASA Near-Earth Asteroid Analysis

## Overview

This project collects and analyzes Near-Earth Object (NEO) data from NASA's API. The data is cleaned, stored in a SQLite database, queried with SQL, and visualized using Python and Plotly.

## Objectives

- Retrieve asteroid close-approach data from NASA.
- Clean and transform the dataset using Pandas.
- Store the data in a SQLite database.
- Analyze asteroid characteristics with SQL.
- Create visualizations to identify trends and potential hazards.

## Technologies Used

- Python
- Pandas
- SQLite
- SQL
- Plotly
- Jupyter Notebook

## Data Source

Data was obtained from the NASA Near-Earth Object API.

## Analysis Performed

- Asteroids approaching Earth within the next seven days
- Potentially hazardous asteroids
- Top 10 closest asteroid approaches
- Largest asteroids by maximum diameter
- Average miss distance by hazardous classification
- Average maximum and minimum diameter

## Visualizations

- Relationship between asteroid size and miss distance
- Distribution of asteroid sizes
- Hazardous vs. non-hazardous asteroids
- Asteroid close approach timeline (next 3 days)

## Key Findings

- Most asteroids were not classified as hazardous.
- The closest asteroid, **1997 NC1**, approaches Earth on **2026-06-27** at **1594339.75** miles.  		
- The largest asteroid, **1997 NC1**, has an estimated maximum diameter of **5200.26** feet.

## Project Structure

├── asteroid_analysis.ipynb  
├── asteroid_data.csv  
├── asteroid_database.db  
├── README.md  

## Future Improvements

- Automate daily data collection.
- Store historical asteroid data.
- Build an interactive dashboard.
- Deploy visualizations to a web application.

## Author

Herb Sneed

