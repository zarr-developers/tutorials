# Zarr Interactive Tutorial

👋 Welcome to the Zarr tutorial! This tutorial was created for the 2022 [Cloud-Native Geo Event](https://schedule.cloudnativegeo.org/). It borrows heavily from the [tutorial section of the Zarr docs](https://zarr.readthedocs.io/en/stable/tutorial.html).

[![Binder](https://aws-uswest2-binder.pangeo.io/badge_logo.svg)](
https://aws-uswest2-binder.pangeo.io/v2/gh/pangeo-data/pangeo-docker-images/793b4d0?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fzarr-developers%252Ftutorials%26urlpath%3Dlab%252Ftree%252Ftutorials%252Fzarr_cloud_native_geospatial_2022_blank.ipynb%26branch%3Dmain)

_Level: intermediate python programs. Ideally you are already a bit familiar with Numpy and Xarray._

This will be a live-coding tutorial. You will get the most out of the tutorial if you follow along in a blank notebook and type the code in yourself. 

**Learing Goals**

By the end of this tutorial, you should be able to 

- Identify the fundamental data structures in Zarr (Groups and Arrays) and the key properties of Arrays (shape, dtype, chunks, attributes)
- Create Arrays and Groups in local files or in S3
- Create and edit attributes (metadata)
- Read and write data into Arrays
- Evaluate the tradeoffs of different Array chunking strageies
- Read and write NetCDF-style data to Zarr using Xarray
- Do parallel processing on Xarray / Zarr data using Dask


