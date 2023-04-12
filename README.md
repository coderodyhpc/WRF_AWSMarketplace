# GUI_AWSMarketplace

**GUI for Numerical Predictions**

:black_medium_square: v0.1.1      
+ It has pre-compiled versions of WRF-4.3 optimized for Intel Skylake/Cascade Lake processors with the following executables:  
    - WRF-4.3 ARW (/home/centos/WRF-4.3). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on January 1st (2021).     
    - WRF-4.3 NMM (/home/centos/NMM)  
+ It has pre-compiled versions of WRF-Chem (4.3) optimized for Intel Skylake/Cascade Lake processors with the following executables:  
    - WRF-Chem - KPP0 (/home/centos/WRF-CHEM/KPP0)  
    - WRF-Chem - KPP1 (/home/centos/WRF-CHEM/KPP1)  
+ Preprocessing tools: WPS (SM - /home/centos/PREPRO/WPS; DM - /home/centos/PREPRO/WPS_DM) 
+ Postprocessing tools: NCL, WRF-python, NCEP Unified Post Processor (UPP) and IDV (v5.7). 
+ The AMI works with AWS-parallelcluster v2.11.0  

+ For organizations that prefer to run V3. it has pre-compiled versions of WRF and WPS optimized for Intel Skylake/Cascade Lake processors with the following executables: 
    - WRF-3.9.1.1 ARW (/home/centos/V3/WRFV3-3.9.1.1)  
    - WPSv3 (/home/centos/V3/WPS-RELEASE-3-8-1)  

___________________________________________________________________________________________________________________________________________

