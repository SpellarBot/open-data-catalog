# San Francisco Development Pipeline 2012 Quarter 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pipeline-q2-2012-65ac2) |
| Metadata | [Link](https://data.sfgov.org/api/views/ugxk-ztb8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ugxk-ztb8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ugxk-ztb8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ugxk-ztb8 |
| Name | San Francisco Development Pipeline 2012 Quarter 2 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, growth, housing, commercial |
| Created | 2012-09-24T21:21:05Z |
| Publication Date | 2012-09-24T22:24:24Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | objectid                     | ObjectID                     | text      | number      |
| Yes      | series tag     | block_lot                    | Block Lot                    | text      | text        |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text      | text        |
| Yes      | series tag     | best_stat                    | Best Stat                    | text      | text        |
| No       |                | best_date                    | Best Date                    | text      | text        |
| Yes      | numeric metric | units                        | Units                        | number    | number      |
| Yes      | series tag     | planning_project_description | Planning Project Description | text      | text        |
| Yes      | series tag     | dbi_project_description      | DBI Project Description      | text      | text        |
| Yes      | series tag     | zoning_generalized           | Zoning Generalized           | text      | text        |
| Yes      | series tag     | zoning_simplified            | Zoning Simplified            | text      | text        |
| Yes      | numeric metric | traffic_analysis_zone        | Traffic Analysis Zone        | number    | number      |
| Yes      | numeric metric | total_gsf_commercial         | Total GSF (Commercial)       | number    | number      |
| Yes      | numeric metric | office                       | Office                       | number    | number      |
| Yes      | numeric metric | cult_inst_educ               | Cult, Inst, Educ             | number    | number      |
| Yes      | numeric metric | medical                      | Medical                      | number    | number      |
| Yes      | numeric metric | prod_dist_rep                | Prod, Dist, Rep              | number    | number      |
| Yes      | numeric metric | ret_ent                      | Ret, Ent                     | number    | number      |
| Yes      | numeric metric | visitor                      | Visitor                      | number    | number      |
| Yes      | series tag     | planning_id                  | Planning ID                  | text      | text        |
| Yes      | series tag     | dbi_permit_id                | DBI Permit ID                | text      | text        |
| Yes      | series tag     | planning_filed               | Planning Filed               | text      | text        |
| Yes      | series tag     | dbi_filed                    | DBI Filed                    | text      | text        |
| Yes      | series tag     | firstfiled                   | FirstFiled                   | text      | text        |
| Yes      | series tag     | landuse                      | LANDUSE                      | text      | text        |
| Yes      | series tag     | entitlementstatus            | EntitlementStatus            | text      | number      |
| Yes      | series tag     | sort                         | sort                         | text      | text        |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | Net Office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number    | number      |
| Yes      | series tag     | block                        | BLOCK                        | text      | text        |
| Yes      | series tag     | lot                          | LOT                          | text      | text        |
| Yes      | series tag     | zoning                       | ZONING                       | text      | text        |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text      | text        |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text      | text        |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text      | text        |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text      | text        |
| Yes      | series tag     | fullname                     | FULLNAME                     | text      | text        |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text      | text        |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = best_date
```

## Data Commands

```ls
series e:ugxk-ztb8 d:2012-01-01T00:00:00.000Z t:sort="Planning Filed" t:block_lot=6593022 t:entitlementstatus=0 t:block=6593 t:heightlimit=40-X t:planning_filed=28-Jun-12 t:planning_project_description="Variance request to the rear yard requirement and for off-street parking." t:zoning_generalized="Mixed Use" t:planning_id=2012.0824 t:sponsor_name="Gang Wu Cheung" t:contactphone=415-637-2234 t:lot=022 t:zoning_simplified=NC-1 t:landuse=Mixres t:objectid=4461 t:firstfiled=28-Jun-12 t:best_stat="PL Filed" t:contactadd="1109 Tennessee Street" t:zoning=NC-1 t:fullname="Gang Wu Cheung 415-637-2234" t:contactcity="San Francisco, CA 94107" m:net_added_sf=716 m:ret_ent=1671 m:net_ret_ent=716 m:total_gsf_commercial=1671 m:traffic_analysis_zone=470 m:net_added_units=1 m:units=2

series e:ugxk-ztb8 d:2012-01-01T00:00:00.000Z t:sort="Planning Filed" t:block_lot=4172006 t:entitlementstatus=0 t:block=4172 t:sponsor_firm="Lundberg Design" t:heightlimit=45-X t:planning_filed=28-Jun-12 t:planning_project_description="Variance request to section 134" t:zoning_generalized="Mixed Use" t:planning_id=2012.0820 t:sponsor_name="Lev Bereznycky" t:contactphone=415-601-1578 t:lot=006 t:zoning_simplified=NCT-2 t:landuse=Resident t:objectid=4458 t:firstfiled=28-Jun-12 t:best_stat="PL Filed" t:contactadd="158 Randall street" t:zoning=NCT-2 t:fullname="Lev Bereznycky 415-601-1578" t:contactcity="San Francisco, CA  94131" m:net_prod_dist_rep=-2051 m:prod_dist_rep=0 m:net_added_sf=-2051 m:total_gsf_commercial=0 m:traffic_analysis_zone=741 m:net_added_units=1 m:units=1

series e:ugxk-ztb8 d:2012-01-01T00:00:00.000Z t:sort="Planning Filed" t:block_lot=0818002 t:entitlementstatus=0 t:block=0818 t:sponsor_firm="Selander Architects" t:heightlimit=50-X t:planning_filed=27-Jun-12 t:planning_project_description="Convert existing garage spaces at ground floor to residential units." t:zoning_generalized="Neighborhood Commercial" t:planning_id=2012.0809 t:sponsor_name="Ernie Selander" t:contactphone=415-385-4339 t:lot=002 t:zoning_simplified="HAYES NCT" t:landuse=Resident t:objectid=4483 t:firstfiled=27-Jun-12 t:best_stat="PL Filed" t:contactadd="2095 Jerrold, Suite 319" t:zoning="HAYES NCT" t:fullname="Ernie Selander 415-385-4339" t:contactcity="San Francisco, CA 94124" m:net_added_sf=0 m:total_gsf_commercial=0 m:traffic_analysis_zone=535 m:net_added_units=4 m:units=19
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:traffic_analysis_zone p:integer l:"Traffic Analysis Zone" t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"Total GSF (Commercial)" t:dataTypeName=number

metric m:office p:integer l:Office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"Cult, Inst, Educ" t:dataTypeName=number

metric m:medical p:integer l:Medical t:dataTypeName=number

metric m:prod_dist_rep p:double l:"Prod, Dist, Rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"Ret, Ent" t:dataTypeName=number

metric m:visitor p:integer l:Visitor t:dataTypeName=number

metric m:net_added_units p:integer l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical p:integer l:"Net Medical" t:dataTypeName=number

metric m:net_office p:integer l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"Net Visitor" t:dataTypeName=number

entity e:ugxk-ztb8 l:"San Francisco Development Pipeline 2012 Quarter 2" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/ugxk-ztb8

property e:ugxk-ztb8 t:meta.view v:id=ugxk-ztb8 v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2012 Quarter 2" v:attribution="San Francisco Planning Department"

property e:ugxk-ztb8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ugxk-ztb8 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:ugxk-ztb8 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| objectid | block_lot | planning_neighborhood | best_stat   | best_date | units | planning_project_description                                                                      | dbi_project_description                                                                              | zoning_generalized      | zoning_simplified | traffic_analysis_zone | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit_id | planning_filed | dbi_filed | firstfiled | landuse  | entitlementstatus | sort           | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | block | lot | zoning    | heightlimit | sponsor_firm                  | sponsor_name    | contactphone | fullname                     | contactcity             | contactadd              | 
| ======== | ========= | ===================== | =========== | ========= | ===== | ================================================================================================= | ==================================================================================================== | ======================= | ================= | ===================== | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============= | ============== | ========= | ========== | ======== | ================= | ============== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ===== | === | ========= | =========== | ============================= | =============== | ============ | ============================ | ======================= | ======================= | 
| 4461     | 6593022   |                       | PL Filed    | 28-Jun-12 | 2     | Variance request to the rear yard requirement and for off-street parking.                         |                                                                                                      | Mixed Use               | NC-1              | 470                   | 1671                 |        |                |         |               | 1671    |         | 2012.0824   |               | 28-Jun-12      |           | 28-Jun-12  | Mixres   | 0                 | Planning Filed | 1               | 716          |                    |             |            |                   | 716         |             | 6593  | 022 | NC-1      | 40-X        |                               | Gang Wu Cheung  | 415-637-2234 | Gang Wu Cheung 415-637-2234  | San Francisco, CA 94107 | 1109 Tennessee Street   | 
| 4458     | 4172006   |                       | PL Filed    | 28-Jun-12 | 1     | Variance request to section 134                                                                   |                                                                                                      | Mixed Use               | NCT-2             | 741                   | 0                    |        |                |         | 0             |         |         | 2012.0820   |               | 28-Jun-12      |           | 28-Jun-12  | Resident | 0                 | Planning Filed | 1               | -2051        |                    |             |            | -2051             |             |             | 4172  | 006 | NCT-2     | 45-X        | Lundberg Design               | Lev Bereznycky  | 415-601-1578 | Lev Bereznycky 415-601-1578  | San Francisco, CA 94131 | 158 Randall street      | 
| 4483     | 0818002   |                       | PL Filed    | 27-Jun-12 | 19    | Convert existing garage spaces at ground floor to residential units.                              |                                                                                                      | Neighborhood Commercial | HAYES NCT         | 535                   | 0                    |        |                |         |               |         |         | 2012.0809   |               | 27-Jun-12      |           | 27-Jun-12  | Resident | 0                 | Planning Filed | 4               | 0            |                    |             |            |                   |             |             | 0818  | 002 | HAYES NCT | 50-X        | Selander Architects           | Ernie Selander  | 415-385-4339 | Ernie Selander 415-385-4339  | San Francisco, CA 94124 | 2095 Jerrold, Suite 319 | 
| 4471     | 2700012   |                       | BP Filed    | 25-Jun-12 | 2     |                                                                                                   | HORIZONTAL & VERTICAL ADDITIONS. ADD 2ND UNIT. ADD ROOF DECK. RENOVATION AND STRUCTURAL UPGRADE.     | Residential             | RH-2              | 519                   | 0                    |        |                |         |               |         |         |             | 201206253387  |                | 25-Jun-12 | 25-Jun-12  | Resident | 0                 | BP Filed       | 1               | 0            |                    |             |            |                   |             |             | 2700  | 012 | RH-2      | 40-X        |                               |                 |              |                              |                         |                         | 
| 4473     | 3705039   |                       | BP Filed    | 20-Jun-12 | 116   |                                                                                                   | ADDITION OF 8 GUEST ROOMS, CREATING A LIGHT WELL & RENOVATION OF GUEST RESTROOMS FOR ADA UPGRADES &  | Commercial              | C-3-R             | 575                   | 0                    |        |                |         |               |         |         |             | 201206202986  |                | 20-Jun-12 | 20-Jun-12  | Resident | 0                 | BP Filed       | 8               | 0            |                    |             |            |                   |             |             | 3705  | 039 | C-3-R     | 90-X/160-S  |                               |                 |              |                              |                         |                         | 
| 4476     | 5518023   |                       | BP Filed    | 20-Jun-12 | 2     |                                                                                                   | CHANGE OF USE FROM COMMERCIAL TO RESIDENTIAL. INTERIOR REMODEL OF BATHROOM, ADDITION OF KITCHEN & ME | Residential             | RH-2              | 721                   | 0                    |        |                |         |               |         |         |             | 201206203050  |                | 20-Jun-12 | 20-Jun-12  | Resident | 0                 | BP Filed       | 1               | 0            |                    |             |            |                   |             |             | 5518  | 023 | RH-2      | 40-X        |                               |                 |              |                              |                         |                         | 
| 4451     | 2393040   |                       | BP Filed    | 20-Jun-12 | 16    |                                                                                                   | TO ERECT 5 STORIES, 16 UNITS, MIXED USE BUILDING.                                                    | Mixed Use               | NC-2              | 374                   | 0                    |        |                |         |               |         |         |             | 201206203038  |                | 20-Jun-12 | 20-Jun-12  | Resident | 0                 | BP Filed       | 16              | -1971        |                    |             |            | -1971             |             |             | 2393  | 040 | NC-2      | 50-X        |                               |                 |              |                              |                         |                         | 
| 4481     | 0634006   |                       | PL Filed    | 19-Jun-12 | 4     | Demo. of existing one story commercial bldg. and new construction of two separate two unit bldgs. |                                                                                                      | Neighborhood Commercial | FILLMORE          | 194                   | 0                    |        |                |         |               |         |         | 2012.0759   |               | 19-Jun-12      |           | 19-Jun-12  | Resident | 0                 | Planning Filed | 4               | 0            |                    |             |            |                   |             |             | 0634  | 006 | FILLMORE  | 40-X        | Sternberg Benjamin Architects | David Sternberg | 882-9783 x11 | David Sternberg 882-9783 x11 | San Francisco, CA 94103 | 1331 Harrison Street    | 
| 4467     | 1150007   |                       | BP Filed    | 15-Jun-12 | 3     |                                                                                                   | COMPLY WITH N.O.V.#201288233. Legalize 3rd. unit @ ground floor.                                     | Residential             | RH-3              | 297                   | 0                    |        |                |         |               |         |         |             | 201206152694  |                | 15-Jun-12 | 15-Jun-12  | Resident | 0                 | BP Filed       | 1               | 0            |                    |             |            |                   |             |             | 1150  | 007 | RH-3      | 40-X        |                               |                 |              |                              |                         |                         | 
| 3307     | 7106058   | Ingleside, Other      | PL Approved |           | 2     | Demo church and build 3 story building: two dwelling units over office space and garage           |                                                                                                      | Mixed Use               | NC-1              | 20                    | 1496                 | 1496   |                |         |               |         |         | 2012.0753   |               | 14-Jun-12      |           | 14-Jun-12  | Resident | -1                | PL Approved    | 2               | 1496         |                    |             | 1496       |                   |             |             | 7106  | 058 | NC-1      | 40-X        |                               | Mario Avives    | 650-745-6399 | Mario Avives 650-745-6399    | South SF, CA 94080      | 382 Alid Wy 203         | 
```