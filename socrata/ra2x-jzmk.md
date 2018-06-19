# San Francisco Development Pipeline 2015 Quarter 4

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-2015-quarter-4) |
| Metadata | [Link](https://data.sfgov.org/api/views/ra2x-jzmk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ra2x-jzmk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ra2x-jzmk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ra2x-jzmk |
| Name | San Francisco Development Pipeline 2015 Quarter 4 |
| Category | Housing and Buildings |
| Tags | development, housing, residential, commercial |
| Created | 2016-02-11T19:26:40Z |
| Publication Date | 2017-03-30T22:59:47Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name           | Data Type     | Render Type   |
| ======== | ============== | ============ | ============== | ============= | ============= |
| Yes      | series tag     | neighborhood | NEIGHBORHOOD   | text          | text          |
| Yes      | series tag     | apn          | APN            | text          | text          |
| Yes      | series tag     | landuse      | LANDUSE        | text          | text          |
| Yes      | series tag     | beststat     | BESTSTAT       | text          | text          |
| Yes      | time           | bestdate     | BESTDATE       | calendar_date | calendar_date |
| Yes      | series tag     | nameaddr     | NAMEADDR       | text          | text          |
| Yes      | series tag     | alias        | Alias          | text          | text          |
| Yes      | series tag     | caseno       | CASENO         | html          | html          |
| Yes      | series tag     | descript     | DESCRIPT       | text          | text          |
| Yes      | numeric metric | bpapplno     | BPAPPLNO       | number        | text          |
| Yes      | series tag     | propuse      | PROPUSE        | text          | text          |
| Yes      | series tag     | dbidesc      | DBIDESC        | text          | text          |
| Yes      | numeric metric | units        | UNITS          | number        | number        |
| Yes      | numeric metric | unitsnet     | UNITSNET       | number        | number        |
| Yes      | numeric metric | affordable   | AFFORDABLE     | number        | number        |
| Yes      | numeric metric | affordab_1   | AFFORDABLENET  | number        | number        |
| Yes      | numeric metric | total_gsf    | TOTAL_GSF      | number        | number        |
| Yes      | numeric metric | net_gsf      | NET_GSF        | number        | number        |
| Yes      | numeric metric | cie          | CIE            | number        | number        |
| Yes      | numeric metric | cienet       | CIENET         | number        | number        |
| Yes      | numeric metric | med          | MED            | number        | number        |
| Yes      | numeric metric | mednet       | MEDNET         | number        | number        |
| Yes      | numeric metric | mips         | MIPS           | number        | number        |
| Yes      | numeric metric | mipsnet      | MIPSNET        | number        | number        |
| Yes      | numeric metric | pdr          | PDR            | number        | number        |
| Yes      | numeric metric | pdrnet       | PDRNET         | number        | number        |
| Yes      | numeric metric | ret          | RET            | number        | number        |
| Yes      | numeric metric | retnet       | RETNET         | number        | number        |
| Yes      | numeric metric | visit        | VISIT          | number        | number        |
| Yes      | numeric metric | visitnet     | VISITNET       | number        | number        |
| No       |                | firstfiled   | FirstFiled     | calendar_date | calendar_date |
| Yes      | series tag     | entitled     | EntitledStatus | text          | number        |
| Yes      | series tag     | sponsor      | SPONSOR        | text          | text          |
| Yes      | series tag     | contact      | CONTACT        | text          | text          |
| Yes      | series tag     | contactph    | CONTACTPH      | text          | text          |
| Yes      | series tag     | planner      | PLANNER        | text          | text          |
| Yes      | series tag     | source       | SOURCE         | text          | text          |
| Yes      | series tag     | supdist      | SUPE_DIST      | text          | text          |
| Yes      | series tag     | district     | PLN_DISTRICT   | text          | text          |
| Yes      | series tag     | planarea     | PLN_AREA       | text          | text          |
| Yes      | series tag     | height       | HEIGHT         | text          | text          |
| Yes      | series tag     | zoning_sim   | ZONING_SIM     | text          | text          |
| Yes      | series tag     | districtname | ZONE_NAME      | text          | text          |
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = firstfiled
```

## Data Commands

```ls
series e:ra2x-jzmk d:2015-10-27T00:00:00.000Z t:entitled=-1 t:districtname=PUBLIC t:alias="HP SHIPYARD PHASE 2 (REMAINING UNITS)" t:descript="Redevelopment plans, rezoning, projects, and infrastructure for 778-acre site encompassing BVHP Areas B, C, and Shipyard, for Candlestick Point, Hunters Point Shipyard, and India Basin Shoreline, including an estimated 9,000-du, 650,000-sf retail, 2,000," t:neighborhood=Bayview t:supdist="SUPERVISORIAL DISTRICT 10" t:zoning_sim=P t:sponsor="SF Redevelopment Agency" t:planarea="Bayview Hunters Point / Candlestick Point" t:contact="Nicole Franklin" t:caseno=2007.0946 t:height=CP t:source=manual t:nameaddr="HUNTERS POINT SHIPYARD, PHASE II" t:planner=JNAVARRE t:landuse=Mixres t:apn="APN 4884025" t:district="South Bayshore" t:beststat="PL APPROVED" m:med=0 m:ret=750000 m:cienet=0 m:affordab_1=3089 m:mednet=0 m:pdr=393750 m:visit=210000 m:cie=0 m:mipsnet=2756250 m:affordable=3345 m:units=10172 m:unitsnet=9916 m:total_gsf=4110000 m:visitnet=210000 m:pdrnet=393750 m:mips=2756250 m:retnet=750000 m:net_gsf=4110000

series e:ra2x-jzmk d:2016-01-25T00:00:00.000Z t:entitled=0 t:districtname=PARKMERCED-RESIDENTIAL t:alias="PARKMERCED (REMAINING UNITS)" t:descript="Phase 1 is comprised of four development subphases: Subphase A through Subphase D. The parcels subject to Phase 1 are shown by subphase on the attached Existing Phase 1 Site Plan diagram and further described by block number and area on page 4 of this ap" t:neighborhood=Lakeshore t:supdist="SUPERVISORIAL DISTRICT 7" t:zoning_sim=PM-R t:planarea=Parkmerced t:caseno=2014.137 t:height=45-PM t:source=MOHCD t:nameaddr="PARKMERCED, PHASE I" t:landuse=Mixres t:apn="APN 7308001" t:district=Ingleside t:beststat="BP FILED" m:med=0 m:ret=0 m:cienet=0 m:affordab_1=284 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=0 m:affordable=284 m:units=4666 m:unitsnet=4666 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:mips=0 m:retnet=0 m:net_gsf=0

series e:ra2x-jzmk d:2014-07-22T00:00:00.000Z t:entitled=-1 t:districtname="MIXED USE-GENERAL" t:alias="2201 BAYSHORE BLVD" t:descript="Schlage Lock Project Tentative Subdivision Map #7182 for the development of up to 1,679 dwelling units and up to 20 commercial condominium units over 13 lots, together with parks, open spaces, pedestrian pathways and public streets." t:neighborhood="Visitacion Valley" t:supdist="SUPERVISORIAL DISTRICT 10" t:zoning_sim=MUG t:planarea="Schlage Lock" t:caseno=2014.114 t:height=57-X t:source=manual t:nameaddr="SCHLAGE LOCK" t:planner=CFLORES t:landuse=Mixres t:apn="APN 5087003" t:district="South Bayshore" t:beststat="PL APPROVED" m:med=0 m:ret=20000 m:cienet=0 m:affordab_1=168 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=18000 m:affordable=168 m:units=1679 m:unitsnet=1679 m:total_gsf=38000 m:visitnet=0 m:pdrnet=0 m:mips=18000 m:retnet=20000 m:net_gsf=38000
```

## Meta Commands

```ls
metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordab_1 p:integer l:AFFORDABLENET t:dataTypeName=number

metric m:total_gsf p:integer l:TOTAL_GSF t:dataTypeName=number

metric m:net_gsf p:integer l:NET_GSF t:dataTypeName=number

metric m:cie p:integer l:CIE t:dataTypeName=number

metric m:cienet p:integer l:CIENET t:dataTypeName=number

metric m:med p:integer l:MED t:dataTypeName=number

metric m:mednet p:integer l:MEDNET t:dataTypeName=number

metric m:mips p:integer l:MIPS t:dataTypeName=number

metric m:mipsnet p:integer l:MIPSNET t:dataTypeName=number

metric m:pdr p:integer l:PDR t:dataTypeName=number

metric m:pdrnet p:integer l:PDRNET t:dataTypeName=number

metric m:ret p:integer l:RET t:dataTypeName=number

metric m:retnet p:integer l:RETNET t:dataTypeName=number

metric m:visit p:integer l:VISIT t:dataTypeName=number

metric m:visitnet p:integer l:VISITNET t:dataTypeName=number

entity e:ra2x-jzmk l:"San Francisco Development Pipeline 2015 Quarter 4" t:url=https://data.sfgov.org/api/views/ra2x-jzmk

property e:ra2x-jzmk t:meta.view v:id=ra2x-jzmk v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2015 Quarter 4"

property e:ra2x-jzmk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ra2x-jzmk t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:ra2x-jzmk t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| neighborhood      | apn          | landuse  | beststat    | bestdate            | nameaddr                         | alias                                 | caseno         | descript                                                                                                                                                                                                                                                       | bpapplno     | propuse           | dbidesc                                        | units | unitsnet | affordable | affordab_1 | total_gsf | net_gsf | cie | cienet | med | mednet | mips    | mipsnet | pdr    | pdrnet | ret    | retnet | visit  | visitnet | firstfiled          | entitled | sponsor                 | contact                            | contactph | planner  | source          | supdist                   | district        | planarea                                             | height      | zoning_sim | districtname                         | 
| ================= | ============ | ======== | =========== | =================== | ================================ | ===================================== | ============== | ============================================================================================================================================================================================================================================================== | ============ | ================= | ============================================== | ===== | ======== | ========== | ========== | ========= | ======= | === | ====== | === | ====== | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ======== | =================== | ======== | ======================= | ================================== | ========= | ======== | =============== | ========================= | =============== | ==================================================== | =========== | ========== | ==================================== | 
| Bayview           | APN 4884025  | Mixres   | PL APPROVED | 2015-10-27T00:00:00 | HUNTERS POINT SHIPYARD, PHASE II | HP SHIPYARD PHASE 2 (REMAINING UNITS) | 2007.0946      | Redevelopment plans, rezoning, projects, and infrastructure for 778-acre site encompassing BVHP Areas B, C, and Shipyard, for Candlestick Point, Hunters Point Shipyard, and India Basin Shoreline, including an estimated 9,000-du, 650,000-sf retail, 2,000, |              |                   |                                                | 10172 | 9916     | 3345       | 3089       | 4110000   | 4110000 | 0   | 0      | 0   | 0      | 2756250 | 2756250 | 393750 | 393750 | 750000 | 750000 | 210000 | 210000   | 2010-01-11T00:00:00 | -1       | SF Redevelopment Agency | Nicole Franklin                    |           | JNAVARRE | manual          | SUPERVISORIAL DISTRICT 10 | South Bayshore  | Bayview Hunters Point / Candlestick Point            | CP          | P          | PUBLIC                               | 
| Lakeshore         | APN 7308001  | Mixres   | BP FILED    | 2016-01-25T00:00:00 | PARKMERCED, PHASE I              | PARKMERCED (REMAINING UNITS)          | 2014.137       | Phase 1 is comprised of four development subphases: Subphase A through Subphase D. The parcels subject to Phase 1 are shown by subphase on the attached Existing Phase 1 Site Plan diagram and further described by block number and area on page 4 of this ap |              |                   |                                                | 4666  | 4666     | 284        | 284        | 0         | 0       | 0   | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 0      | 0      | 0      | 0        | 2014-09-08T00:00:00 | 0        |                         |                                    |           |          | MOHCD           | SUPERVISORIAL DISTRICT 7  | Ingleside       | Parkmerced                                           | 45-PM       | PM-R       | PARKMERCED-RESIDENTIAL               | 
| Visitacion Valley | APN 5087003  | Mixres   | PL APPROVED | 2014-07-22T00:00:00 | SCHLAGE LOCK                     | 2201 BAYSHORE BLVD                    | 2014.114       | Schlage Lock Project Tentative Subdivision Map #7182 for the development of up to 1,679 dwelling units and up to 20 commercial condominium units over 13 lots, together with parks, open spaces, pedestrian pathways and public streets.                       |              |                   |                                                | 1679  | 1679     | 168        | 168        | 38000     | 38000   | 0   | 0      | 0   | 0      | 18000   | 18000   | 0      | 0      | 20000  | 20000  | 0      | 0        | 2014-07-22T00:00:00 | -1       |                         |                                    |           | CFLORES  | manual          | SUPERVISORIAL DISTRICT 10 | South Bayshore  | Schlage Lock                                         | 57-X        | MUG        | MIXED USE-GENERAL                    | 
| South of Market   | APN 9900048  | Mixres   | PL FILED    | 2013-04-23T00:00:00 | PIER 48 / SEAWALL LOT 337        | MISSION ROCK                          | 2013.0208      | The proposed project is the development of Seawall Lot 337 and Pier 48 (i.e. Mission Rock), which will include a mixed-use development, including open space, commercial, residential, retail and parking. The project would include approximately 3,600,000 s |              |                   |                                                | 1500  | 1500     | 0          | 0          | 1950000   | 1950000 | 0   | 0      | 0   | 0      | 1700000 | 1700000 | 0      | 0      | 250000 | 250000 | 0      | 0        | 2013-06-04T00:00:00 | 0        | Jon Knorpp              | Jon Knorpp                         | 972-1760  | TSHEYNER | CASE TRACKING   | SUPERVISORIAL DISTRICT 6  | South of Market |                                                      | 40-X        | M-2        | HEAVY INDUSTRIAL                     | 
| Potrero Hill      | APN 4110001  | Mixres   | PL FILED    | 2015-02-10T00:00:00 | PIER 70                          | WATERFRONT SITE                       | 2014-001272PRJ | The proposed project would involve development of a 28-acre site into a mixed-use development, including parks, roads, and infrastructure. Below is a breakdown of the use types of the pier 70-waterfront site development. Residential ? Development of      |              |                   |                                                | 1100  | 1100     | 0          | 0          | 2492050   | 2492050 | 0   | 0      | 0   | 0      | 2024050 | 2024050 | 468000 | 468000 | 0      | 0      | 0      | 0        | 2014-11-10T00:00:00 | 0        |                         | Forest City Development California | 415)(     | ACONTRER | CASE TRACKING   | SUPERVISORIAL DISTRICT 10 | South of Market | Central Waterfront (EN)                              | 65-X        | M-2        | HEAVY INDUSTRIAL                     | 
| Potrero Hill      | APN 4167004  | Mixres   | PL FILED    | 2010-06-30T00:00:00 | HOPE SF POTRERO                  | 1101 CONNECTICUT ST                   | 2010.0515      | Replace 606 units of public housing with 1,400-1,700 units of mixed-income, mixed-tenure housing, including 1-to1 replacement of public housing. Project will also include neighborhood serving retail, community facilities, parks and open space, and a new  |              | APARTMENTS        |                                                | 1600  | 994      | 0          | 0          | 30000     | 30000   | 0   | 0      | 0   | 0      | 10000   | 10000   | 0      | 0      | 20000  | 20000  | 0      | 0        | 2010-06-30T00:00:00 | 0        |                         |                                    |           | MSNYDER  | PERMIT TRACKING | SUPERVISORIAL DISTRICT 10 | South of Market | Showplace Square/Potrero Hill (EN)                   | 40-X        | RM-2       | RESIDENTIAL- MIXED, MODERATE DENSITY | 
| Bayview           | APN 4644002A | Mixres   | PL FILED    | 2014-12-09T00:00:00 | 700 INNES ST                     | INDIA BASIN                           | 2014-002541PRJ | The Project proposes a multi phased development with 15.9 acres of publicly accessible parks, plazas and open space, 4.02 acres of publicly accessible sreets, sidewalks, stairs & bike lanes and a total of 1,472,150 sf of development building area (reside |              |                   |                                                | 980   | 980      | 0          | 0          | 46400     | 46400   | 0   | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 46400  | 46400  | 0      | 0        | 2014-12-09T00:00:00 | 0        |                         |                                    |           |          | CASE TRACKING   | SUPERVISORIAL DISTRICT 10 | South Bayshore  | India Basin Shoreline/Area C / Bayview Hunters Point | 40-X        | NC-2       | NEIGHBORHOOD COMMERCIAL, SMALL SCALE | 
| Visitacion Valley | APN 6310001  | Mixres   | PL FILED    | 2010-04-28T00:00:00 | HOPE SF SUNNYDALE                | 1500 SUNNYDALE AV                     | 2010.0305      | The project project is the Sunnydale HOPE SF Master Plan. The proposed project would demolish the existing Sunnydale public housing complexes and construct replacement housing, new market rate housing, infrastructure, open space, and community ammentitie |              |                   |                                                | 1700  | 915      | 1700       | 915        | 88700     | 59424   | 0   | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 88700  | 59424  | 0      | 0        | 2010-04-28T00:00:00 | 0        |                         |                                    |           | MSNYDER  | manual          | SUPERVISORIAL DISTRICT 10 | South Central   |                                                      | 40-X        | RM-1       | RESIDENTIAL- MIXED, LOW DENSITY      | 
| Noe Valley        | APN 7518081  | Resident | BP FILED    | 2015-03-02T00:00:00 | 868 DUNCAN ST                    |                                       |                |                                                                                                                                                                                                                                                                | 201503029743 | 2 FAMILY DWELLING | LEGALIZE 1ST FLOOR UNIT AS PER ORDINACE 43-14. | 2     | 1        | 0          | 0          | 0         | 0       | 0   | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 0      | 0      | 0      | 0        | 2015-03-02T00:00:00 | 0        |                         |                                    |           |          | PERMIT TRACKING | SUPERVISORIAL DISTRICT 8  | Central         |                                                      | 40-X        | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY       | 
| South of Market   | APN 3506004  | Mixres   | PL FILED    | 2015-04-14T00:00:00 | 10 SOUTH VAN NESS AV             |                                       | 2015-004568PRJ | New high-rise, mixed-use construction consisting of studio, 1-bedroom, 2-bedroom and 3-bedroom residential units, associated amenity spaces, and retail spaces at the ground floor. Proposed project entails two 400' towers over a 120' podium building, wit  |              |                   |                                                | 767   | 767      | 0          | 0          | 20400     | -30400  | 0   | 0      | 0   | 0      | 0       | 0       | 0      | -50800 | 20400  | 20400  | 0      | 0        | 2015-04-14T00:00:00 | 0        |                         |                                    |           |          | CASE TRACKING   | SUPERVISORIAL DISTRICT 6  | Mission         | Market and Octavia / Downtown                        | 120/400-R-2 | C-3-G      | DOWNTOWN- GENERAL                    | 
```