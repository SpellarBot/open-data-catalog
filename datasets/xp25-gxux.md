# LinkNYC New Site Permit Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/linknyc-new-site-permit-applications) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xp25-gxux) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xp25-gxux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xp25-gxux/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xp25-gxux |
| Name | LinkNYC New Site Permit Applications |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | Social Services |
| Created | 2016-04-25T16:05:24Z |
| Publication Date | 2017-03-31T21:25:31Z |

## Description

Proposed New Site applications for “Links” Wi-Fi Provider: LinkNYC - CityBridge, LLC (Free): LinkNYC 1 gigabyte (GB), Free Wi-Fi Internet Kiosks, Free Nation Wide Phone Locals Map

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date_received              | Date_Received              | calendar_date | calendar_date |
| Yes      | series tag     | appl_type                  | Appl_Type                  | text          | text          |
| Yes      | series tag     | cblinkid                   | CBLinkID                   | text          | text          |
| Yes      | series tag     | kiosktype                  | kiosktype                  | text          | text          |
| No       |                | latitude                   | Latitude                   | number        | number        |
| No       |                | longitude                  | Longitude                  | number        | number        |
| Yes      | series tag     | borough                    | Borough                    | text          | text          |
| Yes      | series tag     | zoningnumb                 | ZoningNumb                 | text          | text          |
| No       |                | cb                         | CB                         | number        | number        |
| Yes      | series tag     | building_number            | Building_Number            | text          | number        |
| Yes      | series tag     | street_name                | Street_Name                | text          | text          |
| Yes      | series tag     | cross_street_1             | Cross_Street 1             | text          | text          |
| Yes      | series tag     | cross_street_2             | Cross_Street 2             | text          | text          |
| Yes      | series tag     | linkinbid                  | LinkInBID                  | text          | text          |
| Yes      | series tag     | greenfield_in_bid_location | Greenfield in BID Location | text          | text          |
| Yes      | series tag     | linkinhist                 | LinkInHist                 | text          | text          |
| Yes      | series tag     | landmark_name              | Landmark_Name              | text          | text          |
| Yes      | numeric metric | permit_app                 | permit_app                 | number        | number        |
| Yes      | series tag     | company_na                 | company_na                 | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,cb
```

## Data Commands

```ls
series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-005408 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:linkinbid=NO t:street_name="NEW DORP LANE" t:zoningnumb=C2-1/R3-1 t:linkinhist=NONE t:appl_type="new site" t:building_number=8 t:borough=SI t:cross_street_2="2 STREET" t:cross_street_1="RICHMOND ROAD" m:permit_app=81420

series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-006874 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:linkinbid=NO t:street_name="QUEENS BOULEVARD" t:zoningnumb=C4-5X/FH t:linkinhist=NONE t:appl_type="new site" t:borough=Queens t:cross_street_2="72 AVENUE" t:cross_street_1="71 ROAD" m:permit_app=81450

series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-006876 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:linkinbid=NO t:street_name="QUEENS BOULEVARD" t:zoningnumb=C1-2/R6 t:linkinhist=NONE t:appl_type="new site" t:borough=Queens t:cross_street_2="73 ROAD" t:cross_street_1="73 AVENUE" m:permit_app=81451
```

## Meta Commands

```ls
metric m:permit_app p:integer l:permit_app d:"The new site permit application number." t:dataTypeName=number

entity e:xp25-gxux l:"LinkNYC New Site Permit Applications" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/xp25-gxux

property e:xp25-gxux t:meta.view v:id=xp25-gxux v:category="Social Services" v:averageRating=0 v:name="LinkNYC New Site Permit Applications" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:xp25-gxux t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xp25-gxux t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date_received       | appl_type | cblinkid    | kiosktype        | latitude           | longitude           | borough | zoningnumb | cb | building_number | street_name      | cross_street_1 | cross_street_2      | linkinbid | greenfield_in_bid_location | linkinhist | landmark_name | permit_app | company_na     | 
| =================== | ========= | =========== | ================ | ================== | =================== | ======= | ========== | == | =============== | ================ | ============== | =================== | ========= | ========================== | ========== | ============= | ========== | ============== | 
| 2016-08-19T00:00:00 | new site  | LINK-005408 | advertising unit | 40.575699          | -74.119691000000003 | SI      | C2-1/R3-1  | 2  | 8               | NEW DORP LANE    | RICHMOND ROAD  | 2 STREET            | NO        |                            | NONE       |               | 81420      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006874 | advertising unit | 40.720554          | -73.842586999999995 | Queens  | C4-5X/FH   | 6  |                 | QUEENS BOULEVARD | 71 ROAD        | 72 AVENUE           | NO        |                            | NONE       |               | 81450      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006876 | advertising unit | 40.718952999999999 | -73.838976000000002 | Queens  | C1-2/R6    | 6  |                 | QUEENS BOULEVARD | 73 AVENUE      | 73 ROAD             | NO        |                            | NONE       |               | 81451      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006878 | advertising unit | 40.718328999999997 | -73.837971999999993 | Queens  | C1-2/R6    | 6  |                 | QUEENS BOULEVARD | 73 ROAD        | 75 AVENUE           | NO        |                            | NONE       |               | 81452      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006880 | advertising unit | 40.717891000000002 | -73.836680000000001 | Queens  | C1-2/R6    | 6  |                 | QUEENS BOULEVARD | 75 ROAD        | 76 AVENUE           | NO        |                            | NONE       |               | 81453      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006882 | advertising unit | 40.71725           | -73.835567999999995 | Queens  | C1-2/R6    | 6  |                 | QUEENS BOULEVARD | 76 AVENUE      | 76 ROAD             | NO        |                            | NONE       |               | 81454      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006885 | advertising unit | 40.714860999999999 | -73.832341          | Queens  | C4-4D      | 6  |                 | QUEENS BOULEVARD | 78 AVENUE      | 78 CRESCENT         | NO        |                            | NONE       |               | 81455      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-006987 | advertising unit | 40.711072000000001 | -73.828159999999997 | Queens  | C4-4       | 9  |                 | KEW GARDENS ROAD | 82 ROAD        | 82 DRIVE            | NO        |                            | NONE       |               | 81456      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-018037 | advertising unit | 40.733345999999997 | -73.870835999999997 | Queens  | C1-2/R6    | 4  |                 | QUEENS BOULEVARD | 90 STREET      | WOODHAVEN BOULEVARD | NO        |                            | NONE       |               | 81457      | CityBridge LLC | 
| 2016-08-19T00:00:00 | new site  | LINK-018039 | advertising unit | 40.726323000000001 | -73.853012000000007 | Queens  | C1-2/R7-1  | 6  |                 | QUEENS BOULEVARD | 67 AVENUE      | 67 ROAD             | NO        |                            | NONE       |               | 81459      | CityBridge LLC | 
```