# zonalstats_to_raster
Python script for calculating Zonal Statistics and outputting to raster

Prerequisites:
A number of packages are required for the below script to work - some of these packages are dependent on gdal.

The easiest way to get started is to use Anaconda to create a new environment:
  conda create -n raster python=3.7
  conda install -n raster gdal

From there, you can use conda/pip to install the remainder of the packages:

-rasterio
-rasterstats
-descartes
-mapclassify
-geopandas
-fiona
-shapely
-matplotlib
