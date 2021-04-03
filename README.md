# WRF_AWSMarketplace

**Numerical Weather Prediction on AWS with WRF**

:black_medium_square: v1.1      
        - It works with AWS-parallelcluster v2.10.3  
* Initial release      
        - It has pre-compiled version of WRF-4.2.2 optimized for Intel Skylake & Cascade-Lake instances  
        - The built case is the January-2000 example  
        - It has pre-compiled NCL 6.6.2  
        - It works with AWS-parallelcluster v2.10.1  


___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS Graviton2 with WRF**
  
:white_medium_square: Initial release v1.0        
+ It has pre-compiled versions of WRF-4.2.2 optimized for Graviton2 (arm 64/AArch64) processors with the following available executables:  
    - WRF-4.2.2 ARW (/home/centos/WRF-4.2.2)  
    - WRF-4.2.2 ARW nested with preset moves (/home/centos/NESTED2)  
    - WRF-4.2.2 ARW nested with vortex following (/home/centos/NESTED3)  
    - WRF-4.2.2 NMM (/home/centos/NMM/NMMR)  
    - WRF-4.2.2 NMM (/home/centos/NMM/NMMR)   
+ The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for three and a half days starting on January 1st.     
+ The AMI works with AWS-parallelcluster v2.10.3  
+ Preprocessing tools: WPS; postprocessing tools: WRF-python.  


