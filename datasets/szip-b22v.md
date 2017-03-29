# Statewide Hatchery Rollup

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-hatchery-rollup-cbaab) |
| Metadata | [Link](https://data.wa.gov/api/views/szip-b22v) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/szip-b22v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/szip-b22v/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | szip-b22v |
| Name | Statewide Hatchery Rollup |
| Created | 2012-12-05T01:33:47Z |
| Publication Date | 2012-12-05T02:57:46Z |

## Columns

```ls
| Included | Schema Type | Field Name    | Name                | Data Type | Render Type |
| ======== | =========== | ============= | =================== | ========= | =========== |
| No       | time        | :updated_at   | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | wdfw_programs | WDFW Programs . . . | text      | text        |
| No       |             | _1            | 1998                | number    | number      |
| No       |             | _2            | 2008                | number    | number      |
| No       |             | _3            | 2010                | number    | number      |
| No       |             | _4            | 2011                | number    | number      |
| No       |             | _5            | 2012                | number    | number      |
| No       |             | _6            | 2013                | number    | number      |
| No       |             | _7            | 2014                | number    | number      |
| No       |             | _8            | 2015                | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5,_6,_7,_8
```

## Data Commands

```ls
series e:szip-b22v d:2012-12-04T18:57:33.000Z t:wdfw_programs="Meeting or will meet" m:row_number.szip-b22v=1

series e:szip-b22v d:2012-12-04T18:57:33.000Z t:wdfw_programs="Not meeting" m:row_number.szip-b22v=2

series e:szip-b22v d:2012-12-04T18:57:33.000Z t:wdfw_programs="Needing agreements" m:row_number.szip-b22v=3
```

## Meta Commands

```ls
metric m:row_number.szip-b22v p:long l:"Row Number"

entity e:szip-b22v l:"Statewide Hatchery Rollup" t:url=https://data.wa.gov/api/views/szip-b22v

property e:szip-b22v t:meta.view v:id=szip-b22v v:averageRating=0 v:name="Statewide Hatchery Rollup"

property e:szip-b22v t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:szip-b22v t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | wdfw_programs        | _1 | _2 | _3 | _4 | _5 | _6 | _7 | _8 | 
| =========== | ==================== | == | == | == | == | == | == | == | == | 
| 1354647453  | Meeting or will meet | 18 | 25 | 45 | 61 | 69 | 75 | 80 | 90 | 
| 1354647453  | Not meeting          | 82 | 75 | 55 | 39 | 16 | 13 | 11 | 10 | 
| 1354647453  | Needing agreements   | 0  | 0  | 0  | 0  | 15 | 12 | 8  | 0  | 
```