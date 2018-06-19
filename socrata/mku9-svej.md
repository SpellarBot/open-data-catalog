# Upper Columbia Juvenile Abundance 10302012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upper-columbia-juvenile-abundance-10302012-404c1) |
| Metadata | [Link](https://data.wa.gov/api/views/mku9-svej) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mku9-svej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mku9-svej/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mku9-svej |
| Name | Upper Columbia Juvenile Abundance 10302012 |
| Created | 2012-10-30T17:37:20Z |
| Publication Date | 2012-10-30T17:38:04Z |

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
series e:mku9-svej d:2000-01-01T00:00:00.000Z t:population_stock_number=1770 t:species="Wenatchee Spring Chinook" m:density=189 m:occupied_river_miles=174.1 m:abundance=32837

series e:mku9-svej d:2001-01-01T00:00:00.000Z t:population_stock_number=1770 t:species="Wenatchee Spring Chinook" m:density=78 m:occupied_river_miles=174.1 m:abundance=13583

series e:mku9-svej d:2002-01-01T00:00:00.000Z t:population_stock_number=1770 t:species="Wenatchee Spring Chinook" m:density=440 m:occupied_river_miles=174.1 m:abundance=76643
```

## Meta Commands

```ls
metric m:occupied_river_miles p:float l:"Occupied River Miles" t:dataTypeName=number

metric m:abundance p:integer l:Abundance t:dataTypeName=number

metric m:density p:integer l:Density t:dataTypeName=number

entity e:mku9-svej l:"Upper Columbia Juvenile Abundance 10302012" t:url=https://data.wa.gov/api/views/mku9-svej

property e:mku9-svej t:meta.view v:id=mku9-svej v:averageRating=0 v:name="Upper Columbia Juvenile Abundance 10302012"

property e:mku9-svej t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:mku9-svej t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | migration_year | species                  | occupied_river_miles | abundance | density | 
| ======================= | ============== | ======================== | ==================== | ========= | ======= | 
| 1770                    | 2000           | Wenatchee Spring Chinook | 174.1                | 32837     | 189     | 
| 1770                    | 2001           | Wenatchee Spring Chinook | 174.1                | 13583     | 78      | 
| 1770                    | 2002           | Wenatchee Spring Chinook | 174.1                | 76643     | 440     | 
| 1770                    | 2003           | Wenatchee Spring Chinook | 174.1                | 243516    | 1399    | 
| 1770                    | 2004           | Wenatchee Spring Chinook | 174.1                | 165116    | 948     | 
| 1770                    | 2005           | Wenatchee Spring Chinook | 174.1                | 70738     | 406     | 
| 1770                    | 2006           | Wenatchee Spring Chinook | 174.1                | 55619     | 319     | 
| 1770                    | 2007           | Wenatchee Spring Chinook | 174.1                | 302116    | 1735    | 
| 1770                    | 2008           | Wenatchee Spring Chinook | 174.1                | 85558     | 491     | 
| 1770                    | 2009           | Wenatchee Spring Chinook | 174.1                | 60219     | 346     | 
```