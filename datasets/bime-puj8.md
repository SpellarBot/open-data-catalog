# San Francisco Development Pipeline 2013 Quarter 1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-pipeline-map-first-quarter-2013-d2de0) |
| Metadata | [Link](https://data.sfgov.org/api/views/bime-puj8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/bime-puj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/bime-puj8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | bime-puj8 |
| Name | San Francisco Development Pipeline 2013 Quarter 1 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, commercial, real estate |
| Created | 2013-06-01T00:53:19Z |
| Publication Date | 2013-06-01T00:59:42Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection&#x27;s Permit Tracking and the Planning Department&#x27;s Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | block_lot                    | Block Lot                    | html      | html        |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text      | text        |
| Yes      | series tag     | best_stat                    | Best Stat                    | text      | text        |
| No       |                | best_date                    | Best Date                    | text      | text        |
| Yes      | numeric metric | units                        | Units                        | number    | number      |
| Yes      | series tag     | planning_project_description | Planning Project Description | text      | text        |
| Yes      | series tag     | dbi_project_description      | DBI Project Description      | text      | text        |
| Yes      | series tag     | zoning_generalized           | Zoning Generalized           | text      | text        |
| Yes      | series tag     | zoning_simplified            | Zoning Simplified            | text      | text        |
| Yes      | numeric metric | taz                          | TAZ                          | number    | number      |
| Yes      | numeric metric | total_gsf_commercial         | Total GSF (Commercial)       | number    | number      |
| Yes      | numeric metric | office                       | Office                       | number    | number      |
| Yes      | numeric metric | cult_inst_educ               | Cult, Inst, Educ             | number    | number      |
| Yes      | numeric metric | medical                      | Medical                      | number    | number      |
| Yes      | numeric metric | prod_dist_rep                | Prod, Dist, Rep              | number    | number      |
| Yes      | numeric metric | ret_ent                      | Ret, Ent                     | number    | number      |
| Yes      | numeric metric | visitor                      | Visitor                      | number    | number      |
| Yes      | series tag     | planning_id                  | Planning ID                  | text      | number      |
| Yes      | numeric metric | dbi_permit                   | DBI Permit                   | number    | number      |
| Yes      | series tag     | planning_filed               | Planning Filed               | text      | text        |
| Yes      | series tag     | dbi_filed                    | DBI Filed                    | text      | text        |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text      | text        |
| Yes      | series tag     | zoning                       | ZONING                       | text      | text        |
| Yes      | series tag     | firstfiled                   | FirstFiled                   | text      | text        |
| Yes      | series tag     | landuse                      | LANDUSE                      | text      | text        |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | Net Office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number    | number      |
| Yes      | numeric metric | supdist                      | SUPDIST                      | number    | number      |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text      | text        |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text      | text        |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text      | text        |
| Yes      | series tag     | fullname                     | FULLNAME                     | text      | text        |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text      | text        |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = best_date
```

## Data Commands

```ls
series e:bime-puj8 d:2013-01-01T00:00:00.000Z t:zoning_generalized=Residential t:block_lot=0185029 t:zoning_simplified=RM-1 t:landuse=Resident t:dbi_filed=31-Oct-12 t:best_stat="BP Filed" t:firstfiled=31-Oct-12 t:heightlimit=40-X t:planning_neighborhood=Northeast t:zoning=RM-1 t:dbi_project_description="CONVERT WAREHOUSE BLDG TO 9 UNIT RESID, 21 OFF-STREET PARKING SPACE, RETAINS EAST, SOUTH & WEST WALL" m:taz=345 m:net_added_sf=3999 m:dbi_permit=201210313210 m:total_gsf_commercial=0 m:supdist=3 m:net_added_units=9 m:units=9 m:net_office=3999

series e:bime-puj8 d:2013-01-01T00:00:00.000Z t:block_lot=0192014 t:sponsor_firm="Kensington Investments" t:heightlimit=65-N t:planning_neighborhood=Northeast t:planning_filed=26-Jun-08 t:planning_project_description="Hospital Replacement and expansion, adding 68,010 gsf total, building new seven-story acute care hospital, moving medical office building uses to existing five-story hospital, and demolishing existing Chinese Hospital and Chinese Hospital Garage (MOB and" t:zoning_generalized="Mixed Use" t:planning_id=2008.0762 t:sponsor_name="Wayne Hu" t:contactphone=986-1372 t:zoning_simplified=CRNC t:landuse=CIE t:firstfiled=26-Jun-08 t:best_stat="PL Approved" t:contactadd="233 Sansome Street, #1100" t:zoning=CRNC t:fullname="Wayne Hu 986-1372" t:contactcity="San Francisco, CA 94104" m:cult_inst_educ=140990 m:taz=346 m:net_added_sf=68010 m:total_gsf_commercial=140990 m:supdist=3 m:net_cult_inst_educ=68010 m:net_added_units=0 m:units=0

series e:bime-puj8 d:2013-01-01T00:00:00.000Z t:block_lot=3507042 t:sponsor_firm="Citizens Housing Corporation" t:heightlimit=150-S/200-S t:planning_neighborhood=Downtown t:planning_filed=08-Apr-09 t:planning_project_description="THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level.  Related to Addendum 2003.0262E EIR." t:zoning_generalized=Commercial t:planning_id=2008.0553 t:sponsor_name="Jake Wegmann" t:contactphone=694-5841 t:zoning_simplified=C-3-G t:landuse=Mixres t:dbi_filed=24-Jun-09 t:firstfiled=08-Apr-09 t:best_stat="PL FILED" t:contactadd="26 O'Farrell St., Suite 600" t:zoning=C-3-G t:fullname="Jake Wegmann 694-5841" t:contactcity="San Francisco, CA 94108" m:office=0 m:prod_dist_rep=0 m:supdist=6 m:net_medical=0 m:visitor=0 m:units=165 m:net_office=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=608 m:medical=0 m:net_added_sf=3640 m:ret_ent=3640 m:net_ret_ent=3640 m:total_gsf_commercial=3640 m:net_cult_inst_educ=0 m:net_added_units=165 m:net_visitor=0
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

metric m:supdist p:integer l:SUPDIST t:dataTypeName=number

entity e:bime-puj8 l:"San Francisco Development Pipeline 2013 Quarter 1" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/bime-puj8

property e:bime-puj8 t:meta.view v:id=bime-puj8 v:category="Housing and Buildings" v:attributionLink=http://sfplanning.org v:averageRating=0 v:name="San Francisco Development Pipeline 2013 Quarter 1" v:attribution="San Francisco Planning Department"

property e:bime-puj8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:bime-puj8 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:bime-puj8 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | best_stat     | best_date | units | planning_project_description                                                                                                                                                                                                                                    | dbi_project_description                                                                              | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed | dbi_filed | heightlimit | zoning | firstfiled | landuse  | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | supdist | sponsor_firm                 | sponsor_name  | contactphone | fullname                   | contactcity             | contactadd                  | 
| ========= | ===================== | ============= | ========= | ===== | =============================================================================================================================================================================================================================================================== | ==================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | ============== | ========= | =========== | ====== | ========== | ======== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ======= | ============================ | ============= | ============ | ========================== | ======================= | =========================== | 
| 0185029   | Northeast             | BP Filed      | 31-Oct-12 | 9     |                                                                                                                                                                                                                                                                 | CONVERT WAREHOUSE BLDG TO 9 UNIT RESID, 21 OFF-STREET PARKING SPACE, RETAINS EAST, SOUTH & WEST WALL | Residential        | RM-1              | 345 | 0                    |        |                |         |               |         |         |             | 201210313210 |                | 31-Oct-12 | 40-X        | RM-1   | 31-Oct-12  | Resident | 9               | 3999         |                    |             | 3999       |                   |             |             | 3       |                              |               |              |                            |                         |                             | 
| 0192014   | Northeast             | PL Approved   | 12-Jul-12 | 0     | Hospital Replacement and expansion, adding 68,010 gsf total, building new seven-story acute care hospital, moving medical office building uses to existing five-story hospital, and demolishing existing Chinese Hospital and Chinese Hospital Garage (MOB and  |                                                                                                      | Mixed Use          | CRNC              | 346 | 140990               |        | 140990         |         |               |         |         | 2008.0762   |              | 26-Jun-08      |           | 65-N        | CRNC   | 26-Jun-08  | CIE      | 0               | 68010        | 68010              |             |            |                   |             |             | 3       | Kensington Investments       | Wayne Hu      | 986-1372     | Wayne Hu 986-1372          | San Francisco, CA 94104 | 233 Sansome Street, #1100   | 
| 3507042   | Downtown              | PL FILED      | 08-Apr-09 | 165   | THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level. Related to Addendum 2003.0262E EIR.                                                                        |                                                                                                      | Commercial         | C-3-G             | 608 | 3640                 | 0      | 0              | 0       | 0             | 3640    | 0       | 2008.0553   |              | 08-Apr-09      | 24-Jun-09 | 150-S/200-S | C-3-G  | 08-Apr-09  | Mixres   | 165             | 3640         | 0                  | 0           | 0          | 0                 | 3640        | 0           | 6       | Citizens Housing Corporation | Jake Wegmann  | 694-5841     | Jake Wegmann 694-5841      | San Francisco, CA 94108 | 26 O'Farrell St., Suite 600 | 
| 0221020   | Northeast             | CONSTRUCTION  | 26-Apr-13 | 3     | Two-floor vertical addition of a residential unit and 2 parking spaces.                                                                                                                                                                                         | ADDITION OF 2 NEW FLOORS, 2 ONSITE PARKING SPACES, CONVERSION OF RESIDENTIAL DUPLEX INTO RESIDENTIAL | Residential        | RM-3              | 341 | 0                    |        |                |         |               |         |         | 2009.0906   | 200905077950 | 28-Sep-09      | 07-May-09 | 65-A        | RM-3   | 07-May-09  | Resident | 1               | 0            |                    |             |            |                   |             |             | 3       | Tecta Associates             | Ahmad Mohazab | 415-362-5857 | Ahmad Mohazab 415-362-5857 | San Francisco, CA 94110 | 2747 - 19th Street          | 
| 0331001A  | Downtown              | PL Filed      | 28-Feb-13 | 7     | Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18  |                                                                                                      | Mixed Use          | RC-4              | 678 | 12460                | 12460  |                |         |               |         |         | 2009.0343   |              | 28-Feb-13      |           | 80-130-T    | RC-4   | 28-Feb-13  | Mixres   | 4               | 0            |                    |             | 0          |                   |             |             | 6       | 229 Ellis Street, LLC        | Michael Wilk  | 415-362-8900 | Michael Wilk 415-362-8900  | San Francisco, CA 94102 | 229 Ellis Street            | 
| 3722027   | Downtown              | PL Approved   | 13-Jul-10 | 0     | Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and ac |                                                                                                      | Commercial         | C-3-S             | 743 | 298378               | 0      | 298378         |         |               |         |         | 2009.0291   |              | 09-Apr-09      |           | 320-I/500-I | C-3-S  | 09-Apr-09  | CIE      |                 | 66685        | 101710             |             | -35025     |                   |             |             | 6       | SFMOMA                       | Ikuko Satoda  |              | Ikuko Satoda               | San Francisco, CA 94103 | 151 Third Street            | 
| 1533017   | Richmond              | BP Filed      | 28-May-09 | 2     |                                                                                                                                                                                                                                                                 | THREE STORY HORIZONTAL ADDITION AT REAR OF BUILDING, AND CHANGE FROM SINGLE FAMILY DWELLING TO TWO F | Residential        | RH-2              | 284 | 0                    |        |                |         |               |         |         |             | 200905289263 |                | 28-May-09 | 40-X        | RH-2   | 28-May-09  | Resident | 1               | 0            |                    |             |            |                   |             |             | 1       |                              |               |              |                            |                         |                             | 
| 0201012   | Northeast             | PL Approved   | 19-Jun-12 | 170   | The proposed project would include the temporary removal of the existing Golden Gateway Tennis and Swim Club facility and the new construction of two mixed use buildings and outdoor health club facilities. The new buildings would include 170 residential u |                                                                                                      | Mixed Use          | RC-4              | 814 | 32100                | 1500   | 0              | 0       | 0             | 30600   | 0       | 2007.0030   |              | 04-Dec-07      |           | 84-E        | RC-4   | 04-Dec-07  | Mixres   | 170             | 32100        | 0                  | 0           | 1500       | 0                 | 30600       | 0           | 3       | Golden Gateway Center        | Tina DiRienzo | 415-434-2000 | Tina DiRienzo 415-434-2000 | San Francisco, CA 94111 | 460 Davis Court             | 
| 0025017   | Northeast             | BP REINSTATED | 24-Apr-13 | 1     | Demolition of an existing 558-sq. ft. one-story warehouse and construction of a new four-unit residential building over 5,589 sq. ft. of groundfloor retail. The new building would be four stories, approximately 40 feet in height, totaling approximately 12 | TO ERECT 3 STORIES, 1 UNIT RESIDENTIAL / COMMERCIAL BUILDING.                                        | Commercial         | C-2               | 847 | 5589                 | 0      | 0              | 0       | 0             | 5589    | 0       | 2006.0441   | 201011295645 | 07-Nov-06      | 29-Nov-10 | 40-X        | C-2    | 07-Nov-06  | Mixres   | 1               | 5589         | 0                  | 0           | 0          | 0                 | 5589        | 0           | 3       | Patri Merker Architects      | Marie Zeller  | 415-334-6494 | Marie Zeller 415-334-6494  | San Francisco, CA 94131 | 318 Arlington Street        | 
| 0028014   | Northeast             | PL Approved   | 08-Jun-11 | 20    | Remove office, new construction 20-unit residential condominium with approximately 6,500 sf retail and 20 parking spaces at ground floor. Variance required because no commercial parking is provided.                                                          |                                                                                                      | Commercial         | C-2               | 832 | 6500                 | 0      |                |         |               | 6500    |         | 2008.0723   |              | 29-Jul-09      |           | 40-X        | C-2    | 29-Jul-09  | Mixres   | 20              | -9352        |                    |             | -15852     |                   | 6500        |             | 3       | Divisadero Hayes LLC         | Bruce Baumann | 415-551-7884 | Bruce Baumann 415-551-7884 | San Francisco, CA 94103 | 1221 Harrison Street, #22   | 
```