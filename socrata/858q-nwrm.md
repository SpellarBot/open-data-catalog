# San Francisco Development Pipeline 2014 Quarter 4

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sf-pipeline-q4-2014) |
| Metadata | [Link](https://data.sfgov.org/api/views/858q-nwrm) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/858q-nwrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/858q-nwrm/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 858q-nwrm |
| Name | San Francisco Development Pipeline 2014 Quarter 4 |
| Category | Housing and Buildings |
| Tags | pipeline, development |
| Created | 2015-05-03T19:14:56Z |
| Publication Date | 2015-09-11T19:47:20Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | neighborhood       | NEIGHBORHOOD       | text          | text          |
| Yes      | series tag     | blklot             | BLKLOT             | text          | text          |
| Yes      | series tag     | nameaddr           | NAMEADDR           | text          | text          |
| Yes      | numeric metric | units              | UNITS              | number        | number        |
| Yes      | numeric metric | unitsnet           | UNITSNET           | number        | number        |
| Yes      | time           | bestdate           | BESTDATE           | calendar_date | calendar_date |
| Yes      | series tag     | beststat           | BESTSTAT           | text          | text          |
| Yes      | series tag     | entitlementstatus  | EntitlementStatus  | text          | checkbox      |
| Yes      | series tag     | caseno             | CASENO             | text          | text          |
| Yes      | series tag     | descript           | DESCRIPT           | text          | text          |
| Yes      | series tag     | pln_review         | PLN_REVIEW         | text          | text          |
| No       |                | pln_reviewdate     | PLN_REVIEWDATE     | calendar_date | calendar_date |
| Yes      | numeric metric | bpapplno           | BPAPPLNO           | number        | text          |
| Yes      | series tag     | propuse            | PROPUSE            | text          | text          |
| Yes      | series tag     | dbidesc            | DBIDESC            | text          | text          |
| Yes      | series tag     | dbi_action         | DBI_ACTION         | text          | text          |
| No       |                | dbi_actdate        | DBI_ACTDATE        | calendar_date | calendar_date |
| Yes      | series tag     | new_rehab          | NEW_REHAB          | text          | text          |
| Yes      | series tag     | source             | source             | text          | text          |
| Yes      | numeric metric | total_gsf          | TOTAL_GSF          | number        | number        |
| Yes      | numeric metric | ret                | RET                | number        | number        |
| Yes      | numeric metric | mips               | MIPS               | number        | number        |
| Yes      | numeric metric | cie                | CIE                | number        | number        |
| Yes      | numeric metric | med                | MED                | number        | number        |
| Yes      | numeric metric | pdr                | PDR                | number        | number        |
| Yes      | numeric metric | visit              | VISIT              | number        | number        |
| Yes      | numeric metric | net_gsf            | NET_GSF            | number        | number        |
| Yes      | numeric metric | cienet             | CIENET             | number        | number        |
| Yes      | numeric metric | mednet             | MEDNET             | number        | number        |
| Yes      | numeric metric | mipsnet            | MIPSNET            | number        | number        |
| Yes      | numeric metric | pdrnet             | PDRNET             | number        | number        |
| Yes      | numeric metric | retnet             | RETNET             | number        | number        |
| Yes      | numeric metric | visitnet           | VISITNET           | number        | number        |
| No       |                | filedate           | FILEDATE           | calendar_date | calendar_date |
| Yes      | series tag     | landuse            | LANDUSE            | text          | text          |
| No       |                | standardaddress    | StandardAddress    | text          | text          |
| Yes      | series tag     | alias              | alias              | text          | text          |
| Yes      | series tag     | entitlement        | Entitlement        | checkbox      | checkbox      |
| Yes      | series tag     | sort               | sort               | text          | text          |
| Yes      | series tag     | sizecat            | sizecat            | text          | text          |
| Yes      | numeric metric | affordable         | AFFORDABLE         | number        | number        |
| Yes      | numeric metric | affnet             | AFFNET             | number        | number        |
| Yes      | series tag     | zoning_gen         | zoning_gen         | text          | text          |
| Yes      | series tag     | zoning_sim         | ZONING_SIM         | text          | text          |
| Yes      | series tag     | zoningdistrictname | ZONINGDISTRICTNAME | text          | text          |
| Yes      | series tag     | heightlimit        | HEIGHTLIMIT        | text          | text          |
| Yes      | series tag     | sponsor            | SPONSOR            | text          | text          |
| Yes      | series tag     | contact            | CONTACT            | text          | text          |
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = pln_reviewdate,dbi_actdate,filedate,standardaddress
```

## Data Commands

```ls
series e:858q-nwrm d:2010-08-03T00:00:00.000Z t:blklot=4886008 t:sort="PL Approved" t:sizecat="Above 250" t:alias="Bayview Waterfront" t:descript="Redevelopment plans, rezoning, projects, and infrastructure for 778-acre site encompassing BVHP Areas B, C, and Shipyard, for Candlestick Point, Hunters Point Shipyard, and India Basin Shoreline, including an estimated 9,000-du, 650,000-sf retail, 2,000," t:entitlementstatus=true t:neighborhood=Bayview t:zoning_sim=P t:pln_review=Approved t:sponsor="SF Redevelopment Agency" t:zoning_gen=Public t:heightlimit=40-X t:contact="Nicole Franklin" t:caseno=2007.0946 t:source="CASE TRACKING" t:nameaddr="HUNTERS POINT EXPY" t:zoningdistrictname=PUBLIC t:landuse=Mixres t:entitlement=true t:beststat="PL APPROVED" m:med=0 m:ret=750000 m:cienet=0 m:mednet=0 m:pdr=393750 m:visit=210000 m:cie=0 m:mipsnet=2756250 m:affordable=3345 m:unitsnet=10237 m:units=10500 m:total_gsf=4110000 m:visitnet=210000 m:pdrnet=393750 m:affnet=3089 m:mips=2756250 m:retnet=750000 m:net_gsf=4110000

series e:858q-nwrm d:2011-05-25T00:00:00.000Z t:blklot=7303001 t:sort="PL Approved" t:sizecat="Above 250" t:alias=Parkmerced t:descript="Master redevelopment program for 116-ac Parkmerced site, proposed to retain existing midrise bldgs and demo/replace all others w/ 4-14-story residential bldgs, on-site relocation of existing residents @ current rent-controlled rates, concurrent infrastru" t:neighborhood=Lakeshore t:entitlementstatus=true t:zoning_sim=PM-OS t:sponsor="Seth Mallen" t:zoning_gen=Residential t:heightlimit=40-OS-PM t:new_rehab=N t:contact="Barbara Sahm" t:caseno=2008.0021 t:source="CASE TRACKING" t:nameaddr=PARKMERCED t:zoningdistrictname="PARKMERCED-OPEN SPACE" t:landuse=Mixres t:entitlement=true t:beststat="PL APPROVED" m:med=0 m:ret=430060 m:cienet=0 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=80615 m:affordable=0 m:unitsnet=5677 m:units=8898 m:total_gsf=521450 m:visitnet=0 m:pdrnet=0 m:affnet=-3221 m:mips=91390 m:retnet=397768 m:net_gsf=478383

series e:858q-nwrm d:2011-03-15T00:00:00.000Z t:blklot=1939001 t:sort="PL Approved" t:sizecat="Above 250" t:alias="Treasure Island" t:entitlementstatus=true t:neighborhood="Treasure Island/YBI" t:descript="Development and Redevelopment Plan for Treasure Island and Yerba Buena Island, including land uses up to (approximately): 6,000 units residential, 500 rooms hotel, 250,000-sf retail, 300 acres park and open space, parking, reuse and historic rehabilitati" t:zoning_sim=TI-OS/TI-R/TI-MU/TI-PCI t:zoning_gen=Public t:heightlimit="See Treasure Island Zoning Map" t:caseno=2007.0903 t:source="CASE TRACKING" t:nameaddr="TREASURE ISLAND" t:zoningdistrictname="TREASURE ISLAND" t:landuse=Mixres t:entitlement=true t:beststat="PL APPROVED" m:med=0 m:ret=250000 m:cienet=0 m:mednet=0 m:pdr=0 m:visit=131000 m:cie=0 m:mipsnet=0 m:affordable=2050 m:unitsnet=7800 m:units=8619 m:total_gsf=381000 m:visitnet=131000 m:pdrnet=0 m:affnet=1800 m:mips=0 m:retnet=250000 m:net_gsf=381000
```

## Meta Commands

```ls
metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:total_gsf p:integer l:TOTAL_GSF t:dataTypeName=number

metric m:ret p:integer l:RET t:dataTypeName=number

metric m:mips p:integer l:MIPS t:dataTypeName=number

metric m:cie p:integer l:CIE t:dataTypeName=number

metric m:med p:integer l:MED t:dataTypeName=number

metric m:pdr p:integer l:PDR t:dataTypeName=number

metric m:visit p:integer l:VISIT t:dataTypeName=number

metric m:net_gsf p:integer l:NET_GSF t:dataTypeName=number

metric m:cienet p:integer l:CIENET t:dataTypeName=number

metric m:mednet p:integer l:MEDNET t:dataTypeName=number

metric m:mipsnet p:integer l:MIPSNET t:dataTypeName=number

metric m:pdrnet p:integer l:PDRNET t:dataTypeName=number

metric m:retnet p:integer l:RETNET t:dataTypeName=number

metric m:visitnet p:integer l:VISITNET t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affnet p:integer l:AFFNET t:dataTypeName=number

entity e:858q-nwrm l:"San Francisco Development Pipeline 2014 Quarter 4" t:url=https://data.sfgov.org/api/views/858q-nwrm

property e:858q-nwrm t:meta.view v:id=858q-nwrm v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2014 Quarter 4"

property e:858q-nwrm t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:858q-nwrm t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:858q-nwrm t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| neighborhood          | blklot  | nameaddr           | units | unitsnet | bestdate            | beststat     | entitlementstatus | caseno    | descript                                                                                                                                                                                                                                                       | pln_review | pln_reviewdate      | bpapplno     | propuse    | dbidesc                                                                                              | dbi_action      | dbi_actdate         | new_rehab | source          | total_gsf | ret    | mips    | cie | med | pdr    | visit  | net_gsf | cienet | mednet | mipsnet | pdrnet | retnet | visitnet | filedate            | landuse  | standardaddress    | alias              | entitlement | sort           | sizecat   | affordable | affnet | zoning_gen               | zoning_sim              | zoningdistrictname                    | heightlimit                    | sponsor                 | contact         | 
| ===================== | ======= | ================== | ===== | ======== | =================== | ============ | ================= | ========= | ============================================================================================================================================================================================================================================================== | ========== | =================== | ============ | ========== | ==================================================================================================== | =============== | =================== | ========= | =============== | ========= | ====== | ======= | === | === | ====== | ====== | ======= | ====== | ====== | ======= | ====== | ====== | ======== | =================== | ======== | ================== | ================== | =========== | ============== | ========= | ========== | ====== | ======================== | ======================= | ===================================== | ============================== | ======================= | =============== | 
| Bayview               | 4886008 | HUNTERS POINT EXPY | 10500 | 10237    | 2010-08-03T00:00:00 | PL APPROVED  | true              | 2007.0946 | Redevelopment plans, rezoning, projects, and infrastructure for 778-acre site encompassing BVHP Areas B, C, and Shipyard, for Candlestick Point, Hunters Point Shipyard, and India Basin Shoreline, including an estimated 9,000-du, 650,000-sf retail, 2,000, | Approved   | 2010-08-03T00:00:00 |              |            |                                                                                                      |                 |                     |           | CASE TRACKING   | 4110000   | 750000 | 2756250 | 0   | 0   | 393750 | 210000 | 4110000 | 0      | 0      | 2756250 | 393750 | 750000 | 210000   | 2010-01-11T00:00:00 | Mixres   | Hunters Point Expy | Bayview Waterfront | true        | PL Approved    | Above 250 | 3345       | 3089   | Public                   | P                       | PUBLIC                                | 40-X                           | SF Redevelopment Agency | Nicole Franklin | 
| Lakeshore             | 7303001 | PARKMERCED         | 8898  | 5677     | 2011-05-25T00:00:00 | PL APPROVED  | true              | 2008.0021 | Master redevelopment program for 116-ac Parkmerced site, proposed to retain existing midrise bldgs and demo/replace all others w/ 4-14-story residential bldgs, on-site relocation of existing residents @ current rent-controlled rates, concurrent infrastru |            |                     |              |            |                                                                                                      |                 |                     | N         | CASE TRACKING   | 521450    | 430060 | 91390   | 0   | 0   | 0      | 0      | 478383  | 0      | 0      | 80615   | 0      | 397768 | 0        | 2009-12-07T00:00:00 | Mixres   | 3711 19th Ave      | Parkmerced         | true        | PL Approved    | Above 250 | 0          | -3221  | Residential              | PM-OS                   | PARKMERCED-OPEN SPACE                 | 40-OS-PM                       | Seth Mallen             | Barbara Sahm    | 
| Treasure Island/YBI   | 1939001 | TREASURE ISLAND    | 8619  | 7800     | 2011-03-15T00:00:00 | PL APPROVED  | true              | 2007.0903 | Development and Redevelopment Plan for Treasure Island and Yerba Buena Island, including land uses up to (approximately): 6,000 units residential, 500 rooms hotel, 250,000-sf retail, 300 acres park and open space, parking, reuse and historic rehabilitati |            |                     |              |            |                                                                                                      |                 |                     |           | CASE TRACKING   | 381000    | 250000 | 0       | 0   | 0   | 0      | 131000 | 381000  | 0      | 0      | 0       | 0      | 250000 | 131000   | 2011-03-15T00:00:00 | Mixres   | Treasure Island    | Treasure Island    | true        | PL Approved    | Above 250 | 2050       | 1800   | Public                   | TI-OS/TI-R/TI-MU/TI-PCI | TREASURE ISLAND                       | See Treasure Island Zoning Map |                         |                 | 
| Visitacion Valley     | 6310001 | 1654 SUNNYDALE AVE | 1700  | 915      | 2010-04-28T00:00:00 | PL FILED     | false             | 2010.0305 | The project project is the Sunnydale HOPE SF Master Plan. The proposed project would demolish the existing Sunnydale public housing complexes and construct replacement housing, new market rate housing, infrastructure, open space, and community ammentitie |            |                     |              |            |                                                                                                      |                 |                     |           | CASE TRACKING   | 88700     | 88700  | 0       | 0   | 0   | 0      | 0      | 59424   | 0      | 0      | 0       | 0      | 59424  | 0        | 2010-04-28T00:00:00 | Mixres   | 1654 Sunnydale Ave | Sunnydale Hope SF  | false       | Planning Filed | Above 250 | 1700       | 915    | Residential              | RM-1                    | RESIDENTIAL- MIXED, LOW DENSITY       | 40-X                           |                         |                 | 
| Potrero Hill          | 4167004 | 1 TURNER TR        | 1600  | 994      | 2010-06-30T00:00:00 | PL FILED     | false             | 2010.0515 | Replace 606 units of public housing with 1,400-1,700 units of mixed-income, mixed-tenure housing, including 1-to1 replacement of public housing. Project will also include neighborhood serving retail, community facilities, parks and open space, and a new  |            |                     |              | APARTMENTS |                                                                                                      |                 |                     |           | PERMIT TRACKING | 30000     | 20000  | 10000   | 0   | 0   | 0      | 0      | 30000   | 0      | 0      | 10000   | 0      | 20000  | 0        | 2010-06-30T00:00:00 | Mixres   | 1 Turner Ter       | Potrero Hope SF    | false       | Planning Filed | Above 250 | 0          | 0      | Residential              | RM-2                    | RESIDENTIAL- MIXED, MODERATE DENSITY  | 40-X                           |                         |                 | 
| South of Market       | 9900048 | PIER 48            | 1500  | 1500     | 2013-04-23T00:00:00 | PL FILED     | false             | 2013.0208 | The proposed project is the development of Seawall Lot 337 and Pier 48 (i.e. Mission Rock), which will include a mixed-use development, including open space, commercial, residential, retail and parking. The project would include approximately 3,600,000 s |            | 2013-04-23T00:00:00 |              |            |                                                                                                      |                 |                     | N         | CASE TRACKING   | 1950000   | 250000 | 1700000 | 0   | 0   | 0      | 0      | 1950000 | 0      | 0      | 1700000 | 0      | 250000 | 0        | 2013-06-04T00:00:00 | Mixres   | 48 Pier            | Seawall Lot 337    | false       | Planning Filed | Above 250 | 0          | 0      | Industrial               | M-2                     | HEAVY INDUSTRIAL                      | 40-X                           | Jon Knorpp              | Jon Knorpp      | 
| South of Market       | 3746001 | 201 FOLSOM ST      | 806   | 806      | 2015-03-30T00:00:00 | CONSTRUCTION | true              | 2000.1073 | Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail pa | Approved   | 2003-11-18T00:00:00 | 201207124717 | APARTMENTS | Multiple Permits                                                                                     | ROUGH FRAME, PA | 2015-03-30T00:00:00 |           | CASE TRACKING   | 23505     | 23505  | 0       | 0   | 0   | 0      | 0      | 23505   | 0      | 0      | 0       | 0      | 23505  | 0        | 2002-07-11T00:00:00 | Resident | 201 Folsom St      | 390 Main St        | true        | Construction   | Above 250 | 0          | 0      | Mixed Use                | RC-4                    | RESIDENTIAL- COMMERCIAL, HIGH DENSITY | 400-W                          |                         |                 | 
| Lakeshore             | 7282005 | 515 JOHN MUIR DR   | 722   | 2        | 2014-10-21T00:00:00 | CONSTRUCTION | true              |           |                                                                                                                                                                                                                                                                |            |                     | 201308093997 | APARTMENTS | WORK FOR UNIT# 104 & # 106 ONLY. CHANGE OF USE. FROM ANCILLARY OFFICE USAGE TO 2 DWELLING UNIT (HIGH | OK TO COVER     | 2014-10-21T00:00:00 | R         | PERMIT TRACKING | 0         | 0      | 0       | 0   | 0   | 0      | 0      | 0       | 0      | 0      | 0       | 0      | 0      | 0        |                     | Resident | 515 John Muir Dr   |                    | true        | Construction   | 2-9       | 0          | 0      | Public                   | P                       | PUBLIC                                | OS                             |                         |                 | 
| Downtown/Civic Center | 0813007 | 1390 MARKET ST     | 676   | 230      | 2009-05-28T00:00:00 | PL APPROVED  | true              | 2005.0979 | Fox Plaza currently contains two buildings: a 29-story mixed-use building and a two-story commercial building. The proposal would demolish the existing two-story, 19,000 structure located on the NE corner of the lot and construct a new building which wo  | CEQA       | 2009-05-28T00:00:00 |              | APARTMENTS |                                                                                                      |                 |                     |           | PERMIT TRACKING | 17500     | 17500  | 0       | 0   | 0   | 0      | 0      | -1500   | 0      | 0      | -9500   | 0      | 8000   | 0        | 2005-10-19T00:00:00 | Mixres   | 1390 Market St     |                    | true        | PL Approved    | 100-249   | 0          | 0      | Commercial               | C-3-G                   | DOWNTOWN- GENERAL                     | 120-R-2                        |                         |                 | 
| Financial District    | 3737012 | 245 01ST ST        | 603   | 603      | 2014-12-23T00:00:00 | BP FILED     | false             |           |                                                                                                                                                                                                                                                                |            |                     | 201412234418 | APARTMENTS | TO ERECT 55 STORIES, 2.5 BASEMENT, 603 UNITS RESIDENTIAL, RETAIL & PARKING BUILDING. ** MAHER: COMPL |                 |                     | N         | PERMIT TRACKING | 0         | 0      | 0       | 0   | 0   | 0      | 0      | 0       | 0      | 0      | 0       | 0      | 0      | 0        |                     | Resident | 245 01ST St        |                    | false       | BP Filed       | Above 250 | 0          | 0      | High Density Residential | TB DTR                  | TRANSBAY DOWNTOWN RESIDENTIAL         | 50/85/550-TB                   |                         |                 | 
```