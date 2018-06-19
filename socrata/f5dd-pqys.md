# HPD Crime Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-crime-incidents) |
| Metadata | [Link](https://data.honolulu.gov/api/views/f5dd-pqys) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/f5dd-pqys/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/f5dd-pqys/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | f5dd-pqys |
| Name | HPD Crime Incidents |
| Created | 2014-12-13T00:26:29Z |
| Publication Date | 2015-03-12T00:11:07Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | objectid     | ObjectID     | text      | text        |
| Yes      | series tag     | kilonbr      | KiloNBR      | text      | text        |
| No       |                | blockaddress | BlockAddress | text      | text        |
| Yes      | series tag     | cmid         | CMID         | text      | text        |
| Yes      | series tag     | cmagency     | CMAgency     | text      | text        |
| Yes      | time           | date         | Date         | date      | date        |
| Yes      | series tag     | type         | Type         | text      | text        |
| Yes      | series tag     | status       | Status       | text      | text        |
| Yes      | numeric metric | score        | Score        | number    | text        |
| Yes      | series tag     | side         | Side         | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = blockaddress
```

## Data Commands

```ls
series e:f5dd-pqys d:2017-03-31T09:55:00.000Z t:kilonbr=LHP170330001881 t:cmagency="Honolulu PD, HI" t:cmid=Honolulu_PD_HI_LHP170330001881_210 t:type=DUI t:objectid=839775 t:status=U m:score=0

series e:f5dd-pqys d:2017-03-31T10:30:00.000Z t:kilonbr=LHP170331000021 t:cmagency="Honolulu PD, HI" t:cmid=Honolulu_PD_HI_LHP170331000021_210 t:type=DUI t:objectid=839776 t:status=U m:score=0

series e:f5dd-pqys d:2017-03-31T10:35:00.000Z t:kilonbr=LHP170331000026 t:cmagency="Honolulu PD, HI" t:cmid=Honolulu_PD_HI_LHP170331000026_210 t:type=DUI t:objectid=839777 t:status=U m:score=0
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:f5dd-pqys l:"HPD Crime Incidents" t:url=https://data.honolulu.gov/api/views/f5dd-pqys

property e:f5dd-pqys t:meta.view d:2017-09-25T07:27:21.613Z v:averageRating=0 v:name="HPD Crime Incidents" v:id=f5dd-pqys

property e:f5dd-pqys t:meta.view.owner d:2017-09-25T07:27:21.613Z v:displayName="Open Data" v:lastNotificationSeenAt=1504043175 v:id=sr3i-nqxd v:screenName="Open Data"

property e:f5dd-pqys t:meta.view.tableauthor d:2017-09-25T07:27:21.613Z v:displayName="Open Data" v:lastNotificationSeenAt=1504043175 v:roleName=administrator v:id=sr3i-nqxd v:screenName="Open Data"
```

## Top Records

```ls
| objectid | kilonbr         | blockaddress                  | cmid                               | cmagency        | date       | type                     | status | score | side | 
| ======== | =============== | ============================= | ================================== | =============== | ========== | ======================== | ====== | ===== | ==== | 
| 839775   | LHP170330001881 | 0 BLOCK H1E FWY               | Honolulu_PD_HI_LHP170330001881_210 | Honolulu PD, HI | 1490954100 | DUI                      | U      | 0     |      | 
| 839776   | LHP170331000021 | 0 BLOCK H1E FWY               | Honolulu_PD_HI_LHP170331000021_210 | Honolulu PD, HI | 1490956200 | DUI                      | U      | 0     |      | 
| 839777   | LHP170331000026 | 0 BLOCK H1E FWY               | Honolulu_PD_HI_LHP170331000026_210 | Honolulu PD, HI | 1490956500 | DUI                      | U      | 0     |      | 
| 839958   | LHP170405000518 | DWN TO EARTH                  | Honolulu_PD_HI_LHP170405000518_060 | Honolulu PD, HI | 1491419520 | THEFT/LARCENY            | U      | 0     |      | 
| 840000   | LHP170405000869 | CORAL SEA RD&FD ROOSEVELT AVE | Honolulu_PD_HI_LHP170405000869_064 | Honolulu PD, HI | 1491433440 | VEHICLE BREAK-IN/THEFT   | U      | 0     |      | 
| 840001   | LHP170405000881 | 900 BLOCK VALKENBURGH ST      | Honolulu_PD_HI_LHP170405000881_060 | Honolulu PD, HI | 1491433980 | THEFT/LARCENY            | U      | 0     |      | 
| 840054   | LHP170405001560 | 1200 BLOCK LUAKALAI ST        | Honolulu_PD_HI_LHP170405001560_060 | Honolulu PD, HI | 1491458400 | THEFT/LARCENY            | U      | 0     |      | 
| 840055   | LHP170405001575 | ALA ALII ST&KAHUAPAANI ST     | Honolulu_PD_HI_LHP170405001575_180 | Honolulu PD, HI | 1491459240 | DRUGS/ALCOHOL VIOLATIONS | U      | 0     |      | 
| 839215   | LHP170327000308 | 913200 BLOCK KUALAKAI PKWY    | Honolulu_PD_HI_LHP170327000308_064 | Honolulu PD, HI | 1490635200 | VEHICLE BREAK-IN/THEFT   | U      | 0     |      | 
| 839218   | LHP170327000324 | 700 BLOCK KAKALA ST           | Honolulu_PD_HI_LHP170327000324_050 | Honolulu PD, HI | 1490636220 | BURGLARY                 | U      | 0     |      | 
```