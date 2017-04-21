# Open Budget Application: Capital Projects List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-capital-projects-list-e2355) |
| Metadata | [Link](https://data.seattle.gov/api/views/sar3-57ew) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/sar3-57ew/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/sar3-57ew/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | sar3-57ew |
| Name | Open Budget Application: Capital Projects List |
| Category | Finance |
| Created | 2014-09-22T23:00:46Z |
| Publication Date | 2016-08-11T20:35:46Z |

## Description

data powering openbudget.seattle.gov

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | project_id          | Project_id          | text      | text        |
| Yes      | series tag     | project_name        | Project_name        | text      | text        |
| Yes      | series tag     | project_description | Project_Description | text      | text        |
| No       |                | address             | Address             | text      | text        |
| Yes      | numeric metric | current_phase       | Current_Phase       | number    | text        |
| Yes      | series tag     | current_phase_type  | Current_Phase_Type  | text      | text        |
| Yes      | series tag     | project_details_url | Project_Details_URL | text      | text        |
| Yes      | series tag     | regions             | Regions             | text      | text        |
| No       |                | latitude            | Latitude            | number    | number      |
| No       |                | longitude           | Longitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:sar3-57ew d:2015-09-28T12:59:42.000Z t:project_details_url=http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm t:project_name="Special Work Equipment - Generation Plant" t:project_id=6102 t:current_phase_type="Rehabilitation or Restoration" t:project_description="This ongoing project provides for the purchase of machinery and tools, and special work equipment to be used for operations activities of the Generation Branch, which include all the utility's generating sites, to ensure timely and efficient maintenance of generation facilities. Purchases are based on a five-year plan to ensure updates for technological improvements." m:current_phase=1

series e:sar3-57ew d:2015-09-28T12:59:42.000Z t:project_details_url=http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm t:project_name="Skagit - Sewer System Rehabilitation" t:project_id=6232 t:current_phase_type="Rehabilitation or Restoration" t:project_description="This project replaces or repairs numerous sewer pipe breaks, leaks, and sags in the combined Skagit River sewer/drainage collection system, located at the Diablo Dam site. This project eliminates potential overloads in the sewage treatment plant that can cause pollution of the Skagit River and surrounding soil contamination." m:current_phase=1

series e:sar3-57ew d:2015-09-28T12:59:42.000Z t:project_details_url=http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm t:project_name="Cedar Falls Powerhouse - Valvehouse Rehabilitation" t:project_id=6324 t:current_phase_type="Rehabilitation or Restoration" t:project_description="This project provides rehabilitation to the Cedar Falls Valvehouse. The extent of the rehabilitation is yet to be determined, but could include exterior structural improvements, replacement of windows, oil spill prevention, and interior remodeling." m:current_phase=1
```

## Meta Commands

```ls
metric m:current_phase p:integer l:Current_Phase t:dataTypeName=number

entity e:sar3-57ew l:"Open Budget Application: Capital Projects List" t:url=https://data.seattle.gov/api/views/sar3-57ew

property e:sar3-57ew t:meta.view v:id=sar3-57ew v:category=Finance v:averageRating=0 v:name="Open Budget Application: Capital Projects List"

property e:sar3-57ew t:meta.view.license v:name="Public Domain"

property e:sar3-57ew t:meta.view.owner v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:displayName="Kirk, Daniel"

property e:sar3-57ew t:meta.view.tableauthor v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:roleName=administrator v:displayName="Kirk, Daniel"
```

## Top Records

```ls
| :updated_at | project_id | project_name                                           | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | address                                       | current_phase | current_phase_type            | project_details_url                                                 | regions | latitude | longitude | 
| =========== | ========== | ====================================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============================================= | ============= | ============================= | =================================================================== | ======= | ======== | ========= | 
| 1443445182  | 6102       | Special Work Equipment - Generation Plant              | This ongoing project provides for the purchase of machinery and tools, and special work equipment to be used for operations activities of the Generation Branch, which include all the utility's generating sites, to ensure timely and efficient maintenance of generation facilities. Purchases are based on a five-year plan to ensure updates for technological improvements.                                                                                                                                                                                                                                                                              | Outside the City of Seattle                   | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6232       | Skagit - Sewer System Rehabilitation                   | This project replaces or repairs numerous sewer pipe breaks, leaks, and sags in the combined Skagit River sewer/drainage collection system, located at the Diablo Dam site. This project eliminates potential overloads in the sewage treatment plant that can cause pollution of the Skagit River and surrounding soil contamination.                                                                                                                                                                                                                                                                                                                         | Milepost 126 State Highway 20                 | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6324       | Cedar Falls Powerhouse - Valvehouse Rehabilitation     | This project provides rehabilitation to the Cedar Falls Valvehouse. The extent of the rehabilitation is yet to be determined, but could include exterior structural improvements, replacement of windows, oil spill prevention, and interior remodeling.                                                                                                                                                                                                                                                                                                                                                                                                       | 19901 Cedar Falls Rd SE, North Bend, WA 98045 | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6326       | Gorge Powerhouse - Fire Protection Improvements        | This project designs and installs a water spray generator fire suppression system for the Gorge Powerhouse Generator 24. The scope of the project includes piping, valving, nozzles for a water delivery system, and a new control system for detection, alarming, and system initiation.                                                                                                                                                                                                                                                                                                                                                                      | Milepost 121 State Highway 20                 | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6343       | Boundary Dam - Instrumentation Upgrade and Integration | This project funds a purchase and installation contract with an electrical contractor or supplier to upgrade or replace Unit 51-56 unit control boards, to enhance and permit a full interface with a new network-based control system. Full interface is required for long-term goal of complete plant automation.                                                                                                                                                                                                                                                                                                                                            | 10382 Boundary Rd, Metaline, WA 99153         | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6351       | Boundary Powerhouse - Unit 51 Generator Rebuild        | This project provides the rewinding and refurbishing of the Unit 51 generator to extend its useful life, which is part of a programmatic series of projects to maintain the Utility's aging generators. It also replaces the carbon dioxide fire-suppression system with a water sprinkler system to enhance worker safety. If technology is sufficiently advanced, it may also include a rotor-mounted scanner or other diagnostic equipment.                                                                                                                                                                                                                 | 10382 Boundary Rd, Metaline, WA 99153         | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6353       | Boundary Powerhouse - Unit 54 Generator Rebuild        | This project provides rewinding and refurbishing of the Boundary Powerhouse Unit 54 generator, which is part of a programmatic series of projects to maintain and extend the useful life of the Utility's aging generators. This project also provides replacement of the carbon dioxide fire-suppression system with a water sprinkler system to improve worker safety. If technology is sufficiently advanced, it may also include a rotor-mounted scanner or other diagnostic equipment.                                                                                                                                                                    | 10382 Boundary Rd, Metaline, WA 99153         | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6354       | Boundary Powerhouse - Unit 56 Generator Rebuild        | This project funds the rewinding and refurbishing of the Unit 56 generator, which is part of a programmatic series of projects to maintain and extend the useful life of the Utility's aging generators. This project also replaces the carbon dioxide fire-suppression system with a water sprinkler system, to improve worker safety, and may also include a rotor-mounted scanner or other diagnostic equipment as part of the rebuild.                                                                                                                                                                                                                     | 10382 Boundary Rd, Metaline, WA 99153         | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6358       | Cedar Falls Powerhouse - Penstock Stabilization        | This project installs a seismic upgrade of penstock bridges, repairs sagging or broken penstock support saddles, and refurbishes the exterior surfaces to extend the life of two 78-inch diameter steel penstocks. It also reduces risks of damage from earthquakes and restores the exterior coating on the pipes in the areas where the penstocks are buried. Any penstock failure will likely damage the environment and Seattle's water supply, and could jeopardize the City's ability to fulfill its obligation to regulate fish flows in the Cedar River.                                                                                               | 19901 Cedar Falls Rd SE, North Bend, WA 98045 | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
| 1443445182  | 6373       | Ross Dam - AC/DC Distribution System Upgrade           | This project upgrades aging AC electrical distribution system at Ross Dam with a new electrical distribution system. It installs conduit, ducting, distribution panels and wire. It improves the 4 kV system, improves lighting, and provides improvements on top of the dam including a center substation room, emergency generator, valve houses, and a 130-volt battery bank. New conduit and conductors improve reliability of spillgate operations and other dam operations requiring electric power. New electrical equipment, new lighting, and the addition of emergency lighting allow staff greater operational flexibility, safety, and efficiency. | Milepost 128 State Highway 20                 | 1             | Rehabilitation or Restoration | http://www.seattle.gov/financedepartment/1520adoptedcip/default.htm |         |          |           | 
```