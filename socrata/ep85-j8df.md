# San Francisco Development Pipeline 2013 Quarter 4

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/development-pipeline-q4-2013-snapshot-a9dd0) |
| Metadata | [Link](https://data.sfgov.org/api/views/ep85-j8df) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ep85-j8df/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ep85-j8df/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ep85-j8df |
| Name | San Francisco Development Pipeline 2013 Quarter 4 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, construction |
| Created | 2014-02-10T23:59:07Z |
| Publication Date | 2014-02-11T00:03:24Z |

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
| Yes      | series tag     | zoning_generalized           | Zoning_Generalized           | text      | text        |
| Yes      | series tag     | zoning_simplified            | Zoning_Simplified            | text      | text        |
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
| Yes      | series tag     | sort                         | sort                         | text      | text        |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | Net Office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number    | number      |
| Yes      | numeric metric | tempselect                   | TempSelect                   | number    | number      |
| Yes      | numeric metric | sitearea                     | SiteArea                     | number    | number      |
| Yes      | series tag     | block                        | BLOCK                        | text      | number      |
| Yes      | series tag     | lot                          | LOT                          | text      | number      |
| Yes      | numeric metric | parking                      | PARKING                      | number    | number      |
| Yes      | numeric metric | parkingnet                   | PARKINGNET                   | number    | number      |
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
series e:ep85-j8df d:2013-01-01T00:00:00.000Z t:sort="PL Approved" t:block_lot=3722027 t:block=3722 t:sponsor_firm=SFMOMA t:heightlimit=320-I/500-I t:planning_neighborhood=Downtown t:planning_filed=09-Apr-09 t:planning_project_description="Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and ac" t:zoning_generalized=Commercial t:planning_id=2009.0291 t:sponsor_name="Ikuko Satoda" t:lot=27 t:zoning_simplified=C-3-S t:landuse=CIE t:objectid=6 t:best_stat="PL Approved" t:firstfiled=09-Apr-09 t:contactadd="151 Third Street" t:zoning=C-3-S t:fullname="Ikuko Satoda" t:contactcity="San Francisco, CA 94103" m:office=0 m:cult_inst_educ=298378 m:taz=743 m:net_added_sf=66685 m:sitearea=71176 m:total_gsf_commercial=298378 m:supdist=6 m:net_cult_inst_educ=101710 m:tempselect=123 m:units=0 m:net_office=-35025

series e:ep85-j8df d:2013-01-01T00:00:00.000Z t:sort="BP Filed" t:block_lot=1533017 t:block=1533 t:planning_neighborhood=Richmond t:heightlimit=40-X t:zoning_generalized=Residential t:lot=17 t:zoning_simplified=RH-2 t:landuse=Resident t:objectid=11 t:dbi_filed=28-May-09 t:best_stat="BP Filed" t:firstfiled=28-May-09 t:zoning=RH-2 t:dbi_project_description="THREE STORY HORIZONTAL ADDITION AT REAR OF BUILDING, AND CHANGE FROM SINGLE FAMILY DWELLING TO TWO F" m:taz=284 m:net_added_sf=0 m:dbi_permit=200905289263 m:sitearea=2979 m:total_gsf_commercial=0 m:supdist=1 m:net_added_units=1 m:units=2

series e:ep85-j8df d:2013-01-01T00:00:00.000Z t:sort="Planning Filed" t:block_lot=3507042 t:block=3507 t:sponsor_firm="Citizens Housing Corporation" t:heightlimit=150-S/200-S t:planning_neighborhood=Downtown t:planning_filed=08-Apr-09 t:planning_project_description="THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level.  Related to Addendum 2003.0262E EIR." t:zoning_generalized=Commercial t:planning_id=2008.0553 t:sponsor_name="Jake Wegmann" t:contactphone=694-5841 t:lot=42 t:zoning_simplified=C-3-G t:landuse=Mixres t:objectid=1 t:dbi_filed=24-Jun-09 t:best_stat="PL FILED" t:firstfiled=08-Apr-09 t:contactadd="26 O'Farrell St., Suite 600" t:zoning=C-3-G t:fullname="Jake Wegmann 694-5841" t:contactcity="San Francisco, CA 94108" m:office=0 m:parking=18 m:prod_dist_rep=0 m:supdist=6 m:tempselect=12 m:net_medical=0 m:net_office=0 m:units=165 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=608 m:medical=0 m:net_added_sf=3640 m:sitearea=24546 m:ret_ent=3640 m:net_ret_ent=3640 m:total_gsf_commercial=3640 m:net_cult_inst_educ=0 m:net_added_units=165 m:net_visitor=0 m:parkingnet=-57
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

metric m:net_added_units p:integer l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical p:integer l:"Net Medical" t:dataTypeName=number

metric m:net_office p:integer l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"Net Visitor" t:dataTypeName=number

metric m:tempselect p:integer l:TempSelect t:dataTypeName=number

metric m:sitearea p:integer l:SiteArea t:dataTypeName=number

metric m:parking p:integer l:PARKING t:dataTypeName=number

metric m:parkingnet p:integer l:PARKINGNET t:dataTypeName=number

metric m:supdist p:integer l:SUPDIST t:dataTypeName=number

entity e:ep85-j8df l:"San Francisco Development Pipeline 2013 Quarter 4" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/ep85-j8df

property e:ep85-j8df t:meta.view v:id=ep85-j8df v:category="Housing and Buildings" v:attributionLink="http://www.sf-planning.org/index.aspx?page=1691" v:averageRating=0 v:name="San Francisco Development Pipeline 2013 Quarter 4" v:attribution="San Francisco Planning Department"

property e:ep85-j8df t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ep85-j8df t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:ep85-j8df t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| objectid | block_lot | planning_neighborhood | best_stat   | best_date | units | planning_project_description                                                                                                                                                                                                                                    | dbi_project_description                                                                                                                                                                                                 | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed | dbi_filed | heightlimit | zoning | firstfiled | landuse  | sort                           | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | tempselect | sitearea | block | lot | parking | parkingnet | supdist | sponsor_firm                 | sponsor_name      | contactphone | fullname                       | contactcity             | contactadd                       | 
| ======== | ========= | ===================== | =========== | ========= | ===== | =============================================================================================================================================================================================================================================================== | ======================================================================================================================================================================================================================= | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | ============== | ========= | =========== | ====== | ========== | ======== | ============================== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ========== | ======== | ===== | === | ======= | ========== | ======= | ============================ | ================= | ============ | ============================== | ======================= | ================================ | 
| 6        | 3722027   | Downtown              | PL Approved | 13-Jul-10 | 0     | Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and ac |                                                                                                                                                                                                                         | Commercial         | C-3-S             | 743 | 298378               | 0      | 298378         |         |               |         |         | 2009.0291   |              | 09-Apr-09      |           | 320-I/500-I | C-3-S  | 09-Apr-09  | CIE      | PL Approved                    |                 | 66685        | 101710             |             | -35025     |                   |             |             | 123        | 71176    | 3722  | 27  |         |            | 6       | SFMOMA                       | Ikuko Satoda      |              | Ikuko Satoda                   | San Francisco, CA 94103 | 151 Third Street                 | 
| 11       | 1533017   | Richmond              | BP Filed    | 28-May-09 | 2     |                                                                                                                                                                                                                                                                 | THREE STORY HORIZONTAL ADDITION AT REAR OF BUILDING, AND CHANGE FROM SINGLE FAMILY DWELLING TO TWO F                                                                                                                    | Residential        | RH-2              | 284 | 0                    |        |                |         |               |         |         |             | 200905289263 |                | 28-May-09 | 40-X        | RH-2   | 28-May-09  | Resident | BP Filed                       | 1               | 0            |                    |             |            |                   |             |             |            | 2979     | 1533  | 17  |         |            | 1       |                              |                   |              |                                |                         |                                  | 
| 1        | 3507042   | Downtown              | PL FILED    | 08-Apr-09 | 165   | THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level. Related to Addendum 2003.0262E EIR.                                                                        |                                                                                                                                                                                                                         | Commercial         | C-3-G             | 608 | 3640                 | 0      | 0              | 0       | 0             | 3640    | 0       | 2008.0553   |              | 08-Apr-09      | 24-Jun-09 | 150-S/200-S | C-3-G  | 08-Apr-09  | Mixres   | Planning Filed                 | 165             | 3640         | 0                  | 0           | 0          | 0                 | 3640        | 0           | 12         | 24546    | 3507  | 42  | 18      | -57        | 6       | Citizens Housing Corporation | Jake Wegmann      | 694-5841     | Jake Wegmann 694-5841          | San Francisco, CA 94108 | 26 O'Farrell St., Suite 600      | 
| 3        | 0331001A  | Downtown              | PL Filed    | 28-Feb-13 | 7     | Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18  |                                                                                                                                                                                                                         | Mixed Use          | RC-4              | 678 | 12460                | 12460  |                |         |               |         |         | 2009.0343   |              | 28-Feb-13      |           | 80-130-T    | RC-4   | 28-Feb-13  | Mixres   | Planning Filed                 | 4               | 0            |                    |             | 0          |                   |             |             |            | 4538     | 331   |     |         |            | 6       | 229 Ellis Street, LLC        | Michael Wilk      | 415-362-8900 | Michael Wilk 415-362-8900      | San Francisco, CA 94102 | 229 Ellis Street                 | 
| 24       | 0192014   | Northeast             | PL Approved | 12-Jul-12 | 0     | Hospital Replacement and expansion, adding 68,010 gsf total, building new seven-story acute care hospital, moving medical office building uses to existing five-story hospital, and demolishing existing Chinese Hospital and Chinese Hospital Garage (MOB and  |                                                                                                                                                                                                                         | Mixed Use          | CRNC              | 346 | 140990               |        | 140990         |         |               |         |         | 2008.0762   |              | 26-Jun-08      |           | 65-N        | CRNC   | 26-Jun-08  | CIE      | PL Approved                    | 0               | 68010        | 68010              |             |            |                   |             |             | 111        | 30346    | 192   | 14  | 1       | -1         | 3       | Kensington Investments       | Wayne Hu          | 986-1372     | Wayne Hu 986-1372              | San Francisco, CA 94104 | 233 Sansome Street, #1100        | 
| 31       | 0201012   | Northeast             | PL Approved | 19-Jun-12 | 170   | The proposed project would include the temporary removal of the existing Golden Gateway Tennis and Swim Club facility and the new construction of two mixed use buildings and outdoor health club facilities. The new buildings would include 170 residential u |                                                                                                                                                                                                                         | Mixed Use          | RC-4              | 814 | 32100                | 1500   | 0              | 0       | 0             | 30600   | 0       | 2007.0030   |              | 04-Dec-07      |           | 84-E        | RC-4   | 04-Dec-07  | Mixres   | PL Approved                    | 170             | 32100        | 0                  | 0           | 1500       | 0                 | 30600       | 0           | 23         | 113510   | 201   | 12  | 520     | 520        | 3       | Golden Gateway Center        | Tina DiRienzo     | 415-434-2000 | Tina DiRienzo 415-434-2000     | San Francisco, CA 94111 | 460 Davis Court                  | 
| 20       | 0185029   | Northeast             | PL Filed    | 10-Jul-13 | 9     | Multi-unit residential. Changing industrial into apartment building                                                                                                                                                                                             | CONVERT WAREHOUSE BLDG TO 9 UNIT RESID, 21 OFF-STREET PARKING SPACE, RETAINS EAST, SOUTH & WEST WALL                                                                                                                    | Residential        | RM-1              | 345 | 1120                 | 1120   |                |         | 0             |         |         | 2013.0915   | 201210313210 | 10-Jul-13      | 31-Oct-12 | 40-X        | RM-1   | 31-Oct-12  | Mixres   | Planning Filed                 | 9               | -9303        |                    |             | -537       | -8766             |             |             |            | 8779     | 185   | 29  |         |            | 3       | Cline Architects             | James Cline       | 415.706.6953 | James Cline 415.706.6953       | San Francisco, CA 94102 | 870 Market Street, Suite 478     | 
| 149      | 0150054   | Northeast             | PL Filed    | 16-Jan-13 | 6     | Proposed project would involve a three-lot subdivision and the new construction of three two-unit buildings, one on each newly subdivided lot. The buildings would total approximately 19,000 sq. ft., 10 parking spaces, and would be approximately 40 feet in |                                                                                                                                                                                                                         | Residential        | RH-2              | 361 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 2006.1202   |              | 03-Dec-07      |           | 40-X        | RH-2   | 03-Dec-07  | Resident | Planning Filed                 | 6               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           | 111        | 12064    | 150   | 54  |         |            | 3       | JMBM                         | David P. Cincotta | 415-398-8080 | David P. Cincotta 415-398-8080 | San Francisco, CA 94111 | 1 Embarcadero Center, 14th Floor | 
| 223      | 0303014   | Downtown              | BP ISSUED   | 20-Jul-12 | 50    | 9 new construction                                                                                                                                                                                                                                              | Vacant ground floor space to be converted to 4 dwelling units on existin builidng. Work to include remodel at 2nd floor manager's apt to raise floor for headroom below. Convert tourist hotel to sro residental hotel. | Mixed Use          | RC-4              | 707 | 0                    |        |                |         |               |         | 0       | 2007.1056   | 200712311569 |                | 31-Dec-07 | 80-T        | RC-4   | 31-Dec-07  | Resident | BP Approved/Issued/Re-Instated | 4               | -15764       |                    |             |            |                   |             | -15764      |            | 4770     | 303   | 14  |         |            | 6       |                              |                   |              |                                |                         |                                  | 
| 41       | 0620006   | Northeast             | PL Approved | 15-Nov-13 | 28    | 27 Unit residential building and parking for 32 cars parking. Demolition of existing vacant former church & construction of a 27-unit residential building & prking for 32 cars. This application is filed as part of a settlement of pending litigation betwee |                                                                                                                                                                                                                         | Residential        | RM-3              | 343 | 0                    |        |                |         |               |         |         | 2013.0890   |              | 03-Jul-13      |           | 65-A        | RM-3   | 03-Jul-13  | Resident | PL Approved                    | 28              | 0            |                    |             |            |                   |             |             |            | 11369    | 620   | 6   | 39      |            | 3       | Reuben, Junius, & Rose, LLP  | David Silverman   | 415-567-9000 | David Silverman 415-567-9000   | San Francisco, CA 94104 | One Bush Street, Suite 600       | 
```