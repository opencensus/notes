# Collaborative Census Containers with Dat

![Dat Container](/imgs/dat.jpg?raw=true "Dat Container")

* Raw census data (files)
    - 1 csv file for Census data for ACS5 at each level with all columns.
    - 1 shapefile for geographies at each level
    - Schema? Where does schema and variables description live
* Cleaning/Analysis Scripts (files)
    - How to tie files to specific csv things. Need to load csv file from same dat, etc.
* Collaborative Data (tables)
    - Tables with specific goal/measure (e.g. segregation in cities)
    - How to tie tables to scripts, csv files, schemas.

*Is each dat per year, or per dataset/year (e.g. SF1, SF3, ACS5, etc.)*

Questions:

* Where to store script that downloads raw data?
*  How much data goes into one Dat container?
*  Should raw data be separate dat from other stuff w/ a dependency for “collaborative tables”?
* Can scripts be dat-aware? Eg. know when they are in a dat and where to find data?
* Data dependency vs single dat size & complexity issue
