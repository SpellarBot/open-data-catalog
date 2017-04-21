# Upper Columbia Final Abundance 10212012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upper-columbia-final-abundance-10212012-10f4c) |
| Metadata | [Link](https://data.wa.gov/api/views/kvxf-jj4x) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kvxf-jj4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kvxf-jj4x/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kvxf-jj4x |
| Name | Upper Columbia Final Abundance 10212012 |
| Created | 2012-10-21T20:38:41Z |
| Publication Date | 2012-10-21T20:42:21Z |

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
series e:kvxf-jj4x d:1989-01-01T00:00:00.000Z t:population_stock_number=1770 t:population_stock_name="Wenatchee Spring Chinook" m:wild=1396 m:hatchery=0 m:wild_hatchery=1396 m:goal_wild=2000

series e:kvxf-jj4x d:1990-01-01T00:00:00.000Z t:population_stock_number=1770 t:population_stock_name="Wenatchee Spring Chinook" m:wild=999 m:hatchery=0 m:wild_hatchery=999 m:goal_wild=2000

series e:kvxf-jj4x d:1991-01-01T00:00:00.000Z t:population_stock_number=1770 t:population_stock_name="Wenatchee Spring Chinook" m:wild=585 m:hatchery=0 m:wild_hatchery=585 m:goal_wild=2000
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:double l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:kvxf-jj4x l:"Upper Columbia Final Abundance 10212012" t:url=https://data.wa.gov/api/views/kvxf-jj4x

property e:kvxf-jj4x t:meta.view v:id=kvxf-jj4x v:averageRating=0 v:name="Upper Columbia Final Abundance 10212012"

property e:kvxf-jj4x t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:kvxf-jj4x t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | population_stock_name    | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | ======================== | ============ | 
| 1770                    | 1989 | 1396 | 0        | 1396          | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1990 | 999  | 0        | 999           | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1991 | 585  | 0        | 585           | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1992 | 1100 | 0        | 1100          | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1993 | 712  | 480      | 1192          | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1994 | 202  | 78       | 280           | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1995 | 22   | 36       | 58            | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1996 | 137  | 45       | 182           | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1997 | 189  | 199      | 388           | 2000      | Wenatchee Spring Chinook | 1999         | 
| 1770                    | 1998 | 140  | 44       | 184           | 2000      | Wenatchee Spring Chinook | 1999         | 
```