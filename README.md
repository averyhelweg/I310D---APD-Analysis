# I310D-APD-Analysis

#### This is the link to where I found the original/raw data set that I started my analysis with. I wasn't able to upload it because the original file was too large to be uploaded.
###### https://data.austintexas.gov/Public-Safety/Crime-Reports/fdj4-gpfu/data

#### Project Summary - 
##### The main goal of my project was to find the top 5 most occurring offenses in my zip code so that I could better understand the crime that most frequently happens in my area. The license of my data is the MIT license and the source data has a public domain license. There are some known potential issues with the data. The data is updated so frequently that the analysis may be different weeks, months, or years from now. The other potential issue I wanted to highlight was that according to the Austin Police Department, "Due to the methodological differences in data collection, different data sources may produce different results." After conducting my analysis I believe the most important part of my data is that it allows me to better understand the reality of what happens where I live. When you think about the top 5 highest offenses in my zip code, what you have to understand is that I live in close proximity to a major university and for the data to show that the top 5 were as follows: burglary of vehicle, theft, criminal mischief, theft of bicycle, and public intoxication, in that order.

#### Data type and description for each attribute in my data -

##### column_a          -                integer   -    The number of the entry
##### incident_number         -          integer   -    Incident Report Number
##### highest_offense_description   -    string    -    Description of the offense committed
##### highest_offense_code      -        integer   -    The code of the offense that was committed
##### family_violence         -          string    -    Incident involves family violence? Y = yes, N = no
##### occurred_date           -          date     -     Date the incident occurred
##### location_type           -          string    -    General description of the premise where the incident occurred
##### address            -               string   -     Incident location
##### zip_code             -             decimal   -    Zip code where incident occurred
##### council_district        -          decimal   -    Austin city council district where the incident occurred
##### apd_sector           -             string    -    APD sector where incident occurred
##### apd_district         -             string    -    APD district where incident occurred
##### pra               -                integer   -    APD police reporting area where incident occurred
##### clearance_status        -          string    -    How/whether crime was solved (see clearance lookup)
##### clearance_date          -          date    -      Date crime was solved
##### category_description      -        string    -    Description for the most serious crimes identified by the FBI as part of its Uniform Crime Reporting program

#### Data.world for this analysis -
###### https://data.world/aphelweg/hds310d-apd-analysis
