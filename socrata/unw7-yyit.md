# NYC Open Data Plan - List Of Datasets Removed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-open-data-plan-list-of-datasets-removed-03693) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/unw7-yyit) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/unw7-yyit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/unw7-yyit/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | unw7-yyit |
| Name | NYC Open Data Plan - List Of Datasets Removed |
| Attribution | Department of Information Technology & Telecommunications(DoITT) |
| Category | City Government |
| Tags | deleted, dataset, compliance, plan, nyc open data, doitt |
| Created | 2014-07-16T14:29:05Z |
| Publication Date | 2014-07-17T14:18:29Z |

## Description

This inventory includes all items removed from the Open Data Plan. The reason for removal is documented for each item removed.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | agency              | Agency              | text      | text        |
| Yes      | series tag  | dataset             | Dataset             | text      | text        |
| Yes      | series tag  | dataset_description | Dataset Description | text      | text        |
| Yes      | series tag  | reason_for_removal  | Reason for Removal  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:unw7-yyit d:2014-07-16T07:29:13.000Z t:reason_for_removal="Does not qualify as a ?public data set? according to Local Law 11 of 2012 (see Notes, pp. 59 )" t:dataset="Aggregate Visits/Visitors" t:dataset_description="Numbers of visitors by day, visits with children" t:agency="Department of Correction (DOC)" m:row_number.unw7-yyit=1

series e:unw7-yyit d:2014-07-16T07:29:13.000Z t:reason_for_removal="Does not qualify as ?data? according to Local Law 11 of 2012 (see Notes, pp. 59)" t:dataset="DEP Cross Connection Control Risk Assessment" t:dataset_description="This is a guideline for Professional Engineers/Registered Architects for filing Backflow Prevention Device Plans for all property types." t:agency="Department of Environmental Protection (DEP)" m:row_number.unw7-yyit=2

series e:unw7-yyit d:2014-07-16T07:29:13.000Z t:reason_for_removal="Does not qualify as ?data? according to Local Law 11 of 2012" t:dataset="Sewer Design Standards" t:dataset_description="Standards for sewers, manholes, catch basins, precast manholes, precast catch basins and sewer appurtenances. Those standards are used in the design of capital & private sewer projects" t:agency="Department of Environmental Protection (DEP)" m:row_number.unw7-yyit=3
```

## Meta Commands

```ls
metric m:row_number.unw7-yyit p:long l:"Row Number"

entity e:unw7-yyit l:"NYC Open Data Plan - List Of Datasets Removed" t:attribution="Department of Information Technology & Telecommunications(DoITT)" t:url=https://data.cityofnewyork.us/api/views/unw7-yyit

property e:unw7-yyit t:meta.view v:id=unw7-yyit v:category="City Government" v:averageRating=0 v:name="NYC Open Data Plan - List Of Datasets Removed" v:attribution="Department of Information Technology & Telecommunications(DoITT)"

property e:unw7-yyit t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:unw7-yyit t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency                                       | dataset                                            | dataset_description                                                                                                                                                                                                                                         | reason_for_removal                                                                                                                                                | 
| =========== | ============================================ | ================================================== | =========================================================================================================================================================================================================================================================== | ================================================================================================================================================================= | 
| 1405495753  | Department of Correction (DOC)               | Aggregate Visits/Visitors                          | Numbers of visitors by day, visits with children                                                                                                                                                                                                            | Does not qualify as a ?public data set? according to Local Law 11 of 2012 (see Notes, pp. 59 )                                                                    | 
| 1405495753  | Department of Environmental Protection (DEP) | DEP Cross Connection Control Risk Assessment       | This is a guideline for Professional Engineers/Registered Architects for filing Backflow Prevention Device Plans for all property types.                                                                                                                    | Does not qualify as ?data? according to Local Law 11 of 2012 (see Notes, pp. 59)                                                                                  | 
| 1405495753  | Department of Environmental Protection (DEP) | Sewer Design Standards                             | Standards for sewers, manholes, catch basins, precast manholes, precast catch basins and sewer appurtenances. Those standards are used in the design of capital & private sewer projects                                                                    | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 1405495753  | Department of Environmental Protection (DEP) | Hydraulic Computation Worksheet Templates          | This is an example worksheet for developing and submitting a Hydraulic Study for DEP approval. A Hydraulic Study is used to analyze the adequacy of an existing sewer to receive sanitary and storm flows generated from an area tributary to the sewer.    | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 1405495753  | Department of Records (DOR)                  | DORIS Performance Indicators                       | Monthly performance statistics for DORIS Archives and City Hall Library operations                                                                                                                                                                          | Performance indicator already provided in open format ? please refer to Citywide Performance Reporting website (http://www.nyc.gov/html/ops/html/data/data.shtml) | 
| 1405495753  | Department of Transportation (DOT)           | Manhattan River Crossings Screen line Traffic Flow | Presents vehicular volumes, classification and trends for all bridge and tunnel facilities serving Manhattan River Crossings                                                                                                                                | Merger ? Data is being combined into one set                                                                                                                      | 
| 1405495753  | Human Resource Administration (HRA)          | Total Homecare Cases                               | Total number of Homecare cases                                                                                                                                                                                                                              | Data is no longer maintained                                                                                                                                      | 
| 1405495753  | Landmarks Preservation Commission (LPC)      | Demolition / Not a Landmark Letter Request Log     | Spreadsheet containing information pertaining to requests for "not a landmark" letters from the public (usually for assistance in applying for DOB demolition permits); used primarily for mail merge purposes (for producing the letters)                  | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 1405495753  | Landmarks Preservation Commission (LPC)      | Archaeology Reports                                | Spreadsheet containing descriptive information for archaeological reports filed with LPC including abstracts for each report, the name of the author, date of publication, and borough location; powers the LPC website "Archaeology Reports" search engine | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
| 1405495753  | New York Police Department (NYPD)            | Murder in NYC                                      | Written 11 page report                                                                                                                                                                                                                                      | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                      | 
```