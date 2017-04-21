# Enrollment Capacity And Utilization Reports - Historical by Organization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-historical-by-organization) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q9xk-w9iv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q9xk-w9iv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q9xk-w9iv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q9xk-w9iv |
| Name | Enrollment Capacity And Utilization Reports - Historical by Organization |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2015-05-11T20:46:16Z |
| Publication Date | 2015-05-11T20:50:13Z |

## Description

Enrollment, historical capacity and utilization data for every building and schools in those buildings, by school

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                 | Data Type | Render Type |
| ======== | ============== | =============================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                           | meta_data | meta_data   |
| Yes      | numeric metric | geo_dist                        | Geo Dist                             | number    | number      |
| Yes      | series tag     | org_id                          | Org ID                               | text      | text        |
| Yes      | series tag     | organization_name               | Organization Name                    | text      | text        |
| Yes      | series tag     | bldg_id                         | Bldg ID                              | text      | text        |
| Yes      | series tag     | incl_class                      | Incl. Class                          | text      | text        |
| Yes      | series tag     | building_name                   | Building Name                        | text      | text        |
| Yes      | numeric metric | enroll                          | Enroll                               | number    | number      |
| Yes      | numeric metric | historical_capacity             | Historical Capacity                  | number    | number      |
| Yes      | numeric metric | historical_utilization          | Historical Utilization               | number    | number      |
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
series e:q9xk-w9iv d:2015-05-11T13:46:22.000Z t:org_id=M015 t:building_name="P.S. 15 - M" t:bldg_id=M015 t:organization_name="P.S. 15 - M" m:historical_capacity=387 m:prek_cap=36 m:no_of_cluster_rms_needed=1 m:geo_dist=1 m:historical_utilization=49 m:no_of_cluster_spec_rms_reported=4 m:enroll=190

series e:q9xk-w9iv d:2015-05-11T13:46:22.000Z t:org_id=M019 t:building_name="P.S. 19 - M" t:bldg_id=M019 t:organization_name="P.S. 19 - M" m:historical_capacity=460 m:prek_cap=36 m:no_of_cluster_rms_needed=2 m:geo_dist=1 m:historical_utilization=62 m:no_of_cluster_spec_rms_reported=2 m:enroll=285

series e:q9xk-w9iv d:2015-05-11T13:46:22.000Z t:org_id=M020 t:building_name="P.S. 20 - M" t:bldg_id=M020 t:organization_name="P.S. 20 - M" m:historical_capacity=968 m:prek_cap=53 m:no_of_cluster_rms_needed=3 m:geo_dist=1 m:historical_utilization=65 m:no_of_cluster_spec_rms_reported=9 m:enroll=631
```

## Meta Commands

```ls
metric m:geo_dist p:integer l:"Geo Dist" t:dataTypeName=number

metric m:enroll p:integer l:Enroll t:dataTypeName=number

metric m:historical_capacity p:integer l:"Historical Capacity" t:dataTypeName=number

metric m:historical_utilization p:integer l:"Historical Utilization" t:dataTypeName=number

metric m:prek_cap p:integer l:"PreK Cap +" t:dataTypeName=number

metric m:no_of_cluster_spec_rms_reported p:integer l:"No. of Cluster / Spec Rms Reported +" t:dataTypeName=number

metric m:no_of_cluster_rms_needed p:integer l:"No. of Cluster Rms Needed +" t:dataTypeName=number

entity e:q9xk-w9iv l:"Enrollment Capacity And Utilization Reports - Historical by Organization" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/q9xk-w9iv

property e:q9xk-w9iv t:meta.view v:id=q9xk-w9iv v:category=Education v:averageRating=0 v:name="Enrollment Capacity And Utilization Reports - Historical by Organization" v:attribution="School Construction Authority (SCA)"

property e:q9xk-w9iv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q9xk-w9iv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | geo_dist | org_id | organization_name           | bldg_id | incl_class | building_name        | enroll | historical_capacity | historical_utilization | prek_cap | no_of_cluster_spec_rms_reported | no_of_cluster_rms_needed | 
| =========== | ======== | ====== | =========================== | ======= | ========== | ==================== | ====== | =================== | ====================== | ======== | =============================== | ======================== | 
| 1431351982  | 1        | M015   | P.S. 15 - M                 | M015    |            | P.S. 15 - M          | 190    | 387                 | 49                     | 36       | 4                               | 1                        | 
| 1431351982  | 1        | M019   | P.S. 19 - M                 | M019    |            | P.S. 19 - M          | 285    | 460                 | 62                     | 36       | 2                               | 2                        | 
| 1431351982  | 1        | M020   | P.S. 20 - M                 | M020    |            | P.S. 20 - M          | 631    | 968                 | 65                     | 53       | 9                               | 3                        | 
| 1431351982  | 1        | M034   | P.S. 34 - M                 | M034    |            | P.S. 34 - M          | 393    | 520                 | 76                     | 18       | 0                               | 3                        | 
| 1431351982  | 1        | M063   | P.S. 63 - M                 | M063    |            | P.S. 63 - M          | 179    | 396                 | 45                     | 18       | 4                               | 1                        | 
| 1431351982  | 1        | M064   | P.S. 64 - M                 | M064    |            | P.S. 64 (OLD 71) - M | 287    | 356                 | 81                     | 36       | 2                               | 2                        | 
| 1431351982  | 1        | M080   | MANHATTAN CHARTER SCHOOL II | M056    |            | J.H.S. 56 - M        | 140    | 155                 | 90                     | 0        | 0                               | 1                        | 
| 1431351982  | 1        | M094   | M094 SPED - M               | M015    | *          | P.S. 15 - M          | 64     | 101                 | 63                     | 0        |                                 | 0                        | 
| 1431351982  | 1        | M094   | M094 SPED - M               | M061    | *          | P.S. 61 - M          | 56     | 88                  | 64                     |          |                                 |                          | 
| 1431351982  | 1        | M094   | M094 SPED - M               | M188    | *          | P.S. 188 - M         | 52     | 97                  | 54                     |          |                                 |                          | 
```