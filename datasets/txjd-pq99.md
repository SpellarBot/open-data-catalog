# Trade Permits : Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trade-permits-current-e2555) |
| Metadata | [Link](https://data.seattle.gov/api/views/txjd-pq99) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/txjd-pq99/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/txjd-pq99/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | txjd-pq99 |
| Name | Trade Permits : Current |
| Attribution | City of Seattle, Department of Planning and Development |
| Category | Permitting |
| Tags | permit, trade permits, dpd |
| Created | 2010-08-27T17:57:25Z |
| Publication Date | 2017-01-23T20:58:03Z |

## Description

Permits for performing Conveyance, refrigeration, boiler/pressure vessel, mechanical, side sewer, and sign/billboard/awning work, issued in the past five years or currently in progress.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | application_permit_number       | Application/Permit Number       | text          | text          |
| Yes      | series tag     | permit_type                     | Permit Type                     | text          | text          |
| No       |                | address                         | Address                         | text          | text          |
| Yes      | series tag     | description                     | Description                     | text          | text          |
| Yes      | series tag     | category                        | Category                        | text          | text          |
| Yes      | series tag     | action_type                     | Action Type                     | text          | text          |
| Yes      | series tag     | work_type                       | Work Type                       | text          | text          |
| Yes      | numeric metric | value                           | Value                           | money         | money         |
| Yes      | series tag     | applicant_name                  | Applicant Name                  | text          | text          |
| Yes      | time           | application_date                | Application Date                | calendar_date | calendar_date |
| No       |                | issue_date                      | Issue Date                      | calendar_date | calendar_date |
| No       |                | final_date                      | Final Date                      | calendar_date | calendar_date |
| No       |                | expiration_date                 | Expiration Date                 | calendar_date | calendar_date |
| Yes      | series tag     | status                          | Status                          | text          | text          |
| Yes      | series tag     | contractor                      | Contractor                      | text          | text          |
| Yes      | series tag     | permit_and_complaint_status_url | Permit and Complaint Status URL | url           | url           |
| No       |                | latitude                        | Latitude                        | number        | number        |
| No       |                | longitude                       | Longitude                       | number        | number        |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,issue_date,final_date,expiration_date,latitude,longitude
```

## Data Commands

```ls
series e:txjd-pq99 d:2017-01-20T00:00:00.000Z t:permit_type=MECHANICAL t:category="SINGLE FAMILY / DUPLEX" t:action_type=FURNACE t:contractor="AMERICOOL HEATING AND A/C LLC" t:status="Permit Issued" t:description="INSTALLING GAS FURNACE." t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576831" t:applicant_name="AMERICOOL HEATING AND A/C LLC" t:application_permit_number=6576831 m:value=0

series e:txjd-pq99 d:2017-01-20T00:00:00.000Z t:permit_type="BOILER / PRESSURE VESSEL" t:category="SINGLE FAMILY / DUPLEX" t:action_type=NEW t:contractor="GREENWOOD HEATING AND AC" t:status="Permit Issued" t:description="INSTALL BOILER (#3820-659-021826-7738501262)" t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576128" t:applicant_name="GREENWOOD HEATING AND AC" t:application_permit_number=6576128 m:value=0

series e:txjd-pq99 d:2017-01-20T00:00:00.000Z t:permit_type=REFRIGERATION t:category="SINGLE FAMILY / DUPLEX" t:contractor="SELECT AIR SERVICE" t:status="Permit Issued" t:description="INSTALL DUCTLESS HEAT PUMP." t:work_type="No plan review" t:permit_and_complaint_status_url="http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576454" t:applicant_name="SELECT AIR SERVICE" t:application_permit_number=6576454 m:value=0
```

## Meta Commands

```ls
metric m:value p:integer l:Value d:"The value of the work being proposed. The value displayed (if any) represents the best available information to date, and is subject to change as more information becomes available. Value is not collected for all permit types." t:dataTypeName=money

entity e:txjd-pq99 l:"Trade Permits : Current" t:attribution="City of Seattle, Department of Planning and Development" t:url=https://data.seattle.gov/api/views/txjd-pq99

property e:txjd-pq99 t:meta.view v:id=txjd-pq99 v:category=Permitting v:attributionLink=http://www.seattle.gov/dpd v:averageRating=0 v:name="Trade Permits : Current" v:attribution="City of Seattle, Department of Planning and Development"

property e:txjd-pq99 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:txjd-pq99 t:meta.view.owner v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:displayName="Department of Planning and Development"

property e:txjd-pq99 t:meta.view.tableauthor v:id=nmed-fmz8 v:profileImageUrlMedium=/api/users/nmed-fmz8/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmed-fmz8/profile_images/LARGE v:screenName="Department of Planning and Development" v:profileImageUrlSmall=/api/users/nmed-fmz8/profile_images/TINY v:roleName=publisher v:displayName="Department of Planning and Development"
```

## Top Records

```ls
| application_permit_number | permit_type              | address               | description                                  | category               | action_type | work_type      | value | applicant_name                | application_date    | issue_date          | final_date | expiration_date     | status        | contractor                    | permit_and_complaint_status_url                                          | latitude    | longitude     | 
| ========================= | ======================== | ===================== | ============================================ | ====================== | =========== | ============== | ===== | ============================= | =================== | =================== | ========== | =================== | ============= | ============================= | ======================================================================== | =========== | ============= | 
| 6576831                   | MECHANICAL               | 8833 16TH AVE SW      | INSTALLING GAS FURNACE.                      | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | AMERICOOL HEATING AND A/C LLC | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | AMERICOOL HEATING AND A/C LLC | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576831, null] | 47.52369896 | -122.35540181 | 
| 6576128                   | BOILER / PRESSURE VESSEL | 3006 NW 63RD ST       | INSTALL BOILER (#3820-659-021826-7738501262) | SINGLE FAMILY / DUPLEX | NEW         | No plan review | 0     | GREENWOOD HEATING AND AC      | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | GREENWOOD HEATING AND AC      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576128, null] | 47.67466727 | -122.39611189 | 
| 6576454                   | REFRIGERATION            | 1975 NW BLUE RIDGE DR | INSTALL DUCTLESS HEAT PUMP.                  | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | SELECT AIR SERVICE            | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | SELECT AIR SERVICE            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576454, null] | 47.70374037 | -122.38175768 | 
| 6576812                   | MECHANICAL               | 2603 NE 86TH ST       | REPLACE GAS FURNACE.                         | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | GREENWOOD HEATING AND AC      | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | GREENWOOD HEATING AND AC      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576812, null] | 47.69053072 | -122.30034002 | 
| 6577270                   | MECHANICAL               | 4058 31ST AVE W       | INSTALL A DUCTED MINI SPLIT SYSTEM.          | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | HEATING WORKS                 | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | HEATING WORKS                 | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577270, null] | 47.6575564  | -122.39669591 | 
| 6575709                   | CONVEYANCE               | 811 5TH AVE           | TEMP USE PERMIT RC-1                         |                        | TEMP        | Plan Review    | 0     | KONE INC                      | 2017-01-11T00:00:00 | 2017-01-13T00:00:00 |            | 2018-07-13T00:00:00 | Permit Issued | KONE INC                      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6575709, null] | 47.60547767 | -122.33119077 | 
| 6576964                   | REFRIGERATION            | 4625 46TH AVE S       | INSTALL DUCTLESS HEAT PUMP                   | SINGLE FAMILY / DUPLEX |             | No plan review | 0     | SELECT AIR SERVICE            | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | SELECT AIR SERVICE            | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576964, null] | 47.56098002 | -122.27606256 | 
| 6576963                   | MECHANICAL               | 4625 46TH AVE S       | INSTALL DUCTLESS HEAT PUMP                   | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | GREENWOOD HEATING AND AC      | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | GREENWOOD HEATING AND AC      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6576963, null] | 47.56098002 | -122.27606256 | 
| 6577114                   | MECHANICAL               | 4567 35TH AVE W       | REPLACE GAS FURNACE                          | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | GREENWOOD HEATING AND AC      | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | GREENWOOD HEATING AND AC      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577114, null] | 47.66301244 | -122.40283526 | 
| 6577103                   | MECHANICAL               | 7326 26TH AVE NW      | REPLACE GAS FURNACE                          | SINGLE FAMILY / DUPLEX | FURNACE     | No plan review | 0     | GREENWOOD HEATING AND AC      | 2017-01-20T00:00:00 | 2017-01-20T00:00:00 |            | 2018-07-20T00:00:00 | Permit Issued | GREENWOOD HEATING AND AC      | [http://web6.seattle.gov/dpd/PermitStatus/Project.aspx?id=6577103, null] | 47.68217548 | -122.38953802 | 
```