# OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-monthly-report-november-2012-pending-investigations-as-of-october-31-2012-0b595) |
| Metadata | [Link](https://data.illinois.gov/api/views/as52-whec) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/as52-whec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/as52-whec/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | as52-whec |
| Name | OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012) |
| Created | 2013-01-16T16:54:39Z |
| Publication Date | 2013-09-16T14:04:27Z |
| Rows Updated | 2013-09-16T14:04:03Z |

## Description

Pursuant to the State Officials and Employees Ethics Act, 5 ILCS 430/20-85, each executive inspector general shall submit monthly reports to the appropriate branch constitutional officer and shall also post the monthly reports on his or her website.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name         | Data Type | Render Type |
| ======== | ============== | ============= | ============ | ========= | =========== |
| Yes      | series tag     | november_2012 | October 2012 | text      | text        |
| Yes      | numeric metric | number        | Number       | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:as52-whec d:2012-01-01T00:00:00.000Z t:november_2012="Number of allegations received:" m:number=238

series e:as52-whec d:2012-01-01T00:00:00.000Z t:november_2012="Number of investigations initiated:" m:number=20

series e:as52-whec d:2012-01-01T00:00:00.000Z t:november_2012="Number of investigations concluded:" m:number=14
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:as52-whec l:"OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)" t:url=https://data.illinois.gov/api/views/as52-whec

property e:as52-whec t:meta.view v:id=as52-whec v:averageRating=0 v:name="OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)"

property e:as52-whec t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:as52-whec t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```