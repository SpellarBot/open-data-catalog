# Libraries - 2015 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2015-holds-placed-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/avse-5iw4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/avse-5iw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/avse-5iw4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | avse-5iw4 |
| Name | Libraries - 2015 Holds Placed by Location |
| Tags | libraries, circulation, holds |
| Created | 2015-02-11T23:33:23Z |
| Publication Date | 2016-01-11T18:34:42Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches.  Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.  Independence Branch closed due to a fire on 10/30/15.

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
series e:avse-5iw4 d:2015-01-01T00:00:00.000Z t:location="Albany Park" m:december=105 m:november=95 m:may=96 m:march=111 m:april=105 m:february=118 m:june=91 m:january=136 m:ytd=1230 m:august=104 m:july=85 m:october=72 m:september=112

series e:avse-5iw4 d:2015-01-01T00:00:00.000Z t:location=Altgeld m:december=15 m:november=19 m:may=10 m:march=14 m:april=7 m:february=3 m:june=12 m:january=17 m:ytd=163 m:august=14 m:july=20 m:october=11 m:september=21

series e:avse-5iw4 d:2015-01-01T00:00:00.000Z t:location="Archer Heights" m:december=70 m:november=130 m:may=86 m:march=81 m:april=112 m:february=69 m:june=119 m:january=87 m:ytd=1405 m:august=178 m:july=149 m:october=157 m:september=167
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

metric m:october p:long l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:long l:YTD t:dataTypeName=number

entity e:avse-5iw4 l:"Libraries - 2015 Holds Placed by Location" t:url=https://data.cityofchicago.org/api/views/avse-5iw4

property e:avse-5iw4 t:meta.view v:id=avse-5iw4 v:averageRating=0 v:name="Libraries - 2015 Holds Placed by Location"

property e:avse-5iw4 t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:avse-5iw4 t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may | june | july | august | september | october | november | december | ytd  | 
| ================= | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park       | 136     | 118      | 111   | 105   | 96  | 91   | 85   | 104    | 112       | 72      | 95       | 105      | 1230 | 
| Altgeld           | 17      | 3        | 14    | 7     | 10  | 12   | 20   | 14     | 21        | 11      | 19       | 15       | 163  | 
| Archer Heights    | 87      | 69       | 81    | 112   | 86  | 119  | 149  | 178    | 167       | 157     | 130      | 70       | 1405 | 
| Austin            | 66      | 39       | 46    | 63    | 31  | 48   | 33   | 53     | 75        | 107     | 157      | 166      | 884  | 
| Austin-Irving     | 237     | 188      | 210   | 202   | 202 | 241  | 254  | 298    | 310       | 317     | 255      | 259      | 2973 | 
| Avalon            | 192     | 144      | 144   | 176   | 164 | 206  | 147  | 155    | 158       | 216     | 149      | 127      | 1978 | 
| Back of the Yards | 67      | 91       | 60    | 64    | 53  | 35   | 59   | 72     | 103       | 91      | 93       | 46       | 834  | 
| Beverly           | 177     | 170      | 186   | 165   | 141 | 191  | 170  | 175    | 176       | 166     | 113      | 113      | 1943 | 
| Bezazian          | 312     | 239      | 330   | 295   | 260 | 336  | 289  | 319    | 307       | 327     | 299      | 262      | 3575 | 
| Blackstone        | 136     | 110      | 100   | 133   | 132 | 140  | 148  | 143    | 147       | 148     | 123      | 133      | 1593 | 
```