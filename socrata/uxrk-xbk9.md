# OEIG FY12 Annual Report - Number of Founded Complaints by Agency (Appendix III)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-fy12-annual-report-number-of-founded-complaints-by-agency-appendix-iii-aac44) |
| Metadata | [Link](https://data.illinois.gov/api/views/uxrk-xbk9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/uxrk-xbk9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/uxrk-xbk9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | uxrk-xbk9 |
| Name | OEIG FY12 Annual Report - Number of Founded Complaints by Agency (Appendix III) |
| Created | 2013-01-08T20:28:20Z |
| Publication Date | 2013-01-08T20:30:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | agency_name | Agency Name | text      | text        |
| Yes      | numeric metric | fy11        | FY11        | number    | number      |
| Yes      | numeric metric | fy12        | FY12        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uxrk-xbk9 d:2013-01-08T12:28:22.000Z t:agency_name="Aging, Department on" m:fy11=1 m:fy12=0

series e:uxrk-xbk9 d:2013-01-08T12:28:22.000Z t:agency_name="Agriculture, Department of" m:fy11=1 m:fy12=0

series e:uxrk-xbk9 d:2013-01-08T12:28:22.000Z t:agency_name="Board of Higher Education, State" m:fy11=1 m:fy12=0
```

## Meta Commands

```ls
metric m:fy11 p:integer l:FY11 t:dataTypeName=number

metric m:fy12 p:integer l:FY12 t:dataTypeName=number

entity e:uxrk-xbk9 l:"OEIG FY12 Annual Report - Number of Founded Complaints by Agency (Appendix III)" t:url=https://data.illinois.gov/api/views/uxrk-xbk9

property e:uxrk-xbk9 t:meta.view v:id=uxrk-xbk9 v:averageRating=0 v:name="OEIG FY12 Annual Report - Number of Founded Complaints by Agency (Appendix III)"

property e:uxrk-xbk9 t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:uxrk-xbk9 t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| :updated_at | agency_name                                      | fy11 | fy12 | 
| =========== | ================================================ | ==== | ==== | 
| 1357648102  | Aging, Department on                             | 1    | 0    | 
| 1357648102  | Agriculture, Department of                       | 1    | 0    | 
| 1357648102  | Board of Higher Education, State                 | 1    | 0    | 
| 1357648102  | Capital Development Board                        | 1    | 0    | 
| 1357648102  | Central Management Services, Department of       | 2    | 1    | 
| 1357648102  | Chicago Transit Authority                        | 0    | 2    | 
| 1357648102  | Children and Family Services, Department of      | 1    | 0    | 
| 1357648102  | Commerce and Economic Opportunity, Department of | 2    | 0    | 
| 1357648102  | Corrections, Department of                       | 6    | 2    | 
| 1357648102  | Eastern Illinois University                      | 4    | 0    | 
```