# Connecticut Fire Department Incidents - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-fire-department-incidents-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/axrk-twst) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/axrk-twst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/axrk-twst/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | axrk-twst |
| Name | Connecticut Fire Department Incidents - 2014 |
| Attribution | FEMA / National Fire Incident Reporting System (NFIRS) |
| Category | Public Safety |
| Tags | fire, ems |
| Created | 2015-09-30T18:34:42Z |
| Publication Date | 2015-10-01T13:11:43Z |

## Description

Incidents reported by Connecticut fire departments on the full range of their activities, from fire to emergency medical services (EMS) to equipment involved in the response.
See the attached documents, under the 'About' tab, for more information.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | series tag     | incident_id                        | Incident Id                        | text          | number        |
| Yes      | series tag     | incident_status                    | Incident Status                    | text          | text          |
| Yes      | time           | incident_date                      | Incident Date                      | calendar_date | calendar_date |
| Yes      | series tag     | incident_type_code                 | Incident Type Code                 | text          | text          |
| Yes      | series tag     | incident_type_code_description     | Incident Type Code Description     | text          | text          |
| No       |                | address_on_wildland                | Address on Wildland                | text          | text          |
| Yes      | series tag     | mutual_aid_flag                    | Mutual Aid Flag                    | text          | text          |
| Yes      | series tag     | mutual_aid_flag_description        | Mutual Aid Flag Description        | text          | text          |
| No       |                | alarm_date                         | Alarm Date                         | calendar_date | calendar_date |
| No       |                | arrival_date                       | Arrival Date                       | calendar_date | calendar_date |
| No       |                | controlled_date                    | Controlled Date                    | calendar_date | calendar_date |
| No       |                | last_unit_cleared_date             | Last Unit Cleared Date             | calendar_date | calendar_date |
| Yes      | series tag     | shift                              | Shift                              | text          | text          |
| Yes      | series tag     | alarms                             | Alarms                             | text          | text          |
| Yes      | numeric metric | apparatus_suppression              | Apparatus Suppression              | number        | number        |
| Yes      | numeric metric | apparatus_ems                      | Apparatus EMS                      | number        | number        |
| Yes      | numeric metric | apparatus_other                    | Apparatus Other                    | number        | number        |
| Yes      | numeric metric | personnel_suppression              | Personnel Suppression              | number        | number        |
| Yes      | numeric metric | personnel_ems                      | Personnel EMS                      | number        | number        |
| Yes      | numeric metric | personnel_other                    | Personnel Other                    | number        | number        |
| Yes      | series tag     | inc_mutual_aid                     | Inc Mutual Aid                     | text          | text          |
| Yes      | numeric metric | loss_property                      | Loss Property                      | number        | number        |
| Yes      | numeric metric | loss_other                         | Loss Other                         | number        | number        |
| Yes      | numeric metric | loss_total                         | Loss Total                         | number        | number        |
| Yes      | numeric metric | value_property                     | Value Property                     | number        | number        |
| Yes      | numeric metric | value_other                        | Value Other                        | number        | number        |
| Yes      | series tag     | fire_department_fatalities         | Fire Department Fatalities         | text          | number        |
| Yes      | numeric metric | fatal_other                        | Fatal Other                        | number        | number        |
| Yes      | series tag     | fire_department_non_fatal          | Fire Department Non Fatal          | text          | number        |
| Yes      | numeric metric | non_fatal_other                    | Non Fatal Other                    | number        | number        |
| Yes      | series tag     | detector_code                      | Detector Code                      | text          | text          |
| Yes      | series tag     | dector_code_description            | Dector Code Description            | text          | text          |
| Yes      | series tag     | hazmat_released_code               | HazMat Released Code               | text          | text          |
| Yes      | series tag     | hazmat_released_description        | HazMat Released Code Description   | text          | text          |
| Yes      | series tag     | mixed_use_code                     | Mixed Use Code                     | text          | text          |
| Yes      | series tag     | mixed_use_description              | Mixed Use Code Description         | text          | text          |
| Yes      | series tag     | property_use_code                  | Property Use Code                  | text          | text          |
| Yes      | series tag     | propery_use_code_description       | Propery Use Code Description       | text          | text          |
| Yes      | series tag     | fire_department_name               | Fire Department Name               | text          | text          |
| Yes      | series tag     | fire_department_zip                | Fire Department Zip                | text          | number        |
| Yes      | series tag     | incident_location_type             | Incident Location Type             | text          | text          |
| Yes      | series tag     | incident_location_type_description | Incident Location Type Description | text          | text          |
```

## Time Field

```ls
Value = incident_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_on_wildland,alarm_date,arrival_date,controlled_date,last_unit_cleared_date
```

## Data Commands

```ls
series e:axrk-twst d:2014-11-13T00:00:00.000Z t:incident_location_type=1 t:incident_type_code=550 t:fire_department_name="RIVERTON VOLUNTEER FIRE DEPT." t:mutual_aid_flag_description="Automatic aid given. Includes departments automatically dispatched to give aid to an outside fire service entity based on a prior agreement between two jurisdictions." t:fire_department_non_fatal=0 t:mutual_aid_flag=4 t:inc_mutual_aid=N t:incident_id=332 t:fire_department_zip=6063 t:alarms=0 t:incident_status=V t:fire_department_fatalities=0 t:incident_type_code_description="Public service assistance, other." t:incident_location_type_description="Street address" m:apparatus_other=0 m:personnel_ems=0 m:fatal_other=0 m:apparatus_suppression=0 m:apparatus_ems=0 m:loss_total=0 m:non_fatal_other=0 m:personnel_suppression=0 m:personnel_other=5

