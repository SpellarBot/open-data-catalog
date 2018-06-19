# 311 Service Requests for 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-for-2004-1d4d5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sqcr-6mww) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sqcr-6mww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sqcr-6mww/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sqcr-6mww |
| Name | 311 Service Requests for 2004 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2004, all service requests |
| Created | 2011-10-10T05:02:42Z |
| Publication Date | 2011-10-20T19:02:49Z |

## Description

311 Service Requests for 2004. This is historical data and will not be updated.

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
series e:sqcr-6mww d:2004-04-02T00:00:00.000Z t:school_number=Unspecified t:school_name=Unspecified t:status=Closed t:descriptor="Cabaret License" t:complaint_type="DCA / DOH New License Application Request" t:agency=DCA t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Consumer Affairs" t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_code=Unspecified t:school_zip=Unspecified m:unique_key=111

series e:sqcr-6mww d:2004-04-02T00:00:00.000Z t:school_number=Unspecified t:school_name=Unspecified t:status=Closed t:descriptor="Day Auctioneer License" t:complaint_type="DCA / DOH New License Application Request" t:agency=DCA t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Consumer Affairs" t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_code=Unspecified t:school_zip=Unspecified m:unique_key=112

series e:sqcr-6mww d:2004-04-06T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10306 t:location_type=Street t:school_name=Unspecified t:descriptor="No Parking, Standing, Stopping" t:status=Closed t:complaint_type="Street Sign - Damaged" t:street_name="AMBOY ROAD" t:agency=DOT t:facility_type=N/A t:borough="STATEN ISLAND" t:agency_name="Department of Transportation" t:cross_street_2="BISHOP STREET" t:cross_street_1="DALE AVENUE" t:city="STATEN ISLAND" t:school_phone_number=Unspecified t:park_borough="STATEN ISLAND" t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="02 STATEN ISLAND" t:school_city=Unspecified t:school_zip=Unspecified m:unique_key=116
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:sqcr-6mww l:"311 Service Requests for 2004" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/sqcr-6mww

property e:sqcr-6mww t:meta.view v:id=sqcr-6mww v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2004" v:attribution=311

