# Middle Columbia Final Abundance 10252012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/middle-columbia-final-abundance-10252012-0637b) |
| Metadata | [Link](https://data.wa.gov/api/views/dbef-72v2) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dbef-72v2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dbef-72v2/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dbef-72v2 |
| Name | Middle Columbia Final Abundance 10252012 |
| Created | 2012-10-25T23:55:09Z |
| Publication Date | 2012-10-26T17:09:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | text        |
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
series e:dbef-72v2 d:1989-01-01T00:00:00.000Z t:population_stock_number=6888 t:population_stock_name="Satus Creek Summer Steelhead" m:wild=409 m:hatchery=41 m:wild_hatchery=450 m:goal_wild=1000

series e:dbef-72v2 d:1990-01-01T00:00:00.000Z t:population_stock_number=6888 t:population_stock_name="Satus Creek Summer Steelhead" m:wild=268 m:hatchery=36 m:wild_hatchery=304 m:goal_wild=1000

series e:dbef-72v2 d:1991-01-01T00:00:00.000Z t:population_stock_number=6888 t:population_stock_name="Satus Creek Summer Steelhead" m:wild=230 m:hatchery=38 m:wild_hatchery=268 m:goal_wild=1000
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:dbef-72v2 l:"Middle Columbia Final Abundance 10252012" t:url=https://data.wa.gov/api/views/dbef-72v2

property e:dbef-72v2 t:meta.view v:id=dbef-72v2 v:averageRating=0 v:name="Middle Columbia Final Abundance 10252012"

property e:dbef-72v2 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:dbef-72v2 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | population_stock_name        | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | ============================ | ============ | 
| 6888                    | 1989 | 409  | 41       | 450           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1990 | 268  | 36       | 304           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1991 | 230  | 38       | 268           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1992 | 928  | 132      | 1060          | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1993 | 414  | 32       | 446           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1994 | 192  | 5        | 197           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1995 | 332  | 8        | 340           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1996 | 154  | 4        | 158           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1997 | 302  | 8        | 310           | 1000      | Satus Creek Summer Steelhead | 1999         | 
| 6888                    | 1998 | 403  | 10       | 413           | 1000      | Satus Creek Summer Steelhead | 1999         | 
```