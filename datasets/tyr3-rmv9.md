# Lane and Road Closures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lane-and-road-closures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/tyr3-rmv9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/tyr3-rmv9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/tyr3-rmv9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | tyr3-rmv9 |
| Name | Lane and Road Closures |
| Category | Government |
| Tags | 311, lane/road, lane, road, closure |
| Created | 2016-09-08T18:17:35Z |
| Publication Date | 2016-09-09T13:46:01Z |

## Description

Dataset is currently in BETA. Lane and road closures reported to Austin 3-1-1. Data is refreshed every 30-minutes.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | service_request_sr_number     | Service Request (SR) Number   | text          | text          |
| Yes      | series tag     | sr_type_code                  | SR Type Code                  | text          | text          |
| Yes      | series tag     | sr_description                | SR Description                | text          | text          |
| Yes      | series tag     | owning_department             | Owning Department             | text          | text          |
| Yes      | series tag     | method_received               | Method Received               | text          | text          |
| Yes      | series tag     | sr_status                     | SR Status                     | text          | text          |
| Yes      | time           | status_change_date            | Status Change Date            | calendar_date | calendar_date |
| No       |                | created_date                  | Created Date                  | calendar_date | calendar_date |
| No       |                | last_update_date              | Last Update Date              | calendar_date | calendar_date |
| No       |                | close_date                    | Close Date                    | calendar_date | calendar_date |
| Yes      | series tag     | sr_location                   | SR Location                   | text          | text          |
| Yes      | series tag     | street_number                 | Street Number                 | text          | number        |
| Yes      | series tag     | zip_code                      | Zip Code                      | text          | text          |
| Yes      | series tag     | county                        | County                        | text          | text          |
| Yes      | numeric metric | state_plane_x_coordinate      | State Plane X Coordinate      | number        | number        |
| Yes      | numeric metric | state_plane_y_coordinate      | State Plane Y Coordinate      | number        | number        |
| No       |                | latitude_coordinate           | Latitude Coordinate           | number        | number        |
| No       |                | longitude_coordinate          | Longitude Coordinate          | number        | number        |
| Yes      | series tag     | council_district              | Council District              | text          | number        |
| Yes      | series tag     | map_page                      | Map Page                      | text          | text          |
| Yes      | series tag     | map_tile                      | Map Tile                      | text          | text          |
| No       |                | date_and_time_of_closure      | Date and Time of Closure      | text          | text          |
| No       |                | date_and_time_of_reopening    | Date and Time of Reopening    | text          | text          |
| Yes      | series tag     | lanes_closed                  | Lanes Closed                  | text          | text          |
| Yes      | series tag     | routine_or_emergency          | Routine or Emergency          | text          | text          |
| Yes      | series tag     | permit_number                 | Permit Number                 | text          | text          |
| Yes      | series tag     | cross_streets                 | Cross Streets                 | text          | text          |
| Yes      | series tag     | detour_information            | Detour Information            | text          | text          |
| Yes      | series tag     | business_or_dept_closing_road | Business or Dept Closing Road | text          | text          |
| Yes      | series tag     | name_of_business              | Name of Business              | text          | text          |
```

## Time Field

```ls
Value = status_change_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = created_date,last_update_date,close_date,latitude_coordinate,longitude_coordinate,date_and_time_of_closure,date_and_time_of_reopening
```

## Data Commands

```ls
series e:tyr3-rmv9 d:2016-09-08T09:20:00.000Z t:name_of_business="Tri-Star Utilities" t:cross_streets="E 7TH ST & CHICON ST" t:sr_status=Closed t:lanes_closed="Eastbound Lane,Westbound Lane" t:zip_code=78702 t:detour_information="No Detour---One lane closure for east and west bound" t:sr_location="E 7TH ST & CHICON ST, AUSTIN, TX 78702" t:sr_description="Lane/Road Closure Notification" t:map_tile=MK22 t:council_district=3 t:map_page=585Y t:business_or_dept_closing_road=Other t:service_request_sr_number=16-00234679 t:permit_number=2016-108138 t:sr_type_code=EMROCLRE t:owning_department=Transportation t:county=TRAVIS t:method_received=Phone t:routine_or_emergency=Routine m:state_plane_y_coordinate=10068910 m:state_plane_x_coordinate=3120889.749

series e:tyr3-rmv9 d:2016-09-09T13:55:00.000Z t:name_of_business="Smith Contracting" t:cross_streets="E Riverside Dr. @ S Lakeshore Blvd" t:sr_status=Closed t:lanes_closed="Southbound Lane" t:zip_code=78741 t:detour_information="Traffic will be required to turn right @ the intersection" t:sr_location="E RIVERSIDE DR & S LAKESHORE BLVD, AUSTIN, TX 78741" t:sr_description="Lane/Road Closure Notification" t:map_tile=MJ20 t:council_district=9 t:map_page=615K t:business_or_dept_closing_road="COA Transportation" t:service_request_sr_number=16-00236393 t:permit_number=2016-078046-EX t:sr_type_code=EMROCLRE t:owning_department=Transportation t:county=TRAVIS t:method_received=Phone t:routine_or_emergency=Routine m:state_plane_y_coordinate=10062402.002346 m:state_plane_x_coordinate=3118440.99741229

