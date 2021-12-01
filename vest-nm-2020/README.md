# pdv-nm

Our final election results validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2020-new-mexico-precinct-and-election-results/).

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed.

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions, or if you would like to request a full validation report.

## Raw from source

### Accessible files:

- File: NM VEST 2020 File
   - Date accessed: 12/01/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5425599&version=27.0
- File: VEST Documentation File, 2020
   - Date accessed: 12/01/2021
   - Link: https://dataverse.harvard.edu/file.xhtml?fileId=5431956&version=27.0
- File: NM Precinct-Level Election Results, 2020
  - Date accessed: 12/01/2021
  - Link: https://electionresults.sos.state.nm.us/Default.aspx?
  - Note: Selected 'EXPORT' and downloaded 'Precinct Level' data for each election
- File: NM County-Level Election Results, 2020
  - Date accessed: 12/01/2021
  - Link: https://electionresults.sos.state.nm.us/Default.aspx?
  - Note: Selected 'EXPORT' and downloaded 'County Level' data for each election
- File: NM Precinct Shapefiles
  - Date accessed: 12/01/2021
  - Link: https://rgis.unm.edu/rgis6/
  - Note: The two files VEST appears to have used are "New Mexico Voting Districts (VTD) October 2021" and "New Mexico Voting Precincts 2012-2020"

## File processing:

`vest-nm-2020-validation.ipynb` is the script that is the basis of the validation report
