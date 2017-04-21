# San Francisco Development Pipeline 2014 Quarter 3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/20141219-pipeline-q3-2014-c8030) |
| Metadata | [Link](https://data.sfgov.org/api/views/n5ik-nmm3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/n5ik-nmm3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/n5ik-nmm3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | n5ik-nmm3 |
| Name | San Francisco Development Pipeline 2014 Quarter 3 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, construction |
| Created | 2014-12-19T23:49:26Z |
| Publication Date | 2014-12-19T23:53:00Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | objectid                     | ObjectID                     | text          | number        |
| Yes      | series tag     | block_lot                    | Block Lot                    | text          | text          |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text          | text          |
| Yes      | series tag     | best_stat                    | Best Stat                    | text          | text          |
| No       |                | best_date                    | Best Date                    | calendar_date | calendar_date |
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
| Yes      | series tag     | planning_id                  | Planning ID                  | text          | number        |
| Yes      | numeric metric | dbi_permit                   | DBI Permit                   | number        | number        |
| Yes      | series tag     | planning_filed               | Planning Filed               | text          | text          |
| Yes      | series tag     | dbi_filed                    | DBI Filed                    | text          | text          |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text          | text          |
| Yes      | numeric metric | heightnum                    | HeightNum                    | number        | number        |
| Yes      | series tag     | zoning                       | ZONING                       | text          | text          |
| Yes      | series tag     | firstfiled                   | FirstFiled                   | text          | text          |
| Yes      | series tag     | landuse                      | LANDUSE                      | text          | text          |
| Yes      | series tag     | beststat_group               | BESTSTAT GROUP               | text          | text          |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number        | number        |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number        | number        |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number        | number        |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number        | number        |
| Yes      | numeric metric | net_office                   | Net Office                   | number        | number        |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number        | number        |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number        | number        |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number        | number        |
| Yes      | series tag     | planningdistrictscombo       | PlanningDistrictsCombo       | text          | text          |
| Yes      | series tag     | entitlementstatus            | EntitlementStatus            | text          | number        |
| Yes      | series tag     | pda                          | PDA                          | text          | text          |
| Yes      | numeric metric | totalsqftestim               | TotalSqftEstim               | number        | number        |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text          | text          |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text          | text          |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text          | text          |
| Yes      | series tag     | fullname                     | FULLNAME                     | text          | text          |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text          | text          |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text          | text          |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = best_date
```

## Data Commands

```ls
series e:n5ik-nmm3 d:2014-01-01T00:00:00.000Z t:planningdistrictscombo=Japantown t:entitlementstatus=0 t:block_lot=0686040 t:beststat_group="BP Filed" t:planning_neighborhood=Japantown t:zoning_generalized="Mixed Use" t:zoning_simplified=NC-2 t:landuse=Resident t:objectid=6367 t:dbi_filed=23-Sep-14 t:best_stat="BP Filed" t:firstfiled=23-Sep-14 t:zoning=NC-2 t:dbi_project_description="CHANGE OF USE: CONVERTING (E) 2ND FLOOR RETAIL SPACE (3,475 SF) TO FOUR RESIDENTIAL APARTMENT UNITS." m:taz=705 m:net_added_sf=0 m:dbi_permit=201409237117 m:heightnum=9999 m:total_gsf_commercial=0 m:totalsqftestim=4800 m:net_added_units=4 m:units=4

series e:n5ik-nmm3 d:2014-01-01T00:00:00.000Z t:planningdistrictscombo=Downtown t:block_lot=3722367 t:entitlementstatus=-1 t:beststat_group=Construction t:sponsor_firm=SFMOMA t:heightlimit=500-I t:planning_neighborhood=Downtown t:planning_filed=09-Apr-09 t:planning_project_description="Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and ac" t:zoning_generalized=Commercial t:planning_id=2009.0291 t:sponsor_name="Ikuko Satoda" t:pda="San Francisco: Downtown-Van Ness-Geary" t:zoning_simplified=C-3-O t:landuse=CIE t:objectid=6 t:best_stat=CONSTRUCTION t:firstfiled=09-Apr-09 t:contactadd="151 Third Street" t:zoning=C-3-O t:fullname="Ikuko Satoda" t:contactcity="San Francisco, CA 94103" m:office=0 m:cult_inst_educ=298378 m:taz=743 m:net_added_sf=66685 m:dbi_permit=201211093897 m:heightnum=500 m:total_gsf_commercial=298378 m:totalsqftestim=298378 m:net_cult_inst_educ=101710 m:units=0 m:net_office=-35025

series e:n5ik-nmm3 d:2014-01-01T00:00:00.000Z t:planningdistrictscombo=Downtown t:block_lot=3507042 t:entitlementstatus=0 t:beststat_group="Planning Filed" t:sponsor_firm="Citizens Housing Corporation" t:heightlimit=150-S/200-S t:planning_neighborhood=Downtown t:planning_filed=08-Apr-09 t:planning_project_description="THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level.  Related to Addendum 2003.0262E EIR." t:zoning_generalized=Commercial t:planning_id=2008.0553 t:sponsor_name="Jake Wegmann" t:contactphone=694-5841 t:pda="San Francisco: Downtown-Van Ness-Geary" t:zoning_simplified=C-3-G t:landuse=Mixres t:objectid=1 t:dbi_filed=24-Jun-09 t:best_stat="PL FILED" t:firstfiled=08-Apr-09 t:contactadd="26 O'Farrell St., Suite 600" t:zoning=C-3-G t:fullname="Jake Wegmann 694-5841" t:contactcity="San Francisco, CA 94108" m:office=0 m:prod_dist_rep=0 m:heightnum=150 m:net_medical=0 m:net_office=0 m:visitor=0 m:units=165 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=608 m:medical=0 m:net_added_sf=3640 m:ret_ent=3640 m:net_ret_ent=3640 m:total_gsf_commercial=3640 m:totalsqftestim=243955 m:net_cult_inst_educ=0 m:net_added_units=165 m:net_visitor=0
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

metric m:dbi_permit p:long l:"DBI Permit" t:dataTypeName=number

metric m:heightnum p:integer l:HeightNum t:dataTypeName=number

metric m:net_added_units p:integer l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical p:integer l:"Net Medical" t:dataTypeName=number

metric m:net_office p:integer l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"Net Visitor" t:dataTypeName=number

metric m:totalsqftestim p:integer l:TotalSqftEstim t:dataTypeName=number

entity e:n5ik-nmm3 l:"San Francisco Development Pipeline 2014 Quarter 3" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/n5ik-nmm3

property e:n5ik-nmm3 t:meta.view v:id=n5ik-nmm3 v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2014 Quarter 3" v:attribution="San Francisco Planning Department"

property e:n5ik-nmm3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:n5ik-nmm3 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:n5ik-nmm3 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| objectid | block_lot | planning_neighborhood | best_stat    | best_date | units | planning_project_description                                                                                                                                                                                                                                    | dbi_project_description                                                                              | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed | dbi_filed | heightlimit | heightnum | zoning             | firstfiled | landuse  | beststat_group | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | planningdistrictscombo | entitlementstatus | pda                                    | totalsqftestim | sponsor_firm                 | sponsor_name    | contactphone | fullname                     | contactcity             | contactadd                    | 
| ======== | ========= | ===================== | ============ | ========= | ===== | =============================================================================================================================================================================================================================================================== | ==================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | ============== | ========= | =========== | ========= | ================== | ========== | ======== | ============== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ====================== | ================= | ====================================== | ============== | ============================ | =============== | ============ | ============================ | ======================= | ============================= | 
| 6367     | 0686040   | Japantown             | BP Filed     |           | 4     |                                                                                                                                                                                                                                                                 | CHANGE OF USE: CONVERTING (E) 2ND FLOOR RETAIL SPACE (3,475 SF) TO FOUR RESIDENTIAL APARTMENT UNITS. | Mixed Use          | NC-2              | 705 | 0                    |        |                |         |               |         |         |             | 201409237117 |                | 23-Sep-14 |             | 9999      | NC-2               | 23-Sep-14  | Resident | BP Filed       | 4               | 0            |                    |             |            |                   |             |             | Japantown              | 0                 |                                        | 4800           |                              |                 |              |                              |                         |                               | 
| 6        | 3722367   | Downtown              | CONSTRUCTION |           | 0     | Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and ac |                                                                                                      | Commercial         | C-3-O             | 743 | 298378               | 0      | 298378         |         |               |         |         | 2009.0291   | 201211093897 | 09-Apr-09      |           | 500-I       | 500       | C-3-O              | 09-Apr-09  | CIE      | Construction   |                 | 66685        | 101710             |             | -35025     |                   |             |             | Downtown               | -1                | San Francisco: Downtown-Van Ness-Geary | 298378         | SFMOMA                       | Ikuko Satoda    |              | Ikuko Satoda                 | San Francisco, CA 94103 | 151 Third Street              | 
| 1        | 3507042   | Downtown              | PL FILED     |           | 165   | THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level. Related to Addendum 2003.0262E EIR.                                                                        |                                                                                                      | Commercial         | C-3-G             | 608 | 3640                 | 0      | 0              | 0       | 0             | 3640    | 0       | 2008.0553   |              | 08-Apr-09      | 24-Jun-09 | 150-S/200-S | 150       | C-3-G              | 08-Apr-09  | Mixres   | Planning Filed | 165             | 3640         | 0                  | 0           | 0          | 0                 | 3640        | 0           | Downtown               | 0                 | San Francisco: Downtown-Van Ness-Geary | 243955         | Citizens Housing Corporation | Jake Wegmann    | 694-5841     | Jake Wegmann 694-5841        | San Francisco, CA 94108 | 26 O'Farrell St., Suite 600   | 
| 3        | 0331001A  | Downtown              | PL Filed     |           | 7     | Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18  |                                                                                                      | Mixed Use          | RC-4              | 678 | 12460                | 12460  |                |         |               |         |         | 2009.0343   |              | 28-Feb-13      |           | 80-130-T    | 80        | RC-4               | 28-Feb-13  | Mixres   | Planning Filed | 4               | 0            |                    |             | 0          |                   |             |             | Downtown               | 0                 | San Francisco: Downtown-Van Ness-Geary | 31440          | 229 Ellis Street, LLC        | Michael Wilk    | 415-362-8900 | Michael Wilk 415-362-8900    | San Francisco, CA 94102 | 229 Ellis Street              | 
| 11       | 1533017   | Richmond              | BP Filed     |           | 2     |                                                                                                                                                                                                                                                                 | THREE STORY HORIZONTAL ADDITION AT REAR OF BUILDING, AND CHANGE FROM SINGLE FAMILY DWELLING TO TWO F | Residential        | RH-2              | 284 | 0                    |        |                |         |               |         |         |             | 200905289263 |                | 28-May-09 | 40-X        | 40        | RH-2               | 28-May-09  | Resident | BP Filed       | 1               | 0            |                    |             |            |                   |             |             | Richmond               | 0                 |                                        | 2400           |                              |                 |              |                              |                         |                               | 
| 20       | 0185029   | Northeast             | PL Filed     |           | 9     | Multi-unit residential. Changing industrial into apartment building                                                                                                                                                                                             | CONVERT WAREHOUSE BLDG TO 9 UNIT RESID, 21 OFF-STREET PARKING SPACE, RETAINS EAST, SOUTH & WEST WALL | Residential        | RM-1              | 345 | 1120                 | 1120   |                |         | 0             |         |         | 2013.0915   | 201210313210 | 10-Jul-13      | 31-Oct-12 | 40-X        | 40        | Pacific Avenue NCD | 31-Oct-12  | Mixres   | Planning Filed | 9               | -9303        |                    |             | -537       | -8766             |             |             | Northeast              | 0                 | San Francisco: Downtown-Van Ness-Geary | 1120           | Cline Architects             | James Cline     | 415.706.6953 | James Cline 415.706.6953     | San Francisco, CA 94102 | 870 Market Street, Suite 478  | 
| 24       | 0192014   | Northeast             | PL Approved  |           | 0     | Hospital Replacement and expansion, adding 68,010 gsf total, building new seven-story acute care hospital, moving medical office building uses to existing five-story hospital, and demolishing existing Chinese Hospital and Chinese Hospital Garage (MOB and  |                                                                                                      | Mixed Use          | CRNC              | 346 | 140990               |        | 140990         |         |               |         |         | 2008.0762   |              | 26-Jun-08      |           | 65-N        | 65        | CRNC               | 26-Jun-08  | CIE      | PL Approved    | 0               | 68010        | 68010              |             |            |                   |             |             | Northeast              | -1                | San Francisco: Downtown-Van Ness-Geary | 140990         | Kensington Investments       | Wayne Hu        | 986-1372     | Wayne Hu 986-1372            | San Francisco, CA 94104 | 233 Sansome Street, #1100     | 
| 27       | 0194009   | Northeast             | PL Filed     |           | 24    | Change of use from 3,317.5 sf residential use over 9,994.5 sf ground floor commercial to 24 units (11,612 sf) of group housing over 1,700 sf of ground floor restuarant use.                                                                                    |                                                                                                      | Mixed Use          | CVR               | 792 | 1700                 |        |                |         |               | 1700    |         | 2014.0775   |              | 26-Sep-14      |           | 50-N        | 50        | CVR                | 26-Sep-14  | Mixres   | Planning Filed | 23              | -8294        |                    |             |            |                   | -8294       |             | Northeast              | 0                 | San Francisco: Downtown-Van Ness-Geary | 13312          | Darosa & Associates          | Johnny Darosa   | 650 692-4072 | Johnny Darosa 650 692-4072   | Millbrae, Ca 94030      | 475 El Camino Real, Suite 308 | 
| 31       | 0201012   | Northeast             | PL Approved  |           | 170   | The proposed project would include the temporary removal of the existing Golden Gateway Tennis and Swim Club facility and the new construction of two mixed use buildings and outdoor health club facilities. The new buildings would include 170 residential u |                                                                                                      | Mixed Use          | RC-4              | 814 | 32100                | 1500   | 0              | 0       | 0             | 30600   | 0       | 2007.0030   |              | 04-Dec-07      |           | 84-E        | 84        | RC-4               | 04-Dec-07  | Mixres   | PL Approved    | 170             | 32100        | 0                  | 0           | 1500       | 0                 | 30600       | 0           | Northeast              | -1                | San Francisco: Downtown-Van Ness-Geary | 318500         | Golden Gateway Center        | Tina DiRienzo   | 415-434-2000 | Tina DiRienzo 415-434-2000   | San Francisco, CA 94111 | 460 Davis Court               | 
| 41       | 0620006   | Northeast             | PL Approved  |           | 28    | 27 Unit residential building and parking for 32 cars parking. Demolition of existing vacant former church & construction of a 27-unit residential building & prking for 32 cars. This application is filed as part of a settlement of pending litigation betwee |                                                                                                      | Residential        | RM-3              | 343 | 0                    |        |                |         |               |         |         | 2013.0890   |              | 03-Jul-13      |           | 65-A        | 65        | RM-3               | 03-Jul-13  | Resident | PL Approved    | 28              | 0            |                    |             |            |                   |             |             | Northeast              | -1                | San Francisco: Downtown-Van Ness-Geary | 30150          | Reuben, Junius, & Rose, LLP  | David Silverman | 415-567-9000 | David Silverman 415-567-9000 | San Francisco, CA 94104 | One Bush Street, Suite 600    | 
```