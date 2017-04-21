# 311 Service Requests for 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-2009-29572) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3rfa-3xsf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3rfa-3xsf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3rfa-3xsf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3rfa-3xsf |
| Name | 311 Service Requests for 2009 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2009, all service requests |
| Created | 2011-10-10T14:09:37Z |
| Publication Date | 2011-10-20T18:52:51Z |

## Description

All 311 Requests from year 2009. This is historical data and will not be updated.

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
series e:3rfa-3xsf d:2009-01-01T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11225 t:location_type="RESIDENTIAL BUILDING" t:school_name=Unspecified t:descriptor=HEAT t:status=Closed t:complaint_type=HEATING t:street_name="WINTHROP STREET" t:agency=HPD t:facility_type=N/A t:borough=Unspecified t:agency_name="Department of Housing Preservation and Development" t:cross_street_2="BEDFORD AVENUE" t:cross_street_1="FLATBUSH AVENUE" t:city=BROOKLYN t:school_phone_number=Unspecified t:park_borough=Unspecified t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="0 Unspecified" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=995885 m:y_coordinate_state_plane_=178504 m:unique_key=12822544

series e:3rfa-3xsf d:2009-01-01T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11102 t:location_type=Restaurant/Bar/Deli/Bakery t:school_name=Unspecified t:descriptor="Smoking Violation" t:status=Pending t:complaint_type=Smoking t:street_name="NEWTOWN AVENUE" t:agency=DOHMH t:facility_type=N/A t:borough=QUEENS t:agency_name="Department of Health and Mental Hygiene" t:cross_street_2="30 STREET" t:cross_street_1="29 STREET" t:city=ASTORIA t:school_phone_number=Unspecified t:park_borough=QUEENS t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="01 QUEENS" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=1005906 m:y_coordinate_state_plane_=219416 m:unique_key=12818524

series e:3rfa-3xsf d:2009-01-01T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11220 t:school_name=Unspecified t:descriptor=Controller t:status=Closed t:complaint_type="Traffic Signal Condition" t:agency=DOT t:facility_type=N/A t:borough=BROOKLYN t:agency_name="Department of Transportation" t:city=BROOKLYN t:school_phone_number=Unspecified t:park_borough=BROOKLYN t:school_state=Unspecified t:park_facility_name=Unspecified t:intersection_street_1="6 AVENUE" t:school_region=Unspecified t:school_code=Unspecified t:community_board="10 BROOKLYN" t:school_city=Unspecified t:school_zip=Unspecified t:intersection_street_2="GOWANUS EXPRESSWAY" m:x_coordinate_state_plane_=979581 m:y_coordinate_state_plane_=170750 m:unique_key=12823061
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:3rfa-3xsf l:"311 Service Requests for 2009" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/3rfa-3xsf

property e:3rfa-3xsf t:meta.view v:id=3rfa-3xsf v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2009" v:attribution=311

property e:3rfa-3xsf t:meta.view.license v:name="Public Domain"

