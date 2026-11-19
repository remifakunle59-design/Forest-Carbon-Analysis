# Forest-Carbon-Analysis
Hi, I'm Remilekun Eunice Fakunle (née Atobatele), an environmental scientist, and welcome to my portfolio!
My M.Sc. research (Pan African University Institute of Life and Earth Sciences, University of Ibadan) asked a simple question: what happens to the carbon stored in the landscape of southeastern Osun State, Nigeria, when forest turns into plantations, farms and towns? I measured trees in the field, took soil samples to the laboratory, and used remote sensing and GIS (ArcGIS, ENVI, QGIS, Google Earth Engine) to follow land cover from 1985 to 2020. Dense forest declined by about 76% over those 35 years.
My thesis was done with desktop GIS tools. This repository is where I am learning to do the same work reproducibly in Python and with cloud satellite data. I rebuilt parts of my thesis analysis in code, then asked new questions of it: can cloud-hosted Landsat data support what I found in the field, and how should satellite data be organised so a carbon model can use it? I have kept the limitations visible, including the places where my own results are weak, because I think an honest result is more useful than a polished one.

# Notebooks | What it entails 
- Land_Cover_Change_and_Carbon_Stocks_reanalysis | Carbon pools (aboveground, belowground, soil), uncertainty, land-cover change 1985-2020, carbon-stock upscaling and stock-change estimate 
- LULCF_Analysis_using_cloud-based_satellite_data | Landsat Collection from Microsoft Planetary Computer: STAC search, cloud masking, NDVI composites, ground-truthing, classification test 
- Model_ready_netCDF |Model-ready Earth observation data using Landsat NDVI cube as NetCDF (Xarray + Dask)

# Skills
- Forest biomass and carbon-stock estimation, with uncertainty 
- Land-use and land-cover change analysis 
- Carbon-stock upscaling (area x carbon per hectare) 
- Satellite data processing in the cloud (STAC, Xarray, Dask) 
- Reproducible, documented Python workflows (pandas, NumPy, Matplotlib, GeoPandas, Rasterio)
# Data and Sources
- M.Sc Thesis: Assessment of Land Use/Land Cover Change on Carbon Stocks in Southeastern part of Osun State, Nigeria
  Author: Remilekun Eunice Atobatele (PAULESI, University of Ibadan)
- Related paper: Atobatele, R. E., Ikporukpo, C. O., Taiwo, O. J., & Fakunle, A. O. (2023).
  International Journal of Environmental and Ecology Research, 5(1), 12-17.
- Landsat Collection accessed through Microsoft Planetary Computer. 
- Admin boundaries: FAO GAUL 2015.

