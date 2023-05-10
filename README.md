# WRF_AWSMarketplace

**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: Initial release v1.0        
+ It has pre-compiled versions of WRF-4.2.2 optimized for Graviton2 (arm 64/AArch64) processors with the following executables:  
    - WRF-4.2.2 ARW (/home/centos/WRF-4.2.2)  
    - WRF-4.2.2 ARW nested with preset moves (/home/centos/NESTED2)  
    - WRF-4.2.2 ARW nested with vortex following (/home/centos/NESTED3)  
    - WRF-4.2.2 NMM (/home/centos/NMM/NMMR)  
    - WRF-4.2.2 NMM_tropical_cyclone (/home/centos/NMM/NMM_tropical_cyclone)   
+ The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for three and a half days starting on January 1st.     
+ The AMI works with AWS-parallelcluster v2.10.3  
+ Preprocessing tools: WPS; postprocessing tools: WRF-python and NCEP Unified Post Processor (UPP). 


___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: v3.1        
+ It has pre-compiled versions of WRF-4.3 optimized for Graviton2 (arm 64/AArch64) processors with the following executables:  
    - WRF-4.3 ARW (/home/centos/WRF-4.3). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on January 1st (2021).     
    - WRF-4.3 ARW nested with preset moves (/home/centos/NESTED2)  
    - WRF-4.3 ARW nested with vortex following (/home/centos/NESTED3)  
    - WRF-4.3 NMM (/home/centos/NMM)  
    - WRF-4.3 NMM nested with preset moves (/home/centos/NMM2)  
+ It has pre-compiled versions of WRF-Chem (4.3) optimized for Graviton2 processors with the following executables:  
    - WRF-Chem - KPP0 (/home/centos/WRF-CHEM/KPP0)  
    - WRF-Chem - KPP1 (/home/centos/WRF-CHEM/KPP1)  
+ Preprocessing tools: WPS (SM - /home/centos/PREPRO/WPS; DM - /home/centos/PREPRO/WPS_DM) 
+ Postprocessing tools: NCL, WRF-python and NCEP Unified Post Processor (UPP). 
+ The AMI works with AWS-parallelcluster v2.10.4  

+ For organizations that prefer to run V3. it has pre-compiled versions of WRF and WPS optimized for Graviton2 (arm 64/AArch64) processors with the following executables: 
    - WRF-3.9.1.1 ARW (/home/centos/V3/WRFV3-3.9.1.1)  
    - WPSv3 (/home/centos/V3/WPS-RELEASE-3-8-1)  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: v3.1.1        
+ It has pre-compiled versions of WRF-4.3 optimized for Graviton2 (arm 64/AArch64) processors with the following executables:  
    - WRF-4.3 ARW (/home/centos/WRF-4.3). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on September 1st (2021).     
    - WRF-4.3 ARW nested with preset moves (/home/centos/NESTED2)  
    - WRF-4.3 ARW nested with vortex following (/home/centos/NESTED3)  
    - WRF-4.3 NMM (/home/centos/NMM)  
+ It has pre-compiled versions of WRF-Chem (4.3) optimized for Graviton2 processors with the following executables:  
    - WRF-Chem - KPP0 (/home/centos/WRF-CHEM/KPP0)  
    - WRF-Chem - KPP1 (/home/centos/WRF-CHEM/KPP1)  
+ Preprocessing tools: WPS (SM - /home/centos/PREPRO/WPS; DM - /home/centos/PREPRO/WPS_DM) & Script to automatically download GFS data
+ Postprocessing tools: NCL, GrADS, ARWpost, WRF-python and NCEP Unified Post Processor (UPP). 
+ The AMI works with AWS-parallelcluster v2.11.2  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: v3.1.2        
+ It has pre-compiled versions of WRF-4.3 optimized for Graviton2 (arm 64/AArch64) processors with the following executables:  
    - WRF-4.3 ARW (/home/centos/WRF-4.3). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on September 1st (2021).     
    - WRF-4.3 ARW nested with preset moves (/home/centos/NESTED2)  
    - WRF-4.3 ARW nested with vortex following (/home/centos/NESTED3)  
    - WRF-4.3 NMM (/home/centos/NMM)  
