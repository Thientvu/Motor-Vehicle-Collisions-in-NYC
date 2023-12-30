# Motor Vehicle Collisions in NYC - Streamlit Dashboard

## Overview

This Streamlit dashboard provides an interactive analysis of motor vehicle collisions in New York City. It leverages various visualization tools to help users explore and understand patterns in collision data.

## Features

1. **Map of Injuries:**
   - Explore locations with the highest number of injured persons by adjusting the slider.
   - The map dynamically updates based on the selected number of injured persons.

2. **Collisions by Time of Day:**
   - Analyze the distribution of collisions during a specific hour of the day.
   - Visualize the data using a hexagonal map layer.

3. **Minute-by-Minute Breakdown:**
   - Investigate minute-by-minute breakdowns of collisions during the selected hour.
   - A bar chart provides insights into collision frequency throughout the hour.

4. **Top Dangerous Streets:**
   - Identify the top 5 dangerous streets based on the type of affected individuals (Pedestrians, Cyclists, Motorists).
   - Filter and explore detailed information about collisions on these streets.

5. **Raw Data Display:**
   - Optionally view the raw data used for analysis by toggling the "Show Raw Data" checkbox.

## Dependencies

- Streamlit
- Pandas
- NumPy
- PyDeck
- Plotly Express
