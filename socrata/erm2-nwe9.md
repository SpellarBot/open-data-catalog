# 311 Service Requests from 2010 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-from-2010-to-present-66980) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/erm2-nwe9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/erm2-nwe9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/erm2-nwe9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | erm2-nwe9 |
| Name | 311 Service Requests from 2010 to Present |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, city government, socialservices, 2010, 2011, 2012, service request status, all service requests |
| Created | 2011-10-10T05:52:17Z |
| Publication Date | 2017-02-02T00:05:07Z |

## Description

All 311 Service Requests from 2010 to present. This information is automatically updated daily.

Click here to download data from 2011 - https://data.cityofnewyork.us/dataset/311-Service-Requests-From-2011/fpz8-jqf4

Click here to download data from 2012 - https://data.cityofnewyork.us/dataset/311-Service-Requests-From-2012/as38-8eb5

Click here to download data from 2013 - https://data.cityofnewyork.us/dataset/311-Service-Requests-From-2013/hybb-af8n

Click here to download data from 2014 - https://data.cityofnewyork.us/dataset/311-Service-Requests-From-2014/vtzg-7562

Click here to download data from 2015 - https://data.cityofnewyork.us/dataset/311-Service-Requests-From-2015/57g5-etyj

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | numeric metric | unique_key                     | Unique Key                     | number        | text          |
| Yes      | time           | created_date                   | Created Date                   | calendar_date | calendar_date |
| No       |                | closed_date                    | Closed Date                    | calendar_date | calendar_date |
| Yes      | series tag     | agency                         | Agency                         | text          | text          |
| Yes      | series tag     | agency_name                    | Agency Name                    | text          | text          |
| Yes      | series tag     | complaint_type                 | Complaint Type                 | text          | text          |
| Yes      | series tag     | descriptor                     | Descriptor                     | text          | text          |
| Yes      | series tag     | location_type                  | Location Type                  | text          | text          |
| Yes      | series tag     | incident_zip                   | Incident Zip                   | text          | text          |
| No       |                | incident_address               | Incident Address               | text          | text          |
| Yes      | series tag     | street_name                    | Street Name                    | text          | text          |
| Yes      | series tag     | cross_street_1                 | Cross Street 1                 | text          | text          |
| Yes      | series tag     | cross_street_2                 | Cross Street 2                 | text          | text          |
| Yes      | series tag     | intersection_street_1          | Intersection Street 1          | text          | text          |
| Yes      | series tag     | intersection_street_2          | Intersection Street 2          | text          | text          |
| No       |                | address_type                   | Address Type                   | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | landmark                       | Landmark                       | text          | text          |
| Yes      | series tag     | facility_type                  | Facility Type                  | text          | text          |
| Yes      | series tag     | status                         | Status                         | text          | text          |
| No       |                | due_date                       | Due Date                       | calendar_date | calendar_date |
| Yes      | series tag     | resolution_description         | Resolution Description         | text          | text          |
| No       |                | resolution_action_updated_date | Resolution Action Updated Date | calendar_date | calendar_date |
| Yes      | series tag     | community_board                | Community Board                | text          | text          |
| Yes      | series tag     | borough                        | Borough                        | text          | text          |
| Yes      | numeric metric | x_coordinate_state_plane       | X Coordinate (State Plane)     | number        | number        |
| Yes      | numeric metric | y_coordinate_state_plane       | Y Coordinate (State Plane)     | number        | number        |
| Yes      | series tag     | park_facility_name             | Park Facility Name             | text          | text          |
| Yes      | series tag     | park_borough                   | Park Borough                   | text          | text          |
| Yes      | series tag     | school_name                    | School Name                    | text          | text          |
| Yes      | series tag     | school_number                  | School Number                  | text          | text          |
| Yes      | series tag     | school_region                  | School Region                  | text          | text          |
| Yes      | series tag     | school_code                    | School Code                    | text          | text          |
| Yes      | series tag     | school_phone_number            | School Phone Number            | text          | text          |
| No       |                | school_address                 | School Address                 | text          | text          |
| Yes      | series tag     | school_city                    | School City                    | text          | text          |
| Yes      | series tag     | school_state                   | School State                   | text          | text          |
| Yes      | series tag     | school_zip                     | School Zip                     | text          | text          |
| Yes      | series tag     | school_not_found               | School Not Found               | text          | text          |
| Yes      | series tag     | school_or_citywide_complaint   | School or Citywide Complaint   | text          | text          |
| Yes      | series tag     | vehicle_type                   | Vehicle Type                   | text          | text          |
| Yes      | series tag     | taxi_company_borough           | Taxi Company Borough           | text          | text          |
| Yes      | series tag     | taxi_pick_up_location          | Taxi Pick Up Location          | text          | text          |
| Yes      | series tag     | bridge_highway_name            | Bridge Highway Name            | text          | text          |
| Yes      | series tag     | bridge_highway_direction       | Bridge Highway Direction       | text          | text          |
| Yes      | series tag     | road_ramp                      | Road Ramp                      | text          | text          |
| Yes      | series tag     | bridge_highway_segment         | Bridge Highway Segment         | text          | text          |
| Yes      | series tag     | garage_lot_name                | Garage Lot Name                | text          | text          |
| Yes      | series tag     | ferry_direction                | Ferry Direction                | text          | text          |
| Yes      | series tag     | ferry_terminal_name            | Ferry Terminal Name            | text          | text          |
| No       |                | latitude                       | Latitude                       | number        | number        |
| No       |                | longitude                      | Longitude                      | number        | number        |
```

## Time Field

```ls
Value = created_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed_date,incident_address,address_type,due_date,resolution_action_updated_date,school_address,latitude,longitude
```

## Data Commands

```ls
series e:erm2-nwe9 d:2010-10-21T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10457 t:location_type="RESIDENTIAL BUILDING" t:school_name=Unspecified t:descriptor=RUBBISH t:status=Closed t:complaint_type=NONCONST t:street_name="RYER AVENUE" t:agency=HPD t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Housing Preservation and Development" t:cross_street_2="EAST 182 STREET" t:cross_street_1="EAST 181 STREET" t:city=BRONX t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:resolution_description="The Department of Housing Preservation and Development inspected the following conditions. No violations were issued. The complaint has been closed." t:school_region=Unspecified t:school_code=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane=1011886 m:y_coordinate_state_plane=250661 m:unique_key=18951796

