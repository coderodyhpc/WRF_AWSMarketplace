# WRF_AWSMarketplace

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction & Air Quality Modeling Graviton4 with Odycloud support**
  
:white_medium_square: v6.0.0        
+ The AMI works with AWS-parallelcluster v3.11.0 (O.S. Ubuntu 22.04) 
+ It has pre-compiled versions of WRF-4.6 optimized for Graviton4 processors with the following executables:  
    - WRF-4.6 ARW (/home/ubuntu/WRF-4.6)     
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile); the preset computation is for 2 days starting on January 1st (2024).
    -   
+ The AMI includes CMAQv5.5 to perform air quality modeling
+ The AMI includes 3 scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download for interactive download of GFS files, download_NAM for interactive download of NAM files, and GFS_batch for downloading GFS files with a one-line command.+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM)  
+ Script to accelerate the download of GFS data
+ Postprocessing tools: GrADS, ARWpost, WRF-python 



