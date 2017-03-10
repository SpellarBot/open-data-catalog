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
| Rows Updated | 2017-01-13T17:16:41Z |

## Description

The Chicago Public Library offers one-hour computer sessions and 15-minute computer sessions. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages. Independence Branch closed due to a fire on 10/30/15.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | location    | LOCATION   | text      | text        |
| Yes      | numeric metric | january     | JANUARY    | number    | number      |
| Yes      | numeric metric | february    | FEBRUARY   | number    | number      |
| Yes      | numeric metric | march       | MARCH      | number    | number      |
| Yes      | numeric metric | april       | APRIL      | number    | number      |
| Yes      | numeric metric | may         | MAY        | number    | number      |
| Yes      | numeric metric | june        | JUNE       | number    | number      |
| Yes      | numeric metric | july        | JULY       | number    | number      |
| Yes      | numeric metric | august      | AUGUST     | number    | number      |
| Yes      | numeric metric | september   | SEPTEMBER  | number    | number      |
| Yes      | numeric metric | october     | OCTOBER    | number    | number      |
| Yes      | numeric metric | november    | NOVEMBER   | number    | number      |
| Yes      | numeric metric | december    | DECEMBER   | number    | number      |
| Yes      | numeric metric | ytd         | YTD        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w7uw-j3pp d:2017-01-13T17:16:33.000Z t:location="Albany Park" m:december=2513 m:may=2779 m:november=3121 m:march=3485 m:april=3522 m:february=3117 m:june=3076 m:january=3275 m:ytd=37025 m:august=3174 m:july=2778 m:october=3202 m:september=2983

series e:w7uw-j3pp d:2017-01-13T17:16:33.000Z t:location=Altgeld m:december=1147 m:may=1289 m:november=1493 m:march=1360 m:april=1501 m:february=1458 m:june=1609 m:january=1893 m:ytd=18826 m:august=2115 m:july=1962 m:october=1457 m:september=1542

series e:w7uw-j3pp d:2017-01-13T17:16:33.000Z t:location="Archer Heights" m:december=1785 m:may=1829 m:november=1966 m:march=2029 m:april=2030 m:february=1877 m:june=1832 m:january=1951 m:ytd=23467 m:august=2202 m:july=1935 m:october=2071 m:september=1960
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

property e:w7uw-j3pp t:meta.view d:2017-03-10T15:59:22.877Z v:id=w7uw-j3pp v:averageRating=0 v:name="Libraries - 2016 Computer Sessions by Location"

property e:w7uw-j3pp t:meta.view.owner d:2017-03-10T15:59:22.877Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"

property e:w7uw-j3pp t:meta.view.tableauthor d:2017-03-10T15:59:22.877Z v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```