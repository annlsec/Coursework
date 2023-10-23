2020 Presidential Results on Nationwide 2020 Census Blocks

## RDH Date Retrieval
04/26/23

## Sources
Election data originally sourced from VEST, disaggregation performed by RDH

## Fields:
Field Name Description                                                   
GEOID20    Census Block GEOID                                            
STATEAB    State Abbreviation                                            
COUNTYFP20 County FIP Code of Census Block                                              
COUNTY     County Name of Census Block                                                    
PRECINCT   Precinct Identifier                                           
TOT_POP    Total Pop. from 2020 Census                                   
VAP_MOD    Voting Age Pop. minus Adult Incarcerated Pop. from 2020 Census
G20PREDBID Election results for Joseph Biden (Democratic Party)          
G20PRELJOR Election results for Jo Jorgensen (Libertarian Party)         
G20PRERTRU Election results for Donald Trump (Republican Party)          

## Processing Steps
Visit the RDH GitHub and the processing script for this code [here](https://github.com/nonpartisan-redistricting-datahub/national_elections)

## Additional Notes
Data is included for all 50 states and Washington, DC. 

Disaggregation is performed using a block's percentage of total VAP_MOD across all the census blocks with the largest part of their area contained within a particular precinct.

Due to minor alignment issues, there may be instances in which the county name, as contained in the "PRECINCT" field, does not match that of the "COUNTY" field, which is the name of the county the block is contained in.

Please direct questions related to processing this dataset to info@redistrictingdatahub.org.
