# Capital Projects, NYS Thruway Authority Capital Programs: Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-projects-nys-thruway-authority-capital-programs-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/n5iq-rskv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n5iq-rskv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n5iq-rskv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n5iq-rskv |
| Name | Capital Projects, NYS Thruway Authority Capital Programs: Beginning 2005 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, construction, bridge, roadway, pavement, canal |
| Created | 2013-05-16T20:27:39Z |
| Publication Date | 2013-07-11T10:59:14Z |

## Description

This is a listing of all NYSTA?s capital projects along with a status beginning with the 2005-2011 Capital Programs.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | source                       | SOURCE                       | text          | text          |
| Yes      | series tag     | status                       | STATUS                       | text          | text          |
| No       |                | program_year                 | PROGRAM YEAR                 | number        | number        |
| No       |                | id                           | ID                           | text          | text          |
| Yes      | series tag     | division                     | DIVISION                     | text          | text          |
| Yes      | series tag     | description                  | DESCRIPTION                  | text          | text          |
| No       |                | estimated_letting_date       | ESTIMATED LETTING DATE       | text          | number        |
| Yes      | time           | letting_date                 | LETTING DATE                 | calendar_date | calendar_date |
| No       |                | estimated_completion_date    | ESTIMATED COMPLETION DATE    | text          | number        |
| No       |                | completion_date              | COMPLETION DATE              | calendar_date | calendar_date |
| Yes      | series tag     | contractor                   | CONTRACTOR                   | text          | text          |
| Yes      | series tag     | contract_no                  | CONTRACT NO.                 | text          | text          |
| Yes      | numeric metric | low_bid_amount               | LOW BID AMOUNT               | money         | money         |
| Yes      | numeric metric | approved_construction_amount | APPROVED CONSTRUCTION AMOUNT | money         | money         |
| Yes      | numeric metric | construction_amount          | CONSTRUCTION AMOUNT          | money         | money         |
| No       |                | latitude                     | Latitude                     | number        | number        |
| No       |                | longitude                    | Longitude                    | number        | number        |
```

## Time Field

```ls
Value = letting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,estimated_letting_date,estimated_completion_date,completion_date,latitude,longitude,program_year
```

## Data Commands

```ls
series e:n5iq-rskv d:2013-05-16T13:57:26.000Z t:division="New York" t:source=plan2012 t:status=PLANNED t:description="Ardsley Service Area (MP 6.0 NB): Replace Aging Water Supply Main and Demolition of Obsolete Fire Water Supply System" m:approved_construction_amount=1700000

series e:n5iq-rskv d:2013-05-16T13:57:26.000Z t:division="New York" t:source=plan2012 t:status=PLANNED t:description="MP 45.03: Repair Deteriorating Utility Tunnels at Woodbury Toll Barrier in New York Division" m:approved_construction_amount=500000

series e:n5iq-rskv d:2013-05-16T13:57:26.000Z t:division=Syracuse t:source=plan2012 t:status=PLANNED t:description="Installation of Authority supplied Generators at Indian Castle, Chittenango and Clifton Springs Service Areas" m:approved_construction_amount=750000
```

## Meta Commands

```ls
metric m:low_bid_amount p:double l:"LOW BID AMOUNT" d:"Low Bid for this project." t:dataTypeName=money

metric m:approved_construction_amount p:double l:"APPROVED CONSTRUCTION AMOUNT" d:"The approved funds for this project" t:dataTypeName=money

metric m:construction_amount p:double l:"CONSTRUCTION AMOUNT" d:"Final Construction Value for the project." t:dataTypeName=money

entity e:n5iq-rskv l:"Capital Projects, NYS Thruway Authority Capital Programs: Beginning 2005" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/n5iq-rskv

property e:n5iq-rskv t:meta.view v:id=n5iq-rskv v:category=Transportation v:attributionLink=http://www.thruway.ny.gov/projectsandstudies/capitalprogram/index.html v:averageRating=0 v:name="Capital Projects, NYS Thruway Authority Capital Programs: Beginning 2005" v:attribution="New York State Thruway Authority"

property e:n5iq-rskv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n5iq-rskv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:n5iq-rskv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| source   | status  | program_year | id     | division | description                                                                                                                                     | estimated_letting_date | letting_date | estimated_completion_date | completion_date | contractor | contract_no | low_bid_amount | approved_construction_amount | construction_amount | latitude           | longitude           | 
| ======== | ======= | ============ | ====== | ======== | =============================================================================================================================================== | ====================== | ============ | ========================= | =============== | ========== | =========== | ============== | ============================ | =================== | ================== | =================== | 
| plan2012 | PLANNED | 2012         | A3.1   | New York | Ardsley Service Area (MP 6.0 NB): Replace Aging Water Supply Main and Demolition of Obsolete Fire Water Supply System                           | 2014                   |              |                           |                 |            |             |                | 1700000.00                   |                     | 40.983997000000002 | -73.852874          | 
| plan2012 | PLANNED | 2012         | A347.1 | New York | MP 45.03: Repair Deteriorating Utility Tunnels at Woodbury Toll Barrier in New York Division                                                    | 2013                   |              |                           |                 |            |             |                | 500000.00                    |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A350.1 | Syracuse | Installation of Authority supplied Generators at Indian Castle, Chittenango and Clifton Springs Service Areas                                   | 2013                   |              |                           |                 |            |             |                | 750000.00                    |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A811.1 | New York | MP 33: Ramapo and Sloatsburg Service Areas - Demolition of Aging Wastewater Facility and Construct Connection to Municipal System               | 2013                   |              |                           |                 |            |             |                | 1450000.00                   |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A839.2 | Albany   | MP 141.92: Administrative Headquarters Building - Replacement of Outdated High Voltage Switch Gear System                                       | 2013                   |              |                           |                 |            |             |                | 1640000.00                   |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A842.1 | New York | Sloatsburg Service Area (MP 33.0) and Modena Service Area (MP 66.0): Replacement of Deteriorated Roofs                                          | 2013                   |              |                           |                 |            |             |                | 1000000.00                   |                     | 41.147114000000002 | -74.186171999999999 | 
| plan2012 | PLANNED | 2012         | A855.1 | Syracuse | MP 210: Replacement of Deteriorated Flat Roof at the Indian Castle Service Area                                                                 | 2013                   |              |                           |                 |            |             |                | 500000.00                    |                     | 43.015495000000001 | -74.802992000000003 | 
| plan2012 | PLANNED | 2012         | A856.1 | Syracuse | MP 324W and MP 337E: Replacement of Deteriorated Pitched Roofs at the Junius Ponds and Clifton Springs Service Areas                            | 2013                   |              |                           |                 |            |             |                | 800000.00                    |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A856.2 | Syracuse | MP 324W and MP 337E: Replacement of Deteriorated Flat Roofs at the Junius Ponds and Clifton Springs Service Areas                               | 2013                   |              |                           |                 |            |             |                | 800000.00                    |                     |                    |                     | 
| plan2012 | PLANNED | 2012         | A866.1 | Syracuse | MP's 227 WB, 280 EB, 292 WB and 310 EB: Replacement of Deteriorated Pitched Roofs at the Schuyler, DeWitt, Warners and Port Byron Service Areas | 2014                   |              |                           |                 |            |             |                | 1600000.00                   |                     |                    |                     | 
```