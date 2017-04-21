# 311 Service Requests for 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-for-2007-167b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/aiww-p3af) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/aiww-p3af/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/aiww-p3af/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | aiww-p3af |
| Name | 311 Service Requests for 2007 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2007, all service requests |
| Created | 2011-10-10T21:55:59Z |
| Publication Date | 2011-10-20T18:52:04Z |

## Description

311 Service Requests for 2007. This is historical data and will not be updated.

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
| No       |                | resolution_action_updated_date | Resolution Action Updated Date | calendar_date | calendar_date |
| Yes      | series tag     | community_board                | Community Board                | text          | text          |
| Yes      | series tag     | borough                        | Borough                        | text          | text          |
| Yes      | numeric metric | x_coordinate_state_plane_      | X Coordinate (State Plane)     | number        | number        |
| Yes      | numeric metric | y_coordinate_state_plane_      | Y Coordinate (State Plane)     | number        | number        |
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
series e:aiww-p3af d:2007-02-06T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10001 t:location_type=Street t:school_name=Unspecified t:descriptor="Driver Complaint" t:status=Closed t:complaint_type="Taxi Complaint" t:agency=TLC t:facility_type=N/A t:borough=MANHATTAN t:agency_name="Taxi and Limousine Commission" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:taxi_pick_up_location=Other t:school_state=Unspecified t:park_facility_name=Unspecified t:intersection_street_1="WEST 29 STREET" t:school_region=Unspecified t:school_code=Unspecified t:community_board="05 MANHATTAN" t:school_city=Unspecified t:school_zip=Unspecified t:intersection_street_2="7 AVENUE" m:x_coordinate_state_plane_=986215 m:y_coordinate_state_plane_=211740 m:unique_key=30427

series e:aiww-p3af d:2007-01-24T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11222 t:location_type=Street t:school_name=Unspecified t:descriptor=Stop t:status=Closed t:complaint_type="Street Sign - Damaged" t:agency=DOT t:facility_type=N/A t:borough=BROOKLYN t:agency_name="Department of Transportation" t:city=BROOKLYN t:school_phone_number=Unspecified t:park_borough=BROOKLYN t:school_state=Unspecified t:park_facility_name=Unspecified t:intersection_street_1="DRIGGS AVENUE" t:school_region=Unspecified t:school_code=Unspecified t:community_board="01 BROOKLYN" t:school_city=Unspecified t:school_zip=Unspecified t:intersection_street_2="ECKFORD STREET" m:x_coordinate_state_plane_=998618 m:y_coordinate_state_plane_=202563 m:unique_key=100005

series e:aiww-p3af d:2007-02-06T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10003 t:school_name=Unspecified t:descriptor="Contact Sign Not Posted" t:status=Closed t:complaint_type="Consumer Complaint" t:street_name="2 AVENUE" t:agency=DCA t:facility_type=N/A t:borough=MANHATTAN t:agency_name="Department of Consumer Affairs" t:cross_street_2="EAST 6 STREET" t:cross_street_1="EAST 5 STREET" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="03 MANHATTAN" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=987381 m:y_coordinate_state_plane_=204211 m:unique_key=101376
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:aiww-p3af l:"311 Service Requests for 2007" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/aiww-p3af

property e:aiww-p3af t:meta.view v:id=aiww-p3af v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2007" v:attribution=311