series e:erm2-nwe9 d:2010-10-21T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10457 t:location_type="RESIDENTIAL BUILDING" t:school_name=Unspecified t:descriptor=RADIATOR t:status=Closed t:complaint_type=PLUMBING t:street_name="GRAND CONCOURSE" t:agency=HPD t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Housing Preservation and Development" t:cross_street_2="EAST 172 STREET" t:cross_street_1="EAST 171 STREET" t:city=BRONX t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:resolution_description="The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd." t:school_region=Unspecified t:school_code=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane=1008379 m:y_coordinate_state_plane=245547 m:unique_key=18951797

series e:erm2-nwe9 d:2010-10-21T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10027 t:location_type="RESIDENTIAL BUILDING" t:school_name=Unspecified t:descriptor=FLOOR t:status=Closed t:complaint_type="GENERAL CONSTRUCTION" t:street_name="ST NICHOLAS AVENUE" t:agency=HPD t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Housing Preservation and Development" t:cross_street_2="WEST 133 STREET" t:cross_street_1="WEST 130 STREET" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:resolution_description="The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd." t:school_region=Unspecified t:school_code=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane=998270 m:y_coordinate_state_plane=236014 m:unique_key=18951798
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" d:"Unique identifier of a Service Request (SR) in the open data set" t:dataTypeName=number

metric m:x_coordinate_state_plane p:integer l:"X Coordinate (State Plane)" d:"Geo validated, X coordinate of the incident location." t:dataTypeName=number

