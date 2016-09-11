# GDAL-Point-Extraction-for-Environmental-Raster-Data

The following code is for pulling the pixel data by lat/long coordinates from environmental raster datasets provided by the USGS: 1) annual maximum green vegetation fraction derived NDVI (normalized difference vegetation index) satellite data; and 2) land cover type (Water, Mixed Forest, Grasslands, Urban & Built Up, etc.) Understanding the geographic distribution of vegetation and environmental resources is crucial for planning and sustainable design strategies. 

The code pulls data from the following .tif maps: 1 km MODIS-based Maximum Green Vegetation Fraction (http://landcover.usgs.gov/green_veg.php) and 0.5 km MODIS-based Global Land Cover Climatology (http://landcover.usgs.gov/global_climatology.php).

NOTE: Make sure to set the GDAL_DATA environment data. Since I installed GDAL with Anacanda, before executing the python file from terminal I ran:

export GDAL_DATA=/austinarrington/anaconda2/share/gdal
