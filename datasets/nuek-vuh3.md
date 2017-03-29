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
| Publication Date | 2016-05-09T22:15:02Z |

## Description

Fire Calls-For-Service includes all fire units responses to calls. Each record includes the call number, incident number, address, unit identifier, call type, and disposition. All relevant time intervals are also included. Because this dataset is based on responses, and since most calls involved multiple units, there are multiple records for each call number. Addresses are associated with a block number, intersection or call box, not a specific address.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | call_number                    | Call Number                    | text          | text          |
| Yes      | series tag     | unit_id                        | Unit ID                        | text          | text          |
| Yes      | series tag     | incident_number                | Incident Number                | text          | text          |
| Yes      | series tag     | call_type                      | Call Type                      | text          | text          |
| Yes      | time           | call_date                      | Call Date                      | calendar_date | calendar_date |
| No       |                | watch_date                     | Watch Date                     | calendar_date | calendar_date |
| No       |                | received_dttm                  | Received DtTm                  | calendar_date | calendar_date |
| No       |                | entry_dttm                     | Entry DtTm                     | calendar_date | calendar_date |
| No       |                | dispatch_dttm                  | Dispatch DtTm                  | calendar_date | calendar_date |
| No       |                | response_dttm                  | Response DtTm                  | calendar_date | calendar_date |
| No       |                | on_scene_dttm                  | On Scene DtTm                  | calendar_date | calendar_date |
| No       |                | transport_dttm                 | Transport DtTm                 | calendar_date | calendar_date |
| No       |                | hospital_dttm                  | Hospital DtTm                  | calendar_date | calendar_date |
| Yes      | series tag     | call_final_disposition         | Call Final Disposition         | text          | text          |
| No       |                | available_dttm                 | Available DtTm                 | calendar_date | calendar_date |
| No       |                | address                        | Address                        | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | zipcode_of_incident            | Zipcode of Incident            | text          | text          |
| Yes      | series tag     | battalion                      | Battalion                      | text          | text          |
| Yes      | series tag     | station_area                   | Station Area                   | text          | text          |
| Yes      | series tag     | box                            | Box                            | text          | text          |
| Yes      | series tag     | original_priority              | Original Priority              | text          | text          |
| Yes      | series tag     | priority                       | Priority                       | text          | text          |
| Yes      | series tag     | final_priority                 | Final Priority                 | text          | text          |
| Yes      | series tag     | als_unit                       | ALS Unit                       | checkbox      | checkbox      |
| Yes      | series tag     | call_type_group                | Call Type Group                | text          | text          |
| Yes      | numeric metric | number_of_alarms               | Number of Alarms               | number        | number        |
| Yes      | series tag     | unit_type                      | Unit Type                      | text          | text          |
| Yes      | numeric metric | unit_sequence_in_call_dispatch | Unit sequence in call dispatch | number        | number        |
| Yes      | series tag     | fire_prevention_district       | Fire Prevention District       | text          | text          |
| Yes      | series tag     | supervisor_district            | Supervisor District            | text          | text          |
| Yes      | series tag     | neighborhood_district          | Neighborhood District          | text          | text          |
| Yes      | series tag     | rowid                          | RowID                          | text          | text          |
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
series e:nuek-vuh3 d:2014-09-05T00:00:00.000Z t:call_type_group=Alarm t:station_area=12 t:final_priority=3 t:neighborhood_district="Haight Ashbury" t:unit_id=B02 t:call_final_disposition=Fire t:incident_number=14086309 t:supervisor_district=5 t:city="San Francisco" t:als_unit=true t:zipcode_of_incident=94117 t:call_type=Alarms t:call_number=142480332 t:priority=3 t:original_priority=3 t:fire_prevention_district=5 t:battalion=B05 t:unit_type=CHIEF t:box=4525 t:rowid=142480332-B02 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=3

series e:nuek-vuh3 d:2015-10-29T00:00:00.000Z t:call_type_group=Alarm t:station_area=13 t:final_priority=3 t:neighborhood_district="Financial District/South Beach" t:unit_id=T02 t:call_final_disposition=Fire t:incident_number=15115908 t:supervisor_district=3 t:city="San Francisco" t:als_unit=false t:zipcode_of_incident=94111 t:call_type="Structure Fire" t:call_number=153022542 t:priority=3 t:original_priority=3 t:fire_prevention_district=1 t:battalion=B01 t:unit_type=TRUCK t:box=1155 t:rowid=153022542-T02 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=4

