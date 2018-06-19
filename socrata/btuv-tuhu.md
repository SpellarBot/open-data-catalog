# Libraries - 2015 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2015-circulation-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/btuv-tuhu) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/btuv-tuhu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/btuv-tuhu/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | btuv-tuhu |
| Name | Libraries - 2015 Circulation by Location |
| Tags | libraries, circulation, performance metrics |
| Created | 2015-02-11T22:57:40Z |
| Publication Date | 2016-01-11T18:48:51Z |

## Description

Circulation figures include new checkouts as well as renewals. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

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
series e:btuv-tuhu d:2015-01-01T00:00:00.000Z t:location="Albany Park" m:december=11056 m:november=11485 m:may=9640 m:march=11000 m:april=11463 m:february=8875 m:june=11323 m:january=10889 m:ytd=133366 m:august=12170 m:july=12627 m:october=11889 m:september=10949

series e:btuv-tuhu d:2015-01-01T00:00:00.000Z t:location=Altgeld m:december=510 m:november=609 m:may=448 m:march=456 m:april=506 m:february=261 m:june=519 m:january=608 m:ytd=6382 m:august=477 m:july=712 m:october=705 m:september=571

series e:btuv-tuhu d:2015-01-01T00:00:00.000Z t:location="Archer Heights" m:december=6317 m:november=6869 m:may=6471 m:march=7422 m:april=7683 m:february=5862 m:june=6651 m:january=6859 m:ytd=82792 m:august=7001 m:july=7269 m:october=7845 m:september=6543
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

entity e:btuv-tuhu l:"Libraries -  2015 Circulation by Location" t:url=https://data.cityofchicago.org/api/views/btuv-tuhu

property e:btuv-tuhu t:meta.view v:id=btuv-tuhu v:averageRating=0 v:name="Libraries -  2015 Circulation by Location"

property e:btuv-tuhu t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:btuv-tuhu t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may  | june  | july  | august | september | october | november | december | ytd    | 
| ================= | ======= | ======== | ===== | ===== | ==== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park       | 10889   | 8875     | 11000 | 11463 | 9640 | 11323 | 12627 | 12170  | 10949     | 11889   | 11485    | 11056    | 133366 | 
| Altgeld           | 608     | 261      | 456   | 506   | 448  | 519   | 712   | 477    | 571       | 705     | 609      | 510      | 6382   | 
| Archer Heights    | 6859    | 5862     | 7422  | 7683  | 6471 | 6651  | 7269  | 7001   | 6543      | 7845    | 6869     | 6317     | 82792  | 
| Austin            | 1850    | 1603     | 1638  | 1904  | 1660 | 2093  | 2139  | 1919   | 1674      | 1939    | 1966     | 2057     | 22442  | 
| Austin-Irving     | 10545   | 8435     | 10773 | 9990  | 9385 | 10784 | 11624 | 11158  | 10160     | 10856   | 9628     | 8997     | 122335 | 
| Avalon            | 4318    | 3296     | 4231  | 4271  | 4045 | 4549  | 4330  | 4259   | 4216      | 4396    | 3832     | 3366     | 49109  | 
| Back of the Yards | 3810    | 2711     | 3748  | 4157  | 3687 | 4336  | 4600  | 3916   | 4189      | 4657    | 3852     | 3192     | 46855  | 
| Beverly           | 5331    | 4353     | 5645  | 5513  | 4902 | 5873  | 6351  | 5492   | 5307      | 5852    | 5009     | 4914     | 64542  | 
| Bezazian          | 9967    | 8813     | 9820  | 10393 | 9943 | 10194 | 10277 | 10108  | 9648      | 9986    | 9098     | 9459     | 117706 | 
| Blackstone        | 8237    | 7104     | 8245  | 9179  | 8338 | 9675  | 9674  | 9419   | 8087      | 8328    | 7500     | 7397     | 101183 | 
```