# 311 Unified Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-unified-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/i26j-ai4z) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/i26j-ai4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/i26j-ai4z/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | i26j-ai4z |
| Name | 311 Unified Data |
| Category | Government |
| Tags | 311, 3-1-1, csr, sr, service request, service requests, austin311, austin 311 |
| Created | 2013-12-30T19:11:01Z |
| Publication Date | 2017-03-02T20:15:59Z |

## Description

Data collected from CSR production system. Data begins 01/03/2014 and is refreshed every half-hour. For more info: http://austintexas.gov/department/311/socrata

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                        | Data Type     | Render Type   |
| ======== | ============== | ============================ | =========================== | ============= | ============= |
| Yes      | series tag     | sr_number                    | Service Request (SR) Number | text          | text          |
| Yes      | series tag     | sr_type_code                 | SR Type Code                | text          | text          |
| Yes      | series tag     | sr_type_desc                 | SR Description              | text          | text          |
| Yes      | series tag     | sr_department_desc           | Owning Department           | text          | text          |
| Yes      | series tag     | sr_method_received_desc      | Method Received             | text          | text          |
| Yes      | series tag     | sr_status_desc               | SR Status                   | text          | text          |
| Yes      | time           | sr_status_date               | Status Change Date          | calendar_date | calendar_date |
| No       |                | sr_created_date              | Created Date                | calendar_date | calendar_date |
| No       |                | sr_updated_date              | Last Update Date            | calendar_date | calendar_date |
| No       |                | sr_closed_date               | Close Date                  | calendar_date | calendar_date |
| Yes      | series tag     | sr_location                  | SR Location                 | text          | text          |
| Yes      | series tag     | sr_location_street_number    | Street Number               | text          | text          |
| Yes      | series tag     | sr_location_street_name      | Street Name                 | text          | text          |
| Yes      | series tag     | sr_location_city             | City                        | text          | text          |
| Yes      | series tag     | sr_location_zip_code         | Zip Code                    | text          | text          |
| Yes      | series tag     | sr_location_county           | County                      | text          | text          |
| Yes      | numeric metric | sr_location_x                | State Plane X Coordinate    | number        | text          |
| Yes      | numeric metric | sr_location_y                | State Plane Y Coordinate    | number        | text          |
| No       |                | sr_location_lat              | Latitude Coordinate         | number        | number        |
| No       |                | sr_location_long             | Longitude Coordinate        | number        | number        |
| Yes      | series tag     | sr_location_council_district | Council District            | text          | number        |
| Yes      | series tag     | sr_location_map_page         | Map Page                    | text          | text          |
| Yes      | series tag     | sr_location_map_tile         | Map Tile                    | text          | text          |
```

## Time Field

```ls
Value = sr_status_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = sr_created_date,sr_updated_date,sr_closed_date,sr_location_lat,sr_location_long
```

## Data Commands

```ls
series e:i26j-ai4z d:2016-05-06T12:11:57.000Z t:sr_type_desc="Traffic Signal - Maintenance" t:sr_location_council_district=10 t:sr_type_code=TRASIGMA t:sr_location_map_page=584C t:sr_number=16-00107769 t:sr_location_city=AUSTIN t:sr_location="WINDSOR RD & EXPOSITION BLVD, AUSTIN, TX 78703" t:sr_location_zip_code=78703 t:sr_location_street_name="WINDSOR RD & EXPOSITION BLVD" t:sr_status_desc="Duplicate (closed)" t:sr_location_map_tile=MH24 t:sr_location_county=TRAVIS t:sr_method_received_desc=Phone t:sr_department_desc=Transportation m:sr_location_x=3106038.49745799 m:sr_location_y=10080978.0030157

series e:i26j-ai4z d:2016-05-06T19:51:27.000Z t:sr_type_desc="Traffic Signal - Maintenance" t:sr_location_map_page=643M t:sr_location_street_number=6001 t:sr_number=16-00108244 t:sr_location="6001 MANCHACA RD, AUSTIN, TX 78745" t:sr_location_zip_code=78745 t:sr_location_county=TRAVIS t:sr_type_code=TRASIGMA t:sr_location_council_district=5 t:sr_location_city=AUSTIN t:sr_status_desc="Duplicate (closed)" t:sr_location_street_name=MANCHACA t:sr_location_map_tile=MF17 t:sr_method_received_desc=Phone t:sr_department_desc=Transportation m:sr_location_x=3096240.5 m:sr_location_y=10050194

