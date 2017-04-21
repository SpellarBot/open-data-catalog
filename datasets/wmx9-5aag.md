# OEIG Monthly Report - December 2012 (Pending investigations as of November 30, 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-monthly-report-december-2012-pending-investigations-as-of-november-30-2012-d0d44) |
| Metadata | [Link](https://data.illinois.gov/api/views/wmx9-5aag) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wmx9-5aag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wmx9-5aag/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wmx9-5aag |
| Name | OEIG Monthly Report - December 2012 (Pending investigations as of November 30, 2012) |
| Created | 2013-01-18T14:31:15Z |
| Publication Date | 2013-09-16T14:03:36Z |

## Description

Pursuant to the State Officials and Employees Ethics Act, 5 ILCS 430/20-85, each executive inspector general shall submit monthly reports to the appropriate branch constitutional officer and shall also post the monthly reports on his or her website.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | december_2012 | November 2012 | text      | text        |
| Yes      | numeric metric | number        | Number        | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wmx9-5aag d:2012-01-01T00:00:00.000Z t:december_2012="Number of allegations received:" m:number=235

series e:wmx9-5aag d:2012-01-01T00:00:00.000Z t:december_2012="Number of investigations initiated:" m:number=11

series e:wmx9-5aag d:2012-01-01T00:00:00.000Z t:december_2012="Number of investigations concluded:" m:number=6
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:wmx9-5aag l:"OEIG Monthly Report - December 2012 (Pending investigations as of November 30, 2012)" t:url=https://data.illinois.gov/api/views/wmx9-5aag

property e:wmx9-5aag t:meta.view v:id=wmx9-5aag v:averageRating=0 v:name="OEIG Monthly Report - December 2012 (Pending investigations as of November 30, 2012)"

property e:wmx9-5aag t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:wmx9-5aag t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| december_2012                                                                                   | number | 
| =============================================================================================== | ====== | 
| Number of allegations received:                                                                 | 235    | 
| Number of investigations initiated:                                                             | 11     | 
| Number of investigations concluded:                                                             | 6      | 
| Number of complaints forwarded to the Attorney General for Executive Ethics Commission hearing: | 0      | 
| Number of pending matters with the Executive Ethics Commission:                                 | 2      | 
| Number of allegations referred to law enforcement:                                              | 41     | 
| Number of investigations pending:                                                               | 121    | 
```