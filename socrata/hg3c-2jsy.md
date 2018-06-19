# Transportation Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-sites) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hg3c-2jsy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hg3c-2jsy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hg3c-2jsy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hg3c-2jsy |
| Name | Transportation Sites |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Created | 2015-11-13T21:17:03Z |
| Publication Date | 2016-05-03T23:12:30Z |

## Description

OPT provides transportation service to many different kinds of locations. Many of these locations are schools but they also include offices or other sites that may be part of certain students? educational plans. The schools may be public, private or religious. OPT provides busing to some Pre-K sites for students who have an IEP for curb-to-curb busing because of medical condition. Transportation service is not limited to school bus service; it includes distribution of MetroCards and approved reimbursement services. Bus service can be conducted on a yellow school bus, an ambulance, or even a coach bus. Yellow school buses are available in a number of sizes and seating configurations. This dataset includes schools, offices or Pre-K/EI sites that currently receive any transportation services from OPT. These sites may be within the New York City limits or up to fifty miles from the city limits in the states of New York, New Jersey or Connecticut. This dataset does not include field trip destinations.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | school_year                   | School_Year                   | text      | text        |
| Yes      | series tag  | opt_code                      | OPT_Code                      | text      | text        |
| Yes      | series tag  | name                          | Name                          | text      | text        |
| Yes      | series tag  | affiliation                   | Affiliation                   | text      | text        |
| Yes      | series tag  | site_type                     | Site_Type                     | text      | text        |
| Yes      | series tag  | street_address                | Street_Address                | text      | text        |
| Yes      | series tag  | city                          | City                          | text      | text        |
| Yes      | series tag  | state                         | State                         | text      | text        |
| Yes      | series tag  | zip                           | Zip                           | text      | text        |
| No       |             | longitude                     | Longitude                     | number    | text        |
| No       |             | latitude                      | Latitude                      | number    | text        |
| Yes      | series tag  | door_to_door_service          | Door_To_Door_Service          | text      | text        |
| Yes      | series tag  | stop_to_school_service        | Stop_To_School_Service        | text      | text        |
| Yes      | series tag  | common_carrier_svc_metrocards | Common_Carrier_Svc_Metrocards | text      | text        |
| Yes      | series tag  | site_reimbursement            | Site_Reimbursement            | text      | text        |
| Yes      | series tag  | mid_day_service               | Mid_Day_Service               | text      | text        |
| Yes      | series tag  | d2d_late_day_programs         | D2D_Late_Day_Programs         | text      | text        |
| Yes      | series tag  | s2s_late_day_programs         | S2S_Late_Day_Programs         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:hg3c-2jsy d:2017-02-01T12:07:02.000Z t:zip=10002 t:s2s_late_day_programs=No t:state=NY t:opt_code=01001 t:school_year=2016-2017 t:city=Manhattan t:door_to_door_service=Yes t:stop_to_school_service=No t:d2d_late_day_programs=No t:name="Comprehensive Kids Devel. Scho" t:mid_day_service=No t:site_type=School t:affiliation="Other Religion" t:site_reimbursement=No t:street_address="101 Norfolk Street" t:common_carrier_svc_metrocards=No m:row_number.hg3c-2jsy=1

series e:hg3c-2jsy d:2016-11-01T11:13:25.000Z t:zip=10002 t:s2s_late_day_programs=No t:state=NY t:opt_code=01137 t:school_year=2016-2017 t:city=Manhattan t:door_to_door_service=Yes t:stop_to_school_service=No t:d2d_late_day_programs=No t:name="PS 137" t:mid_day_service=Yes t:site_type=School t:affiliation=Public t:site_reimbursement=No t:street_address="293 EAST BROADWAY" t:common_carrier_svc_metrocards=Yes m:row_number.hg3c-2jsy=2

series e:hg3c-2jsy d:2016-11-01T11:13:25.000Z t:zip=10002 t:s2s_late_day_programs=No t:state=NY t:opt_code=01345 t:school_year=2016-2017 t:city=Manhattan t:door_to_door_service=No t:stop_to_school_service=No t:d2d_late_day_programs=No t:name=COLL.ACAD.SCI-TECH-LANG.ARTS t:mid_day_service=No t:site_type=School t:affiliation=Public t:site_reimbursement=No t:street_address="220 HENRY STREET" t:common_carrier_svc_metrocards=Yes m:row_number.hg3c-2jsy=3
```

## Meta Commands

```ls
metric m:row_number.hg3c-2jsy p:long l:"Row Number"

