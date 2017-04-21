# 311 Service Requests for 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-for-2005-f9f54) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sxmw-f24h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sxmw-f24h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sxmw-f24h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sxmw-f24h |
| Name | 311 Service Requests for 2005 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2005, all service requests |
| Created | 2011-10-11T04:01:33Z |
| Publication Date | 2011-10-20T18:58:48Z |

## Description

311 Service Requests for 2005. This is historical data and will not be updated.

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
series e:sxmw-f24h d:2005-10-22T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10007 t:location_type=Street t:bridge_highway_direction="South Bound" t:school_name=Unspecified t:descriptor="No Parking, Standing, Stopping" t:status=Closed t:complaint_type="Street Sign - Damaged" t:agency=DOT t:facility_type=N/A t:borough=MANHATTAN t:agency_name="Department of Transportation" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:school_state=Unspecified t:park_facility_name=Unspecified t:intersection_street_1="CHURCH STREET" t:school_region=Unspecified t:school_code=Unspecified t:school_city=Unspecified t:community_board="01 MANHATTAN" t:school_zip=Unspecified t:intersection_street_2="BARCLAY STREET" m:x_coordinate_state_plane_=981684 m:y_coordinate_state_plane_=199135 m:unique_key=2575

series e:sxmw-f24h d:2005-05-26T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11355 t:location_type=N/A t:school_name=Unspecified t:descriptor=N/A t:status=Closed t:complaint_type="Homeless Encampment" t:street_name="BOWNE STREET" t:agency=NYPD t:facility_type=Precinct t:borough=QUEENS t:agency_name="New York City Police Department" t:cross_street_2="LABURNUM AVENUE" t:cross_street_1="HOLLY AVENUE" t:city=FLUSHING t:school_phone_number=Unspecified t:park_borough=QUEENS t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="07 QUEENS" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=1035120 m:y_coordinate_state_plane_=213316 m:unique_key=10663

series e:sxmw-f24h d:2005-01-10T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11369 t:location_type=Highway t:bridge_highway_direction="East Bound" t:school_name=Unspecified t:descriptor="Dead Animal" t:status=Closed t:complaint_type="Highway Condition" t:agency=DOT t:facility_type=N/A t:borough=QUEENS t:agency_name="Department of Transportation" t:cross_street_2="GRND CNTRL PARKWAY ENTRANCE WB" t:cross_street_1="LA GUARDIA ACCESS ROAD" t:city="EAST ELMHURST" t:school_phone_number=Unspecified t:landmark="LA GUARDIA AIRPORT" t:park_borough=QUEENS t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:school_city=Unspecified t:community_board="80 QUEENS" t:school_zip=Unspecified m:x_coordinate_state_plane_=1019486 m:y_coordinate_state_plane_=220530 m:unique_key=34746
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" d:"Unique identifier of a Service Request (SR) in the open data set. This is NOT the Service Request (SR) # provided to the initiating customer. SR #s are not available in this data set." t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:sxmw-f24h l:"311 Service Requests for 2005" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/sxmw-f24h

property e:sxmw-f24h t:meta.view v:id=sxmw-f24h v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2005" v:attribution=311

