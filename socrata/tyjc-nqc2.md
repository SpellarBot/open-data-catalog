# NYC Open Data Plan - Scheduled Releases 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-open-data-plan-scheduled-releases-2014-ab625) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tyjc-nqc2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tyjc-nqc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tyjc-nqc2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tyjc-nqc2 |
| Name | NYC Open Data Plan - Scheduled Releases 2016 |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | open data, scheduled releases, datasets |
| Created | 2014-07-16T14:57:43Z |
| Publication Date | 2016-09-20T23:08:14Z |

## Description

This inventory includes all datasets scheduled for release between July 2016 and December 31, 2018.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | agency               | Agency               | text          | text          |
| Yes      | series tag  | dataset              | Dataset              | text          | text          |
| Yes      | series tag  | dataset_description  | Dataset Description  | text          | text          |
| Yes      | series tag  | update_frequency     | Update Frequency     | text          | text          |
| Yes      | time        | planned_release_date | Planned Release Date | calendar_date | calendar_date |
| Yes      | series tag  | link                 | Link                 | text          | text          |
```

## Time Field

```ls
Value = planned_release_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tyjc-nqc2 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset="Adopted Highway Service Ratings" t:link=https://data.cityofnewyork.us/Transportation/Adopted-Highway-Service-Ratings-Adopt-a-Highway-Hi/dte3-kvx7 t:dataset_description="NYC highways that receive a cleanliness rating of good (%)." t:agency="Department of Transportation (DOT)" m:row_number.tyjc-nqc2=1

series e:tyjc-nqc2 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset="Bicycle network connectivity index" t:link=https://data.cityofnewyork.us/Transportation/Bicycle-Network-Connectivity-Index/d9fg-z42k t:dataset_description="Bicycle network connectivity index." t:agency="Department of Transportation (DOT)" m:row_number.tyjc-nqc2=2

series e:tyjc-nqc2 d:2016-07-15T00:00:00.000Z t:update_frequency="To Be Determined" t:dataset="Bridge ratings" t:link=https://data.cityofnewyork.us/Transportation/Bridge-Ratings/9dux-uz3w t:dataset_description="Bridges rated good or very good (%) (calendar year)." t:agency="Department of Transportation (DOT)" m:row_number.tyjc-nqc2=3
```

## Meta Commands

```ls
metric m:row_number.tyjc-nqc2 p:long l:"Row Number"

entity e:tyjc-nqc2 l:"NYC Open Data Plan - Scheduled Releases 2016" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/tyjc-nqc2

property e:tyjc-nqc2 t:meta.view v:id=tyjc-nqc2 v:category="City Government" v:averageRating=0 v:name="NYC Open Data Plan - Scheduled Releases 2016" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:tyjc-nqc2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tyjc-nqc2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency                                  | dataset                                  | dataset_description                                                                                                   | update_frequency | planned_release_date | link                                                                                                      | 
| ======================================= | ======================================== | ===================================================================================================================== | ================ | ==================== | ========================================================================================================= | 
| Department of Transportation (DOT)      | Adopted Highway Service Ratings          | NYC highways that receive a cleanliness rating of good (%).                                                           | To Be Determined | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Adopted-Highway-Service-Ratings-Adopt-a-Highway-Hi/dte3-kvx7 | 
| Department of Transportation (DOT)      | Bicycle network connectivity index       | Bicycle network connectivity index.                                                                                   | To Be Determined | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Bicycle-Network-Connectivity-Index/d9fg-z42k                 | 
| Department of Transportation (DOT)      | Bridge ratings                           | Bridges rated good or very good (%) (calendar year).                                                                  | To Be Determined | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Bridge-Ratings/9dux-uz3w                                     | 
| Department of Transportation (DOT)      | Pothole work orders                      | Average time to close a pothole work order where repair was done (days).                                              | To Be Determined | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Pothole-Work-Orders-Closed/psde-rqze                         | 
| Department of Transportation (DOT)      | Future Protected Streets - Intersections | List of Future Protected Streets for intersections.                                                                   | Daily            | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Future-Protected-Streets-Intersections/yupw-u2ax             | 
| Department of Transportation (DOT)      | Future Protected Streets - Segments      | List of Future Protected Streets for segments.                                                                        | Daily            | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Future-Protected-Streets-Segments/pnij-y7y6                  | 
| Department of Transportation (DOT)      | Protected Streets - Intersections        | Current list of Protected Streets for intersections.                                                                  | Daily            | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Protected-Streets-Intersections/hfa3-euj3                    | 
| Department of Transportation (DOT)      | Protected Streets - Segments             | Current list of Protected Streets for segments.                                                                       | Daily            | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Transportation/Protected-Streets-Segments/9p9k-tusd                         | 
| New York City Housing Authority (NYCHA) | Electric Consumption and Cost            | Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information. | Quarterly        | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Housing-Development/Electric-Consumption-And-Cost-2016/sd8e-3ugp            | 
| New York City Housing Authority (NYCHA) | Water Consumption and Cost               | Monthly consumption and cost data by borough and development. Data set includes utility vendor and meter information. | Quarterly        | 2016-07-15T00:00:00  | https://data.cityofnewyork.us/Housing-Development/Water-Consumption-And-Cost-2012-2016/66be-66yr          | 
```