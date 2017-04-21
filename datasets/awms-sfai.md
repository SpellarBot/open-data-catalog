# OEIG Monthly Report - October 2013 (Pending Investigations As Of September 30, 2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-monthly-report-october-2013-pending-investigations-as-of-september-30-2013-72a00) |
| Metadata | [Link](https://data.illinois.gov/api/views/awms-sfai) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/awms-sfai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/awms-sfai/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | awms-sfai |
| Name | OEIG Monthly Report - October 2013 (Pending Investigations As Of September 30, 2013) |
| Created | 2013-11-20T13:36:32Z |
| Publication Date | 2013-11-20T13:41:37Z |

## Description

Pursuant to the State Officials and Employees Ethics Act, 5 ILCS 430/20-85, each executive inspector general shall submit monthly reports to the appropriate branch constitutional officer and shall also post the monthly reports on his or her website.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | september_2013 | September 2013 | text      | text        |
| Yes      | numeric metric | number         | Number         | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:awms-sfai d:2013-01-01T00:00:00.000Z t:september_2013="Number of allegations received:" m:number=241

series e:awms-sfai d:2013-01-01T00:00:00.000Z t:september_2013="Number of investigations initiated:" m:number=5

series e:awms-sfai d:2013-01-01T00:00:00.000Z t:september_2013="Number of investigations concluded:" m:number=5
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:awms-sfai l:"OEIG Monthly Report - October 2013 (Pending Investigations As Of September 30, 2013)" t:url=https://data.illinois.gov/api/views/awms-sfai

property e:awms-sfai t:meta.view v:id=awms-sfai v:averageRating=0 v:name="OEIG Monthly Report - October 2013 (Pending Investigations As Of September 30, 2013)"

property e:awms-sfai t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:awms-sfai t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| september_2013                                                                                  | number | 
| =============================================================================================== | ====== | 
| Number of allegations received:                                                                 | 241    | 
| Number of investigations initiated:                                                             | 5      | 
| Number of investigations concluded:                                                             | 5      | 
| Number of investigations pending:1                                                              | 123    | 
| Number of complaints forwarded to the Attorney General for Executive Ethics Commission hearing: | 1      | 
| Number of pending matters with the Executive Ethics Commission:                                 | 4      | 
| Number of allegations referred to law enforcement:                                              | 51     | 
```