# Jan 2015 ECY Stations With Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen And pH

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jan-2015-ecy-stations-with-exceeded-criteria-for-fecal-bacteria-temperature-oxygen-and-ph) |
| Metadata | [Link](https://data.wa.gov/api/views/mf85-v9ji) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mf85-v9ji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mf85-v9ji/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mf85-v9ji |
| Name | Jan 2015 ECY Stations With Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen And pH |
| Attribution | Wa Department of Ecology |
| Created | 2015-03-17T23:53:27Z |
| Publication Date | 2015-03-18T17:17:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | station                  | Station                  | text          | text          |
| Yes      | series tag     | station_name             | Station Name             | text          | text          |
| Yes      | series tag     | station_data             | Station Data             | url           | url           |
| Yes      | series tag     | ecology_region           | Ecology region           | text          | text          |
| Yes      | time           | wq_violation_date        | WQ Violation Date        | calendar_date | calendar_date |
| Yes      | series tag     | time                     | Time                     | text          | text          |
| Yes      | series tag     | variable_units           | Variable/Units           | text          | text          |
| Yes      | numeric metric | sample_result_or_geo_mn  | Sample Result or geo.mn  | number        | number        |
| No       |                | n                        | N                        | number        | number        |
| Yes      | numeric metric | criterion                | Criterion                | number        | number        |
| Yes      | numeric metric | percent_exceeds_standard | Percent exceeds standard | number        | number        |
```

## Time Field

```ls
Value = wq_violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = n
```

## Data Commands

```ls
series e:mf85-v9ji d:2015-03-13T00:00:00.000Z t:station_name="Bertrand @ 0 Ave" t:time=11:03 t:station_data="http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?theyear=&tab=notes&scrolly=0&sta=01N100" t:station=01N100 t:variable_units="Fecal Coliform (#/100ml)" t:ecology_region=Northwest m:criterion=100 m:percent_exceeds_standard=49 m:sample_result_or_geo_mn=149

series e:mf85-v9ji d:2015-01-07T00:00:00.000Z t:station_name="Palouse R @ Palouse" t:time=9:30 t:station_data="http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?sta=34A170" t:station=34A170 t:variable_units="Fecal Coliform (#/100ml)" t:ecology_region=Eastern m:criterion=200 m:percent_exceeds_standard=5 m:sample_result_or_geo_mn=210

series e:mf85-v9ji d:2015-01-13T00:00:00.000Z t:station_name="Bertrand Cr @ Rathbone Rd" t:time=13:23 t:station_data="http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?theyear=&tab=notes&scrolly=0&sta=01N060" t:station=01N060 t:variable_units="Fecal Coliform (#/100ml)" t:ecology_region=Northwest m:criterion=100 m:percent_exceeds_standard=1 m:sample_result_or_geo_mn=114
```

## Meta Commands

```ls
metric m:sample_result_or_geo_mn p:integer l:"Sample Result or geo.mn" t:dataTypeName=number

metric m:criterion p:integer l:Criterion t:dataTypeName=number

metric m:percent_exceeds_standard p:float l:"Percent exceeds standard" t:dataTypeName=number

entity e:mf85-v9ji l:"Jan 2015 ECY Stations With Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen And pH" t:attribution="Wa Department of Ecology" t:url=https://data.wa.gov/api/views/mf85-v9ji

property e:mf85-v9ji t:meta.view v:id=mf85-v9ji v:averageRating=0 v:name="Jan 2015 ECY Stations With Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen And pH" v:attribution="Wa Department of Ecology"

property e:mf85-v9ji t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:mf85-v9ji t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| station | station_name               | station_data                                                                                                 | ecology_region | wq_violation_date   | time  | variable_units           | sample_result_or_geo_mn | n  | criterion | percent_exceeds_standard | 
| ======= | ========================== | ============================================================================================================ | ============== | =================== | ===== | ======================== | ======================= | == | ========= | ======================== | 
| 01N100  | Bertrand @ 0 Ave           | [http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?theyear=&tab=notes&scrolly=0&sta=01N100, null]        | Northwest      | 2015-03-13T00:00:00 | 11:03 | Fecal Coliform (#/100ml) | 149                     | 12 | 100       | 49                       | 
| 34A170  | Palouse R @ Palouse        | [http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?sta=34A170, null]                                     | Eastern        | 2015-01-07T00:00:00 | 9:30  | Fecal Coliform (#/100ml) | 210                     | 12 | 200       | 5                        | 
| 01N060  | Bertrand Cr @ Rathbone Rd  | [http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?theyear=&tab=notes&scrolly=0&sta=01N060, null]        | Northwest      | 2015-01-13T00:00:00 | 13:23 | Fecal Coliform (#/100ml) | 114                     | 11 | 100       | 1                        | 
| 08H070  | Thornton Cr nr Mouth       | [http://www.ecy.wa.gov/apps/watersheds/riv/station.asp?theyear=&tab=notes&scrolly=0&wria=08&sta=first, null] | Northwest      | 2015-01-14T00:00:00 | 11:00 | Fecal Coliform (#/100ml) | 127                     | 4  | 50        | 153.4                    | 
| 22A070  | Humptulips R nr Humptulips | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
| 20B070  | Hoh R @ DNR Campground     | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
| 24F070  | Naselle R nr Naselle       | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
| 23A160  | Chehalis R @ Dryad         | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
| 24B090  | Willapa R nr Willapa       | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
| 23A070  | Chehalis R @ Porter        | [null, null]                                                                                                 |                |                     |       |                          |                         |    |           |                          | 
```