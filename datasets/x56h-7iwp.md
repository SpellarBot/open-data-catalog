# Directory Of Unsheltered Street Homeless To General Population Ratio 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-unsheltered-street-homeless-to-general-population-ratio-2009-acc6d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/x56h-7iwp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/x56h-7iwp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/x56h-7iwp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | x56h-7iwp |
| Name | Directory Of Unsheltered Street Homeless To General Population Ratio 2009 |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, ratio, population |
| Created | 2013-01-30T22:51:24Z |
| Publication Date | 2013-01-30T23:09:49Z |

## Description

"Ratio of Homeless Population to General Population in major US Cities in 2009. 
*This represents a list of large U.S. cities with a similar street count methodology for which DHS was able to confirm a recent Census; 2009 results are not yet available for LA, SF, and Chicago.  All population figures are from the 2007 U.S. Census Bureau Population Estimate."

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | numeric metric | estimated_unsheltered_population                    | Estimated Unsheltered Population                    | number    | number      |
| Yes      | numeric metric | total_population                                    | Total Population                                    | number    | number      |
| Yes      | series tag     | ratio_of_unsheltered_homeless_to_general_population | Ratio of Unsheltered Homeless to General Population | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x56h-7iwp d:2009-01-01T00:00:00.000Z t:ratio_of_unsheltered_homeless_to_general_population="1 in 3,554" m:total_population=8274527 m:estimated_unsheltered_population=2328

series e:x56h-7iwp d:2009-01-01T00:00:00.000Z t:ratio_of_unsheltered_homeless_to_general_population="1 in 96" m:total_population=3834340 m:estimated_unsheltered_population=40144

series e:x56h-7iwp d:2009-01-01T00:00:00.000Z t:ratio_of_unsheltered_homeless_to_general_population="1 in 276" m:total_population=764976 m:estimated_unsheltered_population=2771
```

## Meta Commands

```ls
metric m:estimated_unsheltered_population p:integer l:"Estimated Unsheltered Population" t:dataTypeName=number

metric m:total_population p:integer l:"Total Population" t:dataTypeName=number

entity e:x56h-7iwp l:"Directory Of Unsheltered Street Homeless To General Population Ratio 2009" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/x56h-7iwp

property e:x56h-7iwp t:meta.view v:id=x56h-7iwp v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/hope10_results.pdf v:averageRating=0 v:name="Directory Of Unsheltered Street Homeless To General Population Ratio 2009" v:attribution="Department of Homeless Services (DHS)"

property e:x56h-7iwp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:x56h-7iwp t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| estimated_unsheltered_population | total_population | ratio_of_unsheltered_homeless_to_general_population | 
| ================================ | ================ | =================================================== | 
| 2328                             | 8274527          | 1 in 3,554                                          | 
| 40144                            | 3834340          | 1 in 96                                             | 
| 2771                             | 764976           | 1 in 276                                            | 
| 1976                             | 594210           | 1 in 301                                            | 
| 1576                             | 2836658          | 1 in 1,800                                          | 
| 994                              | 2387170          | 1 in 2,402                                          | 
```