property e:aiww-p3af t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:aiww-p3af t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                             | complaint_type                | descriptor                       | location_type              | incident_zip | incident_address     | street_name     | cross_street_1    | cross_street_2  | intersection_street_1 | intersection_street_2 | address_type | city      | landmark | facility_type | status | due_date            | resolution_action_updated_date | community_board | borough     | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name             | park_borough | school_name                    | school_number | school_region | school_code | school_phone_number | school_address    | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ======================================= | ============================= | ================================ | ========================== | ============ | ==================== | =============== | ================= | =============== | ===================== | ===================== | ============ | ========= | ======== | ============= | ====== | =================== | ============================== | =============== | =========== | ========================= | ========================= | ============================== | ============ | ============================== | ============= | ============= | =========== | =================== | ================= | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 30427      | 2007-02-06T00:00:00 | 2007-03-01T00:00:00 | TLC    | Taxi and Limousine Commission           | Taxi Complaint                | Driver Complaint                 | Street                     | 10001        |                      |                 |                   |                 | WEST 29 STREET        | 7 AVENUE              | INTERSECTION | NEW YORK  |          | N/A           | Closed | 2007-02-28T00:00:00 | 2007-03-01T00:00:00            | 05 MANHATTAN    | MANHATTAN   | 986215                    | 211740                    | Unspecified                    | MANHATTAN    | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      | Other                 |                     |                          |           |                        |                 |                 |                     | 40.74785373937869  | -73.99290823133913 | 
| 100005     | 2007-01-24T00:00:00 | 2007-01-24T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged         | Stop                             | Street                     | 11222        |                      |                 |                   |                 | DRIGGS AVENUE         | ECKFORD STREET        | INTERSECTION | BROOKLYN  |          | N/A           | Closed | 2007-02-07T00:00:00 | 2007-01-24T00:00:00            | 01 BROOKLYN     | BROOKLYN    | 998618                    | 202563                    | Unspecified                    | BROOKLYN     | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.72265368779736  | -73.94816488087825 | 
| 101376     | 2007-02-06T00:00:00 | 2011-07-12T00:00:00 | DCA    | Department of Consumer Affairs          | Consumer Complaint            | Contact Sign Not Posted          |                            | 10003        | 97 2 AVENUE          | 2 AVENUE        | EAST 5 STREET     | EAST 6 STREET   |                       |                       | ADDRESS      | NEW YORK  |          | N/A           | Closed | 2007-03-15T00:00:00 | 2007-02-07T00:00:00            | 03 MANHATTAN    | MANHATTAN   | 987381                    | 204211                    | Unspecified                    | MANHATTAN    | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.727188161896876 | -73.98870359185675 | 
| 100677     | 2007-02-06T00:00:00 | 2007-02-07T00:00:00 | DOT    | Department of Transportation            | Ferry Inquiry                 | Lost and Found                   | Ferry                      |              |                      |                 |                   |                 |                       |                       |              |           |          | N/A           | Closed | 2007-03-08T00:00:00 | 2007-02-07T00:00:00            | 0 Unspecified   | Unspecified |                           |                           | Unspecified                    | Unspecified  | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 | Manhattan Bound | Unknown             |                    |                    | 
| 170532     | 2007-01-26T00:00:00 | 2007-02-08T00:00:00 | DOT    | Department of Transportation            | Broken Parking Meter          | Timer Defect - Fast/Fail         | Street                     | 10029        | 1465 MADISON AVENUE  | MADISON AVENUE  | EAST 99 STREET    | EAST 101 STREET |                       |                       | ADDRESS      | NEW YORK  |          | N/A           | Closed | 2007-02-15T00:00:00 | 2007-02-08T00:00:00            | 11 MANHATTAN    | MANHATTAN   | 997527                    | 227136                    | Unspecified                    | MANHATTAN    | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.790102001126805 | -73.95205233216204 | 
| 170533     | 2007-01-26T00:00:00 | 2007-01-29T00:00:00 | DOHMH  | Department of Health and Mental Hygiene | Food Establishment            | Food Spoiled                     | Restaurant/Bar/Deli/Bakery | 10002        | 53 HESTER STREET     | HESTER STREET   | ESSEX STREET      | LUDLOW STREET   |                       |                       | ADDRESS      | NEW YORK  |          | N/A           | Closed | 2007-03-04T00:00:00 | 2007-01-29T00:00:00            | 03 MANHATTAN    | MANHATTAN   | 986979                    | 200019                    | Unspecified                    | MANHATTAN    | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.71568226714105  | -73.99015567675463 | 
| 170534     | 2007-01-26T00:00:00 | 2007-01-30T00:00:00 | DOE    | Central - Department of Education       | Teaching/Learning/Instruction | Adult and Continuing Education   | School                     | 11221        | 616 QUINCY STREET    | QUINCY STREET   | STUYVESANT AVENUE | LEWIS AVENUE    |                       |                       |              | BROOKLYN  |          | N/A           | Closed | 2007-01-31T00:00:00 | 2007-01-30T00:00:00            | 03 BROOKLYN     | BROOKLYN    | 1002138                   | 190193                    | School - PS 308 Clara Cardwell | BROOKLYN     | School - PS 308 Clara Cardwell | 308           | Region 8      | 16K308      | 7185742373          | 616 Quincy Street | BROOKLYN    | NY           | 11221       | N                | School                       |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.68869454540455  | -73.93549871865369 | 
| 169349     | 2007-01-23T00:00:00 | 2007-01-23T00:00:00 | NYPD   | New York City Police Department         | Graffiti                      | Police Report Requested          | Store/Commercial           | 11385        | 71-02 FOREST AVENUE  | FOREST AVENUE   | GEORGE STREET     | STEPHEN STREET  |                       |                       | ADDRESS      | RIDGEWOOD |          | Precinct      | Closed | 2007-01-23T00:00:00 | 2007-01-23T00:00:00            | 05 QUEENS       | QUEENS      | 1011952                   | 194476                    | Unspecified                    | QUEENS       | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.70042510413209  | -73.90009340766889 | 
| 169350     | 2007-01-23T00:00:00 | 2007-02-08T00:00:00 | DCA    | Department of Consumer Affairs          | Consumer Complaint            | Damaged/Defective Goods          |                            | 10472        |                      |                 |                   |                 | WHITE PLAINS ROAD     | BRUCKNER BOULEVARD    | INTERSECTION | BRONX     |          | N/A           | Closed | 2007-02-07T00:00:00 | 2007-01-23T00:00:00            | 09 BRONX        | BRONX       | 1023078                   | 240343                    | Unspecified                    | BRONX        | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.82627619146205  | -73.85970288046927 | 
| 169357     | 2007-01-24T00:00:00 | 2007-04-06T00:00:00 | DOHMH  | Department of Health and Mental Hygiene | Tattooing                     | Dirty/Inadequate Equip./Facility | Tattoo Parlor              | 10459        | 1093 EAST 165 STREET | EAST 165 STREET | HOE AVENUE        | FAILE STREET    |                       |                       | ADDRESS      | BRONX     |          | N/A           | Closed | 2007-03-02T00:00:00 | 2007-04-06T00:00:00            | 02 BRONX        | BRONX       | 1014728                   | 239916                    | Unspecified                    | BRONX        | Unspecified                    | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.825136958430804 | -73.88987581900433 | 
```