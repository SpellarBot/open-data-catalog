# UI WC2009 To Present ODI

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ui-wc2009-to-present-odi-112b9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ps39-dra9) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ps39-dra9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ps39-dra9/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ps39-dra9 |
| Name | UI WC2009 To Present ODI |
| Attribution | Operations Management Information Section |
| Category | Employment |
| Tags | wc, weeks claimed, ui weeks claimed, ui wc, weeks claims |
| Created | 2013-10-31T02:07:22Z |
| Publication Date | 2017-04-20T17:36:27Z |

## Description

Weeks claimed are requests for weekly unemployment payments, whether or not benefits are actually paid.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | time           | week_end_date | Week end date | calendar_date | calendar_date |
| Yes      | numeric metric | honolulu      | Honolulu      | number        | number        |
| Yes      | numeric metric | kaneohe       | Kaneohe       | number        | number        |
| Yes      | numeric metric | waipahu       | Waipahu       | number        | number        |
| Yes      | numeric metric | oahu          | OAHU          | number        | number        |
| Yes      | numeric metric | hilo          | Hilo          | number        | number        |
| Yes      | numeric metric | kona          | Kona          | number        | number        |
| Yes      | numeric metric | hawaii        | HAWAII        | number        | number        |
| Yes      | numeric metric | wailuku       | Wailuku       | number        | number        |
| Yes      | numeric metric | molokai       | Molokai       | number        | number        |
| Yes      | numeric metric | maui          | MAUI          | number        | number        |
| Yes      | numeric metric | kauai         | KAUAI         | number        | number        |
| Yes      | numeric metric | agent         | Agent         | number        | number        |
| Yes      | numeric metric | all_islands   | All Islands   | number        | number        |
```

## Time Field

```ls
Value = week_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ps39-dra9 d:2009-01-03T00:00:00.000Z m:kona=2110 m:all_islands=17915 m:kauai=1731 m:maui=3241 m:hilo=1775 m:wailuku=3095 m:kaneohe=1166 m:honolulu=3334 m:molokai=146 m:agent=536 m:oahu=8522 m:hawaii=3885 m:waipahu=4022

series e:ps39-dra9 d:2009-01-10T00:00:00.000Z m:kona=2072 m:all_islands=18644 m:kauai=1561 m:maui=3387 m:hilo=1738 m:wailuku=3268 m:kaneohe=1250 m:honolulu=3711 m:molokai=119 m:agent=535 m:oahu=9351 m:hawaii=3810 m:waipahu=4390

series e:ps39-dra9 d:2009-01-17T00:00:00.000Z m:kona=2166 m:all_islands=18874 m:kauai=1904 m:maui=3388 m:hilo=1813 m:wailuku=3233 m:kaneohe=1248 m:honolulu=3615 m:molokai=155 m:agent=533 m:oahu=9070 m:hawaii=3979 m:waipahu=4207
```

## Meta Commands

```ls
metric m:honolulu p:long l:Honolulu t:dataTypeName=number

metric m:kaneohe p:long l:Kaneohe t:dataTypeName=number

metric m:waipahu p:long l:Waipahu t:dataTypeName=number

metric m:oahu p:long l:OAHU t:dataTypeName=number

metric m:hilo p:long l:Hilo t:dataTypeName=number

metric m:kona p:long l:Kona t:dataTypeName=number

metric m:hawaii p:long l:HAWAII t:dataTypeName=number

metric m:wailuku p:long l:Wailuku t:dataTypeName=number

metric m:molokai p:long l:Molokai t:dataTypeName=number

metric m:maui p:long l:MAUI t:dataTypeName=number

metric m:kauai p:long l:KAUAI t:dataTypeName=number

metric m:agent p:long l:Agent t:dataTypeName=number

metric m:all_islands p:long l:"All Islands" t:dataTypeName=number

entity e:ps39-dra9 l:"UI WC2009 To Present ODI" t:attribution="Operations Management Information Section" t:url=https://data.hawaii.gov/api/views/ps39-dra9

property e:ps39-dra9 t:meta.view v:id=ps39-dra9 v:category=Employment v:averageRating=0 v:name="UI WC2009 To Present ODI" v:attribution="Operations Management Information Section"

property e:ps39-dra9 t:meta.view.license v:name="Public Domain"

property e:ps39-dra9 t:meta.view.owner v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:displayName=Bill

property e:ps39-dra9 t:meta.view.tableauthor v:id=5ibs-8u6a v:profileImageUrlMedium=/api/users/5ibs-8u6a/profile_images/THUMB v:profileImageUrlLarge=/api/users/5ibs-8u6a/profile_images/LARGE v:screenName=Bill v:profileImageUrlSmall=/api/users/5ibs-8u6a/profile_images/TINY v:roleName=editor v:displayName=Bill
```

## Top Records

```ls
| week_end_date       | honolulu | kaneohe | waipahu | oahu | hilo | kona | hawaii | wailuku | molokai | maui | kauai | agent | all_islands | 
| =================== | ======== | ======= | ======= | ==== | ==== | ==== | ====== | ======= | ======= | ==== | ===== | ===== | =========== | 
| 2009-01-03T00:00:00 | 3334     | 1166    | 4022    | 8522 | 1775 | 2110 | 3885   | 3095    | 146     | 3241 | 1731  | 536   | 17915       | 
| 2009-01-10T00:00:00 | 3711     | 1250    | 4390    | 9351 | 1738 | 2072 | 3810   | 3268    | 119     | 3387 | 1561  | 535   | 18644       | 
| 2009-01-17T00:00:00 | 3615     | 1248    | 4207    | 9070 | 1813 | 2166 | 3979   | 3233    | 155     | 3388 | 1904  | 533   | 18874       | 
| 2009-01-24T00:00:00 | 3681     | 1231    | 4169    | 9081 | 1603 | 2187 | 3790   | 3360    | 113     | 3473 | 1711  | 516   | 18571       | 
| 2009-01-31T00:00:00 | 3447     | 1217    | 4036    | 8700 | 1680 | 2178 | 3858   | 3262    | 116     | 3378 | 1949  | 616   | 18501       | 
| 2009-02-07T00:00:00 | 3777     | 1279    | 4266    | 9322 | 1660 | 2315 | 3975   | 3515    | 144     | 3659 | 1821  | 555   | 19332       | 
| 2009-02-14T00:00:00 | 3613     | 1314    | 4070    | 8997 | 1741 | 2234 | 3975   | 3450    | 129     | 3579 | 1937  | 604   | 19092       | 
| 2009-02-21T00:00:00 | 3879     | 1281    | 4294    | 9454 | 1675 | 2339 | 4014   | 3409    | 112     | 3521 | 1738  | 532   | 19259       | 
| 2009-02-28T00:00:00 | 3662     | 1348    | 4332    | 9342 | 1759 | 2254 | 4013   | 3364    | 119     | 3483 | 1880  | 650   | 19368       | 
| 2009-03-07T00:00:00 | 4118     | 1360    | 4494    | 9972 | 1660 | 2282 | 3942   | 3521    | 105     | 3626 | 1820  | 597   | 19957       | 
```