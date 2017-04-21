# Enrollment Capacity and Utilization Reports District 1-32

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-district-1-32-8e520) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/my4g-bvvs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/my4g-bvvs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/my4g-bvvs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | my4g-bvvs |
| Name | Enrollment Capacity and Utilization Reports District 1-32 |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2013-04-18T15:19:14Z |
| Publication Date | 2013-11-15T21:30:46Z |

## Description

This dataset is no longer maintained. Updated enrollment capacity and utilization data can be found at https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/hq56-zhrp
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/q9xk-w9iv
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/gkd7-3vk7
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/8b9a-pywy

Enrollment, capacity and utilization data for every elementary and middle school building and schools in those buildings.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                           | meta_data | meta_data   |
| Yes      | series tag     | district                             | District                             | text      | number      |
| Yes      | series tag     | bldg_level                           | Bldg Level                           | text      | text        |
| Yes      | series tag     | bldg_i_d_                            | Bldg I.D.                            | text      | text        |
| Yes      | series tag     | building_name                        | Building Name                        | text      | text        |
| Yes      | numeric metric | bldg_enroll                          | Bldg Enroll                          | number    | number      |
| Yes      | numeric metric | bldg_adjusted_capacity_historical_   | Bldg Adjusted Capacity (Historical)  | number    | number      |
| Yes      | numeric metric | bldg_over_under_historical_          | Bldg Over/Under (Historical)         | number    | number      |
| Yes      | numeric metric | bldg_utilization_historical_         | Bldg Utilization (Historical)        | number    | number      |
| Yes      | numeric metric | bldg_capacity_target_                | Bldg Capacity (Target)               | number    | number      |
| Yes      | numeric metric | bldg_over_under_target_              | Bldg Over/Under (Target)             | number    | number      |
| Yes      | numeric metric | bldg_utilization_target_             | Bldg Utilization (Target)            | number    | number      |
| Yes      | series tag     | org_id                               | Org ID                               | text      | text        |
| Yes      | series tag     | organization_name                    | Organization Name                    | text      | text        |
| Yes      | numeric metric | org_enroll                           | Org Enroll                           | number    | number      |
| Yes      | numeric metric | org_adjusted_capacity_historical_    | Org Adjusted Capacity (Historical)   | number    | number      |
| Yes      | numeric metric | org_over_under_historical_           | Org Over/Under (Historical)          | number    | number      |
| Yes      | numeric metric | org_utilization_historical_          | Org Utilization (Historical)         | number    | number      |
| Yes      | numeric metric | org_adjusted_capacity_target_        | Org Adjusted Capacity (Target)       | number    | number      |
| Yes      | numeric metric | org_over_under_target_               | Org Over Under (Target)              | number    | number      |
| Yes      | numeric metric | org_utilization_target_              | Org Utilization (Target)             | number    | number      |
| Yes      | numeric metric | no_of_actual_cluster_rms_used        | No. of Actual Cluster Rms Used       | number    | number      |
| Yes      | numeric metric | no_of_historical_method_cluster_rms_ | No. of Historical Method Cluster Rms | number    | number      |
| Yes      | numeric metric | no_of_target_method_cluster_rms      | No. of Target Method Cluster Rms     | number    | number      |
| Yes      | numeric metric | pre_k_cap                            | Pre K Cap                            | number    | number      |
| Yes      | numeric metric | no_of_special_rms_used               | No. of Special Rms Used              | number    | number      |
| Yes      | series tag     | inclusionary                         | Inclusionary                         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:my4g-bvvs d:2013-11-15T13:30:31.000Z t:org_id=M298 t:building_name="I.S. 131 - MANHATTAN" t:bldg_i_d_=M131 t:bldg_level=MIDDLE t:district=2 t:organization_name="PACE HIGH SCHOOL - MANHATTAN" m:no_of_target_method_cluster_rms=0 m:pre_k_cap=0 m:no_of_actual_cluster_rms_used=0 m:org_adjusted_capacity_historical_=444 m:bldg_over_under_historical_=-359 m:bldg_adjusted_capacity_historical_=1490 m:bldg_utilization_target_=76 m:no_of_historical_method_cluster_rms_=0 m:bldg_over_under_target_=-356 m:bldg_enroll=1131 m:org_utilization_historical_=96 m:org_over_under_target_=-59 m:org_enroll=426 m:bldg_capacity_target_=1487 m:org_over_under_historical_=-18 m:no_of_special_rms_used=3 m:org_adjusted_capacity_target_=485 m:bldg_utilization_historical_=76 m:org_utilization_target_=88

