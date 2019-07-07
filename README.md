# Example method for determining "voter registration potential" within a given geographic area.  
The following documents an example process for determining voter registration potential. In this example I look at Legislative District 26 in Arizona (ASU). I use the voterbase file along with ACS CVAP data released at the census block level.  I then merge the datasets and compare the results.  The /Output directory contains the census block group file.   

resources/az_ld_26 is voter file data per TargetSmart voter file (geographic/demographic only- no PII)

resources/BlockGr is the latest 5 year ACS CVAP data by block group available here: https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html

For Step 2, if you would like to create the map yourself importing geopandas is neccessary (https://stackoverflow.com/questions/41009215/importerror-no-module-named-geopandas) Otherwise an image of the map is available in the /Images directory

Finally, for visualizations at the block group level, shape files are available here: https://www2.census.gov/geo/tiger/TIGER2018/BG/
