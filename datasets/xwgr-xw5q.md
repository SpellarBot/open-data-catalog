# LAPD Calls for Service 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-cfs-2016-11062016) |
| Metadata | [Link](https://data.lacity.org/api/views/xwgr-xw5q) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/xwgr-xw5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/xwgr-xw5q/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | xwgr-xw5q |
| Name | LAPD Calls for Service 2015 |
| Category | A Safe City |
| Tags | 911, cfs |
| Created | 2016-11-14T19:17:44Z |
| Publication Date | 2016-11-14T21:57:46Z |

## Description

LAPD Calls for Service

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | incident_number | Incident_Number | text          | text          |
| Yes      | series tag  | area_occ        | Area_Occ        | text          | text          |
| Yes      | series tag  | rpt_dist        | Rpt_Dist        | text          | text          |
| No       |             | dispatch_date   | Dispatch_Date   | calendar_date | calendar_date |
| No       |             | dispatch_time   | Dispatch_Time   | text          | text          |
| Yes      | series tag  | call_type_code  | Call_Type_Code  | text          | text          |
| Yes      | series tag  | call_type_text  | Call_Type_Text  | text          | text          |
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
series e:xwgr-xw5q d:2016-10-31T04:57:44.000Z t:call_type_code=9212 t:call_type_text="TRESPASS SUSP" t:area_occ=Newton t:rpt_dist=1321 t:incident_number=161031000621 m:row_number.xwgr-xw5q=1

series e:xwgr-xw5q d:2016-10-31T04:55:22.000Z t:call_type_code=459X t:call_type_text=I/P t:area_occ=Southwest t:rpt_dist=0396 t:incident_number=161031000620 m:row_number.xwgr-xw5q=2

series e:xwgr-xw5q d:2016-10-31T04:54:49.000Z t:call_type_code=906B1 t:call_type_text="CODE 30 RINGER" t:area_occ=Olympic t:rpt_dist=2029 t:incident_number=161031000600 m:row_number.xwgr-xw5q=3
```

## Meta Commands

```ls
metric m:row_number.xwgr-xw5q p:long l:"Row Number"

entity e:xwgr-xw5q l:"LAPD Calls for Service 2015" t:url=https://data.lacity.org/api/views/xwgr-xw5q

property e:xwgr-xw5q t:meta.view d:2017-06-09T14:00:54.343Z v:id=xwgr-xw5q v:category="A Safe City" v:averageRating=0 v:name="LAPD Calls for Service 2015"

property e:xwgr-xw5q t:meta.view.license d:2017-06-09T14:00:54.343Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xwgr-xw5q t:meta.view.owner d:2017-06-09T14:00:54.343Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:lastNotificationSeenAt=1496929966 v:displayName="LAPD OpenData"

property e:xwgr-xw5q t:meta.view.tableauthor d:2017-06-09T14:00:54.343Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1496929966 v:displayName="LAPD OpenData"
```

## Top Records

```ls
| incident_number | area_occ    | rpt_dist | dispatch_date       | dispatch_time | call_type_code | call_type_text | 
| =============== | =========== | ======== | =================== | ============= | ============== | ============== | 
| 161031000621    | Newton      | 1321     | 2016-10-31T00:00:00 | 04:57:44      | 9212           | TRESPASS SUSP  | 
| 161031000620    | Southwest   | 0396     | 2016-10-31T00:00:00 | 04:55:22      | 459X           | I/P            | 
| 161031000600    | Olympic     | 2029     | 2016-10-31T00:00:00 | 04:54:49      | 906B1          | CODE 30 RINGER | 
| 161031000556    | West Valley | 1008     | 2016-10-31T00:00:00 | 04:50:22      | 507P           | PARTY          | 
| 161031000609    | 77th Street | 1256     | 2016-10-31T00:00:00 | 04:45:49      | 620D           | DOM VIOL       | 
| 161031000596    | Pacific     | 1453     | 2016-10-31T00:00:00 | 04:42:58      | 999F           | FD HELP        | 
| 161031000574    | Rampart     | 0257     | 2016-10-31T00:00:00 | 04:42:21      | 415G           | GRP            | 
| 161031000606    | 77th Street | 1219     | 2016-10-31T00:00:00 | 04:37:32      | 620FR          | FAMILY R/O     | 
| 161031000586    | 77th Street | 1241     | 2016-10-31T00:00:00 | 04:33:59      | 9212           | TRESPASS SUSP  | 
| 161031000598    | Devonshire  | 1753     | 2016-10-31T00:00:00 | 04:33:53      | 415M           | MAN            | 
```