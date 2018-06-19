# FY 12 & FY 13 CIP Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-12-fy-13-cip-budget-0ac9c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/dkm3-39id) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/dkm3-39id/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/dkm3-39id/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | dkm3-39id |
| Name | FY 12 & FY 13 CIP Budget |
| Attribution | Department of Budget and Finance |
| Category | Government-Wide Support |
| Tags | budget, fy12, fy13 |
| Created | 2012-10-09T23:32:57Z |
| Publication Date | 2012-10-09T23:40:09Z |

## Description

STATE OF HAWAII													
FY 12 & FY 13 CAPITAL IMPROVEMENT PROJECTS - ACT 164, SLH 2011, AS AMENDED BY ACT 106, SLH 2012													
Note:  Senate and Rep District information for some projects was not available at time of download.  Also, Item Numbers do not include program area alpha designations (e.g., AGR project P12000 is A-1.02).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | dept                | DEPT                | text      | text        |
| Yes      | series tag     | pgm_no              | PGM-NO              | text      | number      |
| Yes      | series tag     | cap_proj            | CAP PROJ            | text      | text        |
| Yes      | series tag     | senate_district     | SENATE DISTRICT     | text      | number      |
| Yes      | numeric metric | island              | ISLAND              | number    | number      |
| Yes      | series tag     | rep_district        | REP DISTRICT        | text      | number      |
| Yes      | series tag     | project_scope       | PROJECT SCOPE       | text      | text        |
| Yes      | series tag     | item_number         | ITEM NUMBER         | text      | number      |
| Yes      | series tag     | expending_agency    | EXPENDING AGENCY    | text      | text        |
| Yes      | series tag     | project_title       | PROJECT TITLE       | text      | text        |
| Yes      | series tag     | project_description | PROJECT DESCRIPTION | text      | text        |
| Yes      | series tag     | mof                 | MOF                 | text      | text        |
| Yes      | numeric metric | fy_2011_2012        | FY 2011-2012($$$)   | number    | number      |
| Yes      | numeric metric | fy_2012_2013        | FY 2012-2013($$$)   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dkm3-39id d:2012-10-09T16:32:59.000Z t:mof=C t:item_number=1.02 t:project_title="AGRICULTURAL INSPECTION FACILITIES, STATEWIDE" t:dept=AGR t:cap_proj=P12000 t:project_scope=N t:pgm_no=122 t:project_description="PLANS AND DESIGN FOR THE CONSTRUCTION OF AGRICULTURAL INSPECTION FACILITIES AND RELATED INFRASTRUCTURE, STATEWIDE." t:expending_agency=AGR m:fy_2012_2013=2000 m:fy_2011_2012=0 m:island=0

series e:dkm3-39id d:2012-10-09T16:32:59.000Z t:mof=N t:item_number=9 t:project_title="STATE AGRICULTURAL WATER AND USE DEVELOPMENT PLAN, STATEWIDE" t:rep_district=0 t:senate_district=0 t:dept=AGR t:cap_proj=200401 t:project_scope=A t:pgm_no=141 t:project_description="PLANS FOR STATE AGRICULTURAL WATER USE DEVELOPMENT PLAN, STATEWIDE. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT." t:expending_agency=AGR m:fy_2012_2013=4350 m:fy_2011_2012=1350 m:island=0

series e:dkm3-39id d:2012-10-09T16:32:59.000Z t:mof=C t:item_number=9 t:project_title="STATE AGRICULTURAL WATER AND USE DEVELOPMENT PLAN, STATEWIDE" t:rep_district=0 t:senate_district=0 t:dept=AGR t:cap_proj=200401 t:project_scope=A t:pgm_no=141 t:project_description="PLANS FOR STATE AGRICULTURAL WATER USE DEVELOPMENT PLAN, STATEWIDE. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT." t:expending_agency=AGR m:fy_2012_2013=1000 m:fy_2011_2012=1000 m:island=0
```

## Meta Commands

```ls
metric m:island p:integer l:ISLAND t:dataTypeName=number

metric m:fy_2011_2012 p:integer l:"FY 2011-2012($$$)" t:dataTypeName=number

metric m:fy_2012_2013 p:integer l:"FY 2012-2013($$$)" t:dataTypeName=number

entity e:dkm3-39id l:"FY 12 & FY 13 CIP Budget" t:attribution="Department of Budget and Finance" t:url=https://data.hawaii.gov/api/views/dkm3-39id

property e:dkm3-39id t:meta.view v:id=dkm3-39id v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/budget v:averageRating=0 v:name="FY 12 & FY 13 CIP Budget" v:attribution="Department of Budget and Finance"

property e:dkm3-39id t:meta.view.license v:name="Creative Commons Attribution | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nd/3.0/legalcode v:logoUrl=images/licenses/cc30bynd.png

