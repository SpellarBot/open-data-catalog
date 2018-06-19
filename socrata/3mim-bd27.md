# Enrollment Capacity and Utilization Reports Regular HS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-regular-hs-93adf) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3mim-bd27) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3mim-bd27/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3mim-bd27/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3mim-bd27 |
| Name | Enrollment Capacity and Utilization Reports Regular HS |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2013-04-18T15:19:05Z |
| Publication Date | 2013-11-15T21:32:56Z |

## Description

This dataset is no longer maintained. Updated enrollment capacity and utilization data can be found at https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/hq56-zhrp
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/q9xk-w9iv
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/gkd7-3vk7
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/8b9a-pywy

Enrollment, capacity and utilization data for every regular high school building and schools in those buildings.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                | Data Type | Render Type |
| ======== | ============== | ================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | district                           | District                            | text      | number      |
| Yes      | series tag     | bldg_i_d_                          | Bldg I.D.                           | text      | text        |
| Yes      | series tag     | building_name                      | Building Name                       | text      | text        |
| Yes      | numeric metric | bldg_enroll                        | Bldg Enroll                         | number    | number      |
| Yes      | numeric metric | bldg_adjusted_capacity_historical_ | Bldg Adjusted Capacity (Historical) | number    | number      |
| Yes      | numeric metric | bldg_over_under_historical         | Bldg Over/Under Historical          | number    | number      |
| Yes      | numeric metric | bldg_utilization_historical_       | Bldg Utilization (Historical)       | number    | number      |
| Yes      | numeric metric | bldg_capacity_target_              | Bldg Capacity (Target)              | number    | number      |
| Yes      | numeric metric | bldg_over_under_target_            | Bldg Over/Under (Target)            | number    | number      |
| Yes      | numeric metric | bldg_utilization_target_           | Bldg Utilization (Target)           | number    | number      |
| Yes      | series tag     | org_id                             | Org ID                              | text      | text        |
| Yes      | series tag     | organization_name                  | Organization Name                   | text      | text        |
| Yes      | numeric metric | org_enroll                         | Org Enroll                          | number    | number      |
| Yes      | numeric metric | org_adjusted_capacity_historical_  | Org Adjusted Capacity (Historical)  | number    | number      |
| Yes      | numeric metric | org_over_under_historical_         | Org Over/Under (Historical)         | number    | number      |
| Yes      | numeric metric | org_utilization_historical_        | Org Utilization (Historical)        | number    | number      |
| Yes      | numeric metric | org_adjusted_capacity_target_      | Org Adjusted Capacity (Target)      | number    | number      |
| Yes      | numeric metric | org_over_under_target_             | Org Over Under (Target)             | number    | number      |
| Yes      | numeric metric | org_utilization_target_            | Org Utilization (Target)            | number    | number      |
| Yes      | numeric metric | no_of_spec_rooms_used              | No. of Spec rooms used              | number    | number      |
| Yes      | series tag     | inclusionary                       | Inclusionary                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3mim-bd27 d:2013-11-15T13:32:38.000Z t:org_id=Q410 t:building_name="BEACH CHANNEL HS - Q" t:bldg_i_d_=Q410 t:district=78 t:organization_name="BEACH CHANNEL HS - QUEENS" m:org_adjusted_capacity_historical_=1195 m:bldg_over_under_historical=-1625 m:bldg_adjusted_capacity_historical_=3324 m:bldg_utilization_target_=56 m:no_of_spec_rooms_used=24 m:bldg_over_under_target_=-1355 m:bldg_enroll=1699 m:org_utilization_historical_=33 m:org_over_under_target_=-1355 m:org_enroll=397 m:bldg_capacity_target_=3054 m:org_over_under_historical_=-798 m:org_adjusted_capacity_target_=3054 m:bldg_utilization_historical_=51 m:org_utilization_target_=56

series e:3mim-bd27 d:2013-11-15T13:32:38.000Z t:org_id=M984 t:building_name="FAR ROCKAWAY HS - Q" t:bldg_i_d_=Q465 t:district=78 t:organization_name=LYFE m:bldg_enroll=1632 m:org_over_under_target_=-220 m:bldg_over_under_historical=-249 m:bldg_adjusted_capacity_historical_=1881 m:bldg_capacity_target_=1852 m:org_over_under_historical_=0 m:bldg_utilization_target_=88 m:no_of_spec_rooms_used=0 m:org_adjusted_capacity_target_=1852 m:bldg_utilization_historical_=87 m:org_utilization_target_=88 m:bldg_over_under_target_=-220

series e:3mim-bd27 d:2013-11-15T13:32:38.000Z t:org_id=Q260 t:building_name="FAR ROCKAWAY HS - Q" t:bldg_i_d_=Q465 t:district=78 t:organization_name="FREDERICK DOUGLASS ACADEMY VI HS-Q" m:org_adjusted_capacity_historical_=521 m:bldg_over_under_historical=-249 m:bldg_adjusted_capacity_historical_=1881 m:bldg_utilization_target_=88 m:no_of_spec_rooms_used=6 m:bldg_over_under_target_=-220 m:bldg_enroll=1632 m:org_utilization_historical_=87 m:org_over_under_target_=-220 m:org_enroll=451 m:bldg_capacity_target_=1852 m:org_over_under_historical_=-70 m:org_adjusted_capacity_target_=1852 m:bldg_utilization_historical_=87 m:org_utilization_target_=88
```

## Meta Commands

```ls
metric m:bldg_enroll p:integer l:"Bldg Enroll" d:"Enrollment for the building" t:dataTypeName=number