series e:axrk-twst d:2014-05-22T00:00:00.000Z t:incident_location_type=3 t:incident_type_code=550 t:fire_department_name="ROXBURY VOLUNTEER FIRE DEPT." t:detector_code=U t:property_use_code=131 t:mutual_aid_flag_description="No aid given or received." t:fire_department_non_fatal=0 t:mutual_aid_flag=N t:fire_department_zip=6058 t:inc_mutual_aid=N t:incident_id=3753 t:incident_status=V t:hazmat_released_code=N t:fire_department_fatalities=0 t:incident_type_code_description="Public service assistance, other." t:hazmat_released_description="No HazMat involved." t:incident_location_type_description="In front of" t:propery_use_code_description="Church, mosque. Includes synagogues, temples, chapels, religious educational facilities, and church halls." t:dector_code_description=Unknown m:loss_other=0 m:apparatus_other=1 m:personnel_ems=0 m:fatal_other=0 m:apparatus_suppression=0 m:apparatus_ems=0 m:loss_total=0 m:value_other=0 m:loss_property=0 m:non_fatal_other=0 m:value_property=0 m:personnel_suppression=0 m:personnel_other=1

series e:axrk-twst d:2014-11-26T00:00:00.000Z t:incident_location_type=1 t:incident_type_code=550 t:fire_department_name="SHARON FIRE DEPARTMENT" t:mutual_aid_flag_description="No aid given or received." t:fire_department_non_fatal=0 t:property_use_code=960 t:mutual_aid_flag=N t:fire_department_zip=6057 t:inc_mutual_aid=N t:incident_id=4009 t:alarms=0 t:incident_status=V t:fire_department_fatalities=0 t:incident_type_code_description="Public service assistance, other." t:incident_location_type_description="Street address" t:propery_use_code_description="Street, other." m:apparatus_other=1 m:personnel_ems=0 m:fatal_other=0 m:apparatus_suppression=0 m:apparatus_ems=0 m:loss_total=0 m:non_fatal_other=0 m:personnel_suppression=0 m:personnel_other=11
```

## Meta Commands

```ls
metric m:apparatus_suppression p:integer l:"Apparatus Suppression" d:"The total number of fire department suppression apparatus that responded to the incident." t:dataTypeName=number

metric m:apparatus_ems p:integer l:"Apparatus EMS" d:"The total number of fire department EMS apparatus that responded to the incident." t:dataTypeName=number

metric m:apparatus_other p:integer l:"Apparatus Other" d:"The total number of fire department other apparatus that responded to the incident. Chief officer vehicles and privately owned vehicles should be counted as ""Other.""" t:dataTypeName=number

metric m:personnel_suppression p:integer l:"Personnel Suppression" d:"The total number of fire department suppression personnel that responded to the incident." t:dataTypeName=number

