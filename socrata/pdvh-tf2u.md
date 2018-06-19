# 2012 Vehicle Collisions Investigated by State Police

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-vehicle-collisions-investigated-by-state-police-4fcd0) |
| Metadata | [Link](https://data.maryland.gov/api/views/pdvh-tf2u) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pdvh-tf2u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pdvh-tf2u/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pdvh-tf2u |
| Name | 2012 Vehicle Collisions Investigated by State Police |
| Attribution | Maryland State Police |
| Category | Public Safety |
| Tags | vehicle, collisions, accidents, car, traffic |
| Created | 2013-05-03T18:15:00Z |
| Publication Date | 2013-05-03T18:45:40Z |

## Description

Collisions investigated by the Maryland State Police in 2012 (does not include collisions investigated by local jurisdictions).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | case_number         | CASE_NUMBER         | text          | text          |
| Yes      | series tag     | barrack             | BARRACK             | text          | text          |
| Yes      | time           | acc_date            | ACC_DATE            | calendar_date | calendar_date |
| No       |                | acc_time            | ACC_TIME            | text          | text          |
| Yes      | series tag     | acc_time_code       | ACC_TIME_CODE       | text          | number        |
| No       |                | day_of_week         | DAY_OF_WEEK         | text          | text          |
| Yes      | series tag     | road                | ROAD                | text          | text          |
| Yes      | series tag     | intersect_road      | INTERSECT_ROAD      | text          | text          |
| Yes      | numeric metric | dist_from_intersect | DIST_FROM_INTERSECT | number        | number        |
| Yes      | series tag     | dist_direction      | DIST_DIRECTION      | text          | text          |
| Yes      | series tag     | city_name           | CITY_NAME           | text          | text          |
| Yes      | series tag     | county_code         | COUNTY_CODE         | text          | number        |
| Yes      | series tag     | county_name         | COUNTY_NAME         | text          | text          |
| Yes      | numeric metric | vehicle_count       | VEHICLE_COUNT       | number        | number        |
| Yes      | series tag     | prop_dest           | PROP_DEST           | text          | text          |
| Yes      | series tag     | injury              | INJURY              | text          | text          |
| Yes      | series tag     | collision_with_1    | COLLISION_WITH_1    | text          | text          |
| Yes      | series tag     | collision_with_2    | COLLISION_WITH_2    | text          | text          |
```

## Time Field

```ls
Value = acc_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = acc_time,day_of_week
```

## Data Commands

```ls
series e:pdvh-tf2u d:2012-01-01T00:00:00.000Z t:city_name="Not Applicable" t:case_number=1363000002 t:road="IS 00495 CAPITAL BELTWAY" t:barrack=Rockville t:intersect_road="IS 00270 EISENHOWER MEMORIAL" t:injury=NO t:dist_direction=U t:acc_time_code=1 t:collision_with_1=VEH t:county_name=Montgomery t:prop_dest=YES t:collision_with_2=OTHER-COLLISION t:county_code=15 m:vehicle_count=2 m:dist_from_intersect=0

series e:pdvh-tf2u d:2012-01-01T00:00:00.000Z t:city_name="Not Applicable" t:case_number=1296000023 t:road="MD 00090 OCEAN CITY EXPWY" t:barrack=Berlin t:intersect_road="CO 00220 ST MARTINS NECK RD" t:injury=NO t:dist_direction=W t:acc_time_code=5 t:collision_with_1="FIXED OBJ" t:county_name=Worcester t:prop_dest=YES t:collision_with_2=OTHER-COLLISION t:county_code=23 m:vehicle_count=1 m:dist_from_intersect=0.25

series e:pdvh-tf2u d:2012-01-01T00:00:00.000Z t:city_name="Not Applicable" t:case_number=1283000016 t:road="MD 00765 MAIN ST" t:barrack="Prince Frederick" t:intersect_road="CO 00208 DUKE ST" t:injury=NO t:dist_direction=S t:acc_time_code=2 t:collision_with_1="FIXED OBJ" t:county_name=Calvert t:prop_dest=YES t:collision_with_2="FIXED OBJ" t:county_code=4 m:vehicle_count=1 m:dist_from_intersect=100
```

## Meta Commands

```ls
metric m:dist_from_intersect p:double l:DIST_FROM_INTERSECT t:dataTypeName=number

metric m:vehicle_count p:integer l:VEHICLE_COUNT t:dataTypeName=number

entity e:pdvh-tf2u l:"2012 Vehicle Collisions Investigated by State Police" t:attribution="Maryland State Police" t:url=https://data.maryland.gov/api/views/pdvh-tf2u

property e:pdvh-tf2u t:meta.view v:id=pdvh-tf2u v:category="Public Safety" v:averageRating=0 v:name="2012 Vehicle Collisions Investigated by State Police" v:attribution="Maryland State Police"

property e:pdvh-tf2u t:meta.view.license v:name="Public Domain"

property e:pdvh-tf2u t:meta.view.owner v:id=u26b-uzyh v:screenName="North East Barrack ""F""" v:displayName="North East Barrack ""F"""

property e:pdvh-tf2u t:meta.view.tableauthor v:id=u26b-uzyh v:screenName="North East Barrack ""F""" v:roleName=editor v:displayName="North East Barrack ""F"""
```

## Top Records

```ls
| case_number | barrack          | acc_date            | acc_time | acc_time_code | day_of_week | road                      | intersect_road               | dist_from_intersect | dist_direction | city_name      | county_code | county_name    | vehicle_count | prop_dest | injury | collision_with_1 | collision_with_2 | 
| =========== | ================ | =================== | ======== | ============= | =========== | ========================= | ============================ | =================== | ============== | ============== | =========== | ============== | ============= | ========= | ====== | ================ | ================ | 
| 1363000002  | Rockville        | 2012-01-01T00:00:00 | 2:01     | 1             | SUNDAY      | IS 00495 CAPITAL BELTWAY  | IS 00270 EISENHOWER MEMORIAL | 0                   | U              | Not Applicable | 15          | Montgomery     | 2             | YES       | NO     | VEH              | OTHER-COLLISION  | 
| 1296000023  | Berlin           | 2012-01-01T00:00:00 | 18:01    | 5             | SUNDAY      | MD 00090 OCEAN CITY EXPWY | CO 00220 ST MARTINS NECK RD  | 0.25                | W              | Not Applicable | 23          | Worcester      | 1             | YES       | NO     | FIXED OBJ        | OTHER-COLLISION  | 
| 1283000016  | Prince Frederick | 2012-01-01T00:00:00 | 7:01     | 2             | SUNDAY      | MD 00765 MAIN ST          | CO 00208 DUKE ST             | 100                 | S              | Not Applicable | 4           | Calvert        | 1             | YES       | NO     | FIXED OBJ        | FIXED OBJ        | 
| 1282000006  | Leonardtown      | 2012-01-01T00:00:00 | 0:01     | 1             | SUNDAY      | MD 00944 MERVELL DEAN RD  | MD 00235 THREE NOTCH RD      | 10                  | E              | Not Applicable | 18          | St. Marys      | 1             | YES       | NO     | FIXED OBJ        | OTHER-COLLISION  | 
| 1267000007  | Essex            | 2012-01-01T00:00:00 | 1:01     | 1             | SUNDAY      | IS 00695 BALTO BELTWAY    | IS 00083 HARRISBURG EXPWY    | 100                 | S              | Not Applicable | 3           | Baltimore      | 2             | YES       | NO     | VEH              | OTHER-COLLISION  | 
| 1267000006  | Essex            | 2012-01-01T00:00:00 | 1:01     | 1             | SUNDAY      | IS 00083 HARRISBURG EXPWY | MD 00137 MT CARMEL RD        | 0.25                | S              | Not Applicable | 3           | Baltimore      |               | NO        | YES    | FIXED OBJ        | OTHER-COLLISION  | 
| 1267000005  | Essex            | 2012-01-01T00:00:00 | 1:01     | 1             | SUNDAY      | IS 00070 NO NAME          | IS 00695 BALTO BELTWAY       | 1.5                 | S              | Not Applicable | 3           | Baltimore      | 1             | YES       | NO     | FIXED OBJ        | OTHER-COLLISION  | 
| 1266000090  | College Park     | 2012-01-01T00:00:00 | 6:01     | 2             | SUNDAY      | IS 00095 NO NAME          | CO 00014 CHERRY HILL RD      | 0.25                | S              | Not Applicable | 16          | Prince Georges | 2             | YES       | NO     | VEH              | OTHER-COLLISION  | 
| 1266000025  | College Park     | 2012-01-01T00:00:00 | 14:01    | 4             | SUNDAY      | US 00050 JOHN HANSON HWY  | MD 00410 VETERANS PKWY       | 0.25                | E              | Not Applicable | 16          | Prince Georges | 1             | YES       | YES    | FIXED OBJ        | OTHER-COLLISION  | 
| 1266000016  | College Park     | 2012-01-01T00:00:00 | 6:01     | 2             | SUNDAY      | US 00050 JOHN HANSON HWY  | US 00050 ARDWICK ARDMORE RD  | 100                 |                | Not Applicable | 16          | Prince Georges | 1             | YES       | NO     | FIXED OBJ        | OTHER-COLLISION  | 
```