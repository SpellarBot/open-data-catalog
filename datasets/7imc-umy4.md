# Libraries - 2015 Visitors by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2015-visitors-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7imc-umy4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7imc-umy4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7imc-umy4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7imc-umy4 |
| Name | Libraries - 2015 Visitors by Location |
| Attribution | Chicago Public Library |
| Tags | libraries, visitors |
| Created | 2015-02-11T22:15:54Z |
| Publication Date | 2016-01-11T19:13:52Z |
| Rows Updated | 2016-01-11T19:12:21Z |

## Description

The Chicago Public Library has more than 70 locations. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages. Independence Branch closed due to a fire on 10/30/15.														
* Count does not reflect the total building visitor count due to location of traffic counter. Community room and program traffic are not included in totals.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | ytd        | YTD       | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location="Albany Park" m:december=12907 m:november=13567 m:may=11979 m:march=13017 m:april=12912 m:february=8979 m:june=14061 m:january=8234 m:ytd=153751 m:august=13078 m:july=14768 m:october=16093 m:september=14156

series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location=Altgeld m:december=5604 m:november=4794 m:may=3939 m:march=4131 m:april=4083 m:february=2619 m:june=4933 m:january=4577 m:ytd=58248 m:august=7272 m:july=5542 m:october=5672 m:september=5082

series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location="Archer Heights*" m:december=8716 m:november=9018 m:may=7536 m:march=9256 m:april=9530 m:february=7672 m:june=8917 m:january=8435 m:ytd=108588 m:august=9613 m:july=10777 m:october=10431 m:september=8687
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:7imc-umy4 l:"Libraries - 2015 Visitors by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/7imc-umy4

property e:7imc-umy4 t:meta.view v:id=7imc-umy4 v:averageRating=0 v:name="Libraries - 2015 Visitors by Location" v:attribution="Chicago Public Library"

property e:7imc-umy4 t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:7imc-umy4 t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```