property e:sxmw-f24h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sxmw-f24h t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                                    | complaint_type        | descriptor                     | location_type | incident_zip | incident_address      | street_name      | cross_street_1         | cross_street_2                 | intersection_street_1 | intersection_street_2 | address_type | city          | landmark           | facility_type | status | due_date | resolution_action_updated_date | community_board | borough     | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name | park_borough | school_name | school_number | school_region | school_code | school_phone_number | school_address | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ============================================== | ===================== | ============================== | ============= | ============ | ===================== | ================ | ====================== | ============================== | ===================== | ===================== | ============ | ============= | ================== | ============= | ====== | ======== | ============================== | =============== | =========== | ========================= | ========================= | ================== | ============ | =========== | ============= | ============= | =========== | =================== | ============== | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 2575       | 2005-10-22T00:00:00 | 2005-10-28T00:00:00 | DOT    | Department of Transportation                   | Street Sign - Damaged | No Parking, Standing, Stopping | Street        | 10007        |                       |                  |                        |                                | CHURCH STREET         | BARCLAY STREET        | INTERSECTION | NEW YORK      |                    | N/A           | Closed |          | 2005-10-28T00:00:00            | 01 MANHATTAN    | MANHATTAN   | 981684                    | 199135                    | Unspecified        | MANHATTAN    | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     | South Bound              |           |                        |                 |                 |                     | 40.71325594707911  | -74.00925599630611 | 
| 10663      | 2005-05-26T00:00:00 | 2005-05-26T00:00:00 | NYPD   | New York City Police Department                | Homeless Encampment   | N/A                            | N/A           | 11355        | 46-06 BOWNE STREET    | BOWNE STREET     | HOLLY AVENUE           | LABURNUM AVENUE                |                       |                       | ADDRESS      | FLUSHING      |                    | Precinct      | Closed |          |                                | 07 QUEENS       | QUEENS      | 1035120                   | 213316                    | Unspecified        | QUEENS       | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.7520333528106   | -73.81639635090929 | 
| 34746      | 2005-01-10T00:00:00 | 2005-01-10T00:00:00 | DOT    | Department of Transportation                   | Highway Condition     | Dead Animal                    | Highway       | 11369        |                       |                  | LA GUARDIA ACCESS ROAD | GRND CNTRL PARKWAY ENTRANCE WB |                       |                       | PLACENAME    | EAST ELMHURST | LA GUARDIA AIRPORT | N/A           | Closed |          |                                | 80 QUEENS       | QUEENS      | 1019486                   | 220530                    | Unspecified        | QUEENS       | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     | East Bound               |           |                        |                 |                 |                     | 40.77191002812788  | -73.87278579409514 | 
| 34748      | 2005-01-10T00:00:00 | 2005-01-10T00:00:00 | DOT    | Department of Transportation                   | Street Sign - Damaged | No Parking, Standing, Stopping | Street        | 10461        | 2121 EASTCHESTER ROAD | EASTCHESTER ROAD | RHINELANDER AVENUE     | PELHAM PARKWAY                 |                       |                       | ADDRESS      | BRONX         |                    | N/A           | Closed |          | 2005-01-10T00:00:00            | 11 BRONX        | BRONX       | 1027434                   | 251387                    | Unspecified        | BRONX        | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.85656847727785  | -73.84389227231065 | 
| 33826      | 2005-01-02T00:00:00 | 2005-01-13T00:00:00 | DOT    | Department of Transportation                   | Street Sign - Damaged | No Parking, Standing, Stopping | Street        | 11229        |                       |                  |                        |                                | ALLEN AVENUE          | EBONY COURT           | INTERSECTION | BROOKLYN      |                    | N/A           | Closed |          | 2005-01-13T00:00:00            | 15 BROOKLYN     | BROOKLYN    | 1003119                   | 156230                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.595471402667506 | -73.932056378608   | 
| 33827      | 2005-01-04T00:00:00 | 2005-01-12T00:00:00 | TLC    | Correspondence - Taxi and Limousine Commission | Taxi Compliment       | Driver Compliment              |               |              |                       |                  |                        |                                |                       |                       |              |               |                    | N/A           | Closed |          |                                | 0 Unspecified   | Unspecified |                           |                           | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     |                    |                    | 
| 33831      | 2005-01-03T00:00:00 | 2005-01-04T00:00:00 | DOT    | Department of Transportation                   | Sidewalk Condition    | Curb Painted                   | Sidewalk      | 11238        | 378 CLERMONT AVENUE   | CLERMONT AVENUE  | LAFAYETTE AVENUE       | GREENE AVENUE                  |                       |                       | ADDRESS      | BROOKLYN      |                    | N/A           | Closed |          | 2005-01-04T00:00:00            | 02 BROOKLYN     | BROOKLYN    | 992689                    | 189442                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     | East Bound               |           |                        |                 |                 |                     | 40.686647276140754 | -73.96957124536337 | 
| 33836      | 2005-01-03T00:00:00 | 2005-01-05T00:00:00 | DOT    | Department of Transportation                   | Street Sign - Damaged | Stop                           | Street        | 11214        |                       |                  |                        |                                | BAY 28 STREET         | 86 STREET             | INTERSECTION | BROOKLYN      |                    | N/A           | Closed |          | 2005-01-05T00:00:00            | 11 BROOKLYN     | BROOKLYN    | 985061                    | 158284                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     | East Bound               |           |                        |                 |                 |                     | 40.60112926603199  | -73.99707949860625 | 
| 33838      | 2005-01-04T00:00:00 | 2005-01-05T00:00:00 | DOT    | Department of Transportation                   | Street Sign - Damaged | Stop                           | Street        | 11214        |                       |                  |                        |                                | BAY 28 STREET         | 86 STREET             | INTERSECTION | BROOKLYN      |                    | N/A           | Closed |          | 2005-01-05T00:00:00            | 11 BROOKLYN     | BROOKLYN    | 985061                    | 158284                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.60112926603199  | -73.99707949860625 | 
| 33840      | 2005-01-03T00:00:00 | 2005-01-03T00:00:00 | DPR    | Department of Parks and Recreation             | Animal in a Park      | Domestic Strays                | Park          | 10039        |                       |                  |                        |                                |                       |                       |              | NEW YORK      |                    | N/A           | Closed |          |                                | 10 MANHATTAN    | MANHATTAN   |                           |                           | Unspecified        | MANHATTAN    | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     |                    |                    | 
```