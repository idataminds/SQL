
# SQL Multi-Layer Architecture with Streamlit Insights

## Project Overview

This project demonstrates a **multi-layer SQL architecture** integrated with a **Streamlit** app to provide real-time insights and analytics. The architecture follows the **Bronze**, **Silver**, and **Gold** layer structure for efficient data handling and transformation. The **Streamlit** app allows users to visualize and interact with the data through a web-based interface.

## Project Structure

. ├── pages/ │ ├── analytics.py # Contains analytics and insights logic │ ├── documentation.py # Documentation and app description page │ ├── visualize.py # Visualization logic for the Streamlit app ├── Readme # Project documentation ├── create.py # Script for creating Bronze, Silver, and Gold layers ├── layers.png # Diagram of the architecture ├── load.py # Script to load data into the layers ├── main.py # Entry point for the Streamlit app ├── query.py # SQL queries for extracting data from the Gold Layer ├── requirements.txt # Dependencies for running the project




## Architecture Layers

- **Bronze Layer:**
  - Stores raw data ingested from various sources.
  - Data is stored in its original format, ensuring no loss of detail.
  
- **Silver Layer:**
  - Processes the raw data by cleaning, transforming, and standardizing it.
  - Prepares the data for analysis by removing duplicates, handling missing values, and applying necessary transformations.

- **Gold Layer:**
  - Final layer for analytics and reporting.
  - Clean, aggregated data is stored for querying insights and generating reports.

## Streamlit App Overview

The **Streamlit** app is used to interact with the data stored in the **Gold Layer** and provides the following features:

- **Data Analytics:** (via `analytics.py`)
  - Generate insights based on key performance indicators (KPIs).
  - Perform comparative analyses between different data points.
  
- **Visualization:** (via `visualize.py`)
  - Visualize trends and patterns in the data using charts and graphs.

- **Documentation:** (via `documentation.py`)
  - Provides an overview and documentation for using the app.

## Setup Instructions

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/surajraghuwanshi05/SQL.git
