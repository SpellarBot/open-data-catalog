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
series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location="Albany Park" m:november=13567 m:may=11979 m:august=13078 m:february=8979 m:ytd=153751 m:july=14768 m:april=12912 m:march=13017 m:june=14061 m:september=14156 m:january=8234 m:december=12907 m:october=16093

series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location=Altgeld m:november=4794 m:may=3939 m:august=7272 m:february=2619 m:ytd=58248 m:july=5542 m:april=4083 m:march=4131 m:june=4933 m:september=5082 m:january=4577 m:december=5604 m:october=5672

series e:7imc-umy4 d:2015-01-01T00:00:00.000Z t:location="Archer Heights*" m:november=9018 m:may=7536 m:august=9613 m:february=7672 m:ytd=108588 m:july=10777 m:april=9530 m:march=9256 m:june=8917 m:september=8687 m:january=8435 m:december=8716 m:october=10431
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

property e:7imc-umy4 t:meta.view d:2017-09-25T07:26:02.243Z v:averageRating=0 v:name="Libraries - 2015 Visitors by Location" v:attribution="Chicago Public Library" v:id=7imc-umy4

property e:7imc-umy4 t:meta.view.owner d:2017-09-25T07:26:02.243Z v:displayName="Marie E. Hardy" v:lastNotificationSeenAt=1503934321 v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:id=vedk-n2zt v:screenName="Marie E. Hardy" v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB

property e:7imc-umy4 t:meta.view.tableauthor d:2017-09-25T07:26:02.243Z v:displayName="Marie E. Hardy" v:lastNotificationSeenAt=1503934321 v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:id=vedk-n2zt v:screenName="Marie E. Hardy" v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB
```

## Top Records

```ls
| location          | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 8234    | 8979     | 13017 | 12912 | 11979 | 14061 | 14768 | 13078  | 14156     | 16093   | 13567    | 12907    | 153751 | 
| Altgeld           | 4577    | 2619     | 4131  | 4083  | 3939  | 4933  | 5542  | 7272   | 5082      | 5672    | 4794     | 5604     | 58248  | 
| Archer Heights*   | 8435    | 7672     | 9256  | 9530  | 7536  | 8917  | 10777 | 9613   | 8687      | 10431   | 9018     | 8716     | 108588 | 
| Austin            | 6241    | 5340     | 6007  | 6403  | 5246  | 7417  | 8461  | 8026   | 7124      | 6489    | 6028     | 6218     | 79000  | 
| Austin-Irving     | 8331    | 8121     | 9915  | 9761  | 8406  | 10528 | 10043 | 9708   | 8886      | 9918    | 8866     | 8211     | 110694 | 
| Avalon*           | 9191    | 7835     | 9721  | 9925  | 8873  | 9908  | 9852  | 10385  | 8937      | 9999    | 8889     | 8479     | 111994 | 
| Back of the Yards | 4541    | 3562     | 4983  | 5615  | 5095  | 6187  | 6507  | 6453   | 6093      | 6176    | 5401     | 4928     | 65541  | 
| Beverly*          | 8853    | 7513     | 9244  | 9025  | 7603  | 10150 | 9306  | 7904   | 7914      | 8613    | 6939     | 6769     | 99833  | 
| Bezazian          | 10431   | 8750     | 11575 | 12767 | 11290 | 11371 | 12367 | 12490  | 11709     | 11874   | 10645    | 10456    | 135725 | 
| Blackstone        | 9266    | 7317     | 9310  | 10315 | 8551  | 11087 | 11434 | 10425  | 9070      | 9854    | 8603     | 8910     | 114142 | 
```