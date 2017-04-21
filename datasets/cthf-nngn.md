# LAFD_ResponseMetrics_RawData

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lafd-responsemetrics-rawdata) |
| Metadata | [Link](https://data.lacity.org/api/views/cthf-nngn) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/cthf-nngn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/cthf-nngn/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | cthf-nngn |
| Name | LAFD_ResponseMetrics_RawData |
| Category | A Safe City |
| Tags | lafd, response metrics, los angeles fire department, open data, cad |
| Created | 2014-09-29T21:22:05Z |
| Publication Date | 2015-10-20T18:01:49Z |

## Description

The Los Angeles Fire Department (LAFD)?s Computer Aided Dispatch (CAD) system is a transactional, event?driven system that records dates and time stamps based on events triggered by two distinct human interactions: interaction with CAD at the dispatch center via CAD workstation, and interaction with CAD via the Mobile Data Computer (MDC) installed in the responding LAFD unit, communicating with CAD through the LAFD?s Radio Network Controller (RNC).

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                         | Data Type | Render Type |
| ======== | =========== | ========================== | ============================ | ========= | =========== |
| No       | time        | :updated_at                | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | randomized_incident_number | Randomized Incident Number   | text      | number      |
| Yes      | series tag  | first_in_district          | First in District            | text      | number      |
| Yes      | series tag  | emergency_dispatch_code    | Emergency Dispatch Code      | text      | text        |
| Yes      | series tag  | dispatch_sequence          | Dispatch Sequence            | text      | text        |
| Yes      | series tag  | dispatch_status            | Dispatch Status              | text      | text        |
| Yes      | series tag  | unit_type                  | Unit Type                    | text      | text        |
| Yes      | series tag  | ppe_level                  | PPE Level                    | text      | text        |
| No       |             | incident_creation_time     | Incident Creation Time (GMT) | text      | text        |
| No       |             | time_of_dispatch           | Time of Dispatch (GMT)       | text      | text        |
| No       |             | en_route_time              | En Route Time (GMT)          | text      | text        |
| No       |             | on_scene_time              | On Scene Time (GMT)          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = incident_creation_time,time_of_dispatch,en_route_time,on_scene_time
```

## Data Commands

```ls
series e:cthf-nngn d:2014-09-29T14:27:36.000Z t:emergency_dispatch_code=Emergency t:first_in_district=2 t:randomized_incident_number=201301168525 m:row_number.cthf-nngn=1

series e:cthf-nngn d:2014-09-29T14:27:36.000Z t:emergency_dispatch_code=Emergency t:first_in_district=46 t:randomized_incident_number=201301745126 m:row_number.cthf-nngn=2

series e:cthf-nngn d:2014-09-29T14:27:37.000Z t:emergency_dispatch_code=Emergency t:first_in_district=59 t:randomized_incident_number=201301275113 m:row_number.cthf-nngn=3
```

## Meta Commands

```ls
metric m:row_number.cthf-nngn p:long l:"Row Number"

entity e:cthf-nngn l:LAFD_ResponseMetrics_RawData t:url=https://data.lacity.org/api/views/cthf-nngn

property e:cthf-nngn t:meta.view v:id=cthf-nngn v:category="A Safe City" v:averageRating=0 v:name=LAFD_ResponseMetrics_RawData

property e:cthf-nngn t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cthf-nngn t:meta.view.owner v:id=9uet-7vvk v:profileImageUrlMedium=/api/users/9uet-7vvk/profile_images/THUMB v:profileImageUrlLarge=/api/users/9uet-7vvk/profile_images/LARGE v:screenName="Fire OpenData" v:profileImageUrlSmall=/api/users/9uet-7vvk/profile_images/TINY v:lastNotificationSeenAt=1491434258 v:displayName="Fire OpenData"

property e:cthf-nngn t:meta.view.tableauthor v:id=9uet-7vvk v:profileImageUrlMedium=/api/users/9uet-7vvk/profile_images/THUMB v:profileImageUrlLarge=/api/users/9uet-7vvk/profile_images/LARGE v:screenName="Fire OpenData" v:profileImageUrlSmall=/api/users/9uet-7vvk/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1491434258 v:displayName="Fire OpenData"
```

## Top Records

```ls
| :updated_at | randomized_incident_number | first_in_district | emergency_dispatch_code | dispatch_sequence | dispatch_status | unit_type | ppe_level | incident_creation_time | time_of_dispatch | en_route_time | on_scene_time | 
| =========== | ========================== | ================= | ======================= | ================= | =============== | ========= | ========= | ====================== | ================ | ============= | ============= | 
| 1412000856  | 201301168525               | 2                 | Emergency               |                   |                 |           |           | 18:27:04               |                  |               |               | 
| 1412000856  | 201301745126               | 46                | Emergency               |                   |                 |           |           | 01:25:31               |                  |               |               | 
| 1412000857  | 201301275113               | 59                | Emergency               |                   |                 |           |           | 22:21:26               |                  |               |               | 
| 1412000861  | 201301433152               | 29                | Emergency               |                   |                 |           |           | 05:40:00               |                  |               |               | 
| 1412000866  | 201301537323               | 63                | Emergency               |                   |                 |           |           | 18:56:02               |                  |               |               | 
| 1412000868  | 201301397942               | 89                | Emergency               |                   |                 |           |           | 02:11:21               |                  |               |               | 
| 1412000870  | 201301585924               | 61                | Emergency               |                   |                 |           |           | 05:38:41               |                  |               |               | 
| 1412000870  | 201301549548               | 81                | Emergency               |                   |                 |           |           | 06:44:35               |                  |               |               | 
| 1412000871  | 201301590987               | 15                | Emergency               |                   |                 |           |           | 18:04:41               |                  |               |               | 
| 1412000871  | 201301498422               | 78                | Emergency               |                   |                 |           |           | 00:53:46               |                  |               |               | 
```