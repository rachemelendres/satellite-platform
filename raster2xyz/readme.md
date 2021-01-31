# Raster2xyz

Raster2xyz is a python module that converts the individual pixel values and coordinates of raster image (GeoTIFF) into a CSV format.

## Install

```
pip install raster2xyz
```

## Execut

```
from raster2xyz.raster2xyz import Raster2xyz

input_raster = "input_raster.tif"
out_csv = "/tmp/out_xyz.csv"

rtxyz = Raster2xyz()
rtxyz.translate(input_raster, out_csv)
```
