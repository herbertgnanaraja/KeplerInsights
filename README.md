# SCS_3253_047 Machine Learning - KeplerInsights

# Final Project: April 5th, 2022

## Team members:
* Lucas Merrick
* Amitha Pillai
* Michael Tan
* Herbert Gnanaraja Richard Sundarrajan

## Project Overview:
The scientific objective of the Kepler Mission is to explore the structure and diversity of planetary systems, using a special-purpose spacecraft to measure light variations from thousands of distant stars, looking for planetary transits.

Kepler Objects of Interest (KOIs) are well vetted, periodic, transit-like events in the Kepler data. The Kepler Project identifies these objects from the Threshold-Crossing Events (TCE) list for further vetting. Some objects will be flagged as false positives.

## Objective:
Predict classification of KOI from Kepler data (exoplanet candidate or false positive)

## Data Exploration:
* Dataset with 82 features, 9564 instances
  * Identification Columns, Exoplanet Archive Information, Project Disposition Columns
  * Transit Properties, Threshold-Crossing Event (TCE) Information, Stellar Parameters, Kepler Input Catalog (KIC) Parameters, Pixel-Based KOI Vetting Statistics
 * Plot scatter matrix of features to evaluate data distributions, trends and understand relationship with other features
  * Mix of distributions: majority left/right skewed, some normally distributed
  * Some outliers observed
 * Plot correlation to identify redundant features
  * High correlation found in subset of features
  
 ## Data source and acknowledgement:
 This research has made use of the NASA Exoplanet Archive, which is operated by the California Institute of Technology, under contract with the National Aeronautics and Space Administration under the Exoplanet Exploration Program.
 
 https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative
