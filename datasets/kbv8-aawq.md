# Lower Columbia Final Abundance 11202012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lower-columbia-final-abundance-11202012-d4ea2) |
| Metadata | [Link](https://data.wa.gov/api/views/kbv8-aawq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kbv8-aawq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kbv8-aawq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kbv8-aawq |
| Name | Lower Columbia Final Abundance 11202012 |
| Created | 2012-11-20T13:23:18Z |
| Publication Date | 2012-12-02T22:04:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery                | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery         | number    | number      |
| Yes      | numeric metric | goal_wild               | Goal (Wild)             | number    | number      |
| Yes      | series tag     | population_stock_name   | Population/Stock Name   | text      | text        |
| No       |                | listing_year            | Listing Year            | number    | number      |
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
series e:kbv8-aawq d:1989-01-01T00:00:00.000Z t:population_stock_number=1496 t:population_stock_name="Grays/Chinook Fall Chinook" m:wild_hatchery=813 m:goal_wild=1000

series e:kbv8-aawq d:1990-01-01T00:00:00.000Z t:population_stock_number=1496 t:population_stock_name="Grays/Chinook Fall Chinook" m:wild_hatchery=287 m:goal_wild=1000

series e:kbv8-aawq d:1991-01-01T00:00:00.000Z t:population_stock_number=1496 t:population_stock_name="Grays/Chinook Fall Chinook" m:wild_hatchery=200 m:goal_wild=1000
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:double l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:kbv8-aawq l:"Lower Columbia Final Abundance 11202012" t:url=https://data.wa.gov/api/views/kbv8-aawq

property e:kbv8-aawq t:meta.view v:id=kbv8-aawq v:averageRating=0 v:name="Lower Columbia Final Abundance 11202012"

property e:kbv8-aawq t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:kbv8-aawq t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | population_stock_name      | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | ========================== | ============ | 
| 1496                    | 1989 |      |          | 813           | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1990 |      |          | 287           | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1991 |      |          | 200           | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1992 |      |          | 4             | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1993 |      |          | 43            | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1994 |      |          | 47            | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1995 |      |          | 29            | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1996 |      |          | 365           | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1997 |      |          | 14            | 1000      | Grays/Chinook Fall Chinook | 1999         | 
| 1496                    | 1998 |      |          | 93            | 1000      | Grays/Chinook Fall Chinook | 1999         | 
```