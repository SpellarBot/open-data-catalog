# Consumer Services Mediated Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/consumer-services-mediated-complaints) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nre2-6m2s) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nre2-6m2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nre2-6m2s/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nre2-6m2s |
| Name | Consumer Services Mediated Complaints |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | complaints, mediation, outcomes, city government, business, dca, department of consumer affairs |
| Created | 2015-03-06T20:39:20Z |
| Publication Date | 2016-10-31T13:50:50Z |

## Description

This data set features consumer complaints against businesses that were mediated by the DCA Consumer Services Division during the last and current calendar years. It excludes complaints that may have ongoing legal investigations.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | business_name         | Business Name         | text          | text          |
| Yes      | series tag     | industry              | Industry              | text          | text          |
| Yes      | series tag     | complaint_type        | Complaint Type        | text          | text          |
| Yes      | time           | mediation_start_date  | Mediation Start Date  | calendar_date | calendar_date |
| No       |                | mediation_close_date  | Mediation Close Date  | calendar_date | calendar_date |
| Yes      | series tag     | complaint_result      | Complaint Result      | text          | text          |
| Yes      | series tag     | satisfaction          | Satisfaction          | text          | text          |
| Yes      | numeric metric | restitution           | Restitution           | number        | text          |
| Yes      | series tag     | business_building     | Business Building     | text          | text          |
| Yes      | series tag     | business_street       | Business Street       | text          | text          |
| No       |                | building_address_unit | Building Address Unit | text          | text          |
| Yes      | series tag     | business_city         | Business City         | text          | text          |
| Yes      | series tag     | business_state        | Business State        | text          | text          |
| Yes      | series tag     | business_zip          | Business Zip          | text          | text          |
| Yes      | series tag     | complainant_zip       | Complainant Zip       | text          | text          |
| No       |                | longitude             | Longitude             | number        | text          |
| No       |                | latitude              | Latitude              | number        | text          |
```

## Time Field

```ls
Value = mediation_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mediation_close_date,building_address_unit,longitude,latitude
```

## Data Commands

```ls
series e:nre2-6m2s d:2016-12-14T00:00:00.000Z t:business_name="YORKVILLE CAR PARK, LLC" t:business_building=1651 t:satisfaction=Yes t:complaint_type="Damaged Goods - D01" t:complainant_zip=07078 t:business_zip=10128 t:complaint_result="Cash Amount - AMT" t:business_street="3RD AVE" t:industry="Garage - 049" t:business_city="NEW YORK" t:business_state=NY m:restitution=1710

series e:nre2-6m2s d:2016-06-01T00:00:00.000Z t:business_name="M & L FLORAL ENTERPRISES INC." t:business_building=8816 t:satisfaction=NA t:complaint_type="Non-Delivery of Goods - N01" t:complainant_zip=12589 t:business_zip=11421 t:complaint_result="Complaint Invalid - CIN" t:business_street="JAMAICA AVE" t:industry="Misc Non-Food Retail - 817" t:business_city=WOODHAVEN t:business_state=NY m:restitution=0

series e:nre2-6m2s d:2016-05-04T00:00:00.000Z t:business_name="LEAP EDUCATION SERVICES" t:business_building=25 t:satisfaction=NA t:complaint_type="Non-Delivery of Goods - N01" t:complainant_zip=10029 t:business_zip=10002 t:complaint_result="Complaint Invalid - CIN" t:business_street="DIVISION ST" t:industry="Misc Non-Food Retail - 817" t:business_city="NEW YORK" t:business_state=NY m:restitution=0
```

## Meta Commands

```ls
metric m:restitution p:float l:Restitution d:"Total amount of consumer restitution secured through mediation." t:dataTypeName=number

entity e:nre2-6m2s l:"Consumer Services Mediated Complaints" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/nre2-6m2s

property e:nre2-6m2s t:meta.view v:id=nre2-6m2s v:category=Business v:averageRating=0 v:name="Consumer Services Mediated Complaints" v:attribution="Department of Consumer Affairs (DCA)"

