# High_Strangeness_RobertYann

## Table of Contents
- [Summary]
- [Prerequisites](#prerequisites)
- [Acknowledgements]
- [Setup Instructions](#setup-instructions)
- [Database Setup](#database-setup)
- [Activating and Deactivating the Virtual Environment](#activating-and-deactivating-the-virtual-environment)
- [Running the Project](#running-the-project)
- [License](#license)

## Summary
I'm analyzing data on missing persons in U.S. national forests to identify connections and
similarities linking these cases to reports of Bigfoot and Dogman sightings, as well as instances
of high strangeness associated with U.S. cave systems. This project aims to uncover patterns
that might suggest a deeper, potentially unexplained phenomenon related to these wilderness
areas. By synthesizing datasets on missing individuals and paranormal sightings, I hope to
provide fresh insights into these mysterious occurrences                                             

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
Below are the top questions I wanted to observe:
1. Similarities in Location of Sightings: Investigate if there are patterns or common geographic locations among sightings of  Bigfoot, Dogman, and UFOs.
2. Proximity to Missing Persons: Analyze whether the locations of these sightings occur near the last known locations of missing persons in various National Parks.
3. Relation to Largest US Cave Systems: Determine if sightings of Bigfoot and Dogman are concentrated near or within major cave systems in the United States.
4. Geographic Distribution of Sightings: Identify regions or states in the U.S. where the majority of these sightings are reported.

Conclusions:
1. The analysis indicates that there is a significant overlap in the locations of Dogman, UFO, and Bigfoot sightings. This suggests that these phenomena may share common geographic areas, possibly indicating hot spots or regions of interest for further investigation.
2. The analysis indicates that there is no significant evidence to support a relationship between the GPS locations of sightings (Bigfoot, Dogman, UFOs) and the last known locations of missing persons in various National Parks.
3. The analysis reveals a noteworthy connection between Bigfoot and Dogman sightings in proximity to large U.S. cave systems. Specifically, there is up to 64 sightings within an 82 square mile radius of these cave systems. By adding additional cave systems and increasing the distance parameter in the analysis, I anticipate that the correlation will further strengthen.
4. After plotting the sightings on a map of the USA using geopandas, etc. there starts to show a pattern of where the ufo, bigfoot and Dogman sightings are occurring. The strongest areas seem to be in the midwest, southeast, especially the appalachian mountain range as well as up and down the west coast with a focus of the Pacific Northwest. Coincidentally, the majority of the US cave systems as well as National Parks are located in these same hot spots. 

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
- **Duck.ai**: It helped in generating code that was not covered in the Code You Data Analysis class. Specific examples include needing to import Regular Expressions (Regex) in order to change the gps coordinate format from DMS to DD in updated_us_cave_systems.csv so that it could be the same format as the other datasets used. Another example is needing help understanding how to use geopandas, geocoding, geodatasets to plot on a US Map as a visualization.

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
            https://www.geolocatify.com/
            https://www.latlong.net/
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
- Thank you to all the mentors and fellow Code you students for their support, knowledge and input.
``
## Authors
- Robert Yann, student at Code You 
- [@ryann1004](https://www.github.com/ryann1004)
