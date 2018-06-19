# King County office locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-office-locations-0991b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/heqd-ysmv) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/heqd-ysmv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/heqd-ysmv/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | heqd-ysmv |
| Name | King County office locations |
| Attribution | King County Facilities Management |
| Category | Operations |
| Tags | county, office, building, location, directions, phone, directory, services, licensing, courts, public safety |
| Created | 2011-05-10T20:30:42Z |
| Publication Date | 2013-04-17T23:44:55Z |

## Description

Locations of all official King County government workplaces

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | department       | Department       | text      | text        |
| Yes      | series tag     | division         | Division         | text      | text        |
| Yes      | series tag     | building         | Building         | text      | text        |
| No       |                | address          | Address          | text      | text        |
| Yes      | series tag     | city             | City             | text      | text        |
| Yes      | series tag     | zip              | Zip              | text      | text        |
| Yes      | series tag     | facility_type    | Facility type    | text      | text        |
| Yes      | series tag     | ownership        | Ownership        | text      | text        |
| Yes      | numeric metric | agreement        | Agreement #      | number    | number      |
| Yes      | numeric metric | budgeted         | 2006 budgeted    | number    | number      |
| Yes      | numeric metric | est_1_1          | 2007 EST         | number    | number      |
| Yes      | numeric metric | est_4            | 2009 EST         | number    | number      |
| Yes      | numeric metric | est_3            | 2011 EST         | number    | number      |
| Yes      | numeric metric | est_2            | 2016 EST         | number    | number      |
| Yes      | series tag     | parcel_id_number | Parcel ID number | text      | text        |
| Yes      | series tag     | downtown         | Downtown         | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:heqd-ysmv d:2013-04-17T16:35:51.000Z t:zip=98032 t:building="Plemmons Industries, Inc" t:ownership=lease t:department=SO t:parcel_id_number=3462800166 t:facility_type=Storage t:city=Kent m:agreement=1593

series e:heqd-ysmv d:2013-04-17T16:36:13.000Z t:building="Lake Union Fm" t:division=TRANSIT t:department=DOT t:downtown=false m:budgeted=59 m:est_2=59 m:est_3=59 m:est_4=59 m:est_1_1=59

series e:heqd-ysmv d:2013-04-17T16:35:19.000Z t:building="Link Operating Base(Sound Transit)" t:division=TRANSIT t:department=DOT t:downtown=false m:budgeted=29 m:est_2=311 m:est_3=311 m:est_4=311 m:est_1_1=147
```

## Meta Commands

```ls
metric m:agreement p:integer l:"Agreement #" t:dataTypeName=number

metric m:budgeted p:integer l:"2006 budgeted" t:dataTypeName=number

metric m:est_1_1 p:integer l:"2007 EST" t:dataTypeName=number

metric m:est_4 p:integer l:"2009 EST" t:dataTypeName=number

metric m:est_3 p:integer l:"2011 EST" t:dataTypeName=number

metric m:est_2 p:integer l:"2016 EST" t:dataTypeName=number

entity e:heqd-ysmv l:"King County office locations" t:attribution="King County Facilities Management" t:url=https://data.kingcounty.gov/api/views/heqd-ysmv

property e:heqd-ysmv t:meta.view v:id=heqd-ysmv v:category=Operations v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="King County office locations" v:attribution="King County Facilities Management"

property e:heqd-ysmv t:meta.view.license v:name="Public Domain"

property e:heqd-ysmv t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:heqd-ysmv t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | department | division                         | building                           | address                 | city | zip   | facility_type  | ownership | agreement | budgeted | est_1_1 | est_4 | est_3 | est_2 | parcel_id_number | downtown | 
| =========== | ========== | ================================ | ================================== | ======================= | ==== | ===== | ============== | ========= | ========= | ======== | ======= | ===== | ===== | ===== | ================ | ======== | 
| 1366216551  | SO         |                                  | Plemmons Industries, Inc           | 1609 Central Ave S      | Kent | 98032 | Storage        | lease     | 1593      |          |         |       |       |       | 3462800166       |          | 
| 1366216573  | DOT        | TRANSIT                          | Lake Union Fm                      |                         |      |       |                |           |           | 59       | 59      | 59    | 59    | 59    |                  | false    | 
| 1366216519  | DOT        | TRANSIT                          | Link Operating Base(Sound Transit) |                         |      |       |                |           |           | 29       | 147     | 311   | 311   | 311   |                  | false    | 
| 1366216271  | DNRP/PARKS |                                  | Kent School District               | Kent                    |      |       | Ground         | lease     | 1048      |          |         |       |       |       |                  |          | 
| 1366216510  | DOT        | TRANSIT                          | Stores                             |                         |      |       |                |           |           | 25       | 25      | 25    | 26    | 26    |                  | false    | 
| 1366216271  | DES        | REALS - Community Service Center | Fall City Community Service Center | ???                     |      |       | Service Center | use       |           | 0        | 0       | 0     | 0     | 0     |                  | false    | 
| 1366216271  | SO         |                                  | Snoqualmie Pass Fpd #51            | Snoq. Pass Comm. Center |      |       | Office         | lease     | 1069      |          |         |       |       |       |                  |          | 
| 1366216271  | DNRP/PARKS |                                  | State Of Wa                        | Adj To Aururn Narrows   |      |       | Park           | lease     | 1353      |          |         |       |       |       |                  |          | 
| 1366216271  | DNRP/PARKS |                                  | Shoreline School Dist              | Cordell Hull School     |      |       | Park           | lease     | 1137      |          |         |       |       |       |                  |          | 
| 1366216271  | DNRP/PARKS |                                  | Us Army Corps Of Engrs.            | Cougar Mountain Park    |      |       | Park           | lease     | 1253      |          |         |       |       |       |                  |          | 
```