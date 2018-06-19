# 311 Service Requests for 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-for-2008-b02f5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uzcy-9puk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uzcy-9puk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uzcy-9puk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uzcy-9puk |
| Name | 311 Service Requests for 2008 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2008, all service requests |
| Created | 2011-10-10T16:48:22Z |
| Publication Date | 2011-10-20T18:52:35Z |

## Description

311 Service Requests for 2008. This is historical data and will not be updated.

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
series e:uzcy-9puk d:2008-06-19T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10007 t:school_name=Unspecified t:descriptor="Demolition - Unsafe" t:status=Closed t:complaint_type="BEST/Site Safety" t:street_name="CHAMBERS STREET" t:agency=DOB t:facility_type=N/A t:borough=MANHATTAN t:agency_name="Department of Buildings" t:cross_street_2="HUDSON STREET" t:cross_street_1="CHURCH STREET" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="01 MANHATTAN" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=981939 m:y_coordinate_state_plane_=199806 m:unique_key=11442723

series e:uzcy-9puk d:2008-06-19T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10003 t:school_name=Unspecified t:descriptor="Building Permit - None" t:status=Closed t:complaint_type="General Construction/Plumbing" t:street_name="MOTT STREET" t:agency=DOB t:facility_type=N/A t:borough=MANHATTAN t:agency_name="Department of Buildings" t:cross_street_2="EAST HOUSTON STREET" t:cross_street_1="PRINCE STREET" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="02 MANHATTAN" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=985801 m:y_coordinate_state_plane_=203107 m:unique_key=11442724

series e:uzcy-9puk d:2008-03-20T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10463 t:location_type="RESIDENTIAL BUILDING" t:school_name=Unspecified t:descriptor=LIGHTING t:status=Closed t:complaint_type=ELECTRIC t:street_name="ORLOFF AVENUE" t:agency=HPD t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Housing Preservation and Development" t:cross_street_2=BEND t:cross_street_1="CANNON PLACE" t:city=BRONX t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=1012964 m:y_coordinate_state_plane_=261425 m:unique_key=10758429
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:uzcy-9puk l:"311 Service Requests for 2008" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/uzcy-9puk

property e:uzcy-9puk t:meta.view v:id=uzcy-9puk v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2008" v:attribution=311

