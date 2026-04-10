# Urban Heat Island Classification — Freetown, Sierra Leone

## Overview
ML pipeline to classify Urban Heat Island (UHI) intensity 
at micro scale using satellite imagery and building footprint data. 
Built as part of the EY AI & Analytics Challenge (Business Challenge II).

## Cities covered
- Santiago, Chile → Random Forest
- Rio de Janeiro, Brazil → Gradient Boosting  
- Freetown, Sierra Leone → LightGBM (primary prediction target)

## Key features used
Sentinel-2 spectral indices (NDVI, NDBI, NDWI), Landsat LST, 
emissivity, building density, weather variables

## Tools & environment
Python · PySpark · LightGBM · Scikit-learn · Rioxarray · GeoPandas  
Microsoft Fabric / Synapse · Planetary Computer STAC API

## Results
F1 Score: 0.46

## Team
Eduardo Vadillo Polo, Fenja Bartels, Luis Schropp, 
Nolan Pierce, Renan Peres, Tyler Lyon
