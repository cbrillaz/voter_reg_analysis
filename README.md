# Example method for determining "voter registration potential" within a given geographic area.  
The following documents an example process for determining voter registration potential. In this example I look at Legislative District 26 in Arizona (ASU). The file 1- Match Datasets.ipynb uses an extract of the voterbase file along with American Community Survey CVAP data released at the census block level.  After pulling both data sources I merge the two the and compare the results.  The /Output directory contains the census block group file. 

The directory resources/az_ld_26 is voter file data per TargetSmart voter file (geographic/demographic only- no PII)

The directory resources/BlockGr is the latest 5 year ACS CVAP data by block group available here: https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html

For step 2 i took a crack at creating a map of LD 26 registration. If you would like to create the map yourself importing geopandas is neccessary (https://stackoverflow.com/questions/41009215/importerror-no-module-named-geopandas) Otherwise an image of the map is available in the /Images directory

Finally, for shape files at the block group level, I obtained those here: https://www2.census.gov/geo/tiger/TIGER2018/BG/