series e:my4g-bvvs d:2013-11-15T13:30:32.000Z t:org_id=M394 t:building_name="I.S. 131 - MANHATTAN" t:bldg_i_d_=M131 t:bldg_level=MIDDLE t:district=2 t:organization_name="EMMA LAZARUS HIGH SCHOOL" m:no_of_target_method_cluster_rms=0 m:pre_k_cap=0 m:no_of_actual_cluster_rms_used=0 m:org_adjusted_capacity_historical_=370 m:bldg_over_under_historical_=-359 m:bldg_adjusted_capacity_historical_=1490 m:bldg_utilization_target_=76 m:no_of_historical_method_cluster_rms_=0 m:bldg_over_under_target_=-356 m:bldg_enroll=1131 m:org_utilization_historical_=66 m:org_over_under_target_=-96 m:org_enroll=245 m:bldg_capacity_target_=1487 m:org_over_under_historical_=-125 m:no_of_special_rms_used=6 m:org_adjusted_capacity_target_=341 m:bldg_utilization_historical_=76 m:org_utilization_target_=72

series e:my4g-bvvs d:2013-11-15T13:30:32.000Z t:org_id=MG18 t:building_name="I.S. 131 - MANHATTAN" t:bldg_i_d_=M131 t:bldg_level=MIDDLE t:district=2 t:organization_name="CHINATOWN YMCA - MANHATTAN" m:pre_k_cap=0 m:no_of_target_method_cluster_rms=0 m:bldg_over_under_historical_=-359 m:no_of_actual_cluster_rms_used=0 m:bldg_adjusted_capacity_historical_=1490 m:bldg_utilization_target_=76 m:no_of_historical_method_cluster_rms_=0 m:bldg_over_under_target_=-356 m:bldg_enroll=1131 m:org_over_under_target_=0 m:bldg_capacity_target_=1487 m:org_over_under_historical_=0 m:no_of_special_rms_used=0 m:bldg_utilization_historical_=76
```

## Meta Commands

```ls
metric m:bldg_enroll p:integer l:"Bldg Enroll" d:"Enrollment for the building" t:dataTypeName=number

metric m:bldg_adjusted_capacity_historical_ p:integer l:"Bldg Adjusted Capacity (Historical)" d:"Total historical building capacity" t:dataTypeName=number

metric m:bldg_over_under_historical_ p:integer l:"Bldg Over/Under (Historical)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:bldg_utilization_historical_ p:integer l:"Bldg Utilization (Historical)" d:"Percentage of Historical Capacity used" t:dataTypeName=number

metric m:bldg_capacity_target_ p:integer l:"Bldg Capacity (Target)" d:"Target Building Capacity" t:dataTypeName=number

metric m:bldg_over_under_target_ p:integer l:"Bldg Over/Under (Target)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:bldg_utilization_target_ p:integer l:"Bldg Utilization (Target)" d:"Percentage of Target Building Capacity used" t:dataTypeName=number

metric m:org_enroll p:integer l:"Org Enroll" d:"School Enrollment" t:dataTypeName=number

metric m:org_adjusted_capacity_historical_ p:integer l:"Org Adjusted Capacity (Historical)" d:"Historical organization capacity" t:dataTypeName=number

metric m:org_over_under_historical_ p:integer l:"Org Over/Under (Historical)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_historical_ p:integer l:"Org Utilization (Historical)" d:"Percentage of Historical Organization Capacity used" t:dataTypeName=number

metric m:org_adjusted_capacity_target_ p:integer l:"Org Adjusted Capacity (Target)" d:"Target organizational capacity" t:dataTypeName=number

metric m:org_over_under_target_ p:integer l:"Org Over Under (Target)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_target_ p:integer l:"Org Utilization (Target)" d:"Percentage of Target Organization Capacity used" t:dataTypeName=number

metric m:no_of_actual_cluster_rms_used p:integer l:"No. of Actual Cluster Rms Used" d:"Number of cluster rooms being used" t:dataTypeName=number

metric m:no_of_historical_method_cluster_rms_ p:integer l:"No. of Historical Method Cluster Rms" d:"Number of historical method cluster rooms" t:dataTypeName=number

metric m:no_of_target_method_cluster_rms p:integer l:"No. of Target Method Cluster Rms" d:"Number of target method cluster rooms" t:dataTypeName=number

metric m:pre_k_cap p:integer l:"Pre K Cap" d:"Pre-K Capacity" t:dataTypeName=number

metric m:no_of_special_rms_used p:integer l:"No. of Special Rms Used" d:"Number of Special Rooms being used" t:dataTypeName=number

entity e:my4g-bvvs l:"Enrollment Capacity and Utilization Reports District 1-32" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/my4g-bvvs

property e:my4g-bvvs t:meta.view v:id=my4g-bvvs v:category=Education v:averageRating=0 v:name="Enrollment Capacity and Utilization Reports District 1-32" v:attribution="School Construction Authority (SCA)"

