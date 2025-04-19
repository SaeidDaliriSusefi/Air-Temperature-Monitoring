# 🌍 Temperature Trend Analysis using Google Earth Engine & Python
This repository contains a Python-based workflow to analyze long-term temperature trends over a selected region using Google Earth Engine (GEE) and ECMWF ERA5 datasets(available from 1950 with 10km resolution). The script leverages geospatial libraries and statistical tools to extract, process, and visualize temperature data over time, providing insights into climate change patterns.



## 🚀 Key Features

📡 Integration with Google Earth Engine for accessing high-resolution ECMWF ERA5 datasets.

🗺️ Interactive selection of region of interest (ROI) via geemap.

🧊 Extraction of monthly 2-meter air temperature data from ERA5/ERA5-Land collections.

📊 Trend analysis using Mann-Kendall test for detecting monotonic trends in time series.

📈 High-quality visualizations with matplotlib.


## 🧰 Tools & Libraries

xee – For loading Earth Engine ImageCollections into Xarray.

geemap – For drawing and selecting regions interactively.

xarray – For handling multi-dimensional data arrays.

pymannkendall – For performing non-parametric trend tests.

matplotlib, pandas, sklearn, geopandas, and more – For visualization and data manipulation.


## 📍 How It Works
Authentication : Authenticate your Google Earth Engine account and initialize the session with your project settings.

ROI Selection : Use an interactive map (via geemap) to draw and define your Region of Interest (ROI).

Period Selection : Define the time period of analysis (e.g., 1950–2025) to explore long-term trends.

Data Collection : Load historical daily or monthly temperature data from ECMWF ERA5/ERA5-Land datasets using xee and xarray.

Trend Analysis : Apply the Mann-Kendall trend test to detect statistically significant increases or decreases in temperature over time.

Country Name Selection :  Select a country by name to automatically load and display its national boundary 

Visualization : Generate time series plots, spatial maps, and clustered regions to better understand spatial and temporal temperature patterns.





📸 Example Outputs
(You can add example charts or screenshots here for better presentation)

📜 License
MIT License


