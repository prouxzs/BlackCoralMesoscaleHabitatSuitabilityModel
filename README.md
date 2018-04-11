# BlackCoralMesoscaleHabitatSuitabilityModel
Mesoscale Habitat Suitability Model for Antipatharians in the Gulf of Mexico 

Objectives

  The goal of this analysis is to create the first mesoscale habitat suitability model for black corals (Antipatharians) in the Gulf of Mexico at depths between 300 and 650 meters.
  Existing habitat suitability models utilize the Coastal Relief Model to determine depth and seafloor topography. Resolution in the Coastal Relief Model is on the scale of kilometers whereas the multibeam sonar data I used has a much higher resolution (10m x 10m pixels).
  Using four primary environmental variables (depth, slope, aspect, and backscatter intensity), along with ground-truthed coral presence/absence data, I did a binomial logistic regression that predicts the likelihood of a black coral occuring in any given 10x10 pixel given a depth, slope, aspect, and backscatter value.
  This code provides a framework to use raster data as predictors of presence or absence. You'll need rasters and presence/absence data with coordinates. Be sure your rasters and coordinates are from the same coordinate reference system.

Structure of the Code-Base

  You'll need to load the following packages:
	library("raster","rgdal","sp")
  
How to Recreate Results

  All you need to do to recreate the code is change the name of the imported files to your file names.

Acknowledgements

  NOAA's Deep Coral Ecology Laboratory provided the presence/absence data 
  
  NOAA Ship Nancy Foster collected the multibeam data in 2008
