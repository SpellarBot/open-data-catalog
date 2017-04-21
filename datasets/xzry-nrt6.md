# Grand List October 1 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grand-list-october-1-2014) |
| Metadata | [Link](https://data.hartford.gov/api/views/xzry-nrt6) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/xzry-nrt6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/xzry-nrt6/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | xzry-nrt6 |
| Name | Grand List October 1 2014 |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | assessor, grand list, property, hartford |
| Created | 2015-05-05T11:31:31Z |
| Publication Date | 2015-05-05T12:07:08Z |

## Description

City of Hartford's grand list for real estate

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | list_no        | LIST_NO        | text      | number      |
| Yes      | numeric metric | parcel         | PARCEL         | number    | number      |
| Yes      | series tag     | owner          | OWNER          | text      | text        |
| Yes      | numeric metric | land           | LAND           | number    | number      |
| Yes      | numeric metric | amount_exempt1 | AMOUNT_EXEMPT1 | money     | money       |
| Yes      | numeric metric | amount_exempt2 | AMOUNT_EXEMPT2 | money     | money       |
| Yes      | numeric metric | gross          | GROSS          | money     | money       |
| Yes      | numeric metric | net_assmt      | NET ASSMT      | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xzry-nrt6 d:2014-01-01T00:00:00.000Z t:list_no=1 t:owner="0 OLIVE STREET LLC" m:parcel=161482041 m:amount_exempt2=0 m:gross=196280 m:amount_exempt1=0 m:land=500 m:net_assmt=196280

series e:xzry-nrt6 d:2014-01-01T00:00:00.000Z t:list_no=2 t:owner="10 40 ALBANY AVENUE ASSOC LLC" m:parcel=244243042 m:amount_exempt2=0 m:gross=32802 m:amount_exempt1=0 m:land=200 m:net_assmt=32802

series e:xzry-nrt6 d:2014-01-01T00:00:00.000Z t:list_no=3 t:owner="10 40 ALBANY AVENUE ASSOC LLC" m:parcel=244243043 m:amount_exempt2=0 m:gross=6776 m:amount_exempt1=0 m:land=200 m:net_assmt=6776
```

## Meta Commands

```ls
metric m:parcel p:integer l:PARCEL t:dataTypeName=number

metric m:land p:integer l:LAND t:dataTypeName=number

metric m:amount_exempt1 p:integer l:AMOUNT_EXEMPT1 t:dataTypeName=money

metric m:amount_exempt2 p:integer l:AMOUNT_EXEMPT2 t:dataTypeName=money

metric m:gross p:integer l:GROSS t:dataTypeName=money

metric m:net_assmt p:integer l:"NET ASSMT" t:dataTypeName=money

entity e:xzry-nrt6 l:"Grand List October 1 2014" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/xzry-nrt6

property e:xzry-nrt6 t:meta.view v:id=xzry-nrt6 v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Grand List October 1 2014" v:attribution="City of Hartford"

property e:xzry-nrt6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xzry-nrt6 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:xzry-nrt6 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| list_no | parcel    | owner                                   | land | amount_exempt1 | amount_exempt2 | gross    | net_assmt | 
| ======= | ========= | ======================================= | ==== | ============== | ============== | ======== | ========= | 
| 1       | 161482041 | 0 OLIVE STREET LLC                      | 500  | 0              | 0              | 196280   | 196280    | 
| 2       | 244243042 | 10 40 ALBANY AVENUE ASSOC LLC           | 200  | 0              | 0              | 32802    | 32802     | 
| 3       | 244243043 | 10 40 ALBANY AVENUE ASSOC LLC           | 200  | 0              | 0              | 6776     | 6776      | 
| 4       | 253674029 | 10 GEORGE STREET LLC                    | 800  | 0              | 0              | 205777   | 205777    | 
| 5       | 242229008 | 10-12 PLINY ST LLC                      | 100  | 0              | 0              | 54457    | 54457     | 
| 6       | 243243055 | 10-50 ALBANY AVENUE LLC                 | 300  | 0              | 0              | 97790    | 97790     | 
| 7       | 227542083 | 100 EAST MAIN STREET LLC                | 200  | 0              | 0              | 518000   | 518000    | 
| 8       | 285074011 | 100 EAST MAIN STREET LLC                | 200  | 0              | 0              | 453880   | 453880    | 
| 9       | 246346034 | 100 PEARL STREET LLC                    | 200  | 0              | 0              | 11908960 | 11908960  | 
| 10      | 181415012 | 100-110 LAUREL STREET ASSOC LIMITED PAR | 800  | 0              | 0              | 938600   | 938600    | 
```