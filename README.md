# voter_reg_analysis
Example process for determining voter registration potential.  Example area is Legislative District 26 in Arizona. 

resources/az_ld_26 is voter file data per TargetSmart voter file (geographic/demographic only- no PII)

resources/BlockGr is the latest 5 year ACS CVAP data by block group available here: https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html

For Step 2, importing geopandas is neccessary (https://stackoverflow.com/questions/41009215/importerror-no-module-named-geopandas)

Finally, for visualizations at the block group level, shape files are available here: https://www2.census.gov/geo/tiger/TIGER2018/BG/
![AZ](Images/az_ld_26.png)
