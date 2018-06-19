# Grand List October 1 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grand-list-october-1-2013) |
| Metadata | [Link](https://data.hartford.gov/api/views/5er3-ksug) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/5er3-ksug/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/5er3-ksug/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 5er3-ksug |
| Name | Grand List October 1 2013 |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | assessor, grand list, property, hartford, ct |
| Created | 2014-03-27T16:49:17Z |
| Publication Date | 2014-03-27T17:01:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | list_no    | LIST NO    | text      | number      |
| Yes      | series tag     | owner_name | OWNER NAME | text      | text        |
| Yes      | numeric metric | parcel     | PARCEL     | number    | number      |
| Yes      | numeric metric | land       | LAND       | number    | number      |
| Yes      | numeric metric | tot_land   | TOT LAND   | money     | money       |
| Yes      | numeric metric | tot_bldg   | TOT BLDG   | money     | money       |
| Yes      | numeric metric | gross      | GROSS      | money     | money       |
| Yes      | numeric metric | exemption  | EXEMPTION  | money     | money       |
| Yes      | numeric metric | net_assmt  | NET ASSMT  | money     | money       |
| Yes      | series tag     | dist       | DIST       | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5er3-ksug d:2013-01-01T00:00:00.000Z t:owner_name="0 OLIVE STREET LLC" t:list_no=45463 t:dist=CITY m:parcel=161482041 m:exemption=0 m:gross=196280 m:land=500 m:tot_bldg=0 m:net_assmt=196280 m:tot_land=196280

series e:5er3-ksug d:2013-01-01T00:00:00.000Z t:owner_name="10 40 ALBANY AVENUE ASSOC LL" t:list_no=45464 t:dist=CITY m:parcel=244243042 m:exemption=0 m:gross=32830 m:land=500 m:tot_bldg=4200 m:net_assmt=32830 m:tot_land=28630

series e:5er3-ksug d:2013-01-01T00:00:00.000Z t:owner_name="10 40 ALBANY AVENUE ASSOC LL" t:list_no=45465 t:dist=CITY m:parcel=244243043 m:exemption=0 m:gross=6790 m:land=500 m:tot_bldg=1190 m:net_assmt=6790 m:tot_land=5600
```

## Meta Commands

```ls
metric m:parcel p:integer l:PARCEL t:dataTypeName=number

metric m:land p:integer l:LAND t:dataTypeName=number

metric m:tot_land p:integer l:"TOT LAND" t:dataTypeName=money

metric m:tot_bldg p:integer l:"TOT BLDG" t:dataTypeName=money

metric m:gross p:integer l:GROSS t:dataTypeName=money

metric m:exemption p:integer l:EXEMPTION t:dataTypeName=money

metric m:net_assmt p:integer l:"NET ASSMT" t:dataTypeName=money

entity e:5er3-ksug l:"Grand List October 1 2013" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/5er3-ksug

property e:5er3-ksug t:meta.view v:id=5er3-ksug v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Grand List October 1 2013" v:attribution="City of Hartford"

property e:5er3-ksug t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5er3-ksug t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:5er3-ksug t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| list_no | owner_name                   | parcel    | land | tot_land | tot_bldg | gross    | exemption | net_assmt | dist | 
| ======= | ============================ | ========= | ==== | ======== | ======== | ======== | ========= | ========= | ==== | 
| 45463   | 0 OLIVE STREET LLC           | 161482041 | 500  | 196280   | 0        | 196280   | 0         | 196280    | CITY | 
| 45464   | 10 40 ALBANY AVENUE ASSOC LL | 244243042 | 500  | 28630    | 4200     | 32830    | 0         | 32830     | CITY | 
| 45465   | 10 40 ALBANY AVENUE ASSOC LL | 244243043 | 500  | 5600     | 1190     | 6790     | 0         | 6790      | CITY | 
| 45466   | 10 GEORGE STREET LLC         | 253674029 | 800  | 25920    | 164040   | 189960   | 0         | 189960    | CITY | 
| 45467   | 10-12 PLINY ST LLC           | 242229008 | 100  | 2574     | 50552    | 53126    | 0         | 53126     | CITY | 
| 45468   | 10-50 ALBANY AVENUE LLC      | 243243055 | 300  | 20090    | 77700    | 97790    | 0         | 97790     | CITY | 
| 45469   | 100 EAST MAIN STREET LLC     | 227542083 | 200  | 97090    | 420910   | 518000   | 0         | 518000    | CITY | 
| 45470   | 100 EAST MAIN STREET LLC     | 285074011 | 200  | 155190   | 298690   | 453880   | 0         | 453880    | CITY | 
| 45471   | 100 PEARL STREET LLC         | 246346034 | 200  | 888300   | 11020660 | 11908960 | 0         | 11908960  | CITY | 
| 45472   | 100-110 LAUREL STREET ASSOC  | 181415012 | 800  | 108000   | 758400   | 866400   | 0         | 866400    | CITY | 
```