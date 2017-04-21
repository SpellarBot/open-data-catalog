# HFD Public Education

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hfd-public-education) |
| Metadata | [Link](https://data.hartford.gov/api/views/e9py-nv9q) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/e9py-nv9q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/e9py-nv9q/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | e9py-nv9q |
| Name | HFD Public Education |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | fire, public safety, hartford, ct |
| Created | 2015-09-11T12:54:35Z |
| Publication Date | 2015-09-11T13:19:58Z |

## Description

This data set represents the number of public education sessions per month performed by the Fire Marshals office.  It is being used for our GovStat website to measure performance.  Updated the first day of every month.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | numeric metric | numberofsessions | NumberOfSessions | number        | number        |
| Yes      | numeric metric | adults           | Adults           | number        | number        |
| Yes      | numeric metric | children         | Children         | number        | number        |
| Yes      | time           | date             | Date             | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:e9py-nv9q d:2013-11-01T00:00:00.000Z m:numberofsessions=18 m:adults=431 m:children=891

series e:e9py-nv9q d:2015-02-01T00:00:00.000Z m:numberofsessions=4 m:adults=43 m:children=64

series e:e9py-nv9q d:2015-12-01T00:00:00.000Z m:numberofsessions=7 m:adults=344 m:children=742
```

## Meta Commands

```ls
metric m:numberofsessions p:integer l:NumberOfSessions t:dataTypeName=number

metric m:adults p:integer l:Adults t:dataTypeName=number

metric m:children p:integer l:Children t:dataTypeName=number

entity e:e9py-nv9q l:"HFD Public Education" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/e9py-nv9q

property e:e9py-nv9q t:meta.view v:id=e9py-nv9q v:category="Public Safety" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="HFD Public Education" v:attribution="City of Hartford"

property e:e9py-nv9q t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:e9py-nv9q t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:e9py-nv9q t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| numberofsessions | adults | children | date                | 
| ================ | ====== | ======== | =================== | 
| 18               | 431    | 891      | 2013-11-01T00:00:00 | 
| 4                | 43     | 64       | 2015-02-01T00:00:00 | 
| 7                | 344    | 742      | 2015-12-01T00:00:00 | 
| 73               | 3803   | 3999     | 2011-10-01T00:00:00 | 
| 14               | 312    | 759      | 2014-01-01T00:00:00 | 
| 27               | 1243   | 850      | 2011-11-01T00:00:00 | 
| 17               | 1607   | 689      | 2013-12-01T00:00:00 | 
| 14               | 398    | 1013     | 2014-11-01T00:00:00 | 
| 37               | 2927   | 3365     | 2012-06-01T00:00:00 | 
| 35               | 3677   | 3594     | 2012-09-01T00:00:00 | 
```