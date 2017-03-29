# San Francisco Development Pipeline 2014 Quarter 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-q2-2014-f06f7) |
| Metadata | [Link](https://data.sfgov.org/api/views/fv2q-qaux) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fv2q-qaux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fv2q-qaux/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fv2q-qaux |
| Name | San Francisco Development Pipeline 2014 Quarter 2 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, construction |
| Created | 2014-09-12T17:43:20Z |
| Publication Date | 2014-09-12T17:45:55Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | block_lot                    | Block Lot                    | text          | text          |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text          | text          |
| Yes      | series tag     | best_stat                    | Best Stat                    | text          | text          |
| Yes      | time           | best_date                    | Best Date                    | calendar_date | calendar_date |
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
| Yes      | series tag     | planning_id                  | Planning ID                  | text          | text          |
| Yes      | series tag     | dbi_permit                   | DBI Permit                   | text          | text          |
| No       |                | planning_filed               | Planning Filed               | calendar_date | calendar_date |
| No       |                | dbi_filed                    | DBI Filed                    | calendar_date | calendar_date |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text          | text          |
| Yes      | numeric metric | heightnum                    | HeightNum                    | number        | number        |
| Yes      | series tag     | zoning                       | ZONING                       | text          | text          |
| No       |                | firstfiled                   | FirstFiled                   | calendar_date | calendar_date |
| Yes      | series tag     | objectid                     | ObjectID                     | text          | number        |
| Yes      | series tag     | landuse                      | LANDUSE                      | text          | text          |
| Yes      | series tag     | sort                         | sort                         | text          | text          |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number        | number        |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number        | number        |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number        | number        |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number        | number        |
| Yes      | numeric metric | net_office                   | Net Office                   | number        | number        |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number        | number        |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number        | number        |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number        | number        |
| Yes      | series tag     | planningdistrictscombo       | PlanningDistrictsCombo       | text          | text          |
| Yes      | numeric metric | affordable                   | AFFORDABLE                   | number        | number        |
| Yes      | numeric metric | affordablenet                | AFFORDABLENET                | number        | number        |
| Yes      | series tag     | entitlementstatus            | EntitlementStatus            | text          | number        |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text          | text          |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text          | text          |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text          | text          |
| Yes      | series tag     | fullname                     | FULLNAME                     | text          | text          |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text          | text          |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text          | text          |
```

## Time Field

```ls
Value = best_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = planning_filed,dbi_filed,firstfiled
```

## Data Commands

```ls
series e:fv2q-qaux d:2009-04-08T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort="Planning Filed" t:entitlementstatus=0 t:block_lot=3507042 t:sponsor_firm="Citizens Housing Corporation" t:heightlimit=150-S/200-S t:planning_neighborhood=Downtown t:planning_project_description="THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level.  Related to Addendum 2003.0262E EIR." t:zoning_generalized=Commercial t:planning_id=2008.0553 t:sponsor_name="Jake Wegmann" t:contactphone=694-5841 t:zoning_simplified=C-3-G t:landuse=Mixres t:objectid=1 t:best_stat="PL FILED" t:contactadd="26 O'Farrell St., Suite 600" t:zoning=C-3-G t:fullname="Jake Wegmann 694-5841" t:contactcity="San Francisco, CA 94108" m:office=0 m:prod_dist_rep=0 m:heightnum=150 m:net_medical=0 m:affordable=165 m:net_office=0 m:visitor=0 m:units=165 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=608 m:medical=0 m:net_added_sf=3640 m:ret_ent=3640 m:net_ret_ent=3640 m:total_gsf_commercial=3640 m:net_cult_inst_educ=0 m:net_added_units=165 m:affordablenet=165 m:net_visitor=0

series e:fv2q-qaux d:2013-02-28T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort="Planning Filed" t:entitlementstatus=0 t:block_lot=0331001A t:sponsor_firm="229 Ellis Street, LLC" t:heightlimit=80-130-T t:planning_neighborhood=Downtown t:planning_project_description="Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18 res units (14,668 sf) and 5,704 sf retail." t:zoning_generalized="Mixed Use" t:planning_id=2009.0343 t:sponsor_name="Michael Wilk" t:contactphone=415-362-8900 t:zoning_simplified=RC-4 t:landuse=Mixres t:objectid=3 t:best_stat="PL Filed" t:contactadd="229 Ellis Street" t:zoning=RC-4 t:fullname="Michael Wilk 415-362-8900" t:contactcity="San Francisco, CA 94102" m:office=12460 m:taz=678 m:net_added_sf=0 m:heightnum=80 m:total_gsf_commercial=12460 m:net_added_units=4 m:units=7 m:net_office=0

series e:fv2q-qaux d:2014-06-17T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort=Construction t:block_lot=3722027 t:entitlementstatus=-1 t:sponsor_firm=SFMOMA t:heightlimit=320-I/500-I t:planning_neighborhood=Downtown t:planning_project_description="Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and accomodation of W Hotel porte-cochere to continue through back of Heald site to Natoma Street. No new parking or loading for single building six story addition, 101,710-gsf." t:zoning_generalized=Commercial t:planning_id=2009.0291 t:dbi_permit=201211093897 t:sponsor_name="Ikuko Satoda" t:zoning_simplified=C-3-S t:landuse=CIE t:objectid=6 t:best_stat=CONSTRUCTION t:contactadd="151 Third Street" t:zoning=C-3-S t:fullname="Ikuko Satoda" t:contactcity="San Francisco, CA 94103" m:office=0 m:cult_inst_educ=298378 m:taz=743 m:net_added_sf=66685 m:heightnum=320 m:total_gsf_commercial=298378 m:net_cult_inst_educ=101710 m:units=0 m:net_office=-35025
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:taz p:integer l:TAZ t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"Total GSF (Commercial)" t:dataTypeName=number

metric m:office p:integer l:Office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"Cult, Inst, Educ" t:dataTypeName=number

metric m:medical p:integer l:Medical t:dataTypeName=number

metric m:prod_dist_rep p:integer l:"Prod, Dist, Rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"Ret, Ent" t:dataTypeName=number

metric m:visitor p:integer l:Visitor t:dataTypeName=number

metric m:heightnum p:integer l:HeightNum t:dataTypeName=number

metric m:net_added_units p:integer l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical p:integer l:"Net Medical" t:dataTypeName=number

metric m:net_office p:integer l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"Net Visitor" t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordablenet p:integer l:AFFORDABLENET t:dataTypeName=number

entity e:fv2q-qaux l:"San Francisco Development Pipeline 2014 Quarter 2" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/fv2q-qaux

property e:fv2q-qaux t:meta.view v:id=fv2q-qaux v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2014 Quarter 2" v:attribution="San Francisco Planning Department"

property e:fv2q-qaux t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fv2q-qaux t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:fv2q-qaux t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | best_stat    | best_date           | units | planning_project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | dbi_project_description                                                                              | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed      | dbi_filed           | heightlimit | heightnum | zoning             | firstfiled          | objectid | landuse  | sort                           | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | planningdistrictscombo | affordable | affordablenet | entitlementstatus | sponsor_firm                 | sponsor_name    | contactphone | fullname                     | contactcity             | contactadd                   | 
| ========= | ===================== | ============ | =================== | ===== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ==================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | =================== | =================== | =========== | ========= | ================== | =================== | ======== | ======== | ============================== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ====================== | ========== | ============= | ================= | ============================ | =============== | ============ | ============================ | ======================= | ============================ | 
| 3507042   | Downtown              | PL FILED     | 2009-04-08T00:00:00 | 165   | THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level. Related to Addendum 2003.0262E EIR.                                                                                                                                                                                                                                                                                                                                                                  |                                                                                                      | Commercial         | C-3-G             | 608 | 3640                 | 0      | 0              | 0       | 0             | 3640    | 0       | 2008.0553   |              | 2009-04-08T00:00:00 | 2009-06-24T00:00:00 | 150-S/200-S | 150       | C-3-G              | 2009-04-08T00:00:00 | 1        | Mixres   | Planning Filed                 | 165             | 3640         | 0                  | 0           | 0          | 0                 | 3640        | 0           | Downtown               | 165        | 165           | 0                 | Citizens Housing Corporation | Jake Wegmann    | 694-5841     | Jake Wegmann 694-5841        | San Francisco, CA 94108 | 26 O'Farrell St., Suite 600  | 
| 0331001A  | Downtown              | PL Filed     | 2013-02-28T00:00:00 | 7     | Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18 res units (14,668 sf) and 5,704 sf retail.                                                                                                                                                                                                                                                 |                                                                                                      | Mixed Use          | RC-4              | 678 | 12460                | 12460  |                |         |               |         |         | 2009.0343   |              | 2013-02-28T00:00:00 |                     | 80-130-T    | 80        | RC-4               | 2013-02-28T00:00:00 | 3        | Mixres   | Planning Filed                 | 4               | 0            |                    |             | 0          |                   |             |             | Downtown               |            |               | 0                 | 229 Ellis Street, LLC        | Michael Wilk    | 415-362-8900 | Michael Wilk 415-362-8900    | San Francisco, CA 94102 | 229 Ellis Street             | 
| 3722027   | Downtown              | CONSTRUCTION | 2014-06-17T00:00:00 | 0     | Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and accomodation of W Hotel porte-cochere to continue through back of Heald site to Natoma Street. No new parking or loading for single building six story addition, 101,710-gsf.                                                                                                                |                                                                                                      | Commercial         | C-3-S             | 743 | 298378               | 0      | 298378         |         |               |         |         | 2009.0291   | 201211093897 | 2009-04-09T00:00:00 |                     | 320-I/500-I | 320       | C-3-S              | 2009-04-09T00:00:00 | 6        | CIE      | Construction                   |                 | 66685        | 101710             |             | -35025     |                   |             |             | Downtown               |            |               | -1                | SFMOMA                       | Ikuko Satoda    |              | Ikuko Satoda                 | San Francisco, CA 94103 | 151 Third Street             | 
| 1533017   | Richmond              | BP Filed     | 2009-05-28T00:00:00 | 2     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | THREE STORY HORIZONTAL ADDITION AT REAR OF BUILDING, AND CHANGE FROM SINGLE FAMILY DWELLING TO TWO F | Residential        | RH-2              | 284 | 0                    |        |                |         |               |         |         |             | 200905289263 |                     | 2009-05-28T00:00:00 | 40-X        | 40        | RH-2               | 2009-05-28T00:00:00 | 11       | Resident | BP Filed                       | 1               | 0            |                    |             |            |                   |             |             | Richmond               |            |               | 0                 |                              |                 |              |                              |                         |                              | 
| 185029    | Northeast             | PL Filed     | 2013-07-10T00:00:00 | 9     | Multi-unit residential. Changing industrial into apartment building                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | CONVERT WAREHOUSE BLDG TO 9 UNIT RESID, 21 OFF-STREET PARKING SPACE, RETAINS EAST, SOUTH & WEST WALL | Residential        | RM-1              | 345 | 1120                 | 1120   |                |         | 0             |         |         | 2013.0915   | 201210313210 | 2013-07-10T00:00:00 | 2012-10-31T00:00:00 | 40-X        | 40        | Pacific Avenue NCD | 2012-10-31T00:00:00 | 20       | Mixres   | Planning Filed                 | 9               | -9303        |                    |             | -537       | -8766             |             |             | Northeast              |            |               | 0                 | Cline Architects             | James Cline     | 415.706.6953 | James Cline 415.706.6953     | San Francisco, CA 94102 | 870 Market Street, Suite 478 | 
| 192014    | Northeast             | PL Approved  | 2012-07-12T00:00:00 | 0     | Hospital Replacement and expansion, adding 68,010 gsf total, building new seven-story acute care hospital, moving medical office building uses to existing five-story hospital, and demolishing existing Chinese Hospital and Chinese Hospital Garage (MOB and garage), equivalent parking provision for hospital through purchase of Powell Street Garage, displacing existing auto repair and commercial garage; Chinese Hospital IMP under development.                                                                                                |                                                                                                      | Mixed Use          | CRNC              | 346 | 140990               |        | 140990         |         |               |         |         | 2008.0762   |              | 2008-06-26T00:00:00 |                     | 65-N        | 65        | CRNC               | 2008-06-26T00:00:00 | 24       | CIE      | PL Approved                    | 0               | 68010        | 68010              |             |            |                   |             |             | Northeast              |            |               | -1                | Kensington Investments       | Wayne Hu        | 986-1372     | Wayne Hu 986-1372            | San Francisco, CA 94104 | 233 Sansome Street, #1100    | 
| 201012    | Northeast             | PL Approved  | 2012-06-19T00:00:00 | 170   | The proposed project would include the temporary removal of the existing Golden Gateway Tennis and Swim Club facility and the new construction of two mixed use buildings and outdoor health club facilities. The new buildings would include 170 residential units (286,400 sq.ft.), 18,600 sq. ft. of retail and restaurant, a 12,000 sq. ft. health club, 1,500 sq. ft. of office, and 520 parking spaces. The new buildings would be 84 feet in height, eight-story with three levels of below grade parking, and approximately 614,000 gross sq. ft. |                                                                                                      | Mixed Use          | RC-4              | 814 | 32100                | 1500   | 0              | 0       | 0             | 30600   | 0       | 2007.003    |              | 2007-12-04T00:00:00 |                     | 84-E        | 84        | RC-4               | 2007-12-04T00:00:00 | 31       | Mixres   | PL Approved                    | 170             | 32100        | 0                  | 0           | 1500       | 0                 | 30600       | 0           | Northeast              |            |               | -1                | Golden Gateway Center        | Tina DiRienzo   | 415-434-2000 | Tina DiRienzo 415-434-2000   | San Francisco, CA 94111 | 460 Davis Court              | 
| 620006    | Northeast             | PL Approved  | 2013-11-15T00:00:00 | 28    | 27 Unit residential building and parking for 32 cars parking. Demolition of existing vacant former church & construction of a 27-unit residential building & prking for 32 cars. This application is filed as part of a settlement of pending litigation between the church & the city regarding development of the church's property.                                                                                                                                                                                                                    |                                                                                                      | Residential        | RM-3              | 343 | 0                    |        |                |         |               |         |         | 2013.089    |              | 2013-07-03T00:00:00 |                     | 65-A        | 65        | RM-3               | 2013-07-03T00:00:00 | 41       | Resident | PL Approved                    | 28              | 0            |                    |             |            |                   |             |             | Northeast              |            |               | -1                | Reuben, Junius, & Rose, LLP  | David Silverman | 415-567-9000 | David Silverman 415-567-9000 | San Francisco, CA 94104 | One Bush Street, Suite 600   | 
| 25017     | Northeast             | CONSTRUCTION | 2014-05-30T00:00:00 | 1     | Demolition of an existing 558-sq. ft. one-story warehouse and construction of a new four-unit residential building over 5,589 sq. ft. of groundfloor retail. The new building would be four stories, approximately 40 feet in height, totaling approximately 12,029 sq. ft. The exisitng building was constructed in 1912.                                                                                                                                                                                                                                | TO ERECT 3 STORIES, 1 UNIT RESIDENTIAL / COMMERCIAL BUILDING.                                        | Commercial         | C-2               | 847 | 5589                 | 0      | 0              | 0       | 0             | 5589    | 0       | 2006.0441   | 201011295645 | 2006-11-07T00:00:00 | 2010-11-29T00:00:00 | 40-X        | 40        | C-2                | 2006-11-07T00:00:00 | 60       | Mixres   | Construction                   | 1               | 5589         | 0                  | 0           | 0          | 0                 | 5589        | 0           | Northeast              |            |               | -1                | Patri Merker Architects      | Marie Zeller    | 415-334-6494 | Marie Zeller 415-334-6494    | San Francisco, CA 94131 | 318 Arlington Street         | 
| 2821010   | Inner Sunset          | BP ISSUED    | 2014-04-04T00:00:00 | 1     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | ERECT A NEW 2 STORY SINGLE FAMILY DWELLING.                                                          | Residential        | RH-1              | 151 | 0                    |        |                |         |               |         |         |             | 200711077576 |                     | 2007-11-07T00:00:00 | 40-X        | 40        | RH-1               | 2007-11-07T00:00:00 | 1349     | Resident | BP Approved/Issued/Re-Instated | 1               | 0            |                    |             |            |                   |             |             | Inner Sunset           |            |               | -1                |                              |                 |              |                              |                         |                              | 
```