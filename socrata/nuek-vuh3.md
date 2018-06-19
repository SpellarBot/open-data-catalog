# Fire Department Calls for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-department-calls-for-service) |
| Metadata | [Link](https://data.sfgov.org/api/views/nuek-vuh3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nuek-vuh3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nuek-vuh3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nuek-vuh3 |
| Name | Fire Department Calls for Service |
| Category | Public Safety |
| Tags | calls, fire, 911, medical |
| Created | 2015-12-17T16:07:05Z |
| Publication Date | 2017-04-27T16:15:02Z |

## Description

Fire Calls-For-Service includes all fire units responses to calls. Each record includes the call number, incident number, address, unit identifier, call type, and disposition. All relevant time intervals are also included. Because this dataset is based on responses, and since most calls involved multiple units, there are multiple records for each call number. Addresses are associated with a block number, intersection or call box, not a specific address.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ================================= | ==================================== | ============= | ============= |
| Yes      | series tag     | call_number                       | Call Number                          | text          | text          |
| Yes      | series tag     | unit_id                           | Unit ID                              | text          | text          |
| Yes      | series tag     | incident_number                   | Incident Number                      | text          | text          |
| Yes      | series tag     | call_type                         | Call Type                            | text          | text          |
| Yes      | time           | call_date                         | Call Date                            | calendar_date | calendar_date |
| No       |                | watch_date                        | Watch Date                           | calendar_date | calendar_date |
| No       |                | received_dttm                     | Received DtTm                        | calendar_date | calendar_date |
| No       |                | entry_dttm                        | Entry DtTm                           | calendar_date | calendar_date |
| No       |                | dispatch_dttm                     | Dispatch DtTm                        | calendar_date | calendar_date |
| No       |                | response_dttm                     | Response DtTm                        | calendar_date | calendar_date |
| No       |                | on_scene_dttm                     | On Scene DtTm                        | calendar_date | calendar_date |
| No       |                | transport_dttm                    | Transport DtTm                       | calendar_date | calendar_date |
| No       |                | hospital_dttm                     | Hospital DtTm                        | calendar_date | calendar_date |
| Yes      | series tag     | call_final_disposition            | Call Final Disposition               | text          | text          |
| No       |                | available_dttm                    | Available DtTm                       | calendar_date | calendar_date |
| No       |                | address                           | Address                              | text          | text          |
| Yes      | series tag     | city                              | City                                 | text          | text          |
| Yes      | series tag     | zipcode_of_incident               | Zipcode of Incident                  | text          | text          |
| Yes      | series tag     | battalion                         | Battalion                            | text          | text          |
| Yes      | series tag     | station_area                      | Station Area                         | text          | text          |
| Yes      | series tag     | box                               | Box                                  | text          | text          |
| Yes      | series tag     | original_priority                 | Original Priority                    | text          | text          |
| Yes      | series tag     | priority                          | Priority                             | text          | text          |
| Yes      | series tag     | final_priority                    | Final Priority                       | text          | text          |
| Yes      | series tag     | als_unit                          | ALS Unit                             | checkbox      | checkbox      |
| Yes      | series tag     | call_type_group                   | Call Type Group                      | text          | text          |
| Yes      | numeric metric | number_of_alarms                  | Number of Alarms                     | number        | number        |
| Yes      | series tag     | unit_type                         | Unit Type                            | text          | text          |
| Yes      | numeric metric | unit_sequence_in_call_dispatch    | Unit sequence in call dispatch       | number        | number        |
| Yes      | series tag     | fire_prevention_district          | Fire Prevention District             | text          | text          |
| Yes      | series tag     | supervisor_district               | Supervisor District                  | text          | text          |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhooods - Analysis Boundaries | text          | text          |
| Yes      | series tag     | rowid                             | RowID                                | text          | text          |
```

## Time Field

```ls
Value = call_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = watch_date,received_dttm,entry_dttm,dispatch_dttm,response_dttm,on_scene_dttm,transport_dttm,hospital_dttm,available_dttm,address
```

## Data Commands

```ls
series e:nuek-vuh3 d:2000-04-12T00:00:00.000Z t:call_number=001030101 t:city=SF t:original_priority=3 t:station_area=18 t:fire_prevention_district=8 t:box=0757 t:neighborhoods_analysis_boundaries=Sunset/Parkside t:unit_type=ENGINE t:priority=3 t:incident_number=00306091 t:battalion=B08 t:call_final_disposition=Other t:supervisor_district=4 t:zipcode_of_incident=94116 t:final_priority=3 t:rowid=001030101-E18 t:als_unit=false t:unit_id=E18 t:call_type="Medical Incident" m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=1

series e:nuek-vuh3 d:2000-04-12T00:00:00.000Z t:call_number=001030104 t:city=SF t:original_priority=3 t:station_area=23 t:fire_prevention_district=8 t:box=7651 t:neighborhoods_analysis_boundaries=Sunset/Parkside t:unit_type=MEDIC t:priority=3 t:incident_number=00030612 t:battalion=B08 t:call_final_disposition=Other t:supervisor_district=4 t:zipcode_of_incident=94122 t:final_priority=3 t:rowid=001030104-M14 t:als_unit=true t:unit_id=M14 t:call_type="Medical Incident" m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=2

series e:nuek-vuh3 d:2000-04-12T00:00:00.000Z t:call_number=001030106 t:city=SF t:original_priority=3 t:station_area=36 t:fire_prevention_district=2 t:box=3111 t:neighborhoods_analysis_boundaries=Tenderloin t:unit_type=MEDIC t:priority=3 t:incident_number=00030614 t:battalion=B02 t:call_final_disposition=Other t:supervisor_district=6 t:zipcode_of_incident=94102 t:final_priority=3 t:rowid=001030106-M36 t:als_unit=false t:unit_id=M36 t:call_type="Medical Incident" m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=1
```

## Meta Commands

```ls
metric m:number_of_alarms p:integer l:"Number of Alarms" d:"Number of alarms associated with the incident. This is a number between 1 and 5." t:dataTypeName=number

metric m:unit_sequence_in_call_dispatch p:integer l:"Unit sequence in call dispatch" d:"A number that indicates the order this unit was assigned to this call" t:dataTypeName=number

entity e:nuek-vuh3 l:"Fire Department Calls for Service" t:url=https://data.sfgov.org/api/views/nuek-vuh3

property e:nuek-vuh3 t:meta.view d:2017-09-25T07:22:40.400Z v:averageRating=0 v:name="Fire Department Calls for Service" v:id=nuek-vuh3 v:category="Public Safety"

property e:nuek-vuh3 t:meta.view.license d:2017-09-25T07:22:40.400Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nuek-vuh3 t:meta.view.owner d:2017-09-25T07:22:40.400Z v:displayName=OpenData v:id=dbag-6qd9 v:screenName=OpenData

property e:nuek-vuh3 t:meta.view.tableauthor d:2017-09-25T07:22:40.400Z v:displayName=OpenData v:roleName=publisher v:id=dbag-6qd9 v:screenName=OpenData
```

## Top Records

```ls
| call_number | unit_id | incident_number | call_type                     | call_date           | watch_date          | received_dttm       | entry_dttm          | dispatch_dttm       | response_dttm       | on_scene_dttm       | transport_dttm      | hospital_dttm       | call_final_disposition | available_dttm      | address                    | city | zipcode_of_incident | battalion | station_area | box  | original_priority | priority | final_priority | als_unit | call_type_group | number_of_alarms | unit_type    | unit_sequence_in_call_dispatch | fire_prevention_district | supervisor_district | neighborhoods_analysis_boundaries | rowid         | 
| =========== | ======= | =============== | ============================= | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | ====================== | =================== | ========================== | ==== | =================== | ========= | ============ | ==== | ================= | ======== | ============== | ======== | =============== | ================ | ============ | ============================== | ======================== | =================== | ================================= | ============= | 
| 001030101   | E18     | 00306091        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:01:40 | 2000-04-12T21:00:29 | 2000-04-12T21:01:40 | 2000-04-12T21:02:00 |                     |                     |                     |                     | Other                  |                     | 2000 Block of 37TH AVE     | SF   | 94116               | B08       | 18           | 0757 | 3                 | 3        | 3              | false    |                 | 1                | ENGINE       | 1                              | 8                        | 4                   | Sunset/Parkside                   | 001030101-E18 | 
| 001030104   | M14     | 00030612        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:10:17 | 2000-04-12T21:09:02 | 2000-04-12T21:10:17 | 2000-04-12T21:10:29 | 2000-04-12T21:12:11 | 2000-04-12T21:19:36 | 2000-04-12T21:43:57 | 2000-04-12T22:03:33 | Other                  | 2000-04-12T22:23:57 | 1700 Block of 43RD AVE     | SF   | 94122               | B08       | 23           | 7651 | 3                 | 3        | 3              | true     |                 | 1                | MEDIC        | 2                              | 8                        | 4                   | Sunset/Parkside                   | 001030104-M14 | 
| 001030106   | M36     | 00030614        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:10:56 | 2000-04-12T21:09:44 | 2000-04-12T21:10:56 | 2000-04-12T21:11:47 |                     | 2000-04-12T21:14:11 | 2000-04-12T21:59:31 | 2000-04-12T22:10:06 | Other                  | 2000-04-12T22:43:40 | 0 Block of FELL ST         | SF   | 94102               | B02       | 36           | 3111 | 3                 | 3        | 3              | false    |                 | 1                | MEDIC        | 1                              | 2                        | 6                   | Tenderloin                        | 001030106-M36 | 
| 001030107   | E01     | 00030615        | Alarms                        | 2000-04-12T00:00:00 | 2000-04-12T21:13:51 | 2000-04-12T21:13:47 | 2000-04-12T21:13:51 | 2000-04-12T21:14:13 | 2000-04-12T21:15:58 | 2000-04-12T21:20:12 |                     |                     | Other                  | 2000-04-12T21:24:19 | 100 Block of JONES ST      | SF   | 94102               | B03       | 01           | 1456 | 3                 | 3        | 3              | false    |                 | 1                | ENGINE       | 3                              | 3                        | 6                   | Tenderloin                        | 001030107-E01 | 
| 001030108   | RS1     | 00030616        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:16:11 | 2000-04-12T21:14:43 | 2000-04-12T21:16:11 | 2000-04-12T21:16:24 | 2000-04-12T21:18:20 | 2000-04-12T21:20:08 |                     |                     | Other                  | 2000-04-12T21:20:36 | 700 Block of MARKET ST     | SF   | 94108               | B03       | 01           | 1322 | 3                 | 3        | 3              | false    |                 | 1                | RESCUE SQUAD | 2                              | 1                        | 3                   | Financial District/South Beach    | 001030108-RS1 | 
| 001030112   | T03     | 00030620        | Citizen Assist / Service Call | 2000-04-12T00:00:00 | 2000-04-12T21:24:54 | 2000-04-12T21:24:27 | 2000-04-12T21:24:54 | 2000-04-12T21:25:10 | 2000-04-12T21:27:10 | 2000-04-12T21:30:26 |                     |                     | Other                  | 2000-04-12T21:44:28 | 800 Block of SUTTER ST     | SF   | 94109               | B01       | 03           | 1463 | 3                 | 3        | 3              | false    |                 | 1                | TRUCK        | 1                              | 1                        | 3                   | Nob Hill                          | 001030112-T03 | 
| 001030116   | E38     | 00030624        | Electrical Hazard             | 2000-04-12T00:00:00 | 2000-04-12T21:28:06 | 2000-04-12T21:25:55 | 2000-04-12T21:28:06 | 2000-04-12T21:28:46 | 2000-04-12T21:29:59 | 2000-04-12T21:31:18 |                     |                     | Other                  | 2000-04-12T21:39:36 | CALIFORNIA ST/VAN NESS AV  | SF   | 94109               | B04       | 38           | 3155 | 3                 | 3        | 3              | false    |                 | 1                | ENGINE       | 1                              | 4                        | 2                   | Nob Hill                          | 001030116-E38 | 
| 001030117   | E15     | 00030626        | Odor (Strange / Unknown)      | 2000-04-12T00:00:00 | 2000-04-12T21:28:38 | 2000-04-12T21:27:55 | 2000-04-12T21:28:38 | 2000-04-12T21:30:27 | 2000-04-12T21:31:43 | 2000-04-12T21:34:57 |                     |                     | Other                  | 2000-04-12T21:38:24 | 2100 Block of ALEMANY BLVD | SF   | 94112               | B09       | 15           | 8331 | 3                 | 3        | 3              | false    |                 | 1                | ENGINE       | 1                              | 9                        | 11                  | Outer Mission                     | 001030117-E15 | 
| 001030118   | E08     | 00030625        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:28:58 | 2000-04-12T21:27:45 | 2000-04-12T21:28:58 | 2000-04-12T21:29:21 | 2000-04-12T21:31:26 | 2000-04-12T21:32:34 |                     |                     | Other                  | 2000-04-12T21:45:28 | 4TH ST/CHANNEL ST          | SF   |                     | B03       | 08           | 2226 | 3                 | 3        | 3              | false    |                 | 1                | ENGINE       | 1                              | 3                        | 6                   | None                              | 001030118-E08 | 
| 001030119   | M17     | 00030628        | Medical Incident              | 2000-04-12T00:00:00 | 2000-04-12T21:30:16 | 2000-04-12T21:29:54 | 2000-04-12T21:30:16 | 2000-04-12T21:31:26 | 2000-04-12T21:32:41 | 2000-04-12T21:37:43 | 2000-04-12T21:48:49 |                     | Other                  | 2000-04-12T22:31:08 | 1400 Block of NEWCOMB AVE  | SF   | 94124               | B10       | 17           | 6516 | 1                 | 1        | 2              | true     |                 | 1                | MEDIC        | 1                              | 10                       | 10                  | Bayview Hunters Point             | 001030119-M17 | 
```