# 2010 Census Population And Housing Units By Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-census-population-and-housing-units-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/igy9-udjm) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/igy9-udjm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/igy9-udjm/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | igy9-udjm |
| Name | 2010 Census Population And Housing Units By Town |
| Attribution | Office of Policy and Management |
| Tags | census, population, housing |
| Created | 2014-03-22T19:44:20Z |
| Publication Date | 2014-03-22T19:45:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | municipality           | Municipality           | text      | text        |
| Yes      | numeric metric | population             | Population             | number    | number      |
| Yes      | numeric metric | total_housing_units    | Total Housing Units    | number    | number      |
| Yes      | numeric metric | occupied_housing_units | Occupied Housing Units | number    | number      |
| Yes      | numeric metric | vacant_housing_units   | Vacant Housing Units   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:igy9-udjm d:2010-01-01T00:00:00.000Z t:municipality=Andover m:total_housing_units=1317 m:occupied_housing_units=1244 m:vacant_housing_units=73 m:population=3303

series e:igy9-udjm d:2010-01-01T00:00:00.000Z t:municipality=Ansonia m:total_housing_units=8148 m:occupied_housing_units=7510 m:vacant_housing_units=638 m:population=19249

series e:igy9-udjm d:2010-01-01T00:00:00.000Z t:municipality=Ashford m:total_housing_units=1903 m:occupied_housing_units=1716 m:vacant_housing_units=187 m:population=4317
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

metric m:total_housing_units p:integer l:"Total Housing Units" t:dataTypeName=number

metric m:occupied_housing_units p:integer l:"Occupied Housing Units" t:dataTypeName=number

metric m:vacant_housing_units p:integer l:"Vacant Housing Units" t:dataTypeName=number

entity e:igy9-udjm l:"2010 Census Population And Housing Units By Town" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/igy9-udjm

property e:igy9-udjm t:meta.view v:id=igy9-udjm v:averageRating=0 v:name="2010 Census Population And Housing Units By Town" v:attribution="Office of Policy and Management"

property e:igy9-udjm t:meta.view.license v:name="Public Domain"

property e:igy9-udjm t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:igy9-udjm t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| municipality | population | total_housing_units | occupied_housing_units | vacant_housing_units | 
| ============ | ========== | =================== | ====================== | ==================== | 
| Andover      | 3303       | 1317                | 1244                   | 73                   | 
| Ansonia      | 19249      | 8148                | 7510                   | 638                  | 
| Ashford      | 4317       | 1903                | 1716                   | 187                  | 
| Avon         | 18098      | 7389                | 7009                   | 380                  | 
| Barkhamsted  | 3799       | 1589                | 1452                   | 137                  | 
| Beacon Falls | 6049       | 2509                | 2360                   | 149                  | 
| Berlin       | 19866      | 8140                | 7808                   | 332                  | 
| Bethany      | 5563       | 2044                | 1971                   | 73                   | 
| Bethel       | 18584      | 7310                | 6938                   | 372                  | 
| Bethlehem    | 3607       | 1575                | 1411                   | 164                  | 
```