# GUI_AWSMarketplace

**Graphical User Interface (GUI) for Numerical Predictions in the public cloud: Graviton4**

:black_medium_square: v1.4
+ Several upgrades to the postprocressing tools: It is now feasible to export snapshots of the map canvas and to generate csv files with hourly values for the WRF output variables
+ The CMAQ interface includes several upgrades mainly targeting simulation using the CRACMM2 chemical mechanism as the GUI facilitates the conversions of CB6R5 files to CRACMM2 regridding purposes
+ It is feasible to directly download NHEMIS files and time-shift them

:black_medium_square: v1.4
+ WRF and WRF-CMAQ have been upgraded to v4.7  

:black_medium_square: v1.3
+ The generation of CRACMM2 files (for regrid purposes) from Carbon Bond 6 concentration files has been streamlined  
+ Experimental integration of WRF-CMAQ with the CRACMM2 mechanism   

:black_medium_square: v1.2
+ Experimental integration of WRF-CMAQ (Carbon Bond 6 mechanism) with the GUI   

:black_medium_square: v1.1
+ O/S has been upgraded to Ubuntu 24.04
+ QGIS has been upgraded to v3.42.3
+ CMAQ can now use CRACMM2 mechanism in addition to Carbon Bond 6   
+ The CMAQ set up menu allows model-users to select the chemical mechanism (CB6R5 vs CRACMM2) and deposition model (m3dry vs stage) 

:black_medium_square: v1.0
The GUI allows users to control the modeling process with WRF, CMAQ and several preprocessing apps.
AMI includes:
+ Pre-compiled WRF-4.6 and preprocessing tools  
+ Pre-compiled CMAQv5.5 and preprocessing tools  

◻️ WRF interface features:
+ Generation of single and nested domains on a GIS framework
+ Download of meteorological data now including GFS (0.25, 0.5 & 1 deg resolutions), NAM and GDAS files
+ Selection of main WRF parameters 
+ Option to run all or any of the 3 components of WPS: geogrib, ungrib, and metgrid
+ Automatic run of WRF based on the available number of cores
+ Widget to transfer all generated files to a S3 bucket (it also includes the ability to create a new bucket or enter credentials)
  
◻️ CMAQ interface features:
+ The CMAQ interface will automatically pick up mesh parameters based on the WRF output file
+ The set up menu allows model-users to select simulation and grid names, starting date/time and duration of the simulation 
+ The MCIP submenus allow model users the customization of several parameters (e.g. BTRIM) before prreprocessing the meteorological data
+ The ICON and BCON interfacess facilitate the generation of boundary conditions either from profiles or via regridding 
+ Emission streams can be either loaded or the GUI includes a widget to generate emission streams from universal inventories (biogenic and anthropogenic emissions are available) 
+ The GUI allows model users to write the batch file and run CMAQ with all available cores 
+ Visualization of the results for hundreds of species on a GIS framework
+ Widget to transfer all generated files to a S3 bucket (it also includes the ability to create a new bucket or enter credentials)
  
