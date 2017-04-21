# Trust Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trust-expenditures-bc8ec) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vvfm-pv8q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vvfm-pv8q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vvfm-pv8q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vvfm-pv8q |
| Name | Trust Expenditures |
| Category | Government-Wide Support |
| Created | 2014-02-03T02:22:38Z |
| Publication Date | 2014-02-03T02:23:55Z |

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
series e:vvfm-pv8q d:2014-02-02T18:22:41.000Z t:obj_code=9200 t:dept="ACCOUNTING AND GENERAL SERVICES" m:amount=63950517.64

series e:vvfm-pv8q d:2014-02-02T18:22:41.000Z t:obj_code=9200 t:dept="ACCOUNTING AND GENERAL SERVICES" m:amount=67071759.23

series e:vvfm-pv8q d:2014-02-02T18:22:41.000Z t:obj_code=7130 t:dept=DEFENSE m:amount=7482
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:vvfm-pv8q l:"Trust Expenditures" t:url=https://data.hawaii.gov/api/views/vvfm-pv8q

property e:vvfm-pv8q t:meta.view v:id=vvfm-pv8q v:category="Government-Wide Support" v:averageRating=0 v:name="Trust Expenditures"

property e:vvfm-pv8q t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:vvfm-pv8q t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | dept                            | pgm_id | obj_code | amount      | 
| =========== | =============================== | ====== | ======== | =========== | 
| 1391365361  | ACCOUNTING AND GENERAL SERVICES |        | 9200     | 63950517.64 | 
| 1391365361  | ACCOUNTING AND GENERAL SERVICES |        | 9200     | 67071759.23 | 
| 1391365361  | DEFENSE                         |        | 7130     | 7482.00     | 
| 1391365361  | DEFENSE                         |        | 7130     | 3200.00     | 
| 1391365361  | DEFENSE                         |        | 7105     | 136         | 
| 1391365361  | DEFENSE                         |        | 7195     | 156.01      | 
| 1391365361  | DEFENSE                         |        | 7195     | 33.51       | 
| 1391365361  | BUDGET AND FINANCE              | BUF143 | 5930     | 35524798.68 | 
| 1391365361  | BUDGET AND FINANCE              | BUF143 | 5930     | 12431348.28 | 
| 1391365361  | BUDGET AND FINANCE              | BUF143 | 5930     | 3875389.24  | 
```