+ It has pre-compiled versions of WRF-Chem (4.3) optimized for Graviton2 processors with the following executables:  
    - WRF-Chem - KPP0 (/home/centos/WRF-CHEM/KPP0)  
    - WRF-Chem - KPP1 (/home/centos/WRF-CHEM/KPP1)  
+ It has pre-compiled versions of WRF Data Assimilation (WRFDA) optimized for Graviton2 processors with the following executables:  
    - WRFDA - (/home/centos/DA/WRFDA)  
    - WRFPLUS - (/home/centos/DA/WRFPLUS)  
+ Preprocessing tools: WPS (SM - /home/centos/PREPRO/WPS; DM - /home/centos/PREPRO/WPS_DM) & Script to automatically download GFS data
+ Postprocessing tools: NCL, GrADS, ARWpost, WRF-python and NCEP Unified Post Processor (UPP). 
+ The AMI works with AWS-parallelcluster v2.11.2  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: v4.0.0        
+ It has pre-compiled versions of WRF-4.4 optimized for Graviton2 processors with the following executables:  
    - WRF-4.4 ARW (/home/ubuntu/WRF-4.4)     
    - WRF-4.4 ARW nested with preset moves (/home/ubuntu/NESTED2)  
    - WRF-4.4 ARW nested with vortex following (/home/ubuntu/NESTED3)  
    - WRF-Chem (/home/ubuntu/WRF-CHEM)  
    - WRFDA (/home/ubuntu/DA/WRFDA)  
    - WRFPLUS (/home/ubuntu/DA/WRFPLUS)
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile); the preset computation is for 2 days starting on January 1st (2022).  
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM)  
+ Script to accelerate the download of GFS data
+ Postprocessing tools: NCL, GrADS, ARWpost, WRF-python 
+ The AMI works with AWS-parallelcluster v3.1.4  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2/3 with WRF**
  
:white_medium_square: v4.2.0        
+ It has pre-compiled versions of WRF-4.4.2 optimized for Graviton2/3 processors with the following executables:  
    - WRF-4.4.2 ARW (/home/ubuntu/WRF-4.4.2)     
    - WRF-4.4.2 ARW nested with preset moves (/home/ubuntu/NESTED2)  
    - WRF-4.4.2 ARW nested with vortex following (/home/ubuntu/NESTED3)  
    - WRF-Chem (/home/ubuntu/WRF-CHEM)  
    - WRF-Fire (/home/ubuntu/WRF-Fire)  
    - WRF-SFIRE (/home/ubuntu/WRF-SFIRE)  
    - WRFDA (/home/ubuntu/DA/WRFDA)  
    - WRFPLUS (/home/ubuntu/DA/WRFPLUS)
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile); the preset computation is for 2 days starting on January 1st (2023).  
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM)  
+ Script to accelerate the download of GFS data
+ Postprocessing tools: GrADS, ARWpost, WRF-python 
+ The AMI works with AWS-parallelcluster v3.4.1  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2/3 with WRF**
  
:white_medium_square: v5.0.0        
+ It has pre-compiled versions of WRF-4.4.2 optimized for Graviton2/3 processors with the following executables:  
    - WRF-4.4.2 ARW (/home/ubuntu/WRF-4.4.2)     
    - WRF-4.4.2 ARW nested with preset moves (/home/ubuntu/NESTED2)  
    - WRF-4.4.2 ARW nested with vortex following (/home/ubuntu/NESTED3)  
    - WRF-Chem (/home/ubuntu/WRF-CHEM)  
    - WRF-Fire (/home/ubuntu/WRF-Fire)  
    - WRF-SFIRE (/home/ubuntu/WRF-SFIRE)  
    - WRFDA (/home/ubuntu/DA/WRFDA)  
    - WRFPLUS (/home/ubuntu/DA/WRFPLUS)
    - A default case representing the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile); the preset computation is for 2 days starting on January 1st (2023).  
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM)  
+ Script to accelerate the download of GFS data
+ Postprocessing tools: GrADS, ARWpost, WRF-python 
+ The AMI works with AWS-parallelcluster v3.5.1  



