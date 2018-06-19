# 2016 NYC Open Data Plan - FOIL Reporting Metrics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-nyc-open-data-plan-foil-reporting-metrics) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a5ru-ygsr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a5ru-ygsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a5ru-ygsr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a5ru-ygsr |
| Name | 2016 NYC Open Data Plan - FOIL Reporting Metrics |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Tags | 2016 nyc open data plan - foil reporting metrics, compliance plan |
| Created | 2016-07-14T22:42:01Z |
| Publication Date | 2016-09-20T23:17:15Z |

## Description

Agency FOIL reporting as per Local 7 of 2016.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                | Name                                                                                                                      | Data Type | Render Type |
| ======== | ============== | ========================================================================================================================= | ========================================================================================================================= | ========= | =========== |
| Yes      | series tag     | agency_name                                                                                                               | Agency Name                                                                                                               | text      | text        |
| Yes      | numeric metric | the_total_number_of_foil_responses_that_included_the_release_of_data                                                      | The total number of FOIL responses that included the release of data                                                      | number    | number      |
| Yes      | numeric metric | the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal | The total number of FOIL responses that included a public data set that had not yet been included on the open data portal | number    | number      |
| Yes      | numeric metric | the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal                 | The total number of FOIL responses that resulted in data being posted voluntarily on the open data portal                 | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a5ru-ygsr d:2016-01-01T00:00:00.000Z t:agency_name="Administration for Children?s Services (ACS)" m:the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal=0 m:the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal=0 m:the_total_number_of_foil_responses_that_included_the_release_of_data=0

series e:a5ru-ygsr d:2016-01-01T00:00:00.000Z t:agency_name="Business Integrity Commission (BIC)" m:the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal=0 m:the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal=3 m:the_total_number_of_foil_responses_that_included_the_release_of_data=55

series e:a5ru-ygsr d:2016-01-01T00:00:00.000Z t:agency_name="Civil Service Commission (CSC)" m:the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal=0 m:the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal=0 m:the_total_number_of_foil_responses_that_included_the_release_of_data=1
```

## Meta Commands

```ls
metric m:the_total_number_of_foil_responses_that_included_the_release_of_data p:integer l:"The total number of FOIL responses that included the release of data" d:"This is the number of FOIL responses that contained the release of ?data? as defined by ? 23-501(b) of the Administrative Code. ?Data? released under this category may include ?public data sets,? as defined by ? 23-501(g) of the Administrative Code that has not yet been uploaded onto the open data portal. ?Data? released under this category may also include information that does not fall under the definition of ?public data set.? For example, ?data? may include information that is not maintained on a computer system or database and is only maintained on one person?s computer, or information that contains personally identifiable information." t:dataTypeName=number

metric m:the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal p:integer l:"The total number of FOIL responses that included a public data set that had not yet been included on the open data portal" d:"This number includes the number of FOIL responses that contained the release of information that falls under the definition of ?public data sets.? Release of information under this category may include ?public data sets? that are already listed in the compliance plan for future inclusion on the open data portal." t:dataTypeName=number

metric m:the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal p:integer l:"The total number of FOIL responses that resulted in data being posted voluntarily on the open data portal" d:"This number includes the number data sets that were ?voluntarily? posted. ?Voluntarily? posted data is data that does not fall under the definition of ?public data sets,? but that the agency nonetheless posts on the open data portal." t:dataTypeName=number

entity e:a5ru-ygsr l:"2016 NYC Open Data Plan - FOIL Reporting Metrics" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/a5ru-ygsr

property e:a5ru-ygsr t:meta.view v:id=a5ru-ygsr v:averageRating=0 v:name="2016 NYC Open Data Plan - FOIL Reporting Metrics" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:a5ru-ygsr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a5ru-ygsr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency_name                                           | the_total_number_of_foil_responses_that_included_the_release_of_data | the_total_number_of_foil_responses_that_included_a_public_data_set_that_had_not_yet_been_included_on_the_open_data_portal | the_total_number_of_foil_responses_that_resulted_in_data_being_posted_voluntarily_on_the_open_data_portal | 
| ===================================================== | ==================================================================== | ========================================================================================================================= | ========================================================================================================= | 
| Administration for Children?s Services (ACS)          | 0                                                                    | 0                                                                                                                         | 0                                                                                                         | 
| Business Integrity Commission (BIC)                   | 55                                                                   | 3                                                                                                                         | 0                                                                                                         | 
| Civil Service Commission (CSC)                        | 1                                                                    | 0                                                                                                                         | 0                                                                                                         | 
| Commission on Human Rights (CCHR)                     | 0                                                                    | 0                                                                                                                         | 0                                                                                                         | 
| Conflicts of Interest Board (COIB)                    | 0                                                                    | 0                                                                                                                         | 0                                                                                                         | 
| Department for the Aging (DFTA)                       | 29                                                                   | 0                                                                                                                         | 0                                                                                                         | 
| Department of City Planning (DCP)                     | 2                                                                    | 0                                                                                                                         | 0                                                                                                         | 
| Department of Citywide Administrative Services (DCAS) | 195                                                                  | 188                                                                                                                       | 0                                                                                                         | 
| Department of Consumer Affairs (DCA)                  | 661                                                                  | 93                                                                                                                        | 0                                                                                                         | 
| Department of Corrections (DOC)                       | 571                                                                  | 2                                                                                                                         | 0                                                                                                         | 
```