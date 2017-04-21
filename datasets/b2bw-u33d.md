# San Francisco Development Pipeline 2012 Quarter 4

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-pipeline-data-fourth-quarter-2012-09c21) |
| Metadata | [Link](https://data.sfgov.org/api/views/b2bw-u33d) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/b2bw-u33d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/b2bw-u33d/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | b2bw-u33d |
| Name | San Francisco Development Pipeline 2012 Quarter 4 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | development, housing, construction, planning |
| Created | 2013-01-19T00:27:55Z |
| Publication Date | 2013-01-19T00:30:45Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
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
| Yes      | series tag     | entitlementstatus            | EntitlementStatus            | text      | number      |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | Net Office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number    | number      |
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
series e:b2bw-u33d d:2012-01-01T00:00:00.000Z t:zoning_generalized=Residential t:block_lot=3027A001 t:entitlementstatus=-1 t:zoning_simplified=RH-1 t:landuse=Resident t:dbi_filed=06-May-08 t:best_stat=CONSTRUCTION t:firstfiled=06-May-08 t:heightlimit=40-X t:planning_neighborhood="Ingleside, Other" t:zoning=RH-1 t:dbi_project_description="CONSTRUCTION OF THREE-STORY SINGLE FAMILY DWELLING." m:taz=436 m:net_added_sf=0 m:dbi_permit=200805061381 m:total_gsf_commercial=0 m:net_added_units=3 m:units=3

series e:b2bw-u33d d:2012-01-01T00:00:00.000Z t:planning_filed=14-Dec-09 t:planning_project_description="New construction of mixed-use building with approximately 60 units of affordable housing, and 7,000 sq.ft of retail, and 6 parking spaces." t:zoning_generalized="Mixed Use" t:planning_id=2009.1117 t:block_lot=3180001 t:entitlementstatus=-1 t:zoning_simplified=NC-T t:landuse=Mixres t:best_stat="PL Approved" t:firstfiled=14-Dec-09 t:heightlimit=40-X/55-X/65- t:planning_neighborhood="Balboa Park" t:zoning="Ocean Avenue NCT/P" m:office=1139 m:taz=65 m:net_added_sf=11682 m:ret_ent=10543 m:net_ret_ent=10543 m:total_gsf_commercial=11682 m:net_added_units=71 m:units=71 m:net_office=1139

series e:b2bw-u33d d:2012-01-01T00:00:00.000Z t:entitlementstatus=0 t:block_lot=3197010 t:planning_neighborhood="Balboa Park" t:heightlimit=45-X t:planning_filed=15-May-08 t:planning_project_description="Demolition of an existing gas station with accessory use and construction of a 4-story building with 13 residential units over commercial space and a 13-car garage." t:zoning_generalized="Mixed Use" t:planning_id=2008.0538 t:zoning_simplified=NC-T t:landuse=Resident t:dbi_filed=31-Oct-08 t:firstfiled=15-May-08 t:best_stat="BP Filed" t:zoning="Ocean Avenue NCT" t:dbi_project_description="ERECT 4 STORIES COMMERCIAL & RESIDENTIAL, 13 DWELLING UNITS BUILDING." m:net_medical=0 m:net_office=0 m:units=13 m:net_prod_dist_rep=0 m:taz=915 m:net_added_sf=-2500 m:dbi_permit=200810315636 m:net_ret_ent=-2500 m:ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=13 m:net_visitor=0
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

entity e:b2bw-u33d l:"San Francisco Development Pipeline 2012 Quarter 4" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/b2bw-u33d

property e:b2bw-u33d t:meta.view v:id=b2bw-u33d v:category="Housing and Buildings" v:attributionLink=http://sfplanning.org v:averageRating=0 v:name="San Francisco Development Pipeline 2012 Quarter 4" v:attribution="San Francisco Planning Department"

property e:b2bw-u33d t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:b2bw-u33d t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:b2bw-u33d t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| block_lot | planning_neighborhood | best_stat     | best_date | units | planning_project_description                                                                                                                                                                                                             | dbi_project_description                                                                              | zoning_generalized | zoning_simplified | taz | total_gsf_commercial | office | cult_inst_educ | medical | prod_dist_rep | ret_ent | visitor | planning_id | dbi_permit   | planning_filed | dbi_filed | heightlimit   | zoning             | firstfiled | landuse  | entitlementstatus | net_added_units | net_added_sf | net_cult_inst_educ | net_medical | net_office | net_prod_dist_rep | net_ret_ent | net_visitor | 
| ========= | ===================== | ============= | ========= | ===== | ======================================================================================================================================================================================================================================== | ==================================================================================================== | ================== | ================= | === | ==================== | ====== | ============== | ======= | ============= | ======= | ======= | =========== | ============ | ============== | ========= | ============= | ================== | ========== | ======== | ================= | =============== | ============ | ================== | =========== | ========== | ================= | =========== | =========== | 
| 3027A001  | Ingleside, Other      | CONSTRUCTION  | 24-Aug-11 | 3     |                                                                                                                                                                                                                                          | CONSTRUCTION OF THREE-STORY SINGLE FAMILY DWELLING.                                                  | Residential        | RH-1              | 436 | 0                    |        |                |         |               |         |         |             | 200805061381 |                | 06-May-08 | 40-X          | RH-1               | 06-May-08  | Resident | -1                | 3               | 0            |                    |             |            |                   |             |             | 
| 3180001   | Balboa Park           | PL Approved   | 12-Jul-10 | 71    | New construction of mixed-use building with approximately 60 units of affordable housing, and 7,000 sq.ft of retail, and 6 parking spaces.                                                                                               |                                                                                                      | Mixed Use          | NC-T              | 65  | 11682                | 1139   |                |         |               | 10543   |         | 2009.1117   |              | 14-Dec-09      |           | 40-X/55-X/65- | Ocean Avenue NCT/P | 14-Dec-09  | Mixres   | -1                | 71              | 11682        |                    |             | 1139       |                   | 10543       |             | 
| 3197010   | Balboa Park           | BP Filed      | 31-Oct-08 | 13    | Demolition of an existing gas station with accessory use and construction of a 4-story building with 13 residential units over commercial space and a 13-car garage.                                                                     | ERECT 4 STORIES COMMERCIAL & RESIDENTIAL, 13 DWELLING UNITS BUILDING.                                | Mixed Use          | NC-T              | 915 | 0                    |        |                |         |               | 0       |         | 2008.0538   | 200810315636 | 15-May-08      | 31-Oct-08 | 45-X          | Ocean Avenue NCT   | 15-May-08  | Resident | 0                 | 13              | -2500        | 0                  | 0           | 0          | 0                 | -2500       | 0           | 
| 3507041   | Downtown              | CONSTRUCTION  | 23-Feb-12 | 719   | Construction of new mixed-use building containing approximately 719 dwelling units and up to 719 parking spaces                                                                                                                          | TO ERECT A NEW 35 STORY 719 DWELLING UNITS WITH RETAIL & PARKING & ASSEMBLY SPACE                    | Commercial         | C-3-G             | 608 | 12250                | 0      | 0              | 0       | 0             | 12250   | 0       | 2006.0584   | 200607207084 | 03-May-06      | 20-Jul-06 | 200-S/320-S   | C-3-G              | 03-May-06  | Mixres   | -1                | 719             | 12250        | 0                  | 0           | 0          | 0                 | 12250       | 0           | 
| 3509027   | WSoMa                 | BP Filed      | 30-Jul-08 | 2     | DEMOLITION OF EXISTING ONE-STORY OVER GARAGE SINGLE-FAMILY HOME. CONSTRUCTION OF A 5-STORY BUILDING WITH TWO RESIDENTIAL UNITS AND TWO OFFICES.                                                                                          | TO ERECT A NEW 5 STORY 2 UNIT BUILDING WITH OFFICES.                                                 | Industrial         | SLR               | 609 | 0                    | 0      |                |         |               |         |         | 2007.1230   | 200807308027 | 05-Jun-08      | 30-Jul-08 | 50-X          | SLR                | 05-Jun-08  | Resident | -1                | 1               | 0            |                    |             | 0          |                   |             |             | 
| 3510001   | Downtown              | BP Filed      | 31-Oct-08 | 117   | Demo. of a tire store and construction of a 16-story mixed-use project with 156 dwelling units, 156 off-street valet parking spaces, and 2,350 GSF of ground floor retail use & 2,430 sf office. Zoning Map Change, CU, and Section 309. | CONSTRUCTION OF FOURTEEN STORIES WITH 3 BASEMENTS ONE HUNDRED SEVENTEEN UNITS W/COMMERCIAL MIXED USE | Industrial         | C-M               | 609 | 4780                 | 2430   | 0              | 0       | 0             | 2350    | 0       | 2005.0540   | 200810315586 | 27-Aug-09      | 31-Oct-08 | 130-L         | C-M                | 31-Oct-08  | Mixres   | -1                | 117             | 300          | 0                  | 0           | 2430       | -4480             | 2350        | 0           | 
| 3518007   | WSoMa                 | CONSTRUCTION  | 22-Apr-09 | 2     | Shadow Study for a new mixed-use building                                                                                                                                                                                                | ERECT A FIVE STORY COML BLDG WITH 2 RESIDENTIAL UNITS                                                | Industrial         | SLR               | 595 | 3750                 | 0      | 0              | 0       | 0             | 3750    | 0       | 2002.0820   | 200203151582 | 18-Jul-02      | 15-Mar-02 | 50-X          | SLR                | 15-Mar-02  | Mixres   | -1                | 2               | 3750         | 0                  | 0           | 0          | 0                 | 3750        | 0           | 
| 3525046   | WSoMa                 | BP ISSUED     | 13-Aug-08 | 0     |                                                                                                                                                                                                                                          | CONSTRUCTION OF 2-STORY TYPE 5-1 HOUR AUTOMOBILE REPAIR SHOP.                                        | Industrial         | SLI               | 599 | 1496.25              |        |                |         | 1496.25       |         |         |             | 200712069799 |                | 06-Dec-07 | 40-X          | SLI                | 06-Dec-07  | PDR      | -1                | 0               | 1496.25      |                    |             |            | 1496.25           |             |             | 
| 3530049   | Mission               | BP ISSUED     | 22-Apr-08 | 1     |                                                                                                                                                                                                                                          | Change of occupancy at 2nd floor to R-3/ PROVIDE 1 HOUR SEPARATION BETWEEN NEW DWELLING UNIT AND EXI | Industrial         | PDR-1-G           | 590 | 0                    |        |                |         |               |         |         |             | 200710034503 |                | 03-Oct-07 | 58-X          | PDR-1-G            | 03-Oct-07  | Resident | -1                | 1               | 0            |                    |             |            |                   |             |             | 
| 3533165   | Market Octavia        | BP REINSTATED | 06-Mar-12 | 3     | The proposal is to demolish an existing office building and construct a new residential, four-story building containing three dwelling units.                                                                                            | TO ERECT 4 STORY 3 FAMILY DWELLING                                                                   | Residential        | RTO               | 232 | 0                    | 0      |                |         |               |         |         | 2007.0984   | 200708109444 | 20-Aug-07      | 10-Aug-07 | 40-X          | RTO                | 10-Aug-07  | Resident | -1                | 3               | -1640        |                    |             | -1640      |                   |             |             | 
```