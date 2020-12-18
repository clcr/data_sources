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
