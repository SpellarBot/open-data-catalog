# Hawaii Capital Projects List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-capital-projects-list) |
| Metadata | [Link](https://data.hawaii.gov/api/views/37rm-jfpm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/37rm-jfpm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/37rm-jfpm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 37rm-jfpm |
| Name | Hawaii Capital Projects List |
| Created | 2015-04-14T19:49:55Z |
| Publication Date | 2016-02-04T16:48:26Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | project_id          | Project ID          | text      | text        |
| Yes      | series tag  | project_name        | Project Name        | text      | text        |
| Yes      | series tag  | project_description | Project Description | text      | text        |
| No       |             | address             | Address             | text      | text        |
| Yes      | series tag  | current_phase       | Current Phase       | text      | text        |
| Yes      | series tag  | current_phase_type  | Current Phase Type  | text      | text        |
| Yes      | series tag  | project_details_url | Project Details URL | text      | text        |
| No       |             | latitude            | Latitude            | number    | number      |
| No       |             | longitude           | Longitude           | number    | number      |
| Yes      | series tag  | regions             | Regions             | text      | text        |
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
series e:37rm-jfpm d:2016-02-04T08:47:27.000Z t:project_name="902 ALDER STREET, HONOLULU, OAHU" t:project_id=HFDC04 t:project_description="PLANS AND DESIGN FOR A MIXED-USE AFFORDABLE RENTAL HOUSING AND MULTI-USE JUVENILE SERVICES AND SHELTER CENTER AT 902 ALDER STREET, TMK (1) 2-3-012-019." m:row_number.37rm-jfpm=1

series e:37rm-jfpm d:2016-02-04T08:47:27.000Z t:project_name="AGRICULTURAL LAND, OAHU" t:project_id=P16004 t:project_description="PLANS, LAND ACQUISITION AND DESIGN FOR LAND ACQUISITION ON OAHU: TMK 7-1-02-32;7-1-02-06; 7-1-02-34; 9-5-03-07; 6-5-02-11" m:row_number.37rm-jfpm=2

series e:37rm-jfpm d:2016-02-04T08:47:27.000Z t:project_name="AIEA INTERMEDIATE SCHOOL, OAHU" t:project_id=P16034 t:project_description="DESIGN, CONSTRUCTION AND EQUIPMENT FOR AN APPLIED TECHNOLOGY CENTER, GROUND AND SITE IMPROVEMENTS, EQUIPMENT AND APPURTENANCES." m:row_number.37rm-jfpm=3
```

## Meta Commands

```ls
metric m:row_number.37rm-jfpm p:long l:"Row Number"

entity e:37rm-jfpm l:"Hawaii Capital Projects List" t:url=https://data.hawaii.gov/api/views/37rm-jfpm

property e:37rm-jfpm t:meta.view v:id=37rm-jfpm v:averageRating=0 v:name="Hawaii Capital Projects List"

property e:37rm-jfpm t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:37rm-jfpm t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | project_id | project_name                                                                 | project_description                                                                                                                                                                                                                                                                                                                                                                       | address | current_phase | current_phase_type | project_details_url | latitude           | longitude           | regions | 
| =========== | ========== | ============================================================================ | ========================================================================================================================================================================================================================================================================================================================================================================================= | ======= | ============= | ================== | =================== | ================== | =================== | ======= | 
| 1454575647  | HFDC04     | 902 ALDER STREET, HONOLULU, OAHU                                             | PLANS AND DESIGN FOR A MIXED-USE AFFORDABLE RENTAL HOUSING AND MULTI-USE JUVENILE SERVICES AND SHELTER CENTER AT 902 ALDER STREET, TMK (1) 2-3-012-019.                                                                                                                                                                                                                                   |         |               |                    |                     |                    |                     |         | 
| 1454575647  | P16004     | AGRICULTURAL LAND, OAHU                                                      | PLANS, LAND ACQUISITION AND DESIGN FOR LAND ACQUISITION ON OAHU: TMK 7-1-02-32;7-1-02-06; 7-1-02-34; 9-5-03-07; 6-5-02-11                                                                                                                                                                                                                                                                 |         |               |                    |                     |                    |                     |         | 
| 1454575647  | P16034     | AIEA INTERMEDIATE SCHOOL, OAHU                                               | DESIGN, CONSTRUCTION AND EQUIPMENT FOR AN APPLIED TECHNOLOGY CENTER, GROUND AND SITE IMPROVEMENTS, EQUIPMENT AND APPURTENANCES.                                                                                                                                                                                                                                                           |         |               |                    |                     | 21.384170000000001 | -157.92582999999999 |         | 
| 1454575647  | F05I       | AIRFIELD IMPROVEMENTS, STATEWIDE                                             | DESIGN AND CONSTRUCTION FOR AIRFIELD IMPROVEMENTS AT STATEWIDE AIRPORTS. THIS PROJECT IS DEEMED NECESSARY TO QUALIFY FOR FEDERAL AID FINANCING AND/OR REIMBURSEMENT.                                                                                                                                                                                                                      |         |               |                    |                     |                    |                     |         | 
| 1454575647  | F04P       | AIRPORT LAYOUT PLAN UPDATE, STATEWIDE                                        | PLANS TO UPDATE THE AIRPORT LAYOUT PLANS FOR ALL AIRPORTS, STATEWIDE.                                                                                                                                                                                                                                                                                                                     |         |               |                    |                     |                    |                     |         | 
| 1454575647  | F04J       | AIRPORT PLANNING STUDY, STATEWIDE                                            | PLANS FOR AIRPORT IMPROVEMENTS, ECONOMIC STUDIES, RESEARCH, NOISE MONITORING STUDIES, NOISE COMPATIBILITY STUDIES AND ADVANCE PLANNING OF FEDERAL AID AND NON-FEDERAL AID PROJECTS.                                                                                                                                                                                                       |         |               |                    |                     |                    |                     |         | 
| 1454575647  | F08F       | AIRPORTS DIVISION CAPITAL IMPROVEMENT PROGRAM PROJECT STAFF COSTS, STATEWIDE | PLANS, DESIGN AND CONSTRUCTION FOR COSTS RELATED TO WAGES AND FRINGES FOR PERMANENT PROJECT FUNDED STAFF POSITIONS FOR THE IMPLEMENTATION OF CAPITAL IMPROVEMENT PROGRAM PROJECTS FOR THE DEPARTMENT OF TRANSPORTATION'S AIRPORTS DIVISION. PROJECT MAY ALSO INCLUDE FUNDS FOR NON-PERMANENT CAPITAL IMPROVEMENT PROGRAM RELATED POSITIONS. (OTHER FUNDS FROM PASSENGER FACILITY CHARGES) |         |               |                    |                     |                    |                     |         | 
| 1454575647  | G54A       | ALA WAI CANAL DREDGING, OAHU                                                 | CONSTRUCTION FOR DREDGING AND RELATED IMPROVEMENTS.                                                                                                                                                                                                                                                                                                                                       |         |               |                    |                     |                    |                     |         | 
| 1454575647  | P16035     | ALA WAI ELEMENTARY SCHOOL, OAHU                                              | CONSTRUCTION AND EQUIPMENT FOR THE RENOVATION OF THE INNOVATION CENTER.                                                                                                                                                                                                                                                                                                                   |         |               |                    |                     |                    |                     |         | 
| 1454575647  | P16036     | ALA WAI ELEMENTARY SCHOOL; REROOF CAFETERIA BUILDING, OAHU                   | DESIGN AND CONSTRUCTION TO REROOF THE CAFETERIA BULIDING                                                                                                                                                                                                                                                                                                                                  |         |               |                    |                     |                    |                     |         | 
```