property e:uzcy-9puk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uzcy-9puk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                                        | complaint_type                | descriptor                       | location_type        | incident_zip | incident_address    | street_name     | cross_street_1      | cross_street_2      | intersection_street_1 | intersection_street_2 | address_type | city          | landmark | facility_type | status | due_date | resolution_action_updated_date | community_board | borough     | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name | park_borough | school_name | school_number | school_region | school_code | school_phone_number | school_address | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ================================================== | ============================= | ================================ | ==================== | ============ | =================== | =============== | =================== | =================== | ===================== | ===================== | ============ | ============= | ======== | ============= | ====== | ======== | ============================== | =============== | =========== | ========================= | ========================= | ================== | ============ | =========== | ============= | ============= | =========== | =================== | ============== | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 11442723   | 2008-06-19T00:00:00 | 2008-07-10T00:00:00 | DOB    | Department of Buildings                            | BEST/Site Safety              | Demolition - Unsafe              |                      | 10007        | 112 CHAMBERS STREET | CHAMBERS STREET | CHURCH STREET       | HUDSON STREET       |                       |                       | ADDRESS      | NEW YORK      |          | N/A           | Closed |          | 2008-07-10T00:00:00            | 01 MANHATTAN    | MANHATTAN   | 981939                    | 199806                    | Unspecified        | MANHATTAN    | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.7150977521531   | -74.00833639849627 | 
| 11442724   | 2008-06-19T00:00:00 | 2008-06-26T00:00:00 | DOB    | Department of Buildings                            | General Construction/Plumbing | Building Permit - None           |                      | 10003        | 284 MOTT STREET     | MOTT STREET     | PRINCE STREET       | EAST HOUSTON STREET |                       |                       | ADDRESS      | NEW YORK      |          | N/A           | Closed |          | 2008-06-26T00:00:00            | 02 MANHATTAN    | MANHATTAN   | 985801                    | 203107                    | Unspecified        | MANHATTAN    | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.72415836830795  | -73.99440436523415 | 
| 10758429   | 2008-03-20T00:00:00 | 2008-03-26T00:00:00 | HPD    | Department of Housing Preservation and Development | ELECTRIC                      | LIGHTING                         | RESIDENTIAL BUILDING | 10463        | 3873 ORLOFF AVENUE  | ORLOFF AVENUE   | CANNON PLACE        | BEND                |                       |                       | ADDRESS      | BRONX         |          | N/A           | Closed |          | 2008-03-26T00:00:00            | 0 Unspecified   | Unspecified | 1012964                   | 261425                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.88417861800582  | -73.8961574296168  | 
| 10761129   | 2008-03-20T00:00:00 | 2008-03-24T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                       | HEAT                             | RESIDENTIAL BUILDING | 10024        | 591 WEST END AVENUE | WEST END AVENUE | WEST 88 STREET      | WEST 89 STREET      |                       |                       | ADDRESS      | NEW YORK      |          | N/A           | Closed |          | 2008-03-24T00:00:00            | 0 Unspecified   | Unspecified | 990714                    | 227296                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.79054876756222  | -73.97665618792385 | 
| 10761130   | 2008-03-20T00:00:00 | 2008-03-31T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                       | HEAT                             | RESIDENTIAL BUILDING | 11224        | 2954 WEST 8 STREET  | WEST 8 STREET   | SHEEPSHEAD BAY ROAD | NYCTA SUBWAY        |                       |                       | ADDRESS      | BROOKLYN      |          | N/A           | Closed |          | 2008-03-31T00:00:00            | 0 Unspecified   | Unspecified | 990775                    | 149341                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.57658015286054  | -73.9765113837678  | 
| 10758140   | 2008-03-20T00:00:00 | 2008-04-30T00:00:00 | HPD    | Department of Housing Preservation and Development | PLUMBING                      | BATHTUB                          | RESIDENTIAL BUILDING | 11103        | 40-15 25 AVENUE     | 25 AVENUE       | STEINWAY STREET     | 41 STREET           |                       |                       | ADDRESS      | ASTORIA       |          | N/A           | Closed |          | 2008-04-30T00:00:00            | 0 Unspecified   | Unspecified | 1008771                   | 219047                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.767875798115675 | -73.9114760466738  | 
| 10758141   | 2008-03-18T00:00:00 | 2008-03-19T00:00:00 | DOT    | Department of Transportation                       | Street Condition              | Pothole                          |                      | 11356        | 14-20 114 STREET    | 114 STREET      | 14 AVENUE           | 14 ROAD             |                       |                       | ADDRESS      | COLLEGE POINT |          | N/A           | Closed |          | 2008-03-19T00:00:00            | 07 QUEENS       | QUEENS      | 1024890                   | 225325                    | Unspecified        | QUEENS       | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.785047826792194 | -73.85324650757364 | 
| 10762169   | 2008-03-20T00:00:00 | 2008-03-20T00:00:00 | DEP    | Department of Environmental Protection             | Sewer                         | Sewer Backup (Use Comments) (SA) |                      | 11236        | 2121 CANARSIE ROAD  | CANARSIE ROAD   | SKIDMORE AVENUE     | SEAVIEW COURT       |                       |                       | ADDRESS      | BROOKLYN      |          | N/A           | Closed |          | 2008-03-20T00:00:00            | 18 BROOKLYN     | BROOKLYN    | 1014863                   | 169254                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.63118678389254  | -73.889709494798   | 
| 10762170   | 2008-03-20T00:00:00 | 2008-03-25T00:00:00 | HPD    | Department of Housing Preservation and Development | ELECTRIC                      | LIGHTING                         | RESIDENTIAL BUILDING | 10463        | 3873 ORLOFF AVENUE  | ORLOFF AVENUE   | CANNON PLACE        | BEND                |                       |                       | ADDRESS      | BRONX         |          | N/A           | Closed |          | 2008-03-25T00:00:00            | 0 Unspecified   | Unspecified | 1012964                   | 261425                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.88417861800582  | -73.8961574296168  | 
| 10762171   | 2008-03-20T00:00:00 | 2008-03-24T00:00:00 | HPD    | Department of Housing Preservation and Development | PLUMBING                      | WATER-SUPPLY                     | RESIDENTIAL BUILDING | 10473        | 920 THIERIOT AVENUE | THIERIOT AVENUE | STORY AVENUE        | BRUCKNER BOULEVARD  |                       |                       | ADDRESS      | BRONX         |          | N/A           | Closed |          | 2008-03-24T00:00:00            | 0 Unspecified   | Unspecified | 1022265                   | 239569                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.82415532063795  | -73.8626448718532  | 
```