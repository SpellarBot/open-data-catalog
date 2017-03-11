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
| Rows Updated | 2016-11-14T19:20:14Z |

## Description

LAPD Calls for Service

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | numeric metric | incident_number | Incident_Number | number        | text          |
| Yes      | series tag     | area_occ        | Area_Occ        | text          | text          |
| Yes      | numeric metric | rpt_dist        | Rpt_Dist        | number        | text          |
| Yes      | time           | dispatch_date   | Dispatch_Date   | calendar_date | calendar_date |
| Yes      | series tag     | dispatch_time   | Dispatch_Time   | text          | text          |
| Yes      | series tag     | call_type_code  | Call_Type_Code  | text          | text          |
| Yes      | series tag     | call_type_text  | Call_Type_Text  | text          | text          |
```

## Time Field

```ls
Value = dispatch_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xwgr-xw5q d:2016-10-31T00:00:00.000Z t:call_type_code=9212 t:call_type_text="TRESPASS SUSP" t:area_occ=Newton t:dispatch_time=04:57:44 m:rpt_dist=1321 m:incident_number=161031000621

series e:xwgr-xw5q d:2016-10-31T00:00:00.000Z t:call_type_code=459X t:call_type_text=I/P t:area_occ=Southwest t:dispatch_time=04:55:22 m:rpt_dist=396 m:incident_number=161031000620

series e:xwgr-xw5q d:2016-10-31T00:00:00.000Z t:call_type_code=906B1 t:call_type_text="CODE 30 RINGER" t:area_occ=Olympic t:dispatch_time=04:54:49 m:rpt_dist=2029 m:incident_number=161031000600
```

## Meta Commands

```ls
metric m:incident_number p:long l:Incident_Number t:dataTypeName=number

metric m:rpt_dist p:integer l:Rpt_Dist t:dataTypeName=number

entity e:xwgr-xw5q l:"LAPD Calls for Service 2015" t:url=https://data.lacity.org/api/views/xwgr-xw5q

property e:xwgr-xw5q t:meta.view v:id=xwgr-xw5q v:category="A Safe City" v:averageRating=0 v:name="LAPD Calls for Service 2015"

property e:xwgr-xw5q t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xwgr-xw5q t:meta.view.owner v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"

property e:xwgr-xw5q t:meta.view.tableauthor v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"
```