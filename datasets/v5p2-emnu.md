# San Francisco Development Pipeline 2012 Quarter 1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-e6bc8) |
| Metadata | [Link](https://data.sfgov.org/api/views/v5p2-emnu) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/v5p2-emnu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/v5p2-emnu/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | v5p2-emnu |
| Name | San Francisco Development Pipeline 2012 Quarter 1 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Created | 2012-04-12T21:27:43Z |
| Publication Date | 2012-04-13T06:29:52Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | block_lot                    | block lot                    | text      | text        |
| Yes      | series tag     | planning_neighborhood        | planning neighborhood        | text      | text        |
| Yes      | series tag     | project_status               | project status               | text      | text        |
| Yes      | time           | project_date                 | project date                 | date      | date        |
| Yes      | numeric metric | units                        | units                        | number    | number      |
| Yes      | series tag     | planning_project_description | planning project description | text      | text        |
| Yes      | series tag     | dbi_project_description      | dbi project description      | text      | text        |
| Yes      | series tag     | zoning_generalized           | zoning_generalized           | text      | text        |
| Yes      | series tag     | zoning_simplified            | zoning_simplified            | text      | text        |
| Yes      | numeric metric | taz                          | taz                          | number    | number      |
| Yes      | numeric metric | total_gsf_commercial         | total gsf (commercial)       | number    | number      |
| Yes      | numeric metric | office                       | office                       | number    | number      |
| Yes      | numeric metric | cult_inst_educ               | cult, inst, educ             | number    | number      |
| Yes      | numeric metric | medical                      | medical                      | number    | number      |
| Yes      | numeric metric | prod_dist_rep                | prod, dist, rep              | number    | number      |
| Yes      | numeric metric | ret_ent                      | ret, ent                     | number    | number      |
| Yes      | numeric metric | visitor                      | visitor                      | number    | number      |
| Yes      | numeric metric | dbi_permit                   | dbi permit                   | number    | number      |
| No       |                | planning_filed               | planning filed               | date      | date        |
| No       |                | dbi_filed                    | dbi filed                    | date      | date        |
| Yes      | series tag     | landuse                      | landuse                      | text      | text        |
| Yes      | series tag     | status_group                 | status group                 | text      | text        |
| Yes      | numeric metric | net_added_units              | net added units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | net added sf                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | net cult, inst, educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | net medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | net office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | net prod, dist, rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | net ret, ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | net visitor                  | number    | number      |
| Yes      | numeric metric | sitearea                     | sitearea                     | number    | number      |
| Yes      | series tag     | block                        | block                        | text      | text        |
| Yes      | series tag     | lot                          | lot                          | text      | text        |
| Yes      | series tag     | zoning                       | zoning                       | text      | text        |
| Yes      | series tag     | heightlimit                  | heightlimit                  | text      | text        |
| Yes      | numeric metric | supdist                      | supdist                      | number    | number      |
```

## Time Field

```ls
Value = project_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = planning_filed,dbi_filed
```

## Data Commands

```ls
series e:v5p2-emnu d:2009-11-03T08:00:00.000Z t:project_status="BP REINSTATED" t:zoning_generalized="Mixed Use" t:block_lot=4172053 t:lot=053 t:zoning_simplified=NCT-2 t:block=4172 t:status_group="BP Approved/Issued/Re-Instated" t:landuse=Resident t:heightlimit=40-X t:planning_neighborhood="Central Waterfront" t:zoning=NCT-2 t:dbi_project_description="ERECT A FOUR STORY EIGHT UNIT RESIDENTIAL BLDG WITH COML" m:office=0 m:prod_dist_rep=0 m:supdist=10 m:net_medical=0 m:net_office=0 m:units=8 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=521 m:medical=0 m:net_added_sf=0 m:dbi_permit=9902819 m:sitearea=6090 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=8 m:net_visitor=0

series e:v5p2-emnu d:2007-04-11T07:00:00.000Z t:project_status="BP ISSUED" t:block_lot=0492025 t:block=0492 t:status_group="BP Approved/Issued/Re-Instated" t:planning_neighborhood=Marina t:heightlimit=40-X t:zoning_generalized="Mixed Use" t:planning_project_description="The proposed project involves the demolition of an 8,630 gsf, two-story (over grade parking) 30-room motel and construction of a 49,001gsf, 4-story hotel containing 97 rooms." t:lot=025 t:zoning_simplified=NC-3 t:landuse=Visitor t:zoning=NC-3 t:dbi_project_description="ERECT A NEW 4 STORY 89 UNIT TOURIST HOTEL W/ GARAGE" m:office=0 m:prod_dist_rep=0 m:supdist=2 m:net_medical=0 m:net_office=0 m:units=0 m:visitor=40370 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=819 m:medical=0 m:net_added_sf=40370 m:dbi_permit=200606023107 m:sitearea=13612 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=40370 m:net_cult_inst_educ=0 m:net_added_units=0 m:net_visitor=40370

series e:v5p2-emnu d:2007-11-28T08:00:00.000Z t:project_status="BP ISSUED" t:block_lot=2676030 t:block=2676 t:status_group="BP Approved/Issued/Re-Instated" t:planning_neighborhood="Inner Sunset" t:heightlimit=40-X t:zoning_generalized=Residential t:planning_project_description="Construct a new single-family dwelling on a vacant parcel in an RH-1(D) (Residential, House, One-Family, Detached) District and a 40-X Height and Bulk District." t:lot=030 t:zoning_simplified=RH-1(D) t:landuse=Resident t:zoning=RH-1(D) t:dbi_project_description="ERECT 3 STORIES, 1 DWELLING UNIT WITH 1 BASEMENT BLDG." m:office=0 m:prod_dist_rep=0 m:supdist=7 m:net_medical=0 m:net_office=0 m:units=1 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=545 m:medical=0 m:net_added_sf=0 m:dbi_permit=200212042761 m:sitearea=6418 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=1 m:net_visitor=0
```

## Meta Commands

```ls
metric m:units p:integer l:units t:dataTypeName=number

metric m:taz p:integer l:taz t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"total gsf (commercial)" t:dataTypeName=number

metric m:office p:integer l:office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"cult, inst, educ" t:dataTypeName=number

metric m:medical p:integer l:medical t:dataTypeName=number

metric m:prod_dist_rep p:integer l:"prod, dist, rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"ret, ent" t:dataTypeName=number

metric m:visitor p:integer l:visitor t:dataTypeName=number

metric m:dbi_permit p:long l:"dbi permit" t:dataTypeName=number

metric m:net_added_units p:integer l:"net added units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"net added sf" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"net cult, inst, educ" t:dataTypeName=number

metric m:net_medical p:integer l:"net medical" t:dataTypeName=number

metric m:net_office p:integer l:"net office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"net prod, dist, rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"net ret, ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"net visitor" t:dataTypeName=number

metric m:sitearea p:integer l:sitearea t:dataTypeName=number

metric m:supdist p:integer l:supdist t:dataTypeName=number

entity e:v5p2-emnu l:"San Francisco Development Pipeline 2012 Quarter 1" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/v5p2-emnu

property e:v5p2-emnu t:meta.view v:id=v5p2-emnu v:category="Housing and Buildings" v:attributionLink=http://sfplanning.org v:averageRating=0 v:name="San Francisco Development Pipeline 2012 Quarter 1" v:attribution="San Francisco Planning Department"

property e:v5p2-emnu t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:v5p2-emnu t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:v5p2-emnu t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | project_status | project_date | units | planning_project_description                                                                                                                                                                                                                                  | dbi_project_description                                                                            | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | dbi_permit   | planning_filed | dbi_filed  | landuse  | status_group                   | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | sitearea | block | lot | zoning         | heightlimit | supdist | 
| ========= | ===================== | ============== | ============ | ===== | ============================================================================================================================================================================================================================================================= | ================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | ============ | ============== | ========== | ======== | ============================== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ======== | ===== | === | ============== | =========== | ======= | 
| block lot | planning neighborhood | best stat      |              |       | planning project description                                                                                                                                                                                                                                  | dbi project description                                                                            | zoning_generalized | zoning_simplified |     |                      |        |                |         |               |         |         |              |                |            | landuse  | status group                   |                 |              |                    |             |            |                   |             |             |          | block | lot | zoning         | heightlimit |         | 
| 4172053   | Central Waterfront    | BP REINSTATED  | 1257235200   | 8     |                                                                                                                                                                                                                                                               | ERECT A FOUR STORY EIGHT UNIT RESIDENTIAL BLDG WITH COML                                           | Mixed Use          | NCT-2             | 521 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 9902819      | 988268400      | 918720000  | Resident | BP Approved/Issued/Re-Instated | 8               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 6090     | 4172  | 053 | NCT-2          | 40-X        | 10      | 
| 0492025   | Marina                | BP ISSUED      | 1176274800   | 0     | The proposed project involves the demolition of an 8,630 gsf, two-story (over grade parking) 30-room motel and construction of a 49,001gsf, 4-story hotel containing 97 rooms.                                                                                | ERECT A NEW 4 STORY 89 UNIT TOURIST HOTEL W/ GARAGE                                                | Mixed Use          | NC-3              | 819 | 40370                | 0      | 0              | 0       | 0             | 0       | 40370   | 200606023107 | 1023778800     | 1149231600 | Visitor  | BP Approved/Issued/Re-Instated | 0               | 40370        | 0                  | 0           | 0          | 0                 | 0           | 40370       | 13612    | 0492  | 025 | NC-3           | 40-X        | 2       | 
| 2676030   | Inner Sunset          | BP ISSUED      | 1196236800   | 1     | Construct a new single-family dwelling on a vacant parcel in an RH-1(D) (Residential, House, One-Family, Detached) District and a 40-X Height and Bulk District.                                                                                              | ERECT 3 STORIES, 1 DWELLING UNIT WITH 1 BASEMENT BLDG.                                             | Residential        | RH-1(D)           | 545 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200212042761 | 1054018800     | 1038988800 | Resident | BP Approved/Issued/Re-Instated | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 6418     | 2676  | 030 | RH-1(D)        | 40-X        | 7       | 
| 3615026   | Mission               | BP ISSUED      | 1251270000   | 0     | The project is to demolish the existing single-story retail building and construct a new building that would be three-stories tall and would contain retail on the ground floor and offices on the second and third floors. 6/15/05 - Environmental Exemption | ERECT A 3 STORY COMMERCIAL SHOP & OFFICE                                                           | Mixed Use          | Mission Street    | 176 | 4999                 | 4999   | 0              | 0       | 0             | 0       | 0       | 200302218059 | 1060239600     | 1045814400 | MIPS     | BP Approved/Issued/Re-Instated | 0               | 4999         | 0                  | 0           | 4999       | 0                 | 0           | 0           | 3675     | 3615  | 026 | Mission St NCT | 65-B        | 9       | 
| 6942039   | Ingleside, Other      | BP ISSUED      | 1223535600   | 2     | Demolish a one-family dwelling and construct a new two-family dwelling in an RH-2 (Residential, House, Two-Family) District and a 40-X Height and Bulk District.                                                                                              | ERECT 3 STORY TWO UNIT DWELLING.                                                                   | Residential        | RH-2              | 53  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200701051057 | 1048579200     | 1167984000 | Resident | BP Approved/Issued/Re-Instated | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 2815     | 6942  | 039 | RH-2           | 40-X        | 11      | 
| 5618020   | Bernal Heights        | BP REINSTATED  | 1235116800   | 1     | the project proposes the new construction of a single family residence without the required two parking spaces.                                                                                                                                               | ERECT A TWO STORY SINGLE FAMILY DWELING                                                            | Residential        | RH-1              | 116 | 0                    |        |                |         |               |         |         | 200310066599 | 1192690800     | 1065423600 | Resident | BP Approved/Issued/Re-Instated | 1               | 0            |                    |             |            |                   |             |             | 1750     | 5618  | 020 | RH-1           | 40-X        | 9       | 
| 7016023   | Ingleside, Other      | BP ISSUED      | 1317193200   | 1     |                                                                                                                                                                                                                                                               | ERECT A THREE STORY SINGLE FAMILY DWELLING                                                         | Residential        | RH-1              | 35  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200311240936 | 1094540400     | 1069660800 | Resident | BP Approved/Issued/Re-Instated | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 2500     | 7016  | 023 | RH-1           | 40-X        | 11      | 
| 6176011   | South Central, Other  | BP ISSUED      | 1275634800   | 1     | Erect 3-story Type V, Single-Family Structure in a RH-1/40-X zoning district.                                                                                                                                                                                 | ERECT 3-STORY TYPE-V SINGLE FAMILY STRUCTURE                                                       | Residential        | RH-1              | 30  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200401063464 | 1232092800     | 1073376000 | Resident | BP Approved/Issued/Re-Instated | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 4159     | 6176  | 011 | RH-1           | 40-X        | 10      | 
| 4645018   | India Basin           | BP APPROVED    | 1225699200   | 4     | Construct a vertical addition to accommodate three DUs, convert ground floor to a three-car garage, and change ground floor use from business to retail in an NC-2 (Small-Scale Neighborhood Commercial) District and a 40-X Height and Bulk District.        | ADD 2 NEW FLOORS TO (E) STRUCTURE.RECONFIGURE (E)SPACE W/NEW ADDED SPACE TO CREATE 1 COMM'L SPACE, | Mixed Use          | NC-2              | 446 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200402267273 | 1102320000     | 1077782400 | Resident | BP Approved/Issued/Re-Instated | 4               | -2560        | 0                  | 0           | 0          | -2560             | 0           | 0           | 2567     | 4645  | 018 | NC-2           | 40-X        | 10      | 
```