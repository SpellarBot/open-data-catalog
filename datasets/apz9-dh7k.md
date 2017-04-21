# San Francisco Development Pipeline 2015 Quarter 3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-2015-quarter-3) |
| Metadata | [Link](https://data.sfgov.org/api/views/apz9-dh7k) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/apz9-dh7k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/apz9-dh7k/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | apz9-dh7k |
| Name | San Francisco Development Pipeline 2015 Quarter 3 |
| Category | Housing and Buildings |
| Tags | development, housing, residential, commercial |
| Created | 2015-11-14T00:19:38Z |
| Publication Date | 2017-03-30T23:01:35Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name              | Data Type     | Render Type   |
| ======== | ============== | ============= | ================= | ============= | ============= |
| Yes      | series tag     | nameaddr      | NAMEADDR          | text          | text          |
| Yes      | series tag     | beststat      | BESTSTAT          | text          | text          |
| Yes      | time           | bestdate      | BESTDATE          | calendar_date | calendar_date |
| Yes      | series tag     | alias         | Alias             | text          | text          |
| Yes      | series tag     | caseno        | CASENO            | text          | text          |
| Yes      | numeric metric | bpapplno      | BPAPPLNO          | number        | number        |
| Yes      | series tag     | plndesc       | PLNDESC           | text          | text          |
| Yes      | series tag     | dbidesc       | DBIDESC           | text          | text          |
| Yes      | series tag     | propuse       | PROPUSE           | text          | text          |
| Yes      | numeric metric | units         | UNITS             | number        | number        |
| Yes      | numeric metric | unitsnet      | UNITSNET          | number        | number        |
| Yes      | numeric metric | affordable    | AFFORDABLE        | number        | number        |
| Yes      | numeric metric | affordablenet | AFFORDABLENET     | number        | number        |
| Yes      | series tag     | aff_dec       | AFFORDABLE_DEC    | text          | text          |
| Yes      | numeric metric | total_gsf     | TOTAL_GSF         | number        | number        |
| Yes      | numeric metric | net_gsf       | NET_GSF           | number        | number        |
| Yes      | numeric metric | cie           | CIE               | number        | number        |
| Yes      | numeric metric | cienet        | CIENET            | number        | number        |
| Yes      | numeric metric | med           | MED               | number        | number        |
| Yes      | numeric metric | mednet        | MEDNET            | number        | number        |
| Yes      | numeric metric | mips          | MIPS              | number        | number        |
| Yes      | numeric metric | mipsnet       | MIPSNET           | number        | number        |
| Yes      | numeric metric | pdr           | PDR               | number        | number        |
| Yes      | numeric metric | pdrnet        | PDRNET            | number        | number        |
| Yes      | numeric metric | ret           | RET               | number        | number        |
| Yes      | numeric metric | retnet        | RETNET            | number        | number        |
| Yes      | numeric metric | visit         | VISIT             | number        | number        |
| Yes      | numeric metric | visitnet      | VISITNET          | number        | number        |
| Yes      | series tag     | landuse       | LANDUSE           | text          | text          |
| Yes      | series tag     | entitled      | EntitlementStatus | text          | number        |
| No       |                | firstfiled    | FirstFiled        | calendar_date | calendar_date |
| Yes      | series tag     | sponsor       | SPONSOR           | text          | text          |
| Yes      | series tag     | contact       | CONTACTNAME       | text          | text          |
| Yes      | series tag     | contactph     | CONTACTPHONE      | text          | text          |
| Yes      | series tag     | source        | SOURCE            | text          | text          |
| Yes      | series tag     | planner       | PLANNER           | text          | text          |
| Yes      | series tag     | apn           | APN               | text          | text          |
| Yes      | series tag     | planarea      | PLANAREA          | text          | text          |
| Yes      | series tag     | centralsoma   | CentralSoMa       | text          | text          |
| Yes      | series tag     | plandistrict  | PLANDISTRICT      | text          | text          |
| Yes      | series tag     | neighborhood  | NEIGHBORHOOD      | text          | text          |
| Yes      | series tag     | zoning_sim    | ZONING_SIM        | text          | text          |
| Yes      | series tag     | zonename      | ZONENAME          | text          | text          |
| Yes      | series tag     | height        | HEIGHT            | text          | text          |
| Yes      | series tag     | supedist      | SUPEDIST          | text          | text          |
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
series e:apz9-dh7k d:2014-12-09T00:00:00.000Z t:entitled=0 t:alias="INDIA BASIN" t:neighborhood=Bayview t:zoning_sim=NC-2 t:supedist="SUPERVISORIAL DISTRICT 10" t:planarea="India Basin Shoreline/Area C; Bayview Hunters Point" t:plandistrict="South Bayshore" t:caseno=2014-002541PRJ t:plndesc="The Project proposes a multi phased development with 15.9 acres of publicly accessible parks, plazas and open space, 4.02 acres of publicly accessible sreets, sidewalks, stairs & bike lanes and a total of 1,472,150 sf of development building area (reside" t:height=40-X t:source="CASE TRACKING" t:nameaddr="700 INNES ST" t:landuse=Mixres t:apn="APN 4644002A" t:zonename="NEIGHBORHOOD COMMERCIAL, SMALL SCALE" t:beststat="PL FILED" m:med=0 m:ret=46400 m:cienet=0 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=0 m:affordable=0 m:unitsnet=980 m:units=980 m:total_gsf=46400 m:visitnet=0 m:pdrnet=0 m:mips=0 m:retnet=46400 m:affordablenet=0 m:net_gsf=46400

series e:apz9-dh7k d:2010-04-28T00:00:00.000Z t:entitled=0 t:alias="HOPE SF SUNNYDALE" t:neighborhood="Visitacion Valley" t:zoning_sim=RM-1 t:supedist="SUPERVISORIAL DISTRICT 10" t:plandistrict="South Central" t:caseno=2010.0305 t:plndesc="The project project is the Sunnydale HOPE SF Master Plan. The proposed project would demolish the existing Sunnydale public housing complexes and construct replacement housing, new market rate housing, infrastructure, open space, and community ammentitie" t:height=40-X t:source=manual t:nameaddr="HOPE SF SUNNYDALE" t:planner=MSNYDER t:landuse=Mixres t:apn="APN 6310001" t:zonename="RESIDENTIAL- MIXED, LOW DENSITY" t:beststat="PL FILED" m:med=0 m:ret=88700 m:cienet=0 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=0 m:affordable=1700 m:unitsnet=915 m:units=1700 m:total_gsf=88700 m:visitnet=0 m:pdrnet=0 m:mips=0 m:retnet=59424 m:affordablenet=915 m:net_gsf=59424

series e:apz9-dh7k d:2015-04-14T00:00:00.000Z t:entitled=0 t:neighborhood="South of Market" t:zoning_sim=C-3-G t:supedist="SUPERVISORIAL DISTRICT 6" t:planarea="Market and Octavia; Downtown" t:plandistrict=Mission t:caseno=2015-004568PRJ t:plndesc="New high-rise, mixed-use construction consisting of studio, 1-bedroom, 2-bedroom and 3-bedroom residential units, associated amenity spaces, and retail spaces at the ground floor.  Proposed project entails two 400' towers over a 120' podium building, wit" t:height=120/400-R-2 t:source="CASE TRACKING" t:nameaddr="10 SOUTH VAN NESS AV" t:landuse=Mixres t:apn="APN 3506004" t:zonename="DOWNTOWN- GENERAL" t:beststat="PL FILED" m:med=0 m:ret=20400 m:cienet=0 m:mednet=0 m:pdr=0 m:visit=0 m:cie=0 m:mipsnet=0 m:affordable=0 m:unitsnet=767 m:units=767 m:total_gsf=20400 m:visitnet=0 m:pdrnet=-50800 m:mips=0 m:retnet=20400 m:affordablenet=0 m:net_gsf=-30400
```

## Meta Commands

```ls
metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordablenet p:integer l:AFFORDABLENET t:dataTypeName=number

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

entity e:apz9-dh7k l:"San Francisco Development Pipeline 2015 Quarter 3" t:url=https://data.sfgov.org/api/views/apz9-dh7k

property e:apz9-dh7k t:meta.view v:id=apz9-dh7k v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2015 Quarter 3"

property e:apz9-dh7k t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:apz9-dh7k t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:apz9-dh7k t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| nameaddr                           | beststat     | bestdate            | alias                        | caseno         | bpapplno     | plndesc                                                                                                                                                                                                                                                        | dbidesc                                                                                                                                                                                                                                              | propuse    | units | unitsnet | affordable | affordablenet | aff_dec | total_gsf | net_gsf | cie   | cienet | med | mednet | mips    | mipsnet | pdr    | pdrnet | ret    | retnet | visit  | visitnet | landuse  | entitled | firstfiled          | sponsor                 | contact         | contactph    | source          | planner  | apn          | planarea                                            | centralsoma | plandistrict    | neighborhood       | zoning_sim | zonename                                                | height       | supedist                  | 
| ================================== | ============ | =================== | ============================ | ============== | ============ | ============================================================================================================================================================================================================================================================== | ==================================================================================================================================================================================================================================================== | ========== | ===== | ======== | ========== | ============= | ======= | ========= | ======= | ===== | ====== | === | ====== | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | =================== | ======================= | =============== | ============ | =============== | ======== | ============ | =================================================== | =========== | =============== | ================== | ========== | ======================================================= | ============ | ========================= | 
| 700 INNES ST                       | PL FILED     | 2014-12-09T00:00:00 | INDIA BASIN                  | 2014-002541PRJ |              | The Project proposes a multi phased development with 15.9 acres of publicly accessible parks, plazas and open space, 4.02 acres of publicly accessible sreets, sidewalks, stairs & bike lanes and a total of 1,472,150 sf of development building area (reside |                                                                                                                                                                                                                                                      |            | 980   | 980      | 0          | 0             |         | 46400     | 46400   | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 46400  | 46400  | 0      | 0        | Mixres   | 0        | 2014-12-09T00:00:00 |                         |                 |              | CASE TRACKING   |          | APN 4644002A | India Basin Shoreline/Area C; Bayview Hunters Point |             | South Bayshore  | Bayview            | NC-2       | NEIGHBORHOOD COMMERCIAL, SMALL SCALE                    | 40-X         | SUPERVISORIAL DISTRICT 10 | 
| HOPE SF SUNNYDALE                  | PL FILED     | 2010-04-28T00:00:00 | HOPE SF SUNNYDALE            | 2010.0305      |              | The project project is the Sunnydale HOPE SF Master Plan. The proposed project would demolish the existing Sunnydale public housing complexes and construct replacement housing, new market rate housing, infrastructure, open space, and community ammentitie |                                                                                                                                                                                                                                                      |            | 1700  | 915      | 1700       | 915           |         | 88700     | 59424   | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 88700  | 59424  | 0      | 0        | Mixres   | 0        | 2010-04-28T00:00:00 |                         |                 |              | manual          | MSNYDER  | APN 6310001  |                                                     |             | South Central   | Visitacion Valley  | RM-1       | RESIDENTIAL- MIXED, LOW DENSITY                         | 40-X         | SUPERVISORIAL DISTRICT 10 | 
| 10 SOUTH VAN NESS AV               | PL FILED     | 2015-04-14T00:00:00 |                              | 2015-004568PRJ |              | New high-rise, mixed-use construction consisting of studio, 1-bedroom, 2-bedroom and 3-bedroom residential units, associated amenity spaces, and retail spaces at the ground floor. Proposed project entails two 400' towers over a 120' podium building, wit  |                                                                                                                                                                                                                                                      |            | 767   | 767      | 0          | 0             |         | 20400     | -30400  | 0     | 0      | 0   | 0      | 0       | 0       | 0      | -50800 | 20400  | 20400  | 0      | 0        | Mixres   | 0        | 2015-04-14T00:00:00 |                         |                 |              | CASE TRACKING   |          | APN 3506004  | Market and Octavia; Downtown                        |             | Mission         | South of Market    | C-3-G      | DOWNTOWN- GENERAL                                       | 120/400-R-2  | SUPERVISORIAL DISTRICT 6  | 
| 925 MISSION ST                     | PL FILED     | 2015-05-15T00:00:00 | 5M                           | 2011.0409      |              |                                                                                                                                                                                                                                                                | Project review for a development . A mix of residential, office, retail and other uses on the approx. 4 acre site on the SE corner of 5th/ Mission and extending towards sixth street & south to Howard Street, The site is comprised of 23 parcels. |            | 688   | 688      | 58         | 58            |         | 617900    | 574800  | 17300 | -23600 | 0   | 0      | 593500  | 591300  | 0      | 0      | 7100   | 7100   | 0      | 0        | Mixres   | 0        | 2011-07-27T00:00:00 |                         |                 |              | CASE TRACKING   | KGUY     | APN 3725093  | Central SoMa; Downtown                              | Y           | Downtown        | South of Market    | C-3-S      | DOWNTOWN SUPPORT                                        | 160-F        | SUPERVISORIAL DISTRICT 6  | 
| 201 FOLSOM ST                      | CONSTRUCTION | 2015-09-24T00:00:00 | LUMINA                       | 2000.1073      | 201207124717 | Residential & Retail uses, and parking. Remove an existing US Postal Service surface parking lot and construct a new 38-40 story building with 806 residential units, ground floor retail, 806 off-street parking spaces for the residential use, 16 retail pa | Multiple Permits                                                                                                                                                                                                                                     |            | 669   | 669      | 0          | 0             |         | 23505     | 23505   | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 23505  | 23505  | 0      | 0        | Mixres   | -1       | 2002-07-11T00:00:00 |                         |                 |              | manual          | MSNYDER  | APN 3746001  | Rincon Hill                                         |             | South of Market | South of Market    | RC-4       | RESIDENTIAL- COMMERCIAL, HIGH DENSITY                   | 400-W        | SUPERVISORIAL DISTRICT 6  | 
| 245 01ST ST                        | BP FILED     | 2014-12-23T00:00:00 |                              |                | 201412234418 |                                                                                                                                                                                                                                                                | TO ERECT 55 STORIES, 2.5 BASEMENT, 603 UNITS RESIDENTIAL, RETAIL & PARKING BUILDING. ** MAHER: COMPL                                                                                                                                                 | APARTMENTS | 603   | 603      | 0          | 0             |         | 0         | 0       | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 0      | 0      | 0      | 0        | Resident | 0        | 2014-12-23T00:00:00 |                         |                 |              | PERMIT TRACKING |          | APN 3737012  | Transbay; Transit Center District                   |             | South of Market | Financial District | TB DTR     | TRANSBAY DOWNTOWN RESIDENTIAL                           | 50/85/550-TB | SUPERVISORIAL DISTRICT 6  | 
| 1601-1637 MARKET ST / 53 COLTON ST | PL FILED     | 2015-07-10T00:00:00 | LOCAL 38 PLUMBERS UNION HALL | 2015-005848PRJ |              | The proposed project is redevelopment of site for a mixed-use, mixed-income project, including a supportive affordable housing building. New units include 107 affordable, supportive housing efficiency units. "Other" use is the Local 38 Plumbers Union hal |                                                                                                                                                                                                                                                      |            | 584   | 584      | 107        | 107           |         | 36571     | 36571   | 0     | 0      | 0   | 0      | 27296   | 27296   | 0      | 0      | 9275   | 9275   | 0      | 0        | Mixres   | 0        | 2015-07-10T00:00:00 |                         |                 |              | CASE TRACKING   |          | APN 3505001  | Market and Octavia                                  |             | Mission         | South of Market    | NCT-3      | MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT | 85-X         | SUPERVISORIAL DISTRICT 6  | 
| 1 HENRY ADAMS ST                   | CONSTRUCTION | 2015-09-22T00:00:00 |                              | 2012.0701      | 201306250394 | Demolish an existing building (Concourse Exhibit Hall) containing 125,000 square feet of space and 280 surface parking spaces and construct new buildings extending up to 70 feet in height and containing 560 dwellings, 438 off-street parking space, and 8, | Multiple Permits                                                                                                                                                                                                                                     | APARTMENTS | 560   | 560      | 0          | 0             |         | 0         | 15000   | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 0      | 15000  | 0      | 0        | Resident | -1       | 2012-05-31T00:00:00 | Robert Meyers           | Robert Meyers   | 415-788-2777 | CASE TRACKING   | DSIDER   | APN 3911001  | Showplace Square/Potrero Hill (EN)                  |             | South of Market | South of Market    | UMU        | URBAN MIXED USE                                         | 68-X         | SUPERVISORIAL DISTRICT 10 | 
| TRINITY PLAZA, PHASE III           | CONSTRUCTION | 2015-10-14T00:00:00 | TRINITY PLAZA, PHASE III     |                | 201209069080 |                                                                                                                                                                                                                                                                | ERECT 19 STORIES, 6 BASEMENT WITH RESIDENTIAL & COMMERCIAL BUILDING.                                                                                                                                                                                 |            | 550   | 550      | 0          | 0             |         | 0         | 0       | 0     | 0      | 0   | 0      | 0       | 0       | 0      | 0      | 0      | 0      | 0      | 0        | Resident | -1       | 2012-09-06T00:00:00 |                         |                 |              | PERMIT TRACKING |          | APN 3702391  | Downtown                                            |             | Downtown        | South of Market    | C-3-G      | DOWNTOWN- GENERAL                                       | 240-S        | SUPERVISORIAL DISTRICT 6  | 
| HUNTERS POINT EXPY                 | PL APPROVED  | 2010-08-03T00:00:00 | BAYVIEW WATERFRONT           | 2007.0946      |              | Redevelopment plans, rezoning, projects, and infrastructure for 778-acre site encompassing BVHP Areas B, C, and Shipyard, for Candlestick Point, Hunters Point Shipyard, and India Basin Shoreline, including an estimated 9,000-du, 650,000-sf retail, 2,000, |                                                                                                                                                                                                                                                      |            | 10500 | 10237    | 3345       | 3089          |         | 4110000   | 4110000 | 0     | 0      | 0   | 0      | 2756250 | 2756250 | 393750 | 393750 | 750000 | 750000 | 210000 | 210000   | Mixres   | -1       | 2010-01-11T00:00:00 | SF Redevelopment Agency | Nicole Franklin |              | CASE TRACKING   | JNAVARRE | APN 4886008  | Bayview Hunters Point; Candlestick Point            |             | South Bayshore  | Bayview            | P          | PUBLIC                                                  | OS           | SUPERVISORIAL DISTRICT 10 | 
```