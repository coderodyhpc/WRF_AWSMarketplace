# WRF_AWSMarketplace

___________________________________________________________________________________________________________________________________________
**Odycloud NWP & AQM with added preprocessing apps and support**
  
:white_medium_square: v6.2.0        
+ The AMI works with AWS-parallelcluster v3.15.0 (O.S. Ubuntu 24.04) 
+ It has pre-compiled versions of WRF-4.7 & WRF-4.8 optimized for Graviton4 processors with the following executables:  
    - WRF-4.7 ARW (/home/ubuntu/WRF-4.7)     
    - WRF-4.8 ARW (/home/ubuntu/WRF-4.8)     
+ The AMI includes CMAQv5.5 to perform air quality modeling with 4 different combinations of chemical mechanism and deposition module: 
    - cb6r5_ae7_aq_m3dry, cb6r5_ae7_aq_stage, cracmm2_m3dry and cracmm2_stage     
    - Batch and files to run the CRACMM2 and cb6r5_ae7_aq benchmarks for the 12NE3 domain
+ The AMI includes a new compilation of WRFv4.8-CMAQv5.5 to perform coupled numerical weather predictions - air quality modeling with 2 different combinations: 
    - Subdirectory /home/ubuntu/WRF-CMAQ (chemical mechanism: cb6r5_ae7_aq; deposition module: m3_dry)     
    - Subdirectory /home/ubuntu/WRF-CRACMM (chemical mechanism: cracmm2; deposition module: stage)
Contact us (support@odycloud-hpc.com) 
+ The AMI includes 3 scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download and NAM_download for interactive download of GFS and NAM files, respectively; download_GFS for downloading of GFS files via a batch call 
+ Preprocessing tools: WPS (/home/ubuntu/PREPRO/WPS)  
+ Postprocessing tools: ARWpost, WRF-python
___________________________________________________________________________________________________________________________________________
**Odycloud NWP & AQM with added preprocessing apps and support**
  
:white_medium_square: v6.1.0        
+ The AMI works with AWS-parallelcluster v3.15.0 (O.S. Ubuntu 24.04) 
+ It has pre-compiled versions of WRF-4.7 optimized for Graviton4 processors with the following executables:  
    - WRF-4.7 ARW (/home/ubuntu/WRF-4.7)     
+ The AMI includes a new compilation for CMAQv5.5 to perform air quality modeling with 4 different combinations of chemical mechanism and deposition module: 
    - cb6r5_ae7_aq_m3dry, cb6r5_ae7_aq_stage, cracmm2_m3dry and cracmm2_stage     
    - Batch and files to run the CRACMM2 and cb6r5_ae7_aq benchmarks for the 12NE3 domain
+ The AMI includes 3 scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download and NAM_download for interactive download of GFS and NAM files, respectively; download_GFS for downloading of GFS files via a batch call 
+ Preprocessing tools: WPS (/home/ubuntu/PREPRO/WPS)  
+ Postprocessing tools: ARWpost, WRF-python

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction & Air Quality Modeling (Graviton4) with Odycloud support**

:white_medium_square: v6.0.2
+ The AMI works with AWS-parallelcluster v3.11.0 (O.S. Ubuntu 22.04)
+ It has pre-compiled versions of WRF-4.6 optimized for Graviton4 processors with the following executables:
    - WRF-4.6 ARW (/home/ubuntu/WRF-4.6)
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile)
+ The AMI includes CMAQv5.5 to perform air quality modeling in 4 different flavors:
    - cb6r5_ae7_aq_m3dry, cb6r5_ae7_aq_stage, cracmm2_m3dry and cracmm2_stage
    - Batch and files to run the CRACMM2 and cb6r5_ae7_aq benchmarks for the 12NE3 domain
+ The AMI includes 3 scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download and NAM_download for interactive download of GFS and NAM files, respectively; download_GFS for downloading of GFS files via a batch call
+ Preprocessing tools: WPS (/home/ubuntu/PREPRO/WPS)
+ Postprocessing tools: ARWpost, WRF-python
 
___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction & Air Quality Modeling (Graviton4) with Odycloud support**

:white_medium_square: v6.0.1        
+ The AMI works with AWS-parallelcluster v3.11.0 (O.S. Ubuntu 22.04) 
+ It has pre-compiled versions of WRF-4.6 optimized for Graviton4 processors with the following executables:  
    - WRF-4.6 ARW (/home/ubuntu/WRF-4.6)     
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile)
+ The AMI includes CMAQv5.5 to perform air quality modeling in 4 different flavors: 
    - cb6r5_ae7_aq_m3dry, cb6r5_ae7_aq_stage, cracmm2_m3dry and cracmm2_stage     
    - Batch and files to run the CRACMM2 and cb6r5_ae7_aq benchmarks for the 12NE3 domain
+ The AMI includes 3 scripts to accelerate the download of meteorological data at /home/ubuntu/DATA: GFS_download and NAM_download for interactive download of GFS and NAM files, respectively; download_GFS for downloading of GFS files via a batch call 
+ Preprocessing tools: WPS (/home/ubuntu/PREPRO/WPS)  
+ Postprocessing tools: ARWpost, WRF-python 
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
