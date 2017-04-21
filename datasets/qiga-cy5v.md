# DCEO IL Coal Balance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-il-coal-balance-a0e3f) |
| Metadata | [Link](https://data.illinois.gov/api/views/qiga-cy5v) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qiga-cy5v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qiga-cy5v/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qiga-cy5v |
| Name | DCEO IL Coal Balance |
| Category | Economics |
| Tags | coal balance |
| Created | 2012-01-27T21:59:12Z |
| Publication Date | 2012-01-27T22:00:01Z |

## Description

Illinois Coal Balance

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                        | Data Type | Render Type |
| ======== | =========== | ========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | coal_balance_million_tons_ | Coal Balance (million tons) | text      | text        |
| No       |             | _1                         | 2009                        | number    | number      |
| No       |             | _2                         | 2010                        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2
```

## Data Commands

```ls
series e:qiga-cy5v d:2012-01-27T13:59:22.000Z t:coal_balance_million_tons_=Production m:row_number.qiga-cy5v=1

series e:qiga-cy5v d:2012-01-27T13:59:22.000Z t:coal_balance_million_tons_=Consumption m:row_number.qiga-cy5v=2

series e:qiga-cy5v d:2012-01-27T13:59:22.000Z t:coal_balance_million_tons_="Consumption of IL coal" m:row_number.qiga-cy5v=3
```

## Meta Commands

```ls
metric m:row_number.qiga-cy5v p:long l:"Row Number"

entity e:qiga-cy5v l:"DCEO IL Coal Balance" t:url=https://data.illinois.gov/api/views/qiga-cy5v

property e:qiga-cy5v t:meta.view v:id=qiga-cy5v v:category=Economics v:averageRating=0 v:name="DCEO IL Coal Balance"

property e:qiga-cy5v t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:qiga-cy5v t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | coal_balance_million_tons_  | _1    | _2    | 
| =========== | =========================== | ===== | ===== | 
| 1327672762  | Production                  | 33748 | 33241 | 
| 1327672762  | Consumption                 | 55155 | 59950 | 
| 1327672762  | Consumption of IL coal      | 4427  | 4839  | 
| 1327672762  | Consumption of Western coal | 50258 | 55111 | 
| 1327672762  | Consumption of other coal   | 470   | 1834  | 
```