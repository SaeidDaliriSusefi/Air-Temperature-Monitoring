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