property e:sqcr-6mww t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sqcr-6mww t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                             | complaint_type                            | descriptor                     | location_type | incident_zip | incident_address | street_name     | cross_street_1 | cross_street_2 | intersection_street_1 | intersection_street_2 | address_type | city            | landmark | facility_type | status | due_date | resolution_action_updated_date | community_board  | borough       | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name | park_borough  | school_name | school_number | school_region | school_code | school_phone_number | school_address | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude          | longitude          | 
| ========== | =================== | =================== | ====== | ======================================= | ========================================= | ============================== | ============= | ============ | ================ | =============== | ============== | ============== | ===================== | ===================== | ============ | =============== | ======== | ============= | ====== | ======== | ============================== | ================ | ============= | ========================= | ========================= | ================== | ============= | =========== | ============= | ============= | =========== | =================== | ============== | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================= | ================== | 
| 111        | 2004-04-02T00:00:00 | 2004-04-06T00:00:00 | DCA    | Department of Consumer Affairs          | DCA / DOH New License Application Request | Cabaret License                |               |              |                  |                 |                |                |                       |                       |              |                 |          | N/A           | Closed |          |                                | 0 Unspecified    | Unspecified   |                           |                           | Unspecified        | Unspecified   | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     |                   |                    | 
| 112        | 2004-04-02T00:00:00 | 2004-04-06T00:00:00 | DCA    | Department of Consumer Affairs          | DCA / DOH New License Application Request | Day Auctioneer License         |               |              |                  |                 |                |                |                       |                       |              |                 |          | N/A           | Closed |          |                                | 0 Unspecified    | Unspecified   |                           |                           | Unspecified        | Unspecified   | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     |                   |                    | 
| 116        | 2004-04-06T00:00:00 | 2004-04-09T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged                     | No Parking, Standing, Stopping | Street        | 10306        | 2690 AMBOY ROAD  | AMBOY ROAD      | DALE AVENUE    | BISHOP STREET  |                       |                       | ADDRESS      | STATEN ISLAND   |          | N/A           | Closed |          | 2004-04-09T00:00:00            | 02 STATEN ISLAND | STATEN ISLAND |                           |                           | Unspecified        | STATEN ISLAND | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     |                   |                    | 
| 117        | 2004-09-13T00:00:00 | 2004-09-13T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged                     | Stop                           | Street        | 11422        |                  |                 |                |                | 148 AVENUE            | 235 STREET            | INTERSECTION | ROSEDALE        |          | N/A           | Closed |          | 2004-09-13T00:00:00            | 13 QUEENS        | QUEENS        | 1054404                   | 178256                    | Unspecified        | QUEENS        | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.65567033677405 | -73.74716073535694 | 
| 118        | 2004-04-06T00:00:00 | 2004-06-16T00:00:00 | TLC    | Taxi and Limousine Commission           | Taxi Complaint                            | Driver Complaint               |               |              |                  |                 | AVENUE D       | NEWKIRK AVENUE |                       |                       | BLOCKFACE    | BROOKLYN        |          | N/A           | Closed |          |                                | 14 BROOKLYN      | BROOKLYN      |                           |                           | Unspecified        | BROOKLYN      | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      | Other                 |                     |                          |           |                        |                 |                 |                     |                   |                    | 
| 119        | 2004-04-06T00:00:00 | 2004-04-09T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged                     | Stop                           | Street        | 10310        | BEMENT AVENUE    | BEMENT AVENUE   | DALLAS STREET  | TYLER AVENUE   |                       |                       | BLOCKFACE    | STATEN ISLAND   |          | N/A           | Closed |          | 2004-04-09T00:00:00            | 01 STATEN ISLAND | STATEN ISLAND | 953550                    | 166710                    | Unspecified        | STATEN ISLAND | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.62420374360422 | -74.11059237140697 | 
| 121        | 2004-04-10T00:00:00 | 2004-05-01T00:00:00 | DOHMH  | Department of Health and Mental Hygiene | Smoking                                   | Smoking Violation              | Pool Hall     | 11385        | 70-02 70 STREET  | 70 STREET       | 70 AVENUE      | CENTRAL AVENUE |                       |                       | ADDRESS      | JACKSON HEIGHTS |          | N/A           | Closed |          |                                | 05 QUEENS        | QUEENS        | 1016818                   | 196363                    | Unspecified        | QUEENS        | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.70558790082511 | -73.88253519011639 | 
| 131        | 2004-07-22T00:00:00 | 2004-07-23T00:00:00 | DOT    | Department of Transportation            | Street Sign - Missing                     | St Name - Attached to Pole     | Street        | 11218        |                  |                 |                |                | CONEY ISLAND AVENUE   | BEVERLY ROAD          | INTERSECTION | BROOKLYN        |          | N/A           | Closed |          | 2004-07-23T00:00:00            | 14 BROOKLYN      | BROOKLYN      | 992608                    | 173551                    | Unspecified        | BROOKLYN      | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.64303008633706 | -73.96988300943386 | 
| 132        | 2004-09-01T00:00:00 | 2004-09-01T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged                     | No Parking, Standing, Stopping | Street        | 10028        |                  |                 |                |                | 2 AVENUE              | EAST 81 STREET        | INTERSECTION | NEW YORK        |          | N/A           | Closed |          | 2004-09-01T00:00:00            | 08 MANHATTAN     | MANHATTAN     | 997094                    | 221740                    | Unspecified        | MANHATTAN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.77529205657226 | -73.95362635525348 | 
| 133        | 2004-09-04T00:00:00 | 2004-09-08T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged                     | No Parking, Standing, Stopping | Street        | 11216        | BROOKLYN AVENUE  | BROOKLYN AVENUE | BERGEN STREET  | DEAN STREET    |                       |                       | BLOCKFACE    | BROOKLYN        |          | N/A           | Closed |          | 2004-09-08T00:00:00            | 08 BROOKLYN      | BROOKLYN      | 999689                    | 185633                    | Unspecified        | BROOKLYN      | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.67618299669919 | -73.9443398681681  | 
```