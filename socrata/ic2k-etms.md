# Social Indicators Report Data By Neighborhood Tabulation Districts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/social-indicators-report-data-by-neighborhood-tabulation-districts) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ic2k-etms) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ic2k-etms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ic2k-etms/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ic2k-etms |
| Name | Social Indicators Report Data By Neighborhood Tabulation Districts |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | Social Services |
| Tags | ceo, moo, indicators, social conditions |
| Created | 2016-04-13T15:57:04Z |
| Publication Date | 2016-04-25T21:24:03Z |

## Description

Select metrics by Community District/Neighborhood Tabulation Districts  where available. To see the full set of indicators (including those without CD/NTD level data), please refer to ?Social Indicators Report Data ? Citywide? at https://data.cityofnewyork.us/Social-Services/Social-Indicators-Report-Data-Citywide/gysw-j2f3.

The Social Indicators Report is an analysis of social conditions across New York City, including geographic and demographic breakdowns, changes over time, and the Mayor's plan for responding to problems highlighted in the report. The report can be found at http://www1.nyc.gov/assets/operations/downloads/pdf/Social-Indicators-Report-April-2016.pdf. See also, the recently released Disparity Report produced by the Center for Innovation through Data Intelligence (CIDI). The report can be found at http://www1.nyc.gov/assets/operations/downloads/pdf/Social-Indicators-Report-April-2016.pdf

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | domain      | Domain     | text      | text        |
| Yes      | series tag     | indicator   | Indicator  | text      | text        |
| Yes      | series tag     | geoid       | GeoID      | text      | text        |
| Yes      | series tag     | 2011        | 2011       | text      | text        |
| Yes      | series tag     | 2012        | 2012       | text      | text        |
| Yes      | numeric metric | 2013        | 2013       | number    | text        |
| Yes      | series tag     | 2014        | 2014       | text      | text        |
| Yes      | series tag     | 2015        | 2015       | text      | text        |
| Yes      | series tag     | definition  | Definition | text      | text        |
| Yes      | series tag     | source      | Source     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ic2k-etms d:2016-04-25T14:23:03.000Z t:indicator="Mean Travel Time to Work (2009-2013)" t:source="U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov" t:definition="Mean travel time for workers 16 years and over who did not work at home." t:2014=* t:2015=* t:2012=* t:domain="Core Infrastructure & the Environment" t:2011=* t:geoid="BX01 Claremont-Bathgate" m:2013=45.7

series e:ic2k-etms d:2016-04-25T14:23:03.000Z t:indicator="Mean Travel Time to Work (2009-2013)" t:source="U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov" t:definition="Mean travel time for workers 16 years and over who did not work at home." t:2014=* t:2015=* t:2012=* t:domain="Core Infrastructure & the Environment" t:2011=* t:geoid="BX03 Eastchester-Edenwald-Baychester" m:2013=44.6

series e:ic2k-etms d:2016-04-25T14:23:03.000Z t:indicator="Mean Travel Time to Work (2009-2013)" t:source="U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov" t:definition="Mean travel time for workers 16 years and over who did not work at home." t:2014=* t:2015=* t:2012=* t:domain="Core Infrastructure & the Environment" t:2011=* t:geoid="BX05 Bedford Park-Fordham North" m:2013=41.9
```

## Meta Commands

```ls
metric m:2013 p:float l:2013 t:dataTypeName=number

entity e:ic2k-etms l:"Social Indicators Report Data By Neighborhood Tabulation Districts" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/ic2k-etms

property e:ic2k-etms t:meta.view v:id=ic2k-etms v:category="Social Services" v:averageRating=0 v:name="Social Indicators Report Data By Neighborhood Tabulation Districts" v:attribution="Mayor's Office of Operations (OPS)"

property e:ic2k-etms t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ic2k-etms t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | domain                                | indicator                            | geoid                                                | 2011 | 2012 | 2013 | 2014 | 2015 | definition                                                               | source                                                                                                     | 
| =========== | ===================================== | ==================================== | ==================================================== | ==== | ==== | ==== | ==== | ==== | ======================================================================== | ========================================================================================================== | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX01 Claremont-Bathgate                              | *    | *    | 45.7 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX03 Eastchester-Edenwald-Baychester                 | *    | *    | 44.6 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX05 Bedford Park-Fordham North                      | *    | *    | 41.9 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX06 Belmont                                         | *    | *    | 37.9 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX07 Bronxdale                                       | *    | *    | 39.6 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX08 West Farms-Bronx River                          | *    | *    | 42.6 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX09 Soundview-Castle Hill-Clason Point-Harding Park | *    | *    | 45.0 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX10 Pelham Bay-Country Club-City Island             | *    | *    | 37.2 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX13 Co-Op City                                      | *    | *    | 50.0 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
| 1461594183  | Core Infrastructure & the Environment | Mean Travel Time to Work (2009-2013) | BX14 East Concourse-Concourse Village                | *    | *    | 41.7 | *    | *    | Mean travel time for workers 16 years and over who did not work at home. | U.S. Census Bureau, 2009-2013 American Community Survey Five Year Estimates; http://factfinder2.census.gov | 
```