metric m:bldg_adjusted_capacity_historical_ p:integer l:"Bldg Adjusted Capacity (Historical)" d:"Total historical building capacity" t:dataTypeName=number

metric m:bldg_over_under_historical p:integer l:"Bldg Over/Under Historical" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:bldg_utilization_historical_ p:integer l:"Bldg Utilization (Historical)" d:"Percentage of Historical Capacity used" t:dataTypeName=number

metric m:bldg_capacity_target_ p:integer l:"Bldg Capacity (Target)" d:"Target Building Capacity" t:dataTypeName=number

metric m:bldg_over_under_target_ p:integer l:"Bldg Over/Under (Target)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:bldg_utilization_target_ p:integer l:"Bldg Utilization (Target)" d:"Percentage of Target Building Capacity used" t:dataTypeName=number

metric m:org_enroll p:integer l:"Org Enroll" d:"School Enrollment" t:dataTypeName=number

metric m:org_adjusted_capacity_historical_ p:integer l:"Org Adjusted Capacity (Historical)" d:"Historical organizational capacity" t:dataTypeName=number

metric m:org_over_under_historical_ p:integer l:"Org Over/Under (Historical)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_historical_ p:integer l:"Org Utilization (Historical)" d:"Percentage of Historical Organizational Capacity used" t:dataTypeName=number

metric m:org_adjusted_capacity_target_ p:integer l:"Org Adjusted Capacity (Target)" d:"Target Organizational capacity" t:dataTypeName=number

metric m:org_over_under_target_ p:integer l:"Org Over Under (Target)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_target_ p:integer l:"Org Utilization (Target)" d:"Percentage of Target Organization Capacity used" t:dataTypeName=number

metric m:no_of_spec_rooms_used p:integer l:"No. of Spec rooms used" d:"No. of Specialty Rooms Used" t:dataTypeName=number

entity e:3mim-bd27 l:"Enrollment Capacity and Utilization Reports Regular HS" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/3mim-bd27

property e:3mim-bd27 t:meta.view v:id=3mim-bd27 v:category=Education v:averageRating=0 v:name="Enrollment Capacity and Utilization Reports Regular HS" v:attribution="School Construction Authority (SCA)"

property e:3mim-bd27 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3mim-bd27 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | bldg_i_d_ | building_name        | bldg_enroll | bldg_adjusted_capacity_historical_ | bldg_over_under_historical | bldg_utilization_historical_ | bldg_capacity_target_ | bldg_over_under_target_ | bldg_utilization_target_ | org_id | organization_name                  | org_enroll | org_adjusted_capacity_historical_ | org_over_under_historical_ | org_utilization_historical_ | org_adjusted_capacity_target_ | org_over_under_target_ | org_utilization_target_ | no_of_spec_rooms_used | inclusionary | 
| =========== | ======== | ========= | ==================== | =========== | ================================== | ========================== | ============================ | ===================== | ======================= | ======================== | ====== | ================================== | ========== | ================================= | ========================== | =========================== | ============================= | ====================== | ======================= | ===================== | ============ | 
| 1384522358  | 78       | Q410      | BEACH CHANNEL HS - Q | 1699        | 3324                               | -1625                      | 51                           | 3054                  | -1355                   | 56                       | Q410   | BEACH CHANNEL HS - QUEENS          | 397        | 1195                              | -798                       | 33                          | 3054                          | -1355                  | 56                      | 24                    |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | M984   | LYFE                               |            |                                   | 0                          |                             | 1852                          | -220                   | 88                      | 0                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | Q260   | FREDERICK DOUGLASS ACADEMY VI HS-Q | 451        | 521                               | -70                        | 87                          | 1852                          | -220                   | 88                      | 6                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | Q282   | M.S. 282 - QUEENS                  | 268        | 326                               | -58                        | 82                          | 1852                          | -220                   | 88                      | 0                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | Q302   | QNS HS FOR INF. RESEARCH & TECH.-Q | 313        | 429                               | -116                       | 73                          | 1852                          | -220                   | 88                      | 4                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | Q309   | ACAD. OF MEDICAL TECHNOLOGY - Q    | 600        | 605                               | -5                         | 99                          | 1852                          | -220                   | 88                      | 3                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | QG13   | SCHOOL SAFETY - QUEENS             |            |                                   | 0                          |                             | 1852                          | -220                   | 88                      | 0                     |              | 
| 1384522358  | 78       | Q465      | FAR ROCKAWAY HS - Q  | 1632        | 1881                               | -249                       | 87                           | 1852                  | -220                    | 88                       | QG16   | NORTH SHORE CLINIC - QUEENS        |            |                                   | 0                          |                             | 1852                          | -220                   | 88                      | 0                     |              | 
| 1384522358  | 78       | Q475      | RICHMOND HILL HS - Q | 2336        | 2281                               | 55                         | 102                          | 2165                  | 171                     | 108                      | Q475   | RICHMOND HILL HS - QUEENS          | 2336       | 2281                              | 55                         | 102                         | 2165                          | 171                    | 108                     | 26                    |              | 
| 1384522358  | 78       | Q475      | RICHMOND HILL HS - Q | 2336        | 2281                               | 55                         | 102                          | 2165                  | 171                     | 108                      | QG05   | UFT USE - QUEENS                   |            |                                   | 0                          |                             | 2165                          | 171                    | 108                     | 0                     |              | 
```