metric m:personnel_ems p:integer l:"Personnel EMS" d:"The total number of fire department EMS personnel that responded to the incident." t:dataTypeName=number

metric m:personnel_other p:integer l:"Personnel Other" d:"The total number of fire department other personnel that responded to the incident." t:dataTypeName=number

metric m:loss_property p:integer l:"Loss Property" d:"Rough estimation of the total loss to the structure in terms of the cost of replacement in like kind and quantity." t:dataTypeName=number

metric m:loss_other p:integer l:"Loss Other" d:"Rough estimation of the total loss to the contents in terms of the cost of replacement in like kind and quantity. This estimation of the fire loss includes contents damaged by fire, smoke, water, and overhaul." t:dataTypeName=number

metric m:loss_total p:integer l:"Loss Total" t:dataTypeName=number

metric m:value_property p:integer l:"Value Property" d:"Estimation of the replacement cost of the structure." t:dataTypeName=number

metric m:value_other p:integer l:"Value Other" d:"Estimation of the replacement cost of the contents." t:dataTypeName=number

metric m:fatal_other p:integer l:"Fatal Other" t:dataTypeName=number

metric m:non_fatal_other p:integer l:"Non Fatal Other" t:dataTypeName=number

entity e:axrk-twst l:"Connecticut Fire Department Incidents - 2014" t:attribution="FEMA / National Fire Incident Reporting System (NFIRS)" t:url=https://data.ct.gov/api/views/axrk-twst

property e:axrk-twst t:meta.view v:id=axrk-twst v:category="Public Safety" v:attributionLink=http://www.usfa.fema.gov/data/nfirs/ v:averageRating=0 v:name="Connecticut Fire Department Incidents - 2014" v:attribution="FEMA / National Fire Incident Reporting System (NFIRS)"

property e:axrk-twst t:meta.view.license v:name="Public Domain"

