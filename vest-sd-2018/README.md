# pdv-sd

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2018-south-dakota-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: SD VEST 2018 File
   - Date accessed: 8/25/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/UBKYRU/5VODZ0&version=45.0
   - File: `sd_2016.zip`
- File: VEST Documentation File, 2018
   - Date accessed: 8/25/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5007790&version=45.0
   - File: `documentation.txt`
- File: SD Precinct-Level Election Results, 2018
  - Date accessed: 8/12/2021
  - Link: http://electionresults.sd.gov/Default.aspx?eid=291
  - Note: Selected 'EXPORT' and downloaded 'Precinct' data for each election
- File: 2020 Redistricting Data Program Final Release (SD Partnership Shapefile)
  - Date accessed: 8/25/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st46_sd.html
  - Note: Downloaded up to 5 at a time

## File processing:

`vest-sd-2018-validation.ipynb` is the script that is the basis of the validation report