# Libraries - 2016 Visitors by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2016-visitors-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cpc6-pxmp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cpc6-pxmp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cpc6-pxmp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cpc6-pxmp |
| Name | Libraries - 2016 Visitors by Location |
| Tags | libraries, visitors |
| Created | 2016-02-11T21:24:07Z |
| Publication Date | 2017-01-13T17:15:09Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cpc6-pxmp d:2016-01-01T00:00:00.000Z t:location="Albany Park" m:december=12789 m:march=12368 m:may=10915 m:november=14463 m:february=10593 m:april=12556 m:june=15341 m:ytd=159397 m:january=11735 m:august=13907 m:july=14151 m:october=16460 m:september=14119

series e:cpc6-pxmp d:2016-01-01T00:00:00.000Z t:location=Altgeld m:december=3325 m:march=4529 m:may=3880 m:november=4584 m:february=5034 m:april=4471 m:june=4431 m:ytd=57479 m:january=5335 m:august=5867 m:july=5526 m:october=5064 m:september=5433

series e:cpc6-pxmp d:2016-01-01T00:00:00.000Z t:location="Archer Heights*" m:december=6754 m:march=10522 m:may=8714 m:november=8400 m:february=9079 m:april=9747 m:june=9567 m:ytd=107323 m:january=8375 m:august=8831 m:july=9514 m:october=9209 m:september=8611
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

entity e:cpc6-pxmp l:"Libraries - 2016 Visitors by Location" t:url=https://data.cityofchicago.org/api/views/cpc6-pxmp

property e:cpc6-pxmp t:meta.view d:2017-06-09T14:00:57.243Z v:id=cpc6-pxmp v:averageRating=0 v:name="Libraries - 2016 Visitors by Location"

property e:cpc6-pxmp t:meta.view.owner d:2017-06-09T14:00:57.243Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:cpc6-pxmp t:meta.view.tableauthor d:2017-06-09T14:00:57.243Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ================= | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 11735   | 10593    | 12368 | 12556 | 10915 | 15341 | 14151 | 13907  | 14119     | 16460   | 14463    | 12789    | 159397 | 
| Altgeld           | 5335    | 5034     | 4529  | 4471  | 3880  | 4431  | 5526  | 5867   | 5433      | 5064    | 4584     | 3325     | 57479  | 
| Archer Heights*   | 8375    | 9079     | 10522 | 9747  | 8714  | 9567  | 9514  | 8831   | 8611      | 9209    | 8400     | 6754     | 107323 | 
| Austin            | 5849    | 5190     | 5691  | 6313  | 6092  | 7489  | 9012  | 8202   | 7521      | 7257    | 6395     | 6632     | 81643  | 
| Austin-Irving     | 8726    | 9201     | 10017 | 10010 | 8346  | 9571  | 9567  | 9386   | 9110      | 10505   | 10540    | 9913     | 114892 | 
| Avalon*           | 8835    | 8984     | 8993  | 9729  | 9201  | 9755  | 10089 | 9860   | 9053      | 9772    | 10110    | 8970     | 113351 | 
| Back of the Yards | 4871    | 5896     | 5552  | 6453  | 5713  | 5487  | 5694  | 6857   | 5719      | 5223    | 4421     | 3863     | 65749  | 
| Beverly*          | 6813    | 7666     | 7943  | 7639  | 7568  | 7814  | 9243  | 8953   | 7615      | 7971    | 10466    | 9545     | 99236  | 
| Bezazian          | 10658   | 10329    | 11799 | 11849 | 9770  | 11750 | 12560 | 13404  | 11076     | 11920   | 10424    | 9317     | 134856 | 
| Blackstone        | 8355    | 7777     | 8607  | 9328  | 7925  | 9337  | 10983 | 10176  | 8849      | 9178    | 8333     | 7691     | 106539 | 
```