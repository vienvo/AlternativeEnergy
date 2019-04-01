# AlternativeEnergy
Where are the best locations to build wind farms? 

## Procedure for running:
-  First, be sure that the individual station files appear within a folder called AlternativeEnergy/data/rawdata/weatherstations.  They need to be manually placed there because even zipped up, they would exceed Github's size limit.
-  Run these notebooks under notebooks/Steve in the following order:
    -  inventory_select
    -  weatherdata_select
    -  find_weatherdata_values
    -  parse_station_data
-  Data_Sourcing.ipynb is primarily a markdown notebook offering a summary of this process.  Also available is a dataflow.png diagram located in AlternativeEnergy/data.
