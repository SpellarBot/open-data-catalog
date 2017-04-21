# Major Object Descriptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/major-object-descriptions-479b1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mk6a-j3ft) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mk6a-j3ft/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mk6a-j3ft/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mk6a-j3ft |
| Name | Major Object Descriptions |
| Created | 2014-01-31T19:44:50Z |
| Publication Date | 2014-02-01T00:21:11Z |

## Description

for use with Expenditure data

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | object_number      | OBJ CODE           | text      | text        |
| Yes      | series tag  | object_description | Object Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mk6a-j3ft d:2014-01-31T11:44:53.000Z t:object_number=20 t:object_description="Personal Servics - Payroll" m:row_number.mk6a-j3ft=1

series e:mk6a-j3ft d:2014-01-31T11:44:53.000Z t:object_number=21 t:object_description="Personal Services - Payroll" m:row_number.mk6a-j3ft=2

series e:mk6a-j3ft d:2014-01-31T11:44:53.000Z t:object_number=22 t:object_description="Personal Services - Payroll" m:row_number.mk6a-j3ft=3
```

## Meta Commands

```ls
metric m:row_number.mk6a-j3ft p:long l:"Row Number"

entity e:mk6a-j3ft l:"Major Object Descriptions" t:url=https://data.hawaii.gov/api/views/mk6a-j3ft

property e:mk6a-j3ft t:meta.view v:id=mk6a-j3ft v:averageRating=0 v:name="Major Object Descriptions"

property e:mk6a-j3ft t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:mk6a-j3ft t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | object_number | object_description                                  | 
| =========== | ============= | =================================================== | 
| 1391168693  | 20            | Personal Servics - Payroll                          | 
| 1391168693  | 21            | Personal Services - Payroll                         | 
| 1391168693  | 22            | Personal Services - Payroll                         | 
| 1391168693  | 25            | Personal Services - Payroll                         | 
| 1391168693  | 28            | Personal Services (Employer Employee Relationship)  | 
| 1391168693  | 29            | Pers Svcs Rend By Other Dept Agen (State Employees) | 
| 1391168693  | 30            | Operating Supplies                                  | 
| 1391168693  | 31            | Repair and Maintenance Supplies                     | 
| 1391168693  | 32            | Office Supplies                                     | 
| 1391168693  | 33            | Food Supplies                                       | 
```