# WA Coast Upload 09242012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-coast-upload-09242012-7c7f3) |
| Metadata | [Link](https://data.wa.gov/api/views/b4xk-sd6y) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/b4xk-sd6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/b4xk-sd6y/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | b4xk-sd6y |
| Name | WA Coast Upload 09242012 |
| Created | 2012-09-24T12:06:06Z |
| Publication Date | 2012-09-24T12:09:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_name | Population/Stock Name   | text      | text        |
| Yes      | time           | year                  | Year                    | number    | number      |
| Yes      | numeric metric | wild                  | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery              | Hatchery                | number    | number      |
| Yes      | numeric metric | total_wild_hatchery   | Total (Wild + Hatchery) | number    | number      |
| Yes      | numeric metric | goal_wild_1           | Goal (Wild)1            | number    | number      |
| Yes      | numeric metric | goal_wild_2           | Goal (Wild)2            | number    | number      |
| No       |                | listing_year          | Listing Year            | number    | number      |
| Yes      | series tag     | source                | Source                  | text      | text        |
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
series e:b4xk-sd6y d:1994-01-01T00:00:00.000Z t:population_stock_name="Ozette Sockeye" t:source="Source Link" m:wild=894 m:total_wild_hatchery=964 m:hatchery=70 m:goal_wild_2=121000 m:goal_wild_1=31250

series e:b4xk-sd6y d:1995-01-01T00:00:00.000Z t:population_stock_name="Ozette Sockeye" t:source="Source Link" m:wild=230 m:total_wild_hatchery=363 m:hatchery=133 m:goal_wild_2=121000 m:goal_wild_1=31250

series e:b4xk-sd6y d:1996-01-01T00:00:00.000Z t:population_stock_name="Ozette Sockeye" t:source="Source Link" m:wild=3725 m:total_wild_hatchery=3931 m:hatchery=206 m:goal_wild_2=121000 m:goal_wild_1=31250
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:total_wild_hatchery p:integer l:"Total (Wild + Hatchery)" t:dataTypeName=number

metric m:goal_wild_1 p:integer l:"Goal (Wild)1" t:dataTypeName=number

metric m:goal_wild_2 p:integer l:"Goal (Wild)2" t:dataTypeName=number

entity e:b4xk-sd6y l:"WA Coast Upload 09242012" t:url=https://data.wa.gov/api/views/b4xk-sd6y

property e:b4xk-sd6y t:meta.view v:id=b4xk-sd6y v:averageRating=0 v:name="WA Coast Upload 09242012"

property e:b4xk-sd6y t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:b4xk-sd6y t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_name | year | wild | hatchery | total_wild_hatchery | goal_wild_1 | goal_wild_2 | listing_year | source      | 
| ===================== | ==== | ==== | ======== | =================== | =========== | =========== | ============ | =========== | 
| Ozette Sockeye        | 1994 | 894  | 70       | 964                 | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 1995 | 230  | 133      | 363                 | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 1996 | 3725 | 206      | 3931                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 1997 | 1052 | 294      | 1346                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 1998 | 1714 | 168      | 1882                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 1999 | 2248 | 372      | 2620                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 2000 | 4208 | 643      | 4851                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 2001 | 3846 | 305      | 4151                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 2002 | 3344 | 478      | 3822                | 31250       | 121000      | 1999         | Source Link | 
| Ozette Sockeye        | 2003 | 4830 | 46       | 4876                | 31250       | 121000      | 1999         | Source Link | 
```