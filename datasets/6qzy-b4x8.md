# Total Housing Units By Occupancy Status And Tenure By Borough

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-housing-units-by-occupancy-status-and-tenure-by-borough-d7fdc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6qzy-b4x8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6qzy-b4x8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6qzy-b4x8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6qzy-b4x8 |
| Name | Total Housing Units By Occupancy Status And Tenure By Borough |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, population, growth, housing, occupancy, tenure |
| Created | 2013-02-20T19:02:10Z |
| Publication Date | 2013-06-21T20:45:07Z |

## Description

Details of Housing Unit numbers by Occupancy Status and Tenure in New York City Boroughs

## Columns

```ls
| Included | Schema Type    | Field Name                                               | Name                                                      | Data Type | Render Type |
| ======== | ============== | ======================================================== | ========================================================= | ========= | =========== |
| Yes      | series tag     | borough                                                  | Borough                                                   | text      | text        |
| Yes      | time           | year                                                     | Year                                                      | number    | number      |
| Yes      | numeric metric | total_housing_units                                      | Total Housing Units                                       | number    | number      |
| Yes      | numeric metric | owner_occupied                                           | Owner Occupied                                            | number    | number      |
| Yes      | numeric metric | renter_occupied                                          | Renter Occupied                                           | number    | number      |
| Yes      | numeric metric | total_vacant_units                                       | Total Vacant Units                                        | number    | number      |
| Yes      | numeric metric | vacant_units_for_seasonal_recreational_or_occasional_use | Vacant Units for Seasonal, Recreational or Occasional Use | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6qzy-b4x8 d:2010-01-01T00:00:00.000Z t:borough=Bronx m:total_housing_units=511896 m:renter_occupied=390348 m:owner_occupied=93101 m:total_vacant_units=28447 m:vacant_units_for_seasonal_recreational_or_occasional_use=1196

series e:6qzy-b4x8 d:2010-01-01T00:00:00.000Z t:borough=Brooklyn m:total_housing_units=1000293 m:renter_occupied=662615 m:owner_occupied=254241 m:total_vacant_units=83437 m:vacant_units_for_seasonal_recreational_or_occasional_use=3872

series e:6qzy-b4x8 d:2010-01-01T00:00:00.000Z t:borough=Manhattan m:total_housing_units=847090 m:renter_occupied=589885 m:owner_occupied=173961 m:total_vacant_units=83244 m:vacant_units_for_seasonal_recreational_or_occasional_use=28184
```

## Meta Commands

```ls
metric m:total_housing_units p:integer l:"Total Housing Units" t:dataTypeName=number

metric m:owner_occupied p:integer l:"Owner Occupied" t:dataTypeName=number

metric m:renter_occupied p:integer l:"Renter Occupied" t:dataTypeName=number

metric m:total_vacant_units p:integer l:"Total Vacant Units" t:dataTypeName=number

metric m:vacant_units_for_seasonal_recreational_or_occasional_use p:integer l:"Vacant Units for Seasonal, Recreational or Occasional Use" t:dataTypeName=number

entity e:6qzy-b4x8 l:"Total Housing Units By Occupancy Status And Tenure By Borough" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/6qzy-b4x8

property e:6qzy-b4x8 t:meta.view v:id=6qzy-b4x8 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/census/census2010/pgrhc.pdf v:averageRating=0 v:name="Total Housing Units By Occupancy Status And Tenure By Borough" v:attribution="Department of City Planning (DCP)"

property e:6qzy-b4x8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6qzy-b4x8 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| borough       | year | total_housing_units | owner_occupied | renter_occupied | total_vacant_units | vacant_units_for_seasonal_recreational_or_occasional_use | 
| ============= | ==== | =================== | ============== | =============== | ================== | ======================================================== | 
| Bronx         | 2010 | 511896              | 93101          | 390348          | 28447              | 1196                                                     | 
| Brooklyn      | 2010 | 1000293             | 254241         | 662615          | 83437              | 3872                                                     | 
| Manhattan     | 2010 | 847090              | 173961         | 589885          | 83244              | 28184                                                    | 
| Queens        | 2010 | 835127              | 335454         | 444663          | 55010              | 5894                                                     | 
| Staten Island | 2010 | 176656              | 106135         | 59381           | 11140              | 647                                                      | 
```