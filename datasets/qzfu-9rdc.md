# OEIG FY12 Annual Report - Number of Complaints Received by Type (Appendix II)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-fy12-annual-report-number-of-complaints-received-by-type-appendix-ii-62ade) |
| Metadata | [Link](https://data.illinois.gov/api/views/qzfu-9rdc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qzfu-9rdc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qzfu-9rdc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qzfu-9rdc |
| Name | OEIG FY12 Annual Report - Number of Complaints Received by Type (Appendix II) |
| Created | 2013-01-08T20:23:33Z |
| Publication Date | 2013-01-08T20:26:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | primary_alleged_misconduct | PRIMARY ALLEGED MISCONDUCT | text      | text        |
| Yes      | numeric metric | fy11                       | FY11                       | number    | number      |
| Yes      | numeric metric | fy12                       | FY12                       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qzfu-9rdc d:2013-01-08T12:23:34.000Z t:primary_alleged_misconduct=Abuse m:fy11=29 m:fy12=42

series e:qzfu-9rdc d:2013-01-08T12:23:34.000Z t:primary_alleged_misconduct="Abuse of Time" m:fy11=94 m:fy12=127

series e:qzfu-9rdc d:2013-01-08T12:23:34.000Z t:primary_alleged_misconduct="Americans with Disabilities Act Violations" m:fy11=1 m:fy12=1
```

## Meta Commands

```ls
metric m:fy11 p:integer l:FY11 t:dataTypeName=number

metric m:fy12 p:integer l:FY12 t:dataTypeName=number

entity e:qzfu-9rdc l:"OEIG FY12 Annual Report - Number of Complaints Received by Type (Appendix II)" t:url=https://data.illinois.gov/api/views/qzfu-9rdc

property e:qzfu-9rdc t:meta.view v:id=qzfu-9rdc v:averageRating=0 v:name="OEIG FY12 Annual Report - Number of Complaints Received by Type (Appendix II)"

property e:qzfu-9rdc t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:qzfu-9rdc t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| :updated_at | primary_alleged_misconduct                 | fy11 | fy12 | 
| =========== | ========================================== | ==== | ==== | 
| 1357647814  | Abuse                                      | 29   | 42   | 
| 1357647814  | Abuse of Time                              | 94   | 127  | 
| 1357647814  | Americans with Disabilities Act Violations | 1    | 1    | 
| 1357647814  | Bid-Rigging                                | 4    | 2    | 
| 1357647814  | Breach of Confidentiality                  | 19   | 31   | 
| 1357647814  | Bribery                                    | 4    | 5    | 
| 1357647814  | Child Support                              | 9    | 2    | 
| 1357647814  | Conflict of Interest                       | 28   | 56   | 
| 1357647814  | Corruption                                 | 5    | 4    | 
| 1357647814  | Discrimination                             | 26   | 27   | 
```