property e:my4g-bvvs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:my4g-bvvs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | bldg_level | bldg_i_d_ | building_name                      | bldg_enroll | bldg_adjusted_capacity_historical_ | bldg_over_under_historical_ | bldg_utilization_historical_ | bldg_capacity_target_ | bldg_over_under_target_ | bldg_utilization_target_ | org_id | organization_name                | org_enroll | org_adjusted_capacity_historical_ | org_over_under_historical_ | org_utilization_historical_ | org_adjusted_capacity_target_ | org_over_under_target_ | org_utilization_target_ | no_of_actual_cluster_rms_used | no_of_historical_method_cluster_rms_ | no_of_target_method_cluster_rms | pre_k_cap | no_of_special_rms_used | inclusionary | 
| =========== | ======== | ========== | ========= | ================================== | =========== | ================================== | =========================== | ============================ | ===================== | ======================= | ======================== | ====== | ================================ | ========== | ================================= | ========================== | =========================== | ============================= | ====================== | ======================= | ============================= | ==================================== | =============================== | ========= | ====================== | ============ | 
| 1384522231  | 2        | MIDDLE     | M131      | I.S. 131 - MANHATTAN               | 1131        | 1490                               | -359                        | 76                           | 1487                  | -356                    | 76                       | M298   | PACE HIGH SCHOOL - MANHATTAN     | 426        | 444                               | -18                        | 96                          | 485                           | -59                    | 88                      | 0                             | 0                                    | 0                               | 0         | 3                      |              | 
| 1384522232  | 2        | MIDDLE     | M131      | I.S. 131 - MANHATTAN               | 1131        | 1490                               | -359                        | 76                           | 1487                  | -356                    | 76                       | M394   | EMMA LAZARUS HIGH SCHOOL         | 245        | 370                               | -125                       | 66                          | 341                           | -96                    | 72                      | 0                             | 0                                    | 0                               | 0         | 6                      |              | 
| 1384522232  | 2        | MIDDLE     | M131      | I.S. 131 - MANHATTAN               | 1131        | 1490                               | -359                        | 76                           | 1487                  | -356                    | 76                       | MG18   | CHINATOWN YMCA - MANHATTAN       |            |                                   | 0                          |                             |                               | 0                      |                         | 0                             | 0                                    | 0                               | 0         | 0                      |              | 
| 1384522232  | 2        | MIDDLE     | M167      | I.S. 167 - MANHATTAN               | 1216        | 1652                               | -436                        | 74                           | 1472                  | -256                    | 83                       | M167   | I.S. 167 - MANHATTAN             | 1216       | 1652                              | -436                       | 74                          | 1472                          | -256                   | 83                      | 0                             | 0                                    | 0                               | 0         | 11                     |              | 
| 1384522232  | 2        | MIDDLE     | M660      | SCHL OF THE FUTURE (OLD BACON) - M | 722         | 866                                | -144                        | 83                           | 803                   | -81                     | 90                       | M138   | M138 SPED - MANHATTAN            | 15         | 0                                 | 15                         | 0                           | 0                             | 15                     | 0                       | 0                             | 0                                    | 0                               | 0         | 0                      | All          | 
| 1384522232  | 2        | MIDDLE     | M660      | SCHL OF THE FUTURE (OLD BACON) - M | 722         | 866                                | -144                        | 83                           | 803                   | -81                     | 90                       | M413   | SCHOOL OF THE FUTURE - MANHATTAN | 707        | 866                               | -159                       | 82                          | 803                           | -96                    | 88                      | 0                             | 0                                    | 0                               | 0         | 7                      |              | 
| 1384522232  | 2        | MIDDLE     | M933      | I.S. 260 - MANHATTAN               | 249         | 500                                | -251                        | 50                           | 460                   | -211                    | 54                       | M260   | I.S. 260 - MANHATTAN             | 249        | 500                               | -251                       | 50                          | 460                           | -211                   | 54                      | 0                             | 0                                    | 0                               | 0         | 2                      |              | 
| 1384522232  | 2        | HS         | M824      | MILLENNIUM HS - MANHATTAN          | 665         | 582                                | 83                          | 114                          | 525                   | 140                     | 127                      | M226   | M226 SPED - MANHATTAN            | 7          | 0                                 | 7                          | 0                           | 0                             | 7                      | 0                       | 0                             | 0                                    | 0                               | 0         | 0                      | All          | 
| 1384522232  | 2        | HS         | M824      | MILLENNIUM HS - MANHATTAN          | 665         | 582                                | 83                          | 114                          | 525                   | 140                     | 127                      | M418   | MILLENNIUM HS - MANHATTAN        | 658        | 582                               | 76                         | 113                         | 525                           | 133                    | 125                     | 0                             | 0                                    | 0                               | 0         | 1                      |              | 
| 1384522232  | 2        | HS         | M824      | MILLENNIUM HS - MANHATTAN          | 665         | 582                                | 83                          | 114                          | 525                   | 140                     | 127                      | MG18   | Y.M.C.A. - MANHATTAN             |            |                                   | 0                          |                             |                               | 0                      |                         | 0                             | 0                                    | 0                               | 0         | 0                      |              | 
```