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
Section 3.3.1 - Reprojecting_MAIAC_data.ipynb
