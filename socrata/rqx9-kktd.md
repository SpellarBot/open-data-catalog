# Enrollment Capacity and Utilization Reports Alternative HS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-alternative-hs-8aed7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rqx9-kktd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rqx9-kktd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rqx9-kktd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rqx9-kktd |
| Name | Enrollment Capacity and Utilization Reports Alternative HS |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2013-04-18T15:19:06Z |
| Publication Date | 2013-11-15T21:33:18Z |

## Description

This dataset is no longer maintained. Updated enrollment capacity and utilization data can be found at https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/hq56-zhrp
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Histor/q9xk-w9iv
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/gkd7-3vk7
https://data.cityofnewyork.us/Education/Enrollment-Capacity-And-Utilization-Reports-Target/8b9a-pywy. 

Enrollment, capacity and utilization data for every alternative high school building and schools in those buildings.

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
| Yes      | numeric metric | bldg_over_under_historical_        | Bldg Over/Under (Historical)        | number    | number      |
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
series e:rqx9-kktd d:2013-11-15T13:33:08.000Z t:org_id=X490 t:building_name="PHOENIX ACADEMY HS (UPSTATE)" t:bldg_i_d_=X458 t:district=78 t:organization_name="PHOENIX ACADEMY HS - UPSTATE" m:bldg_over_under_historical_=-200 m:org_adjusted_capacity_historical_=322 m:bldg_adjusted_capacity_historical_=322 m:bldg_utilization_target_=38 m:no_of_spec_rooms_used=3 m:bldg_over_under_target_=-196 m:bldg_enroll=122 m:org_utilization_historical_=38 m:org_over_under_target_=-196 m:org_enroll=122 m:bldg_capacity_target_=318 m:org_over_under_historical_=-200 m:org_adjusted_capacity_target_=318 m:bldg_utilization_historical_=38 m:org_utilization_target_=38

series e:rqx9-kktd d:2013-11-15T13:33:08.000Z t:org_id=M458 t:building_name="FORSYTH HS (AUXSVC-OLD 91) - M" t:bldg_i_d_=M510 t:district=78 t:organization_name="SATELLITE AT FORSYTHE" m:bldg_over_under_historical_=-76 m:org_adjusted_capacity_historical_=245 m:bldg_adjusted_capacity_historical_=784 m:bldg_utilization_target_=87 m:no_of_spec_rooms_used=2 m:bldg_over_under_target_=-107 m:bldg_enroll=708 m:org_utilization_historical_=92 m:org_over_under_target_=-38 m:org_enroll=225 m:bldg_capacity_target_=815 m:org_over_under_historical_=-20 m:org_adjusted_capacity_target_=263 m:bldg_utilization_historical_=90 m:org_utilization_target_=86

series e:rqx9-kktd d:2013-11-15T13:33:08.000Z t:org_id=M650 t:building_name="FORSYTH HS (AUXSVC-OLD 91) - M" t:bldg_i_d_=M510 t:district=78 t:organization_name="CASCADES CTR FOR TCHING & LNG - M" m:bldg_over_under_historical_=-76 m:org_adjusted_capacity_historical_=295 m:bldg_adjusted_capacity_historical_=784 m:bldg_utilization_target_=87 m:no_of_spec_rooms_used=5 m:bldg_over_under_target_=-107 m:bldg_enroll=708 m:org_utilization_historical_=77 m:org_over_under_target_=-76 m:org_enroll=228 m:bldg_capacity_target_=815 m:org_over_under_historical_=-67 m:org_adjusted_capacity_target_=304 m:bldg_utilization_historical_=90 m:org_utilization_target_=75
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

metric m:org_adjusted_capacity_historical_ p:integer l:"Org Adjusted Capacity (Historical)" d:"Historical organizational capacity" t:dataTypeName=number

metric m:org_over_under_historical_ p:integer l:"Org Over/Under (Historical)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_historical_ p:integer l:"Org Utilization (Historical)" d:"Percentage of Historical Organizational Capacity used" t:dataTypeName=number

metric m:org_adjusted_capacity_target_ p:integer l:"Org Adjusted Capacity (Target)" d:"Target Organizational capacity" t:dataTypeName=number

metric m:org_over_under_target_ p:integer l:"Org Over Under (Target)" d:"Enrollment minus capacity" t:dataTypeName=number

metric m:org_utilization_target_ p:integer l:"Org Utilization (Target)" d:"Percentage of Target Organization Capacity used" t:dataTypeName=number

metric m:no_of_spec_rooms_used p:integer l:"No. of Spec rooms used" d:"No. of Specialty Rooms Used" t:dataTypeName=number

entity e:rqx9-kktd l:"Enrollment Capacity and Utilization Reports Alternative HS" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/rqx9-kktd

