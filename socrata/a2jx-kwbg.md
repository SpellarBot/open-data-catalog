# Libraries - 2015 Holds Filled by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2015-holds-filled-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/a2jx-kwbg) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/a2jx-kwbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/a2jx-kwbg/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | a2jx-kwbg |
| Name | Libraries - 2015 Holds Filled by Location |
| Tags | libraries, holds, circulation |
| Created | 2015-02-11T23:04:24Z |
| Publication Date | 2016-01-11T18:41:15Z |

## Description

Materials pulled to fulfill patron holds. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.  Independence Branch closed due to a fire on 10/30/15.

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
series e:a2jx-kwbg d:2015-01-01T00:00:00.000Z t:location="Albany Park" m:december=2873 m:november=2761 m:may=2340 m:march=2552 m:april=2504 m:february=2022 m:june=2445 m:january=2374 m:ytd=31162 m:august=2772 m:july=2811 m:october=2708 m:september=3000

series e:a2jx-kwbg d:2015-01-01T00:00:00.000Z t:location=Altgeld m:december=218 m:november=199 m:may=175 m:march=252 m:april=236 m:february=245 m:june=222 m:january=257 m:ytd=2671 m:august=189 m:july=202 m:october=256 m:september=220

series e:a2jx-kwbg d:2015-01-01T00:00:00.000Z t:location="Archer Heights" m:december=1423 m:november=1410 m:may=1376 m:march=1507 m:april=1429 m:february=968 m:june=1464 m:january=1236 m:ytd=16742 m:august=1518 m:july=1438 m:october=1460 m:september=1513
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

entity e:a2jx-kwbg l:"Libraries - 2015 Holds Filled by Location" t:url=https://data.cityofchicago.org/api/views/a2jx-kwbg

property e:a2jx-kwbg t:meta.view v:id=a2jx-kwbg v:averageRating=0 v:name="Libraries - 2015 Holds Filled by Location"

property e:a2jx-kwbg t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:a2jx-kwbg t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 2374    | 2022     | 2552  | 2504  | 2340 | 2445 | 2811 | 2772   | 3000      | 2708    | 2761     | 2873     | 31162 | 
| Altgeld           | 257     | 245      | 252   | 236   | 175  | 222  | 202  | 189    | 220       | 256     | 199      | 218      | 2671  | 
| Archer Heights    | 1236    | 968      | 1507  | 1429  | 1376 | 1464 | 1438 | 1518   | 1513      | 1460    | 1410     | 1423     | 16742 | 
| Austin            | 542     | 444      | 552   | 569   | 466  | 567  | 515  | 553    | 601       | 583     | 640      | 676      | 6708  | 
| Austin-Irving     | 2200    | 1855     | 3132  | 2748  | 2631 | 2712 | 2819 | 3092   | 3053      | 2986    | 2950     | 2704     | 32882 | 
| Avalon            | 1125    | 845      | 1099  | 1012  | 984  | 1114 | 983  | 959    | 1051      | 1032    | 929      | 806      | 11939 | 
| Back of the Yards | 891     | 581      | 873   | 1220  | 1180 | 1140 | 1115 | 1142   | 1194      | 1236    | 1034     | 950      | 12556 | 
| Beverly           | 1783    | 1490     | 2079  | 1809  | 1835 | 2136 | 2018 | 2142   | 2217      | 2125    | 1894     | 1681     | 23209 | 
| Bezazian          | 3343    | 3100     | 3545  | 3684  | 3338 | 3900 | 3792 | 3548   | 3759      | 3940    | 3254     | 3726     | 42929 | 
| Blackstone        | 2737    | 2110     | 3043  | 3659  | 3028 | 3099 | 3087 | 2963   | 3044      | 3318    | 3050     | 3065     | 36203 | 
```