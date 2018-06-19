# SF Development Pipeline 2016 Q1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-2016-quarter-1) |
| Metadata | [Link](https://data.sfgov.org/api/views/dtz9-jkjt) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dtz9-jkjt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dtz9-jkjt/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dtz9-jkjt |
| Name | SF Development Pipeline 2016 Q1 |
| Category | Housing and Buildings |
| Tags | development, housing, residential, commercial |
| Created | 2016-04-23T02:02:41Z |
| Publication Date | 2016-04-29T00:40:18Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | bestdate            | BESTDATE            | calendar_date | calendar_date |
| Yes      | series tag     | beststat            | BESTSTAT            | text          | text          |
| Yes      | series tag     | nameaddr            | NAMEADDR            | text          | text          |
| Yes      | series tag     | alias               | Alias               | text          | text          |
| Yes      | series tag     | landuse             | LANDUSE             | text          | text          |
| Yes      | series tag     | caseno              | CASENO              | text          | text          |
| Yes      | series tag     | plndesc             | PLNDESC             | text          | text          |
| Yes      | numeric metric | bpapplno            | BPAPPLNO            | number        | text          |
| Yes      | series tag     | dbidesc             | DBIDESC             | text          | text          |
| Yes      | time           | firstfiled          | FirstFiled          | calendar_date | calendar_date |
| Yes      | numeric metric | cost                | COST                | money         | money         |
| Yes      | series tag     | propuse             | PROPUSE             | text          | text          |
| Yes      | series tag     | apn                 | APN                 | text          | text          |
| Yes      | series tag     | entitlementstatus   | EntitlementStatus   | text          | number        |
| Yes      | series tag     | neighborhood        | NEIGHBORHOOD        | text          | text          |
| Yes      | series tag     | planarea            | PLANAREA            | text          | text          |
| Yes      | series tag     | district            | PLANDISTRICT        | text          | text          |
| Yes      | series tag     | supdist             | SUPDIST             | text          | text          |
| Yes      | series tag     | zoning              | ZONING              | text          | text          |
| Yes      | series tag     | districtname        | ZONEDISTRICTNAME    | text          | text          |
| Yes      | series tag     | heightlimit         | HEIGHTLIMIT         | text          | text          |
| Yes      | numeric metric | units               | UNITS               | number        | number        |
| Yes      | numeric metric | unitsnet            | UNITSNET            | number        | number        |
| Yes      | numeric metric | affordable          | AFFORDABLE          | number        | number        |
| Yes      | numeric metric | affordable_net      | AFFORDABLE_NET      | number        | number        |
| Yes      | numeric metric | retailcomm_existing | RETAILCOMM_EXISTING | number        | number        |
| Yes      | numeric metric | retailcomm_proposed | RETAILCOMM_PROPOSED | number        | number        |
| Yes      | numeric metric | retailcomm_net      | RETAILCOMM_NET      | number        | number        |
| Yes      | numeric metric | office_existing     | OFFICE_EXISTING     | number        | number        |
| Yes      | numeric metric | office_proposed     | OFFICE_PROPOSED     | number        | number        |
| Yes      | numeric metric | office_net          | OFFICE_NET          | number        | number        |
| Yes      | numeric metric | industrial_existing | INDUSTRIAL_EXISTING | number        | number        |
| Yes      | numeric metric | industrial_proposed | INDUSTRIAL_PROPOSED | number        | number        |
| Yes      | numeric metric | industrial_net      | INDUSTRIAL_NET      | number        | number        |
| Yes      | numeric metric | medical_existing    | MEDICAL_EXISTING    | number        | number        |
| Yes      | numeric metric | medical_proposed    | MEDICAL_PROPOSED    | number        | number        |
| Yes      | numeric metric | medical_net         | MEDICAL_NET         | number        | number        |
| Yes      | numeric metric | visitor_existing    | VISITOR_EXISTING    | number        | number        |
| Yes      | numeric metric | visitor_proposed    | VISITOR_PROPOSED    | number        | number        |
| Yes      | numeric metric | visitor_net         | VISITOR_NET         | number        | number        |
| Yes      | numeric metric | cie_existing        | CIE_EXISTING        | number        | number        |
| Yes      | numeric metric | cie_proposed        | CIE_PROPOSED        | number        | number        |
| Yes      | numeric metric | cie_net             | CIE_NET             | number        | number        |
| Yes      | series tag     | sponsor             | SPONSOR             | text          | text          |
| Yes      | series tag     | contact             | CONTACT             | text          | text          |
| Yes      | series tag     | contactph           | CONTACTPH           | text          | text          |
| Yes      | series tag     | planner             | PLANNER             | text          | text          |
```

## Time Field

```ls
Value = firstfiled
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = bestdate
```

## Data Commands

```ls
series e:dtz9-jkjt d:2015-11-17T00:00:00.000Z t:districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:neighborhood=Bayview t:entitlementstatus=0 t:supdist="SUPERVISORIAL DISTRICT 10" t:propuse="RECREATION BLDG" t:sponsor="HB&A Architects" t:planarea="Bayview Hunters Point" t:heightlimit=40-X t:contact="Hafsa Burt" t:caseno=2015-003310PRJ t:plndesc="New construction of a community center to be located on an empty patch of land on the corner of Harbor Road and Ingalls Street." t:nameaddr="1 ARDATH COURT (COMMUNITY CENTER)" t:planner=JDISALVO t:contactph=415-702-1609 t:landuse=CIE t:district="South Bayshore" t:apn="APN 4712008" t:dbidesc="ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER.
** MAHER: N/A **" t:zoning=RH-2 t:beststat="BP FILED" m:visitor_existing=0 m:affordable_net=0 m:office_net=0 m:retailcomm_proposed=0 m:visitor_proposed=0 m:office_proposed=0 m:cie_proposed=5588 m:industrial_net=0 m:retailcomm_existing=0 m:medical_net=0 m:bpapplno=201512175326 m:affordable=0 m:cost=600000 m:unitsnet=0 m:units=0 m:medical_existing=0 m:industrial_existing=0 m:office_existing=0 m:medical_proposed=0 m:industrial_proposed=0 m:cie_net=5588 m:retailcomm_net=0 m:visitor_net=0 m:cie_existing=0

series e:dtz9-jkjt d:2015-05-08T00:00:00.000Z t:districtname="RESIDENTIAL- HOUSE, ONE FAMILY" t:neighborhood="Ocean View" t:entitlementstatus=0 t:nameaddr="1 EDGAR AV" t:supdist="SUPERVISORIAL DISTRICT 11" t:propuse="1 FAMILY DWELLING" t:landuse=Resident t:apn="APN 6978069" t:district=Ingleside t:heightlimit=40-X t:dbidesc="CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT" t:zoning=RH-1 t:beststat="BP FILED" m:visitor_existing=0 m:affordable_net=0 m:office_net=0 m:retailcomm_proposed=0 m:visitor_proposed=0 m:office_proposed=0 m:cie_proposed=0 m:industrial_net=0 m:retailcomm_existing=0 m:medical_net=0 m:bpapplno=201505085755 m:affordable=0 m:cost=300000 m:unitsnet=1 m:units=1 m:medical_existing=0 m:industrial_existing=0 m:office_existing=0 m:medical_proposed=0 m:industrial_proposed=0 m:cie_net=0 m:retailcomm_net=0 m:visitor_net=0 m:cie_existing=0

series e:dtz9-jkjt d:2009-12-03T00:00:00.000Z t:districtname="MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT" t:entitlementstatus=-1 t:neighborhood="Downtown/Civic Center" t:supdist="SUPERVISORIAL DISTRICT 5" t:sponsor="John Ramsbacher" t:planarea="Market and Octavia" t:heightlimit=85-X t:contact="Warner Schmalz" t:caseno=2010.0102 t:plndesc="Construct a new 8-story, 35-unit mixed-use building with ground-floor commercial.  See 2008.1328" t:nameaddr="1 FRANKLIN ST" t:planner=TFRYE t:contactph=415-252-7063 t:landuse=Mixres t:district="Buena Vista" t:apn="APN 0837003" t:dbidesc="CONSTRUCTION OF 8-STORY 35 DWELLING UNITS W/RETAIL & PARKING." t:zoning=NCT-3 t:beststat=CONSTRUCTION m:visitor_existing=0 m:affordable_net=5 m:office_net=0 m:retailcomm_proposed=2384 m:visitor_proposed=0 m:office_proposed=0 m:cie_proposed=0 m:industrial_net=0 m:retailcomm_existing=0 m:medical_net=0 m:bpapplno=200912032516 m:affordable=5 m:cost=11000000 m:unitsnet=35 m:units=35 m:medical_existing=0 m:industrial_existing=0 m:office_existing=0 m:medical_proposed=0 m:industrial_proposed=0 m:cie_net=0 m:retailcomm_net=2384 m:visitor_net=0 m:cie_existing=0
```

## Meta Commands

```ls
metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:cost p:double l:COST t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordable_net p:integer l:AFFORDABLE_NET t:dataTypeName=number

metric m:retailcomm_existing p:integer l:RETAILCOMM_EXISTING t:dataTypeName=number

metric m:retailcomm_proposed p:integer l:RETAILCOMM_PROPOSED t:dataTypeName=number

metric m:retailcomm_net p:integer l:RETAILCOMM_NET t:dataTypeName=number

metric m:office_existing p:integer l:OFFICE_EXISTING t:dataTypeName=number

metric m:office_proposed p:integer l:OFFICE_PROPOSED t:dataTypeName=number

metric m:office_net p:integer l:OFFICE_NET t:dataTypeName=number

metric m:industrial_existing p:integer l:INDUSTRIAL_EXISTING t:dataTypeName=number

metric m:industrial_proposed p:integer l:INDUSTRIAL_PROPOSED t:dataTypeName=number

metric m:industrial_net p:integer l:INDUSTRIAL_NET t:dataTypeName=number

metric m:medical_existing p:integer l:MEDICAL_EXISTING t:dataTypeName=number

metric m:medical_proposed p:integer l:MEDICAL_PROPOSED t:dataTypeName=number

metric m:medical_net p:integer l:MEDICAL_NET t:dataTypeName=number

metric m:visitor_existing p:integer l:VISITOR_EXISTING t:dataTypeName=number

metric m:visitor_proposed p:integer l:VISITOR_PROPOSED t:dataTypeName=number

metric m:visitor_net p:integer l:VISITOR_NET t:dataTypeName=number

metric m:cie_existing p:integer l:CIE_EXISTING t:dataTypeName=number

metric m:cie_proposed p:integer l:CIE_PROPOSED t:dataTypeName=number

metric m:cie_net p:integer l:CIE_NET t:dataTypeName=number

entity e:dtz9-jkjt l:"SF Development Pipeline 2016 Q1" t:url=https://data.sfgov.org/api/views/dtz9-jkjt

property e:dtz9-jkjt t:meta.view v:id=dtz9-jkjt v:category="Housing and Buildings" v:averageRating=0 v:name="SF Development Pipeline 2016 Q1"

property e:dtz9-jkjt t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dtz9-jkjt t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:dtz9-jkjt t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| bestdate            | beststat     | nameaddr                          | alias         | landuse  | caseno         | plndesc                                                                                                                                                                                                                                                        | bpapplno     | dbidesc                                                                  | firstfiled          | cost        | propuse           | apn          | entitlementstatus | neighborhood          | planarea                           | district        | supdist                   | zoning  | districtname                                            | heightlimit | units | unitsnet | affordable | affordable_net | retailcomm_existing | retailcomm_proposed | retailcomm_net | office_existing | office_proposed | office_net | industrial_existing | industrial_proposed | industrial_net | medical_existing | medical_proposed | medical_net | visitor_existing | visitor_proposed | visitor_net | cie_existing | cie_proposed | cie_net | sponsor                | contact        | contactph    | planner  | 
| =================== | ============ | ================================= | ============= | ======== | ============== | ============================================================================================================================================================================================================================================================== | ============ | ======================================================================== | =================== | =========== | ================= | ============ | ================= | ===================== | ================================== | =============== | ========================= | ======= | ======================================================= | =========== | ===== | ======== | ========== | ============== | =================== | =================== | ============== | =============== | =============== | ========== | =================== | =================== | ============== | ================ | ================ | =========== | ================ | ================ | =========== | ============ | ============ | ======= | ====================== | ============== | ============ | ======== | 
| 2015-12-17T00:00:00 | BP FILED     | 1 ARDATH COURT (COMMUNITY CENTER) |               | CIE      | 2015-003310PRJ | New construction of a community center to be located on an empty patch of land on the corner of Harbor Road and Ingalls Street.                                                                                                                                | 201512175326 | ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER. ** MAHER: N/A ** | 2015-11-17T00:00:00 | 600000.00   | RECREATION BLDG   | APN 4712008  | 0                 | Bayview               | Bayview Hunters Point              | South Bayshore  | SUPERVISORIAL DISTRICT 10 | RH-2    | RESIDENTIAL- HOUSE, TWO FAMILY                          | 40-X        | 0     | 0        | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 5588         | 5588    | HB&A Architects        | Hafsa Burt     | 415-702-1609 | JDISALVO | 
| 2015-05-08T00:00:00 | BP FILED     | 1 EDGAR AV                        |               | Resident |                |                                                                                                                                                                                                                                                                | 201505085755 | CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT                        | 2015-05-08T00:00:00 | 300000.00   | 1 FAMILY DWELLING | APN 6978069  | 0                 | Ocean View            |                                    | Ingleside       | SUPERVISORIAL DISTRICT 11 | RH-1    | RESIDENTIAL- HOUSE, ONE FAMILY                          | 40-X        | 1     | 1        | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       |                        |                |              |          | 
| 2016-03-28T00:00:00 | CONSTRUCTION | 1 FRANKLIN ST                     |               | Mixres   | 2010.0102      | Construct a new 8-story, 35-unit mixed-use building with ground-floor commercial. See 2008.1328                                                                                                                                                                | 200912032516 | CONSTRUCTION OF 8-STORY 35 DWELLING UNITS W/RETAIL & PARKING.            | 2009-12-03T00:00:00 | 11000000.00 |                   | APN 0837003  | -1                | Downtown/Civic Center | Market and Octavia                 | Buena Vista     | SUPERVISORIAL DISTRICT 5  | NCT-3   | MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT | 85-X        | 35    | 35       | 5          | 5              | 0                   | 2384                | 2384           | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       | John Ramsbacher        | Warner Schmalz | 415-252-7063 | TFRYE    | 
| 2016-03-17T00:00:00 | CONSTRUCTION | 1 HENRY ADAMS ST                  |               | Resident | 2012.0701      | Demolish an existing building (Concourse Exhibit Hall) containing 125,000 square feet of space and 280 surface parking spaces and construct new buildings extending up to 70 feet in height and containing 560 dwellings, 438 off-street parking space, and 8, | 201306250394 | Multiple Permits                                                         | 2012-05-31T00:00:00 | 45000000.00 | APARTMENTS        | APN 3911001  | -1                | South of Market       | Showplace Square/Potrero Hill (EN) | South of Market | SUPERVISORIAL DISTRICT 10 | UMU     | URBAN MIXED USE                                         | 68-X        | 560   | 560      | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       | Robert Meyers          | Robert Meyers  | 415-788-2777 | DSIDER   | 
| 2014-09-24T00:00:00 | BP FILED     | 1 HORACE ST                       |               | Resident | 2014.1301      | Variance request to the rear yard requirement to permit the new construction of an additional dwelling unit.                                                                                                                                                   | 201409247165 | CONSTRUCT (N) 3-STORY SINGLE FAMILY RESIDENCE.                           | 2014-08-22T00:00:00 | 550000.00   | 1 FAMILY DWELLING | APN 6525001A | 0                 | Mission               | Mission (EN)                       | Mission         | SUPERVISORIAL DISTRICT 9  | RH-2    | RESIDENTIAL- HOUSE, TWO FAMILY                          | 40-X        | 2     | 1        | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       | Chris Giouzelis        | Yakuh Askew    | 415-920-1839 |          | 
| 2015-10-22T00:00:00 | BP APPROVED  | 1 STANYAN ST                      |               | Mixres   | 2007.0113      | The proposed project would demolish the existing gas station and construct a new 13-unit residential building with 1,700 sq. ft. of ground floor retail and 14 parking spaces. The building would be approx. 24,256 sq ft, four-stories, and 40 feet in height | 200712140534 | ERECT A NEW 4 STORIES, 13 UNITS MIXED USE BUILDING                       | 2007-01-30T00:00:00 | 1950000.00  |                   | APN 1084001B | -1                | Inner Richmond        |                                    | Richmond        | SUPERVISORIAL DISTRICT 1  | NC-3    | NEIGHBORHOOD COMMERCIAL, MODERATE SCALE                 | 40-X        | 13    | 13       | 0          | 0              | 0                   | 1700                | 1700           | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       | John E. McInerney Esq. | Bruce Baumann  | 415 551-7884 | SVELLVE  | 
| 2012-03-05T00:00:00 | BP FILED     | 10 APTOS AV                       |               | Resident |                |                                                                                                                                                                                                                                                                | 201203055412 | ERECT THREE STORY SINGLE FAMILY HOUSE.                                   | 2012-03-05T00:00:00 | 800000.00   | 1 FAMILY DWELLING | APN 3261002  | 0                 | West of Twin Peaks    |                                    | Ingleside       | SUPERVISORIAL DISTRICT 7  | RH-1(D) | RESIDENTIAL- HOUSE, ONE FAMILY- DETACHED                | 40-X        | 1     | 1        | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       |                        |                |              |          | 
| 2015-07-09T00:00:00 | BP FILED     | 10 TINGLEY ST                     |               | Resident |                |                                                                                                                                                                                                                                                                | 201507091034 | Multiple Permits                                                         | 2015-07-09T00:00:00 | 1086000.00  | 1 FAMILY DWELLING | APN 6800004  | 0                 | Outer Mission         |                                    | South Central   | SUPERVISORIAL DISTRICT 11 | RH-1    | RESIDENTIAL- HOUSE, ONE FAMILY                          | 40-X        | 2     | 2        | 0          | 0              | 0                   | 0                   | 0              | 0               | 0               | 0          | 0                   | 0                   | 0              | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       |                        |                |              |          | 
| 2015-12-17T00:00:00 | BP ISSUED    | 1000 07TH ST (BLDG 1 OF 3)        | 100 HOOPER ST | MIPS     | 2012.0203      |                                                                                                                                                                                                                                                                | 201410209377 | CONSTRUCT (N) MERCANTILE/RETAIL/PDR BUILDING.                            | 2014-10-23T00:00:00 | 52500000.00 | OFFICE            | APN 3808003  | -1                | South of Market       | Showplace Square/Potrero Hill (EN) | South of Market | SUPERVISORIAL DISTRICT 10 | PDR-1-D | PRODUCTION, DISTRIBUTION & REPAIR - 1 - DESIGN          | 58-X        | 0     | 0        | 0          | 0              | 0                   | 0                   | 0              | 0               | 284471          | 284471     | 86532               | 142784              | 56252          | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       |                        |                |              | CTOWNES  | 
| 2015-12-17T00:00:00 | BP ISSUED    | 1000 07TH ST (BLDG 2 OF 3)        | 150 HOOPER ST | Mixed    | 2012.0203      |                                                                                                                                                                                                                                                                | 201410239755 | CONSTRUCT (N) MERCANTILE/RETAIL/PDR BUILDING.                            | 2014-10-23T00:00:00 | 7500000.00  | RETAIL SALES      | APN 3808003  | -1                | South of Market       | Showplace Square/Potrero Hill (EN) | South of Market | SUPERVISORIAL DISTRICT 10 | PDR-1-D | PRODUCTION, DISTRIBUTION & REPAIR - 1 - DESIGN          | 58-X        | 0     | 0        | 0          | 0              | 0                   | 0                   | 0              | 0               | 284471          | 284471     | 86532               | 142784              | 56252          | 0                | 0                | 0           | 0                | 0                | 0           | 0            | 0            | 0       |                        |                |              | CTOWNES  | 
```