# Weights, Measures, and Other Tests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weights-measures-and-other-tests) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8fei-z6rz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8fei-z6rz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8fei-z6rz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8fei-z6rz |
| Name | Weights, Measures, and Other Tests |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | City Government |
| Tags | dca, wam, inspections |
| Created | 2016-07-25T16:35:59Z |
| Publication Date | 2017-01-27T22:39:17Z |

## Description

This dataset features detailed information about DCA inspections of scales, measuring devices, pricing, and other equipment.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | record_id          | Record ID          | text          | text          |
| Yes      | series tag     | business_name      | Business Name      | text          | text          |
| Yes      | series tag     | industry           | Industry           | text          | text          |
| Yes      | series tag     | certificate_number | Certificate Number | text          | text          |
| Yes      | time           | inspection_date    | Inspection Date    | calendar_date | calendar_date |
| Yes      | series tag     | inspection_result  | Inspection Result  | text          | text          |
| Yes      | series tag     | test_type          | Test Type          | text          | text          |
| Yes      | numeric metric | approved           | Approved           | number        | number        |
| Yes      | numeric metric | condemned          | Condemned          | number        | number        |
| Yes      | numeric metric | confiscated        | Confiscated        | number        | number        |
| Yes      | series tag     | notes              | Notes              | text          | text          |
| Yes      | series tag     | building_number    | Building Number    | text          | text          |
| Yes      | series tag     | street             | Street             | text          | text          |
| Yes      | series tag     | city               | City               | text          | text          |
| Yes      | series tag     | state              | State              | text          | text          |
| Yes      | series tag     | zip                | Zip                | text          | text          |
| Yes      | series tag     | unit               | Unit               | text          | text          |
| No       |                | longitude          | Longitude          | number        | number        |
| No       |                | latitude           | Latitude           | number        | number        |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:8fei-z6rz d:2016-10-17T00:00:00.000Z t:business_name="NICMANDA TRUCKING INC" t:zip=11762 t:inspection_result=Fail t:street="LILAC PL" t:certificate_number=40004444 t:state=NY t:building_number=5 t:industry="Fuel Oil Dealer - 814" t:test_type="TANK TRUCK-72" t:city="MASSAPEQUA PARK" t:record_id=67373-2016-ENFO m:confiscated=0 m:approved=0 m:condemned=1

series e:8fei-z6rz d:2016-10-17T00:00:00.000Z t:business_name="ATLANTIC COAST TRANSPORT GROUP INC" t:zip=10601 t:inspection_result=Fail t:street="MITCHELL PL" t:certificate_number=40004448 t:state=NY t:building_number=9 t:industry="Fuel Oil Dealer - 814" t:test_type="TANK TRUCK-72" t:city="WHITE PLAINS" t:record_id=67340-2016-ENFO m:confiscated=0 m:approved=0 m:condemned=1

series e:8fei-z6rz d:2016-10-18T00:00:00.000Z t:business_name="RAGS FUEL CORP" t:zip=07631 t:inspection_result=Fail t:street="LIBERTY RD" t:certificate_number=40004450 t:state=NJ t:building_number=170 t:industry="Fuel Oil Dealer - 814" t:test_type="PETROL METER TYPE B-22" t:city=ENGLEWOOD t:record_id=67402-2016-ENFO m:confiscated=0 m:approved=0 m:condemned=1
```

## Meta Commands

```ls
metric m:approved p:integer l:Approved d:"The number of items that passed the inspection." t:dataTypeName=number

metric m:condemned p:integer l:Condemned d:"The number of items that DCA condemned." t:dataTypeName=number

metric m:confiscated p:integer l:Confiscated d:"The number of items that DCA confiscated." t:dataTypeName=number

entity e:8fei-z6rz l:"Weights, Measures, and Other Tests" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/8fei-z6rz

property e:8fei-z6rz t:meta.view v:id=8fei-z6rz v:category="City Government" v:averageRating=0 v:name="Weights, Measures, and Other Tests" v:attribution="Department of Consumer Affairs (DCA)"

