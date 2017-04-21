# San Francisco Development Pipeline 2015 Quarter 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-2015-quarter-2) |
| Metadata | [Link](https://data.sfgov.org/api/views/w3e8-bxrm) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/w3e8-bxrm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/w3e8-bxrm/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | w3e8-bxrm |
| Name | San Francisco Development Pipeline 2015 Quarter 2 |
| Category | Housing and Buildings |
| Tags | development, housing, residential, commercial |
| Created | 2015-08-25T00:40:56Z |
| Publication Date | 2015-08-28T19:25:50Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | apn               | APN               | text          | text          |
| Yes      | series tag     | nameaddr          | NAMEADDR          | text          | text          |
| Yes      | series tag     | beststat          | BESTSTAT          | text          | text          |
| Yes      | time           | bestdate          | BESTDATE          | calendar_date | calendar_date |
| Yes      | series tag     | caseno            | CASENO            | text          | text          |
| Yes      | numeric metric | bpapplno          | BPAPPLNO          | number        | text          |
| Yes      | series tag     | propuse           | PROPUSE           | text          | text          |
| Yes      | series tag     | new_rehab         | NEW_REHAB         | text          | text          |
| Yes      | series tag     | alias             | Alias             | text          | text          |
| Yes      | series tag     | landuse           | LANDUSE           | text          | text          |
| Yes      | series tag     | descript          | DESCRIPT          | text          | text          |
| Yes      | series tag     | dbidesc           | DBIDESC           | text          | text          |
| Yes      | numeric metric | units             | UNITS             | number        | number        |
| Yes      | numeric metric | unitsnet          | UNITSNET          | number        | number        |
| Yes      | numeric metric | affordable        | AFFORDABLE        | number        | number        |
| Yes      | numeric metric | affordablenet     | AFFORDABLENET     | number        | number        |
| Yes      | series tag     | entitlementstatus | EntitlementStatus | text          | number        |
| Yes      | numeric metric | parking           | PARKING           | number        | number        |
| Yes      | numeric metric | parkingnet        | PARKINGNET        | number        | number        |
| Yes      | numeric metric | total_gsf         | TOTAL_GSF         | number        | number        |
| Yes      | numeric metric | net_gsf           | NET_GSF           | number        | number        |
| Yes      | numeric metric | cie               | CIE               | number        | number        |
| Yes      | numeric metric | cienet            | CIENET            | number        | number        |
| Yes      | numeric metric | med               | MED               | number        | number        |
| Yes      | numeric metric | mednet            | MEDNET            | number        | number        |
| Yes      | numeric metric | mips              | MIPS              | number        | number        |
| Yes      | numeric metric | mipsnet           | MIPSNET           | number        | number        |
| Yes      | numeric metric | pdr               | PDR               | number        | number        |
| Yes      | numeric metric | pdrnet            | PDRNET            | number        | number        |
| Yes      | numeric metric | ret               | RET               | number        | number        |
| Yes      | numeric metric | retnet            | RETNET            | number        | number        |
| Yes      | numeric metric | visit             | VISIT             | number        | number        |
| Yes      | numeric metric | visitnet          | VISITNET          | number        | number        |
| No       |                | filedate          | FILEDATE          | calendar_date | calendar_date |
| Yes      | series tag     | planner           | PLANNER           | text          | text          |
| Yes      | series tag     | sponsor           | SPONSOR           | text          | text          |
| Yes      | series tag     | contact           | CONTACT           | text          | text          |
| Yes      | series tag     | contactph         | CONTACTPH         | text          | text          |
| Yes      | series tag     | decision          | DECISION          | text          | text          |
| No       |                | decdate           | DECDATE           | calendar_date | calendar_date |
| Yes      | series tag     | action            | ACTION            | text          | text          |
| No       |                | actdate           | ACTDATE           | calendar_date | calendar_date |
| Yes      | series tag     | source            | SOURCE            | text          | text          |
| Yes      | series tag     | dname             | SupeDistrict      | text          | text          |
| Yes      | series tag     | planarea          | PLANAREA          | text          | text          |
| Yes      | series tag     | plndistrict       | PLNDISTRICT       | text          | text          |
| Yes      | series tag     | neighborhood      | NEIGHBORHOOD      | text          | text          |
| Yes      | series tag     | zoning_sim        | ZONING_SIM        | text          | text          |
| Yes      | series tag     | districtname      | DISTRICTNAME      | text          | text          |
| Yes      | series tag     | height_lim        | HEIGHT_LIMIT      | text          | text          |
| No       |                | x                 | X                 | number        | number        |
| No       |                | y                 | Y                 | number        | number        |
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = filedate,decdate,actdate,x,y
```

## Data Commands

```ls
series e:w3e8-bxrm d:2015-05-15T00:00:00.000Z t:alias=5M t:districtname="DOWNTOWN SUPPORT" t:dname=D6 t:entitlementstatus=0 t:neighborhood="South of Market" t:zoning_sim=C-3-S t:planarea="Central SoMa; Downtown" t:caseno=2011.0409 t:plndistrict=Downtown t:source="CASE TRACKING" t:nameaddr="925 MISSION ST" t:height_lim=160-F t:planner=KGUY t:landuse=Mixres t:apn="APN 3725093" t:dbidesc="Project review for a development .  A mix of residential, office, retail and other uses on the approx. 4 acre site on the SE corner of 5th/ Mission and extending towards sixth street & south to Howard Street,  The site is comprised of 23 parcels." t:beststat="PL FILED" m:ret=7100 m:med=0 m:cienet=-23600 m:parking=0 m:mednet=0 m:visit=0 m:pdr=0 m:cie=17300 m:mipsnet=591300 m:affordable=58 m:unitsnet=688 m:units=688 m:total_gsf=617900 m:visitnet=0 m:pdrnet=0 m:mips=593500 m:retnet=7100 m:affordablenet=58 m:parkingnet=0 m:net_gsf=574800

series e:w3e8-bxrm d:2015-07-23T00:00:00.000Z t:alias=Lumina t:districtname="RESIDENTIAL- COMMERCIAL, HIGH DENSITY" t:dname=D6 t:entitlementstatus=-1 t:neighborhood="South of Market" t:descript="Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail pa" t:zoning_sim=RC-4 t:planarea="Rincon Hill" t:decision=Approved t:caseno=2000.1073 t:plndistrict="South of Market" t:source=manual t:action="ROUGH FRAME, PA" t:height_lim=400-W t:nameaddr="201 FOLSOM ST" t:planner=MSNYDER t:landuse=Mixres t:apn="APN 3746003" t:dbidesc="Multiple Permits" t:beststat=CONSTRUCTION m:med=0 m:ret=23505 m:cienet=0 m:parking=1085 m:mednet=0 m:visit=0 m:pdr=0 m:bpapplno=201207124717 m:cie=0 m:mipsnet=0 m:affordable=0 m:units=669 m:unitsnet=669 m:total_gsf=23505 m:visitnet=0 m:pdrnet=0 m:mips=0 m:retnet=23505 m:affordablenet=0 m:parkingnet=1085 m:net_gsf=23505

series e:w3e8-bxrm d:2014-12-23T00:00:00.000Z t:districtname="TRANSBAY DOWNTOWN RESIDENTIAL" t:dname=D6 t:entitlementstatus=0 t:neighborhood="Financial District" t:zoning_sim="TB DTR" t:propuse=APARTMENTS t:planarea="Transbay; Transit Center District" t:new_rehab=N t:plndistrict="South of Market" t:source="PERMIT TRACKING" t:height_lim=50/85/550-TB t:nameaddr="245 01ST ST" t:landuse=Resident t:apn="APN 3737012" t:dbidesc="TO ERECT 55 STORIES, 2.5 BASEMENT, 603 UNITS RESIDENTIAL, RETAIL & PARKING BUILDING.
** MAHER: COMPL" t:beststat="BP FILED" m:med=0 m:ret=0 m:cienet=0 m:parking=0 m:mednet=0 m:visit=0 m:pdr=0 m:bpapplno=201412234418 m:cie=0 m:mipsnet=0 m:affordable=0 m:units=603 m:unitsnet=603 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:mips=0 m:retnet=0 m:affordablenet=0 m:parkingnet=0 m:net_gsf=0
```

## Meta Commands

```ls
metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordablenet p:integer l:AFFORDABLENET t:dataTypeName=number

metric m:parking p:integer l:PARKING t:dataTypeName=number

metric m:parkingnet p:integer l:PARKINGNET t:dataTypeName=number

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

entity e:w3e8-bxrm l:"San Francisco Development Pipeline 2015 Quarter 2" t:url=https://data.sfgov.org/api/views/w3e8-bxrm

property e:w3e8-bxrm t:meta.view v:id=w3e8-bxrm v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2015 Quarter 2"

property e:w3e8-bxrm t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:w3e8-bxrm t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:w3e8-bxrm t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| apn         | nameaddr             | beststat     | bestdate            | caseno         | bpapplno     | propuse    | new_rehab | alias       | landuse  | descript                                                                                                                                                                                                                                                       | dbidesc                                                                                                                                                                                                                                              | units | unitsnet | affordable | affordablenet | entitlementstatus | parking | parkingnet | total_gsf | net_gsf | cie   | cienet | med | mednet | mips   | mipsnet | pdr | pdrnet | ret   | retnet | visit | visitnet | filedate            | planner  | sponsor                          | contact              | contactph    | decision | decdate              | action          | actdate              | source          | dname | planarea                           | plndistrict     | neighborhood       | zoning_sim | districtname                          | height_lim    | x                | y              | 
| =========== | ==================== | ============ | =================== | ============== | ============ | ========== | ========= | =========== | ======== | ============================================================================================================================================================================================================================================================== | ==================================================================================================================================================================================================================================================== | ===== | ======== | ========== | ============= | ================= | ======= | ========== | ========= | ======= | ===== | ====== | === | ====== | ====== | ======= | === | ====== | ===== | ====== | ===== | ======== | =================== | ======== | ================================ | ==================== | ============ | ======== | ==================== | =============== | ==================== | =============== | ===== | ================================== | =============== | ================== | ========== | ===================================== | ============= | ================ | ============== | 
| APN 3725093 | 925 MISSION ST       | PL FILED     | 2015-05-15T00:00:00 | 2011.0409      |              |            |           | 5M          | Mixres   |                                                                                                                                                                                                                                                                | Project review for a development . A mix of residential, office, retail and other uses on the approx. 4 acre site on the SE corner of 5th/ Mission and extending towards sixth street & south to Howard Street, The site is comprised of 23 parcels. | 688   | 688      | 58         | 58            | 0                 | 0       | 0          | 617900    | 574800  | 17300 | -23600 | 0   | 0      | 593500 | 591300  | 0   | 0      | 7100  | 7100   | 0     | 0        | 2011-07-27T00:00:00 | KGUY     |                                  |                      |              |          |                      |                 |                      | CASE TRACKING   | D6    | Central SoMa; Downtown             | Downtown        | South of Market    | C-3-S      | DOWNTOWN SUPPORT                      | 160-F         | -122.40660110900 | 37.78215365440 | 
| APN 3746003 | 201 FOLSOM ST        | CONSTRUCTION | 2015-07-23T00:00:00 | 2000.1073      | 201207124717 |            |           | Lumina      | Mixres   | Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail pa | Multiple Permits                                                                                                                                                                                                                                     | 669   | 669      | 0          | 0             | -1                | 1085    | 1085       | 23505     | 23505   | 0     | 0      | 0   | 0      | 0      | 0       | 0   | 0      | 23505 | 23505  | 0     | 0        | 2002-07-11T00:00:00 | MSNYDER  |                                  |                      |              | Approved | 37943-01-01T00:00:00 | ROUGH FRAME, PA | 42208-01-01T00:00:00 | manual          | D6    | Rincon Hill                        | South of Market | South of Market    | RC-4       | RESIDENTIAL- COMMERCIAL, HIGH DENSITY | 400-W         | -122.39185135300 | 37.78868201650 | 
| APN 3737012 | 245 01ST ST          | BP FILED     | 2014-12-23T00:00:00 |                | 201412234418 | APARTMENTS | N         |             | Resident |                                                                                                                                                                                                                                                                | TO ERECT 55 STORIES, 2.5 BASEMENT, 603 UNITS RESIDENTIAL, RETAIL & PARKING BUILDING. ** MAHER: COMPL                                                                                                                                                 | 603   | 603      | 0          | 0             | 0                 | 0       | 0          | 0         | 0       | 0     | 0      | 0   | 0      | 0      | 0       | 0   | 0      | 0     | 0      | 0     | 0        |                     |          |                                  |                      |              |          |                      |                 |                      | PERMIT TRACKING | D6    | Transbay; Transit Center District  | South of Market | Financial District | TB DTR     | TRANSBAY DOWNTOWN RESIDENTIAL         | 50/85/550-TB  | -122.39459403800 | 37.78790011200 | 
| APN 3911001 | 1 HENRY ADAMS ST     | CONSTRUCTION | 2015-04-21T00:00:00 | 2012.0701      | 201306250394 | APARTMENTS |           |             | Resident | Demolish an existing building (Concourse Exhibit Hall) containing 125,000 square feet of space and 280 surface parking spaces and construct new buildings extending up to 70 feet in height and containing 560 dwellings, 438 off-street parking space, and 8, | Multiple Permits                                                                                                                                                                                                                                     | 560   | 560      | 0          | 0             | -1                | 341     | 0          | 0         | 15000   | 0     | 0      | 0   | 0      | 0      | 0       | 0   | 0      | 0     | 15000  | 0     | 0        | 2012-05-31T00:00:00 | DSIDER   | Robert Meyers                    | Robert Meyers        | 415-788-2777 | Approved | 41242-01-01T00:00:00 | REINFORCING STE | 42115-01-01T00:00:00 | CASE TRACKING   | D10   | Showplace Square/Potrero Hill (EN) | South of Market | South of Market    | UMU        | URBAN MIXED USE                       | 68-X          | -122.40347298500 | 37.76920143220 | 
| APN 3506007 | 1500-1580 MISSION ST | PL FILED     | 2014-12-18T00:00:00 | 2014-000362PRJ |              |            |           | GOODWILL    | Mixres   | The proposed project would demolish two buildings, except for a portion of Mission Street frontage and clock tower of the 1500 Mission Street building and construct a mixed-use project. The mixed-use building would include ground-floor retail, residentia |                                                                                                                                                                                                                                                      | 550   | 550      | 110        | 110           | 0                 | 423     | 308        | 513000    | 426018  | 0     | 0      | 0   | 0      | 462000 | 447009  | 0   | -5700  | 51000 | 36009  | 0     | 0        |                     | KGUY     | Related California Urban Housing |                      | 415-677-9000 | FILED    |                      |                 |                      | manual          | D6    | Market and Octavia; Downtown       | Mission         | South of Market    | C-3-G      | DOWNTOWN- GENERAL                     | 85/250-R-2    | -122.41841702400 | 37.77382218830 | 
| APN 3736120 | 500 FOLSOM ST        | BP FILED     | 2015-03-11T00:00:00 |                | 201503110506 | APARTMENTS | N         |             | Resident |                                                                                                                                                                                                                                                                | TO ERECT 42 STORIES, 6 BASEMENTS, 545 UNITS RESIDENTIAL APARTMENT BUILDING.                                                                                                                                                                          | 545   | 545      | 0          | 0             | 0                 | 0       | 0          | 0         | 0       | 0     | 0      | 0   | 0      | 0      | 0       | 0   | 0      | 0     | 0      | 0     | 0        |                     |          |                                  |                      |              |          |                      |                 |                      | PERMIT TRACKING | D6    | Transbay; Transit Center District  | South of Market | Financial District | TB DTR     | TRANSBAY DOWNTOWN RESIDENTIAL         | 50/165/400-TB | -122.39510677000 | 37.78720355540 | 
| APN 3833001 | 1000 16TH ST         | CONSTRUCTION | 2012-09-07T00:00:00 | 2003.0527      | 201112070227 |            |           | Potrero1010 | Mixres   | The proposed project involves the construction of three building residential complex including 450 dwelling units, 26,500gsf of ground-floor retail space and 503 off-street parking spaces. The project would include a partial street vacation to narrow th  |                                                                                                                                                                                                                                                      | 470   | 470      | 94         | 94            | -1                | 0       | 0          | 26500     | 26500   | 0     | 0      | 0   | 0      | 0      | 0       | 0   | 0      | 26500 | 26500  | 0     | 0        | 2006-02-23T00:00:00 | KDURANDE | Andy Stewart                     | Daniel Murphy        | (650)359-535 | APPR/WC  | 40752-01-01T00:00:00 | ISSUED          | 41159-01-01T00:00:00 | BLDG PERMIT     | D10   | Showplace Square/Potrero Hill (EN) | South of Market | South of Market    | UMU        | URBAN MIXED USE                       | 68-X          | -122.39659516800 | 37.76710834060 | 
| APN 4105009 | 800 INDIANA STREET   | PL FILED     | 2013-10-10T00:00:00 | 2011.1374      |              |            | N         |             | Resident | The proposed project is the demolition of the existing Opera Warehouse and construction of a new 340-unit multi-family units and 294 parking spaces. The project would be constructed in six building with a semi subterraen parking garage.                   |                                                                                                                                                                                                                                                      | 340   | 340      | 0          | 0             | 0                 | 289     | 289        | 0         | -78240  | 0     | 0      | 0   | 0      | 0      | 0       | 0   | -78240 | 0     | 0      | 0     | 0        | 2013-10-10T00:00:00 | RSUCRE   | Lou Vasquez                      | Joe Kirchofer        | 415-284-9080 |          | 40940-01-01T00:00:00 |                 |                      | CASE TRACKING   | D10   | Central Waterfront (EN)            | South of Market | Potrero Hill       | UMU        | URBAN MIXED USE                       | 58-X          | -122.39172904700 | 37.75919640330 | 
| APN 3747320 | 399 FREMONT ST       | CONSTRUCTION | 2015-07-20T00:00:00 | 2002.0449      | 200605161774 |            |           |             | Mixres   | The proposal is to demolish the existing structure and construct a new structure that would include a 400-foot tower, 450 dwelling units, and 450 off-street parking spaces.                                                                                   | ERECT 41 STORIES 432 DWELLING RESIDENTIAL/PARKING BLDG.                                                                                                                                                                                              | 452   | 452      | 0          | 0             | -1                | 359     | 359        | 33000     | -2256   | 0     | 0      | 0   | 0      | 24500  | 24500   | 0   | -35256 | 8500  | 8500   | 0     | 0        | 2006-04-18T00:00:00 | MSNYDER  | Katie Haley                      | Lucian Robert Blazej | 415.695.1111 | Approved | 38792-01-01T00:00:00 | ROUGH FRAME, PA | 42205-01-01T00:00:00 | CASE TRACKING   | D6    | Rincon Hill                        | South of Market | South of Market    | RH DTR     | RINCON HILL DOWNTOWN RESIDENTIAL      | 85/400-R      | -122.39222370700 | 37.78732243330 | 
| APN 0857001 | 55 Laguna Street     | CONSTRUCTION | 2015-07-30T00:00:00 | 2004.0773      | 201209059006 |            |           |             | Mixres   | Mixed-use project which would include construction of seven new buildings and the adaptive re-use of two existing buildings for 491 dwelling units, 421 off-street parking spaces, 3,500 GSF of retail use, 12,000 GSF for a dental clinic, and 12,590 GSF for |                                                                                                                                                                                                                                                      | 450   | 450      | 160        | 160           | -1                | 310     | 310        | 3500      | 28090   | 0     | 12590  | 0   | 12000  | 0      | 0       | 0   | 0      | 3500  | 3500   | 0     | 0        | 2006-10-31T00:00:00 | JKUGLER  | Ruthy Bennett                    | Ruthy Bennett        | 510-267-4679 | CEQA     | 39511-01-01T00:00:00 | SITE VERIFICATI | 42215-01-01T00:00:00 | CASE TRACKING   | D8    | Market and Octavia                 | Buena Vista     | Western Addition   | RM-3       | RESIDENTIAL- MIXED, MEDIUM DENSITY    | 40-X          | -122.42627864400 | 37.77234985560 | 
```