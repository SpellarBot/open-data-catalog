# Department Descriptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-descriptions-6d929) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xa5e-sf37) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xa5e-sf37/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xa5e-sf37/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xa5e-sf37 |
| Name | Department Descriptions |
| Created | 2014-01-31T19:40:39Z |
| Publication Date | 2014-01-31T19:41:56Z |

## Description

to be used with Expenditure data

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | department_code | Department Code | text      | text        |
| Yes      | series tag  | department_name | Department Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xa5e-sf37 d:2014-01-31T11:40:59.000Z t:department_code=A t:department_name=AGRICULTURE m:row_number.xa5e-sf37=1

series e:xa5e-sf37 d:2014-01-31T11:40:59.000Z t:department_code=B t:department_name="BUSINESS, ECONOMIC DEVELOPMENT, AND TOURISM" m:row_number.xa5e-sf37=2

series e:xa5e-sf37 d:2014-01-31T11:40:59.000Z t:department_code=C t:department_name="LAND AND NATURAL RESOURCES" m:row_number.xa5e-sf37=3
```

## Meta Commands

```ls
metric m:row_number.xa5e-sf37 p:long l:"Row Number"

entity e:xa5e-sf37 l:"Department Descriptions" t:url=https://data.hawaii.gov/api/views/xa5e-sf37

property e:xa5e-sf37 t:meta.view v:id=xa5e-sf37 v:averageRating=0 v:name="Department Descriptions"

property e:xa5e-sf37 t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:xa5e-sf37 t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | department_code | department_name                             | 
| =========== | =============== | =========================================== | 
| 1391168459  | A               | AGRICULTURE                                 | 
| 1391168459  | B               | BUSINESS, ECONOMIC DEVELOPMENT, AND TOURISM | 
| 1391168459  | C               | LAND AND NATURAL RESOURCES                  | 
| 1391168459  | D               | TRANSPORTATION                              | 
| 1391168459  | E               | EDUCATION                                   | 
| 1391168459  | F               | UNIVERSITY OF HAWAII                        | 
| 1391168459  | G               | DEFENSE                                     | 
| 1391168459  | H               | HEALTH                                      | 
| 1391168459  | I               | HAWAIIAN HOME LANDS                         | 
| 1391168459  | J               | JUDICIARY                                   | 
```