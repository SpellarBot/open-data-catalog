# OEIG FY12 Annual Report - Number of Founded Complaints by Type (Appendix IV)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-fy12-annual-report-number-of-founded-complaints-by-type-appendix-iv-f1069) |
| Metadata | [Link](https://data.illinois.gov/api/views/xb2x-ki6u) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xb2x-ki6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xb2x-ki6u/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xb2x-ki6u |
| Name | OEIG FY12 Annual Report - Number of Founded Complaints by Type (Appendix IV) |
| Created | 2013-01-08T20:32:54Z |
| Publication Date | 2013-01-08T20:34:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | primary_type | Primary Type | text      | text        |
| Yes      | numeric metric | fy11         | FY11         | number    | number      |
| Yes      | numeric metric | fy12         | FY12         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xb2x-ki6u d:2013-01-08T12:32:55.000Z t:primary_type="Abuse of Time" m:fy11=16 m:fy12=1

series e:xb2x-ki6u d:2013-01-08T12:32:55.000Z t:primary_type=Bid-Rigging m:fy11=0 m:fy12=1

series e:xb2x-ki6u d:2013-01-08T12:32:55.000Z t:primary_type="Breach of Confidentiality" m:fy11=1 m:fy12=0
```

## Meta Commands

```ls
metric m:fy11 p:integer l:FY11 t:dataTypeName=number

metric m:fy12 p:integer l:FY12 t:dataTypeName=number

entity e:xb2x-ki6u l:"OEIG FY12 Annual Report - Number of Founded Complaints by Type (Appendix IV)" t:url=https://data.illinois.gov/api/views/xb2x-ki6u

property e:xb2x-ki6u t:meta.view v:id=xb2x-ki6u v:averageRating=0 v:name="OEIG FY12 Annual Report - Number of Founded Complaints by Type (Appendix IV)"

property e:xb2x-ki6u t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:xb2x-ki6u t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| :updated_at | primary_type                    | fy11 | fy12 | 
| =========== | =============================== | ==== | ==== | 
| 1357648375  | Abuse of Time                   | 16   | 1    | 
| 1357648375  | Bid-Rigging                     | 0    | 1    | 
| 1357648375  | Breach of Confidentiality       | 1    | 0    | 
| 1357648375  | Bribery                         | 1    | 0    | 
| 1357648375  | Conflict of Interest            | 6    | 2    | 
| 1357648375  | Discrimination                  | 1    | 0    | 
| 1357648375  | Failure to Follow Agency Policy | 0    | 1    | 
| 1357648375  | False Employment Application    | 1    | 0    | 
| 1357648375  | Fraud                           | 10   | 3    | 
| 1357648375  | Ghost Pay Rolling               | 1    | 2    | 
```