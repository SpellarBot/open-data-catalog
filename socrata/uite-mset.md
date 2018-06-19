# Missourians Receiving Unemployment Benefits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missourians-receiving-unemployment-benefits-cc31d) |
| Metadata | [Link](https://data.mo.gov/api/views/uite-mset) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/uite-mset/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/uite-mset/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | uite-mset |
| Name | Missourians Receiving Unemployment Benefits |
| Category | Labor |
| Tags | labor, unemployment |
| Created | 2013-02-25T14:53:04Z |
| Publication Date | 2013-03-11T19:54:34Z |

## Description

This data represents the number of Missourians currently receiving unemployment benefits.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                | Data Type | Render Type |
| ======== | ============== | ========== | =================================== | ========= | =========== |
| Yes      | time           | date       | Date                                | date      | date        |
| No       |                | eb         | Extended Benefits                   | number    | number      |
| Yes      | numeric metric | euc        | Emergency Unemployment Compensation | number    | number      |
| Yes      | numeric metric | regular    | Regular State Benefits              | number    | number      |
| Yes      | numeric metric | total      | Total                               | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = eb
```

## Data Commands

```ls
series e:uite-mset d:2012-03-01T08:00:00.000Z m:total=111235 m:euc=47191 m:regular=55645

series e:uite-mset d:2011-09-01T07:00:00.000Z m:total=110757 m:euc=48062 m:regular=53481

series e:uite-mset d:2012-09-01T07:00:00.000Z m:total=79987 m:euc=33059 m:regular=46928
```

## Meta Commands

```ls
metric m:euc p:float l:"Emergency Unemployment Compensation" t:dataTypeName=number

metric m:regular p:float l:"Regular State Benefits" t:dataTypeName=number

metric m:total p:float l:Total t:dataTypeName=number

entity e:uite-mset l:"Missourians Receiving Unemployment Benefits" t:url=https://data.mo.gov/api/views/uite-mset

property e:uite-mset t:meta.view v:id=uite-mset v:category=Labor v:averageRating=0 v:name="Missourians Receiving Unemployment Benefits"

property e:uite-mset t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:uite-mset t:meta.view.tableauthor v:id=9z8w-z2yk v:screenName=Amy_Susan v:roleName=editor v:displayName=Amy_Susan
```

## Top Records

```ls
| date       | eb      | euc     | regular | total    | 
| ========== | ======= | ======= | ======= | ======== | 
| 1330588800 | 8399.0  | 47191.0 | 55645.0 | 111235.0 | 
| 1314860400 | 9214.0  | 48062.0 | 53481.0 | 110757.0 | 
| 1346482800 | 0.0     | 33059.0 | 46928.0 | 79987.0  | 
| 1298966400 | 10202.0 | 59173.0 | 74775.0 | 144158.0 | 
| 1349074800 | 0.0     | 32346.0 | 41201.0 | 73547.0  | 
| 1317452400 | 9136.0  | 48284.0 | 50354.0 | 107774.0 | 
| 1304233200 | 9210.0  | 52647.0 | 60663.0 | 122520.0 | 
| 1335855600 | 42.0    | 41358.0 | 47437.0 | 88837.0  | 
| 1293868800 | 9912.0  | 57244.0 | 88024.0 | 153180.0 | 
| 1325404800 | 6777.0  | 51045.0 | 67981.0 |          | 
```