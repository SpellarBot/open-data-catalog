# OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/as52-whec/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/oeig-monthly-report-november-2012-pending-investigations-as-of-october-31-2012-0b595)
* [Metadata URL](https://data.illinois.gov/api/views/as52-whec)
* Id = as52-whec
* Name = OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)
* Created = 2013-01-16T16:54:39Z
* Publication Date = 2013-09-16T14:04:27Z
* Rows Updated = 2013-09-16T14:04:03Z

## Description

Pursuant to the State Officials and Employees Ethics Act, 5 ILCS 430/20-85, each executive inspector general shall submit monthly reports to the appropriate branch constitutional officer and shall also post the monthly reports on his or her website.

## Columns

```ls
| Name         | Field Name    | Data Type | Render Type | Schema Type    | Included | 
| ============ | ============= | ========= | =========== | ============== | ======== | 
| updated_at   | :updated_at   | meta_data | meta_data   | time           | No       | 
| October 2012 | november_2012 | text      | text        | series tag     | Yes      | 
| Number       | number        | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:as52-whec d:2013-01-16T08:54:43.000Z t:november_2012="Number of allegations received:" m:number=238

series e:as52-whec d:2013-01-16T08:54:43.000Z t:november_2012="Number of investigations initiated:" m:number=20

series e:as52-whec d:2013-01-16T08:54:43.000Z t:november_2012="Number of investigations concluded:" m:number=14
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:as52-whec l:"OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)" t:url=https://data.illinois.gov/api/views/as52-whec

property e:as52-whec t:meta.view d:2017-03-07T17:26:09.909Z v:id=as52-whec v:averageRating=0 v:name="OEIG Monthly Report - November 2012 (Pending investigations as of October 31, 2012)"

property e:as52-whec t:meta.view.owner d:2017-03-07T17:26:09.909Z v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke

property e:as52-whec t:meta.view.tableauthor d:2017-03-07T17:26:09.909Z v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```