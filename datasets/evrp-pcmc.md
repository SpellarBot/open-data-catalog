# San Francisco Development Pipeline 2013 Quarter 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/development-pipeline-second-quarter-2013-34327) |
| Metadata | [Link](https://data.sfgov.org/api/views/evrp-pcmc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/evrp-pcmc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/evrp-pcmc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | evrp-pcmc |
| Name | San Francisco Development Pipeline 2013 Quarter 2 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, commercial, real estate |
| Created | 2013-08-28T22:42:22Z |
| Publication Date | 2013-08-28T22:47:20Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | block_lot                    | Block Lot                    | text          | text          |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text          | text          |
| Yes      | series tag     | best_stat                    | Best Stat                    | text          | text          |
| No       |                | best_date                    | Best Date                    | calendar_date | calendar_date |
| Yes      | series tag     | building_type_id             | building_type_id             | text          | number        |
| Yes      | numeric metric | units                        | Units                        | number        | number        |
| Yes      | series tag     | planning_project_description | Planning Project Description | text          | text          |
| Yes      | series tag     | dbi_project_description      | DBI Project Description      | text          | text          |
| Yes      | series tag     | zoning_generalized           | Zoning_Generalized           | text          | text          |
| Yes      | series tag     | zoning_simplified            | Zoning_Simplified            | text          | text          |
| Yes      | numeric metric | taz                          | TAZ                          | number        | number        |
| Yes      | numeric metric | total_gsf_commercial         | Total GSF (Commercial)       | number        | number        |
| Yes      | numeric metric | office                       | Office                       | number        | number        |
| Yes      | numeric metric | cult_inst_educ               | Cult, Inst, Educ             | number        | number        |
| Yes      | numeric metric | medical                      | Medical                      | number        | number        |
| Yes      | numeric metric | prod_dist_rep                | Prod, Dist, Rep              | number        | number        |
| Yes      | numeric metric | ret_ent                      | Ret, Ent                     | number        | number        |
| Yes      | numeric metric | visitor                      | Visitor                      | number        | number        |
| Yes      | numeric metric | dbi_permit                   | DBI Permit                   | number        | number        |
| No       |                | planning_filed               | Planning Filed               | calendar_date | calendar_date |
| No       |                | dbi_filed                    | DBI Filed                    | calendar_date | calendar_date |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text          | text          |
| Yes      | series tag     | zoning                       | ZONING                       | text          | text          |
| Yes      | time           | firstfiled                   | FirstFiled                   | calendar_date | calendar_date |
| Yes      | series tag     | landuse                      | LANDUSE                      | text          | text          |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number        | number        |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number        | number        |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number        | number        |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number        | number        |
| Yes      | numeric metric | net_office                   | Net Office                   | number        | number        |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number        | number        |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number        | number        |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number        | number        |
| Yes      | series tag     | block                        | BLOCK                        | text          | number        |
| Yes      | series tag     | lot                          | LOT                          | text          | number        |
```

## Time Field

```ls
Value = firstfiled
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = planning_filed,dbi_filed,best_date
```

## Data Commands

```ls
series e:evrp-pcmc d:1999-02-11T00:00:00.000Z t:building_type_id=4 t:zoning_generalized="Mixed Use" t:block_lot=4172053 t:lot=53 t:zoning_simplified=NCT-2 t:block=4172 t:landuse=Resident t:best_stat="BP REINSTATED" t:heightlimit=40-X t:planning_neighborhood="Central Waterfront" t:zoning=NCT-2 t:dbi_project_description="ERECT A FOUR STORY EIGHT UNIT RESIDENTIAL BLDG WITH COML" m:office=0 m:prod_dist_rep=0 m:net_medical=0 m:visitor=0 m:units=8 m:net_office=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=521 m:medical=0 m:net_added_sf=0 m:dbi_permit=9902819 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=8 m:net_visitor=0

series e:evrp-pcmc d:2002-07-11T00:00:00.000Z t:block_lot=3746001 t:block=3746 t:planning_neighborhood="Rincon Hill" t:heightlimit=400-W t:building_type_id=4 t:zoning_generalized="Mixed Use" t:planning_project_description="Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail parking spaces and 263 USPS parking spaces." t:lot=1 t:zoning_simplified=RC-4 t:landuse=Resident t:best_stat="BP ISSUED" t:zoning=RC-4 t:dbi_project_description="Multiple Permits" m:office=0 m:prod_dist_rep=0 m:net_medical=0 m:visitor=0 m:units=669 m:net_office=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=765 m:medical=0 m:net_added_sf=0 m:dbi_permit=201207124717 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=669 m:net_visitor=0

series e:evrp-pcmc d:2003-02-21T00:00:00.000Z t:block_lot=3615026 t:block=3615 t:planning_neighborhood=Mission t:heightlimit=65-B t:building_type_id=10 t:zoning_generalized="Mixed Use" t:planning_project_description="The project is to demolish the existing single-story retail building and construct a new building that would be three-stories tall and would contain retail on the ground floor and offices on the second and third floors._x000d_
6/15/05 - Environmental Exemption" t:lot=26 t:zoning_simplified="Mission Street" t:landuse=MIPS t:best_stat="BP ISSUED" t:zoning="Mission St NCT" t:dbi_project_description="ERECT A 3 STORY COMMERCIAL SHOP & OFFICE" m:office=4999 m:prod_dist_rep=0 m:net_medical=0 m:visitor=0 m:units=0 m:net_office=4999 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=176 m:medical=0 m:net_added_sf=4999 m:dbi_permit=200302218059 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=4999 m:net_cult_inst_educ=0 m:net_added_units=0 m:net_visitor=0
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:taz p:integer l:TAZ t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"Total GSF (Commercial)" t:dataTypeName=number

metric m:office p:integer l:Office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"Cult, Inst, Educ" t:dataTypeName=number

metric m:medical p:integer l:Medical t:dataTypeName=number

metric m:prod_dist_rep p:double l:"Prod, Dist, Rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"Ret, Ent" t:dataTypeName=number

metric m:visitor p:integer l:Visitor t:dataTypeName=number

metric m:dbi_permit p:long l:"DBI Permit" t:dataTypeName=number

metric m:net_added_units p:integer l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical p:integer l:"Net Medical" t:dataTypeName=number

metric m:net_office p:integer l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"Net Visitor" t:dataTypeName=number

entity e:evrp-pcmc l:"San Francisco Development Pipeline 2013 Quarter 2" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/evrp-pcmc

property e:evrp-pcmc t:meta.view v:id=evrp-pcmc v:category="Housing and Buildings" v:attributionLink=http://sfplanning.org v:averageRating=0 v:name="San Francisco Development Pipeline 2013 Quarter 2" v:attribution="San Francisco Planning Department"

property e:evrp-pcmc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:evrp-pcmc t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:evrp-pcmc t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | best_stat     | best_date           | building_type_id | units | planning_project_description                                                                                                                                                                                                                                                                            | dbi_project_description                                                                            | zoning_generalized       | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | dbi_permit   | planning_filed      | dbi_filed           | heightlimit   | zoning         | firstfiled          | landuse  | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | block | lot | 
| ========= | ===================== | ============= | =================== | ================ | ===== | ======================================================================================================================================================================================================================================================================================================= | ================================================================================================== | ======================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | ============ | =================== | =================== | ============= | ============== | =================== | ======== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ===== | === | 
| 4172053   | Central Waterfront    | BP REINSTATED | 2009-11-03T00:00:00 | 4                | 8     |                                                                                                                                                                                                                                                                                                         | ERECT A FOUR STORY EIGHT UNIT RESIDENTIAL BLDG WITH COML                                           | Mixed Use                | NCT-2             | 521 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 9902819      | 2001-04-26T00:00:00 | 1999-02-11T00:00:00 | 40-X          | NCT-2          | 1999-02-11T00:00:00 | Resident | 8               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 4172  | 53  | 
| 3746001   | Rincon Hill           | BP ISSUED     | 2013-05-29T00:00:00 | 4                | 669   | Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail parking spaces and 263 USPS parking spaces. | Multiple Permits                                                                                   | Mixed Use                | RC-4              | 765 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 201207124717 | 2002-07-11T00:00:00 | 2012-07-12T00:00:00 | 400-W         | RC-4           | 2002-07-11T00:00:00 | Resident | 669             | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 3746  | 1   | 
| 3615026   | Mission               | BP ISSUED     | 2009-08-26T00:00:00 | 10               | 0     | The project is to demolish the existing single-story retail building and construct a new building that would be three-stories tall and would contain retail on the ground floor and offices on the second and third floors._x000d_ 6/15/05 - Environmental Exemption                                    | ERECT A 3 STORY COMMERCIAL SHOP & OFFICE                                                           | Mixed Use                | Mission Street    | 176 | 4999                 | 4999   | 0              | 0       | 0             | 0       | 0       | 200302218059 | 2003-08-07T00:00:00 | 2003-02-21T00:00:00 | 65-B          | Mission St NCT | 2003-02-21T00:00:00 | MIPS     | 0               | 4999         | 0                  | 0           | 4999       | 0                 | 0           | 0           | 3615  | 26  | 
| 6942039   | Ingleside, Other      | BP ISSUED     | 2008-10-09T00:00:00 | 14               | 2     | Demolish a one-family dwelling and construct a new two-family dwelling in an RH-2 (Residential, House, Two-Family) District and a 40-X Height and Bulk District.                                                                                                                                        | ERECT 3 STORY TWO UNIT DWELLING.                                                                   | Residential              | RH-2              | 53  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200701051057 | 2003-03-25T00:00:00 | 2007-01-05T00:00:00 | 40-X          | RH-2           | 2003-03-25T00:00:00 | Resident | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 6942  | 39  | 
| 5618020   | Bernal Heights        | BP REINSTATED | 2009-02-20T00:00:00 | 14               | 1     | the project proposes the new construction of a single family residence without the required two parking spaces.                                                                                                                                                                                         | ERECT A TWO STORY SINGLE FAMILY DWELING                                                            | Residential              | RH-1              | 116 | 0                    |        |                |         |               |         |         | 200310066599 | 2007-10-18T00:00:00 | 2003-10-06T00:00:00 | 40-X          | RH-1           | 2003-10-06T00:00:00 | Resident | 1               | 0            |                    |             |            |                   |             |             | 5618  | 20  | 
| 7016023   | Ingleside, Other      | BP ISSUED     | 2011-09-28T00:00:00 | 14               | 1     |                                                                                                                                                                                                                                                                                                         | ERECT A THREE STORY SINGLE FAMILY DWELLING                                                         | Residential              | RH-1              | 35  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200311240936 | 2004-09-07T00:00:00 | 2003-11-24T00:00:00 | 40-X          | RH-1           | 2003-11-24T00:00:00 | Resident | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 7016  | 23  | 
| 6176011   | South Central, Other  | BP ISSUED     | 2010-06-04T00:00:00 | 14               | 1     | Erect 3-story Type V, Single-Family Structure in a RH-1/40-X zoning district.                                                                                                                                                                                                                           | ERECT 3-STORY TYPE-V SINGLE FAMILY STRUCTURE                                                       | Residential              | RH-1              | 30  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200401063464 | 2009-01-16T00:00:00 | 2004-01-06T00:00:00 | 40-X          | RH-1           | 2004-01-06T00:00:00 | Resident | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 6176  | 11  | 
| 4645018   | India Basin           | BP ISSUED     | 2013-06-24T00:00:00 | 4                | 4     | Construct a vertical addition to accommodate three DUs, convert ground floor to a three-car garage, and change ground floor use from business to retail in an NC-2 (Small-Scale Neighborhood Commercial) District and a 40-X Height and Bulk District.                                                  | ADD 2 NEW FLOORS TO (E) STRUCTURE.RECONFIGURE (E)SPACE W/NEW ADDED SPACE TO CREATE 1 COMM'L SPACE, | Mixed Use                | NC-2              | 446 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 200402267273 | 2004-12-06T00:00:00 | 2004-02-26T00:00:00 | 40-X          | NC-2           | 2004-02-26T00:00:00 | Resident | 4               | -2560        | 0                  | 0           | 0          | -2560             | 0           | 0           | 4645  | 18  | 
| 3749059   | Rincon Hill           | BP ISSUED     | 2012-09-05T00:00:00 | 4                | 224   | Demolition of an existing building and construction of a 400-foot mixed-use building with 305 dwelling units, 280 off-street parking spaces, and 1,000 GSF of ground floor retail use.                                                                                                                  | TO ERECT 40 STORIES, 224 UNITS RESIDENTIAL & MIXED USE BUILDING.                                   | High Density Residential | RH DTR            | 732 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 201009140800 | 2004-05-19T00:00:00 | 2010-09-14T00:00:00 | 65-X/ 65/400- | RH DTR         | 2004-05-19T00:00:00 | Resident | 224             | -14000       | 0                  | 0           | -15000     | 0                 | 1000        | 0           | 3749  | 59  | 
| 4846018   | BVHP Area A,B         | BP ISSUED     | 2008-05-23T00:00:00 | 7                | 0     |                                                                                                                                                                                                                                                                                                         | ERECT A NEW 2 STORY CONTRACTOR'S WAREHOUSE & OFFICE                                                | Industrial               | PDR-2             | 892 | 7500                 | 1000   | 0              | 0       | 6500          | 0       | 0       | 200405285091 |                     | 2004-05-28T00:00:00 | 40-X          | PDR-2          | 2004-05-28T00:00:00 | PDR      | 0               | 7500         | 0                  | 0           | 1000       | 6500              | 0           | 0           | 4846  | 18  | 
```