property e:nre2-6m2s t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nre2-6m2s t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| business_name                      | industry                          | complaint_type                          | mediation_start_date | mediation_close_date | complaint_result                      | satisfaction | restitution | business_building | business_street | building_address_unit | business_city    | business_state | business_zip | complainant_zip | longitude          | latitude          | 
| ================================== | ================================= | ======================================= | ==================== | ==================== | ===================================== | ============ | =========== | ================= | =============== | ===================== | ================ | ============== | ============ | =============== | ================== | ================= | 
| YORKVILLE CAR PARK, LLC            | Garage - 049                      | Damaged Goods - D01                     | 2016-12-14T00:00:00  | 2016-12-23T00:00:00  | Cash Amount - AMT                     | Yes          | 1710.00     | 1651              | 3RD AVE         | 207                   | NEW YORK         | NY             | 10128        | 07078           |                    |                   | 
| M & L FLORAL ENTERPRISES INC.      | Misc Non-Food Retail - 817        | Non-Delivery of Goods - N01             | 2016-06-01T00:00:00  | 2016-06-20T00:00:00  | Complaint Invalid - CIN               | NA           | 0.00        | 8816              | JAMAICA AVE     |                       | WOODHAVEN        | NY             | 11421        | 12589           |                    |                   | 
| LEAP EDUCATION SERVICES            | Misc Non-Food Retail - 817        | Non-Delivery of Goods - N01             | 2016-05-04T00:00:00  | 2016-06-08T00:00:00  | Complaint Invalid - CIN               | NA           | 0.00        | 25                | DIVISION ST     |                       | NEW YORK         | NY             | 10002        | 10029           | -73.99610420665974 | 40.71412085311541 | 
| BEAR TRANSPORTATION LLC            | Tow Truck Company - 124           | Misrepresentation - M01                 | 2016-12-20T00:00:00  | 2017-02-07T00:00:00  | Cash Amount - AMT                     | Yes          | 68.00       | 953               | COLGATE AVE     |                       | BRONX            | NY             | 10473        | 10472           |                    |                   | 
| ASHLEY FURNITURE HOME STORE        | Furniture Sales - 242             | Misrepresentation - M01                 | 2016-02-05T00:00:00  | 2016-02-25T00:00:00  | Advised to Sue - ATS                  | No           | 0.00        | 1                 | ASHLEY WAY      |                       | ARCADIA          | WI             | 54612        | 11206           |                    |                   | 
| DONE DEAL COLLISION & RECOVERY INC | Tow Truck Company - 124           | Billing Dispute - B02                   | 2017-02-07T00:00:00  | 2017-03-23T00:00:00  | Advised to Sue - ATS                  | No           | 0.00        | 2920              | 202ND ST        |                       | BAYSIDE          | NY             | 11360        | 11411           |                    |                   | 
| FURNITURE SAVINGS CORP.            | Furniture Sales - 242             | Exchange Goods/Contract Cancelled - E01 | 2016-09-27T00:00:00  | 2016-11-04T00:00:00  | Cash Amount - AMT                     | Yes          | 800.00      | 8708              | QUEENS BLVD     |                       | ELMHURST         | NY             | 11373        | 11237           | -73.87581781421594 | 40.73548502801671 | 
| SURE FIRE FUEL CORP. (#25)         | Misc Non-Food Retail - 817        | Exchange Goods/Contract Cancelled - E01 | 2017-01-11T00:00:00  | 2017-02-24T00:00:00  | Resolved and Consumer Satisfied - SPF | Yes          | 0.00        | 2610              | E TREMONT AVE   |                       | BRONX            | NY             | 10461        | 10469           | -73.84667780034809 | 40.84314784399833 | 
| PATRICK FORRESTER                  | Home Improvement Contractor - 100 | Quality of Work - Q01                   | 2016-03-03T00:00:00  | 2016-05-03T00:00:00  | Referred to Hearing - RTH             | No           | 0.00        | 71                | SCRIBNER AVE    |                       | STATEN ISLAND    | NY             | 10301        | 10026           |                    |                   | 
| EPC MANAGEMENT INC.                | Home Improvement Contractor - 100 | Quality of Work - Q01                   | 2016-07-01T00:00:00  | 2016-08-11T00:00:00  | Referred to Hearing - RTH             | No           | 0.00        | 63                | CENTER ST       |                       | ENGLEWOOD CLIFFS | NJ             | 07632        | 10280           | -74.01725210502414 | 40.70944804111834 | 
```