property e:3rfa-3xsf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3rfa-3xsf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                                        | complaint_type           | descriptor        | location_type              | incident_zip | incident_address     | street_name     | cross_street_1   | cross_street_2  | intersection_street_1 | intersection_street_2 | address_type | city       | landmark | facility_type | status  | due_date            | resolution_action_updated_date | community_board | borough     | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name | park_borough | school_name | school_number | school_region | school_code | school_phone_number | school_address | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ================================================== | ======================== | ================= | ========================== | ============ | ==================== | =============== | ================ | =============== | ===================== | ===================== | ============ | ========== | ======== | ============= | ======= | =================== | ============================== | =============== | =========== | ========================= | ========================= | ================== | ============ | =========== | ============= | ============= | =========== | =================== | ============== | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 12822544   | 2009-01-01T00:00:00 | 2009-01-07T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                  | HEAT              | RESIDENTIAL BUILDING       | 11225        | 55 WINTHROP STREET   | WINTHROP STREET | FLATBUSH AVENUE  | BEDFORD AVENUE  |                       |                       | ADDRESS      | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-07T00:00:00            | 0 Unspecified   | Unspecified | 995885                    | 178504                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.65662129596871  | -73.95806621423951 | 
| 12818524   | 2009-01-01T00:00:00 |                     | DOHMH  | Department of Health and Mental Hygiene            | Smoking                  | Smoking Violation | Restaurant/Bar/Deli/Bakery | 11102        | 29-35 NEWTOWN AVENUE | NEWTOWN AVENUE  | 29 STREET        | 30 STREET       |                       |                       | ADDRESS      | ASTORIA    |          | N/A           | Pending | 2009-02-07T00:00:00 | 2009-01-02T00:00:00            | 01 QUEENS       | QUEENS      | 1005906                   | 219416                    | Unspecified        | QUEENS       | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.76889608950418  | -73.92181786912313 | 
| 12823061   | 2009-01-01T00:00:00 | 2009-01-01T00:00:00 | DOT    | Department of Transportation                       | Traffic Signal Condition | Controller        |                            | 11220        |                      |                 |                  |                 | 6 AVENUE              | GOWANUS EXPRESSWAY    | INTERSECTION | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-01T00:00:00            | 10 BROOKLYN     | BROOKLYN    | 979581                    | 170750                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.635344653337626 | -74.01682221017914 | 
| 12823062   | 2009-01-01T00:00:00 | 2009-01-01T00:00:00 | DOT    | Department of Transportation                       | Traffic Signal Condition | Controller        |                            | 11201        |                      |                 |                  |                 | GOLD STREET           | NASSAU STREET         | INTERSECTION | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-01T00:00:00            | 02 BROOKLYN     | BROOKLYN    | 988950                    | 193715                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.698378448801606 | -73.98305008771115 | 
| 12823063   | 2009-01-01T00:00:00 | 2009-01-01T00:00:00 | DOT    | Department of Transportation                       | Traffic Signal Condition | Controller        |                            | 11235        |                      |                 |                  |                 | AVENUE X              | OCEAN AVENUE          | INTERSECTION | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-01T00:00:00            | 15 BROOKLYN     | BROOKLYN    | 998094                    | 155236                    | Unspecified        | BROOKLYN     | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.59275234651692  | -73.95015246435702 | 
| 12826508   | 2009-01-01T00:00:00 | 2009-01-12T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                  | HEAT              | RESIDENTIAL BUILDING       | 11417        | 103-60 104 STREET    | 104 STREET      | 103 AVENUE       | LIBERTY AVENUE  |                       |                       | ADDRESS      | OZONE PARK |          | N/A           | Closed  |                     | 2009-01-12T00:00:00            | 0 Unspecified   | Unspecified | 1029334                   | 188130                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.68293534353076  | -73.83744823185012 | 
| 12826510   | 2009-01-01T00:00:00 | 2009-01-12T00:00:00 | HPD    | Department of Housing Preservation and Development | NONCONST                 | VERMIN            | RESIDENTIAL BUILDING       | 11225        | 1211 NOSTRAND AVENUE | NOSTRAND AVENUE | HAWTHORNE STREET | WINTHROP STREET |                       |                       | ADDRESS      | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-12T00:00:00            | 0 Unspecified   | Unspecified | 998041                    | 178876                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.65763925884526  | -73.95029500016935 | 
| 12826511   | 2009-01-01T00:00:00 | 2009-01-07T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                  | HEAT              | RESIDENTIAL BUILDING       | 11237        | 1409 HANCOCK STREET  | HANCOCK STREET  | IRVING AVENUE    | WYCKOFF AVENUE  |                       |                       | ADDRESS      | BROOKLYN   |          | N/A           | Closed  |                     | 2009-01-07T00:00:00            | 0 Unspecified   | Unspecified | 1009873                   | 192822                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.69589152610558  | -73.9075975573773  | 
| 12826512   | 2009-01-01T00:00:00 | 2009-01-10T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                  | HEAT              | RESIDENTIAL BUILDING       | 11377        | 31-38 68 STREET      | 68 STREET       | 31 AVENUE        | 32 AVENUE       |                       |                       | ADDRESS      | WOODSIDE   |          | N/A           | Closed  |                     | 2009-01-10T00:00:00            | 0 Unspecified   | Unspecified | 1012203                   | 215159                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.75719405987824  | -73.8991022643995  | 
| 12826513   | 2009-01-01T00:00:00 | 2009-01-07T00:00:00 | HPD    | Department of Housing Preservation and Development | HEATING                  | HEAT              | RESIDENTIAL BUILDING       | 10028        | 227 EAST 82 STREET   | EAST 82 STREET  | 3 AVENUE         | 2 AVENUE        |                       |                       | ADDRESS      | NEW YORK   |          | N/A           | Closed  |                     | 2009-01-07T00:00:00            | 0 Unspecified   | Unspecified | 996683                    | 221971                    | Unspecified        | Unspecified  | Unspecified | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified    | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.77592667846     | -73.9551098553282  | 
```