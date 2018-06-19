# Libraries - 2016 Holds Filled by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2016-holds-filled-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hixh-ndcj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hixh-ndcj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hixh-ndcj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hixh-ndcj |
| Name | Libraries - 2016 Holds Filled by Location |
| Tags | libraries, holds, circulation |
| Created | 2016-02-16T22:53:49Z |
| Publication Date | 2017-01-13T17:21:32Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hixh-ndcj d:2016-01-01T00:00:00.000Z t:location="Albany Park" m:december=3019 m:november=3639 m:may=3123 m:march=3575 m:april=3341 m:february=3105 m:june=3650 m:january=3085 m:ytd=40522 m:august=3648 m:july=3387 m:october=3540 m:september=3410

series e:hixh-ndcj d:2016-01-01T00:00:00.000Z t:location=Altgeld m:december=165 m:november=147 m:may=216 m:march=277 m:april=220 m:february=252 m:june=194 m:january=306 m:ytd=2730 m:august=246 m:july=255 m:october=224 m:september=228

series e:hixh-ndcj d:2016-01-01T00:00:00.000Z t:location="Archer Heights" m:december=1494 m:november=1569 m:may=1552 m:march=1628 m:april=1739 m:february=1499 m:june=1631 m:january=1614 m:ytd=19264 m:august=1739 m:july=1603 m:october=1468 m:september=1728
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

entity e:hixh-ndcj l:"Libraries - 2016 Holds Filled by Location" t:url=https://data.cityofchicago.org/api/views/hixh-ndcj

property e:hixh-ndcj t:meta.view v:id=hixh-ndcj v:averageRating=0 v:name="Libraries - 2016 Holds Filled by Location"

property e:hixh-ndcj t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:hixh-ndcj t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 3085    | 3105     | 3575  | 3341  | 3123 | 3650 | 3387 | 3648   | 3410      | 3540    | 3639     | 3019     | 40522 | 
| Altgeld           | 306     | 252      | 277   | 220   | 216  | 194  | 255  | 246    | 228       | 224     | 147      | 165      | 2730  | 
| Archer Heights    | 1614    | 1499     | 1628  | 1739  | 1552 | 1631 | 1603 | 1739   | 1728      | 1468    | 1569     | 1494     | 19264 | 
| Austin            | 786     | 812      | 822   | 758   | 633  | 756  | 657  | 803    | 803       | 799     | 711      | 686      | 9026  | 
| Austin-Irving     | 3302    | 3235     | 3464  | 3689  | 3131 | 3337 | 3113 | 3886   | 3507      | 3219    | 3045     | 2952     | 39880 | 
| Avalon            | 1118    | 1109     | 1013  | 1276  | 1013 | 1060 | 1233 | 1308   | 1219      | 1246    | 1238     | 1236     | 14069 | 
| Back of the Yards | 1137    | 1136     | 1171  | 1244  | 1069 | 1142 | 1073 | 1366   | 1099      | 1007    | 1045     | 892      | 13381 | 
| Beverly           | 1971    | 1741     | 2425  | 2279  | 2138 | 2340 | 2277 | 2482   | 2389      | 2365    | 2499     | 2100     | 27006 | 
| Bezazian          | 4061    | 3928     | 4113  | 4353  | 4047 | 4056 | 3920 | 4674   | 4365      | 4117    | 4058     | 3850     | 49542 | 
| Blackstone        | 3276    | 3376     | 3963  | 3963  | 3598 | 3850 | 4136 | 4103   | 3879      | 3627    | 3519     | 3464     | 44754 | 
```