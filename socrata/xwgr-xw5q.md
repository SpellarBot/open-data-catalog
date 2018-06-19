# LAPD Calls for Service 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-cfs-2016-11062016) |
| Metadata | [Link](https://data.lacity.org/api/views/xwgr-xw5q) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/xwgr-xw5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/xwgr-xw5q/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | xwgr-xw5q |
| Name | LAPD Calls for Service 2016 |
| Category | A Safe City |
| Tags | 911, cfs, calls, lapd, safety, police |
| Created | 2016-11-14T19:17:44Z |
| Publication Date | 2017-08-08T18:12:24Z |

## Description

This dataset reflects calls for service incidents in the City of Los Angeles in the year 2016. This data is as accurate as the data in the database. Please note questions or concerns in the comments.

## Columns

```ls
| Included | Schema Type | Field Name      | Name                  | Data Type     | Render Type   |
| ======== | =========== | =============== | ===================== | ============= | ============= |
| Yes      | series tag  | incident_number | Incident Number       | text          | text          |
| Yes      | series tag  | rpt_dist        | Reporting District    | text          | text          |
| Yes      | series tag  | area_occ        | Area Occurred         | text          | text          |
| No       |             | dispatch_date   | Dispatch Date         | calendar_date | calendar_date |
| No       |             | dispatch_time   | Dispatch Time         | text          | text          |
| Yes      | series tag  | call_type_code  | Call Type Code        | text          | text          |
| Yes      | series tag  | call_type_text  | Call Type Description | text          | text          |
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
series e:xwgr-xw5q d:2016-10-31T04:57:44.000Z t:rpt_dist=1321 t:call_type_code=9212 t:area_occ=Newton t:call_type_text="TRESPASS SUSP" t:incident_number=161031000621 m:row_number.xwgr-xw5q=1

series e:xwgr-xw5q d:2016-10-31T04:55:22.000Z t:rpt_dist=0396 t:call_type_code=459X t:area_occ=Southwest t:call_type_text=I/P t:incident_number=161031000620 m:row_number.xwgr-xw5q=2

series e:xwgr-xw5q d:2016-10-31T04:54:49.000Z t:rpt_dist=2029 t:call_type_code=906B1 t:area_occ=Olympic t:call_type_text="CODE 30 RINGER" t:incident_number=161031000600 m:row_number.xwgr-xw5q=3
```

## Meta Commands

```ls
metric m:row_number.xwgr-xw5q p:long l:"Row Number"

entity e:xwgr-xw5q l:"LAPD Calls for Service 2016" t:url=https://data.lacity.org/api/views/xwgr-xw5q

property e:xwgr-xw5q t:meta.view d:2017-09-25T07:32:10.339Z v:averageRating=0 v:name="LAPD Calls for Service 2016" v:id=xwgr-xw5q v:category="A Safe City"

property e:xwgr-xw5q t:meta.view.license d:2017-09-25T07:32:10.339Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xwgr-xw5q t:meta.view.owner d:2017-09-25T07:32:10.339Z v:displayName="LAPD OpenData" v:lastNotificationSeenAt=1501608368 v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:id=art8-rc4x v:screenName="LAPD OpenData" v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB

property e:xwgr-xw5q t:meta.view.tableauthor d:2017-09-25T07:32:10.339Z v:displayName="LAPD OpenData" v:lastNotificationSeenAt=1501608368 v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:id=art8-rc4x v:screenName="LAPD OpenData" v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB
```

## Top Records

```ls
| incident_number | rpt_dist | area_occ    | dispatch_date       | dispatch_time | call_type_code | call_type_text | 
| =============== | ======== | =========== | =================== | ============= | ============== | ============== | 
| 161031000621    | 1321     | Newton      | 2016-10-31T00:00:00 | 04:57:44      | 9212           | TRESPASS SUSP  | 
| 161031000620    | 0396     | Southwest   | 2016-10-31T00:00:00 | 04:55:22      | 459X           | I/P            | 
| 161031000600    | 2029     | Olympic     | 2016-10-31T00:00:00 | 04:54:49      | 906B1          | CODE 30 RINGER | 
| 161031000556    | 1008     | West Valley | 2016-10-31T00:00:00 | 04:50:22      | 507P           | PARTY          | 
| 161031000609    | 1256     | 77th Street | 2016-10-31T00:00:00 | 04:45:49      | 620D           | DOM VIOL       | 
| 161031000596    | 1453     | Pacific     | 2016-10-31T00:00:00 | 04:42:58      | 999F           | FD HELP        | 
| 161031000574    | 0257     | Rampart     | 2016-10-31T00:00:00 | 04:42:21      | 415G           | GRP            | 
| 161031000606    | 1219     | 77th Street | 2016-10-31T00:00:00 | 04:37:32      | 620FR          | FAMILY R/O     | 
| 161031000586    | 1241     | 77th Street | 2016-10-31T00:00:00 | 04:33:59      | 9212           | TRESPASS SUSP  | 
| 161031000598    | 1753     | Devonshire  | 2016-10-31T00:00:00 | 04:33:53      | 415M           | MAN            | 
```