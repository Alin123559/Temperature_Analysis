# NOAA Temperature Data Analysis

## Overview

This repository contains the analysis of NOAA temperature data near Ann Arbor, Michigan, spanning from 2005 to 2015. The analysis includes:

1. Visualization of record high and low temperatures from 2005-2014.
2. Identification and visualization of record-breaking temperatures in 2015.
3. Mapping of data collection stations near Ann Arbor.
4. Summary of temperature trends for 2015.

## Files

- `temperature(1)(1)(1).csv`: Temperature data with columns `ID`, `Date`, `Element`, `Data_Value`.
- `BinSize(1)(1)(1).csv`: Station data containing geographical coordinates.
- `Temperature_Analysis.ipynb`: Jupyter Notebook containing the analysis and visualizations.
- `station_map.html`: Interactive map of data collection stations.
- `README.md`: This documentation.

## Requirements

Ensure you have the following Python libraries installed:

- pandas
- matplotlib
- folium

You can install the required libraries using:

```bash
pip install pandas matplotlib folium
