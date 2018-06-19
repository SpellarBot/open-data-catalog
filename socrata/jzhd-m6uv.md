# Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspections-dcb76) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jzhd-m6uv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jzhd-m6uv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jzhd-m6uv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jzhd-m6uv |
| Name | Inspections |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | city government, business, dca, department of consumer affairs, inspections, compliance, consumer |
| Created | 2016-01-26T14:46:48Z |
| Publication Date | 2016-03-04T23:19:19Z |

## Description

This data set features DCA inspections during the last and current calendar years to ensure compliance with local consumer protection and licensing laws, and State and federal regulations.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | record_id          | Record ID          | text          | text          |
| Yes      | series tag  | certificate_number | Certificate Number | text          | text          |
| Yes      | series tag  | business_name      | Business Name      | text          | text          |
| Yes      | time        | inspection_date    | Inspection Date    | calendar_date | calendar_date |
| Yes      | series tag  | inspection_result  | Inspection Result  | text          | text          |
| Yes      | series tag  | industry           | Industry           | text          | text          |
| Yes      | series tag  | borough            | Borough            | text          | text          |
| Yes      | series tag  | building_number    | Building Number    | text          | text          |
| Yes      | series tag  | street             | Street             | text          | text          |
| Yes      | series tag  | street_2           | Street 2           | text          | text          |
| Yes      | series tag  | unit_type          | Unit Type          | text          | text          |
| Yes      | series tag  | unit               | Unit               | text          | text          |
| Yes      | series tag  | description        | Description        | text          | text          |
| Yes      | series tag  | city               | City               | text          | text          |
| Yes      | series tag  | state              | State              | text          | text          |
| Yes      | series tag  | zip                | Zip                | text          | text          |
| No       |             | longitude          | Longitude          | number        | number        |
| No       |             | latitude           | Latitude           | number        | number        |
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
series e:jzhd-m6uv d:2016-09-14T00:00:00.000Z t:business_name="94 D & H PRODUCE INC." t:unit=1 t:zip=10128 t:inspection_result="No Violation Issued" t:certificate_number=09346560 t:street="2ND AVE" t:state=NY t:building_number=1821 t:unit_type=FRNT t:borough=Manhattan t:industry="Cigarette Retail Dealer - 127" t:city="NEW YORK" t:record_id=60662-2016-ENFO m:row_number.jzhd-m6uv=1

series e:jzhd-m6uv d:2016-12-12T00:00:00.000Z t:business_name="ONE WAY DELI CORP." t:zip=10037 t:inspection_result=Pass t:certificate_number=03060844 t:street="LENOX AVE" t:state=NY t:building_number=619 t:borough=Manhattan t:industry="Grocery-Retail - 808" t:city="NEW YORK" t:record_id=78126-2016-ENFO m:row_number.jzhd-m6uv=2

series e:jzhd-m6uv d:2016-05-05T00:00:00.000Z t:business_name="GENOVESE DRUG STORES, INC." t:zip=11219 t:inspection_result=Pass t:certificate_number=03056722 t:street="FORT HAMILTON PKWY" t:state=NY t:building_number=6423 t:borough=Brooklyn t:industry="Drug Store Retail - 810" t:city=BROOKLYN t:record_id=30123-2016-ENFO m:row_number.jzhd-m6uv=3
```

## Meta Commands

```ls
metric m:row_number.jzhd-m6uv p:long l:"Row Number"

entity e:jzhd-m6uv l:Inspections t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/jzhd-m6uv

property e:jzhd-m6uv t:meta.view v:id=jzhd-m6uv v:category=Business v:averageRating=0 v:name=Inspections v:attribution="Department of Consumer Affairs (DCA)"

