# OCIO IT Project Oversight Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ocio-it-project-oversight-summary) |
| Metadata | [Link](https://data.wa.gov/api/views/hdh3-xc9r) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hdh3-xc9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hdh3-xc9r/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hdh3-xc9r |
| Name | OCIO IT Project Oversight Summary |
| Attribution | Office of the CIO |
| Category | Procurements and Contracts |
| Tags | it projects ocio |
| Created | 2015-03-29T06:30:16Z |
| Publication Date | 2015-05-01T23:06:57Z |

## Description

Project oversight summary

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                | Data Type | Render Type |
| ======== | ============== | ================= | =================== | ========= | =========== |
| No       | time           | :updated_at       | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | agency            | Agency              | text      | text        |
| Yes      | series tag     | project           | Project             | text      | text        |
| Yes      | series tag     | description       | Description         | text      | text        |
| Yes      | series tag     | status            | Status              | text      | text        |
| Yes      | numeric metric | budget            | Budget              | money     | money       |
| Yes      | numeric metric | riskseveritylevel | Risk Severity Level | number    | number      |
| Yes      | series tag     | scopestatus       | Scope Status        | text      | text        |
| Yes      | series tag     | schedulestatus    | Schedule Status     | text      | text        |
| Yes      | series tag     | budgetstatus      | Budget Status       | text      | text        |
| Yes      | series tag     | ocioassessment    | OCIO Assessment     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hdh3-xc9r d:2015-03-28T23:30:26.000Z t:project="State Data Center Move (Phase 1)" t:ocioassessment=Green t:schedulestatus=Green t:status=Complete t:description="This investment will refresh, install, and move equipment operating in the Office Building 2 (OB2) data center into the State Data Center (SDC)." t:agency="Consolidated Technology Services" t:budgetstatus=Green t:scopestatus=Green m:budget=5069541 m:riskseveritylevel=2

series e:hdh3-xc9r d:2015-03-28T23:30:26.000Z t:project="FamLink Performance Base Contracting & Family Assessment Response" t:ocioassessment=Green t:schedulestatus=Yellow t:status=Complete t:description="Critical changes will be implemented in the FamLink system to support the Performance Based Contracting (PBC) and Family Assessment Resonse (FAR) per HB2264 and SB655." t:agency="Social and Health Services, Department of" t:budgetstatus=Green t:scopestatus=Green m:budget=6728040 m:riskseveritylevel=2

series e:hdh3-xc9r d:2015-03-28T23:30:26.000Z t:project="Unemployment Tax and Benefit (UTAB) System" t:ocioassessment=Green t:status=Active t:description="The Employment Security Department proposes Phase 2 of modernizing the  unemployment insurance system with the Unemployment Tax and Benefit (UTAB) project." t:agency="Employment Security, Department of" m:budget=43662000 m:riskseveritylevel=3
```

## Meta Commands

```ls
metric m:budget p:integer l:Budget t:dataTypeName=money

metric m:riskseveritylevel p:integer l:"Risk Severity Level" t:dataTypeName=number

entity e:hdh3-xc9r l:"OCIO IT Project Oversight Summary" t:attribution="Office of the CIO" t:url=https://data.wa.gov/api/views/hdh3-xc9r

property e:hdh3-xc9r t:meta.view v:id=hdh3-xc9r v:category="Procurements and Contracts" v:attributionLink=http://www.ocio.wa.gov/its-transparent-project-dashboard v:averageRating=0 v:name="OCIO IT Project Oversight Summary" v:attribution="Office of the CIO"

property e:hdh3-xc9r t:meta.view.license v:name="Public Domain"

property e:hdh3-xc9r t:meta.view.owner v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:displayName=max.pham

property e:hdh3-xc9r t:meta.view.tableauthor v:id=nahs-vrbk v:profileImageUrlMedium=/api/users/nahs-vrbk/profile_images/THUMB v:profileImageUrlLarge=/api/users/nahs-vrbk/profile_images/LARGE v:screenName=max.pham v:profileImageUrlSmall=/api/users/nahs-vrbk/profile_images/TINY v:roleName=editor v:displayName=max.pham
```

## Top Records

```ls
| :updated_at | agency                                    | project                                                           | description                                                                                                                                                                                        | status   | budget      | riskseveritylevel | scopestatus | schedulestatus | budgetstatus | ocioassessment | 
| =========== | ========================================= | ================================================================= | ================================================================================================================================================================================================== | ======== | =========== | ================= | =========== | ============== | ============ | ============== | 
| 1427585426  | Consolidated Technology Services          | State Data Center Move (Phase 1)                                  | This investment will refresh, install, and move equipment operating in the Office Building 2 (OB2) data center into the State Data Center (SDC).                                                   | Complete | 5069541.00  | 2                 | Green       | Green          | Green        | Green          | 
| 1427585426  | Social and Health Services, Department of | FamLink Performance Base Contracting & Family Assessment Response | Critical changes will be implemented in the FamLink system to support the Performance Based Contracting (PBC) and Family Assessment Resonse (FAR) per HB2264 and SB655.                            | Complete | 6728040.00  | 2                 | Green       | Yellow         | Green        | Green          | 
| 1427585426  | Employment Security, Department of        | Unemployment Tax and Benefit (UTAB) System                        | The Employment Security Department proposes Phase 2 of modernizing the unemployment insurance system with the Unemployment Tax and Benefit (UTAB) project.                                         | Active   | 43662000.00 | 3                 |             |                |              | Green          | 
| 1427585426  | Transportation, Department of             | Ferries Vehicle Reservation System (VRS)                          | Design a ferry vehicle reservation system to manage demand, spread peak vehicle traffic, improve asset utilization, reduce wait times, and minimize costly terminal and vessel expansion projects. | Active   | 8640000.00  | 3                 | Green       | Green          | Green        | Green          | 
| 1427585426  | Public Instruction, Superintendent of     | Meals Application                                                 |                                                                                                                                                                                                    |          |             | 2                 |             |                |              | Green          | 
| 1427585426  | Licensing, Department of                  | Modernization                                                     | Entire Agency Technology Modernization - Placeholder for project in the very beginning stages.                                                                                                     | Active   | 70400000.00 | 3                 | Green       | Green          | Green        | Green          | 
| 1427585426  | Licensing, Department of                  | Business and Tech. Modernization                                  | The Business and Technology Modernization (BTM) Project is a multi-biennia effort to modernize the agency?s business processes and information technology systems for Vehicle and Drivers.         | Active   | 70400000.00 | 3                 | Green       | Green          | Green        | Green          | 
| 1427585426  | Corrections, Department of                | OMNI off the Mainframe                                            | This project will move the Offender Management Network Information (OMNI) system from the mainframe at Consolidate Technology Services (CTS) onto virtual servers.                                 | Active   | 2300000.00  | 2                 | Green       | Green          | Green        | Green          | 
| 1427585426  | Employment Security, Department of        | Integrated WorkSource Technology                                  | The Employment Security Department (ESD) seeks a job management and worker tracking and information system to support WorkSource Washington.                                                       |          | 10.00       | 2                 |             |                |              | Green          | 
| 1427585426  | Licensing, Department of                  | Prorate & Fuel Tax System Replacement                             | Replaces the current Fuel Tax collection service. The contract for this will expire and needs to be upgraded                                                                                       | Active   | 10158000.00 | 3                 | Green       | Green          | Green        | Green          | 
```