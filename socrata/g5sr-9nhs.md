# SF Development Pipeline 2016 Q2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pipeline-q2-2016) |
| Metadata | [Link](https://data.sfgov.org/api/views/g5sr-9nhs) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/g5sr-9nhs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/g5sr-9nhs/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | g5sr-9nhs |
| Name | SF Development Pipeline 2016 Q2 |
| Category | Housing and Buildings |
| Tags | planning, development, construction, residential, commercial |
| Created | 2016-08-04T23:03:39Z |
| Publication Date | 2017-05-02T01:20:11Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name            | Data Type     | Render Type   |
| ======== | ============== | ==================== | =============== | ============= | ============= |
| Yes      | series tag     | apn                  | APN             | text          | text          |
| Yes      | numeric metric | entitlement          | Entitlement     | number        | number        |
| Yes      | series tag     | beststat             | BESTSTAT        | text          | text          |
| Yes      | time           | bestdate             | BESTDATE        | calendar_date | calendar_date |
| Yes      | series tag     | nameaddr             | NAMEADDR        | text          | text          |
| Yes      | series tag     | alias                | Alias           | text          | text          |
| Yes      | series tag     | pln_caseno           | PLN_CASENO      | text          | text          |
| Yes      | numeric metric | bpapplno             | BP_APPLNO       | number        | text          |
| Yes      | numeric metric | units                | UNITS           | number        | number        |
| Yes      | numeric metric | unitsnet             | NET_UNITS       | number        | number        |
| Yes      | numeric metric | aff                  | AFF_UNITS       | number        | number        |
| Yes      | numeric metric | affnet               | NET_AFF_UNITS   | number        | number        |
| Yes      | series tag     | section415           | SECTION415      | text          | text          |
| Yes      | series tag     | sec415_ten           | TENURE_TYPE     | text          | text          |
| Yes      | numeric metric | cost                 | COST            | money         | money         |
| Yes      | series tag     | bldguse              | PROPUSE         | text          | text          |
| Yes      | numeric metric | total_gsf            | TOTAL_GSF       | number        | number        |
| Yes      | numeric metric | net_gsf              | NET_GSF         | number        | number        |
| Yes      | numeric metric | cie                  | CIE             | number        | number        |
| Yes      | numeric metric | cienet               | NET_CIE         | number        | number        |
| Yes      | numeric metric | med                  | MED             | number        | number        |
| Yes      | numeric metric | mednet               | NET_MED         | number        | number        |
| Yes      | numeric metric | mips                 | MIPS            | number        | number        |
| Yes      | numeric metric | mipsnet              | NET_MIPS        | number        | number        |
| Yes      | numeric metric | pdr                  | PDR             | number        | number        |
| Yes      | numeric metric | pdrnet               | NET_PDR         | number        | number        |
| Yes      | numeric metric | ret                  | RET             | number        | number        |
| Yes      | numeric metric | retnet               | NET_RET         | number        | number        |
| Yes      | numeric metric | visit                | VISIT           | number        | number        |
| Yes      | numeric metric | visitnet             | NET_VISIT       | number        | number        |
| No       |                | firstfiled           | FirstFiled      | calendar_date | calendar_date |
| Yes      | series tag     | pln_desc             | PLN_DESC        | text          | text          |
| Yes      | series tag     | dbi_desc             | BP_DESC         | text          | text          |
| Yes      | series tag     | planner              | PLANNER         | text          | text          |
| Yes      | series tag     | sponsor              | SPONSOR         | text          | text          |
| Yes      | series tag     | sp_contact           | SP_CONTACT      | text          | text          |
| Yes      | series tag     | sp_contactph         | SP_CONTACTPH    | text          | text          |
| Yes      | series tag     | neighborhood         | NEIGHBORHOOD    | text          | text          |
| Yes      | series tag     | pln_area             | PLAN_AREA       | text          | text          |
| Yes      | series tag     | pln_district         | PLAN_DISTRICT   | text          | text          |
| Yes      | series tag     | height               | HEIGHT_DISTRICT | text          | text          |
| Yes      | series tag     | zoning_sim           | ZONING_SIM      | text          | text          |
| Yes      | series tag     | zoning_district_name | ZONING_DISTRICT | text          | text          |
| Yes      | series tag     | supe_dist            | SUPE_DISTRICT   | text          | text          |
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
series e:g5sr-9nhs d:2015-12-17T00:00:00.000Z t:sponsor=PENDING t:bldguse="RECREATION BLDG" t:nameaddr="1 ARDATH COURT (COMMUNITY CENTER)" t:beststat="BP FILED" t:zoning_sim=RH-2 t:supe_dist="SUPERVISORIAL DISTRICT 10" t:dbi_desc="ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER.
** MAHER: N/A **" t:sp_contact=PENDING t:sp_contactph=PENDING t:zoning_district_name="RESIDENTIAL- HOUSE, TWO FAMILY" t:pln_caseno=2015-003310PRJ t:pln_area="Bayview Hunters Point" t:pln_district="South Bayshore" t:neighborhood=Bayview t:planner=JDISALVO t:pln_desc="New construction of a community center to be located on an empty patch of land on the corner of Harbor Road and Ingalls Street." t:apn="APN 4712008" t:height=40-X m:aff=0 m:ret=0 m:cost=600000 m:total_gsf=5588 m:visitnet=0 m:bpapplno=201512175326 m:mipsnet=0 m:pdrnet=0 m:entitlement=0 m:units=0 m:mips=0 m:med=0 m:net_gsf=5588 m:affnet=0 m:mednet=0 m:unitsnet=0 m:retnet=0 m:cienet=5588 m:visit=0 m:cie=5588 m:pdr=0

series e:g5sr-9nhs d:2015-05-08T00:00:00.000Z t:bldguse="1 FAMILY DWELLING" t:nameaddr="1 EDGAR AV" t:beststat="BP FILED" t:zoning_sim=RH-1 t:supe_dist="SUPERVISORIAL DISTRICT 11" t:dbi_desc="CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT" t:pln_district=Ingleside t:neighborhood="Ocean View" t:planner=FLORESVE t:zoning_district_name="RESIDENTIAL- HOUSE, ONE FAMILY" t:apn="APN 6978069" t:height=40-X m:aff=0 m:ret=0 m:cost=300000 m:total_gsf=0 m:visitnet=0 m:bpapplno=201505085755 m:mipsnet=0 m:pdrnet=0 m:entitlement=0 m:units=1 m:mips=0 m:med=0 m:net_gsf=0 m:affnet=0 m:mednet=0 m:unitsnet=1 m:retnet=0 m:cienet=0 m:visit=0 m:cie=0 m:pdr=0

series e:g5sr-9nhs d:2016-06-16T00:00:00.000Z t:sponsor=Closed t:bldguse=APARTMENTS t:nameaddr="1 FRANKLIN ST" t:beststat=CONSTRUCTION t:zoning_sim=NCT-3 t:supe_dist="SUPERVISORIAL DISTRICT 5" t:dbi_desc="CONSTRUCTION OF 8-STORY 35 DWELLING UNITS W/RETAIL & PARKING." t:sp_contact=Closed t:sp_contactph=Closed t:zoning_district_name="MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT" t:sec415_ten=Ownership t:pln_caseno=2010 t:section415="On-site BMR Project" t:pln_area="Market and Octavia" t:pln_district="Buena Vista" t:neighborhood="Downtown/Civic Center" t:planner=TFRYE t:pln_desc="Construct a new 8-story, 35-unit mixed-use building with ground-floor commercial.  See 2008.1328" t:apn="APN 0837003" t:height=85-X m:aff=5 m:ret=2384 m:cost=10050000 m:total_gsf=2384 m:visitnet=0 m:bpapplno=200912032516 m:mipsnet=0 m:pdrnet=0 m:entitlement=1 m:units=35 m:mips=0 m:med=0 m:net_gsf=2384 m:affnet=5 m:mednet=0 m:unitsnet=35 m:retnet=2384 m:cienet=0 m:visit=0 m:cie=0 m:pdr=0
```

## Meta Commands

```ls
metric m:entitlement p:integer l:Entitlement t:dataTypeName=number

metric m:bpapplno p:long l:BP_APPLNO t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:NET_UNITS t:dataTypeName=number

metric m:aff p:integer l:AFF_UNITS t:dataTypeName=number

metric m:affnet p:integer l:NET_AFF_UNITS t:dataTypeName=number

metric m:cost p:double l:COST t:dataTypeName=money

metric m:total_gsf p:integer l:TOTAL_GSF t:dataTypeName=number

metric m:net_gsf p:integer l:NET_GSF t:dataTypeName=number

metric m:cie p:integer l:CIE t:dataTypeName=number

metric m:cienet p:integer l:NET_CIE t:dataTypeName=number

metric m:med p:integer l:MED t:dataTypeName=number

metric m:mednet p:integer l:NET_MED t:dataTypeName=number

metric m:mips p:integer l:MIPS t:dataTypeName=number

metric m:mipsnet p:integer l:NET_MIPS t:dataTypeName=number

metric m:pdr p:integer l:PDR t:dataTypeName=number

metric m:pdrnet p:integer l:NET_PDR t:dataTypeName=number

metric m:ret p:integer l:RET t:dataTypeName=number

metric m:retnet p:integer l:NET_RET t:dataTypeName=number

metric m:visit p:integer l:VISIT t:dataTypeName=number

metric m:visitnet p:integer l:NET_VISIT t:dataTypeName=number

entity e:g5sr-9nhs l:"SF Development Pipeline 2016 Q2" t:url=https://data.sfgov.org/api/views/g5sr-9nhs

property e:g5sr-9nhs t:meta.view d:2017-09-25T07:29:18.499Z v:averageRating=0 v:name="SF Development Pipeline 2016 Q2" v:id=g5sr-9nhs v:category="Housing and Buildings"

property e:g5sr-9nhs t:meta.view.license d:2017-09-25T07:29:18.499Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:g5sr-9nhs t:meta.view.owner d:2017-09-25T07:29:18.499Z v:displayName="Information & Analysis Group (IAG) - SFPlanning" v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning"

property e:g5sr-9nhs t:meta.view.tableauthor d:2017-09-25T07:29:18.499Z v:displayName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| apn          | entitlement | beststat     | bestdate            | nameaddr                          | alias | pln_caseno     | bpapplno     | units | unitsnet | aff | affnet | section415          | sec415_ten | cost        | bldguse              | total_gsf | net_gsf | cie  | cienet | med | mednet | mips | mipsnet | pdr | pdrnet | ret   | retnet | visit | visitnet | firstfiled          | pln_desc                                                                                                                                                                                                                                                       | dbi_desc                                                                                                                                                                                                                                                      | planner  | sponsor              | sp_contact           | sp_contactph         | neighborhood          | pln_area                           | pln_district    | height      | zoning_sim | zoning_district_name                                    | supe_dist                 | 
| ============ | =========== | ============ | =================== | ================================= | ===== | ============== | ============ | ===== | ======== | === | ====== | =================== | ========== | =========== | ==================== | ========= | ======= | ==== | ====== | === | ====== | ==== | ======= | === | ====== | ===== | ====== | ===== | ======== | =================== | ============================================================================================================================================================================================================================================================== | ============================================================================================================================================================================================================================================================= | ======== | ==================== | ==================== | ==================== | ===================== | ================================== | =============== | =========== | ========== | ======================================================= | ========================= | 
| APN 4712008  | 0           | BP FILED     | 2015-12-17T00:00:00 | 1 ARDATH COURT (COMMUNITY CENTER) |       | 2015-003310PRJ | 201512175326 | 0     | 0        | 0   | 0      |                     |            | 600000.00   | RECREATION BLDG      | 5588      | 5588    | 5588 | 5588   | 0   | 0      | 0    | 0       | 0   | 0      | 0     | 0      | 0     | 0        | 2015-11-17T00:00:00 | New construction of a community center to be located on an empty patch of land on the corner of Harbor Road and Ingalls Street.                                                                                                                                | ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER. ** MAHER: N/A **                                                                                                                                                                                      | JDISALVO | PENDING              | PENDING              | PENDING              | Bayview               | Bayview Hunters Point              | South Bayshore  | 40-X        | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY                          | SUPERVISORIAL DISTRICT 10 | 
| APN 6978069  | 0           | BP FILED     | 2015-05-08T00:00:00 | 1 EDGAR AV                        |       |                | 201505085755 | 1     | 1        | 0   | 0      |                     |            | 300000.00   | 1 FAMILY DWELLING    | 0         | 0       | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 0     | 0      | 0     | 0        | 2015-05-08T00:00:00 |                                                                                                                                                                                                                                                                | CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT                                                                                                                                                                                                             | FLORESVE |                      |                      |                      | Ocean View            |                                    | Ingleside       | 40-X        | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY                          | SUPERVISORIAL DISTRICT 11 | 
| APN 0837003  | 1           | CONSTRUCTION | 2016-06-16T00:00:00 | 1 FRANKLIN ST                     |       | 2010           | 200912032516 | 35    | 35       | 5   | 5      | On-site BMR Project | Ownership  | 10050000.00 | APARTMENTS           | 2384      | 2384    | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 2384  | 2384   | 0     | 0        | 2009-12-03T00:00:00 | Construct a new 8-story, 35-unit mixed-use building with ground-floor commercial. See 2008.1328                                                                                                                                                                | CONSTRUCTION OF 8-STORY 35 DWELLING UNITS W/RETAIL & PARKING.                                                                                                                                                                                                 | TFRYE    | Closed               | Closed               | Closed               | Downtown/Civic Center | Market and Octavia                 | Buena Vista     | 85-X        | NCT-3      | MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT | SUPERVISORIAL DISTRICT 5  | 
| APN 3911001  | 1           | CONSTRUCTION | 2016-04-07T00:00:00 | 1 HENRY ADAMS ST                  |       | 2012           | 201306250394 | 239   | 239      | 0   | 0      | Land Dedication     | Rental     | 20000000.00 | APARTMENTS           | 11770     | 11770   | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 11770 | 11770  | 0     | 0        | 2012-05-31T00:00:00 | Demolish an existing building (Concourse Exhibit Hall) containing 125,000 square feet of space and 280 surface parking spaces and construct new buildings extending up to 70 feet in height and containing 560 dwellings, 438 off-street parking space, and 8, | TO ERECT 6 STORIES, NO BASEMENT, 85 UNITS RESIDENTIAL WITH RETAIL & PARKING BUILDING.                                                                                                                                                                         | DSIDER   | Closed               | Closed               | Closed               | South of Market       | Showplace Square/Potrero Hill (EN) | South of Market | 68-X        | UMU        | URBAN MIXED USE                                         | SUPERVISORIAL DISTRICT 10 | 
| APN 6525001A | 0           | BP FILED     | 2014-09-24T00:00:00 | 1 HORACE ST                       |       | 2014           | 201409247165 | 2     | 1        | 0   | 0      |                     |            | 550000.00   | 1 FAMILY DWELLING    | 0         | 0       | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 0     | 0      | 0     | 0        | 2014-08-22T00:00:00 | Variance request to the rear yard requirement to permit the new construction of an additional dwelling unit.                                                                                                                                                   | CONSTRUCT (N) 3-STORY SINGLE FAMILY RESIDENCE.                                                                                                                                                                                                                | RSUCRE   | UNDER REVIEW         | UNDER REVIEW         | UNDER REVIEW         | Mission               | Mission (EN)                       | Mission         | 40-X        | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY                          | SUPERVISORIAL DISTRICT 9  | 
| APN 5688040  | 0           | BP FILED     | 2016-05-12T00:00:00 | 1 PUTNAM ST                       |       |                | 201605127314 | 1     | -1       | 0   | 0      |                     |            | 2000.00     | 1 FAMILY DWELLING    | 0         | 0       | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 0     | 0      | 0     | 0        | 2016-05-12T00:00:00 |                                                                                                                                                                                                                                                                | REMOV ILLEGAL UNIT TRIGGERS AVALOS LEGISLATION ORD 33-16 DWELLING UNIT CONSTRUCTED OR INSTALLED WITHOUT PERMIT (REVERT INTERIOR AT LOWER GARAGE LEVEL BACK TO LAST KNOWN LEGAL STATUS (DBI APP #2002-23-03-4390) NOV#201579415- REMOVAL OF ILLEGAL BEDRM BACK |          |                      |                      |                      | Bernal Heights        |                                    | Bernal Heights  | 40-X        | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY                          | SUPERVISORIAL DISTRICT 9  | 
| APN 1084001B | 1           | BP ISSUED    | 2016-06-15T00:00:00 | 1 STANYAN ST                      |       | 2007           | 200712140534 | 13    | 13       | 0   | 0      | Fee Payment         |            | 6000000.00  | APARTMENTS           | 1700      | -5810   | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 1700  | -5810  | 0     | 0        | 2007-01-30T00:00:00 | The proposed project would demolish the existing gas station and construct a new 13-unit residential building with 1,700 sq. ft. of ground floor retail and 14 parking spaces. The building would be approx. 24,256 sq ft, four-stories, and 40 feet in height | TO ERECT 4 STORIES, NO BASEMENT, 13 UNITS RESIDENTIAL WITH RETAIL & PARKING BUILDING.                                                                                                                                                                         | SVELLVE  | Closed               | Closed               | Closed               | Inner Richmond        |                                    | Richmond        | 40-X        | NC-3       | NEIGHBORHOOD COMMERCIAL, MODERATE SCALE                 | SUPERVISORIAL DISTRICT 1  | 
| APN 0086012  | 0           | BP FILED     | 2016-04-25T00:00:00 | 1 TELEGRAPH HILL BL               |       | 2016-006762PRJ | 201604255639 | 0     | 0        | 0   | 0      |                     |            | 10000.00    | FOOD/BEVERAGE HNDLNG | 135       | -865    | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 135   | -865   | 0     | 0        | 2016-04-25T00:00:00 |                                                                                                                                                                                                                                                                | (REAR BUILDING) TO ERECT 1 STORY, NO BASEMENT, LIMITED RESTAURANT.                                                                                                                                                                                            | LAVALLEY | Application Accepted | Application Accepted | Application Accepted | North Beach           |                                    | Northeast       | OS          | P          | PUBLIC                                                  | SUPERVISORIAL DISTRICT 3  | 
| APN 3506004  | 0           | PL FILED     | 2016-04-11T00:00:00 | 10 SOUTH VAN NESS AV              |       | 2015-004568PRJ |              | 855   | 855      | 0   | 0      |                     |            | 0.00        |                      | 28100     | -71900  | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 28100 | -71900 | 0     | 0        | 2015-04-14T00:00:00 | New high-rise, mixed-use construction consisting of studio, 1-bedroom, 2-bedroom and 3-bedroom residential units, associated amenity spaces, and retail spaces at the ground floor. Proposed project entails two 400' towers over a 120' podium building, wit  |                                                                                                                                                                                                                                                               | VBYRD    | UNDER REVIEW         | UNDER REVIEW         | UNDER REVIEW         | South of Market       | Market and Octavia; Downtown       | Mission         | 120/400-R-2 | C-3-G      | DOWNTOWN- GENERAL                                       | SUPERVISORIAL DISTRICT 6  | 
| APN 6800004  | 0           | BP FILED     | 2015-07-09T00:00:00 | 10 TINGLEY ST                     |       |                | 201507091034 | 2     | 2        | 0   | 0      |                     |            | 546000.00   | 1 FAMILY DWELLING    | 0         | 0       | 0    | 0      | 0   | 0      | 0    | 0       | 0   | 0      | 0     | 0      | 0     | 0        | 2015-07-09T00:00:00 |                                                                                                                                                                                                                                                                | ERECT A THREE STORY SINGLE FAMILY DWELLING.                                                                                                                                                                                                                   | TRANNANC |                      |                      |                      | Outer Mission         |                                    | South Central   | 40-X        | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY                          | SUPERVISORIAL DISTRICT 11 | 
```