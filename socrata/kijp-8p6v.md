# OEIG Monthly Report - January 2013 (Pending investigations as of December 31, 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-monthly-report-january-2013-pending-investigations-as-of-december-31-2012-e87a3) |
| Metadata | [Link](https://data.illinois.gov/api/views/kijp-8p6v) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kijp-8p6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kijp-8p6v/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kijp-8p6v |
| Name | OEIG Monthly Report - January 2013 (Pending investigations as of December 31, 2012) |
| Created | 2013-01-18T14:36:05Z |
| Publication Date | 2013-09-16T14:02:53Z |

## Description

Pursuant to the State Officials and Employees Ethics Act, 5 ILCS 430/20-85, each executive inspector general shall submit monthly reports to the appropriate branch constitutional officer and shall also post the monthly reports on his or her website.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name          | Data Type | Render Type |
| ======== | ============== | ============ | ============= | ========= | =========== |
| Yes      | series tag     | january_2013 | December 2012 | text      | text        |
| Yes      | numeric metric | number       | Number        | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kijp-8p6v d:2013-01-01T00:00:00.000Z t:january_2013="Number of allegations received:" m:number=247

series e:kijp-8p6v d:2013-01-01T00:00:00.000Z t:january_2013="Number of investigations initiated:" m:number=5

series e:kijp-8p6v d:2013-01-01T00:00:00.000Z t:january_2013="Number of investigations concluded:" m:number=13
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:kijp-8p6v l:"OEIG Monthly Report - January 2013 (Pending investigations as of December 31, 2012)" t:url=https://data.illinois.gov/api/views/kijp-8p6v

property e:kijp-8p6v t:meta.view v:id=kijp-8p6v v:averageRating=0 v:name="OEIG Monthly Report - January 2013 (Pending investigations as of December 31, 2012)"

property e:kijp-8p6v t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:kijp-8p6v t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| january_2013                                                                                    | number | 
| =============================================================================================== | ====== | 
| Number of allegations received:                                                                 | 247    | 
| Number of investigations initiated:                                                             | 5      | 
| Number of investigations concluded:                                                             | 13     | 
| Number of investigations pending:                                                               | 113    | 
| Number of allegations referred to law enforcement:                                              | 56     | 
| Number of complaints forwarded to the Attorney General for Executive Ethics Commission hearing: | 0      | 
| Number of pending matters with the Executive Ethics Commission:                                 | 3      | 
```