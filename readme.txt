Readme.txt for Atwood, Hille, et al. Code Repository

This repository consists of two Jupyter notebooks (one for isotope, rainfall and hydraulic conductivity data and one for ET data) and the datasets required to run the code in those notebooks. These notebooks requires Python 3.10 and the following packages to run: Pandas, NumPy, rasterio, rasterstats, os, geopandas. 

To use these files, download both the notebooks and dataset folders and replace /path/to/data with local data path. Outputs are all data used in plots in the manuscript. For code for plotting data, please reach out to corresponding author. The runtime should be negligible on most machines. To use own data, datafiles will need to be constructed similarly to the CSV files in the example folder. 

Jupyter notebooks:
AtwoodHille_ET_data.ipynb: Ecostress evapotranspiration data
AtwoodHille_isotope_rainfall_Kfs_data.ipynb: isotope, rainfall and hydraulic conductivity data 

Datasets:
AtwoodHille_Kfs_results.csv: Hydraulic conductivity
AtwoodHille_SanGabes_Fnew_isotopes.csv: New water fraction data
AtwoodHille_SanGabes_WaterIsotopeData.csv: streamflow and rainfall water isotope data
Bobat_Fire_Rain_Gauge_Dec2020_May2022.csv: rainfall amount from rain gauge data
catchment_polygons_3857.shp: Shapefile of catchments in EPSG 3857
ecostress_rasters_example: subset of Ecostress (Fisher et al., 2020) rasters used in datasets
