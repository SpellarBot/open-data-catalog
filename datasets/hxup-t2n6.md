# San Francisco Development Pipeline 2013 Quarter 3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-quarter-3-2013-babd5) |
| Metadata | [Link](https://data.sfgov.org/api/views/hxup-t2n6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hxup-t2n6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hxup-t2n6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hxup-t2n6 |
| Name | San Francisco Development Pipeline 2013 Quarter 3 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, housing, commercial, development, building, retail, condos |
| Created | 2013-12-17T20:28:29Z |
| Publication Date | 2013-12-17T20:32:52Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | block_lot                    | Block Lot                    | text          | text          |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text          | text          |
| Yes      | series tag     | best_stat                    | Best Stat                    | text          | text          |
| No       |                | best_date                    | Best Date                    | text          | text          |
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
| Yes      | series tag     | dbi_filed                    | DBI Filed                    | text          | text          |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text          | text          |
| Yes      | series tag     | zoning                       | ZONING                       | text          | text          |
| Yes      | series tag     | firstfiled                   | FirstFiled                   | html          | html          |
| Yes      | series tag     | objectid                     | ObjectID                     | text          | number        |
| Yes      | series tag     | landuse                      | LANDUSE                      | text          | text          |
| Yes      | series tag     | entitlementstatus            | EntitlementStatus            | text          | checkbox      |
| Yes      | series tag     | statusgroup                  | StatusGroup                  | text          | text          |
| Yes      | numeric metric | action_seq                   | ACTION_SEQ                   | number        | number        |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number        | number        |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number        | number        |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number        | number        |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number        | number        |
| Yes      | numeric metric | net_office                   | Net Office                   | number        | number        |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number        | number        |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number        | number        |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number        | number        |
| Yes      | numeric metric | tempselect                   | TempSelect                   | number        | number        |
| Yes      | numeric metric | sitearea                     | SiteArea                     | number        | number        |
| Yes      | series tag     | block                        | BLOCK                        | text          | text          |
| Yes      | series tag     | lot                          | LOT                          | text          | text          |
| Yes      | numeric metric | parking                      | PARKING                      | number        | number        |
| Yes      | numeric metric | parkingnet                   | PARKINGNET                   | number        | number        |
| Yes      | numeric metric | supdist                      | SUPDIST                      | number        | number        |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text          | text          |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text          | text          |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text          | text          |
| Yes      | series tag     | fullname                     | FULLNAME                     | text          | text          |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text          | text          |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text          | text          |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = best_date,planning_filed
```

## Data Commands

```ls
series e:hxup-t2n6 d:2013-01-01T00:00:00.000Z t:statusgroup="PL Approved" t:block_lot=1643051 t:block=1643 t:heightlimit=40-X t:planning_neighborhood=Richmond t:planning_project_description="One story vertical addition over the existing two-story over garage and convert existing single-family dwelling to two family dwellings." t:zoning_generalized=Residential t:sponsor_name="Gus Fallay" t:planning_id=2008.1273 t:contactphone=510-469-5202 t:zoning_simplified=RM-2 t:lot=051 t:landuse=Resident t:firstfiled=02-Mar-10 t:best_stat="PL Approved" t:objectid=1027 t:contactadd="595 Market Street, Suite 1350" t:zoning=RM-2 t:fullname="Gus Fallay 510-469-5202" t:contactcity="San Francisco, CA 94105" m:taz=637 m:net_added_sf=0 m:sitearea=2506 m:total_gsf_commercial=0 m:supdist=1 m:net_added_units=1 m:action_seq=5 m:units=2

series e:hxup-t2n6 d:2013-01-01T00:00:00.000Z t:statusgroup="BP Filed" t:entitlementstatus=false t:block_lot=2396036 t:block=2396 t:heightlimit=50-X t:planning_neighborhood="Outer Sunset" t:zoning_generalized="Mixed Use" t:dbi_permit=200612069310 t:zoning_simplified=NC-2 t:lot=036 t:landuse=Resident t:dbi_filed=06-Dec-06 t:firstfiled=06-Dec-06 t:best_stat="BP Filed" t:objectid=1040 t:zoning=NC-2 t:dbi_project_description="ADD 2 FLOORS ON TOP OF(E)BLDG. & ALSO HORIZONTAL ADDITION TOWARDS REAR YARD. COMPLETED BUILDING TO HAVE: 1/F- 520 SQ.FT. OF OFFICE SPACE & 2 CAR GARAGE.2/F RESIDENT-UNIT#1 WITH LIVING ROOM, DINING ROOM, KITCHEN, SUTDY ROOM, 2 BEDROOM, 2 BATHS.3/F UNIT#2-L" m:office=0 m:prod_dist_rep=0 m:supdist=4 m:net_medical=0 m:action_seq=6 m:visitor=0 m:units=2 m:net_office=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=435 m:medical=0 m:net_added_sf=0 m:ret_ent=0 m:sitearea=1988 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=2 m:net_visitor=0

series e:hxup-t2n6 d:2013-01-01T00:00:00.000Z t:statusgroup="PL Approved" t:block_lot=2515001 t:block=2515 t:sponsor_firm="Hamilton & Company Architecture" t:heightlimit=100-A t:planning_neighborhood="Outer Sunset" t:planning_project_description="Demolition of existing buildings and construction of three new five-story buildings with a total of 55 dwelling units, 48 parking spaces in an underground parking garage, 26,000 gsf of ground floor retail, and 34 covered spaces for the commercial use." t:zoning_generalized="Mixed Use" t:sponsor_name="Rachel Hamilton" t:planning_id=2005.1066 t:contactphone=510-549-1312 t:zoning_simplified=NC-2 t:lot=001 t:landuse=Resident t:firstfiled=19-Jul-07 t:objectid=1054 t:best_stat="PL Approved" t:contactadd="1035 Carleton Street, Suite 100" t:zoning=NC-2 t:fullname="Rachel Hamilton 510-549-1312" t:contactcity="Berkeley, CA 94710" m:office=0 m:prod_dist_rep=0 m:supdist=4 m:net_medical=0 m:action_seq=5 m:visitor=0 m:units=55 m:net_office=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=99 m:medical=0 m:net_added_sf=9656 m:ret_ent=0 m:sitearea=33763 m:net_ret_ent=26000 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=55 m:net_visitor=-16344 m:parkingnet=82
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

metric m:action_seq p:integer l:ACTION_SEQ t:dataTypeName=number

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

entity e:hxup-t2n6 l:"San Francisco Development Pipeline 2013 Quarter 3" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/hxup-t2n6

property e:hxup-t2n6 t:meta.view v:id=hxup-t2n6 v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2013 Quarter 3" v:attribution="San Francisco Planning Department"

property e:hxup-t2n6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hxup-t2n6 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:hxup-t2n6 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | best_stat    | best_date | units | planning_project_description                                                                                                                                                                                                                                | dbi_project_description                                                                                                                                                                                                                                         | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed | dbi_filed | heightlimit | zoning | firstfiled | objectid | landuse  | entitlementstatus | statusgroup                    | action_seq | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | tempselect | sitearea | block | lot  | parking | parkingnet | supdist | sponsor_firm                    | sponsor_name        | contactphone | fullname                         | contactcity             | contactadd                      | 
| ========= | ===================== | ============ | ========= | ===== | =========================================================================================================================================================================================================================================================== | =============================================================================================================================================================================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | ============== | ========= | =========== | ====== | ========== | ======== | ======== | ================= | ============================== | ========== | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | ========== | ======== | ===== | ==== | ======= | ========== | ======= | =============================== | =================== | ============ | ================================ | ======================= | =============================== | 
| 1643051   | Richmond              | PL Approved  | 12-Jan-09 | 2     | One story vertical addition over the existing two-story over garage and convert existing single-family dwelling to two family dwellings.                                                                                                                    |                                                                                                                                                                                                                                                                 | Residential        | RM-2              | 637 | 0                    |        |                |         |               |         |         | 2008.1273   |              |                |           | 40-X        | RM-2   | 02-Mar-10  | 1027     | Resident |                   | PL Approved                    | 5          | 1               | 0            |                    |             |            |                   |             |             |            | 2506     | 1643  | 051  |         |            | 1       |                                 | Gus Fallay          | 510-469-5202 | Gus Fallay 510-469-5202          | San Francisco, CA 94105 | 595 Market Street, Suite 1350   | 
| 2396036   | Outer Sunset          | BP Filed     | 06-Dec-06 | 2     |                                                                                                                                                                                                                                                             | ADD 2 FLOORS ON TOP OF(E)BLDG. & ALSO HORIZONTAL ADDITION TOWARDS REAR YARD. COMPLETED BUILDING TO HAVE: 1/F- 520 SQ.FT. OF OFFICE SPACE & 2 CAR GARAGE.2/F RESIDENT-UNIT#1 WITH LIVING ROOM, DINING ROOM, KITCHEN, SUTDY ROOM, 2 BEDROOM, 2 BATHS.3/F UNIT#2-L | Mixed Use          | NC-2              | 435 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       |             | 200612069310 |                | 06-Dec-06 | 50-X        | NC-2   | 06-Dec-06  | 1040     | Resident | false             | BP Filed                       | 6          | 2               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           |            | 1988     | 2396  | 036  |         |            | 4       |                                 |                     |              |                                  |                         |                                 | 
| 2515001   | Outer Sunset          | PL Approved  | 13-Nov-08 | 55    | Demolition of existing buildings and construction of three new five-story buildings with a total of 55 dwelling units, 48 parking spaces in an underground parking garage, 26,000 gsf of ground floor retail, and 34 covered spaces for the commercial use. |                                                                                                                                                                                                                                                                 | Mixed Use          | NC-2              | 99  | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 2005.1066   |              |                |           | 100-A       | NC-2   | 19-Jul-07  | 1054     | Resident |                   | PL Approved                    | 5          | 55              | 9656         | 0                  | 0           | 0          | 0                 | 26000       | -16344      |            | 33763    | 2515  | 001  |         | 82         | 4       | Hamilton & Company Architecture | Rachel Hamilton     | 510-549-1312 | Rachel Hamilton 510-549-1312     | Berkeley, CA 94710      | 1035 Carleton Street, Suite 100 | 
| 2799013   | Central               | CONSTRUCTION | 13-Mar-07 | 3     | 3 New Unit Condominium                                                                                                                                                                                                                                      | TO ERECT 4 STORY 3 DWELLING RESIDENCE                                                                                                                                                                                                                           | Residential        | RM-1              | 167 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 2006.0641   | 200201106632 |                | 10-Jan-02 | 40-X        | RM-1   | 10-Jan-02  | 1059     | Resident |                   | Construction                   | 13         | 3               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           |            | 2857     | 2799  | 013  |         |            | 8       | HERZIG & BERLESE                | MARGARET J. BERLESE | 415.861.8800 | MARGARET J. BERLESE 415.861.8800 | SF, CA 94102            | 414 GOUGH ST, #5                | 
| 1671008M  | Richmond              | PL Approved  | 10-Jul-08 | 2     | New Construction                                                                                                                                                                                                                                            |                                                                                                                                                                                                                                                                 | Residential        | RH-2              | 251 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       | 2006.1470   |              |                |           | 40-X        | RH-2   | 06-Dec-06  | 1063     | Resident |                   | PL Approved                    | 5          | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           |            | 3024     | 1671  | 008M |         |            | 1       |                                 |                     |              |                                  |                         |                                 | 
| 1672018   | Richmond              | BP ISSUED    | 26-Jan-09 | 2     |                                                                                                                                                                                                                                                             | (N) THIRD FLOOR VERTICAL ADDITION (2ND UNIT). RELOCATE GARAGE DOOR & ENTRANCE. EXPAND & RECONFIGURE                                                                                                                                                             | Residential        | RH-2              | 250 | 0                    |        |                |         |               |         |         |             | 200711289065 |                | 28-Nov-07 | 40-X        | RH-2   | 28-Nov-07  | 1066     | Resident |                   | BP Approved/Issued/Re-Instated | 11         | 1               | 0            |                    |             |            |                   |             |             |            | 3000     | 1672  | 018  |         |            | 1       |                                 |                     |              |                                  |                         |                                 | 
| 1684002I  | Richmond              | CONSTRUCTION | 03-Jun-11 | 2     | To construct a two-story vertical addition, fill in side setbacks at the rear of the structure and add one dwelling unit per the enclosed plans.                                                                                                            | 2 STORY VERTICAL ADDITION OVER EXISTING 2 STORY. CONVERT FROM 1 UNIT TO 2 UNITS                                                                                                                                                                                 | Residential        | RH-2              | 576 | 0                    |        |                |         |               |         |         | 2008.0742   | 200712200952 |                | 20-Dec-07 | 40-X        | RH-2   | 20-Dec-07  | 1071     | Resident |                   | Construction                   | 13         | 1               | 0            |                    |             |            |                   |             |             |            | 2500     | 1684  | 002I |         |            | 1       |                                 | Ronald Gate         | 793-2722     | Ronald Gate 793-2722             | San Francisco, CA 94122 | 750 Lawton Street               | 
| 1684004L  | Richmond              | PL Approved  | 15-Feb-08 | 2     | Add 2nd unit to 3rd floor of existing building. Remodel existing 2nd floor and garage floor.                                                                                                                                                                | ADD 3/F NEW 2ND UNIT ADDITION, LEGALIZED EXISTING GROUND FLOOR ROOM & EXTENTION.                                                                                                                                                                                | Residential        | RH-2              | 576 | 0                    |        |                |         |               |         |         | 2008.0079   | 200612200235 |                |           | 40-X        | RH-2   | 16-Jan-08  | 1072     | Resident |                   | PL Approved                    | 10         | 1               | 0            |                    |             |            |                   |             |             |            | 2416     | 1684  | 004L |         |            | 1       |                                 | Anthony Tam         | 415-509-5025 | Anthony Tam 415-509-5025         | San Francisco, CA 94122 | 3649 Lawton Street #622         | 
| 1686033   | Richmond              | CONSTRUCTION | 29-Jun-06 | 1     |                                                                                                                                                                                                                                                             | ADDITION OF NEW 3/F & ADDITION OF NEW DWELLING UNIT                                                                                                                                                                                                             | Residential        | RH-2              | 576 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       |             | 200412161565 |                | 16-Dec-04 | 40-X        | RH-2   | 16-Dec-04  | 1073     | Resident |                   | Construction                   | 13         | 1               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           |            | 3480     | 1686  | 033  |         |            | 1       |                                 |                     |              |                                  |                         |                                 | 
| 1688001A  | Richmond              | BP Filed     | 13-Dec-06 | 3     |                                                                                                                                                                                                                                                             | ERECT 4 STORIES 3 DWELLING UNITS BLDG. PLUS COMMERCIAL                                                                                                                                                                                                          | Mixed Use          | NC-1              | 689 | 0                    | 0      | 0              | 0       | 0             | 0       | 0       |             | 200612139805 |                | 13-Dec-06 | 40-X        | NC-1   | 13-Dec-06  | 1074     | Resident | false             | BP Filed                       | 6          | 3               | 0            | 0                  | 0           | 0          | 0                 | 0           | 0           |            | 2500     | 1688  | 001A |         |            | 1       |                                 |                     |              |                                  |                         |                                 | 
```