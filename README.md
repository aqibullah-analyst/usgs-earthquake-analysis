# USGS Earthquake Data Analysis

A Python-based data pipeline designed to fetch, parse, and analyze real-time global seismic data using the United States Geological Survey (USGS) API.

## Features

- **Real-Time Data Ingestion:** Connects directly to the live USGS GeoJSON feed.
- **Nested JSON Parsing:** Converts complex, hierarchical API structures into clean, flat Pandas DataFrames.
- **Geospatial & Magnitude Extraction:** Extracts key variables including magnitude, location, timestamp, coordinates, and depth.

## Tech Stack

- **Language:** Python 3.8+
- **Libraries:** `pandas`, `requests`
- **Environment:** Jupyter Notebook

## How to Run

1. Install required packages:
   ```bash
   pip install pandas requests
