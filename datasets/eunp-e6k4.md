# Special Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-expenditures-c969e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/eunp-e6k4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/eunp-e6k4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/eunp-e6k4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | eunp-e6k4 |
| Name | Special Expenditures |
| Category | Government-Wide Support |
| Created | 2014-02-03T02:57:34Z |
| Publication Date | 2014-02-03T03:05:52Z |

## Description

FY 13 - 01-12

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | dept        | Dept       | text      | text        |
| Yes      | series tag     | pgm_id      | Pgm ID     | text      | text        |
| Yes      | series tag     | obj_code    | Obj code   | text      | text        |
| Yes      | numeric metric | amount      | Amount     | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eunp-e6k4 d:2014-02-02T18:57:38.000Z t:obj_code=6900 t:dept="LABOR AND INDUSTRIAL RELATIONS" t:pgm_id=LBR171 m:amount=544431.63

series e:eunp-e6k4 d:2014-02-02T18:57:38.000Z t:obj_code=6900 t:dept="LABOR AND INDUSTRIAL RELATIONS" t:pgm_id=LBR171 m:amount=4683602.33

series e:eunp-e6k4 d:2014-02-02T18:57:38.000Z t:obj_code=3140 t:dept=TRANSPORTATION t:pgm_id=TRN501 m:amount=19502.4
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:eunp-e6k4 l:"Special Expenditures" t:url=https://data.hawaii.gov/api/views/eunp-e6k4

property e:eunp-e6k4 t:meta.view v:id=eunp-e6k4 v:category="Government-Wide Support" v:averageRating=0 v:name="Special Expenditures"

property e:eunp-e6k4 t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:eunp-e6k4 t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | dept                           | pgm_id | obj_code | amount     | 
| =========== | ============================== | ====== | ======== | ========== | 
| 1391367458  | LABOR AND INDUSTRIAL RELATIONS | LBR171 | 6900     | 544431.63  | 
| 1391367458  | LABOR AND INDUSTRIAL RELATIONS | LBR171 | 6900     | 4683602.33 | 
| 1391367458  | TRANSPORTATION                 | TRN501 | 3140     | 19502.40   | 
| 1391367458  | TRANSPORTATION                 | TRN501 | 5832     | 25422.00   | 
| 1391367458  | TRANSPORTATION                 | TRN501 | 5812     | 8560.00    | 
| 1391367458  | TRANSPORTATION                 | TRN501 | 5862     | 14000.00   | 
| 1391367458  | DEFENSE                        | DEF110 | 5825     | 13671.24   | 
| 1391367458  | HEALTH                         | HTH840 | 7290     | 7142.40    | 
| 1391367458  | HEALTH                         | HTH840 | 7290     | 22261.45   | 
| 1391367458  | HEALTH                         | HTH730 | 7290     | 24284.54   | 
```