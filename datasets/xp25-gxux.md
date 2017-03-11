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
| Publication Date | 2016-11-18T17:34:57Z |
| Rows Updated | 2016-11-18T17:33:44Z |

## Description

Proposed New Site applications for ?Links? Wi-Fi Provider: LinkNYC - CityBridge, LLC (Free): LinkNYC 1 gigabyte (GB), Free Wi-Fi Internet Kiosks, Free Nation Wide Phone Locals Map

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | date_received   | Date_Received   | calendar_date | calendar_date |
| Yes      | series tag     | appl_type       | Appl_Type       | text          | text          |
| Yes      | series tag     | cblinkid        | CBLinkID        | text          | text          |
| Yes      | series tag     | kiosktype       | kiosktype       | text          | text          |
| No       |                | latitude        | Latitude        | number        | number        |
| No       |                | longitude       | Longitude       | number        | number        |
| Yes      | series tag     | borough         | Borough         | text          | text          |
| Yes      | series tag     | zoningnumb      | ZoningNumb      | text          | text          |
| No       |                | cb              | CB              | number        | number        |
| Yes      | numeric metric | building_number | Building_Number | number        | number        |
| Yes      | series tag     | street_name     | Street_Name     | text          | text          |
| Yes      | series tag     | cross_street_1  | Cross_Street 1  | text          | text          |
| Yes      | series tag     | cross_street_2  | Cross_Street 2  | text          | text          |
| Yes      | series tag     | linkinhist      | LinkInHist      | text          | text          |
| Yes      | series tag     | landmark_name   | Landmark_Name   | text          | text          |
| Yes      | series tag     | pavementty      | PavementTy      | text          | text          |
| Yes      | series tag     | linkinbid       | LinkInBID       | text          | text          |
| Yes      | series tag     | bid_name        | BID_Name        | text          | text          |
| Yes      | numeric metric | permit_app      | permit_app      | number        | number        |
| Yes      | series tag     | company_na      | company_na      | text          | text          |
| Yes      | series tag     | linkinsadname   | LinkInSADName   | text          | text          |
| Yes      | series tag     | linkinsad       | LinkInSAD       | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cb,longitude,latitude
```

## Data Commands

```ls
series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-005408 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:pavementty="2 STREET" t:linkinbid=NO t:street_name="NEW DORP LANE" t:zoningnumb=C2-1/R3-1 t:linkinhist=NONE t:appl_type="new site" t:borough=SI t:cross_street_2="2 STREET" t:cross_street_1="RICHMOND ROAD" m:permit_app=81420 m:building_number=8

series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-006874 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:pavementty="72 AVENUE" t:linkinbid=NO t:street_name="QUEENS BOULEVARD" t:zoningnumb=C4-5X/FH t:linkinhist=NONE t:appl_type="new site" t:borough=Queens t:cross_street_2="72 AVENUE" t:cross_street_1="71 ROAD" m:permit_app=81450

series e:xp25-gxux d:2016-08-19T00:00:00.000Z t:cblinkid=LINK-006876 t:company_na="CityBridge LLC" t:kiosktype="advertising unit" t:pavementty="73 ROAD" t:linkinbid=NO t:street_name="QUEENS BOULEVARD" t:zoningnumb=C1-2/R6 t:linkinhist=NONE t:appl_type="new site" t:borough=Queens t:cross_street_2="73 ROAD" t:cross_street_1="73 AVENUE" m:permit_app=81451
```

## Meta Commands

```ls
metric m:building_number p:integer l:Building_Number t:dataTypeName=number

metric m:permit_app p:integer l:permit_app t:dataTypeName=number

entity e:xp25-gxux l:"LinkNYC New Site Permit Applications" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/xp25-gxux

property e:xp25-gxux t:meta.view d:2017-03-10T14:17:48.539Z v:id=xp25-gxux v:category="Social Services" v:averageRating=0 v:name="LinkNYC New Site Permit Applications" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:xp25-gxux t:meta.view.owner d:2017-03-10T14:17:48.539Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:xp25-gxux t:meta.view.tableauthor d:2017-03-10T14:17:48.539Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```