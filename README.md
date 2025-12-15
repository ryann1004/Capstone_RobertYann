# Capstone_RobertYann

# Missing Persons in US National Forests
This project starts exploring geographical location similarities between Missing Persons in the US National Forest, bigfoot, dogman, and ufo sightings as well as US cave systems in the United States. This capstone project demonstrates data cleaning, data wrangling, exploratory analysis, visualization and Sqlite3 for building a database and running queries. 

## Table of Contents
- [Prerequisites](#prerequisites)
- [Acknowledgements]
- [Setup Instructions](#setup-instructions)
- [Database Setup](#database-setup)
- [Activating and Deactivating the Virtual Environment](#activating-and-deactivating-the-virtual-environment)
- [Running the Project](#running-the-project)
- [License](#license)

## Requirements
Ensure the following are installed on your computer
-  **Python3.6 or higher**
-  **Pip/Pip3**
-  **SQLite3**
-  **pandas as pd**
-  **matplotlib.pyplot as plt**
-  **seaborn**
-  **requests**
-  **geopandas as gpd**
-  **shapely.geometry import LineString**
-  **numpy as np**
-  **geodatasets**
-  **plotly.express as px**
-  **geopy.geocoders import Nominatim**
-  **geopy.extra.rate_limiter import RateLimiter**

## Installation
1. Clone this repository from Github
2. Set up Virtual Environment
Windows
    1. Create: python -m venv venv 
    2. Activate: venv\Scripts\activate
    3. Deactivate: deactivate 
macOS and Linus
    1. Create: python -m venv venv
    2. Activate: python3 -m venv venv
    3. Deactivate: deactivate
2. Install the required Python packages using the requireements.txt:
    pip install -r requirements.txt
3. Open 'Capstone_RY.ipynb' in VS Code or other appropriate IDE
    Windows: python Capstone_RY.py
    macOS and Linux: python3 Capstone_RY.py
    Jupyter Notebook: jupyter notebook

## Summary of observations and conclusions from the main questions queried

## Acknowledgements
This project would not have been possible without several tools, frameworks, and external resources that are listed below. 

### Tools and Frameworks
- **Python**: The primary programming language used for data analysis and visualization.
- **Pandas**: A powerful data manipulation library that facilitated data cleaning and analysis.
- **NumPy**: Useful for numerical operations and handling arrays effectively.
- **SQLite3**: A lightweight database engine used to store and manage data efficiently.
- **Matplotlib**: A plotting library for creating static, animated, and interactive visualizations in Python.
- **Seaborn**: Built on top of Matplotlib, it provides a high-level interface for drawing attractive statistical graphics.
- **Jupyter Notebook**: An interactive environment for running Python code and documenting the analysis process step by step.

### AI Tools and Assistance
- **Duck.ai**: Leveraged for code generation, debugging suggestions, and enhancing documentation. It helped in generating code that was not covered in the Code You Data Analysis class. Specific examples include needing to import Regular Expressions (Regex) in order to change the gps coordinate format from DMS to DD in updated_us_cave_systems.csv so that it could be the same format as the other datasets used. Another example is needing help understanding how to use geopandas, geocoding, geodatasets to plot on a US Map as a visualization.
- **GitHub Copilot**: Assisted in writing functions and improving code efficiency by suggesting code completions and patterns.

## Data Sources
Dataset Name: victims_coords.csv
    Source: https://locationsunknown.org/the-missing-list
            https://www.geolocatify.com/
            https://www.latlong.net/
    Fields: The Missing Map
    
Dataset Name: bfro_sightings.csv
    Source: Bigfoot Field Researchers Organization
            bfro.net
            https://github.com/timothyrenner/bfro_sightings_data
    Fields: United States Sightings Reports
   
Dataset Name: updated_us_cave_systems.csv
    Source: https://en.wikipedia.org/wiki/List_of_longest_caves_in_the_United_State
    Fields: List of longest caves in the United States
    
Dataset Name: dogman_sightings.csv
    Source: North American Dogman Project
            https://github.com/timothyrenner/nadp-sightings-data
            https://northamericandogmanproject.com/
    Fields: Encounters
   
Dataset Name: ufo_sightings_transformed.csv
    Source: https://corgis-edu.github.io/corgis/csv/ufo_sightings/
            https://nuforc.org/databank/
    Fields; Sightings

### Personal Acknowledgments
- Thank you to all the mentors and fellow Code you students for their knowledge and input.
``
## Authors
- Robert Yann, student at Code You 
- [@ryann1004](https://www.github.com/ryann1004)
