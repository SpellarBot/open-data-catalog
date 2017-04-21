# LAPD Calls for Service 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lapd-calls-for-service-2014) |
| Metadata | [Link](https://data.lacity.org/api/views/mgue-vbsx) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/mgue-vbsx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/mgue-vbsx/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | mgue-vbsx |
| Name | LAPD Calls for Service 2014 |
| Category | A Safe City |
| Tags | police, crime, collisions, lapd, traffic, safety |
| Created | 2014-05-29T17:32:31Z |
| Publication Date | 2015-11-19T23:40:10Z |

## Description

LAPD Calls for Service 2014

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | incident_number | Incident Number | text          | text          |
| Yes      | series tag  | rpt_dist        | Rpt Dist        | text          | text          |
| Yes      | series tag  | area_occ        | Area Occ        | text          | text          |
| No       |             | dispatch_date   | Dispatch Date   | calendar_date | calendar_date |
| No       |             | dispatch_time   | Dispatch Time   | text          | text          |
| Yes      | series tag  | call_type_code  | Call Type Code  | text          | text          |
| Yes      | series tag  | call_type_text  | Call Type Text  | text          | text          |
```

## Time Field

```ls
Value = dispatch_date-dispatch_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dispatch_time,dispatch_date
```

## Data Commands

```ls
series e:mgue-vbsx d:2014-02-12T18:11:47.000Z t:call_type_code=415W t:call_type_text=WOMAN t:area_occ=Central t:rpt_dist=0127 t:incident_number=140212004623 m:row_number.mgue-vbsx=1

series e:mgue-vbsx d:2014-02-12T18:11:44.000Z t:call_type_code=415G t:call_type_text=GRP t:area_occ=Newton t:rpt_dist=1385 t:incident_number=140212004304 m:row_number.mgue-vbsx=2

series e:mgue-vbsx d:2014-02-12T18:11:41.000Z t:call_type_code=594O t:call_type_text="OFCR HLDG" t:area_occ=Newton t:rpt_dist=1307 t:incident_number=140212004626 m:row_number.mgue-vbsx=3
```

## Meta Commands

```ls
metric m:row_number.mgue-vbsx p:long l:"Row Number"

entity e:mgue-vbsx l:"LAPD Calls for Service 2014" t:url=https://data.lacity.org/api/views/mgue-vbsx

property e:mgue-vbsx t:meta.view v:id=mgue-vbsx v:category="A Safe City" v:averageRating=0 v:name="LAPD Calls for Service 2014"

property e:mgue-vbsx t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:mgue-vbsx t:meta.view.owner v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"

property e:mgue-vbsx t:meta.view.tableauthor v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"
```

## Top Records

```ls
| incident_number | rpt_dist | area_occ    | dispatch_date       | dispatch_time | call_type_code | call_type_text    | 
| =============== | ======== | =========== | =================== | ============= | ============== | ================= | 
| 140212004623    | 0127     | Central     | 2014-02-12T00:00:00 | 18:11:47      | 415W           | WOMAN             | 
| 140212004304    | 1385     | Newton      | 2014-02-12T00:00:00 | 18:11:44      | 415G           | GRP               | 
| 140212004626    | 1307     | Newton      | 2014-02-12T00:00:00 | 18:11:41      | 594O           | OFCR HLDG         | 
| 140212004685    | 2015     | Olympic     | 2014-02-12T00:00:00 | 18:11:29      | 1101           | NARCOTIC ACTIVITY | 
| 140212004668    | 1636     | Foothill    | 2014-02-12T00:00:00 | 18:10:58      | 904A           | AMB               | 
| 140212004596    | 1079     | West Valley | 2014-02-12T00:00:00 | 18:10:41      | 245D           | DOM VIOL          | 
| 140212004636    | 1998     | Mission     | 2014-02-12T00:00:00 | 18:09:53      | 242SN          | SUSP NOW          | 
| 140212004667    | 0453     | Hollenbeck  | 2014-02-12T00:00:00 | 18:09:08      | 415M8W         | MAN ASSLTG WMN    | 
| 140212004664    | 0657     | Hollywood   | 2014-02-12T00:00:00 | 18:08:52      | 246H           | HEARD ONLY        | 
| 140212004652    | 0723     | Wilshire    | 2014-02-12T00:00:00 | 18:08:43      | 918VM          | VIOLENT MALE      | 
```