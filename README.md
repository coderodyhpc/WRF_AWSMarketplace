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
**Air pollution modeling with CMAQ & WRF-CMAQ on AWS**
  
:black_medium_square: v1.0        
+ It has pre-compiled versions of CMAQ v5.3.3 optimized for Intel Ice Lake processors with the following executables:  
    - Standard CMAQ (CCTM_v533.exe) at /home/centos/CMAQ/CCTM/scripts/BLD_CCTM_v533_gcc
    - CMAQ-DDM3D (CCTM_DDM3D_v533.exe) at /home/centos/CMAQ-DDM3D/CCTM/scripts/BLD_CCTM_v533_gcc
    - CMAQ-ISAM (CCTM_ISAM_v533.exe) at /home/centos/CMAQ-ISAM/CCTM/scripts/BLD_CCTM_v533_gcc
    - WRF-CMAQ (wrf.exe) at /home/centos/WRF-CMAQ/CMAQ-v5.3.3/CCTM/scripts/WRF-4.3/test/em_realWRF-4.3
    
The default cases represent the standard benchmark cases over the Southeast U.S. with a horizontal resolution of 12 km. See https://www.epa.gov/cmaq/cmaq-inputs-and-test-case-data for details.     
+ Preprocessing tools: MCIP (/home/centos/CMAQ/PREP/mcip), create_omi (/home/centos/CMAQ/PREP/create_omi), BCON (/home/centos/CMAQ/PREP/bcon), ICON (/home/centos/CMAQ/PREP/icon), SMOKE (/home/centos/PREPRO/SMOKE), WPS (/home/centos/PREPRO/WPS) 
+ Postprocessing tools: VERDI v2.1, IDV. 
+ The AMI works with AWS-parallelcluster v2.12.2       


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
**Air quality modeling with CMAQ & WRF-CMAQ on AWS**
  
:black_medium_square: v1.1        
+ It has pre-compiled versions of CMAQ v5.3.3 optimized for Intel Ice Lake/Cascade Lake/Skylake processors with the following executables:  
    - Standard CMAQ (CCTM_v533.exe) at /home/ubuntu/CMAQ/CCTM/scripts/BLD_CCTM_v533_gcc
    - CMAQ-DDM3D (CCTM_DDM3D_v533.exe) at /home/ubuntu/CMAQ-DDM3D/CCTM/scripts/BLD_CCTM_v533_DDM3D_gcc
    - CMAQ-ISAM (CCTM_ISAM_v533.exe) at /home/ubuntu/CMAQ-ISAM/CCTM/scripts/BLD_CCTM_v533_ISAM_gcc
    - WRF-CMAQ (wrf.exe) at /home/ubuntu/WRF-CMAQ/CMAQ-v5.3.3/CCTM/scripts/WRF-4.3/test/em_real
    
The default cases represent the standard benchmark cases over the Southeast U.S. with a horizontal resolution of 12 km. See https://www.epa.gov/cmaq/cmaq-inputs-and-test-case-data for details.     
+ Preprocessing tools: MCIP (/home/centos/CMAQ/PREP/mcip), create_omi (/home/centos/CMAQ/PREP/create_omi), BCON (/home/centos/CMAQ/PREP/bcon), ICON (/home/centos/CMAQ/PREP/icon), SMOKE (/home/centos/PREPRO/SMOKE), WPS (/home/centos/PREPRO/WPS), WRF (/home/centos/PREPRO/WPS) 
+ Postprocessing tools: VERDI v2.1, IDV. 
+ The AMI works with AWS-parallelcluster v3.1.3       

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