entity e:hg3c-2jsy l:"Transportation Sites" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/hg3c-2jsy

property e:hg3c-2jsy t:meta.view v:id=hg3c-2jsy v:category=Transportation v:averageRating=0 v:name="Transportation Sites" v:attribution="Department of Education (DOE)"

property e:hg3c-2jsy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hg3c-2jsy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | school_year | opt_code | name                           | affiliation    | site_type | street_address        | city      | state | zip   | longitude      | latitude      | door_to_door_service | stop_to_school_service | common_carrier_svc_metrocards | site_reimbursement | mid_day_service | d2d_late_day_programs | s2s_late_day_programs | 
| =========== | =========== | ======== | ============================== | ============== | ========= | ===================== | ========= | ===== | ===== | ============== | ============= | ==================== | ====================== | ============================= | ================== | =============== | ===================== | ===================== | 
| 1485950822  | 2016-2017   | 01001    | Comprehensive Kids Devel. Scho | Other Religion | School    | 101 Norfolk Street    | Manhattan | NY    | 10002 | -73.9872710000 | 40.7187910000 | Yes                  | No                     | No                            | No                 | No              | No                    | No                    | 
| 1477998805  | 2016-2017   | 01137    | PS 137                         | Public         | School    | 293 EAST BROADWAY     | Manhattan | NY    | 10002 | -73.9837310000 | 40.7144920000 | Yes                  | No                     | Yes                           | No                 | Yes             | No                    | No                    | 
| 1477998805  | 2016-2017   | 01345    | COLL.ACAD.SCI-TECH-LANG.ARTS   | Public         | School    | 220 HENRY STREET      | Manhattan | NY    | 10002 | -73.9863310000 | 40.7136080000 | No                   | No                     | Yes                           | No                 | No              | No                    | No                    | 
| 1477998806  | 2016-2017   | 02539    | SOS                            | Public         | School    | 121 6TH AVENUE        | Manhattan | NY    | 10013 | -74.0047880000 | 40.7239230000 | No                   | No                     | No                            | No                 | No              | No                    | No                    | 
| 1477998806  | 2016-2017   | 02541    | HS OF GRAPHIC COMM ARTS        | Public         | School    | 439 WEST 49TH STREET  | Manhattan | NY    | 10019 | -73.9905410000 | 40.7634360000 | No                   | No                     | Yes                           | No                 | No              | No                    | No                    | 
| 1475319851  | 2015-2016   | 11002    | PS 483                         | Public         | School    | 4520 MATILDA AVENUE   | Bronx     | NY    | 10470 | -73.8544000000 | 40.9014280000 | No                   | Yes                    | Yes                           | No                 | No              | No                    | No                    | 
| 1477998806  | 2016-2017   | 03564    | MANHATTAN THEATRE LAB H.S.     | Public         | School    | 122 AMSTERDAM AVENUE  | Manhattan | NY    | 10023 | -73.9848420000 | 40.7743840000 | No                   | No                     | No                            | No                 | No              | No                    | No                    | 
| 1491043957  | 2016-2017   | 01002    | WCL Academy                    | Nonsectarian   | School    | 44 EAST 2ND STREET    | Manhattan | NY    | 10003 | -73.9900630000 | 40.7249040000 | No                   | No                     | Yes                           | No                 | No              | No                    | No                    | 
| 1491043958  | 2016-2017   | 03800    | P754X @ LINCOLN CTR            | Public         | School    | 133 WEST 60TH STREET  | Manhattan | NY    | 10023 | -73.9853080000 | 40.7703680000 | No                   | No                     | No                            | No                 | No              | No                    | No                    | 
| 1485950823  | 2016-2017   | 03985    | STANDING TALL (IMPARTIAL)      | Nonsectarian   | School    | 101 WEST 116TH STREET | Manhattan | NY    | 10026 | -73.9500930000 | 40.8022940000 | No                   | No                     | No                            | No                 | No              | No                    | No                    | 
```