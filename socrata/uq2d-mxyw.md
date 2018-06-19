# HC LULC 01162013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hc-lulc-01162013-29d87) |
| Metadata | [Link](https://data.wa.gov/api/views/uq2d-mxyw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/uq2d-mxyw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/uq2d-mxyw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | uq2d-mxyw |
| Name | HC LULC 01162013 |
| Created | 2013-01-16T17:33:45Z |
| Publication Date | 2013-01-16T17:52:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | region      | Region     | text      | text        |
| Yes      | series tag     | category    | Category   | text      | text        |
| Yes      | numeric metric | percent     | Percent    | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uq2d-mxyw d:2013-01-16T09:52:04.000Z t:region="Hood Canal1" t:category=Development m:percent=0.82

series e:uq2d-mxyw d:2013-01-16T09:52:04.000Z t:region="Hood Canal1" t:category=Forestry m:percent=91

series e:uq2d-mxyw d:2013-01-16T09:52:04.000Z t:region="Hood Canal1" t:category=Natural m:percent=7
```

## Meta Commands

```ls
metric m:percent p:double l:Percent t:dataTypeName=percent

entity e:uq2d-mxyw l:"HC LULC 01162013" t:url=https://data.wa.gov/api/views/uq2d-mxyw

property e:uq2d-mxyw t:meta.view v:id=uq2d-mxyw v:averageRating=0 v:name="HC LULC 01162013"

property e:uq2d-mxyw t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:uq2d-mxyw t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region      | category    | percent | 
| =========== | =========== | =========== | ======= | 
| 1358329924  | Hood Canal1 | Development | 0.82    | 
| 1358329924  | Hood Canal1 | Forestry    | 91      | 
| 1358329924  | Hood Canal1 | Natural     | 7       | 
| 1358329924  | Hood Canal2 | Development | 25      | 
| 1358329924  | Hood Canal2 | Forestry    | 75      | 
```