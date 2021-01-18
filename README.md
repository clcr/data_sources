# data_sources
A repository for GIS data sources; please feel free to add to these using the edit button.

## Cloud-optimised geotifs
Can be used with gdal /vsicurl/\
See github.com/clcr/s2_subset_download

### Sentinel 2 L2A

#### Spec:
https://registry.opendata.aws/sentinel-2-l2a-cogs/

#### Example URL:
http://sentinel-cogs.s3.us-west-2.amazonaws.com/sentinel-s2-l2a-cogs/50/R/KV/2020/7/S2A_50RKV_20200708_0_L2A/B02.tif
	
#### Notes:
Single-band\
Native resolution\
Split by granule and month

### Sentinel 1 L1C

#### Spec:
https://registry.opendata.aws/sentinel-1/

#### Example URL:
/vsis3/sentinel-s1-l1c/GRD/2018/1/11/EW/DH/S1A_EW_GRDH_1SDH_20180111T110409_20180111T110513_020106_02247C_FBAB/measurement/ew-hh.tiff

#### Notes:
COSTS SOME MONEY; AWS account needed\
Note /vsis3/ prefix instead of /vsicurl/\
Need to setup AWS account and `export AWS_REQUEST_PAYER=requester` to consent to payment
Single band GRD\
State of images unclear- needs investigation\
Geolocation surprisingly good\
Need AWS account 

### MODIS veg indicies (and friends)

#### Spec:
https://earthdata.nasa.gov/collaborate/cloud-optimized-geotiffs

#### Example URL:
https://modis-vi-nasa.s3-us-west-2.amazonaws.com/MOD13A1.006/2018.01.17.tif
	
#### Notes
Coarse-resolution\
Each image is worldwide\
Atmospherics\

### Landsat

#### Spec:
https://earthdata.nasa.gov/collaborate/cloud-optimized-geotiffs

#### Example URL:
https://landsat-pds.s3.amazonaws.com/c1/L8/202/025/LC08_L1TP_202025_20200508_20200508_01_RT/LC08_L1TP_202025_20200508_20200508_01_RT_B2.TIF​
	

## Potential COGs
Data providers that advertise the availability of COG data, but we haven't found the access protocol yet.

- Planet
- The CEDA archive
- OpenDroneMap
