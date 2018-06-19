# Transportation Projects in Your Neighborhood

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportation-projects-in-your-neighborhood) |
| Metadata | [Link](https://data.ny.gov/api/views/rz8t-4kmq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rz8t-4kmq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rz8t-4kmq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rz8t-4kmq |
| Name | Transportation Projects in Your Neighborhood |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | transportation, economic development |
| Created | 2013-02-14T19:40:58Z |
| Publication Date | 2017-04-14T22:02:44Z |

## Description

This data set contains DOT construction project information. The data is refreshed nightly from multiple data sources, therefore the data becomes stale rather quickly.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | series tag     | major_pin                          | Major PIN                          | text          | text          |
| Yes      | series tag     | contract_number                    | Contract Number                    | text          | text          |
| Yes      | series tag     | region                             | Region                             | text          | text          |
| Yes      | series tag     | project_title                      | Project Title                      | text          | text          |
| Yes      | series tag     | project_status                     | Project Description                | text          | text          |
| Yes      | series tag     | status                             | Status                             | text          | text          |
| No       |                | in_future_development_start_date   | In/Future Development Start Date   | text          | text          |
| No       |                | bid_opening_date                   | Bid Opening Date                   | text          | text          |
| No       |                | construction_start_date            | Construction Start Date            | text          | text          |
| No       |                | construction_end_date              | Construction End Date              | text          | text          |
| Yes      | numeric metric | construction_amount                | Construction Amount                | money         | money         |
| Yes      | series tag     | federal_funding                    | Federal Funding                    | text          | text          |
| Yes      | series tag     | state_funding                      | State Funding                      | text          | text          |
| Yes      | series tag     | local_funding                      | Local Funding                      | text          | text          |
| Yes      | series tag     | type_of_work                       | Type of Work                       | text          | text          |
| Yes      | series tag     | public_friendly_description        | Public Friendly Description        | text          | text          |
| No       |                | contract_award_date                | Contract Award Date                | calendar_date | calendar_date |
| Yes      | numeric metric | contract_award_amount              | Contract Award Amount              | money         | money         |
| Yes      | numeric metric | approved_cost_changes              | Approved Cost Changes              | money         | money         |
| Yes      | numeric metric | current_award_amount               | Current Award Amount               | money         | money         |
| Yes      | time           | estimated_or_actual_completed_date | Estimated or Actual Completed Date | calendar_date | calendar_date |
| Yes      | series tag     | schedule_performance               | Schedule Performance               | text          | text          |
| Yes      | series tag     | cost_performance                   | Cost Performance                   | text          | text          |
```

## Time Field

```ls
Value = estimated_or_actual_completed_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = in_future_development_start_date,bid_opening_date,construction_start_date,construction_end_date,contract_award_date
```

## Data Commands

```ls
series e:rz8t-4kmq d:2017-04-14T22:02:29.000Z t:region="10 LONG ISLAND" t:project_status="Construction of 3rd phase of 14 mile shared-use path along the north side of Ocean Parkway. Phase 3 extends between TOBAY and Captree State Park Towns of Oyster Bay, Islip and Babylon, Nassau and Suffolk Counties" t:project_title="OP SHARED USE PATH TOBAY TO CAPTREE" t:local_funding=No t:federal_funding=Yes t:status="In Development" t:type_of_work="This project involves the building or maintenance of bicycle facilities." t:public_friendly_description="Project proposes to construct the 3rd phase of 14 mile shared-use path along the north side of Ocean Parkway. Phase 3 extends between Tobay Beach and Captree State Park in the Towns of Oyster Bay, Islip and Babylon, Nassau and Suffolk Counties." t:major_pin=000616 t:state_funding=Yes m:construction_amount=16900000

series e:rz8t-4kmq d:2017-04-14T22:02:29.000Z t:region="10 LONG ISLAND" t:project_status="NY231 Safety Improvements at NSP Interchange - add a new SB to EB loop ramp, signalize and extend EB to NB ramp and merge it with WB Deforest Road, extend WB to NB ramp deceleration lane, install raised median  Huntington Town, Suffolk County" t:project_title="NY231 SAFETY IMPVTS @ NSP INTCHNG" t:local_funding=No t:federal_funding=Yes t:status="In Development" t:type_of_work="This project involves work to align roads and highways." t:public_friendly_description="This project proposes to reconfigure the NY231 and Northern State Parkway interchange to provide for safer movements. Town of Huntington Suffolk County" t:major_pin=001143 t:state_funding=Yes m:construction_amount=14800000

series e:rz8t-4kmq d:2017-04-14T22:02:29.000Z t:region="10 LONG ISLAND" t:project_status="CONCRETE PAVEMENT REPAIR INCLUDING JOINT SEALING, DIAMOND GRINDING  ON NY231 between Southern State Pkwy and I495 Towns of Babylon and Huntington, Suffolk County" t:project_title="NY231 CONCRETE PVMNT REPAIR SSP-I495" t:local_funding=No t:federal_funding=Yes t:status="In Development" t:type_of_work="This project involves repairing concrete pavement." t:public_friendly_description="This project proposes to provide concrete pavement repairs on NY231 between Southrn State Pkwy and I495 (Long Island Expressway) in the Towns of Babylon and Huntington, Suffolk County to improve efficiency and provide a smoother driving surface and help a" t:major_pin=001144 t:state_funding=Yes m:construction_amount=6900000
```

## Meta Commands

```ls
metric m:construction_amount p:integer l:"Construction Amount" d:"Estimated Construction amount for Projects ?In Development? or ?Future Development? Status" t:dataTypeName=money

metric m:contract_award_amount p:double l:"Contract Award Amount" d:"Contract Award Cost" t:dataTypeName=money

metric m:approved_cost_changes p:double l:"Approved Cost Changes" d:"Approved Cost Changes" t:dataTypeName=money

metric m:current_award_amount p:double l:"Current Award Amount" d:"Current construction contract cost" t:dataTypeName=money

entity e:rz8t-4kmq l:"Transportation Projects in Your Neighborhood" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/rz8t-4kmq

property e:rz8t-4kmq t:meta.view v:id=rz8t-4kmq v:category=Transportation v:attributionLink=https://www.dot.ny.gov/projects v:averageRating=0 v:name="Transportation Projects in Your Neighborhood" v:attribution="New York State Department of Transportation"

property e:rz8t-4kmq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rz8t-4kmq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rz8t-4kmq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| major_pin | contract_number | region         | project_title                        | project_status                                                                                                                                                                                                                                             | status             | in_future_development_start_date | bid_opening_date | construction_start_date | construction_end_date | construction_amount | federal_funding | state_funding | local_funding | type_of_work                                                                                                       | public_friendly_description                                                                                                                                                                                                                                     | contract_award_date | contract_award_amount | approved_cost_changes | current_award_amount | estimated_or_actual_completed_date | schedule_performance | cost_performance | 
| ========= | =============== | ============== | ==================================== | ========================================================================================================================================================================================================================================================== | ================== | ================================ | ================ | ======================= | ===================== | =================== | =============== | ============= | ============= | ================================================================================================================== | =============================================================================================================================================================================================================================================================== | =================== | ===================== | ===================== | ==================== | ================================== | ==================== | ================ | 
| 000616    |                 | 10 LONG ISLAND | OP SHARED USE PATH TOBAY TO CAPTREE  | Construction of 3rd phase of 14 mile shared-use path along the north side of Ocean Parkway. Phase 3 extends between TOBAY and Captree State Park Towns of Oyster Bay, Islip and Babylon, Nassau and Suffolk Counties                                       | In Development     | Summer 2014                      | Spring 2019      | Summer 2019             | Summer 2020           | 16900000            | Yes             | Yes           | No            | This project involves the building or maintenance of bicycle facilities.                                           | Project proposes to construct the 3rd phase of 14 mile shared-use path along the north side of Ocean Parkway. Phase 3 extends between Tobay Beach and Captree State Park in the Towns of Oyster Bay, Islip and Babylon, Nassau and Suffolk Counties.            |                     |                       |                       |                      |                                    |                      |                  | 
| 001143    |                 | 10 LONG ISLAND | NY231 SAFETY IMPVTS @ NSP INTCHNG    | NY231 Safety Improvements at NSP Interchange - add a new SB to EB loop ramp, signalize and extend EB to NB ramp and merge it with WB Deforest Road, extend WB to NB ramp deceleration lane, install raised median Huntington Town, Suffolk County          | In Development     | Winter 2012/2013                 | Summer 2017      | Summer 2017             | Fall 2018             | 14800000            | Yes             | Yes           | No            | This project involves work to align roads and highways.                                                            | This project proposes to reconfigure the NY231 and Northern State Parkway interchange to provide for safer movements. Town of Huntington Suffolk County                                                                                                         |                     |                       |                       |                      |                                    |                      |                  | 
| 001144    |                 | 10 LONG ISLAND | NY231 CONCRETE PVMNT REPAIR SSP-I495 | CONCRETE PAVEMENT REPAIR INCLUDING JOINT SEALING, DIAMOND GRINDING ON NY231 between Southern State Pkwy and I495 Towns of Babylon and Huntington, Suffolk County                                                                                           | In Development     | Winter 2015/2016                 | Spring 2017      | Spring 2017             | Fall 2018             | 6900000             | Yes             | Yes           | No            | This project involves repairing concrete pavement.                                                                 | This project proposes to provide concrete pavement repairs on NY231 between Southrn State Pkwy and I495 (Long Island Expressway) in the Towns of Babylon and Huntington, Suffolk County to improve efficiency and provide a smoother driving surface and help a |                     |                       |                       |                      |                                    |                      |                  | 
| 001625    | D262794         | 10 LONG ISLAND | NY112 3R GRANNY RD TO NY25           | Reconstruct NY112 between Granny Rd and NY25 from 2 to 3 lanes including center left turn lane / median and shoulders/bike lane, pavement reconstruction, sidewalk, signing, signals and drainage. Town of Brookhaven, Suffolk County                      | Under Construction |                                  | 02/05/2015       |                         |                       |                     | No              | Yes           | No            | This project involves the widening of highways.                                                                    | This project proposes to reconstruct approximately 1.5 miles of NY Route 112, between Granny Road and NY Route 25, in the Town of Brookhaven, Suffolk County. It will improve motorist and pedestrian safety, reduce accidents, and improve traffic flow for ap | 2015-03-16T00:00:00 | 16661661.61           | 0                     | 16661661.61          | 2017-04-26T00:00:00                | GREEN                | GREEN            | 
| 001627    |                 | 10 LONG ISLAND | NY112 RECONS I495 TO GRANNY RD       | Reconstruction of NY112 between I495 and Granny Rd including safety improvements at the intersection of NY112 and Horseblock Rd (CR16), improved bike/ped facilities, center left turn lane and 5 foot wide shoulders. Town of Brookhaven, Suffolk County. | In Development     | Fall 2014                        | Spring 2018      | Summer 2018             | Summer 2020           | 31400000            | Yes             | Yes           | No            | This project involves the widening of highways.                                                                    | This project proposes to provide safety improvements at the intersection of NY112 and Horseblock Rd (CR16), widening of NY112 between I495 (Long Island Expressway) and Granny Rd, to provide 12 foot travel lanes in both directions, a 13 foot two way left t |                     |                       |                       |                      |                                    |                      |                  | 
| 003014    |                 | 10 LONG ISLAND | NY454 DRAINAGE FEUERISEN TO JOHNSON  | DRAINAGE RECONSTRUCTION ON NY454 BETWEEN FEUERISEN AVE AND JOHNSON AVE INCLUDING A NEW CLOSED CONDUIT DRAINAGE SYSTEM AND RECHARGE BASINS IN ISLIP TOWN, SUFFOLK COUNTY.                                                                                   | In Development     | Fall 2005                        | Spring 2018      | Summer 2018             | Spring 2020           | 8600000             | Yes             | Yes           | No            | This project involves improvements for drainage along bridges and roads.                                           | This project proposes to upgrade the drainage with the installation of a new drainage system and recharge basins on NY Route 454 (Veterans Memorial Highway) between Feuerisen and Johnson Avenues in the Town of Islip, Suffolk County                         |                     |                       |                       |                      |                                    |                      |                  | 
| 003015    |                 | 10 LONG ISLAND | NY454 DRAINAGE JOHNSON TO BROADWAY   | RECONSTRUCT DARAINAGE ALONG NY454 BETWEEN JOHNSON AVE AND BROADWAY AVE INCLUDING A NEW CLOSED CONDUIT SYSTEM AND RECHARGE BASINS Town of Islip, Suffolk County                                                                                             | In Development     | Fall 2005                        | Winter 2019/2020 | Spring 2020             | Spring 2021           | 6300000             | No              | Yes           | No            | This project involves improvements for drainage along bridges and roads.                                           | The drainage on NY Route 454 (Veterans Memorial Highway) between Johnson and Broadway Avenues in the Town of Islip, Suffolk County, is proposed to be upgraded with the installation of a new drainage system and recharge basins.                              |                     |                       |                       |                      |                                    |                      |                  | 
| 003016    |                 | 10 LONG ISLAND | NY454 & NY27 ITS                     | INSTALL ITS ALONG NY27 AND NY454 IN ISLIP AND BROOKHAVEN TOWNS, Suffolk County                                                                                                                                                                             | Future Development | Fall 2005                        | Fall 2025        | Fall 2025               | Fall 2027             | 12700000            | Yes             | Yes           | No            | This project involves various technologies to assist in managing traffic to improve flow, safety, and air quality. | This project proposes to install ITS (Intelligent Transportation Systems) along NY27 AND NY454 in Islip and Brookhaven Towns, Suffolk County                                                                                                                    |                     |                       |                       |                      |                                    |                      |                  | 
| 004218    |                 | 10 LONG ISLAND | NY25 & NY110 INTERSECTION IMPVTS     | IMPROVE NY110 SOUTHBOUND @ NY25 ,NY25 NY110 TO NEW YORK AVE; CONSTRUCT ONE-WAY NEW ROAD TO ALLOW FOR WESTBOUND LEFT TURNS; EASTBOUND LEFT TURNS WILL BE DIVERTED TO NEW YORK AVE, HUNTINGTON TOWN, SUFFOLK COUNTY.                                         | In Development     | Spring 1996                      | Spring 2025      | Spring 2025             | Summer 2026           | 6900000             | Yes             | Yes           | No            | This project involves reconstruction of intersections.                                                             | This project proposes to improve motorist and pedestrian safety, reduce accidents, and improve traffic flow by reconstructing a section of NY Routes 25 and NY Route 110 within a half mile of their intersection in the Town of Huntington, Suffolk County. Th |                     |                       |                       |                      |                                    |                      |                  | 
| 004233    | D262708         | 10 LONG ISLAND | NY25 OVER I495 BRIDGE REPAIR         | BRIDGE REPAIR OF NY25 OVER I495 IN RIVERHEAD TOWN, SUFFOLK COUNTY. BIN 1056219                                                                                                                                                                             | Under Construction | Winter 2006/2007                 | 12/04/2014       |                         |                       |                     | Yes             | Yes           | No            | This project involves general bridge repairs.                                                                      | This project proposes to repair the structure that carries NY Route 25 over the Long Island Expressway (I495) in the Town of Riverhead, Suffolk County. It will improve the service life of the bridge and ensure the safety of the traveling public.           | 2015-01-30T00:00:00 | 10232905.3            | 666124.48             | 10899029.78          | 2016-08-01T00:00:00                | GREEN                | YELLOW           | 
```