# Hood Canal Final Abundance 01032013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hood-canal-final-abundance-01032013-b6afa) |
| Metadata | [Link](https://data.wa.gov/api/views/wnng-dhxk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/wnng-dhxk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/wnng-dhxk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | wnng-dhxk |
| Name | Hood Canal Final Abundance 01032013 |
| Created | 2012-11-15T13:18:59Z |
| Publication Date | 2013-01-03T19:43:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                     | Data Type | Render Type |
| ======== | ============== | ======================= | ======================== | ========= | =========== |
| Yes      | series tag     | population_stock_number | WFDW SCoRE ID            | text      | number      |
| Yes      | time           | year                    | Year                     | number    | number      |
| Yes      | numeric metric | wild                    | Wild Spawners            | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery Origin Spawners | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery          | number    | number      |
| Yes      | numeric metric | goal_wild_1             | Recovery Goal 1          | number    | number      |
| Yes      | numeric metric | goal_wild_2             | Recovery Goal 2          | number    | number      |
| Yes      | series tag     | population_stock_name   | Population Name          | text      | text        |
| No       |                | listing_year            | ESA Listing Year         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = listing_year
```

## Data Commands

```ls
series e:wnng-dhxk d:1974-01-01T00:00:00.000Z t:population_stock_number=2301 t:population_stock_name="Big Beef Creek Summer Chum" m:wild=75 m:hatchery=0 m:wild_hatchery=75 m:goal_wild_2=21500 m:goal_wild_1=18600

series e:wnng-dhxk d:1975-01-01T00:00:00.000Z t:population_stock_number=2301 t:population_stock_name="Big Beef Creek Summer Chum" m:wild=1152 m:hatchery=0 m:wild_hatchery=1152 m:goal_wild_2=21500 m:goal_wild_1=18600

series e:wnng-dhxk d:1976-01-01T00:00:00.000Z t:population_stock_number=2301 t:population_stock_name="Big Beef Creek Summer Chum" m:wild=1281 m:hatchery=0 m:wild_hatchery=1281 m:goal_wild_2=21500 m:goal_wild_1=18600
```

## Meta Commands

```ls
metric m:wild p:integer l:"Wild Spawners" t:dataTypeName=number

metric m:hatchery p:double l:"Hatchery Origin Spawners" t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild_1 p:integer l:"Recovery Goal 1" t:dataTypeName=number

metric m:goal_wild_2 p:integer l:"Recovery Goal 2" t:dataTypeName=number

entity e:wnng-dhxk l:"Hood Canal Final Abundance 01032013" t:url=https://data.wa.gov/api/views/wnng-dhxk

property e:wnng-dhxk t:meta.view v:id=wnng-dhxk v:averageRating=0 v:name="Hood Canal Final Abundance 01032013"

property e:wnng-dhxk t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:wnng-dhxk t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild_1 | goal_wild_2 | population_stock_name      | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | =========== | =========== | ========================== | ============ | 
| 2301                    | 1974 | 75   | 0        | 75            | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1975 | 1152 | 0        | 1152          | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1976 | 1281 | 0        | 1281          | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1977 | 302  | 0        | 302           | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1978 | 680  | 0        | 680           | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1979 | 191  | 0        | 191           | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1980 | 123  | 0        | 123           | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1981 | 90   | 0        | 90            | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1982 | 0    | 0        | 0             | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
| 2301                    | 1983 | 0    | 0        | 0             | 18600       | 21500       | Big Beef Creek Summer Chum | 1999         | 
```