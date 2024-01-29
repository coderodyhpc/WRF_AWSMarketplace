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
**Numerical Weather Prediction on AWS with WRF**
  
:black_medium_square: v3.1        
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
**Numerical Weather Prediction on AWS with WRF**
  
:black_medium_square: v3.2        
+ It has pre-compiled versions of WRF-4.3.3 optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-4.3.3 ARW (/home/centos/WRF-4.3.3). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on January 1st (2022)     
+ It has pre-compiled versions of WRF-Chem (4.3) optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-Chem - KPP1 (/home/centos/WRF-CHEM)  
+ Preprocessing tools: WPS (SM - /home/centos/PREPRO/WPS; DM - /home/centos/PREPRO/WPS_DM) 
+ Postprocessing tools: NCL, WRF-python, NCEP Unified Post Processor (UPP), ARWPost, GrADS, and IDV (v5.7) 
+ Data Assimilation tool: WRFDA (/home/centos/DA)
+ WRF non-linear, WRF tangent-linear and WRF adjoint models app: WRFPLUS (/home/centos/DA)
+ The AMI works with AWS-parallelcluster v2.11.3  

___________________________________________________________________________________________________________________________________________
**Numerical Weather Prediction on AWS with WRF**
  
:black_medium_square: v4.0.0        
+ It has pre-compiled versions of WRF-4.4 optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-4.4 ARW (/home/ubuntu/WRF-4.4). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on January 1st (2022)     
+ It has pre-compiled versions of WRF-Chem (4.4) optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-Chem - KPP1 (/home/ubuntu/WRF-CHEM)  
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM) 
+ Postprocessing tools: NCL, WRF-python, NCEP Unified Post Processor (UPP), ARWPost, GrADS, and IDV (v6.0) 
+ Data Assimilation tool: WRFDA (/home/ubuntu/DA/WRFDA) 
+ WRF non-linear, WRF tangent-linear and WRF adjoint models app: WRFPLUS (/home/ubuntu/DA/WRFPLUS)
+ The AMI works with AWS-parallelcluster v3.1.3  

___________________________________________________________________________________________________________________________________________
**Odycloud Numerical Weather Prediction & Air Quality Modeling on AWS**
  
:black_medium_square: v5.0.0        
+ It has pre-compiled versions of WRF-4.5.1 optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-4.5.1 ARW (/home/ubuntu/WRF-4.5). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on May 1st (2023)     
+ It has pre-compiled versions of WRF-Chem (4.5.1) optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-Chem - KPP1 (/home/ubuntu/WRF-CHEM)  
+ It includes CMAQv5.4 to perform air quality modeling
+ Script to accelerate the download of GFS data
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS; DM - /home/ubuntu/PREPRO/WPS_DM) 
+ Postprocessing tools: WRF-python, ARWPost, GrADS, and IDV  
+ Data Assimilation tool: WRFDA (/home/ubuntu/DA/WRFDA) 
+ WRF non-linear, WRF tangent-linear and WRF adjoint models app: WRFPLUS (/home/ubuntu/DA/WRFPLUS)
+ The AMI works with AWS-parallelcluster v3.7.1  
___________________________________________________________________________________________________________________________________________
**Odycloud Numerical Weather Prediction & Air Quality Modeling on AWS**
  
:black_medium_square: v5.1.0        
+ It has pre-compiled versions of WRF-4.5.2 optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-4.5.2 ARW (/home/ubuntu/WRF-4.5). The default case represents the continental U.S. with a horizontal resolution of 8 km (~5 miles) and a nested simulation of the Washington-DC area with a resolution of 1.6 km (~1 mile). The preset computation is for 2 days starting on May 1st (2023)     
+ It has pre-compiled versions of WRF-Chem (4.5.2) optimized for Intel Scalable (Skylake/Cascade Lake/Ice Lake) processors with the following executable:  
    - WRF-Chem - KPP1 (/home/ubuntu/WRF-CHEM)  
+ It includes CMAQv5.4 to perform air quality modeling
+ Script to accelerate the download of GFS data
+ Preprocessing tools: WPS (SM - /home/ubuntu/PREPRO/WPS) 
+ Postprocessing tools: WRF-python, ARWPost, GrADS, and IDV  
+ Data Assimilation tool: WRFDA (/home/ubuntu/DA/WRFDA) 
+ WRF non-linear, WRF tangent-linear and WRF adjoint models app: WRFPLUS (/home/ubuntu/DA/WRFPLUS)
+ The AMI works with AWS-parallelcluster v3.8.0  



