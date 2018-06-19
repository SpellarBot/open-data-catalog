# Traffic Signals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-signals-3a507) |
| Metadata | [Link](https://data.sfgov.org/api/views/inpn-273m) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/inpn-273m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/inpn-273m/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | inpn-273m |
| Name | Traffic Signals |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | traffic signals |
| Created | 2016-08-18T22:07:19Z |
| Publication Date | 2016-10-12T01:00:27Z |

## Description

This dataset serves as an inventory of traffic signals. This data is updated quarterly off of the operational data.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | object_id                    | Object ID                    | text      | number      |
| Yes      | series tag     | cnn_segment_id               | CNN Segment ID               | text      | text        |
| Yes      | series tag     | code                         | Code                         | text      | text        |
| Yes      | series tag     | cross_street_1               | Cross Street 1               | text      | text        |
| Yes      | series tag     | cross_street_2               | Cross Street 2               | text      | text        |
| Yes      | series tag     | detection_type               | Detection Type               | text      | text        |
| Yes      | series tag     | cross_street_3               | Cross Street 3               | text      | text        |
| Yes      | series tag     | supervisor_district          | Supervisor District          | text      | text        |
| Yes      | series tag     | cross_street_4               | Cross Street 4               | text      | text        |
| Yes      | series tag     | equipment_type               | Equipment Type               | text      | text        |
| Yes      | series tag     | vehicle_actuation            | Vehicle Actuation            | text      | text        |
| Yes      | series tag     | pedestrian_signal            | Pedestrian Signal            | text      | text        |
| Yes      | series tag     | pedestrian_actuation         | Pedestrian Actuation         | text      | text        |
| Yes      | series tag     | preemption_priority          | Preemption Priority          | text      | text        |
| Yes      | series tag     | upgraded                     | Upgraded                     | text      | text        |
| Yes      | series tag     | year_of_contract             | Year of Contract             | text      | text        |
| Yes      | numeric metric | last_upgraded                | Last Upgraded                | number    | text        |
| Yes      | series tag     | new_signals_project          | New Signals Project          | text      | text        |
| Yes      | series tag     | modification_project         | Modification Project         | text      | text        |
| Yes      | series tag     | full_upgrade_project         | Full Upgrade Project         | text      | text        |
| Yes      | series tag     | beacon_flasher               | Beacon Flasher               | text      | text        |
| Yes      | series tag     | funding_source               | Funding Source               | text      | text        |
| Yes      | series tag     | red_light_camera             | Red Light Camera             | text      | text        |
| Yes      | numeric metric | start_year                   | Start Year                   | number    | text        |
| Yes      | series tag     | caltrans_route               | CALTRANS Route               | text      | text        |
| Yes      | series tag     | maintained_caltrans          | Maintained CALTRANS          | text      | text        |
| Yes      | numeric metric | percent_caltrans_maintenance | Percent Caltrans Maintenance | number    | number      |
| Yes      | series tag     | maintained_sf                | Maintained SF                | text      | text        |
| Yes      | numeric metric | percent_sf_maintenance       | Percent SF Maintenance       | number    | number      |
| Yes      | numeric metric | percent_port_maintenance     | Percent Port Maintenance     | number    | number      |
| Yes      | time           | last_edited_date             | Last Edited Date             | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:inpn-273m d:2017-04-07T00:00:00.000Z t:pedestrian_signal=ALL t:cnn_segment_id=5331101 t:equipment_type=SIGNAL t:funding_source="SALES TAX" t:object_id=1601 t:pedestrian_actuation=YES t:code=Actuated t:supervisor_district=10 t:vehicle_actuation=WIRELESS t:cross_street_2="POST OFFICE" t:upgraded="NEW DONE" t:cross_street_1=EVANS m:percent_sf_maintenance=0 m:start_year=1999 m:percent_port_maintenance=0 m:percent_caltrans_maintenance=0 m:last_upgraded=1999

series e:inpn-273m d:2017-04-07T00:00:00.000Z t:pedestrian_signal=ALL t:cnn_segment_id=33708000 t:equipment_type=SIGNAL t:funding_source="SALES TAX" t:object_id=1602 t:year_of_contract=4/01 t:code=Actuated t:supervisor_district=7 t:vehicle_actuation=LOOPS t:cross_street_2="CHURCH PARKING LOT (655)" t:upgraded="NEW DONE" t:cross_street_1=BROTHERHOOD m:percent_sf_maintenance=0 m:start_year=2001 m:percent_port_maintenance=0 m:percent_caltrans_maintenance=0

series e:inpn-273m d:2017-04-07T00:00:00.000Z t:beacon_flasher=NONE t:pedestrian_signal=ALL t:modification_project=NONE t:object_id=1603 t:full_upgrade_project=DONE t:pedestrian_actuation=YES t:code=Actuated&Preempt t:supervisor_district=6 t:preemption_priority="BRIDGE PREEMPT" t:cross_street_2="TERRY FRANCOIS" t:cross_street_1="03RD ST" t:cnn_segment_id=30021000 t:equipment_type=SIGNAL t:new_signals_project=NONE t:funding_source=DPW t:vehicle_actuation=WIRELESS t:upgraded="FULL DONE" m:percent_sf_maintenance=0 m:start_year=1952 m:percent_port_maintenance=100 m:percent_caltrans_maintenance=0 m:last_upgraded=1999
```

## Meta Commands

```ls
metric m:last_upgraded p:long l:"Last Upgraded" t:dataTypeName=number

metric m:start_year p:integer l:"Start Year" t:dataTypeName=number

metric m:percent_caltrans_maintenance p:integer l:"Percent Caltrans Maintenance" t:dataTypeName=number

metric m:percent_sf_maintenance p:integer l:"Percent SF Maintenance" t:dataTypeName=number

metric m:percent_port_maintenance p:integer l:"Percent Port Maintenance" t:dataTypeName=number

entity e:inpn-273m l:"Traffic Signals" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/inpn-273m

property e:inpn-273m t:meta.view v:id=inpn-273m v:category=Transportation v:attributionLink=http://sfgov.org/ v:averageRating=0 v:name="Traffic Signals" v:attribution="City and County of San Francisco"

property e:inpn-273m t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:inpn-273m t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:inpn-273m t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_segment_id | code             | cross_street_1 | cross_street_2           | detection_type | cross_street_3 | supervisor_district | cross_street_4 | equipment_type | vehicle_actuation | pedestrian_signal | pedestrian_actuation | preemption_priority  | upgraded    | year_of_contract | last_upgraded | new_signals_project | modification_project | full_upgrade_project | beacon_flasher | funding_source | red_light_camera | start_year | caltrans_route | maintained_caltrans | percent_caltrans_maintenance | maintained_sf | percent_sf_maintenance | percent_port_maintenance | last_edited_date | 
| ========= | ============== | ================ | ============== | ======================== | ============== | ============== | =================== | ============== | ============== | ================= | ================= | ==================== | ==================== | =========== | ================ | ============= | =================== | ==================== | ==================== | ============== | ============== | ================ | ========== | ============== | =================== | ============================ | ============= | ====================== | ======================== | ================ | 
| 1601      | 5331101        | Actuated         | EVANS          | POST OFFICE              |                |                | 10                  |                | SIGNAL         | WIRELESS          | ALL               | YES                  |                      | NEW DONE    |                  | 1999          |                     |                      |                      |                | SALES TAX      |                  | 1999       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1602      | 33708000       | Actuated         | BROTHERHOOD    | CHURCH PARKING LOT (655) |                |                | 7                   |                | SIGNAL         | LOOPS             | ALL               |                      |                      | NEW DONE    | 4/01             |               |                     |                      |                      |                | SALES TAX      |                  | 2001       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1603      | 30021000       | Actuated&Preempt | 03RD ST        | TERRY FRANCOIS           |                |                | 6                   |                | SIGNAL         | WIRELESS          | ALL               | YES                  | BRIDGE PREEMPT       | FULL DONE   |                  | 1999          | NONE                | NONE                 | DONE                 | NONE           | DPW            |                  | 1952       |                |                     | 0                            |               | 0                      | 100                      | 1491523200       | 
| 1604      | 33776000       | Actuated         | BRYANT         | MAIN                     |                |                | 6                   |                | SIGNAL         | LOOPS             | ALL               | YES                  |                      | NEW DONE    | 10/99            |               |                     |                      |                      |                | FEDS           |                  | 2001       |                |                     | 0                            |               | 0                      | 67                       | 1491523200       | 
| 1605      | 23599000       | Actuated         | BEALE          | BRYANT                   |                |                | 6                   |                | SIGNAL         | LOOPS             | ALL               | YES                  |                      | NEW DONE    | 10/99            |               |                     |                      |                      |                | FEDS           |                  | 2001       |                |                     | 0                            |               | 0                      | 40                       | 1491523200       | 
| 1606      | 25098000       | Preempt          | MASON          | WASHINGTON               | MECHANICAL     |                |                     |                | FLASHER        |                   | n.a.              |                      | CABLE CAR PREEMPTION | B&F         |                  |               | NONE                | NONE                 | NONE                 | DONE           |                |                  | 1985       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1607      | 25002000       | FLASHER          | CALIFORNIA     | POWELL                   |                |                |                     |                | FLASHER        |                   | n.a.              |                      |                      | NEW PENDING |                  |               |                     |                      |                      |                | Prop B Go Bond |                  | 1954       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1608      | 21444000       | Fix              | GENEVA         | PARIS                    | OPTICOM        |                | 11                  |                | SIGNAL         | WIRELESS          | ALL               | YES                  | TSP,FIRE PREEMPT     | NEW DONE    |                  | 1999          |                     |                      |                      |                | SALES TAX      |                  | 1999       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1609      | 27290000       | Fix              | 08TH AVE       | CLEMENT                  |                |                | 1                   |                | SIGNAL         |                   | ALL               |                      |                      | NEW DONE    |                  | 1999          | DONE                | NONE                 | NONE                 | NONE           | SALES TAX      |                  | 1999       |                |                     | 0                            |               | 0                      | 0                        | 1491523200       | 
| 1610      | 24800000       | Fix              | BROADWAY       | FRONT                    |                |                | 3                   |                | SIGNAL         |                   | ALL               |                      |                      | FULL DONE   | 10/99            |               | NONE                | NONE                 | DONE                 | NONE           | FEDS           |                  | 2001       |                |                     | 0                            |               | 0                      | 50                       | 1491523200       | 
```