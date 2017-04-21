# Puget Sound Juvenile Abundance 10302012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/puget-sound-juvenile-abundance-10302012-e33e1) |
| Metadata | [Link](https://data.wa.gov/api/views/p6mz-hz4g) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/p6mz-hz4g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/p6mz-hz4g/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | p6mz-hz4g |
| Name | Puget Sound Juvenile Abundance 10302012 |
| Created | 2012-10-31T22:46:35Z |
| Publication Date | 2012-10-31T22:47:29Z |

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
series e:p6mz-hz4g d:1994-01-01T00:00:00.000Z t:population_stock_number=1040 t:species="Skagit River Chinook Salmon" m:density=6366 m:occupied_river_miles=325.3 m:abundance=2071000

series e:p6mz-hz4g d:1995-01-01T00:00:00.000Z t:population_stock_number=1040 t:species="Skagit River Chinook Salmon" m:density=5943 m:occupied_river_miles=325.3 m:abundance=1933398

series e:p6mz-hz4g d:1996-01-01T00:00:00.000Z t:population_stock_number=1040 t:species="Skagit River Chinook Salmon" m:density=3075 m:occupied_river_miles=325.3 m:abundance=1000270
```

## Meta Commands

```ls
metric m:occupied_river_miles p:float l:"Occupied River Miles" t:dataTypeName=number

metric m:abundance p:integer l:Abundance t:dataTypeName=number

metric m:density p:integer l:Density t:dataTypeName=number

entity e:p6mz-hz4g l:"Puget Sound Juvenile Abundance 10302012" t:url=https://data.wa.gov/api/views/p6mz-hz4g

property e:p6mz-hz4g t:meta.view v:id=p6mz-hz4g v:averageRating=0 v:name="Puget Sound Juvenile Abundance 10302012"

property e:p6mz-hz4g t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:p6mz-hz4g t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | migration_year | species                     | occupied_river_miles | abundance | density | 
| ======================= | ============== | =========================== | ==================== | ========= | ======= | 
| 1040                    | 1994           | Skagit River Chinook Salmon | 325.3                | 2071000   | 6366    | 
| 1040                    | 1995           | Skagit River Chinook Salmon | 325.3                | 1933398   | 5943    | 
| 1040                    | 1996           | Skagit River Chinook Salmon | 325.3                | 1000270   | 3075    | 
| 1040                    | 1997           | Skagit River Chinook Salmon | 325.3                | 2758000   | 8478    | 
| 1040                    | 1998           | Skagit River Chinook Salmon | 325.3                | 2454000   | 7544    | 
| 1040                    | 1999           | Skagit River Chinook Salmon | 325.3                | 7712000   | 23707   | 
| 1040                    | 2000           | Skagit River Chinook Salmon | 325.3                | 1775000   | 5457    | 
| 1040                    | 2001           | Skagit River Chinook Salmon | 325.3                | 6793000   | 20882   | 
| 1040                    | 2002           | Skagit River Chinook Salmon | 325.3                | 5835000   | 17937   | 
| 1040                    | 2003           | Skagit River Chinook Salmon | 325.3                | 5018000   | 15426   | 
```