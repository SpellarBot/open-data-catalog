# Fire Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-incidents) |
| Metadata | [Link](https://data.sfgov.org/api/views/wr8u-xric) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wr8u-xric/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wr8u-xric/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wr8u-xric |
| Name | Fire Incidents |
| Category | Public Safety |
| Created | 2015-12-18T22:15:10Z |
| Publication Date | 2016-07-06T01:29:24Z |
| Rows Updated | 2017-03-21T08:25:36Z |

## Description

Fire Incidents includes a summary of each (non-medical) incident to which the SF Fire Department responded. Each incident record includes the call number, incident number, address, number and type of each unit responding, call type (as determined by dispatch), prime situation (field observation), actions taken, and property loss.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ============================================ | ============================================ | ============= | ============= |
| Yes      | series tag     | incident_number                              | Incident Number                              | text          | text          |
| Yes      | series tag     | exposure_number                              | Exposure Number                              | text          | number        |
| No       |                | address                                      | Address                                      | text          | text          |
| Yes      | time           | incident_date                                | Incident Date                                | calendar_date | calendar_date |
| Yes      | series tag     | call_number                                  | Call Number                                  | text          | text          |
| No       |                | alarm_dttm                                   | Alarm DtTm                                   | calendar_date | calendar_date |
| No       |                | arrival_dttm                                 | Arrival DtTm                                 | calendar_date | calendar_date |
| No       |                | close_dttm                                   | Close DtTm                                   | calendar_date | calendar_date |
| Yes      | series tag     | city                                         | City                                         | text          | text          |
| Yes      | series tag     | zipcode                                      | Zipcode                                      | text          | text          |
| Yes      | series tag     | battalion                                    | Battalion                                    | text          | text          |
| Yes      | series tag     | station_area                                 | Station Area                                 | text          | text          |
| Yes      | series tag     | box                                          | Box                                          | text          | text          |
| Yes      | numeric metric | suppression_units                            | Suppression Units                            | number        | number        |
| Yes      | numeric metric | suppression_personnel                        | Suppression Personnel                        | number        | number        |
| Yes      | numeric metric | ems_units                                    | EMS Units                                    | number        | number        |
| Yes      | numeric metric | ems_personnel                                | EMS Personnel                                | number        | number        |
| Yes      | numeric metric | other_units                                  | Other Units                                  | number        | number        |
| Yes      | numeric metric | other_personnel                              | Other Personnel                              | number        | number        |
| Yes      | series tag     | first_unit_on_scene                          | First Unit On Scene                          | text          | text          |
| Yes      | numeric metric | estimated_property_loss                      | Estimated Property Loss                      | number        | number        |
| Yes      | numeric metric | estimated_contents_loss                      | Estimated Contents Loss                      | number        | number        |
| Yes      | numeric metric | fire_fatalities                              | Fire Fatalities                              | number        | number        |
| Yes      | numeric metric | fire_injuries                                | Fire Injuries                                | number        | number        |
| Yes      | numeric metric | civilian_fatalities                          | Civilian Fatalities                          | number        | number        |
| Yes      | numeric metric | civilian_injuries                            | Civilian Injuries                            | number        | number        |
| Yes      | numeric metric | number_of_alarms                             | Number of Alarms                             | number        | number        |
| Yes      | series tag     | primary_situation                            | Primary Situation                            | text          | text          |
| Yes      | series tag     | mutual_aid                                   | Mutual Aid                                   | text          | text          |
| Yes      | series tag     | action_taken_primary                         | Action Taken Primary                         | text          | text          |
| Yes      | series tag     | action_taken_secondary                       | Action Taken Secondary                       | text          | text          |
| Yes      | series tag     | action_taken_other                           | Action Taken Other                           | text          | text          |
| Yes      | series tag     | detector_alerted_occupants                   | Detector Alerted Occupants                   | text          | text          |
| Yes      | series tag     | property_use                                 | Property Use                                 | text          | text          |
| Yes      | series tag     | area_of_fire_origin                          | Area of Fire Origin                          | text          | text          |
| Yes      | series tag     | ignition_cause                               | Ignition Cause                               | text          | text          |
| Yes      | series tag     | ignition_factor_primary                      | Ignition Factor Primary                      | text          | text          |
| Yes      | series tag     | ignition_factor_secondary                    | Ignition Factor Secondary                    | text          | text          |
| Yes      | series tag     | heat_source                                  | Heat Source                                  | text          | text          |
| Yes      | series tag     | item_first_ignited                           | Item First Ignited                           | text          | text          |
| Yes      | series tag     | human_factors_associated_with_ignition       | Human Factors Associated with Ignition       | text          | text          |
| Yes      | series tag     | structure_type                               | Structure Type                               | text          | text          |
| Yes      | series tag     | structure_status                             | Structure Status                             | text          | text          |
| Yes      | numeric metric | floor_of_fire_origin                         | Floor of Fire Origin                         | number        | number        |
| Yes      | series tag     | fire_spread                                  | Fire Spread                                  | text          | text          |
| Yes      | series tag     | no_flame_spead                               | No Flame Spead                               | text          | text          |
| Yes      | numeric metric | number_of_floors_with_minimum_damage         | Number of floors with minimum damage         | number        | number        |
| Yes      | numeric metric | number_of_floors_with_significant_damage     | Number of floors with significant damage     | number        | text          |
| Yes      | numeric metric | number_of_floors_with_heavy_damage           | Number of floors with heavy damage           | number        | number        |
| Yes      | numeric metric | number_of_floors_with_extreme_damage         | Number of floors with extreme damage         | number        | number        |
| Yes      | series tag     | detectors_present                            | Detectors Present                            | text          | text          |
| Yes      | series tag     | detector_type                                | Detector Type                                | text          | text          |
| Yes      | series tag     | detector_operation                           | Detector Operation                           | text          | text          |
| Yes      | series tag     | detector_effectiveness                       | Detector Effectiveness                       | text          | text          |
| Yes      | series tag     | detector_failure_reason                      | Detector Failure Reason                      | text          | text          |
| Yes      | series tag     | automatic_extinguishing_system_present       | Automatic Extinguishing System Present       | text          | text          |
| Yes      | series tag     | automatic_extinguishing_sytem_type           | Automatic Extinguishing Sytem Type           | text          | text          |
| Yes      | series tag     | automatic_extinguishing_sytem_perfomance     | Automatic Extinguishing Sytem Perfomance     | text          | text          |
| Yes      | series tag     | automatic_extinguishing_sytem_failure_reason | Automatic Extinguishing Sytem Failure Reason | text          | text          |
| Yes      | numeric metric | number_of_sprinkler_heads_operating          | Number of Sprinkler Heads Operating          | number        | number        |
| Yes      | series tag     | supervisor_district                          | Supervisor District                          | text          | text          |
| Yes      | series tag     | neighborhood_district                        | Neighborhood District                        | text          | text          |
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,alarm_dttm,arrival_dttm,close_dttm
```

## Data Commands

```ls
series e:wr8u-xric d:2009-04-12T00:00:00.000Z t:first_unit_on_scene=T15 t:primary_situation="551 - assist pd or other govern. agency" t:property_use="000 - property use, other" t:action_taken_other=- t:station_area=15 t:call_number=091020273 t:mutual_aid=none t:detector_alerted_occupants=- t:exposure_number=0 t:battalion=B09 t:action_taken_primary="52 - forcible entry" t:action_taken_secondary=- t:incident_number=09030109 t:city=SF m:suppression_units=1 m:other_personnel=0 m:ems_personnel=0 m:ems_units=0 m:civilian_fatalities=0 m:other_units=0 m:fire_fatalities=0 m:suppression_personnel=5 m:fire_injuries=0 m:civilian_injuries=0

series e:wr8u-xric d:2013-07-18T00:00:00.000Z t:first_unit_on_scene=E39 t:primary_situation="745 - alarm system sounded/no fire-accidental" t:property_use="429 - multifamily dwellings" t:action_taken_other=- t:station_area=39 t:call_number=131990117 t:mutual_aid=none t:detector_alerted_occupants=- t:exposure_number=0 t:battalion=B09 t:action_taken_primary="86 - investigate" t:action_taken_secondary=- t:box=8571 t:incident_number=13067402 t:city=SF m:suppression_units=3 m:other_personnel=0 m:ems_personnel=0 m:ems_units=0 m:civilian_fatalities=0 m:other_units=0 m:fire_fatalities=0 m:suppression_personnel=11 m:fire_injuries=0 m:civilian_injuries=0

series e:wr8u-xric d:2012-05-13T00:00:00.000Z t:primary_situation="711 - municipal alarm system, street box false" t:property_use="963 - street or road in commercial area" t:station_area=01 t:mutual_aid=none t:zipcode=94103 t:detector_alerted_occupants=- t:neighborhood_district="South of Market" t:exposure_number=0 t:incident_number=12044490 t:supervisor_district=6 t:city=SF t:first_unit_on_scene=B03 t:action_taken_other=- t:call_number=121340051 t:battalion=B03 t:action_taken_secondary=- t:action_taken_primary="86 - investigate" m:suppression_units=3 m:other_personnel=0 m:ems_personnel=0 m:ems_units=0 m:civilian_fatalities=0 m:other_units=0 m:fire_fatalities=0 m:suppression_personnel=10 m:fire_injuries=0 m:civilian_injuries=0
```

## Meta Commands

```ls
metric m:suppression_units p:integer l:"Suppression Units" t:dataTypeName=number

metric m:suppression_personnel p:integer l:"Suppression Personnel" t:dataTypeName=number

metric m:ems_units p:integer l:"EMS Units" t:dataTypeName=number

metric m:ems_personnel p:integer l:"EMS Personnel" t:dataTypeName=number

metric m:other_units p:integer l:"Other Units" t:dataTypeName=number

metric m:other_personnel p:integer l:"Other Personnel" t:dataTypeName=number

metric m:estimated_property_loss p:integer l:"Estimated Property Loss" t:dataTypeName=number

metric m:estimated_contents_loss p:integer l:"Estimated Contents Loss" t:dataTypeName=number

metric m:fire_fatalities p:integer l:"Fire Fatalities" t:dataTypeName=number

metric m:fire_injuries p:integer l:"Fire Injuries" t:dataTypeName=number

metric m:civilian_fatalities p:integer l:"Civilian Fatalities" t:dataTypeName=number

metric m:civilian_injuries p:integer l:"Civilian Injuries" t:dataTypeName=number

metric m:number_of_alarms p:long l:"Number of Alarms" t:dataTypeName=number

metric m:floor_of_fire_origin p:integer l:"Floor of Fire Origin" t:dataTypeName=number

metric m:number_of_floors_with_minimum_damage p:integer l:"Number of floors with minimum damage" t:dataTypeName=number

metric m:number_of_floors_with_significant_damage p:integer l:"Number of floors with significant damage" t:dataTypeName=number

metric m:number_of_floors_with_heavy_damage p:integer l:"Number of floors with heavy damage" t:dataTypeName=number

metric m:number_of_floors_with_extreme_damage p:integer l:"Number of floors with extreme damage" t:dataTypeName=number

metric m:number_of_sprinkler_heads_operating p:integer l:"Number of Sprinkler Heads Operating" t:dataTypeName=number

entity e:wr8u-xric l:"Fire Incidents" t:url=https://data.sfgov.org/api/views/wr8u-xric

property e:wr8u-xric t:meta.view v:id=wr8u-xric v:category="Public Safety" v:averageRating=0 v:name="Fire Incidents"

property e:wr8u-xric t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wr8u-xric t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:wr8u-xric t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```