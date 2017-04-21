# Puget Sound Final Abundance (Chinook) 11152012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/puget-sound-final-abundance-chinook-11152012-f65c0) |
| Metadata | [Link](https://data.wa.gov/api/views/xzqf-dbht) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xzqf-dbht/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xzqf-dbht/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xzqf-dbht |
| Name | Puget Sound Final Abundance (Chinook) 11152012 |
| Created | 2012-11-15T14:10:47Z |
| Publication Date | 2012-11-15T14:12:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery                | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery         | number    | number      |
| Yes      | numeric metric | goal_wild_1             | Goal (Wild)1            | number    | number      |
| Yes      | numeric metric | goal_wild_2             | Goal (Wild)2            | number    | number      |
| Yes      | numeric metric | goal_wild_3             | Goal (Wild)3            | number    | number      |
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
series e:xzqf-dbht d:1984-01-01T00:00:00.000Z t:population_stock_number=1008 t:population_stock_name="North Fork Nooksack Chinook" m:wild=43 m:hatchery=3 m:wild_hatchery=46 m:goal_wild_3=9900 m:goal_wild_2=16000 m:goal_wild_1=3800

series e:xzqf-dbht d:1985-01-01T00:00:00.000Z t:population_stock_number=1008 t:population_stock_name="North Fork Nooksack Chinook" m:wild=225 m:hatchery=31 m:wild_hatchery=256 m:goal_wild_3=9900 m:goal_wild_2=16000 m:goal_wild_1=3800

series e:xzqf-dbht d:1986-01-01T00:00:00.000Z t:population_stock_number=1008 t:population_stock_name="North Fork Nooksack Chinook" m:wild=183 m:hatchery=43 m:wild_hatchery=226 m:goal_wild_3=9900 m:goal_wild_2=16000 m:goal_wild_1=3800
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:integer l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild_1 p:integer l:"Goal (Wild)1" t:dataTypeName=number

metric m:goal_wild_2 p:integer l:"Goal (Wild)2" t:dataTypeName=number

metric m:goal_wild_3 p:integer l:"Goal (Wild)3" t:dataTypeName=number

entity e:xzqf-dbht l:"Puget Sound Final Abundance (Chinook) 11152012" t:url=https://data.wa.gov/api/views/xzqf-dbht

property e:xzqf-dbht t:meta.view v:id=xzqf-dbht v:averageRating=0 v:name="Puget Sound Final Abundance (Chinook) 11152012"

property e:xzqf-dbht t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:xzqf-dbht t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild_1 | goal_wild_2 | goal_wild_3 | population_stock_name       | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | =========== | =========== | =========== | =========================== | ============ | 
| 1008                    | 1984 | 43   | 3        | 46            | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1985 | 225  | 31       | 256           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1986 | 183  | 43       | 226           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1987 | 136  | 45       | 181           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1988 | 298  | 154      | 452           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1989 | 217  | 84       | 301           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1990 | 4    | 6        | 10            | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1991 | 79   | 29       | 108           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1992 | 334  | 164      | 498           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
| 1008                    | 1993 | 183  | 263      | 446           | 3800        | 16000       | 9900        | North Fork Nooksack Chinook | 1999         | 
```