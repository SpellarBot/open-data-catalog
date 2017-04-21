# Directory Of Unsheltered Street Homeless To General Population Ratio 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-unsheltered-street-homeless-to-general-population-ratio-2010-23fc9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8kiv-2ukd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8kiv-2ukd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8kiv-2ukd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8kiv-2ukd |
| Name | Directory Of Unsheltered Street Homeless To General Population Ratio 2010 |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, ratio, population |
| Created | 2013-01-30T23:13:04Z |
| Publication Date | 2013-01-30T23:53:54Z |

## Description

"Ratio of Homeless Population to General Population in major US Cities in 2010. 
*This represents a list of large U.S. cities for which DHS was able to confirm a recent estimate of the unsheltered population.  A 2010 result is only available for Seattle, WA. Other cities either did not conduct a count in 2010, or their 2010 results are not yet available.  2009 unsheltered census   figures were used for Los Angeles, San Francisco, Miami, and Washington, DC, and Boston; the 2007 estimate is used for Chicago.  General population figures are the latest estimates from the U.S. Census Bureau."

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | series tag     | street_homeless_population                          | Street Homeless Population                          | text      | number      |
| Yes      | numeric metric | general_population                                  | General Population                                  | number    | number      |
| Yes      | series tag     | ratio_of_unsheltered_homeless_to_general_population | Ratio of Unsheltered Homeless to General Population | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8kiv-2ukd d:2010-01-01T00:00:00.000Z t:street_homeless_population=3111 t:ratio_of_unsheltered_homeless_to_general_population="1 in 2,688" m:general_population=8363710

series e:8kiv-2ukd d:2010-01-01T00:00:00.000Z t:street_homeless_population=24915 t:ratio_of_unsheltered_homeless_to_general_population="1 in 154" m:general_population=3833995

series e:8kiv-2ukd d:2010-01-01T00:00:00.000Z t:street_homeless_population=2709 t:ratio_of_unsheltered_homeless_to_general_population="1 in 299" m:general_population=808976
```

## Meta Commands

```ls
metric m:general_population p:integer l:"General Population" t:dataTypeName=number

entity e:8kiv-2ukd l:"Directory Of Unsheltered Street Homeless To General Population Ratio 2010" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/8kiv-2ukd

property e:8kiv-2ukd t:meta.view v:id=8kiv-2ukd v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/hope10_results.pdf v:averageRating=0 v:name="Directory Of Unsheltered Street Homeless To General Population Ratio 2010" v:attribution="Department of Homeless Services (DHS)"

property e:8kiv-2ukd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8kiv-2ukd t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| street_homeless_population | general_population | ratio_of_unsheltered_homeless_to_general_population | 
| ========================== | ================== | =================================================== | 
| 3111                       | 8363710            | 1 in 2,688                                          | 
| 24915                      | 3833995            | 1 in 154                                            | 
| 2709                       | 808976             | 1 in 299                                            | 
| 1986                       | 598541             | 1 in 301                                            | 
| 411                        | 413201             | 1 in 1005                                           | 
| 1576                       | 2853114            | 1 in 1,810                                          | 
| 321                        | 591833             | 1 in 1,844                                          | 
| 219                        | 609023             | 1 in 2,781                                          | 
```