property e:axrk-twst t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:axrk-twst t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| incident_id | incident_status | incident_date       | incident_type_code | incident_type_code_description    | address_on_wildland | mutual_aid_flag | mutual_aid_flag_description                                                                                                                                            | alarm_date          | arrival_date        | controlled_date     | last_unit_cleared_date | shift | alarms | apparatus_suppression | apparatus_ems | apparatus_other | personnel_suppression | personnel_ems | personnel_other | inc_mutual_aid | loss_property | loss_other | loss_total | value_property | value_other | fire_department_fatalities | fatal_other | fire_department_non_fatal | non_fatal_other | detector_code | dector_code_description | hazmat_released_code | hazmat_released_description | mixed_use_code | mixed_use_description                                      | property_use_code | propery_use_code_description                                                                               | fire_department_name          | fire_department_zip | incident_location_type | incident_location_type_description | 
| =========== | =============== | =================== | ================== | ================================= | =================== | =============== | ====================================================================================================================================================================== | =================== | =================== | =================== | ====================== | ===== | ====== | ===================== | ============= | =============== | ===================== | ============= | =============== | ============== | ============= | ========== | ========== | ============== | =========== | ========================== | =========== | ========================= | =============== | ============= | ======================= | ==================== | =========================== | ============== | ========================================================== | ================= | ========================================================================================================== | ============================= | =================== | ====================== | ================================== | 
| 332         | V               | 2014-11-13T00:00:00 | 550                | Public service assistance, other. | N                   | 4               | Automatic aid given. Includes departments automatically dispatched to give aid to an outside fire service entity based on a prior agreement between two jurisdictions. | 2014-11-13T15:57:00 | 2014-11-13T16:05:00 | 2014-11-13T17:04:00 | 2014-11-13T17:04:00    |       | 0      | 0                     | 0             | 0               | 0                     | 0             | 5               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         |                      |                             |                |                                                            |                   |                                                                                                            | RIVERTON VOLUNTEER FIRE DEPT. | 6063                | 1                      | Street address                     | 
| 3753        | V               | 2014-05-22T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-05-22T10:28:00 | 2014-05-22T10:28:00 |                     | 2014-05-22T14:26:00    |       |        | 0                     | 0             | 1               | 0                     | 0             | 1               | N              | 0             | 0          | 0          | 0              | 0           | 0                          | 0           | 0                         | 0               | U             | Unknown                 | N                    | No HazMat involved.         |                |                                                            | 131               | Church, mosque. Includes synagogues, temples, chapels, religious educational facilities, and church halls. | ROXBURY VOLUNTEER FIRE DEPT.  | 6058                | 3                      | In front of                        | 
| 4009        | V               | 2014-11-26T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-11-26T19:14:00 | 2014-11-26T19:32:00 |                     | 2014-11-26T19:44:00    |       | 0      | 0                     | 0             | 1               | 0                     | 0             | 11              | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         |                      |                             |                |                                                            | 960               | Street, other.                                                                                             | SHARON FIRE DEPARTMENT        | 6057                | 1                      | Street address                     | 
| 4160        | V               | 2014-06-04T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-06-04T09:38:00 | 2014-06-04T09:38:00 |                     | 2014-06-04T09:38:00    |       | 0      | 1                     | 0             | 0               | 0                     | 0             | 0               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         | N                    | No HazMat involved.         | NN             | Not mixed use. Incident property consists of a single use. | 131               | Church, mosque. Includes synagogues, temples, chapels, religious educational facilities, and church halls. | TERRYVILLE FIRE DEPT.         | 6786                | 2                      | Intersection                       | 
| 4161        | V               | 2014-06-04T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-06-04T09:39:00 | 2014-06-04T09:40:00 |                     | 2014-06-04T09:40:00    |       | 0      | 1                     | 0             | 0               | 0                     | 0             | 0               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         | N                    | No HazMat involved.         | NN             | Not mixed use. Incident property consists of a single use. | 131               | Church, mosque. Includes synagogues, temples, chapels, religious educational facilities, and church halls. | TERRYVILLE FIRE DEPT.         | 6786                | 2                      | Intersection                       | 
| 4166        | V               | 2014-06-09T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-06-09T18:32:00 | 2014-06-09T18:33:00 |                     | 2014-06-09T21:29:00    |       | 0      | 5                     | 0             | 0               | 0                     | 0             | 0               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         | N                    | No HazMat involved.         | NN             | Not mixed use. Incident property consists of a single use. | 200               | Educational, other.                                                                                        | TERRYVILLE FIRE DEPT.         | 6786                | 1                      | Street address                     | 
| 4291        | V               | 2014-02-21T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-02-21T23:10:00 | 2014-02-21T23:15:00 |                     | 2014-02-21T23:37:00    |       | 0      | 0                     | 0             | 2               | 0                     | 0             | 16              | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         |                      |                             |                |                                                            | 961               | Highway or divided highway. Includes limited-access highways with few intersections or at grade crossings. | THOMASTON FIRE DEPT.          | 6787                | 1                      | Street address                     | 
| 5182        | V               | 2014-04-20T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-04-20T13:37:00 | 2014-04-20T13:46:00 |                     | 2014-04-20T13:48:00    |       | 1S     | 1                     | 0             | 0               | 1                     | 0             | 0               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         | N                    | No HazMat involved.         | NN             | Not mixed use. Incident property consists of a single use. | NNN               | None.                                                                                                      | TORRINGTON FIRE DEPT.         | 6790                | 1                      | Street address                     | 
| 7395        | V               | 2014-03-15T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-03-15T08:33:00 | 2014-03-15T08:35:00 |                     | 2014-03-15T08:58:00    |       | 0      | 0                     | 0             | 2               | 0                     | 0             | 29              | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         |                      |                             |                |                                                            | 963               | Street or road in commercial area.                                                                         | WATERTOWN FIRE DEPT.          | 6795                | 2                      | Intersection                       | 
| 4562        | V               | 2014-01-09T00:00:00 | 550                | Public service assistance, other. | N                   | N               | No aid given or received.                                                                                                                                              | 2014-01-09T14:19:00 | 2014-01-09T14:26:00 |                     | 2014-01-09T14:46:00    |       | 1      | 1                     | 0             | 0               | 4                     | 0             | 0               | N              |               |            | 0          |                |             | 0                          | 0           | 0                         | 0               |               |                         | N                    | No HazMat involved.         | NN             | Not mixed use. Incident property consists of a single use. | 215               | High school, junior high, middle school.                                                                   | TORRINGTON FIRE DEPT.         | 6790                | 1                      | Street address                     | 
```