series e:tyr3-rmv9 d:2016-09-12T14:44:18.000Z t:cross_streets="rainey @ river" t:name_of_business="capform, project manager" t:sr_status=Closed t:lanes_closed="Southbound Lane" t:zip_code=78701 t:detour_information="westbound on davis" t:sr_location="70 RAINEY ST, AUSTIN, TX 78701" t:sr_description="Lane/Road Closure Notification" t:map_tile=MJ21 t:council_district=9 t:map_page=615B t:business_or_dept_closing_road=Other t:service_request_sr_number=16-00239291 t:permit_number=2016-0055061 t:sr_type_code=EMROCLRE t:owning_department=Transportation t:county=TRAVIS t:street_number=70 t:method_received=Phone t:routine_or_emergency=Routine m:state_plane_y_coordinate=10067264.0008437 m:state_plane_x_coordinate=3115581.99958699
```

## Meta Commands

```ls
metric m:state_plane_x_coordinate p:double l:"State Plane X Coordinate" t:dataTypeName=number

metric m:state_plane_y_coordinate p:double l:"State Plane Y Coordinate" t:dataTypeName=number

entity e:tyr3-rmv9 l:"Lane and Road Closures" t:url=https://data.austintexas.gov/api/views/tyr3-rmv9

property e:tyr3-rmv9 t:meta.view v:id=tyr3-rmv9 v:category=Government v:averageRating=0 v:name="Lane and Road Closures"

property e:tyr3-rmv9 t:meta.view.owner v:id=xy86-z82g v:screenName="Austin 311" v:displayName="Austin 311"

