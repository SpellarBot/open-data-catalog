# Hood Canal Juvenile Abundance 10302012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hood-canal-juvenile-abundance-10302012-9e782) |
| Metadata | [Link](https://data.wa.gov/api/views/dz4g-nx7j) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dz4g-nx7j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dz4g-nx7j/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dz4g-nx7j |
| Name | Hood Canal Juvenile Abundance 10302012 |
| Created | 2012-10-31T18:09:56Z |
| Publication Date | 2012-10-31T18:10:58Z |

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
series e:dz4g-nx7j d:2002-01-01T00:00:00.000Z t:population_stock_number=1236 t:species="Hamma Hamma River Chinook Salmon" m:density=9757 m:occupied_river_miles=2.7 m:abundance=26344

series e:dz4g-nx7j d:2003-01-01T00:00:00.000Z t:population_stock_number=1236 t:species="Hamma Hamma River Chinook Salmon" m:density=1194 m:occupied_river_miles=2.7 m:abundance=3225

series e:dz4g-nx7j d:2004-01-01T00:00:00.000Z t:population_stock_number=1236 t:species="Hamma Hamma River Chinook Salmon" m:density=1412 m:occupied_river_miles=2.7 m:abundance=3813
```

## Meta Commands

```ls
metric m:occupied_river_miles p:float l:"Occupied River Miles" t:dataTypeName=number

metric m:abundance p:integer l:Abundance t:dataTypeName=number

metric m:density p:integer l:Density t:dataTypeName=number

entity e:dz4g-nx7j l:"Hood Canal Juvenile Abundance 10302012" t:url=https://data.wa.gov/api/views/dz4g-nx7j

property e:dz4g-nx7j t:meta.view v:id=dz4g-nx7j v:averageRating=0 v:name="Hood Canal Juvenile Abundance 10302012"

property e:dz4g-nx7j t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:dz4g-nx7j t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | migration_year | species                          | occupied_river_miles | abundance | density | 
| ======================= | ============== | ================================ | ==================== | ========= | ======= | 
| 1236                    | 2002           | Hamma Hamma River Chinook Salmon | 2.7                  | 26344     | 9757    | 
| 1236                    | 2003           | Hamma Hamma River Chinook Salmon | 2.7                  | 3225      | 1194    | 
| 1236                    | 2004           | Hamma Hamma River Chinook Salmon | 2.7                  | 3813      | 1412    | 
| 1236                    | 2005           | Hamma Hamma River Chinook Salmon | 2.7                  | 6683      | 2475    | 
| 1236                    | 2006           | Hamma Hamma River Chinook Salmon | 2.7                  | 468       | 173     | 
| 1236                    | 2007           | Hamma Hamma River Chinook Salmon | 2.7                  |           |         | 
| 1236                    | 2008           | Hamma Hamma River Chinook Salmon | 2.7                  | 220       | 81      | 
| 1236                    | 2009           | Hamma Hamma River Chinook Salmon | 2.7                  | 279       | 103     | 
| 1236                    | 2010           | Hamma Hamma River Chinook Salmon | 2.7                  | 1841      | 682     | 
| 1236                    | 2011           | Hamma Hamma River Chinook Salmon | 2.7                  | 10664     | 3950    | 
```