property e:jzhd-m6uv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jzhd-m6uv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| record_id       | certificate_number | business_name                          | inspection_date     | inspection_result   | industry                      | borough       | building_number | street             | street_2 | unit_type | unit | description | city          | state | zip   | longitude          | latitude           | 
| =============== | ================== | ====================================== | =================== | =================== | ============================= | ============= | =============== | ================== | ======== | ========= | ==== | =========== | ============= | ===== | ===== | ================== | ================== | 
| 60662-2016-ENFO | 09346560           | 94 D & H PRODUCE INC.                  | 2016-09-14T00:00:00 | No Violation Issued | Cigarette Retail Dealer - 127 | Manhattan     | 1821            | 2ND AVE            |          | FRNT      | 1    |             | NEW YORK      | NY    | 10128 | -73.94790835987693 | 40.783136814586875 | 
| 78126-2016-ENFO | 03060844           | ONE WAY DELI CORP.                     | 2016-12-12T00:00:00 | Pass                | Grocery-Retail - 808          | Manhattan     | 619             | LENOX AVE          |          |           |      |             | NEW YORK      | NY    | 10037 | -73.93816629858274 | 40.81781162969775  | 
| 30123-2016-ENFO | 03056722           | GENOVESE DRUG STORES, INC.             | 2016-05-05T00:00:00 | Pass                | Drug Store Retail - 810       | Brooklyn      | 6423            | FORT HAMILTON PKWY |          |           |      |             | BROOKLYN      | NY    | 11219 | -74.00868256137537 | 40.630986832697104 | 
| 78072-2016-ENFO | 09364759           | KINGS DRUG & SURGICAL CORP.            | 2016-12-08T00:00:00 | No Violation Issued | Cigarette Retail Dealer - 127 | Brooklyn      | 492             | CLARKSON AVE       |          |           |      |             | BROOKLYN      | NY    | 11203 | -73.9430918179898  | 40.65583534402563  | 
| 77311-2016-ENFO | 03058657           | GOLDEN VEGE & GROCERY AT FLATBUSH, INC | 2016-12-07T00:00:00 | Pass                | Grocery-Retail - 808          | Brooklyn      | 1819            | FLATBUSH AVE       |          |           |      |             | BROOKLYN      | NY    | 11210 | -73.93994391198207 | 40.625536791605164 | 
| 57218-2016-ENFO | 40002098           | 20TH AVE FARMERS MARKET INC            | 2016-08-30T00:00:00 | Pass                | Gas Station-Retail - 815      | Queens        | 13005           | 20TH AVE           |          |           |      |             | COLLEGE POINT | NY    | 11356 | -73.83853236699625 | 40.781679569242634 | 
| 63383-2016-ENFO | 09354189           | RED HOOK NEWSSTAND CORP.               | 2016-09-22T00:00:00 | Out of Business     | Grocery-Retail - 808          | Brooklyn      | 56              | LORRAINE ST        |          |           |      |             | BROOKLYN      | NY    | 11231 | -74.00744808592178 | 40.67454386446424  | 
| 64376-2016-ENFO | 09346649           | HANEUL GROUP INC.                      | 2016-09-21T00:00:00 | Warning             | Laundry Jobber - 066          | Manhattan     | 101             | W 58TH ST          |          |           |      |             | NEW YORK      | NY    | 10019 | -73.97712715658254 | 40.765182007690264 | 
| 68203-2016-ENFO | 03054778           | 110 SUTPHIN DELI GROCERY CORP          | 2016-09-09T00:00:00 | Pass                | Grocery-Retail - 808          | Queens        | 11010           | SUTPHIN BLVD       |          |           |      |             | JAMAICA       | NY    | 11435 | -73.79642929892685 | 40.68960851754779  | 
| 61760-2016-ENFO | 50073217           | 843 FOREST FOODS & BAGELS INC.         | 2016-09-24T00:00:00 | No Violation Issued | Cigarette Retail Dealer - 127 | Staten Island | 843             | FOREST AVE         |          |           |      |             | STATEN ISLAND | NY    | 10310 | -74.117441580955   | 40.6289372073898   | 
```