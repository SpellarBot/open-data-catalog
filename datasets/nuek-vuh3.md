# Fire Department Calls for Service

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/nuek-vuh3/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/fire-department-calls-for-service)
* [Metadata URL](https://data.sfgov.org/api/views/nuek-vuh3)
* Id = nuek-vuh3
* Name = Fire Department Calls for Service
* Category = Public Safety
* Tags = [calls, fire, 911, medical]
* Created = 2015-12-17T16:07:05Z
* Publication Date = 2016-05-09T22:15:02Z
* Rows Updated = 2017-03-07T11:07:58Z

## Description

Fire Calls-For-Service includes all fire units responses to calls. Each record includes the call number, incident number, address, unit identifier, call type, and disposition. All relevant time intervals are also included. Because this dataset is based on responses, and since most calls involved multiple units, there are multiple records for each call number. Addresses are associated with a block number, intersection or call box, not a specific address.

## Columns

```ls
| Name                           | Field Name                     | Data Type     | Render Type   | Schema Type    | Included | 
| ============================== | ============================== | ============= | ============= | ============== | ======== | 
| Call Number                    | call_number                    | number        | text          | numeric metric | Yes      | 
| Unit ID                        | unit_id                        | text          | text          | series tag     | Yes      | 
| Incident Number                | incident_number                | number        | text          | numeric metric | Yes      | 
| Call Type                      | call_type                      | text          | text          | series tag     | Yes      | 
| Call Date                      | call_date                      | calendar_date | calendar_date | time           | Yes      | 
| Watch Date                     | watch_date                     | calendar_date | calendar_date |                | No       | 
| Received DtTm                  | received_dttm                  | calendar_date | calendar_date |                | No       | 
| Entry DtTm                     | entry_dttm                     | calendar_date | calendar_date |                | No       | 
| Dispatch DtTm                  | dispatch_dttm                  | calendar_date | calendar_date |                | No       | 
| Response DtTm                  | response_dttm                  | calendar_date | calendar_date |                | No       | 
| On Scene DtTm                  | on_scene_dttm                  | calendar_date | calendar_date |                | No       | 
| Transport DtTm                 | transport_dttm                 | calendar_date | calendar_date |                | No       | 
| Hospital DtTm                  | hospital_dttm                  | calendar_date | calendar_date |                | No       | 
| Call Final Disposition         | call_final_disposition         | text          | text          | series tag     | Yes      | 
| Available DtTm                 | available_dttm                 | calendar_date | calendar_date |                | No       | 
| Address                        | address                        | text          | text          |                | No       | 
| City                           | city                           | text          | text          | series tag     | Yes      | 
| Zipcode of Incident            | zipcode_of_incident            | text          | text          | series tag     | Yes      | 
| Battalion                      | battalion                      | text          | text          | series tag     | Yes      | 
| Station Area                   | station_area                   | text          | text          | series tag     | Yes      | 
| Box                            | box                            | text          | text          | series tag     | Yes      | 
| Original Priority              | original_priority              | number        | text          | numeric metric | Yes      | 
| Priority                       | priority                       | number        | text          | numeric metric | Yes      | 
| Final Priority                 | final_priority                 | number        | text          | numeric metric | Yes      | 
| ALS Unit                       | als_unit                       | checkbox      | checkbox      | series tag     | Yes      | 
| Call Type Group                | call_type_group                | text          | text          | series tag     | Yes      | 
| Number of Alarms               | number_of_alarms               | number        | number        | numeric metric | Yes      | 
| Unit Type                      | unit_type                      | text          | text          | series tag     | Yes      | 
| Unit sequence in call dispatch | unit_sequence_in_call_dispatch | number        | number        | numeric metric | Yes      | 
| Fire Prevention District       | fire_prevention_district       | text          | text          | series tag     | Yes      | 
| Supervisor District            | supervisor_district            | text          | text          | series tag     | Yes      | 
| Neighborhood District          | neighborhood_district          | text          | text          | series tag     | Yes      | 
| RowID                          | rowid                          | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = call_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = transport_dttm,dispatch_dttm,received_dttm,address,hospital_dttm,response_dttm,on_scene_dttm,available_dttm,watch_date,entry_dttm
Annotation Fields = 
```

## Data Commands

```ls
series e:nuek-vuh3 d:2014-09-05T00:00:00.000Z t:call_type_group=Alarm t:station_area=12 t:neighborhood_district="Haight Ashbury" t:unit_id=B02 t:call_final_disposition=Fire t:supervisor_district=5 t:city="San Francisco" t:zipcode_of_incident=94117 t:als_unit=true t:call_type=Alarms t:battalion=B05 t:fire_prevention_district=5 t:unit_type=CHIEF t:box=4525 t:rowid=142480332-B02 m:call_number=142480332 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=3 m:incident_number=14086309

series e:nuek-vuh3 d:2015-10-29T00:00:00.000Z t:call_type_group=Alarm t:station_area=13 t:neighborhood_district="Financial District/South Beach" t:unit_id=T02 t:call_final_disposition=Fire t:supervisor_district=3 t:city="San Francisco" t:zipcode_of_incident=94111 t:als_unit=false t:call_type="Structure Fire" t:battalion=B01 t:fire_prevention_district=1 t:unit_type=TRUCK t:box=1155 t:rowid=153022542-T02 m:call_number=153022542 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=4 m:incident_number=15115908

series e:nuek-vuh3 d:2014-12-11T00:00:00.000Z t:call_type_group="Potentially Life-Threatening" t:station_area=21 t:neighborhood_district="Castro/Upper Market" t:unit_id=AM04 t:call_final_disposition="Code 2 Transport" t:supervisor_district=8 t:city="San Francisco" t:zipcode_of_incident=94117 t:als_unit=false t:call_type="Medical Incident" t:battalion=B05 t:fire_prevention_district=5 t:unit_type=PRIVATE t:box=5136 t:rowid=143451112-AM04 m:call_number=143451112 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=1 m:incident_number=14122741
```

## Meta Commands

```ls
metric m:call_number p:integer l:"Call Number" d:"A unique 9-digit number assigned by the 911 Dispatch Center (DEM) to this call. These number are used for both Police and Fire calls." t:dataTypeName=number

metric m:incident_number p:integer l:"Incident Number" d:"A unique 8-digit number assigned by DEM to this Fire incident." t:dataTypeName=number

metric m:final_priority p:integer l:"Final Priority" d:"Final call priority (Code 2: Non-Emergency or Code 3:Emergency)." t:dataTypeName=number

metric m:number_of_alarms p:integer l:"Number of Alarms" d:"Number of alarms associated with the incident. This is a number between 1 and 5." t:dataTypeName=number

metric m:unit_sequence_in_call_dispatch p:integer l:"Unit sequence in call dispatch" d:"A number that indicates the order this unit was assigned to this call" t:dataTypeName=number

entity e:nuek-vuh3 l:"Fire Department Calls for Service" t:url=https://data.sfgov.org/api/views/nuek-vuh3

property e:nuek-vuh3 t:meta.view d:2017-03-08T02:28:51.394Z v:id=nuek-vuh3 v:category="Public Safety" v:averageRating=0 v:name="Fire Department Calls for Service"

property e:nuek-vuh3 t:meta.view.license d:2017-03-08T02:28:51.394Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nuek-vuh3 t:meta.view.owner d:2017-03-08T02:28:51.394Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:nuek-vuh3 t:meta.view.tableauthor d:2017-03-08T02:28:51.394Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```