# Table 8 Offenses Known To Law Enforcement By Mississippi By City 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-8-offenses-known-to-law-enforcement-by-mississippi-by-city-2012) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/u55u-qyg7) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/u55u-qyg7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/u55u-qyg7/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | u55u-qyg7 |
| Name | Table 8 Offenses Known To Law Enforcement By Mississippi By City 2012 |
| Created | 2015-09-30T03:27:05Z |
| Publication Date | 2015-09-30T03:28:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | numeric metric | population                         | Population                         | number    | number      |
| Yes      | numeric metric | violentcrime                       | Violentcrime                       | number    | number      |
| Yes      | numeric metric | murder_andnonnegligentmanslaughter | Murder andnonnegligentmanslaughter | number    | number      |
| Yes      | numeric metric | forciblerape                       | Forciblerape                       | number    | number      |
| Yes      | numeric metric | robbery                            | Robbery                            | number    | number      |
| Yes      | numeric metric | aggravatedassault                  | Aggravatedassault                  | number    | number      |
| Yes      | numeric metric | propertycrime                      | Propertycrime                      | number    | number      |
| Yes      | numeric metric | burglary                           | Burglary                           | number    | number      |
| Yes      | numeric metric | larceny_theft                      | Larceny-theft                      | number    | number      |
| Yes      | numeric metric | motorvehicletheft                  | Motorvehicletheft                  | number    | number      |
| Yes      | numeric metric | arson                              | Arson                              | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u55u-qyg7 d:2012-01-01T00:00:00.000Z m:larceny_theft=164 m:robbery=11 m:arson=0 m:forciblerape=4 m:burglary=144 m:violentcrime=52 m:aggravatedassault=37 m:murder_andnonnegligentmanslaughter=0 m:propertycrime=319 m:motorvehicletheft=11 m:population=7529

series e:u55u-qyg7 d:2012-01-01T00:00:00.000Z m:larceny_theft=253 m:robbery=8 m:arson=0 m:forciblerape=8 m:burglary=119 m:violentcrime=63 m:aggravatedassault=44 m:murder_andnonnegligentmanslaughter=3 m:propertycrime=375 m:motorvehicletheft=3 m:population=11245

series e:u55u-qyg7 d:2012-01-01T00:00:00.000Z m:larceny_theft=58 m:robbery=1 m:arson=0 m:forciblerape=0 m:burglary=9 m:violentcrime=4 m:aggravatedassault=3 m:murder_andnonnegligentmanslaughter=0 m:propertycrime=69 m:motorvehicletheft=2 m:population=2962
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

metric m:violentcrime p:integer l:Violentcrime t:dataTypeName=number

metric m:murder_andnonnegligentmanslaughter p:integer l:"Murder andnonnegligentmanslaughter" t:dataTypeName=number

metric m:forciblerape p:integer l:Forciblerape t:dataTypeName=number

metric m:robbery p:integer l:Robbery t:dataTypeName=number

metric m:aggravatedassault p:integer l:Aggravatedassault t:dataTypeName=number

metric m:propertycrime p:integer l:Propertycrime t:dataTypeName=number

metric m:burglary p:integer l:Burglary t:dataTypeName=number

metric m:larceny_theft p:integer l:Larceny-theft t:dataTypeName=number

metric m:motorvehicletheft p:integer l:Motorvehicletheft t:dataTypeName=number

metric m:arson p:integer l:Arson t:dataTypeName=number

entity e:u55u-qyg7 l:"Table 8 Offenses Known To Law Enforcement By Mississippi By City 2012" t:url=https://data.jacksonms.gov/api/views/u55u-qyg7

property e:u55u-qyg7 t:meta.view v:id=u55u-qyg7 v:averageRating=0 v:name="Table 8 Offenses Known To Law Enforcement By Mississippi By City 2012"

property e:u55u-qyg7 t:meta.view.owner v:id=jiyc-ay7w v:profileImageUrlMedium=/api/users/jiyc-ay7w/profile_images/THUMB v:profileImageUrlLarge=/api/users/jiyc-ay7w/profile_images/LARGE v:screenName="Stuart Gano" v:profileImageUrlSmall=/api/users/jiyc-ay7w/profile_images/TINY v:lastNotificationSeenAt=1491499876 v:displayName="Stuart Gano"

property e:u55u-qyg7 t:meta.view.tableauthor v:id=jiyc-ay7w v:profileImageUrlMedium=/api/users/jiyc-ay7w/profile_images/THUMB v:profileImageUrlLarge=/api/users/jiyc-ay7w/profile_images/LARGE v:screenName="Stuart Gano" v:profileImageUrlSmall=/api/users/jiyc-ay7w/profile_images/TINY v:lastNotificationSeenAt=1491499876 v:displayName="Stuart Gano"
```

## Top Records

```ls
| population | violentcrime | murder_andnonnegligentmanslaughter | forciblerape | robbery | aggravatedassault | propertycrime | burglary | larceny_theft | motorvehicletheft | arson | 
| ========== | ============ | ================================== | ============ | ======= | ================= | ============= | ======== | ============= | ================= | ===== | 
| 7529       | 52           | 0                                  | 4            | 11      | 37                | 319           | 144      | 164           | 11                | 0     | 
| 11245      | 63           | 3                                  | 8            | 8       | 44                | 375           | 119      | 253           | 3                 | 0     | 
| 2962       | 4            | 0                                  | 0            | 1       | 3                 | 69            | 9        | 58            | 2                 | 0     | 
| 15010      | 109          | 1                                  | 23           | 36      | 49                | 871           | 286      | 577           | 8                 | 0     | 
| 2184       | 11           | 0                                  | 0            | 10      | 1                 | 70            | 27       | 43            | 0                 | 0     | 
| 22477      | 86           | 0                                  | 31           | 33      | 22                | 1339          | 268      | 991           | 80                | 11    | 
| 13756      | 104          | 0                                  | 12           | 29      | 63                | 736           | 314      | 368           | 54                | 2     | 
| 34141      | 70           | 1                                  | 12           | 17      | 40                | 999           | 402      | 562           | 35                | 1     | 
| 25530      | 33           | 0                                  | 10           | 2       | 21                | 629           | 172      | 446           | 11                | 0     | 
| 15706      | 58           | 3                                  | 11           | 26      | 18                | 845           | 185      | 651           | 9                 | 11    | 
```