series e:i26j-ai4z d:2016-05-06T20:22:56.000Z t:sr_type_desc="Traffic Signal - Maintenance" t:sr_location_map_page=643M t:sr_location_street_number=6001 t:sr_number=16-00108269 t:sr_location="6001 MANCHACA RD, AUSTIN, TX 78745" t:sr_location_zip_code=78745 t:sr_location_county=TRAVIS t:sr_type_code=TRASIGMA t:sr_location_council_district=5 t:sr_location_city=AUSTIN t:sr_status_desc="Duplicate (closed)" t:sr_location_street_name=MANCHACA t:sr_location_map_tile=MF17 t:sr_method_received_desc=Phone t:sr_department_desc=Transportation m:sr_location_x=3096240.5 m:sr_location_y=10050194
```

## Meta Commands

```ls
metric m:sr_location_x p:double l:"State Plane X Coordinate" d:"State plane X coordinate." t:dataTypeName=number

metric m:sr_location_y p:double l:"State Plane Y Coordinate" d:"State plane Y coordinate." t:dataTypeName=number

entity e:i26j-ai4z l:"311 Unified Data" t:url=https://data.austintexas.gov/api/views/i26j-ai4z

property e:i26j-ai4z t:meta.view v:id=i26j-ai4z v:category=Government v:averageRating=0 v:name="311 Unified Data"

property e:i26j-ai4z t:meta.view.owner v:id=xy86-z82g v:screenName="Austin 311" v:displayName="Austin 311"

