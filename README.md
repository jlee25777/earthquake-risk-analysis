# Shaky Grounds: Earthquake Insights for Home Relocation Decisions

## Overview
A data analysis project using USGS earthquake data to identify regions most 
susceptible to seismic activity, providing actionable insights for homeowners 
making relocation decisions.

## Published Analysis
Read the full data story on Medium: [Shaky Grounds: Earthquake Insights for 
Home Relocation Decisions](https://medium.com/@jennifergawon/shaky-grounds-earthquake-insights-for-home-relocation-decisions-5256f64143ec)

## Data Source
USGS Earthquake API — 9,750 earthquakes recorded from 2013 to 2023

## Tech Stack
- Python
- Pandas
- Matplotlib
- scikit-learn (K-Means Clustering)
- Google Colab

## My Contributions
- K-Means clustering analysis for earthquake magnitudes using the Elbow Method
- Identified three magnitude clusters and analyzed their distributions
- Contributed to data cleaning and dataset selection
- Wrote the key course concepts section connecting analysis to coursework
- Authored the limitations section
- Co-contributed to overall data analysis and findings

## Analysis Approach
1. Pulled earthquake data from the USGS API
2. Cleaned dataset and handled null values
3. Applied min-max normalization to handle outliers
4. Used the Elbow Method to determine optimal k value (k=3)
5. Applied K-Means clustering to group earthquakes by magnitude
6. Applied K-Means clustering by magnitude, latitude, and longitude
7. Identified highest magnitude earthquakes within each cluster

## Key Findings
- Three magnitude clusters identified with mean magnitudes of 4.5, 1.9, and 0.7
- Areas near the Philippine Sea and South Pacific Ocean showed the highest 
  magnitude earthquakes
- Top 10 earthquakes by magnitude concentrated in the Philippines and 
  Papua New Guinea
- Homeowners advised to avoid Pacific Oceanic island regions due to consistent 
  high-severity seismic activity

## Note
This was a collaborative academic project. Contributions are noted above.
