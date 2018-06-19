# Enrollment Capacity And Utilization Reports - Target by Organization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-target-by-organization) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8b9a-pywy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8b9a-pywy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8b9a-pywy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8b9a-pywy |
| Name | Enrollment Capacity And Utilization Reports - Target by Organization |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2015-05-11T20:54:25Z |
| Publication Date | 2015-05-11T20:55:56Z |

## Description

Enrollment, target capacity and utilization data for every building and schools in those buildings, by school

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                               | Data Type | Render Type |
| ======== | ============== | =============================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                         | meta_data | meta_data   |
| Yes      | numeric metric | geo_dist                        | Geo Dist                           | number    | number      |
| Yes      | series tag     | org_id                          | Org ID                             | text      | text        |
| Yes      | series tag     | organization_name               | Organization Name                  | text      | text        |
| Yes      | series tag     | bldg_id                         | Bldg ID                            | text      | text        |
| Yes      | series tag     | incl_class                      | Incl. Class                        | text      | text        |
| Yes      | series tag     | building_name                   | Building Name                      | text      | text        |
| Yes      | numeric metric | enroll                          | Enroll                             | number    | number      |
| Yes      | numeric metric | target_capacity                 | Target Capacity                    | number    | number      |
| Yes      | numeric metric | target_utilization              | Target Utilization                 | number    | number      |
| Yes      | numeric metric | prek_cap                        | PreK Cap                           | number    | number      |
| Yes      | numeric metric | no_of_cluster_spec_rms_reported | No. of Cluster / Spec Rms Reported | number    | number      |
| Yes      | numeric metric | no_of_cluster_rms_needed        | No. of Cluster Rms Needed          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8b9a-pywy d:2015-05-11T13:54:31.000Z t:org_id=M015 t:building_name="P.S. 15 - M" t:bldg_id=M015 t:organization_name="P.S. 15 - M" m:prek_cap=36 m:target_capacity=315 m:no_of_cluster_rms_needed=2 m:geo_dist=1 m:no_of_cluster_spec_rms_reported=4 m:target_utilization=60 m:enroll=190

series e:8b9a-pywy d:2015-05-11T13:54:31.000Z t:org_id=M019 t:building_name="P.S. 19 - M" t:bldg_id=M019 t:organization_name="P.S. 19 - M" m:prek_cap=36 m:target_capacity=395 m:no_of_cluster_rms_needed=3 m:geo_dist=1 m:no_of_cluster_spec_rms_reported=2 m:target_utilization=72 m:enroll=285

series e:8b9a-pywy d:2015-05-11T13:54:31.000Z t:org_id=M020 t:building_name="P.S. 20 - M" t:bldg_id=M020 t:organization_name="P.S. 20 - M" m:prek_cap=53 m:target_capacity=826 m:no_of_cluster_rms_needed=3 m:geo_dist=1 m:no_of_cluster_spec_rms_reported=9 m:target_utilization=76 m:enroll=631
```

## Meta Commands

```ls
metric m:geo_dist p:integer l:"Geo Dist" t:dataTypeName=number

metric m:enroll p:integer l:Enroll t:dataTypeName=number

metric m:target_capacity p:integer l:"Target Capacity" t:dataTypeName=number

metric m:target_utilization p:integer l:"Target Utilization" t:dataTypeName=number

metric m:prek_cap p:integer l:"PreK Cap" t:dataTypeName=number

metric m:no_of_cluster_spec_rms_reported p:integer l:"No. of Cluster / Spec Rms Reported" t:dataTypeName=number

metric m:no_of_cluster_rms_needed p:integer l:"No. of Cluster Rms Needed" t:dataTypeName=number

entity e:8b9a-pywy l:"Enrollment Capacity And Utilization Reports - Target by Organization" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/8b9a-pywy

property e:8b9a-pywy t:meta.view v:id=8b9a-pywy v:category=Education v:averageRating=0 v:name="Enrollment Capacity And Utilization Reports - Target by Organization" v:attribution="School Construction Authority (SCA)"

property e:8b9a-pywy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8b9a-pywy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | geo_dist | org_id | organization_name           | bldg_id | incl_class | building_name        | enroll | target_capacity | target_utilization | prek_cap | no_of_cluster_spec_rms_reported | no_of_cluster_rms_needed | 
| =========== | ======== | ====== | =========================== | ======= | ========== | ==================== | ====== | =============== | ================== | ======== | =============================== | ======================== | 
| 1431352471  | 1        | M015   | P.S. 15 - M                 | M015    |            | P.S. 15 - M          | 190    | 315             | 60                 | 36       | 4                               | 2                        | 
| 1431352471  | 1        | M019   | P.S. 19 - M                 | M019    |            | P.S. 19 - M          | 285    | 395             | 72                 | 36       | 2                               | 3                        | 
| 1431352471  | 1        | M020   | P.S. 20 - M                 | M020    |            | P.S. 20 - M          | 631    | 826             | 76                 | 53       | 9                               | 3                        | 
| 1431352471  | 1        | M034   | P.S. 34 - M                 | M034    |            | P.S. 34 - M          | 393    | 409             | 96                 | 18       | 0                               | 3                        | 
| 1431352471  | 1        | M063   | P.S. 63 - M                 | M063    |            | P.S. 63 - M          | 179    | 325             | 55                 | 18       | 4                               | 2                        | 
| 1431352471  | 1        | M064   | P.S. 64 - M                 | M064    |            | P.S. 64 (OLD 71) - M | 287    | 306             | 94                 | 36       | 2                               | 3                        | 
| 1431352471  | 1        | M080   | MANHATTAN CHARTER SCHOOL II | M056    |            | J.H.S. 56 - M        | 140    | 140             | 100                | 0        | 0                               | 1                        | 
| 1431352471  | 1        | M094   | M094 SPED - M               | M015    | *          | P.S. 15 - M          | 64     | 101             | 63                 | 0        |                                 | 0                        | 
| 1431352471  | 1        | M094   | M094 SPED - M               | M061    | *          | P.S. 61 - M          | 56     | 88              | 64                 |          |                                 |                          | 
| 1431352471  | 1        | M094   | M094 SPED - M               | M188    | *          | P.S. 188 - M         | 52     | 97              | 54                 |          |                                 |                          | 
```