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
series e:wr8u-xric d:2009-04-12T00:00:00.000Z t:mutual_aid=none t:property_use="000 - property use, other" t:call_number=091020273 t:detector_alerted_occupants=- t:action_taken_primary="52 - forcible entry" t:city=SF t:first_unit_on_scene=T15 t:exposure_number=0 t:station_area=15 t:incident_number=09030109 t:battalion=B09 t:primary_situation="551 - assist pd or other govern. agency" t:action_taken_secondary=- t:action_taken_other=- m:ems_personnel=0 m:fire_fatalities=0 m:fire_injuries=0 m:ems_units=0 m:suppression_personnel=5 m:other_personnel=0 m:suppression_units=1 m:other_units=0 m:civilian_injuries=0 m:civilian_fatalities=0

series e:wr8u-xric d:2013-07-18T00:00:00.000Z t:mutual_aid=none t:property_use="429 - multifamily dwellings" t:call_number=131990117 t:detector_alerted_occupants=- t:action_taken_primary="86 - investigate" t:city=SF t:first_unit_on_scene=E39 t:exposure_number=0 t:station_area=39 t:box=8571 t:incident_number=13067402 t:battalion=B09 t:primary_situation="745 - alarm system sounded/no fire-accidental" t:action_taken_secondary=- t:action_taken_other=- m:ems_personnel=0 m:fire_fatalities=0 m:fire_injuries=0 m:ems_units=0 m:suppression_personnel=11 m:other_personnel=0 m:suppression_units=3 m:other_units=0 m:civilian_injuries=0 m:civilian_fatalities=0

series e:wr8u-xric d:2012-05-13T00:00:00.000Z t:mutual_aid=none t:property_use="963 - street or road in commercial area" t:call_number=121340051 t:detector_alerted_occupants=- t:action_taken_primary="86 - investigate" t:city=SF t:first_unit_on_scene=B03 t:exposure_number=0 t:station_area=01 t:incident_number=12044490 t:battalion=B03 t:supervisor_district=6 t:primary_situation="711 - municipal alarm system, street box false" t:zipcode=94103 t:action_taken_secondary=- t:action_taken_other=- t:neighborhood_district="South of Market" m:ems_personnel=0 m:fire_fatalities=0 m:fire_injuries=0 m:ems_units=0 m:suppression_personnel=10 m:other_personnel=0 m:suppression_units=3 m:other_units=0 m:civilian_injuries=0 m:civilian_fatalities=0
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

property e:wr8u-xric t:meta.view d:2017-09-25T07:28:45.729Z v:averageRating=0 v:name="Fire Incidents" v:id=wr8u-xric v:category="Public Safety"

property e:wr8u-xric t:meta.view.license d:2017-09-25T07:28:45.729Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wr8u-xric t:meta.view.owner d:2017-09-25T07:28:45.729Z v:displayName=OpenData v:id=dbag-6qd9 v:screenName=OpenData

