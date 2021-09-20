# pdv-nm

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-new-mexico-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report. 

## Raw from source

### Accessible files:

- File: NM VEST 2016 File
   - Date accessed: 08/17/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?persistentId=doi:10.7910/DVN/NH5S2I/GYKA9U&version=67.0
   - File: `nm_2016.zip`
- File: VEST documentation File, 2016
   - Date accessed: 08/17/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5007728&version=67.0
   - File: `documentation.txt`
- File: NM Precinct-Level Election Results, 2016
  - Date accessed: 08/17/2021
  - Link: https://electionresults.sos.state.nm.us/?eid=84
  - Note: Selected 'EXPORT' and downloaded 'Precinct' data for each election
- File: NM Precinct Shapefiles
  - Date accessed: 09/17/2021
  - Link: https://www.nmlegis.gov/Redistricting/
- File: 2020 Redistricting Data Program Final Release (NM Partnership Shapefile)
  - Date accessed: 8/17/2021
  - Link: https://www.census.gov/geo/partnerships/pvs/partnership19v2/st35_nm.html
  - Note: Downloaded files for Lincoln, Los Alamos, McKinley, Sandoval, and Socorro counties

## File processing:

`vest-nm-2016-validation.ipynb` is the script that is the basis of the validation report
