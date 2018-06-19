# Fire Response Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-response-compliance) |
| Metadata | [Link](https://data.srcity.org/api/views/q3vj-z25u) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/q3vj-z25u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/q3vj-z25u/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | q3vj-z25u |
| Name | Fire Response Compliance |
| Category | Fire |
| Tags | compliance |
| Created | 2016-02-17T14:31:29Z |
| Publication Date | 2017-02-01T14:50:44Z |

## Description

In 2007, the Council modified the Fire Department Response Time Standard to be in compliance with NFPA 1710 recommendations.  The Fire Department shall achieve 90% performance of arrival of the first fire company at an emergency within five minutes of notification by the dispatch center.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | year       | Year       | number    | number      |
| Yes      | numeric metric | percentage | Percentage | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q3vj-z25u d:2013-01-01T00:00:00.000Z m:percentage=71.23

series e:q3vj-z25u d:2008-01-01T00:00:00.000Z m:percentage=71.56

series e:q3vj-z25u d:2011-01-01T00:00:00.000Z m:percentage=74.25
```

## Meta Commands

```ls
metric m:percentage p:float l:Percentage t:dataTypeName=percent

entity e:q3vj-z25u l:"Fire Response Compliance" t:url=https://data.srcity.org/api/views/q3vj-z25u

property e:q3vj-z25u t:meta.view v:id=q3vj-z25u v:category=Fire v:averageRating=0 v:name="Fire Response Compliance"

property e:q3vj-z25u t:meta.view.owner v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:displayName="Reese, Jackie"

property e:q3vj-z25u t:meta.view.tableauthor v:id=jizs-3xc2 v:screenName="Reese, Jackie" v:roleName=publisher v:displayName="Reese, Jackie"
```

## Top Records

```ls
| year | percentage | 
| ==== | ========== | 
| 2013 | 71.23      | 
| 2008 | 71.56      | 
| 2011 | 74.25      | 
| 2014 | 74.12      | 
| 2007 | 72.31      | 
| 2012 | 71.52      | 
| 2009 | 74.09      | 
| 2010 | 75.8       | 
| 2015 | 72.22      | 
| 2016 | 73.53      | 
```