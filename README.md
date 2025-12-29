PRISM Climate data are no longer available for manual bulk download, particularly the daily raster products for the newer 800 m resolution datasets. Because I needed to download large volumes of daily data across multiple years and date ranges, following their instructions I put together a Python workflow in a Jupyter Notebook to automate the process.

The code downloads PRISM daily climate data in bulk, organizes the files by variable, and automatically extracts the raster files along with their associated supporting files into structured folders.

**The workflow requires changing only three inputs:**

The local output directory

The date range

The PRISM variable(s) of interest

After setting these parameters, the notebook will download daily PRISM climate rasters for the entire CONUS directly to your local machine.

This repository is intended to simplify and standardize bulk access to PRISM daily climate data for research and analysis.