series e:nuek-vuh3 d:2014-12-11T00:00:00.000Z t:call_type_group="Potentially Life-Threatening" t:station_area=21 t:final_priority=3 t:neighborhood_district="Castro/Upper Market" t:unit_id=AM04 t:call_final_disposition="Code 2 Transport" t:incident_number=14122741 t:supervisor_district=8 t:city="San Francisco" t:als_unit=false t:zipcode_of_incident=94117 t:call_type="Medical Incident" t:call_number=143451112 t:priority=3 t:original_priority=3 t:fire_prevention_district=5 t:battalion=B05 t:unit_type=PRIVATE t:box=5136 t:rowid=143451112-AM04 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=1
```

## Meta Commands

```ls
metric m:number_of_alarms p:integer l:"Number of Alarms" d:"Number of alarms associated with the incident. This is a number between 1 and 5." t:dataTypeName=number

metric m:unit_sequence_in_call_dispatch p:integer l:"Unit sequence in call dispatch" d:"A number that indicates the order this unit was assigned to this call" t:dataTypeName=number

entity e:nuek-vuh3 l:"Fire Department Calls for Service" t:url=https://data.sfgov.org/api/views/nuek-vuh3

property e:nuek-vuh3 t:meta.view v:id=nuek-vuh3 v:category="Public Safety" v:averageRating=0 v:name="Fire Department Calls for Service"

