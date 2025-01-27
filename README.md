# GUI_AWSMarketplace

**Graphical User Interface (GUI) for Numerical Predictions in the public cloud: Graviton 3 & 4**

:black_medium_square: v1.0.0
The GUI allows users to control the modeling process with WRF, CMAQ and MPAS (global meshes).
AMI includes:
+ Pre-compiled WRF-4.6 and preprocessing tools  
+ Pre-compiled CMAQv5.5 and preprocessing tools  
+ Pre-compiled MPAS-8.2  

◻️ WRF interface features:
+ The interface allows model-users the generation of single and nested domains.
+ Download of meteorological data now includes GFS (0.25, 0.5 & 1 deg resolutions), NAM and GDAS.
+ Selection of main WRF parameters 
+ Running the 3 components of WPS: geogrib, ungrib, and metgrid
+ Automatic run of WRF based on the available number of cores
  
◻️ WRF interface features:
+ The CMAQ interface will automatically pick up mesh parameters based on the WRF outputfile
+ The MCIP, ICON and BCON submenus allow model users the customization of several parameters before proceeding with the computations
+ Output hundreds of species on a GIS framework
  
◻️ MPAS interface features:
+ It works with global meshes
+ The interface will set up most parameters based on mesh selection and number of available cores  

