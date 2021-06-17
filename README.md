# s3-sadness
S3 issues in USGS CHS dev-et-data bucket

## xarray time series pixelrod selection - very slow from s3
- works reasonably well from disk - netcdf examples
- needed for ET model evaluation among other applications lcmap pyccd etc...

## S3 permission problem NLCD compositing

- some rcloned data now gets a permision error
	- rclone problem?
	- why not 0% or 100%
- develop a test notebook to identify which scenes can be viewed and which cannot
- look at objects in gui AWS console to identify differences