property e:8fei-z6rz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8fei-z6rz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| record_id       | business_name                      | industry              | certificate_number | inspection_date     | inspection_result | test_type              | approved | condemned | confiscated | notes | building_number | street              | city            | state | zip   | unit | longitude          | latitude           | 
| =============== | ================================== | ===================== | ================== | =================== | ================= | ====================== | ======== | ========= | =========== | ===== | =============== | =================== | =============== | ===== | ===== | ==== | ================== | ================== | 
| 67373-2016-ENFO | NICMANDA TRUCKING INC              | Fuel Oil Dealer - 814 | 40004444           | 2016-10-17T00:00:00 | Fail              | TANK TRUCK-72          | 0        | 1         | 0           |       | 5               | LILAC PL            | MASSAPEQUA PARK | NY    | 11762 |      |                    |                    | 
| 67340-2016-ENFO | ATLANTIC COAST TRANSPORT GROUP INC | Fuel Oil Dealer - 814 | 40004448           | 2016-10-17T00:00:00 | Fail              | TANK TRUCK-72          | 0        | 1         | 0           |       | 9               | MITCHELL PL         | WHITE PLAINS    | NY    | 10601 |      |                    |                    | 
| 67402-2016-ENFO | RAGS FUEL CORP                     | Fuel Oil Dealer - 814 | 40004450           | 2016-10-18T00:00:00 | Fail              | PETROL METER TYPE B-22 | 0        | 1         | 0           |       | 170             | LIBERTY RD          | ENGLEWOOD       | NJ    | 07631 |      |                    |                    | 
| 68681-2016-ENFO | COLDGATE FUEL OIL CORP             | Fuel Oil Dealer - 814 | 40004487           | 2016-10-25T00:00:00 | Pass              | TANK TRUCK-72          | 1        | 0         | 0           |       | 246             | OAK ST              | WEST HEMPSTEAD  | NY    | 11552 |      |                    |                    | 
| 70397-2016-ENFO | C & JJ FODD CORP                   | Supermarket - 819     | 03062254           | 2016-10-24T00:00:00 | Pass              | SCALE TO 33 LBS-01     | 1        | 0         | 0           |       | 760             | CONCOURSE VLG W     | BRONX           | NY    | 10451 |      | -73.92310859321469 | 40.823544523241026 | 
| 69981-2016-ENFO | LITTLE NECK GROCERY INC.           | Supermarket - 819     | 03065606           | 2016-10-25T00:00:00 | Pass              | SCALE TO 33 LBS-01     | 5        | 0         | 0           |       | 24936           | HORACE HARDING EXPY | LITTLE NECK     | NY    | 11362 |      | -73.7312369026548  | 40.76059720859429  | 
| 69978-2016-ENFO | FREDERICK M. WILKLOW               | Grocery-Retail - 808  | 03059674           | 2016-10-21T00:00:00 | Pass              | SCALE TO 33 LBS-01     | 1        | 0         | 0           |       | 4               | SOUTH ST            | NEW YORK        | NY    | 10004 |      | -74.0116311034501  | 40.701694786940216 | 
| 68551-2016-ENFO | NAZMUN INC.                        | Grocery-Retail - 808  | 03065186           | 2016-10-19T00:00:00 | Pass              | SCALE TO 33 LBS-01     | 1        | 0         | 0           |       | 7114            | 35TH AVE            | JACKSON HEIGHTS | NY    | 11372 |      | -73.89466912157464 | 40.750734444193675 | 
| 67642-2016-ENFO | LEWIS OIL CO INC                   | Fuel Oil Dealer - 814 | 40004463           | 2016-10-20T00:00:00 | Pass              | TANK TRUCK-72          | 1        | 0         | 0           |       | 175             | SUNNYSIDE BLVD      | PLAINVIEW       | NY    | 11803 |      |                    |                    | 
| 69618-2016-ENFO | NICMANDA TRUCKING INC              | Fuel Oil Dealer - 814 | 40004703           | 2016-10-27T00:00:00 | Pass              | AIR ELIMINATOR-73      | 1        | 0         | 0           |       | 5               | LILAC PL            | MASSAPEQUA PARK | NY    | 11762 |      |                    |                    | 
```