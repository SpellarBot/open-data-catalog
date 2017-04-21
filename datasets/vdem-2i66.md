# 2016 NYC Open Data Plan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-nyc-open-data-plan) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vdem-2i66) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vdem-2i66/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vdem-2i66/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vdem-2i66 |
| Name | 2016 NYC Open Data Plan |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | 2016 nyc open data plan, local law 11 of 2012, compliance, july 15 |
| Created | 2016-07-15T15:27:29Z |
| Publication Date | 2017-02-16T23:19:52Z |

## Description

This inventory includes all data sets scheduled for release between July 2016 and December 31, 2018.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | agency              | Agency              | text          | text          |
| Yes      | series tag  | data_set_title      | Data Set Title      | text          | text          |
| Yes      | series tag  | dataset_description | Dataset Description | text          | text          |
| Yes      | series tag  | update_frequency    | Update Frequency    | text          | text          |
| Yes      | time        | release_date        | Release Date        | calendar_date | calendar_date |
| No       |             | date_status         | Date Status         | text          | text          |
| Yes      | series tag  | agency_comment      | Agency Comment      | text          | text          |
```

## Time Field

```ls
Value = release_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_status
```

## Data Commands

```ls
series e:vdem-2i66 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset_description="NYC highways that receive a cleanliness rating of good (%)." t:data_set_title="Adopted Highway Service Ratings" t:agency="Department of Transportation (DOT)" t:agency_comment="Additional data quality review required" m:row_number.vdem-2i66=1

series e:vdem-2i66 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset_description="Bicycle network connectivity index." t:data_set_title="Bicycle network connectivity index" t:agency="Department of Transportation (DOT)" t:agency_comment="Additional data quality review required" m:row_number.vdem-2i66=2

series e:vdem-2i66 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset_description="Bridges rated good or very good (%) (calendar year)." t:data_set_title="Bridge ratings" t:agency="Department of Transportation (DOT)" t:agency_comment="Additional data quality review required" m:row_number.vdem-2i66=3
```

## Meta Commands

```ls
metric m:row_number.vdem-2i66 p:long l:"Row Number"

entity e:vdem-2i66 l:"2016 NYC Open Data Plan" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/vdem-2i66

property e:vdem-2i66 t:meta.view v:id=vdem-2i66 v:category="City Government" v:averageRating=0 v:name="2016 NYC Open Data Plan" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:vdem-2i66 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vdem-2i66 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency                                  | data_set_title                           | dataset_description                                                                                                   | update_frequency | release_date        | date_status | agency_comment                                       | 
| ======================================= | ======================================== | ===================================================================================================================== | ================ | =================== | =========== | ==================================================== | 
| Department of Transportation (DOT)      | Adopted Highway Service Ratings          | NYC highways that receive a cleanliness rating of good (%).                                                           | To Be Determined | 2016-07-15T00:00:00 | Updated     | Additional data quality review required              | 
| Department of Transportation (DOT)      | Bicycle network connectivity index       | Bicycle network connectivity index.                                                                                   | To Be Determined | 2016-07-15T00:00:00 | Updated     | Additional data quality review required              | 
| Department of Transportation (DOT)      | Bridge ratings                           | Bridges rated good or very good (%) (calendar year).                                                                  | To Be Determined | 2016-07-15T00:00:00 | Updated     | Additional data quality review required              | 
| Department of Transportation (DOT)      | Pothole work orders                      | Average time to close a pothole work order where repair was done (days).                                              | To Be Determined | 2016-07-15T00:00:00 | Updated     | Under review ? privacy or sensitivity considerations | 
| Department of Transportation (DOT)      | Future Protected Streets - Intersections | List of Future Protected Streets for intersections.                                                                   | Daily            | 2016-07-15T00:00:00 | New         |                                                      | 
| Department of Transportation (DOT)      | Future Protected Streets - Segments      | List of Future Protected Streets for segments.                                                                        | Daily            | 2016-07-15T00:00:00 | New         |                                                      | 
| Department of Transportation (DOT)      | Protected Streets - Intersections        | Current list of Protected Streets for intersections.                                                                  | Daily            | 2016-07-15T00:00:00 | New         |                                                      | 
| Department of Transportation (DOT)      | Protected Streets - Segments             | Current list of Protected Streets for segments.                                                                       | Daily            | 2016-07-15T00:00:00 | New         |                                                      | 
| New York City Housing Authority (NYCHA) | Electric Consumption and Cost            | Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information. | Quarterly        | 2016-07-15T00:00:00 | New         |                                                      | 
| New York City Housing Authority (NYCHA) | Water Consumption and Cost               | Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information. | Quarterly        | 2016-07-15T00:00:00 | New         |                                                      | 
```