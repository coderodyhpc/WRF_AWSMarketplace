GFS DOWNLOAD
===========
Accelerated GFS download is feasible with 2 different tools:
1 - GFS_download.exe will sequentially ask you for the GFS resolution to be downloaded, start date, number of days and if you want to download the first dataset for the following day before starting the GFS files download.
2 - GFS_batch.exe downloads the GFS data based on the arguments to the batch file without having to enter any data interactively. The call to the batch file must follow the folowing syntax:
$ /home/ubuntu/DATA/GFS_batch.exe -r XXX -s YYYYMMDDHH -e YYYYMMDDHH
Here, 'r' is the GFS data resolution (0.25/0.5) where valid entries are 025, 05 and 050, 's' is the starting date that must follow the format (YYYYMMDDHH and 'e' is the end date. Hours (HH) must be 00, 06, 12 or 18.

NAM DOWNLOAD
===========
1 - download_NAM.exe will sequentially ask you for the start date, number of days and if you want to download the first dataset for the following day before starting the NAM files download.
