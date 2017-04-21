# 311 Service Requests for 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-for-2006-12afe) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hy4q-igkk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hy4q-igkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hy4q-igkk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hy4q-igkk |
| Name | 311 Service Requests for 2006 |
| Attribution | 311 |
| Category | Social Services |
| Tags | 311, 311 service requests, 2006, all service requests |
| Created | 2011-10-11T01:13:03Z |
| Publication Date | 2011-10-20T19:03:13Z |

## Description

311 Service Requests for 2006. This is historical data and will not be updated.

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
series e:hy4q-igkk d:2006-07-25T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10019 t:location_type=Street/Sidewalk t:school_name=Unspecified t:descriptor=N/A t:status=Closed t:complaint_type="Homeless Encampment" t:street_name="WEST 51 STREET" t:agency=NYPD t:facility_type=Precinct t:borough=MANHATTAN t:agency_name="New York City Police Department" t:cross_street_2="9 AVENUE" t:cross_street_1="8 AVENUE" t:city="NEW YORK" t:school_phone_number=Unspecified t:park_borough=MANHATTAN t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="04 MANHATTAN" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=988053 m:y_coordinate_state_plane_=217327 m:unique_key=105

series e:hy4q-igkk d:2006-07-25T00:00:00.000Z t:school_number=Unspecified t:incident_zip=10452 t:location_type=Street/Sidewalk t:school_name=Unspecified t:descriptor=Unlicensed t:status=Closed t:complaint_type=Vending t:street_name="WALTON AVENUE" t:agency=NYPD t:facility_type=Precinct t:borough=BRONX t:agency_name="New York City Police Department" t:cross_street_2="EAST 164 STREET" t:cross_street_1="EAST 161 STREET" t:city=BRONX t:school_phone_number=Unspecified t:park_borough=BRONX t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="04 BRONX" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=1005381 m:y_coordinate_state_plane_=240934 m:unique_key=107

series e:hy4q-igkk d:2006-07-25T00:00:00.000Z t:school_number=Unspecified t:incident_zip=11201 t:location_type=Street t:school_name=Unspecified t:descriptor="No Parking, Standing, Stopping" t:status=Closed t:complaint_type="Street Sign - Damaged" t:street_name="DEAN STREET" t:agency=DOT t:facility_type=N/A t:borough=BROOKLYN t:agency_name="Department of Transportation" t:cross_street_2="HOYT STREET" t:cross_street_1="SMITH STREET" t:city=BROOKLYN t:school_phone_number=Unspecified t:park_borough=BROOKLYN t:school_state=Unspecified t:park_facility_name=Unspecified t:school_region=Unspecified t:school_code=Unspecified t:community_board="02 BROOKLYN" t:school_city=Unspecified t:school_zip=Unspecified m:x_coordinate_state_plane_=987496 m:y_coordinate_state_plane_=189448 m:unique_key=125
```

## Meta Commands

```ls
metric m:unique_key p:integer l:"Unique Key" t:dataTypeName=number

metric m:x_coordinate_state_plane_ p:integer l:"X Coordinate (State Plane)" t:dataTypeName=number

metric m:y_coordinate_state_plane_ p:integer l:"Y Coordinate (State Plane)" t:dataTypeName=number

entity e:hy4q-igkk l:"311 Service Requests for 2006" t:attribution=311 t:url=https://data.cityofnewyork.us/api/views/hy4q-igkk

property e:hy4q-igkk t:meta.view v:id=hy4q-igkk v:category="Social Services" v:averageRating=0 v:name="311 Service Requests for 2006" v:attribution=311

