# Libraries - 2016 Computer Sessions by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2016-computer-sessions-by-location) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/w7uw-j3pp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/w7uw-j3pp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/w7uw-j3pp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | w7uw-j3pp |
| Name | Libraries - 2016 Computer Sessions by Location |
| Tags | libraries, technology, computer sessions |
| Created | 2016-02-11T21:46:21Z |
| Publication Date | 2017-01-13T17:17:12Z |

## Description

The Chicago Public Library offers one-hour computer sessions and 15-minute computer sessions. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages. Independence Branch closed due to a fire on 10/30/15.

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
series e:w7uw-j3pp d:2016-01-01T00:00:00.000Z t:location="Albany Park" m:december=2513 m:march=3485 m:may=2779 m:november=3121 m:february=3117 m:april=3522 m:june=3076 m:ytd=37025 m:january=3275 m:august=3174 m:july=2778 m:october=3202 m:september=2983

series e:w7uw-j3pp d:2016-01-01T00:00:00.000Z t:location=Altgeld m:december=1147 m:march=1360 m:may=1289 m:november=1493 m:february=1458 m:april=1501 m:june=1609 m:ytd=18826 m:january=1893 m:august=2115 m:july=1962 m:october=1457 m:september=1542

series e:w7uw-j3pp d:2016-01-01T00:00:00.000Z t:location="Archer Heights" m:december=1785 m:march=2029 m:may=1829 m:november=1966 m:february=1877 m:april=2030 m:june=1832 m:ytd=23467 m:january=1951 m:august=2202 m:july=1935 m:october=2071 m:september=1960
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

entity e:w7uw-j3pp l:"Libraries - 2016 Computer Sessions by Location" t:url=https://data.cityofchicago.org/api/views/w7uw-j3pp

property e:w7uw-j3pp t:meta.view d:2017-06-09T13:51:48.842Z v:id=w7uw-j3pp v:averageRating=0 v:name="Libraries - 2016 Computer Sessions by Location"

property e:w7uw-j3pp t:meta.view.owner d:2017-06-09T13:51:48.842Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:w7uw-j3pp t:meta.view.tableauthor d:2017-06-09T13:51:48.842Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| location          | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 3275    | 3117     | 3485  | 3522  | 2779 | 3076 | 2778 | 3174   | 2983      | 3202    | 3121     | 2513     | 37025 | 
| Altgeld           | 1893    | 1458     | 1360  | 1501  | 1289 | 1609 | 1962 | 2115   | 1542      | 1457    | 1493     | 1147     | 18826 | 
| Archer Heights    | 1951    | 1877     | 2029  | 2030  | 1829 | 1832 | 1935 | 2202   | 1960      | 2071    | 1966     | 1785     | 23467 | 
| Austin            | 1542    | 1383     | 1583  | 1562  | 1482 | 1733 | 1682 | 1815   | 1474      | 1538    | 1303     | 1191     | 18288 | 
| Austin-Irving     | 1683    | 1721     | 1809  | 1735  | 1552 | 1610 | 1568 | 1727   | 1758      | 1835    | 1685     | 1596     | 20279 | 
| Avalon            | 3272    | 3296     | 3529  | 3633  | 3239 | 3518 | 3536 | 3860   | 3560      | 3712    | 3695     | 3662     | 42512 | 
| Back of the Yards | 2061    | 2145     | 2112  | 2364  | 2189 | 2263 | 2636 | 3030   | 2215      | 1964    | 1924     | 1657     | 26560 | 
| Beverly           | 1964    | 2149     | 2333  | 2179  | 2076 | 2106 | 2118 | 2420   | 2197      | 2091    | 3324     | 3551     | 28508 | 
| Bezazian          | 2801    | 2597     | 2740  | 3054  | 2272 | 2751 | 3094 | 3509   | 2787      | 3110    | 2787     | 2717     | 34219 | 
| Blackstone        | 1835    | 1529     | 1805  | 1909  | 1844 | 2068 | 2026 | 2336   | 2023      | 1986    | 1878     | 1725     | 22964 | 
```