metric m:y_coordinate_state_plane p:integer l:"Y Coordinate (State Plane)" d:"Geo validated, Y coordinate of the incident location." t:dataTypeName=number

entity e:erm2-nwe9 l:"311 Service Requests from 2010 to Present" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/erm2-nwe9

property e:erm2-nwe9 t:meta.view v:id=erm2-nwe9 v:category="Social Services" v:averageRating=0 v:name="311 Service Requests from 2010 to Present" v:attribution=311

property e:erm2-nwe9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:erm2-nwe9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                                        | complaint_type       | descriptor      | location_type        | incident_zip | incident_address       | street_name        | cross_street_1  | cross_street_2  | intersection_street_1 | intersection_street_2 | address_type | city     | landmark | facility_type | status | due_date | resolution_description                                                                                                                                                                                                                                     | resolution_action_updated_date | community_board | borough     | x_coordinate_state_plane | y_coordinate_state_plane | park_facility_name | park_borough | school_name | school_number | school_region | school_code | school_phone_number | school_address | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ================================================== | ==================== | =============== | ==================== | ============ | ====================== | ================== | =============== | =============== | ===================== | ===================== | ============ | ======== | ======== | ============= | ====== | ======== | ========================================================================================================================================================================================================================================================== | ============================== | =============== | =========== | ======================== | ======================== | ================== | ============ | =========== | ============= | ============= | =========== | =================== | ============== | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 18951796   | 2010-10-21T00:00:00 | 2010-10-28T00:00:00 | HPD    | Department of Housing Preservation and Development | NONCONST             | RUBBISH         | RESIDENTIAL BUILDING | 10457        | 2170 RYER AVENUE       | RYER AVENUE        | EAST 181 STREET | EAST 182 STREET |                       |                       | ADDRESS      | BRONX    |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. No violations were issued. The complaint has been closed.                                                                                                       | 2010-10-28T00:00:00            | 0 Unspecified   | Unspecified | 1011886                  | 250661                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.85463818541571  | -73.90010034716846 | 
| 18951797   | 2010-10-21T00:00:00 | 2010-10-25T00:00:00 | HPD    | Department of Housing Preservation and Development | PLUMBING             | RADIATOR        | RESIDENTIAL BUILDING | 10457        | 1466 GRAND CONCOURSE   | GRAND CONCOURSE    | EAST 171 STREET | EAST 172 STREET |                       |                       | ADDRESS      | BRONX    |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd.                                                                  | 2010-10-25T00:00:00            | 0 Unspecified   | Unspecified | 1008379                  | 245547                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.840612050743175 | -73.91279597705399 | 
| 18951798   | 2010-10-21T00:00:00 | 2010-11-01T00:00:00 | HPD    | Department of Housing Preservation and Development | GENERAL CONSTRUCTION | FLOOR           | RESIDENTIAL BUILDING | 10027        | 422 ST NICHOLAS AVENUE | ST NICHOLAS AVENUE | WEST 130 STREET | WEST 133 STREET |                       |                       | ADDRESS      | NEW YORK |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd.                                                                  | 2010-11-01T00:00:00            | 0 Unspecified   | Unspecified | 998270                   | 236014                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.81446852634858  | -73.94935057418112 | 
| 18951799   | 2010-10-21T00:00:00 | 2010-11-01T00:00:00 | HPD    | Department of Housing Preservation and Development | GENERAL CONSTRUCTION | FLOOR           | RESIDENTIAL BUILDING | 10027        | 422 ST NICHOLAS AVENUE | ST NICHOLAS AVENUE | WEST 130 STREET | WEST 133 STREET |                       |                       | ADDRESS      | NEW YORK |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. No violations were issued. The complaint has been closed.                                                                                                       | 2010-11-01T00:00:00            | 0 Unspecified   | Unspecified | 998270                   | 236014                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.81446852634858  | -73.94935057418112 | 
| 18951800   | 2010-10-21T00:00:00 | 2010-11-03T00:00:00 | HPD    | Department of Housing Preservation and Development | GENERAL CONSTRUCTION | DOORS           | RESIDENTIAL BUILDING | 11225        | 1119 CARROLL STREET    | CARROLL STREET     | ROGERS AVENUE   | NOSTRAND AVENUE |                       |                       | ADDRESS      | BROOKLYN |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd.                                                                  | 2010-11-03T00:00:00            | 0 Unspecified   | Unspecified | 997465                   | 182387                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.66727705470382  | -73.95236411569952 | 
| 18951801   | 2010-10-21T00:00:00 | 2010-10-25T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING              | HEAT            | RESIDENTIAL BUILDING | 10460        | 1531 TAYLOR AVENUE     | TAYLOR AVENUE      | ARCHER STREET   | GUERLAIN STREET |                       |                       | ADDRESS      | BRONX    |          | N/A           | Closed |          | The Department of Housing Preservation and Development responded to a complaint of no heat or hot water and was advised by a tenant in the building that heat and hot water had been restored. If the condition still exists, please file a new complaint. | 2010-10-25T00:00:00            | 0 Unspecified   | Unspecified | 1021178                  | 244770                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.83843516720237  | -73.86654376469986 | 
| 18951802   | 2010-10-21T00:00:00 | 2010-12-14T00:00:00 | HPD    | Department of Housing Preservation and Development | APPLIANCE            | REFRIGERATOR    | RESIDENTIAL BUILDING | 10034        | 25 VERMILYEA AVENUE    | VERMILYEA AVENUE   | DYCKMAN STREET  | ACADEMY STREET  |                       |                       | ADDRESS      | NEW YORK |          | N/A           | Closed |          | The Department of Housing Preservation and Development was not able to gain access to inspect the following conditions. The complaint has been closed. If the condition still exists, please file a new complaint.                                         | 2010-12-14T00:00:00            | 0 Unspecified   | Unspecified | 1004849                  | 254403                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.86492806954402  | -73.92552644507623 | 
| 18951804   | 2010-10-21T00:00:00 | 2010-11-12T00:00:00 | HPD    | Department of Housing Preservation and Development | NONCONST             | VERMIN          | RESIDENTIAL BUILDING | 11225        | 1119 CARROLL STREET    | CARROLL STREET     | ROGERS AVENUE   | NOSTRAND AVENUE |                       |                       | ADDRESS      | BROOKLYN |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. No violations were issued. The complaint has been closed.                                                                                                       | 2010-11-12T00:00:00            | 0 Unspecified   | Unspecified | 997465                   | 182387                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.66727705470382  | -73.95236411569952 | 
| 18951805   | 2010-10-21T00:00:00 | 2010-10-25T00:00:00 | HPD    | Department of Housing Preservation and Development | NONCONST             | CARBON MONOXIDE | RESIDENTIAL BUILDING | 10463        | 3018 HEATH AVENUE      | HEATH AVENUE       | WEST 230 STREET | ALBANY CRESCENT |                       |                       | ADDRESS      | BRONX    |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. Violations were issued. Information about specific violations is available at www.nyc.gov/hpd.                                                                  | 2010-10-25T00:00:00            | 0 Unspecified   | Unspecified | 1011122                  | 258546                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.87628246342609  | -73.9028304631379  | 
| 18951806   | 2010-10-21T00:00:00 | 2010-10-29T00:00:00 | HPD    | Department of Housing Preservation and Development | PAINT - PLASTER      | CEILING         | RESIDENTIAL BUILDING | 11225        | 1141 PRESIDENT STREET  | PRESIDENT STREET   | ROGERS AVENUE   | NOSTRAND AVENUE |                       |                       | ADDRESS      | BROOKLYN |          | N/A           | Closed |          | The Department of Housing Preservation and Development inspected the following conditions. No violations were issued. The complaint has been closed.                                                                                                       | 2010-10-29T00:00:00            | 0 Unspecified   | Unspecified | 997438                   | 182716                   | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.66818012654851  | -73.9524607985058  | 
```