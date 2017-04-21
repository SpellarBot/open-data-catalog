# Snake Final Abundance 01022013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snake-final-abundance-01022013-02b07) |
| Metadata | [Link](https://data.wa.gov/api/views/b6j7-zus9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/b6j7-zus9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/b6j7-zus9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | b6j7-zus9 |
| Name | Snake Final Abundance 01022013 |
| Created | 2012-11-14T12:28:47Z |
| Publication Date | 2013-01-02T20:00:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                     | Data Type | Render Type |
| ======== | ============== | ======================= | ======================== | ========= | =========== |
| Yes      | series tag     | population_stock_number | WFDW SCoRE ID            | text      | number      |
| Yes      | time           | year                    | Year                     | number    | number      |
| Yes      | numeric metric | wild                    | Wild Spawners            | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery Origin Spawners | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery          | number    | number      |
| Yes      | numeric metric | goal_wild               | Recovery Goal 1          | number    | number      |
| Yes      | series tag     | recovery_goal_2         | Recovery Goal 2          | text      | text        |
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
series e:b6j7-zus9 d:1982-01-01T00:00:00.000Z t:population_stock_number=1696 t:population_stock_name="Snake River Fall Chinook" t:recovery_goal_2=n/a m:wild=720 m:hatchery=0 m:wild_hatchery=720 m:goal_wild=3000

series e:b6j7-zus9 d:1983-01-01T00:00:00.000Z t:population_stock_number=1696 t:population_stock_name="Snake River Fall Chinook" t:recovery_goal_2=n/a m:wild=428 m:hatchery=118 m:wild_hatchery=546 m:goal_wild=3000

series e:b6j7-zus9 d:1984-01-01T00:00:00.000Z t:population_stock_number=1696 t:population_stock_name="Snake River Fall Chinook" t:recovery_goal_2=n/a m:wild=324 m:hatchery=316 m:wild_hatchery=640 m:goal_wild=3000
```

## Meta Commands

```ls
metric m:wild p:integer l:"Wild Spawners" t:dataTypeName=number

metric m:hatchery p:double l:"Hatchery Origin Spawners" t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Recovery Goal 1" t:dataTypeName=number

entity e:b6j7-zus9 l:"Snake Final Abundance 01022013" t:url=https://data.wa.gov/api/views/b6j7-zus9

property e:b6j7-zus9 t:meta.view v:id=b6j7-zus9 v:averageRating=0 v:name="Snake Final Abundance 01022013"

property e:b6j7-zus9 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:b6j7-zus9 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | recovery_goal_2 | population_stock_name    | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | =============== | ======================== | ============ | 
| 1696                    | 1982 | 720  | 0        | 720           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1983 | 428  | 118      | 546           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1984 | 324  | 316      | 640           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1985 | 438  | 253      | 691           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1986 | 449  | 335      | 784           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1987 | 253  | 698      | 951           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1988 | 368  | 268      | 636           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1989 | 295  | 411      | 706           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1990 | 78   | 307      | 385           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
| 1696                    | 1991 | 318  | 312      | 630           | 3000      | n/a             | Snake River Fall Chinook | 1992         | 
```