property e:nuek-vuh3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nuek-vuh3 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:nuek-vuh3 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| call_number | unit_id | incident_number | call_type        | call_date           | watch_date          | received_dttm       | entry_dttm          | dispatch_dttm       | response_dttm       | on_scene_dttm       | transport_dttm      | hospital_dttm       | call_final_disposition | available_dttm      | address                      | city          | zipcode_of_incident | battalion | station_area | box  | original_priority | priority | final_priority | als_unit | call_type_group              | number_of_alarms | unit_type      | unit_sequence_in_call_dispatch | fire_prevention_district | supervisor_district | neighborhood_district          | rowid          | 
| =========== | ======= | =============== | ================ | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | ====================== | =================== | ============================ | ============= | =================== | ========= | ============ | ==== | ================= | ======== | ============== | ======== | ============================ | ================ | ============== | ============================== | ======================== | =================== | ============================== | ============== | 
| 142480332   | B02     | 14086309        | Alarms           | 2014-09-05T00:00:00 | 2014-09-04T00:00:00 | 2014-09-05T03:15:13 | 2014-09-05T03:17:26 | 2014-09-05T03:18:18 | 2014-09-05T03:20:30 | 2014-09-05T03:24:11 | 2016-04-25T13:15:16 | 2016-04-25T13:15:16 | Fire                   | 2014-09-05T03:33:20 | 1600 Block of HAIGHT ST      | San Francisco | 94117               | B05       | 12           | 4525 | 3                 | 3        | 3              | true     | Alarm                        | 1                | CHIEF          | 3                              | 5                        | 5                   | Haight Ashbury                 | 142480332-B02  | 
| 153022542   | T02     | 15115908        | Structure Fire   | 2015-10-29T00:00:00 | 2015-10-29T00:00:00 | 2015-10-29T15:39:06 | 2015-10-29T15:39:25 | 2015-10-29T15:39:49 | 2015-10-29T15:40:55 | 2015-10-29T15:43:21 | 2016-04-25T13:07:30 | 2016-04-25T13:07:30 | Fire                   | 2015-10-29T15:51:21 | BATTERY ST/VALLEJO ST        | San Francisco | 94111               | B01       | 13           | 1155 | 3                 | 3        | 3              | false    | Alarm                        | 1                | TRUCK          | 4                              | 1                        | 3                   | Financial District/South Beach | 153022542-T02  | 
| 143451112   | AM04    | 14122741        | Medical Incident | 2014-12-11T00:00:00 | 2014-12-11T00:00:00 | 2014-12-11T09:02:07 | 2014-12-11T09:03:01 | 2014-12-11T09:03:11 | 2014-12-11T09:06:19 | 2014-12-11T09:20:16 | 2014-12-11T09:20:26 | 2014-12-11T09:43:41 | Code 2 Transport       | 2014-12-11T10:06:26 | 300 Block of BUENA VISTA AVE | San Francisco | 94117               | B05       | 21           | 5136 | 3                 | 3        | 3              | false    | Potentially Life-Threatening | 1                | PRIVATE        | 1                              | 5                        | 8                   | Castro/Upper Market            | 143451112-AM04 | 
| 141660300   | E01     | 14057129        | Medical Incident | 2014-06-15T00:00:00 | 2014-06-14T00:00:00 | 2014-06-15T02:04:57 | 2014-06-15T02:06:42 | 2014-06-15T02:10:01 | 2014-06-15T02:12:55 | 2014-06-15T02:24:55 | 2016-04-25T13:16:45 | 2016-04-25T13:16:45 | Code 2 Transport       | 2014-06-15T02:51:39 | 0 Block of HALLAM ST         | San Francisco | 94103               | B03       | 1            | 2313 | 2                 | 2        | 2              | true     | Non Life-threatening         | 1                | ENGINE         | 2                              | 2                        | 6                   | South of Market                | 141660300-E01  | 
| 152633454   | E36     | 15100829        | Outside Fire     | 2015-09-20T00:00:00 | 2015-09-20T00:00:00 | 2015-09-20T20:15:00 | 2015-09-20T20:15:53 | 2015-09-20T20:16:17 | 2015-09-20T20:18:07 | 2016-04-25T13:08:14 | 2016-04-25T13:08:14 | 2016-04-25T13:08:14 | Fire                   | 2015-09-20T20:22:11 | MARKET ST/VAN NESS AV        | San Francisco | 94103               | B02       | 36           | 3211 | 3                 | 3        | 3              | true     | Fire                         | 1                | ENGINE         | 1                              | 2                        | 6                   | Mission                        | 152633454-E36  | 
| 160941229   | 62      | 16037213        | Medical Incident | 2016-04-03T00:00:00 | 2016-04-03T00:00:00 | 2016-04-03T10:11:05 | 2016-04-03T10:13:32 | 2016-04-03T10:13:50 | 2016-04-03T10:14:04 | 2016-04-03T10:17:26 | 2016-04-03T10:28:20 | 2016-04-03T11:00:27 | Code 2 Transport       | 2016-04-03T11:27:46 | CABRILLO ST/LA PLAYA         | San Francisco | 94121               | B07       | 34           | 7277 | 2                 | 2        | 2              | true     | Non Life-threatening         | 1                | MEDIC          | 1                              | 7                        | 1                   | Outer Richmond                 | 160941229-62   | 
| 142672360   | E43     | 14093558        | Medical Incident | 2014-09-24T00:00:00 | 2014-09-24T00:00:00 | 2014-09-24T15:07:36 | 2014-09-24T15:08:31 | 2014-09-24T15:09:33 | 2014-09-24T15:11:28 | 2016-04-25T13:14:55 | 2016-04-25T13:14:55 | 2016-04-25T13:14:55 | Code 2 Transport       | 2014-09-24T15:11:52 | 4900 Block of MISSION ST     | San Francisco | 94112               | B09       | 43           | 6123 | 2                 | 2        | 2              | false    | Potentially Life-Threatening | 1                | ENGINE         | 2                              | 9                        | 11                  | Excelsior                      | 142672360-E43  | 
| 152052982   | E11     | 15078184        | Medical Incident | 2015-07-24T00:00:00 | 2015-07-24T00:00:00 | 2015-07-24T17:45:39 | 2015-07-24T17:49:36 | 2015-07-24T17:50:18 | 2015-07-24T17:51:14 | 2015-07-24T17:52:56 | 2016-04-25T13:09:17 | 2016-04-25T13:09:17 | Code 2 Transport       | 2015-07-24T18:02:50 | 1500 Block of DOLORES ST     | San Francisco | 94110               | B06       | 11           | 5576 | 3                 | 3        | 3              | true     | Potentially Life-Threatening | 1                | ENGINE         | 1                              | 6                        | 8                   | Noe Valley                     | 152052982-E11  | 
| 150172539   | RC3     | 15006796        | Medical Incident | 2015-01-17T00:00:00 | 2015-01-17T00:00:00 | 2015-01-17T16:56:52 | 2015-01-17T16:58:19 | 2015-01-17T17:07:34 | 2015-01-17T17:07:34 | 2015-01-17T17:36:03 | 2016-04-25T13:12:46 | 2016-04-25T13:12:46 | Code 3 Transport       | 2015-01-17T17:36:07 | BERNAL HEIGHTS BL/FOLSOM ST  | San Francisco | 94110               | B06       | 11           | 5663 | 2                 | 2        | 2              | true     | Potentially Life-Threatening | 1                | RESCUE CAPTAIN | 5                              | 6                        | 9                   | Bernal Heights                 | 150172539-RC3  | 
| 160921973   | 65      | 16036463        | Medical Incident | 2016-04-01T00:00:00 | 2016-04-01T00:00:00 | 2016-04-01T14:12:55 | 2016-04-01T14:14:42 | 2016-04-01T14:16:11 | 2016-04-01T14:16:19 | 2016-04-01T14:25:50 | 2016-04-01T14:36:59 | 2016-04-01T14:56:19 | Code 2 Transport       | 2016-04-01T15:26:51 | 1800 Block of CHESTNUT ST    | San Francisco | 94123               | B04       | 16           | 3445 | 2                 | 2        | 2              | true     | Non Life-threatening         | 1                | MEDIC          | 2                              | 4                        | 2                   | Marina                         | 160921973-65   | 
```