# NYC Open Data Removed Datasets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-open-data-removed-datasets) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/avwh-jmzt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/avwh-jmzt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/avwh-jmzt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | avwh-jmzt |
| Name | NYC Open Data Removed Datasets |
| Category | City Government |
| Created | 2015-08-03T19:53:38Z |
| Publication Date | 2016-06-08T20:50:57Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | time        | plan_year           | Plan Year           | number    | number      |
| Yes      | series tag  | agency              | Agency              | text      | text        |
| Yes      | series tag  | dataset             | Dataset             | text      | text        |
| Yes      | series tag  | dataset_description | Dataset Description | text      | text        |
| Yes      | series tag  | reason_for_removal  | Reason for Removal  | text      | text        |
```

## Time Field

```ls
Value = plan_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:avwh-jmzt l:"NYC Open Data Removed Datasets" t:url=https://data.cityofnewyork.us/api/views/avwh-jmzt

property e:avwh-jmzt t:meta.view v:id=avwh-jmzt v:category="City Government" v:averageRating=0 v:name="NYC Open Data Removed Datasets"

property e:avwh-jmzt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:avwh-jmzt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| plan_year | agency                                       | dataset                                            | dataset_description                                                                                                                                                                                                                                         | reason_for_removal                                                                                                                                                | 
| ========= | ============================================ | ================================================== | =========================================================================================================================================================================================================================================================== | ================================================================================================================================================================= | 
| 2014      | Department of Correction (DOC)               | Aggregate Visits/Visitors                          | Numbers of visitors by day, visits with children                                                                                                                                                                                                            | Does not qualify as a ?public data set? according to Local Law 11 of 2012 (see Notes, pp. 59 )                                                                    | 
| 2014      | Department of Environmental Protection (DEP) | DEP Cross Connection Control Risk Assessment       | This is a guideline for Professional Engineers/Registered Architects for filing Backflow Prevention Device Plans for all property types.                                                                                                                    | Does not qualify as ?data? according to Local Law 11 of 2012 (see Notes, pp. 59)                                                                                  | 
| 2014      | Department of Environmental Protection (DEP) | Sewer Design Standards                             | Standards for sewers, manholes, catch basins, precast manholes, precast catch basins and sewer appurtenances. Those standards are used in the design of capital & private sewer projects                                                                    | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 2014      | Department of Environmental Protection (DEP) | Hydraulic Computation Worksheet Templates          | This is an example worksheet for developing and submitting a Hydraulic Study for DEP approval. A Hydraulic Study is used to analyze the adequacy of an existing sewer to receive sanitary and storm flows generated from an area tributary to the sewer.    | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 2014      | Department of Records (DOR)                  | DORIS Performance Indicators                       | Monthly performance statistics for DORIS Archives and City Hall Library operations                                                                                                                                                                          | Performance indicator already provided in open format ? please refer to Citywide Performance Reporting website (http://www.nyc.gov/html/ops/html/data/data.shtml) | 
| 2014      | Department of Transportation (DOT)           | Manhattan River Crossings Screen line Traffic Flow | Presents vehicular volumes, classification and trends for all bridge and tunnel facilities serving Manhattan River Crossings                                                                                                                                | Merger ? Data is being combined into one set                                                                                                                      | 
| 2014      | Human Resource Administration (HRA)          | Total Homecare Cases                               | Total number of Homecare cases                                                                                                                                                                                                                              | Data is no longer maintained                                                                                                                                      | 
| 2014      | Landmarks Preservation Commission (LPC)      | Demolition / Not a Landmark Letter Request Log     | Spreadsheet containing information pertaining to requests for "not a landmark" letters from the public (usually for assistance in applying for DOB demolition permits); used primarily for mail merge purposes (for producing the letters)                  | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 2014      | Landmarks Preservation Commission (LPC)      | Archaeology Reports                                | Spreadsheet containing descriptive information for archaeological reports filed with LPC including abstracts for each report, the name of the author, date of publication, and borough location; powers the LPC website "Archaeology Reports" search engine | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 2014      | New York Police Department (NYPD)            | Murder in NYC                                      | Written 11 page report                                                                                                                                                                                                                                      | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
```