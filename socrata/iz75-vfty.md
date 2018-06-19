# Rms ITest

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rms-itest-d3fb0) |
| Metadata | [Link](https://data.seattle.gov/api/views/iz75-vfty) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/iz75-vfty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/iz75-vfty/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | iz75-vfty |
| Name | Rms ITest |
| Category | Public Safety |
| Created | 2013-02-12T19:16:24Z |
| Publication Date | 2013-02-12T22:16:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | numeric metric | idcolumn                    | IDColumn                    | number        | number        |
| Yes      | numeric metric | 2010127523                  | 2010127523                  | number        | number        |
| Yes      | numeric metric | 1206                        | 1206                        | number        | number        |
| No       |                | _0                          | 0                           | number        | number        |
| Yes      | series tag     | robbery_street_bodyforce    | ROBBERY-STREET-BODYFORCE    | text          | text          |
| Yes      | numeric metric | 1200                        | 1200                        | number        | number        |
| Yes      | series tag     | robbery                     | ROBBERY                     | text          | text          |
| Yes      | time           | date1                       | date1                       | calendar_date | calendar_date |
| No       |                | date2                       | date2                       | calendar_date | calendar_date |
| Yes      | series tag     | 24xx_block_of_sw_genesee_st | 24XX BLOCK OF SW GENESEE ST | text          | text          |
| No       |                | w                           | W                           | text          | text          |
| No       |                | w1                          | W1                          | text          | text          |
| Yes      | numeric metric | 9900_2011                   | 9900.2011                   | number        | number        |
| Yes      | numeric metric | 122_363840492               | -122.363840492              | number        | number        |
| Yes      | numeric metric | 47_564727820                | 47.564727820                | number        | number        |
```

## Time Field

```ls
Value = date1
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = _0,date2,w,w1
```

## Data Commands

```ls
series e:iz75-vfty d:2010-04-19T16:23:00.000Z t:24xx_block_of_sw_genesee_st="46XX BLOCK OF S HOLLY ST" t:robbery=BURGLARY t:robbery_street_bodyforce=BURGLARY-NOFORCE-RES m:47_564727820=47.542470251 m:1206=2204 m:1200=2200 m:2010127523=2010127550 m:idcolumn=31457 m:122_363840492=-122.274090991 m:9900_2011=11101.1002

series e:iz75-vfty d:2010-04-21T07:57:00.000Z t:24xx_block_of_sw_genesee_st="13XX BLOCK OF STEWART ST" t:robbery=BURGLARY t:robbery_street_bodyforce=BURGLARY-FORCE-NONRES m:47_564727820=47.619221274 m:1206=2203 m:1200=2200 m:2010127523=2010129519 m:idcolumn=31458 m:122_363840492=-122.329773841 m:9900_2011=7300.2001

series e:iz75-vfty d:2010-04-20T12:44:00.000Z t:24xx_block_of_sw_genesee_st="5XX BLOCK OF OLIVE WAY" t:robbery=BURGLARY t:robbery_street_bodyforce=BURGLARY-NOFORCE-NONRES m:47_564727820=47.612897738 m:1206=2205 m:1200=2200 m:2010127523=2010128562 m:idcolumn=31459 m:122_363840492=-122.336837724 m:9900_2011=8200.1003
```

## Meta Commands

```ls
metric m:idcolumn p:integer l:IDColumn t:dataTypeName=number

metric m:2010127523 p:integer l:2010127523 t:dataTypeName=number

metric m:1206 p:integer l:1206 t:dataTypeName=number

metric m:1200 p:integer l:1200 t:dataTypeName=number

metric m:9900_2011 p:double l:9900.2011 t:dataTypeName=number

metric m:122_363840492 p:double l:-122.363840492 t:dataTypeName=number

metric m:47_564727820 p:double l:47.564727820 t:dataTypeName=number

entity e:iz75-vfty l:"Rms ITest" t:url=https://data.seattle.gov/api/views/iz75-vfty

property e:iz75-vfty t:meta.view v:id=iz75-vfty v:category="Public Safety" v:averageRating=0 v:name="Rms ITest"

property e:iz75-vfty t:meta.view.license v:name="Public Domain"

property e:iz75-vfty t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:iz75-vfty t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| idcolumn | 2010127523 | 1206 | _0 | robbery_street_bodyforce | 1200 | robbery  | date1               | date2               | 24xx_block_of_sw_genesee_st                | w | w1 | 9900_2011  | 122_363840492  | 47_564727820 | 
| ======== | ========== | ==== | == | ======================== | ==== | ======== | =================== | =================== | ========================================== | = | == | ========== | ============== | ============ | 
| 31457    | 2010127550 | 2204 | 0  | BURGLARY-NOFORCE-RES     | 2200 | BURGLARY | 2010-04-19T16:23:00 | 2010-04-15T14:00:00 | 46XX BLOCK OF S HOLLY ST                   | S | S1 | 11101.1002 | -122.274090991 | 47.542470251 | 
| 31458    | 2010129519 | 2203 | 0  | BURGLARY-FORCE-NONRES    | 2200 | BURGLARY | 2010-04-21T07:57:00 | 2010-04-21T00:01:00 | 13XX BLOCK OF STEWART ST                   | D | D2 | 7300.2001  | -122.329773841 | 47.619221274 | 
| 31459    | 2010128562 | 2205 | 0  | BURGLARY-NOFORCE-NONRES  | 2200 | BURGLARY | 2010-04-20T12:44:00 | 2010-04-12T15:00:00 | 5XX BLOCK OF OLIVE WAY                     | M | M2 | 8200.1003  | -122.336837724 | 47.612897738 | 
| 31460    | 2010128837 | 2202 | 0  | BURGLARY-FORCE-RES       | 2200 | BURGLARY | 2010-04-20T16:28:00 | 2010-04-20T10:30:00 | 103XX BLOCK OF 51ST AVE S                  | S | S3 | 11900.5003 | -122.270103931 | 47.507905705 | 
| 31461    | 2010131571 | 1305 | 0  | ASSLT-AGG-WEAPON         | 1300 | ASSAULT  | 2010-04-22T21:06:00 | 2010-04-22T21:06:00 | 83XX BLOCK OF RAINIER AVE S                | S | S2 | 11800.6005 | -122.269987327 | 47.529330662 | 
| 31462    | 2010131753 | 2203 | 0  | BURGLARY-FORCE-NONRES    | 2200 | BURGLARY | 2010-04-23T00:37:00 | 2010-04-23T00:37:00 | 17XX BLOCK OF E UNION ST                   | G | G1 | 7900.3     | -122.309514473 | 47.612903428 | 
| 31463    | 2010130853 | 2203 | 0  | BURGLARY-FORCE-NONRES    | 2200 | BURGLARY | 2010-04-22T10:49:00 | 2010-04-22T01:00:00 | 17XX BLOCK OF E MADISON ST                 | G | G1 | 7900.4     | -122.309496850 | 47.615862548 | 
| 31464    | 2010128822 | 1206 | 0  | ROBBERY-STREET-BODYFORCE | 1200 | ROBBERY  | 2010-04-20T16:17:00 | 2010-04-20T16:17:00 | 42XX BLOCK OF S JUNEAU ST                  | R | R3 | 10300.201  | -122.279461531 | 47.549700148 | 
| 31466    | 2010127505 | 2203 | 0  | BURGLARY-FORCE-NONRES    | 2200 | BURGLARY | 2010-04-19T15:48:00 | 2010-04-19T15:48:00 | 100XX BLOCK OF MARTIN LUTHER KING JR WAY S | S | S2 | 11700.4005 | -122.278352452 | 47.510452909 | 
| 31468    | 2010127894 | 2202 | 0  | BURGLARY-FORCE-RES       | 2200 | BURGLARY | 2010-04-19T21:15:00 | 2010-04-15T09:00:00 | 80XX BLOCK OF 17TH AVE NW                  | B | B2 | 3000.5008  | -122.378945638 | 47.687797147 | 
```