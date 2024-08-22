# Raster Data Processing in Relational Database Management Systems

This research project is done as part of the master's curriculum of RCSE at TU Ilmenau and focuses on acquiring, processing, and organizing raster data within the DuckDB environment, with an emphasis on spatio-temporal datasets.

## Methodology

First, the ERA5 dataset from the Climate Data Store website was accessed using the CDS API client. The dataset, originally in netCDF4 format, was then converted into Zarr and Parquet formats for more efficient storage within DuckDB. Afterward, three different relational-raster mappings based on the original table, the third normal form, and region approaches were implemented to explore various data organization strategies. Finally, a set of predefined queries was created to evaluate and compare the efficiency and performance of these relational-raster mappings, with the goal of identifying the optimal strategy.
