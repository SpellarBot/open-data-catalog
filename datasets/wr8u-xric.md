# Fire Incidents

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/wr8u-xric/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/fire-incidents)
* [Metadata URL](https://data.sfgov.org/api/views/wr8u-xric)
* Id = wr8u-xric
* Name = Fire Incidents
* Category = Public Safety
* Created = 2015-12-18T22:15:10Z
* Publication Date = 2016-07-06T01:29:24Z
* Rows Updated = 2017-03-07T09:32:29Z

## Description

Fire Incidents includes a summary of each (non-medical) incident to which the SF Fire Department responded. Each incident record includes the call number, incident number, address, number and type of each unit responding, call type (as determined by dispatch), prime situation (field observation), actions taken, and property loss.

## Columns

```ls
| Name                                         | Field Name                                   | Data Type     | Render Type   | Schema Type    | Included | 
| ============================================ | ============================================ | ============= | ============= | ============== | ======== | 
| Incident Number                              | incident_number                              | number        | text          | numeric metric | Yes      | 
| Exposure Number                              | exposure_number                              | number        | number        | numeric metric | Yes      | 
| Address                                      | address                                      | text          | text          |                | No       | 
| Incident Date                                | incident_date                                | calendar_date | calendar_date | time           | Yes      | 
| Call Number                                  | call_number                                  | number        | text          | numeric metric | Yes      | 
| Alarm DtTm                                   | alarm_dttm                                   | calendar_date | calendar_date |                | No       | 
| Arrival DtTm                                 | arrival_dttm                                 | calendar_date | calendar_date |                | No       | 
| Close DtTm                                   | close_dttm                                   | calendar_date | calendar_date |                | No       | 
| City                                         | city                                         | text          | text          | series tag     | Yes      | 
| Zipcode                                      | zipcode                                      | text          | text          | series tag     | Yes      | 
| Battalion                                    | battalion                                    | text          | text          | series tag     | Yes      | 
| Station Area                                 | station_area                                 | text          | text          | series tag     | Yes      | 
| Box                                          | box                                          | text          | text          | series tag     | Yes      | 
| Suppression Units                            | suppression_units                            | number        | number        | numeric metric | Yes      | 
| Suppression Personnel                        | suppression_personnel                        | number        | number        | numeric metric | Yes      | 
| EMS Units                                    | ems_units                                    | number        | number        | numeric metric | Yes      | 
| EMS Personnel                                | ems_personnel                                | number        | number        | numeric metric | Yes      | 
| Other Units                                  | other_units                                  | number        | number        | numeric metric | Yes      | 
| Other Personnel                              | other_personnel                              | number        | number        | numeric metric | Yes      | 
| First Unit On Scene                          | first_unit_on_scene                          | text          | text          | series tag     | Yes      | 
| Estimated Property Loss                      | estimated_property_loss                      | number        | number        | numeric metric | Yes      | 
| Estimated Contents Loss                      | estimated_contents_loss                      | number        | number        | numeric metric | Yes      | 
| Fire Fatalities                              | fire_fatalities                              | number        | number        | numeric metric | Yes      | 
| Fire Injuries                                | fire_injuries                                | number        | number        | numeric metric | Yes      | 
| Civilian Fatalities                          | civilian_fatalities                          | number        | number        | numeric metric | Yes      | 
| Civilian Injuries                            | civilian_injuries                            | number        | number        | numeric metric | Yes      | 
| Number of Alarms                             | number_of_alarms                             | number        | number        | numeric metric | Yes      | 
| Primary Situation                            | primary_situation                            | text          | text          | series tag     | Yes      | 
| Mutual Aid                                   | mutual_aid                                   | text          | text          | series tag     | Yes      | 
| Action Taken Primary                         | action_taken_primary                         | text          | text          | series tag     | Yes      | 
| Action Taken Secondary                       | action_taken_secondary                       | text          | text          | series tag     | Yes      | 
| Action Taken Other                           | action_taken_other                           | text          | text          | series tag     | Yes      | 
| Detector Alerted Occupants                   | detector_alerted_occupants                   | text          | text          | series tag     | Yes      | 
| Property Use                                 | property_use                                 | text          | text          | series tag     | Yes      | 
| Area of Fire Origin                          | area_of_fire_origin                          | text          | text          | series tag     | Yes      | 
| Ignition Cause                               | ignition_cause                               | text          | text          | series tag     | Yes      | 
| Ignition Factor Primary                      | ignition_factor_primary                      | text          | text          | series tag     | Yes      | 
| Ignition Factor Secondary                    | ignition_factor_secondary                    | text          | text          | series tag     | Yes      | 
| Heat Source                                  | heat_source                                  | text          | text          | series tag     | Yes      | 
| Item First Ignited                           | item_first_ignited                           | text          | text          | series tag     | Yes      | 
| Human Factors Associated with Ignition       | human_factors_associated_with_ignition       | text          | text          | series tag     | Yes      | 
| Structure Type                               | structure_type                               | text          | text          | series tag     | Yes      | 
| Structure Status                             | structure_status                             | text          | text          | series tag     | Yes      | 
| Floor of Fire Origin                         | floor_of_fire_origin                         | number        | number        | numeric metric | Yes      | 
| Fire Spread                                  | fire_spread                                  | text          | text          | series tag     | Yes      | 
| No Flame Spead                               | no_flame_spead                               | text          | text          | series tag     | Yes      | 
| Number of floors with minimum damage         | number_of_floors_with_minimum_damage         | number        | number        | numeric metric | Yes      | 
| Number of floors with significant damage     | number_of_floors_with_significant_damage     | number        | text          | numeric metric | Yes      | 
| Number of floors with heavy damage           | number_of_floors_with_heavy_damage           | number        | number        | numeric metric | Yes      | 
| Number of floors with extreme damage         | number_of_floors_with_extreme_damage         | number        | number        | numeric metric | Yes      | 
| Detectors Present                            | detectors_present                            | text          | text          | series tag     | Yes      | 
| Detector Type                                | detector_type                                | text          | text          | series tag     | Yes      | 
| Detector Operation                           | detector_operation                           | text          | text          | series tag     | Yes      | 
| Detector Effectiveness                       | detector_effectiveness                       | text          | text          | series tag     | Yes      | 
| Detector Failure Reason                      | detector_failure_reason                      | text          | text          | series tag     | Yes      | 
| Automatic Extinguishing System Present       | automatic_extinguishing_system_present       | text          | text          | series tag     | Yes      | 
| Automatic Extinguishing Sytem Type           | automatic_extinguishing_sytem_type           | text          | text          | series tag     | Yes      | 
| Automatic Extinguishing Sytem Perfomance     | automatic_extinguishing_sytem_perfomance     | text          | text          | series tag     | Yes      | 
| Automatic Extinguishing Sytem Failure Reason | automatic_extinguishing_sytem_failure_reason | text          | text          | series tag     | Yes      | 
| Number of Sprinkler Heads Operating          | number_of_sprinkler_heads_operating          | number        | number        | numeric metric | Yes      | 
| Supervisor District                          | supervisor_district                          | text          | text          | series tag     | Yes      | 
| Neighborhood District                        | neighborhood_district                        | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = arrival_dttm,address,close_dttm,alarm_dttm
Annotation Fields = 
```

## Data Commands

```ls
series e:wr8u-xric d:2009-04-12T00:00:00.000Z t:first_unit_on_scene=T15 t:primary_situation="551 - assist pd or other govern. agency" t:property_use="000 - property use, other" t:action_taken_other=- t:station_area=15 t:mutual_aid=none t:detector_alerted_occupants=- t:battalion=B09 t:action_taken_primary="52 - forcible entry" t:action_taken_secondary=- t:city=SF m:ems_personnel=0 m:civilian_fatalities=0 m:other_units=0 m:exposure_number=0 m:incident_number=9030109 m:suppression_units=1 m:other_personnel=0 m:call_number=91020273 m:ems_units=0 m:fire_fatalities=0 m:suppression_personnel=5 m:fire_injuries=0 m:civilian_injuries=0

series e:wr8u-xric d:2013-07-18T00:00:00.000Z t:first_unit_on_scene=E39 t:primary_situation="745 - alarm system sounded/no fire-accidental" t:property_use="429 - multifamily dwellings" t:action_taken_other=- t:station_area=39 t:mutual_aid=none t:detector_alerted_occupants=- t:battalion=B09 t:action_taken_primary="86 - investigate" t:action_taken_secondary=- t:box=8571 t:city=SF m:ems_personnel=0 m:civilian_fatalities=0 m:other_units=0 m:exposure_number=0 m:incident_number=13067402 m:suppression_units=3 m:other_personnel=0 m:call_number=131990117 m:ems_units=0 m:fire_fatalities=0 m:suppression_personnel=11 m:fire_injuries=0 m:civilian_injuries=0

series e:wr8u-xric d:2012-05-13T00:00:00.000Z t:primary_situation="711 - municipal alarm system, street box false" t:property_use="963 - street or road in commercial area" t:station_area=01 t:mutual_aid=none t:zipcode=94103 t:detector_alerted_occupants=- t:neighborhood_district="South of Market" t:supervisor_district=6 t:city=SF t:first_unit_on_scene=B03 t:action_taken_other=- t:battalion=B03 t:action_taken_secondary=- t:action_taken_primary="86 - investigate" m:ems_personnel=0 m:civilian_fatalities=0 m:other_units=0 m:exposure_number=0 m:incident_number=12044490 m:suppression_units=3 m:other_personnel=0 m:call_number=121340051 m:ems_units=0 m:fire_fatalities=0 m:suppression_personnel=10 m:fire_injuries=0 m:civilian_injuries=0
```

## Meta Commands

```ls
metric m:incident_number p:integer l:"Incident Number" t:dataTypeName=number

metric m:exposure_number p:integer l:"Exposure Number" t:dataTypeName=number

metric m:call_number p:integer l:"Call Number" t:dataTypeName=number

metric m:suppression_units p:integer l:"Suppression Units" t:dataTypeName=number

metric m:suppression_personnel p:integer l:"Suppression Personnel" t:dataTypeName=number

metric m:ems_units p:integer l:"EMS Units" t:dataTypeName=number

metric m:ems_personnel p:integer l:"EMS Personnel" t:dataTypeName=number

metric m:other_units p:integer l:"Other Units" t:dataTypeName=number

metric m:other_personnel p:integer l:"Other Personnel" t:dataTypeName=number

metric m:estimated_property_loss l:"Estimated Property Loss" t:dataTypeName=number

metric m:estimated_contents_loss l:"Estimated Contents Loss" t:dataTypeName=number

metric m:fire_fatalities p:integer l:"Fire Fatalities" t:dataTypeName=number

metric m:fire_injuries p:integer l:"Fire Injuries" t:dataTypeName=number

metric m:civilian_fatalities p:integer l:"Civilian Fatalities" t:dataTypeName=number

metric m:civilian_injuries p:integer l:"Civilian Injuries" t:dataTypeName=number

metric m:number_of_alarms l:"Number of Alarms" t:dataTypeName=number

metric m:floor_of_fire_origin l:"Floor of Fire Origin" t:dataTypeName=number

metric m:number_of_floors_with_minimum_damage p:integer l:"Number of floors with minimum damage" t:dataTypeName=number

metric m:number_of_floors_with_significant_damage p:integer l:"Number of floors with significant damage" t:dataTypeName=number

metric m:number_of_floors_with_heavy_damage p:integer l:"Number of floors with heavy damage" t:dataTypeName=number

metric m:number_of_floors_with_extreme_damage p:integer l:"Number of floors with extreme damage" t:dataTypeName=number

metric m:number_of_sprinkler_heads_operating p:integer l:"Number of Sprinkler Heads Operating" t:dataTypeName=number

entity e:wr8u-xric l:"Fire Incidents" t:url=https://data.sfgov.org/api/views/wr8u-xric

property e:wr8u-xric t:meta.view d:2017-03-07T17:19:11.229Z v:id=wr8u-xric v:category="Public Safety" v:averageRating=0 v:name="Fire Incidents"

property e:wr8u-xric t:meta.view.license d:2017-03-07T17:19:11.229Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wr8u-xric t:meta.view.owner d:2017-03-07T17:19:11.229Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:wr8u-xric t:meta.view.tableauthor d:2017-03-07T17:19:11.229Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```