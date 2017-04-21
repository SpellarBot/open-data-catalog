# Enrollment Capacity And Utilization Reports - Target by Building

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-target-by-building) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gkd7-3vk7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gkd7-3vk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gkd7-3vk7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gkd7-3vk7 |
| Name | Enrollment Capacity And Utilization Reports - Target by Building |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2015-05-11T20:51:59Z |
| Publication Date | 2015-05-11T20:53:39Z |

## Description

Enrollment, target capacity and utilization data for every building and schools in those buildings, by building

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                 | Data Type | Render Type |
| ======== | ============== | =============================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                           | meta_data | meta_data   |
| Yes      | numeric metric | geo_dist                        | Geo Dist                             | number    | number      |
| Yes      | series tag     | bldg_id                         | Bldg ID                              | text      | text        |
| Yes      | series tag     | bldg_name                       | Bldg Name                            | text      | text        |
| Yes      | numeric metric | bldg_enroll                     | Bldg Enroll                          | number    | number      |
| Yes      | numeric metric | target_bldg_cap                 | Target Bldg Cap                      | number    | number      |
| Yes      | numeric metric | target_bldg_util                | Target Bldg Util                     | number    | number      |
| Yes      | series tag     | org_id                          | Org ID                               | text      | text        |
| Yes      | series tag     | incl_class                      | Incl. Class                          | text      | text        |
| Yes      | series tag     | organization_name               | Organization Name                    | text      | text        |
| Yes      | numeric metric | org_enroll                      | Org Enroll                           | number    | number      |
| Yes      | numeric metric | org_target_cap                  | Org Target Cap                       | number    | number      |
| Yes      | numeric metric | org_target_util                 | Org Target Util                      | number    | number      |
| Yes      | numeric metric | prek_cap                        | PreK Cap +                           | number    | number      |
| Yes      | numeric metric | no_of_cluster_spec_rms_reported | No. of Cluster / Spec Rms Reported + | number    | number      |
| Yes      | numeric metric | no_of_cluster_rms_needed        | No. of Cluster Rms Needed +          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gkd7-3vk7 d:2015-05-11T13:52:06.000Z t:org_id=M015 t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="P.S. 15 - M" m:bldg_enroll=254 m:prek_cap=36 m:org_target_cap=315 m:no_of_cluster_rms_needed=2 m:geo_dist=1 m:org_enroll=190 m:org_target_util=60 m:target_bldg_util=61 m:no_of_cluster_spec_rms_reported=4 m:target_bldg_cap=416

series e:gkd7-3vk7 d:2015-05-11T13:52:06.000Z t:org_id=M094 t:incl_class=* t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="M094 SPED - M" m:org_target_cap=101 m:geo_dist=1 m:org_enroll=64 m:org_target_util=63

series e:gkd7-3vk7 d:2015-05-11T13:52:06.000Z t:org_id=MCBO t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="EDUCATION ALLIANCE - M" m:geo_dist=1
```

## Meta Commands

```ls
metric m:geo_dist p:integer l:"Geo Dist" t:dataTypeName=number

metric m:bldg_enroll p:integer l:"Bldg Enroll" t:dataTypeName=number

metric m:target_bldg_cap p:integer l:"Target Bldg Cap" t:dataTypeName=number

metric m:target_bldg_util p:integer l:"Target Bldg Util" t:dataTypeName=number

metric m:org_enroll p:integer l:"Org Enroll" t:dataTypeName=number

metric m:org_target_cap p:integer l:"Org Target Cap" t:dataTypeName=number

metric m:org_target_util p:integer l:"Org Target Util" t:dataTypeName=number

metric m:prek_cap p:integer l:"PreK Cap +" t:dataTypeName=number

metric m:no_of_cluster_spec_rms_reported p:integer l:"No. of Cluster / Spec Rms Reported +" t:dataTypeName=number

metric m:no_of_cluster_rms_needed p:integer l:"No. of Cluster Rms Needed +" t:dataTypeName=number

entity e:gkd7-3vk7 l:"Enrollment Capacity And Utilization Reports - Target by Building" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/gkd7-3vk7

property e:gkd7-3vk7 t:meta.view v:id=gkd7-3vk7 v:category=Education v:averageRating=0 v:name="Enrollment Capacity And Utilization Reports - Target by Building" v:attribution="School Construction Authority (SCA)"

property e:gkd7-3vk7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gkd7-3vk7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | geo_dist | bldg_id | bldg_name             | bldg_enroll | target_bldg_cap | target_bldg_util | org_id | incl_class | organization_name               | org_enroll | org_target_cap | org_target_util | prek_cap | no_of_cluster_spec_rms_reported | no_of_cluster_rms_needed | 
| =========== | ======== | ======= | ===================== | =========== | =============== | ================ | ====== | ========== | =============================== | ========== | ============== | =============== | ======== | =============================== | ======================== | 
| 1431352326  | 1        | M015    | P.S. 15 - M           | 254         | 416             | 61               | M015   |            | P.S. 15 - M                     | 190        | 315            | 60              | 36       | 4                               | 2                        | 
| 1431352326  | 1        | M015    | P.S. 15 - M           |             |                 |                  | M094   | *          | M094 SPED - M                   | 64         | 101            | 63              |          |                                 |                          | 
| 1431352326  | 1        | M015    | P.S. 15 - M           |             |                 |                  | MCBO   |            | EDUCATION ALLIANCE - M          |            |                |                 |          |                                 |                          | 
| 1431352326  | 1        | M019    | P.S. 19 - M           | 443         | 687             | 64               | M019   |            | P.S. 19 - M                     | 285        | 395            | 72              | 36       | 2                               | 3                        | 
| 1431352326  | 1        | M019    | P.S. 19 - M           |             |                 |                  | M301   |            | I.S. 301 - M                    | 158        | 292            | 54              |          | 0                               | 0                        | 
| 1431352326  | 1        | M020    | P.S. 20 - M           | 631         | 826             | 76               | M020   |            | P.S. 20 - M                     | 631        | 826            | 76              | 53       | 9                               | 3                        | 
| 1431352326  | 1        | M020    | P.S. 20 - M           |             |                 |                  | MCBO   |            | ED ALLIANCE/DISTRICT 1 OFFICE-M |            |                |                 |          |                                 |                          | 
| 1431352326  | 1        | M020    | P.S. 20 - M           |             |                 |                  | MSFS   |            | FOOD SERVICES - M               |            |                |                 |          |                                 |                          | 
| 1431352326  | 1        | M022    | N.E.S.T (OLD J22) - M | 1725        | 1610            | 107              | M539   |            | NEW EXPLORATIONS - M            | 1725       | 1610           | 107             | 0        | 11                              | 5                        | 
| 1431352326  | 1        | M025    | J.H.S. 25 - M         | 1196        | 1664            | 72               | M378   |            | I.S. 378 - M                    | 244        | 343            | 71              |          | 0                               | 0                        | 
```