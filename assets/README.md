# Description

This directory contains three main files: 1) `coord_wrf_idx.ncl`, 2) `coord_XLAT_XLONG_conus_i.nc`, and 3) `coord_XLAT_XLONG_conus_ii.sh`. The first is a simple [NCL](https://www.ncl.ucar.edu/get_started.shtml) script that extracts the indices of the latitude and logitude limits given by the `extract-dataset.sh` script. The second is the NetCDF file containing necessary coordinate variables of the [`WRF-CONUSI`](../conus_i) dataset. And the third NetCDF file contains the coordinate variables for the [`WRF-CONUSII`](../conus_ii) dataset.