property e:hy4q-igkk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hy4q-igkk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| unique_key | created_date        | closed_date         | agency | agency_name                             | complaint_type            | descriptor                     | location_type              | incident_zip | incident_address     | street_name     | cross_street_1  | cross_street_2  | intersection_street_1 | intersection_street_2 | address_type | city          | landmark | facility_type | status | due_date            | resolution_action_updated_date | community_board  | borough       | x_coordinate_state_plane_ | y_coordinate_state_plane_ | park_facility_name          | park_borough  | school_name                 | school_number | school_region | school_code | school_phone_number | school_address    | school_city | school_state | school_zip  | school_not_found | school_or_citywide_complaint | vehicle_type | taxi_company_borough | taxi_pick_up_location | bridge_highway_name | bridge_highway_direction | road_ramp | bridge_highway_segment | garage_lot_name | ferry_direction | ferry_terminal_name | latitude           | longitude          | 
| ========== | =================== | =================== | ====== | ======================================= | ========================= | ============================== | ========================== | ============ | ==================== | =============== | =============== | =============== | ===================== | ===================== | ============ | ============= | ======== | ============= | ====== | =================== | ============================== | ================ | ============= | ========================= | ========================= | =========================== | ============= | =========================== | ============= | ============= | =========== | =================== | ================= | =========== | ============ | =========== | ================ | ============================ | ============ | ==================== | ===================== | =================== | ======================== | ========= | ====================== | =============== | =============== | =================== | ================== | ================== | 
| 105        | 2006-07-25T00:00:00 | 2006-07-25T00:00:00 | NYPD   | New York City Police Department         | Homeless Encampment       | N/A                            | Street/Sidewalk            | 10019        | 311 WEST 51 STREET   | WEST 51 STREET  | 8 AVENUE        | 9 AVENUE        |                       |                       | ADDRESS      | NEW YORK      |          | Precinct      | Closed | 2006-07-26T00:00:00 | 2006-07-25T00:00:00            | 04 MANHATTAN     | MANHATTAN     | 988053                    | 217327                    | Unspecified                 | MANHATTAN     | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.763188032775005 | -73.98627165108385 | 
| 107        | 2006-07-25T00:00:00 | 2006-07-25T00:00:00 | NYPD   | New York City Police Department         | Vending                   | Unlicensed                     | Street/Sidewalk            | 10452        | 901 WALTON AVENUE    | WALTON AVENUE   | EAST 161 STREET | EAST 164 STREET |                       |                       | ADDRESS      | BRONX         |          | Precinct      | Closed | 2006-07-26T00:00:00 | 2006-07-25T00:00:00            | 04 BRONX         | BRONX         | 1005381                   | 240934                    | Unspecified                 | BRONX         | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.82795838412844  | -73.9236455009091  | 
| 125        | 2006-07-25T00:00:00 | 2006-11-08T00:00:00 | DOT    | Department of Transportation            | Street Sign - Damaged     | No Parking, Standing, Stopping | Street                     | 11201        | 130 DEAN STREET      | DEAN STREET     | SMITH STREET    | HOYT STREET     |                       |                       | ADDRESS      | BROOKLYN      |          | N/A           | Closed | 2007-01-23T00:00:00 | 2006-11-08T00:00:00            | 02 BROOKLYN      | BROOKLYN      | 987496                    | 189448                    | Unspecified                 | BROOKLYN      | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.68666717264917  | -73.98829579744877 | 
| 127        | 2006-08-29T00:00:00 | 2006-08-29T00:00:00 | NYPD   | New York City Police Department         | Noise - Park              | Loud Music/Party               | Park/Playground            | 11385        | 60-72 MADISON STREET | MADISON STREET  | 60 PLACE        | FRESH POND ROAD |                       |                       | ADDRESS      | RIDGEWOOD     |          | Precinct      | Closed | 2006-08-30T00:00:00 | 2006-08-29T00:00:00            | 05 QUEENS        | QUEENS        | 1012421                   | 196800                    | Unspecified                 | QUEENS        | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.70680245319897  | -73.89839225003249 | 
| 144        | 2006-08-29T00:00:00 | 2006-08-31T00:00:00 | NYPD   | New York City Police Department         | Homeless Encampment       | N/A                            | Street/Sidewalk            | 11432        | 153-10 89 AVENUE     | 89 AVENUE       | 153 STREET      | BURDETTE PLACE  |                       |                       | ADDRESS      | JAMAICA       |          | Precinct      | Closed | 2006-08-30T00:00:00 | 2006-08-31T00:00:00            | 12 QUEENS        | QUEENS        | 1038751                   | 196284                    | Unspecified                 | QUEENS        | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.70526315478051  | -73.80342907545086 | 
| 147        | 2006-08-29T00:00:00 |                     | DOHMH  | Department of Health and Mental Hygiene | Food Establishment        | Handwashing                    | Restaurant/Bar/Deli/Bakery | 10302        |                      |                 |                 |                 | DECKER AVENUE         | BARRETT AVENUE        | INTERSECTION | STATEN ISLAND |          | N/A           | Open   | 2006-10-05T00:00:00 | 2006-08-30T00:00:00            | 01 STATEN ISLAND | STATEN ISLAND | 945974                    | 167905                    | Unspecified                 | STATEN ISLAND | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.62745427115626  | -74.13789056665027 | 
| 149        | 2006-09-18T00:00:00 | 2006-09-18T00:00:00 | DPR    | Department of Parks and Recreation      | Overgrown Tree/Branches   | Regular/Routine Pruning        | Street                     | 11214        | 1672 82 STREET       | 82 STREET       | 16 AVENUE       | 17 AVENUE       |                       |                       | ADDRESS      | BROOKLYN      |          | N/A           | Closed | 2006-09-25T00:00:00 |                                | 11 BROOKLYN      | BROOKLYN      | 983329                    | 162014                    | Unspecified                 | BROOKLYN      | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.611367343148224 | -74.00331713230251 | 
| 7          | 2006-08-09T00:00:00 | 2006-08-09T00:00:00 | DOHMH  | Department of Health and Mental Hygiene | Food Establishment        | Pet/Animal                     | Restaurant/Bar/Deli/Bakery | 11226        | 1617 NOSTRAND AVENUE | NOSTRAND AVENUE | TILDEN AVENUE   | BEVERLY ROAD    |                       |                       | ADDRESS      | BROOKLYN      |          | N/A           | Closed | 2006-09-15T00:00:00 | 2006-08-09T00:00:00            | 17 BROOKLYN      | BROOKLYN      | 998375                    | 174808                    | Unspecified                 | BROOKLYN      | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.64647296005029  | -73.94909972980435 | 
| 91         | 2006-07-25T00:00:00 | 2006-07-26T00:00:00 | NYPD   | New York City Police Department         | Disorderly Youth          | Nuisance/Truant                | Residential Building/House | 10030        | 2680 8 AVENUE        | 8 AVENUE        | WEST 142 STREET | WEST 143 STREET |                       |                       | ADDRESS      | NEW YORK      |          | Precinct      | Closed | 2006-07-26T00:00:00 | 2006-07-26T00:00:00            | 10 MANHATTAN     | MANHATTAN     | 1000003                   | 238477                    | Unspecified                 | MANHATTAN     | Unspecified                 | Unspecified   | Unspecified   | Unspecified | Unspecified         | Unspecified       | Unspecified | Unspecified  | Unspecified |                  |                              |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.821225847628206 | -73.9430840629769  | 
| 95         | 2006-07-25T00:00:00 | 2006-08-02T00:00:00 | DOE    | Central - Department of Education       | Discipline and Suspension | Student/Parent Rights          | School                     | 11385        | 976 SENECA AVENUE    | SENECA AVENUE   | GEORGE STREET   | CENTRE STREET   |                       |                       |              | RIDGEWOOD     |          | N/A           | Closed | 2006-07-29T00:00:00 | 2006-08-02T00:00:00            | 05 QUEENS        | QUEENS        | 1011385                   | 194144                    | School - IS 285 Meyer Levin | QUEENS        | School - IS 285 Meyer Levin | 285           | Region 6      | 18K285      | 7184512200          | 5909 Beverly Road | BROOKLYN    | NY           | 11203       | N                | School                       |              |                      |                       |                     |                          |           |                        |                 |                 |                     | 40.6995155990858   | -73.90213961535707 | 
```