property e:dkm3-39id t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:dkm3-39id t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | dept | pgm_no | cap_proj | senate_district | island | rep_district | project_scope | item_number | expending_agency | project_title                                                         | project_description                                                                                                                                                                                                         | mof | fy_2011_2012 | fy_2012_2013 | 
| =========== | ==== | ====== | ======== | =============== | ====== | ============ | ============= | =========== | ================ | ===================================================================== | =========================================================================================================================================================================================================================== | === | ============ | ============ | 
| 1349800379  | AGR  | 122    | P12000   |                 | 0      |              | N             | 1.02        | AGR              | AGRICULTURAL INSPECTION FACILITIES, STATEWIDE                         | PLANS AND DESIGN FOR THE CONSTRUCTION OF AGRICULTURAL INSPECTION FACILITIES AND RELATED INFRASTRUCTURE, STATEWIDE.                                                                                                          | C   | 0            | 2000         | 
| 1349800379  | AGR  | 141    | 200401   | 0               | 0      | 0            | A             | 9           | AGR              | STATE AGRICULTURAL WATER AND USE DEVELOPMENT PLAN, STATEWIDE          | PLANS FOR STATE AGRICULTURAL WATER USE DEVELOPMENT PLAN, STATEWIDE. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT.                                                             | N   | 1350         | 4350         | 
| 1349800379  | AGR  | 141    | 200401   | 0               | 0      | 0            | A             | 9           | AGR              | STATE AGRICULTURAL WATER AND USE DEVELOPMENT PLAN, STATEWIDE          | PLANS FOR STATE AGRICULTURAL WATER USE DEVELOPMENT PLAN, STATEWIDE. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT.                                                             | C   | 1000         | 1000         | 
| 1349800379  | AGR  | 141    | 200402   | 6               | 5      | 13           | A             | 7           | AGR              | MOLOKAI IRRIGATION SYSTEM IMPROVEMENTS, MOLOKAI                       | PLANS, DESIGN, AND CONSTRUCTION FOR IMPROVEMENTS TO THE MOLOKAI IRRIGATION SYSTEM.                                                                                                                                          | C   | 1250         | 0            | 
| 1349800379  | AGR  | 141    | 200603   | 25              | 1      | 51           | R             | 4           | AGR              | WAIMANALO IRRIGATION SYSTEM IMPROVEMENTS, OAHU                        | DESIGN AND CONSTRUCTION FOR IMPROVEMENTS TO THE WAIMANALO IRRIGATION SYSTEM, OAHU.                                                                                                                                          | C   | 1850         | 1000         | 
| 1349800379  | AGR  | 141    | 201006   | 7               | 4      | 16           | N             | 6           | AGR              | KEKAHA DITCH IMPROVEMENTS, KAUAI                                      | PLANS, DESIGN, AND CONSTRUCTION FOR IMPROVEMENTS TO THE BLACK PIPE SIPHON, PALI WOODEN FLUME, AND OTHER STRUCTURES.                                                                                                         | C   | 300          | 1400         | 
| 1349800379  | AGR  | 141    | 201101   | 23              | 1      | 46           | I             | 8           | AGR              | KAHUKU AGRICULTURAL PARK SUBDIVISION MISCELLANEOUS IMPROVEMENTS, OAHU | CONSTRUCTION OF MISCELLANEOUS IMPROVEMENTS TO THE KAHUKU AGRICULTURAL PARK SUBDIVISION.                                                                                                                                     | C   | 110          | 0            | 
| 1349800379  | AGR  | 141    | 201104   | 19              | 1      | 40           | I             | 10          | AGR              | WAIAHOLE WATER SYSTEMS IMPROVEMENTS, OAHU                             | PLANS, DESIGN AND CONSTRUCTION FOR IMPROVEMENTS TO WAIAHOLE WATER SYSTEM, OAHU.                                                                                                                                             | C   | 500          | 2500         | 
| 1349800379  | AGR  | 141    | 21103    | 2               | 3      | 5            | A             | 11          | AGR              | KA'U IRRIGATION SYSTEM IMPROVEMENTS, HAWAII                           | PLANS, DESIGN AND CONSTRUCTION TO THE KA'U IRRIGATION SYSTEM, INCLUDING RENOVATION OF EXISTING WATER TUNNEL SYSTEMS IN THE KA'U AREA.                                                                                       | C   | 500          | 1500         | 
| 1349800379  | AGR  | 141    | 980002   | 1               | 3      | 1            | O             | 3           | AGR              | LOWER HAMAKUA DITCH WATERSHED PROJECT, HAWAII                         | LAND ACQUISITION, DESIGN, AND CONSTRUCTION FOR IMPROVEMENTS TO THE LOWER HAMAKUA DITCH SYSTEM, TOGETHER WITH APPURTENANT WORKS. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT. | N   | 3200         | 1500         | 
```