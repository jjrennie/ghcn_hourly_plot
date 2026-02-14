# Plot Weather Station Data from GHCN-Hourly
## Written By Jared Rennie (@jjrennie)

Taps into the NCEI Website to get hourly station data for a particular year and then plot a days worth of data. Some bonus plotting fun of Dew Point data will also be had!

The dataset we will be using is from the Global Historical Climatology Network's (GHCN's) hourly dataset, which includes multiple sources of US and international data, including airport data from the ASOS network. If you would like to learn more about this dataset, check out the information below. 

- GHCNh Info: https://www.ncei.noaa.gov/products/global-historical-climatology-network-hourly
- GHCNh Documentation: https://www.ncei.noaa.gov/oa/global-historical-climatology-network/hourly/doc/ghcnh_DOCUMENTATION.pdf

This notebook is designed so you do not have to download any data locally, and with just a few lines of code, you can download data and plots at your fingertips. Let's get into it!

### What You Need

First off, the entire codebase works in Python 3. In addition to base Python, you will need the following packages installed: 
- pandas (to slice annd dice the data)
- matplotlib (to plot the data)
- timezonefinder and pytz (to deal with timezone conversions)
    
The "easiest" way is to install these is by installing <a href='https://www.anaconda.com' target="_blank">anaconda</a>, and then applying <a href='https://conda-forge.org/' target="_blank">conda-forge</a>. Afterward, then you can install the above packages. 

### Importing Packages
Assuming you did the above, it should (in theory) import everything no problem:

### Launch right now with Binder!
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjrennie/ghcn_hourly_plot/HEAD?urlpath=%2Fdoc%2Ftree%2Fghcnh_plot_parquet.ipynb)