property e:rqx9-kktd t:meta.view v:id=rqx9-kktd v:category=Education v:attributionLink=http://www.nycsca.org/Community/CapitalPlanManagementReportsData/Enrollment/2011-2012_Classic.pdf v:averageRating=0 v:name="Enrollment Capacity and Utilization Reports Alternative HS" v:attribution="School Construction Authority (SCA)"

property e:rqx9-kktd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rqx9-kktd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | bldg_i_d_ | building_name                  | bldg_enroll | bldg_adjusted_capacity_historical_ | bldg_over_under_historical_ | bldg_utilization_historical_ | bldg_capacity_target_ | bldg_over_under_target_ | bldg_utilization_target_ | org_id | organization_name                  | org_enroll | org_adjusted_capacity_historical_ | org_over_under_historical_ | org_utilization_historical_ | org_adjusted_capacity_target_ | org_over_under_target_ | org_utilization_target_ | no_of_spec_rooms_used | inclusionary | 
| =========== | ======== | ========= | ============================== | =========== | ================================== | =========================== | ============================ | ===================== | ======================= | ======================== | ====== | ================================== | ========== | ================================= | ========================== | =========================== | ============================= | ====================== | ======================= | ===================== | ============ | 
| 1384522388  | 78       | X458      | PHOENIX ACADEMY HS (UPSTATE)   | 122         | 322                                | -200                        | 38                           | 318                   | -196                    | 38                       | X490   | PHOENIX ACADEMY HS - UPSTATE       | 122        | 322                               | -200                       | 38                          | 318                           | -196                   | 38                      | 3                     |              | 
| 1384522388  | 78       | M510      | FORSYTH HS (AUXSVC-OLD 91) - M | 708         | 784                                | -76                         | 90                           | 815                   | -107                    | 87                       | M458   | SATELLITE AT FORSYTHE              | 225        | 245                               | -20                        | 92                          | 263                           | -38                    | 86                      | 2                     |              | 
| 1384522388  | 78       | M510      | FORSYTH HS (AUXSVC-OLD 91) - M | 708         | 784                                | -76                         | 90                           | 815                   | -107                    | 87                       | M650   | CASCADES CTR FOR TCHING & LNG - M  | 228        | 295                               | -67                        | 77                          | 304                           | -76                    | 75                      | 5                     |              | 
| 1384522388  | 78       | M510      | FORSYTH HS (AUXSVC-OLD 91) - M | 708         | 784                                | -76                         | 90                           | 815                   | -107                    | 87                       | M984   | LYFE                               |            |                                   | 0                          |                             |                               | 0                      |                         | 0                     |              | 
| 1384522388  | 78       | M510      | FORSYTH HS (AUXSVC-OLD 91) - M | 708         | 784                                | -76                         | 90                           | 815                   | -107                    | 87                       | MG04   | ADULT BASIC EDUCATION - MANHATTAN  |            |                                   | 0                          |                             |                               | 0                      |                         | 0                     |              | 
| 1384522388  | 78       | M510      | FORSYTH HS (AUXSVC-OLD 91) - M | 708         | 784                                | -76                         | 90                           | 815                   | -107                    | 87                       | Q950   | GED PLUS - CITYWIDE                | 255        | 244                               | 11                         | 105                         | 248                           | 7                      | 103                     | 0                     |              | 
| 1384522388  | 78       | M451      | LIBERTY HS - MANHATTAN         | 383         | 288                                | 95                          | 133                          | 280                   | 103                     | 137                      | M550   | LIBERTY HS ACADEMY FOR NEWCOMERS-M | 383        | 288                               | 95                         | 133                         | 280                           | 103                    | 137                     | 4                     |              | 
| 1384522388  | 78       | M641      | CITY AS SCHOOL (OLD 95) - M    | 829         | 573                                | 256                         | 145                          | 569                   | 260                     | 146                      | M544   | INDEPENDENCE HS - MANHATTAN        | 100        | 149                               | -49                        | 67                          | 152                           | -52                    | 66                      | 4                     |              | 
| 1384522388  | 78       | M641      | CITY AS SCHOOL (OLD 95) - M    | 829         | 573                                | 256                         | 145                          | 569                   | 260                     | 146                      | M560   | CITY-AS-SCHOOL - MANHATTAN         | 540        | 220                               | 320                        | 245                         | 213                           | 327                    | 254                     | 3                     |              | 
| 1384522388  | 78       | M641      | CITY AS SCHOOL (OLD 95) - M    | 829         | 573                                | 256                         | 145                          | 569                   | 260                     | 146                      | M721   | M721 SPED - MANHATTAN              | 189        | 204                               | -15                        | 93                          | 204                           | -15                    | 93                      | 0                     |              | 
```