property e:tyr3-rmv9 t:meta.view.tableauthor v:id=xy86-z82g v:screenName="Austin 311" v:roleName=publisher v:displayName="Austin 311"
```

## Top Records

```ls
| service_request_sr_number | sr_type_code | sr_description                 | owning_department | method_received | sr_status | status_change_date  | created_date        | last_update_date    | close_date          | sr_location                                           | street_number | zip_code | county | state_plane_x_coordinate | state_plane_y_coordinate | latitude_coordinate | longitude_coordinate | council_district | map_page | map_tile | date_and_time_of_closure                                        | date_and_time_of_reopening                                                       | lanes_closed                  | routine_or_emergency | permit_number  | cross_streets                      | detour_information                                        | business_or_dept_closing_road | name_of_business              | 
| ========================= | ============ | ============================== | ================= | =============== | ========= | =================== | =================== | =================== | =================== | ===================================================== | ============= | ======== | ====== | ======================== | ======================== | =================== | ==================== | ================ | ======== | ======== | =============================================================== | ================================================================================ | ============================= | ==================== | ============== | ================================== | ========================================================= | ============================= | ============================= | 
| 16-00234679               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-08T09:20:00 | 2016-09-08T09:20:00 | 2016-09-08T09:20:00 | 2016-09-08T09:20:00 | E 7TH ST & CHICON ST, AUSTIN, TX 78702                |               | 78702    | TRAVIS | 3120889.749              | 10068910                 | 30.26257579         | -97.7221165          | 3                | 585Y     | MK22     | Saturday, 9-10-16 from 7am-7pm and Sunday, 9-11-16 from 7am-7pm | 9-10-16 from 7pm-Sunday, 9-11-16 to 7am and Then reopen again on Sunday at 7pm . | Eastbound Lane,Westbound Lane | Routine              | 2016-108138    | E 7TH ST & CHICON ST               | No Detour---One lane closure for east and west bound      | Other                         | Tri-Star Utilities            | 
| 16-00236393               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-09T13:55:00 | 2016-09-09T13:55:00 | 2016-09-09T13:55:00 | 2016-09-09T13:55:00 | E RIVERSIDE DR & S LAKESHORE BLVD, AUSTIN, TX 78741   |               | 78741    | TRAVIS | 3118440.99741229         | 10062402.002346          | 30.24484417         | -97.73035307         | 9                | 615K     | MJ20     |                                                                 | 09/17/16 7 am                                                                    | Southbound Lane               | Routine              | 2016-078046-EX | E Riverside Dr. @ S Lakeshore Blvd | Traffic will be required to turn right @ the intersection | COA Transportation            | Smith Contracting             | 
| 16-00239291               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-12T14:44:18 | 2016-09-12T14:44:18 | 2016-09-12T14:44:18 | 2016-09-12T14:44:18 | 70 RAINEY ST, AUSTIN, TX 78701                        | 70            | 78701    | TRAVIS | 3115581.99958699         | 10067264.0008437         | 30.25839263         | -97.73904572         | 9                | 615B     | MJ21     |                                                                 | 9/13/2016, 7:30 start(closed), 9/15/2016 5:00 pm                                 | Southbound Lane               | Routine              | 2016-0055061   | rainey @ river                     | westbound on davis                                        | Other                         | capform, project manager      | 
| 16-00240026               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-13T09:02:18 | 2016-09-13T09:02:18 | 2016-09-13T09:02:18 | 2016-09-13T09:02:18 | 517 S LAMAR BLVD, AUSTIN, TX 78704                    | 517           | 78704    | TRAVIS | 3109537.99894766         | 10067577.0025832         | 30.25963913         | -97.75816108         | 5                | 614D     | MH21     | 9/13/2016 9 am                                                  | 09/13/2016 4 pm                                                                  | Southbound Lane               | Emergency            |                | barton springs                     | n/a                                                       | TXGas                         |                               | 
| 16-00241234               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-14T07:51:25 | 2016-09-14T07:51:25 | 2016-09-14T07:51:25 | 2016-09-14T07:51:25 | BARTON SPRINGS RD & S LAMAR BLVD NB, AUSTIN, TX 78704 |               | 78704    | TRAVIS | 3109411.09858774         | 10068018.8427318         | 30.26086175         | -97.75853052         | 5                | 614D     | MH21     | 09/14/16 9AM                                                    | 09/14/16 4PM                                                                     | Southbound Lane               | Emergency            |                | Barton Springs Rd                  | n/a                                                       | TXGas                         | Texas Gas                     | 
| 16-00241452               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-14T10:14:42 | 2016-09-14T10:14:42 | 2016-09-14T10:14:42 | 2016-09-14T10:14:42 | LAVACA ST & W 5TH ST, AUSTIN, TX 78701                |               | 78701    | TRAVIS | 3113449.49937663         | 10070635.0001825         | 30.26779554         | -97.7455499          | 9                | 585S     | MJ22     |                                                                 | 09/14/2016 6pm to 8:30pm                                                         |                               | Routine              | 2016-099423-ex | 5th                                | none                                                      | TXGas                         |                               | 
| 16-00241868               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-14T16:25:05 | 2016-09-14T16:25:05 | 2016-09-14T16:25:05 | 2016-09-14T16:25:05 | E STASSNEY LN & BURLESON RD, AUSTIN, TX 78744         |               | 78744    | TRAVIS | 3123120.95               | 10048221.56              | 30.20556275         | -97.7165925          | 2                | 645R     | MK17     | 21st of september through the 23rd, 9:00am to 4:00pm            | 23rd of september, 4:00pm                                                        | Southbound Lane,Center Lane   | Routine              | 2016-096316-ex | stassney @ burleson                | n/a                                                       | Other                         | haeglaen construction company | 
| 16-00241940               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-14T17:24:56 | 2016-09-14T17:24:56 | 2016-09-14T17:24:56 | 2016-09-14T17:24:56 | E 5TH ST & COMAL ST, AUSTIN, TX 78702                 |               | 78702    | TRAVIS | 3119361.49958841         | 10068719.0007189         | 30.26214929         | -97.72697005         | 3                | 585Y     | MK22     | September 23, Friday at 7:00am to 5 pm                          | September 23, Friday after 5:00 pm                                               | Eastbound Lane,Westbound Lane | Emergency            |                | 5th steet                          | dirvert to 6th or 7th street                              | Other                         | Peyton Kurio                  | 
| 16-00243848               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-16T09:51:21 | 2016-09-16T09:51:21 | 2016-09-16T09:51:21 | 2016-09-16T09:51:21 | RIO GRANDE ST & W 16TH ST, AUSTIN, TX 78701           |               | 78701    | TRAVIS | 3113243.49739654         | 10074991.0013952         | 30.2797827          | -97.74588135         | 9                | 585J     | MJ23     | 9/20 - 8:00PM                                                   | 9/21 - 6 AM                                                                      | Southbound Lane               | Routine              | 2016-112996-EX | RIO GRANDE ST & W 16TH ST          | N/A                                                       | Other                         | Peabody                       | 
| 16-00247132               | EMROCLRE     | Lane/Road Closure Notification | Transportation    | Phone           | Closed    | 2016-09-19T16:39:10 | 2016-09-19T16:39:10 | 2016-09-19T16:39:10 | 2016-09-19T16:39:10 | S 5TH ST & W OLTORF ST, AUSTIN, TX 78704              |               | 78704    | TRAVIS | 3107719.99944407         | 10061823.0021761         | 30.2439378          | -97.7643387          | 3                | 614Q     | MH20     | 09/22/2016 9:00 a.m.                                            | 09/26/2016 4:00 p.m.                                                             | Westbound Lane,Eastbound Lane | Routine              | 2016094641RW   | s 5th, w oltorf,                   | none                                                      | ATT                           | R&R Ditching                  | 
```