# Directory Of Unsheltered Street Homeless To General Population Ratio 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-unsheltered-street-homeless-to-general-population-ratio-2011-89d3d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ivbu-e2q7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ivbu-e2q7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ivbu-e2q7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ivbu-e2q7 |
| Name | Directory Of Unsheltered Street Homeless To General Population Ratio 2011 |
| Attribution | Department of Homeless Services (DHS) |
| Category | Social Services |
| Tags | dhs, homeless, ratio, population |
| Created | 2013-01-30T23:24:05Z |
| Publication Date | 2013-01-30T23:39:22Z |

## Description

"Ratio of Homeless Population to General Population in major US Cities in 2011.
*This represents a list of large U.S. cities for which DHS was able to confirm a recent estimate of the unsheltered population.  A 2011 result is available for Seattle, WA, Miami, FL, and Boston, MA.. 2011 results are not yet available for the other cities, and their 2009 data are displayed in this chart. General population figures are 2010 estimates in New York, San Francisco, and Chicago, and 2009 estimates elsewhere."

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ivbu-e2q7 d:2011-01-01T00:00:00.000Z t:street_homeless_population=182 t:ratio_of_unsheltered_homeless_to_general_population="1 in 3,545" m:general_population=645169

series e:ivbu-e2q7 d:2011-01-01T00:00:00.000Z t:street_homeless_population=884 t:ratio_of_unsheltered_homeless_to_general_population="1 in 3,225" m:general_population=2851268

series e:ivbu-e2q7 d:2011-01-01T00:00:00.000Z t:street_homeless_population=2648 t:ratio_of_unsheltered_homeless_to_general_population="1 in 3,087" m:general_population=8175133
```

## Meta Commands

```ls
metric m:general_population p:integer l:"General Population" t:dataTypeName=number

entity e:ivbu-e2q7 l:"Directory Of Unsheltered Street Homeless To General Population Ratio 2011" t:attribution="Department of Homeless Services (DHS)" t:url=https://data.cityofnewyork.us/api/views/ivbu-e2q7

property e:ivbu-e2q7 t:meta.view v:id=ivbu-e2q7 v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dhs/downloads/pdf/hope11_results.pdf v:averageRating=0 v:name="Directory Of Unsheltered Street Homeless To General Population Ratio 2011" v:attribution="Department of Homeless Services (DHS)"

property e:ivbu-e2q7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ivbu-e2q7 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| street_homeless_population | general_population | ratio_of_unsheltered_homeless_to_general_population | 
| ========================== | ================== | =================================================== | 
| 182                        | 645169             | 1 in 3,545                                          | 
| 884                        | 2851268            | 1 in 3,225                                          | 
| 2648                       | 8175133            | 1 in 3,087                                          | 
| 321                        | 601723             | 1 in 1,875                                          | 
| 487                        | 433136             | 1 in 889                                            | 
| 1753                       | 616627             | 1 in 352                                            | 
| 2709                       | 805235             | 1 in 297                                            | 
| 15770                      | 3831868            | 1 in 243                                            | 
```