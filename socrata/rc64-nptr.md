# Grand List October 1 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grand-list-october-1-2015) |
| Metadata | [Link](https://data.hartford.gov/api/views/rc64-nptr) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/rc64-nptr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/rc64-nptr/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | rc64-nptr |
| Name | Grand List October 1 2015 |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | assessor, grand list, property, hartford, ct |
| Created | 2016-04-28T20:09:43Z |
| Publication Date | 2016-04-28T20:15:02Z |

## Description

City of Hartford's grand list for real estate

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | list_no      | LIST_NO      | text      | number      |
| Yes      | numeric metric | parcel       | PARCEL       | number    | number      |
| Yes      | series tag     | owner        | OWNER        | text      | text        |
| Yes      | numeric metric | land         | LAND         | number    | number      |
| Yes      | numeric metric | gross_assmt  | GROSS_ASSMT  | money     | money       |
| Yes      | numeric metric | total_exempt | TOTAL_EXEMPT | money     | money       |
| Yes      | numeric metric | net_assmt    | NET_ASSMT    | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rc64-nptr d:2015-01-01T00:00:00.000Z t:list_no=1 t:owner="0 OLIVE STREET LLC" m:parcel=161482041 m:gross_assmt=196280 m:land=500 m:total_exempt=0 m:net_assmt=196280

series e:rc64-nptr d:2015-01-01T00:00:00.000Z t:list_no=2 t:owner="10 40 ALBANY AVENUE ASSOC LLC" m:parcel=244243042 m:gross_assmt=32802 m:land=200 m:total_exempt=0 m:net_assmt=32802

series e:rc64-nptr d:2015-01-01T00:00:00.000Z t:list_no=3 t:owner="10 40 ALBANY AVENUE ASSOC LLC" m:parcel=244243043 m:gross_assmt=6776 m:land=200 m:total_exempt=0 m:net_assmt=6776
```

## Meta Commands

```ls
metric m:parcel p:integer l:PARCEL t:dataTypeName=number

metric m:land p:integer l:LAND t:dataTypeName=number

metric m:gross_assmt p:integer l:GROSS_ASSMT t:dataTypeName=money

metric m:total_exempt p:integer l:TOTAL_EXEMPT t:dataTypeName=money

metric m:net_assmt p:integer l:NET_ASSMT t:dataTypeName=money

entity e:rc64-nptr l:"Grand List October 1 2015" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/rc64-nptr

property e:rc64-nptr t:meta.view v:id=rc64-nptr v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Grand List October 1 2015" v:attribution="City of Hartford"

property e:rc64-nptr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rc64-nptr t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:rc64-nptr t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| list_no | parcel    | owner                         | land | gross_assmt | total_exempt | net_assmt | 
| ======= | ========= | ============================= | ==== | =========== | ============ | ========= | 
| 1       | 161482041 | 0 OLIVE STREET LLC            | 500  | 196280      | 0            | 196280    | 
| 2       | 244243042 | 10 40 ALBANY AVENUE ASSOC LLC | 200  | 32802       | 0            | 32802     | 
| 3       | 244243043 | 10 40 ALBANY AVENUE ASSOC LLC | 200  | 6776        | 0            | 6776      | 
| 4       | 253674029 | 10 GEORGE STREET LLC          | 800  | 221606      | 0            | 221606    | 
| 5       | 242229008 | 10-12 PLINY ST LLC            | 100  | 57173       | 0            | 57173     | 
| 6       | 243243055 | 10-50 ALBANY AVENUE LLC       | 300  | 97790       | 0            | 97790     | 
| 7       | 227542083 | 100 EAST MAIN STREET LLC      | 200  | 518000      | 0            | 518000    | 
| 8       | 285074011 | 100 EAST MAIN STREET LLC      | 200  | 453880      | 0            | 453880    | 
| 9       | 205530084 | 100 LINCOLN STREET LLC        | 100  | 54145       | 0            | 54145     | 
| 10      | 253672223 | 100 PRESTON ST LLC            | 100  | 21291       | 0            | 21291     | 
```