# Budget Proposed Resources 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-proposed-resources-2017) |
| Metadata | [Link](https://data.seattle.gov/api/views/yakm-xjzg) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/yakm-xjzg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/yakm-xjzg/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | yakm-xjzg |
| Name | Budget Proposed Resources 2017 |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | budget proposed resources 2017 |
| Created | 2016-09-26T18:37:46Z |
| Publication Date | 2016-09-26T22:11:30Z |

## Description

Budget Proposed Resources 2017

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | dept                 | Dept                 | text      | text        |
| Yes      | series tag     | fundname             | FundName             | text      | text        |
| Yes      | series tag     | revenuetablecategory | RevenueTableCategory | text      | text        |
| Yes      | series tag     | revenuesourcename    | RevenueSourceName    | text      | text        |
| Yes      | numeric metric | 2015_actuals         | 2015 Actuals         | number    | number      |
| Yes      | numeric metric | 2016_adopted         | 2016 Adopted         | number    | number      |
| Yes      | numeric metric | 2017_proposed        | 2017 Proposed        | number    | number      |
| Yes      | numeric metric | 2018_proposed        | 2018 Proposed        | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yakm-xjzg d:2017-01-01T00:00:00.000Z t:revenuetablecategory="Levy Revenue" t:dept=12LIBLEVY t:revenuesourcename="Interest Earnings" t:fundname="2012 Library Levy Fund (18100)" m:2017_proposed=100000 m:2015_actuals=110333 m:2018_proposed=50000 m:2016_adopted=50000

series e:yakm-xjzg d:2017-01-01T00:00:00.000Z t:revenuetablecategory="Levy Revenue" t:dept=12LIBLEVY t:revenuesourcename="Property Tax" t:fundname="2012 Library Levy Fund (18100)" m:2017_proposed=17513077 m:2015_actuals=17283986 m:2018_proposed=17688208 m:2016_adopted=17340000

series e:yakm-xjzg d:2017-01-01T00:00:00.000Z t:revenuetablecategory="Levy Revenue" t:dept=12LIBLEVY t:revenuesourcename="Use of (Contribution To) Fund Balance" t:fundname="2012 Library Levy Fund (18100)" m:2017_proposed=1500344 m:2015_actuals=-1562341 m:2018_proposed=1745362 m:2016_adopted=-1482163
```

## Meta Commands

```ls
metric m:2015_actuals p:integer l:"2015 Actuals" t:dataTypeName=number

metric m:2016_adopted p:integer l:"2016 Adopted" t:dataTypeName=number

metric m:2017_proposed p:integer l:"2017 Proposed" t:dataTypeName=number

metric m:2018_proposed p:integer l:"2018 Proposed" t:dataTypeName=number

entity e:yakm-xjzg l:"Budget Proposed Resources 2017" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/yakm-xjzg

property e:yakm-xjzg t:meta.view v:id=yakm-xjzg v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Budget Proposed Resources 2017" v:attribution="City of Seattle"

property e:yakm-xjzg t:meta.view.license v:name="Public Domain"

property e:yakm-xjzg t:meta.view.owner v:id=58et-jnvx v:screenName="Butler, Mark" v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"

property e:yakm-xjzg t:meta.view.tableauthor v:id=58et-jnvx v:screenName="Butler, Mark" v:roleName=administrator v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"
```

## Top Records

```ls
| dept      | fundname                       | revenuetablecategory     | revenuesourcename                     | 2015_actuals | 2016_adopted | 2017_proposed | 2018_proposed | 
| ========= | ============================== | ======================== | ===================================== | ============ | ============ | ============= | ============= | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy Revenue             | Interest Earnings                     | 110333       | 50000        | 100000        | 50000         | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy Revenue             | Property Tax                          | 17283986     | 17340000     | 17513077      | 17688208      | 
| 12LIBLEVY | 2012 Library Levy Fund (18100) | Levy Revenue             | Use of (Contribution To) Fund Balance | -1562341     | -1482163     | 1500344       | 1745362       | 
| ARTS      | Arts Account (00140)           | Misc Revenues            | Interest Earnings                     | 25862        | 20000        | 20000         | 20000         | 
| ARTS      | Municipal Arts Fund (62600)    | Misc Revenues            | Interest Earnings                     | 88995        | 74986        | 77235         | 79552         | 
| ARTS      | Arts Account (00140)           | Misc Revenues            | Interest Increase/Decrease            | -2243        | 0            | 0             | 0             | 
| ARTS      | Municipal Arts Fund (62600)    | Misc Revenues            | Interest Increase/Decrease            | -9735        | 0            | 0             | 0             | 
| ARTS      | Arts Account (00140)           | Admission Tax Allocation | Interfund Transfers                   | 5953328      | 6492924      | 7914128       | 9004368       | 
| ARTS      | Arts Account (00140)           | General Fund             | Interfund Transfers                   | 0            | 1500000      | 1300000       | 0             | 
| ARTS      | Arts Account (00140)           | Misc Revenues            | Interfund Transfers                   | 30880        | 31961        | 32000         | 32000         | 
```