property e:i26j-ai4z t:meta.view.tableauthor v:id=xy86-z82g v:screenName="Austin 311" v:roleName=publisher v:displayName="Austin 311"
```

## Top Records

```ls
| sr_number   | sr_type_code | sr_type_desc                 | sr_department_desc       | sr_method_received_desc | sr_status_desc     | sr_status_date      | sr_created_date     | sr_updated_date     | sr_closed_date      | sr_location                                      | sr_location_street_number | sr_location_street_name      | sr_location_city | sr_location_zip_code | sr_location_county | sr_location_x    | sr_location_y    | sr_location_lat | sr_location_long | sr_location_council_district | sr_location_map_page | sr_location_map_tile | 
| =========== | ============ | ============================ | ======================== | ======================= | ================== | =================== | =================== | =================== | =================== | ================================================ | ========================= | ============================ | ================ | ==================== | ================== | ================ | ================ | =============== | ================ | ============================ | ==================== | ==================== | 
| 16-00107769 | TRASIGMA     | Traffic Signal - Maintenance | Transportation           | Phone                   | Duplicate (closed) | 2016-05-06T12:11:57 | 2016-05-06T12:01:46 | 2016-05-06T12:11:57 | 2016-05-06T12:11:57 | WINDSOR RD & EXPOSITION BLVD, AUSTIN, TX 78703   |                           | WINDSOR RD & EXPOSITION BLVD | AUSTIN           | 78703                | TRAVIS             | 3106038.49745799 | 10080978.0030157 | 30.29669887     | -97.76826374     | 10                           | 584C                 | MH24                 | 
| 16-00108244 | TRASIGMA     | Traffic Signal - Maintenance | Transportation           | Phone                   | Duplicate (closed) | 2016-05-06T19:51:27 | 2016-05-06T19:51:27 | 2016-05-06T19:51:27 | 2016-05-06T19:51:27 | 6001 MANCHACA RD, AUSTIN, TX 78745               | 6001                      | MANCHACA                     | AUSTIN           | 78745                | TRAVIS             | 3096240.5        | 10050194         | 30.2126949      | -97.8015215      | 5                            | 643M                 | MF17                 | 
| 16-00108269 | TRASIGMA     | Traffic Signal - Maintenance | Transportation           | Phone                   | Duplicate (closed) | 2016-05-06T20:22:56 | 2016-05-06T20:22:56 | 2016-05-06T20:22:56 | 2016-05-06T20:22:56 | 6001 MANCHACA RD, AUSTIN, TX 78745               | 6001                      | MANCHACA                     | AUSTIN           | 78745                | TRAVIS             | 3096240.5        | 10050194         | 30.2126949      | -97.8015215      | 5                            | 643M                 | MF17                 | 
| 16-00324071 | SWSDEADA     | ARR Dead Animal Collection   | Austin Resource Recovery | Phone                   | Closed             | 2016-12-15T09:05:43 | 2016-12-15T06:41:40 | 2016-12-15T09:05:43 | 2016-12-15T09:05:43 | 2200 E OLTORF ST, AUSTIN, TX 78741               | 2200                      | OLTORF                       | AUSTIN           | 78741                | TRAVIS             | 3118116.50749136 | 10057053.9397969 | 30.23016411     | -97.73177647     | 3                            | 615X                 | MJ19                 | 
| 16-00108062 | TRASIGMA     | Traffic Signal - Maintenance | Transportation           | Phone                   | Duplicate (closed) | 2016-05-10T16:56:52 | 2016-05-06T17:03:45 | 2016-05-10T16:56:52 | 2016-05-10T16:56:52 | 8401 N CAPITAL OF TEXAS HWY NB, AUSTIN, TX 78759 | 8401                      | CAPITAL OF TEXAS             | AUSTIN           | 78759                | TRAVIS             | 3105863.35797435 | 10113092.5341337 | 30.38498865     | -97.76647071     | 10                           | 494L                 | MH32                 | 
| 16-00107654 | STREETL2     | Street Light Issue- Address  | Austin Energy Department | Phone                   | Closed             | 2016-05-10T06:58:01 | 2016-05-06T10:28:16 | 2016-05-10T06:58:01 | 2016-05-10T06:58:01 | 300 WEST AVE, AUSTIN, TX 78703                   | 300                       | WEST                         | AUSTIN           | 78703                | TRAVIS             | 3111493.73999999 | 10070696.54      | 30.26808964     | -97.75173887     | 9                            | 584V                 | MH22                 | 
| 16-00107641 | STREETL2     | Street Light Issue- Address  | Austin Energy Department | Phone                   | Closed             | 2016-05-11T16:41:32 | 2016-05-06T10:19:24 | 2016-05-11T16:41:33 | 2016-05-11T16:41:32 | 1212 BEGONIA TER, AUSTIN, TX 78741               | 1212                      | BEGONIA                      | AUSTIN           | 78741                | TRAVIS             | 3127314.74792452 | 10058154.0013629 | 30.23259324     | -97.70257675     | 3                            | 616W                 | ML19                 | 
| 16-00107655 | STREETL2     | Street Light Issue- Address  | Austin Energy Department | Phone                   | Closed             | 2016-05-11T16:42:25 | 2016-05-06T10:29:40 | 2016-05-11T16:42:26 | 2016-05-11T16:42:25 | 7432 ELK PASS DR, AUSTIN, TX 78744               | 7432                      | ELK PASS                     | AUSTIN           | 78744                | TRAVIS             | 3130322.58738476 | 10046378.9104246 | 30.20002989     | -97.6939397      | 2                            | 646T                 | ML16                 | 
| 16-00107684 | STREETL2     | Street Light Issue- Address  | Austin Energy Department | Spot311 Interface       | Closed             | 2016-05-11T16:43:10 | 2016-05-06T10:50:02 | 2016-05-11T16:43:11 | 2016-05-11T16:43:10 | 1820 TREADWELL ST, AUSTIN, TX 78704              | 1820                      | TREADWELL                    | AUSTIN           | 78704                | TRAVIS             | 3106296.99838993 | 10067557.0008973 | 30.25979001     | -97.76842531     | 5                            | 614C                 | MH21                 | 
| 16-00107711 | STREETL2     | Street Light Issue- Address  | Austin Energy Department | Phone                   | Closed             | 2016-05-11T16:43:54 | 2016-05-06T11:12:06 | 2016-05-11T16:43:55 | 2016-05-11T16:43:54 | 111 ATTAYAC ST, AUSTIN, TX 78702                 | 111                       | ATTAYAC                      | AUSTIN           | 78702                | TRAVIS             | 3118045.49753782 | 10067920.0003881 | 30.26003767     | -97.7311965      | 3                            | 615B                 | MJ21                 | 
```