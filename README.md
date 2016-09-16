## General Details
This repository contains code used to for Annalisa Sheehan, University of Southampton, 
MSc in Applied GIS and Remote Sensing thesis on: 
### Satellite-derived Particulate Matter pollution measurements and their relationship with hospital admissions in the Wessex region

For more information please contact: ans1g15@soton.ac.uk or annalisa.sheehan@hotmail.com

If you use this code please cite my thesis: 
Sheehan, A.N. (2016) Satellite-derived Particule Matter pollution measurements and their relationship with hospital admissions in the Wessex region, MSc Thesis, University of Southampton. 

This code is written for personal use and the data used within the code is not publically available. 
However, to run the code in the environment in which it was written use the environment.yml file and run the following code in the command line:
```conda env create -f environment.yml```

## Overview of the Code
The code in this repository reprojects MAIAC AOT images from WGS84 datum into the British National Grid and converts AOT measurements into PM2.5 estimates. Additionally, the code analyses the PM2.5 data to investigate how PM2.5 is changing spatially and temporally over Wessex and the impact on hospital admissions for circulatory and respiratory diseases.

The different jupyter notebooks correspond to different sections of my thesis. 
- Section 3.3 - Getting_MAIAC_into_dask_daily_data.ipynb
- Section 3.4.1 - Reprojecting_MAIAC_data.ipynb
- Section 3.4.1/3.5.1/3.5.2/3.5.4 - MAIAC_Analysis.ipynb 
- Section 3.4.2 Rasterstats_from_Xarray.ipynb
- Section 3.4.4 Lamb_Weather_Types.ipynb
- Section 3.5.2 Linear_regression.ipynb
- Section 3.5.3 Regression_analysis.ipynb
- Section 3.5.3 Regression_MSOA.ipynb
- Section 3.5.3 Regression_coastal.ipynb
- Section 3.5.3 Stratified_regression.ipynb
- Section 3.5.3 Weighted_least_square_regression.ipynb
- Section 3.6 AERONET_validation.ipynb
- Section 3.6 AURN_Validation.ipynb