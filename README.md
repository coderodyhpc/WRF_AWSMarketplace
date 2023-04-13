# GUI_AWSMarketplace

**Graphical User Interface (GUI) for Numerical Predictions in the public cloud: Graviton3&3(E)**

:black_medium_square: v0.1.0
The GUI allows users to control all aspects of the modeling process with WRF and CMAQ.
The AMI includes:
+ Pre-compiled WRF-4.4.2 optimized for Graviton3 processors  
+ Pre-compiled CMAQv5.4 optimized for Graviton3 processors  
+ All files necessary to run the 2018 N.E. benchmark (12NE3) for CMAQv5.4
+ Implementation to run the CONUS benchmark (12US1) for CMAQv5.4 (files with meteorological data and emissions must be uploaded before performing the benchmark)

:white_medium_square: New features included in v0.1.0
+ The interface for WRF is fully functional for a single domain.
+ Download of meteorological data now includes NAM and GD?? files in addition to GFS (0.25 & 0.5 deg resolution)
+ The interface with CMAQ includes the option to create a custom case (based on WRF output)
+ MCIP, ICON and BCON admit the customization of several parameters

___________________________________________________________________________________________________________________________________________

