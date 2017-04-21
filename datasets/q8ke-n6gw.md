# Department of Public Safety Weekly Population Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-public-safety-weekly-population-reports-dad5d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/q8ke-n6gw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/q8ke-n6gw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/q8ke-n6gw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | q8ke-n6gw |
| Name | Department of Public Safety Weekly Population Reports |
| Attribution | PSD |
| Category | Public Safety |
| Created | 2013-06-07T23:54:28Z |
| Publication Date | 2013-08-06T23:07:30Z |

## Description

July 2012 - July 31, 2013 Attached PSD definitions for data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| No       |                | date        | Date        | text      | text        |
| Yes      | series tag     | facility    | Facility    | text      | text        |
| Yes      | series tag     | location    | location    | text      | text        |
| Yes      | series tag     | description | description | text      | text        |
| Yes      | numeric metric | male        | male        | number    | number      |
| Yes      | numeric metric | female      | female      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:q8ke-n6gw d:2013-08-06T16:07:03.000Z t:facility=hccc t:location=hi t:description=head-count-ending-sent-fel m:female=7 m:male=63

series e:q8ke-n6gw d:2013-08-06T16:07:03.000Z t:facility=hccc t:location=hi t:description=head-count-ending-sent-fel-prob m:female=21 m:male=67

series e:q8ke-n6gw d:2013-08-06T16:07:03.000Z t:facility=hccc t:location=hi t:description=head-count-ending-sent-misd m:female=5 m:male=37
```

## Meta Commands

```ls
metric m:male p:integer l:male t:dataTypeName=number

metric m:female p:integer l:female t:dataTypeName=number

entity e:q8ke-n6gw l:"Department of  Public Safety Weekly Population Reports" t:attribution=PSD t:url=https://data.hawaii.gov/api/views/q8ke-n6gw

property e:q8ke-n6gw t:meta.view v:id=q8ke-n6gw v:category="Public Safety" v:averageRating=0 v:name="Department of  Public Safety Weekly Population Reports" v:attribution=PSD

property e:q8ke-n6gw t:meta.view.license v:name="Public Domain"

property e:q8ke-n6gw t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:q8ke-n6gw t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | date     | facility | location | description                     | male | female | 
| =========== | ======== | ======== | ======== | =============================== | ==== | ====== | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-sent-fel      | 63   | 7      | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-sent-fel-prob | 67   | 21     | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-sent-misd     | 37   | 5      | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-pretrial-fel  | 84   | 12     | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-pretrial-misd | 23   | 6      | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-other-juris   | 3    | 1      | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-par-viol      | 11   | 1      | 
| 1375805223  | 2-Jul-12 | hccc     | hi       | head-count-ending-prb-viol      | 17   | 2      | 
| 1375805223  | 2-Jul-12 | hmsf     | hi       | head-count-ending-sent-fel      | 692  |        | 
| 1375805223  | 2-Jul-12 | hmsf     | hi       | head-count-ending-sent-fel-prob |      |        | 
```