property e:wr8u-xric t:meta.view.tableauthor d:2017-09-25T07:28:45.729Z v:displayName=OpenData v:roleName=publisher v:id=dbag-6qd9 v:screenName=OpenData
```

## Top Records

```ls
| incident_number | exposure_number | address                   | incident_date       | call_number | alarm_dttm          | arrival_dttm        | close_dttm          | city          | zipcode | battalion | station_area | box  | suppression_units | suppression_personnel | ems_units | ems_personnel | other_units | other_personnel | first_unit_on_scene | estimated_property_loss | estimated_contents_loss | fire_fatalities | fire_injuries | civilian_fatalities | civilian_injuries | number_of_alarms | primary_situation                              | mutual_aid | action_taken_primary | action_taken_secondary | action_taken_other | detector_alerted_occupants         | property_use                                     | area_of_fire_origin | ignition_cause | ignition_factor_primary | ignition_factor_secondary | heat_source | item_first_ignited | human_factors_associated_with_ignition | structure_type | structure_status | floor_of_fire_origin | fire_spread | no_flame_spead | number_of_floors_with_minimum_damage | number_of_floors_with_significant_damage | number_of_floors_with_heavy_damage | number_of_floors_with_extreme_damage | detectors_present | detector_type | detector_operation | detector_effectiveness | detector_failure_reason | automatic_extinguishing_system_present | automatic_extinguishing_sytem_type | automatic_extinguishing_sytem_perfomance | automatic_extinguishing_sytem_failure_reason | number_of_sprinkler_heads_operating | supervisor_district | neighborhood_district | 
| =============== | =============== | ========================= | =================== | =========== | =================== | =================== | =================== | ============= | ======= | ========= | ============ | ==== | ================= | ===================== | ========= | ============= | =========== | =============== | =================== | ======================= | ======================= | =============== | ============= | =================== | ================= | ================ | ============================================== | ========== | ==================== | ====================== | ================== | ================================== | ================================================ | =================== | ============== | ======================= | ========================= | =========== | ================== | ====================================== | ============== | ================ | ==================== | =========== | ============== | ==================================== | ======================================== | ================================== | ==================================== | ================= | ============= | ================== | ====================== | ======================= | ====================================== | ================================== | ======================================== | ============================================ | =================================== | =================== | ===================== | 
| 09030109        | 0               | 310 Colon Av.             | 2009-04-12T00:00:00 | 091020273   | 2009-04-12T18:09:13 | 2009-04-12T18:13:45 | 2009-04-12T19:23:13 | SF            |         | B09       | 15           |      | 1                 | 5                     | 0         | 0             | 0           | 0               | T15                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 551 - assist pd or other govern. agency        | none       | 52 - forcible entry  | -                      | -                  | -                                  | 000 - property use, other                        |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     |                     |                       | 
| 13067402        | 0               | 20 Lansdale Av            | 2013-07-18T00:00:00 | 131990117   | 2013-07-18T10:32:03 | 2013-07-18T10:37:15 | 2013-07-18T10:39:55 | SF            |         | B09       | 39           | 8571 | 3                 | 11                    | 0         | 0             | 0           | 0               | E39                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 745 - alarm system sounded/no fire-accidental  | none       | 86 - investigate     | -                      | -                  | -                                  | 429 - multifamily dwellings                      |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     |                     |                       | 
| 12044490        | 0               | 7th St. / Folsom St.      | 2012-05-13T00:00:00 | 121340051   | 2012-05-13T03:55:37 | 2012-05-13T04:01:57 | 2012-05-13T04:05:44 | SF            | 94103   | B03       | 01           |      | 3                 | 10                    | 0         | 0             | 0           | 0               | B03                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 711 - municipal alarm system, street box false | none       | 86 - investigate     | -                      | -                  | -                                  | 963 - street or road in commercial area          |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 6                   | South of Market       | 
| 13033326        | 0               | 2799 Pacific Av           | 2013-04-09T00:00:00 | 130990286   | 2013-04-09T16:34:07 | 2013-04-09T16:39:31 | 2013-04-09T17:20:27 | SF            |         | B04       | 10           | 4163 | 3                 | 10                    | 0         | 0             | 0           | 0               | B04                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 746 - co detector activation, no co            | none       | 86 - investigate     | -                      | -                  | -                                  | 419 - 1 or 2 family dwelling                     |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     |                     |                       | 
| 11101416        | 0               | Polk St. / Pine St.       | 2011-11-01T00:00:00 | 113050357   | 2011-11-01T18:07:45 | 2011-11-01T18:10:17 | 2011-11-01T18:11:09 | SF            | 94109   | B04       | 03           |      | 2                 | 9                     | 0         | 0             | 0           | 0               | E03                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 711 - municipal alarm system, street box false | none       | 86 - investigate     | -                      | -                  | -                                  | 960 - street, other                              |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 3                   | Nob Hill              | 
| 12077793        | 0               | 2824 Scott St.            | 2012-08-22T00:00:00 | 122350085   | 2012-08-22T08:58:06 | 2012-08-22T09:10:06 | 2012-08-22T09:13:18 | SF            | 94123   | B04       | 16           |      | 3                 | 11                    | 0         | 0             | 0           | 0               | E51                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 700 - false alarm or false call, other         | none       | 86 - investigate     | -                      | -                  | -                                  | 400 - residential, other                         |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 2                   | Marina                | 
| 07021713        | 0               | San Bruno Av. / Teddy Av. | 2007-03-15T00:00:00 | 070740223   | 2007-03-15T13:55:35 | 2007-03-15T13:59:24 | 2007-03-15T13:59:56 | SF            | 94134   | B10       | 44           |      | 1                 | 4                     | 0         | 0             | 0           | 0               | E42                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 711 - municipal alarm system, street box false | none       | 86 - investigate     | -                      | -                  | -                                  | 962 - residential street, road or residential dr |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 10                  | Visitacion Valley     | 
| 15065212        | 0               | 1532 Noriega Street       | 2015-06-20T00:00:00 | 151710341   | 2015-06-20T02:44:56 | 2015-06-20T02:51:39 | 2015-06-20T03:18:48 | San Francisco | 94122   | B08       | 40           | 7431 | 8                 | 28                    | 1         | 2             | 1           | 2               |                     | 800                     |                         | 0               | 0             | 0                   | 0                 |                  | 113 cooking fire, confined to container        | n none     | 52 forcible entry    |                        |                    | 2 detector did not alert occupants | 161 restaurant or cafeteria                      |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             | na             |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 4                   | Sunset/Parkside       | 
| 10097225        | 0               | 1215 Carolina St.         | 2010-10-31T00:00:00 | 103040303   | 2010-10-31T17:14:49 | 2010-10-31T17:19:50 | 2010-10-31T17:27:14 | SF            | 94107   | B10       | 37           |      | 3                 | 10                    | 0         | 0             | 0           | 0               | E37                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 745 - alarm system sounded/no fire-accidental  | none       | 86 - investigate     | -                      | -                  | -                                  | 500 - mercantile, business, other                |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 10                  | Potrero Hill          | 
| 08033299        | 0               | 870 Kansas St.            | 2008-04-17T00:00:00 | 081080319   | 2008-04-17T17:54:33 | 2008-04-17T18:00:46 | 2008-04-17T18:04:55 | SF            | 94107   | B10       | 37           |      | 1                 | 4                     | 0         | 0             | 0           | 0               | E37                 |                         |                         | 0               | 0             | 0                   | 0                 |                  | 550 - public service assistance, other         | none       | 86 - investigate     | -                      | -                  | -                                  | 960 - street, other                              |                     |                |                         |                           |             |                    |                                        |                |                  |                      |             |                |                                      |                                          |                                    |                                      |                   |               |                    |                        |                         |                                        |                                    |                                          |                                              |                                     | 10                  | Potrero Hill          | 
```