## Global-temperature-sea-level-project
Global Temperature and Sea Level Change Since 1993

## Group Members
* Yaojun Du
* Lingfeng Deng

## Project Title
Global Temperature and Sea Level Change Since 1993

## Research Question
How have global temperature anomalies and global mean sea level changed since 1993, and do these two climate indicators show similar long-term trends?

## Datasets
We plan to use two public climate datasets from NOAA.
1. NOAA Global Temperature Anomaly Data
    Dataset source: NOAA Climate at a Glance / NOAAGlobalTemp
    Link: https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land_ocean/tavg/1/1/1993-2026
    This dataset provides global temperature anomaly time series that can be used to analyze long-term temperature change.
2. NOAA Global Mean Sea Level Time Series
    Dataset source: NOAA / NESDIS Global Mean Sea Level Time Series
    Link: https://www.star.nesdis.noaa.gov/socd/lsa/SeaLevelRise/LSA_SLR_timeseries.php
    This dataset provides global mean sea level time series that can be used to analyze long-term sea level rise.

## Three-Sentence Project Summary
This project will analyze how global temperature anomalies and global mean sea level have changed since 1993. We will use Pandas to load, clean, filter, aggregate, and visualize the two datasets, focusing on annual trends and long-term changes. The final analysis will compare the direction and timing of temperature anomaly changes and sea level rise to investigate whether these two climate indicators show a clear relationship over time.

## Planned Division of Work
Notebook 1: Global Temperature Anomaly Analysis
Yaojun Du will analyze NOAA global temperature anomaly data. This notebook will calculate annual temperature anomalies, identify the warmest years, and create visualizations showing the long-term warming trend.

Notebook 2: Global Mean Sea Level Analysis
Lingfeng Deng will analyze NOAA global mean sea level data. This notebook will calculate annual sea level averages, visualize the long-term sea level rise trend, and compare sea level change with global temperature anomalies.

## Planned Figures
Each notebook will contain 3 to 5 well-formatted figures.

## Possible figures include:
* Annual global temperature anomaly over time
* Rolling average of global temperature anomaly
* Top 10 warmest years
* Global mean sea level over time
* Annual sea level change
* Scatter plot comparing temperature anomaly and sea level

## Tools
We plan to use JupyterLab on Leap Pangeo Hub to write and run our notebooks. The project repository will be stored on GitHub as a public repo. For the analysis, we plan to use Python, Pandas, NumPy, and Matplotlib to load, clean, analyze, and visualize the datasets.

## Data Access
All data will either be loaded directly from public dataset URLs inside the notebooks or clearly documented in the repository. No manual download steps will be required.
