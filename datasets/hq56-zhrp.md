# Enrollment Capacity And Utilization Reports - Historical by Building

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enrollment-capacity-and-utilization-reports-historical-by-building) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hq56-zhrp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hq56-zhrp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hq56-zhrp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hq56-zhrp |
| Name | Enrollment Capacity And Utilization Reports - Historical by Building |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | school, construction, authority, sca, education, enrollment, capacity, facility, utilization |
| Created | 2015-05-11T20:38:02Z |
| Publication Date | 2015-05-11T20:42:29Z |

## Description

Enrollment, historical capacity and utilization data for every building and schools in those buildings, by building

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                 | Data Type | Render Type |
| ======== | ============== | =============================== | ==================================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                           | meta_data | meta_data   |
| Yes      | numeric metric | geo_dist                        | Geo Dist                             | number    | number      |
| Yes      | series tag     | bldg_id                         | Bldg ID                              | text      | text        |
| Yes      | numeric metric | admin_dist                      | Admin Dist                           | number    | text        |
| Yes      | series tag     | bldg_name                       | Bldg Name                            | text      | text        |
| Yes      | numeric metric | bldg_enroll                     | Bldg Enroll                          | number    | number      |
| Yes      | numeric metric | historical_bldg_cap             | Historical Bldg Cap                  | number    | number      |
| Yes      | numeric metric | historical_bldg_util            | Historical Bldg Util                 | number    | number      |
| Yes      | series tag     | org_id                          | Org ID                               | text      | text        |
| Yes      | series tag     | incl_class                      | Incl. Class                          | text      | text        |
| Yes      | series tag     | organization_name               | Organization Name                    | text      | text        |
| Yes      | numeric metric | org_enroll                      | Org Enroll                           | number    | number      |
| Yes      | numeric metric | org_historical_cap              | Org Historical Cap                   | number    | number      |
| Yes      | numeric metric | org_historical_util             | Org Historical Util                  | number    | number      |
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
series e:hq56-zhrp d:2015-05-11T13:38:08.000Z t:org_id=M015 t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="P.S. 15 - M" m:admin_dist=1 m:historical_bldg_util=52 m:bldg_enroll=254 m:prek_cap=36 m:no_of_cluster_rms_needed=1 m:geo_dist=1 m:org_enroll=190 m:org_historical_util=49 m:no_of_cluster_spec_rms_reported=4 m:org_historical_cap=387 m:historical_bldg_cap=488

series e:hq56-zhrp d:2015-05-11T13:38:08.000Z t:org_id=M094 t:incl_class=* t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="M094 SPED - M" m:admin_dist=1 m:geo_dist=1 m:org_enroll=64 m:org_historical_util=63 m:org_historical_cap=101

series e:hq56-zhrp d:2015-05-11T13:38:08.000Z t:org_id=MCBO t:bldg_id=M015 t:bldg_name="P.S. 15 - M" t:organization_name="EDUCATION ALLIANCE - M" m:admin_dist=1 m:geo_dist=1
```

## Meta Commands

```ls
metric m:geo_dist p:integer l:"Geo Dist" t:dataTypeName=number

metric m:admin_dist p:integer l:"Admin Dist" t:dataTypeName=number

metric m:bldg_enroll p:integer l:"Bldg Enroll" t:dataTypeName=number

metric m:historical_bldg_cap p:integer l:"Historical Bldg Cap" t:dataTypeName=number

metric m:historical_bldg_util p:integer l:"Historical Bldg Util" t:dataTypeName=number

metric m:org_enroll p:integer l:"Org Enroll" t:dataTypeName=number

metric m:org_historical_cap p:integer l:"Org Historical Cap" t:dataTypeName=number

metric m:org_historical_util p:integer l:"Org Historical Util" t:dataTypeName=number

metric m:prek_cap p:integer l:"PreK Cap +" t:dataTypeName=number

metric m:no_of_cluster_spec_rms_reported p:integer l:"No. of Cluster / Spec Rms Reported +" t:dataTypeName=number

metric m:no_of_cluster_rms_needed p:integer l:"No. of Cluster Rms Needed +" t:dataTypeName=number

entity e:hq56-zhrp l:"Enrollment Capacity And Utilization Reports - Historical by Building" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/hq56-zhrp

property e:hq56-zhrp t:meta.view v:id=hq56-zhrp v:category=Education v:averageRating=0 v:name="Enrollment Capacity And Utilization Reports - Historical by Building" v:attribution="School Construction Authority (SCA)"

property e:hq56-zhrp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hq56-zhrp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | geo_dist | bldg_id | admin_dist | bldg_name             | bldg_enroll | historical_bldg_cap | historical_bldg_util | org_id | incl_class | organization_name               | org_enroll | org_historical_cap | org_historical_util | prek_cap | no_of_cluster_spec_rms_reported | no_of_cluster_rms_needed | 
| =========== | ======== | ======= | ========== | ===================== | =========== | =================== | ==================== | ====== | ========== | =============================== | ========== | ================== | =================== | ======== | =============================== | ======================== | 
| 1431351488  | 1        | M015    | 1          | P.S. 15 - M           | 254         | 488                 | 52                   | M015   |            | P.S. 15 - M                     | 190        | 387                | 49                  | 36       | 4                               | 1                        | 
| 1431351488  | 1        | M015    | 1          | P.S. 15 - M           |             |                     |                      | M094   | *          | M094 SPED - M                   | 64         | 101                | 63                  |          |                                 |                          | 
| 1431351488  | 1        | M015    | 1          | P.S. 15 - M           |             |                     |                      | MCBO   |            | EDUCATION ALLIANCE - M          |            |                    |                     |          |                                 |                          | 
| 1431351488  | 1        | M019    | 1          | P.S. 19 - M           | 443         | 735                 | 60                   | M019   |            | P.S. 19 - M                     | 285        | 460                | 62                  | 36       | 2                               | 2                        | 
| 1431351488  | 1        | M019    | 1          | P.S. 19 - M           |             |                     |                      | M301   |            | I.S. 301 - M                    | 158        | 275                | 57                  |          | 0                               | 0                        | 
| 1431351488  | 1        | M020    | 1          | P.S. 20 - M           | 631         | 968                 | 65                   | M020   |            | P.S. 20 - M                     | 631        | 968                | 65                  | 53       | 9                               | 3                        | 
| 1431351488  | 1        | M020    | 1          | P.S. 20 - M           |             |                     |                      | MCBO   |            | ED ALLIANCE/DISTRICT 1 OFFICE-M |            |                    |                     |          |                                 |                          | 
| 1431351488  | 1        | M020    | 1          | P.S. 20 - M           |             |                     |                      | MSFS   |            | FOOD SERVICES - M               |            |                    |                     |          |                                 |                          | 
| 1431351488  | 1        | M022    | 1          | N.E.S.T (OLD J22) - M | 1725        | 1723                | 100                  | M539   |            | NEW EXPLORATIONS - M            | 1725       | 1723               | 100                 | 0        | 11                              | 4                        | 
| 1431351488  | 1        | M025    | 1          | J.H.S. 25 - M         | 1196        | 1721                | 69                   | M378   |            | I.S. 378 - M                    | 244        | 321                | 76                  |          | 0                               | 0                        | 
```