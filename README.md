# Household Data Analysis Dashboard

This Streamlit application provides an interactive dashboard for analyzing household data from various regions in India. The dashboard includes data filtering, bar charts, scatter plots, and geographic visualization capabilities.

## Features

- **Data Selection**: Choose between different household datasets (Gosaba 1, Gosaba 2, and Pathar)
- **Data Filtering**: Filter data based on categorical columns
- **Bar Chart Analysis**: Create bar charts to analyze relationships between categorical and numeric variables
- **Scatter Plot Analysis**: Visualize relationships between numeric variables
- **Geographic Analysis**: Interactive map visualization with color-coded data points

## Installation

1. Clone this repository:
```bash
git clone https://github.com/akvo/oak-india.git
cd oak-india
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Running the App

To run the application, use the following command:
```bash
streamlit run app.py
```

The app will open in your default web browser at `http://localhost:8501`.

## Usage

1. **Data Selection**: Use the sidebar to select the dataset you want to analyze
2. **Data Filter**: Use the "Data Filter" tab to filter data based on categorical columns
3. **Bar Chart**: Create bar charts by selecting categorical and numeric columns
4. **Scatter Plot**: Create scatter plots by selecting numeric columns for X and Y axes
5. **Map**: Visualize data geographically by selecting a column to color-code the points

## Data Sources

The application uses data from the following sources:
- Household data from Gosaba 1
- Household data from Gosaba 2
- Household data from Pathar
- Village boundaries GeoJSON data

All data is loaded directly from the GitHub repository.

## Requirements

See `requirements.txt` for a complete list of dependencies.