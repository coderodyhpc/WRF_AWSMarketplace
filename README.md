# WRF_AWSMarketplace

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction & Air Quality Modeling (Graviton4) with Odycloud support**
  
:white_medium_square: v6.0.0        
+ The AMI works with AWS-parallelcluster v3.11.0 (O.S. Ubuntu 22.04) 
+ It has pre-compiled versions of WRF-4.6 optimized for Graviton4 processors with the following executables:  
    - WRF-4.6 ARW (/home/ubuntu/WRF-4.6)     
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile)
+ The AMI includes CMAQv5.5 to perform air quality modeling in 4 different flavors: 
    - cb6r5_ae7_aq_m3dry, cb6r5_ae7_aq_stage, cracmm2_m3dry and cracmm2_stage     
    - Batch and files to run the CRACMM2 and cb6r5_ae7_aq benchmarks for the 12NE3 domain
+ The AMI includes scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download for interactive download of GFS files 
+ Preprocessing tools: WPS (/home/ubuntu/PREPRO/WPS)  
+ Postprocessing tools: ARWpost, WRF-python 

