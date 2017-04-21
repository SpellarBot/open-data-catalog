# Lower Columbia Juvenile Abundance 10302012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lower-columbia-juvenile-abundance-10302012-84670) |
| Metadata | [Link](https://data.wa.gov/api/views/t7uz-a2px) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/t7uz-a2px/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/t7uz-a2px/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | t7uz-a2px |
| Name | Lower Columbia Juvenile Abundance 10302012 |
| Created | 2012-11-01T11:08:14Z |
| Publication Date | 2012-11-01T11:09:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | migration_year          | Migration Year          | number    | number      |
| Yes      | series tag     | species                 | Species                 | text      | text        |
| Yes      | numeric metric | occupied_river_miles    | Occupied River Miles    | number    | number      |
| Yes      | numeric metric | abundance               | Abundance               | number    | number      |
| Yes      | numeric metric | density                 | Density                 | number    | number      |
```

## Time Field

```ls
Value = migration_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t7uz-a2px d:2001-01-01T00:00:00.000Z t:population_stock_number=1525 t:species="Mill Creek Tule Fall Chinook Salmon" m:occupied_river_miles=12.2

series e:t7uz-a2px d:2002-01-01T00:00:00.000Z t:population_stock_number=1525 t:species="Mill Creek Tule Fall Chinook Salmon" m:occupied_river_miles=12.2

series e:t7uz-a2px d:2003-01-01T00:00:00.000Z t:population_stock_number=1525 t:species="Mill Creek Tule Fall Chinook Salmon" m:occupied_river_miles=12.2
```

## Meta Commands

```ls
metric m:occupied_river_miles p:double l:"Occupied River Miles" t:dataTypeName=number

metric m:abundance p:integer l:Abundance t:dataTypeName=number

metric m:density p:integer l:Density t:dataTypeName=number

entity e:t7uz-a2px l:"Lower Columbia Juvenile Abundance 10302012" t:url=https://data.wa.gov/api/views/t7uz-a2px

property e:t7uz-a2px t:meta.view v:id=t7uz-a2px v:averageRating=0 v:name="Lower Columbia Juvenile Abundance 10302012"

property e:t7uz-a2px t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:t7uz-a2px t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | migration_year | species                             | occupied_river_miles | abundance | density | 
| ======================= | ============== | =================================== | ==================== | ========= | ======= | 
| 1525                    | 2001           | Mill Creek Tule Fall Chinook Salmon | 12.2                 |           |         | 
| 1525                    | 2002           | Mill Creek Tule Fall Chinook Salmon | 12.2                 |           |         | 
| 1525                    | 2003           | Mill Creek Tule Fall Chinook Salmon | 12.2                 |           |         | 
| 1525                    | 2004           | Mill Creek Tule Fall Chinook Salmon | 12.2                 |           |         | 
| 1525                    | 2005           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 246475    | 20203   | 
| 1525                    | 2006           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 411211    | 33706   | 
| 1525                    | 2007           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 23080     | 1892    | 
| 1525                    | 2008           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 29464     | 2415    | 
| 1525                    | 2009           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 7897      | 647     | 
| 1525                    | 2010           | Mill Creek Tule Fall Chinook Salmon | 12.2                 | 200000    | 16393   | 
```