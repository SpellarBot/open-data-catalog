# Libraries - 2016 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2016-holds-placed-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/3hsw-3tjv) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/3hsw-3tjv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/3hsw-3tjv/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 3hsw-3tjv |
| Name | Libraries - 2016 Holds Placed by Location |
| Tags | libraries, circulation, holds |
| Created | 2016-02-11T22:12:27Z |
| Publication Date | 2017-01-13T17:26:05Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3hsw-3tjv d:2016-01-01T00:00:00.000Z t:location="Albany Park" m:december=138 m:november=139 m:may=119 m:march=142 m:april=172 m:february=145 m:june=154 m:january=129 m:ytd=1637 m:august=111 m:july=124 m:october=161 m:september=103

series e:3hsw-3tjv d:2016-01-01T00:00:00.000Z t:location=Altgeld m:december=13 m:november=12 m:may=14 m:march=23 m:april=11 m:february=19 m:june=12 m:january=24 m:ytd=174 m:august=9 m:july=9 m:october=19 m:september=9

series e:3hsw-3tjv d:2016-01-01T00:00:00.000Z t:location="Archer Heights" m:december=79 m:november=82 m:may=100 m:march=129 m:april=141 m:february=101 m:june=107 m:january=100 m:ytd=1230 m:august=87 m:july=106 m:october=87 m:september=111
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:long l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:long l:YTD t:dataTypeName=number

entity e:3hsw-3tjv l:"Libraries - 2016 Holds Placed by Location" t:url=https://data.cityofchicago.org/api/views/3hsw-3tjv

property e:3hsw-3tjv t:meta.view v:id=3hsw-3tjv v:averageRating=0 v:name="Libraries - 2016 Holds Placed by Location"

property e:3hsw-3tjv t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:3hsw-3tjv t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may | june | july | august | september | october | november | december | ytd  | 
| ================= | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park       | 129     | 145      | 142   | 172   | 119 | 154  | 124  | 111    | 103       | 161     | 139      | 138      | 1637 | 
| Altgeld           | 24      | 19       | 23    | 11    | 14  | 12   | 9    | 9      | 9         | 19      | 12       | 13       | 174  | 
| Archer Heights    | 100     | 101      | 129   | 141   | 100 | 107  | 106  | 87     | 111       | 87      | 82       | 79       | 1230 | 
| Austin            | 172     | 155      | 135   | 165   | 152 | 142  | 110  | 157    | 179       | 101     | 176      | 153      | 1797 | 
| Austin-Irving     | 305     | 314      | 324   | 312   | 250 | 218  | 248  | 264    | 214       | 193     | 215      | 152      | 3009 | 
| Avalon            | 239     | 140      | 195   | 230   | 202 | 200  | 217  | 203    | 174       | 138     | 170      | 133      | 2241 | 
| Back of the Yards | 54      | 76       | 77    | 89    | 61  | 60   | 106  | 137    | 50        | 59      | 92       | 52       | 913  | 
| Beverly           | 271     | 133      | 228   | 168   | 175 | 140  | 175  | 248    | 138       | 141     | 130      | 94       | 2041 | 
| Bezazian          | 228     | 215      | 268   | 304   | 221 | 218  | 236  | 280    | 236       | 245     | 249      | 236      | 2936 | 
| Blackstone        | 150     | 167      | 172   | 172   | 182 | 126  | 146  | 162    | 183       | 134     | 118      | 131      | 1843 | 
```