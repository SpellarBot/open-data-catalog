# San Francisco Development Pipeline 2015 Quarter 1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sf-development-pipeline-2015-q1) |
| Metadata | [Link](https://data.sfgov.org/api/views/2cma-9y6y) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2cma-9y6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2cma-9y6y/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2cma-9y6y |
| Name | San Francisco Development Pipeline 2015 Quarter 1 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | development, housing, residential, commercial, construction, building |
| Created | 2015-08-01T04:09:24Z |
| Publication Date | 2015-08-18T21:30:24Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name            | Data Type     | Render Type   |
| ======== | ============== | ============ | =============== | ============= | ============= |
| Yes      | series tag     | beststat     | BESTSTAT        | text          | text          |
| Yes      | time           | bestdate     | BESTDATE        | calendar_date | calendar_date |
| Yes      | series tag     | nameaddr     | NAMEADDR        | text          | text          |
| Yes      | series tag     | caseno       | CASENO          | text          | text          |
| Yes      | numeric metric | bpapplno     | BPAPPLNO        | number        | number        |
| Yes      | series tag     | propuse      | PROPUSE         | text          | text          |
| Yes      | series tag     | blklot       | BLKLOT          | html          | html          |
| Yes      | series tag     | landuse      | LANDUSE         | text          | text          |
| Yes      | series tag     | descript     | DESCRIPT        | text          | text          |
| Yes      | series tag     | dbidesc      | DBIDESC         | text          | text          |
| Yes      | numeric metric | units        | UNITS           | number        | number        |
| Yes      | numeric metric | unitsnet     | UNITSNET        | number        | number        |
| Yes      | numeric metric | aff          | AFF             | number        | number        |
| Yes      | numeric metric | affnet       | AFFNET          | number        | number        |
| Yes      | numeric metric | total_gsf    | TOTAL_GSF       | number        | number        |
| Yes      | numeric metric | cie          | CIE             | number        | number        |
| Yes      | numeric metric | med          | MED             | number        | number        |
| Yes      | numeric metric | mips         | MIPS            | number        | number        |
| Yes      | numeric metric | pdr          | PDR             | number        | number        |
| Yes      | numeric metric | ret          | RET             | number        | number        |
| Yes      | numeric metric | visit        | VISIT           | number        | number        |
| Yes      | numeric metric | net_gsf      | NET_GSF         | number        | number        |
| Yes      | numeric metric | cienet       | CIENET          | number        | number        |
| Yes      | numeric metric | mednet       | MEDNET          | number        | number        |
| Yes      | numeric metric | mipsnet      | MIPSNET         | number        | number        |
| Yes      | numeric metric | pdrnet       | PDRNET          | number        | number        |
| Yes      | numeric metric | retnet       | RETNET          | number        | number        |
| Yes      | numeric metric | visitnet     | VISITNET        | number        | number        |
| Yes      | series tag     | entitlement  | Entitlement     | checkbox      | checkbox      |
| Yes      | series tag     | alias        | Alias           | text          | text          |
| Yes      | series tag     | districtname | ZONING          | text          | text          |
| Yes      | series tag     | zoning_sim   | ZONING_SIMPLIFY | text          | text          |
| Yes      | series tag     | height       | HEIGHT          | text          | text          |
| Yes      | series tag     | neighborhood | PLNNBRHOOD      | text          | text          |
| Yes      | series tag     | district     | PLNDISTRICT     | text          | text          |
| Yes      | series tag     | supdist      | SUPEDIST        | text          | text          |
| Yes      | series tag     | source       | SOURCE          | text          | text          |
| Yes      | series tag     | planner      | PLANNER         | text          | text          |
| No       |                | filedate     | FILEDATE        | calendar_date | calendar_date |
| Yes      | series tag     | sponsor      | SPONSOR         | text          | text          |
| Yes      | series tag     | contact      | CONTACT         | text          | text          |
| Yes      | series tag     | contactph    | CONTACTPH       | text          | text          |
| Yes      | series tag     | decision     | DECISION        | text          | text          |
| No       |                | decdate      | DECDATE         | calendar_date | calendar_date |
| Yes      | series tag     | action       | ACTION          | text          | text          |
| No       |                | actdate      | ACTDATE         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = filedate,decdate,actdate
```

## Data Commands

```ls
series e:2cma-9y6y d:2015-03-25T00:00:00.000Z t:blklot=3965021 t:districtname="URBAN MIXED USE" t:neighborhood=Mission t:supdist="SUPERVISORIAL DISTRICT 9" t:zoning_sim=UMU t:caseno=2014.1201 t:height=68-X t:source=manual t:nameaddr="2435-2445 16TH ST" t:planner=EJACKSON t:landuse=Mixres t:district=Mission t:beststat="PL FILED" m:ret=7399 m:med=0 m:cienet=0 m:mednet=0 m:aff=6 m:visit=0 m:pdr=0 m:cie=0 m:mipsnet=0 m:unitsnet=53 m:units=53 m:total_gsf=65369 m:visitnet=0 m:pdrnet=-9997 m:affnet=6 m:mips=0 m:retnet=7399 m:net_gsf=55372

series e:2cma-9y6y d:2015-03-20T00:00:00.000Z t:blklot=2628032 t:height=40-X t:source="PERMIT TRACKING" t:districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:neighborhood="Castro/Upper Market" t:nameaddr="271 UPPER TR" t:supdist="SUPERVISORIAL DISTRICT 8" t:zoning_sim=RH-2 t:propuse="1 FAMILY DWELLING" t:landuse=Resident t:district="Buena Vista" t:dbidesc="Multiple Permits" t:beststat="BP FILED" m:ret=0 m:med=0 m:cienet=0 m:mednet=0 m:aff=0 m:visit=0 m:pdr=0 m:cie=0 m:bpapplno=201503201418 m:mipsnet=0 m:unitsnet=2 m:units=2 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:affnet=0 m:mips=0 m:retnet=0 m:net_gsf=0

series e:2cma-9y6y d:2013-07-15T00:00:00.000Z t:blklot=1505014 t:height=40-X t:source="PERMIT TRACKING" t:districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:neighborhood="Outer Richmond" t:nameaddr="579 39TH AV" t:supdist="SUPERVISORIAL DISTRICT 1" t:zoning_sim=RH-2 t:propuse="2 FAMILY DWELLING" t:landuse=Resident t:district=Richmond t:dbidesc="ERECT 3 STORIES, 2 DWELLING UNITS." t:beststat="BP FILED" m:ret=0 m:med=0 m:cienet=0 m:mednet=0 m:aff=0 m:visit=0 m:pdr=0 m:cie=0 m:bpapplno=201307151829 m:mipsnet=0 m:unitsnet=2 m:units=2 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:affnet=0 m:mips=0 m:retnet=0 m:net_gsf=0
```

## Meta Commands

```ls
metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:aff p:integer l:AFF t:dataTypeName=number

metric m:affnet p:integer l:AFFNET t:dataTypeName=number

metric m:total_gsf p:integer l:TOTAL_GSF t:dataTypeName=number

metric m:cie p:integer l:CIE t:dataTypeName=number

metric m:med p:integer l:MED t:dataTypeName=number

metric m:mips p:integer l:MIPS t:dataTypeName=number

metric m:pdr p:integer l:PDR t:dataTypeName=number

metric m:ret p:integer l:RET t:dataTypeName=number

metric m:visit p:integer l:VISIT t:dataTypeName=number

metric m:net_gsf p:integer l:NET_GSF t:dataTypeName=number

metric m:cienet p:integer l:CIENET t:dataTypeName=number

metric m:mednet p:integer l:MEDNET t:dataTypeName=number

metric m:mipsnet p:integer l:MIPSNET t:dataTypeName=number

metric m:pdrnet p:integer l:PDRNET t:dataTypeName=number

metric m:retnet p:integer l:RETNET t:dataTypeName=number

metric m:visitnet p:integer l:VISITNET t:dataTypeName=number

entity e:2cma-9y6y l:"San Francisco Development Pipeline 2015 Quarter 1" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/2cma-9y6y

property e:2cma-9y6y t:meta.view v:id=2cma-9y6y v:category="Housing and Buildings" v:attributionLink="http://sf-planning.org/index.aspx?page=1691" v:averageRating=0 v:name="San Francisco Development Pipeline 2015 Quarter 1" v:attribution="San Francisco Planning Department"

property e:2cma-9y6y t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2cma-9y6y t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:2cma-9y6y t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| beststat | bestdate            | nameaddr              | caseno    | bpapplno     | propuse           | blklot  | landuse  | descript | dbidesc                                                                                                                                                                                                                                              | units | unitsnet | aff | affnet | total_gsf | cie   | med | mips   | pdr | ret  | visit | net_gsf | cienet | mednet | mipsnet | pdrnet | retnet | visitnet | entitlement | alias | districtname                         | zoning_sim | height       | neighborhood        | district        | supdist                   | source          | planner  | filedate            | sponsor | contact | contactph | decision | decdate | action | actdate | 
| ======== | =================== | ===================== | ========= | ============ | ================= | ======= | ======== | ======== | ==================================================================================================================================================================================================================================================== | ===== | ======== | === | ====== | ========= | ===== | === | ====== | === | ==== | ===== | ======= | ====== | ====== | ======= | ====== | ====== | ======== | =========== | ===== | ==================================== | ========== | ============ | =================== | =============== | ========================= | =============== | ======== | =================== | ======= | ======= | ========= | ======== | ======= | ====== | ======= | 
| PL FILED | 2015-03-25T00:00:00 | 2435-2445 16TH ST     | 2014.1201 |              |                   | 3965021 | Mixres   |          |                                                                                                                                                                                                                                                      | 53    | 53       | 6   | 6      | 65369     | 0     | 0   | 0      | 0   | 7399 | 0     | 55372   | 0      | 0      | 0       | -9997  | 7399   | 0        |             |       | URBAN MIXED USE                      | UMU        | 68-X         | Mission             | Mission         | SUPERVISORIAL DISTRICT 9  | manual          | EJACKSON |                     |         |         |           |          |         |        |         | 
| BP FILED | 2015-03-20T00:00:00 | 271 UPPER TR          |           | 201503201418 | 1 FAMILY DWELLING | 2628032 | Resident |          | Multiple Permits                                                                                                                                                                                                                                     | 2     | 2        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- HOUSE, TWO FAMILY       | RH-2       | 40-X         | Castro/Upper Market | Buena Vista     | SUPERVISORIAL DISTRICT 8  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2013-07-15T00:00:00 | 579 39TH AV           |           | 201307151829 | 2 FAMILY DWELLING | 1505014 | Resident |          | ERECT 3 STORIES, 2 DWELLING UNITS.                                                                                                                                                                                                                   | 2     | 2        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- HOUSE, TWO FAMILY       | RH-2       | 40-X         | Outer Richmond      | Richmond        | SUPERVISORIAL DISTRICT 1  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2014-10-28T00:00:00 | 1167 PALOU AV         |           | 201410280026 | 2 FAMILY DWELLING | 4757047 | Resident |          | LEGALIZE IN LAW UNIT AT 1ST FLOOR PER ORINANCE 43-14                                                                                                                                                                                                 | 2     | 1        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- HOUSE, ONE FAMILY       | RH-1       | 40-X         | Bayview             | South Bayshore  | SUPERVISORIAL DISTRICT 10 | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2014-12-31T00:00:00 | 3945 JUDAH ST         |           | 201412314770 | APARTMENTS        | 1809028 | Resident |          | TO ERECT 4 STORIES, 1 BASEMENT, 6 UNITS RESIDENTIAL WITH COMMERCIAL BUILDING.                                                                                                                                                                        | 6     | 6        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | NEIGHBORHOOD COMMERCIAL, CLUSTER     | NC-1       | 40-X         | Outer Sunset        | Outer Sunset    | SUPERVISORIAL DISTRICT 4  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2014-11-12T00:00:00 | 726 PRESIDIO AV       |           | 201411121318 | APARTMENTS        | 1055013 | Resident |          | TO ERECT 4 STORIES, 1 BASEMENT, 7 UNITS MULTI-FAMILY RESIDENT. ** MAHER: COMPLIANCE WITH ORDINANCE N                                                                                                                                                 | 7     | 7        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- MIXED, MODERATE DENSITY | RM-2       | 40-X         | Western Addition    | Richmond        | SUPERVISORIAL DISTRICT 2  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2014-10-10T00:00:00 | 44 WOODWARD ST        |           | 201410108600 | APARTMENTS        | 3532048 | Resident |          | CONSTRUCT (N) 4-STORY, 3-UNITS APARTMENT.                                                                                                                                                                                                            | 3     | 3        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- MIXED, LOW DENSITY      | RM-1       | 40-X         | Mission             | Mission         | SUPERVISORIAL DISTRICT 9  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| BP FILED | 2014-12-11T00:00:00 | 835 SOUTH VAN NESS AV |           | 201412113579 | APARTMENTS        | 3594023 | Resident |          | ERECT 4-STORY, TYPE 5A, 3 DWELLING UNITS BUILDING.                                                                                                                                                                                                   | 3     | 3        | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | RESIDENTIAL- HOUSE, THREE FAMILY     | RH-3       | 50-X         | Mission             | Mission         | SUPERVISORIAL DISTRICT 9  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
| PL FILED | 2015-05-15T00:00:00 | 925 MISSION ST        | 2011.0409 |              |                   | 3725093 | Mixres   |          | Project review for a development . A mix of residential, office, retail and other uses on the approx. 4 acre site on the SE corner of 5th/ Mission and extending towards sixth street & south to Howard Street, The site is comprised of 23 parcels. | 688   | 688      | 58  | 58     | 617900    | 17300 | 0   | 593500 | 0   | 7100 | 0     | 574800  | -23600 | 0      | 591300  | 0      | 7100   | 0        |             | 5M    | DOWNTOWN SUPPORT                     | C-3-S      | 160-F        | South of Market     | Downtown        | SUPERVISORIAL DISTRICT 6  | CASE TRACKING   | KGUY     | 2011-07-27T00:00:00 |         |         |           |          |         |        |         | 
| BP FILED | 2014-12-23T00:00:00 | 245 01ST ST           |           | 201412234418 | APARTMENTS        | 3737012 | Resident |          | TO ERECT 55 STORIES, 2.5 BASEMENT, 603 UNITS RESIDENTIAL, RETAIL & PARKING BUILDING. ** MAHER: COMPL                                                                                                                                                 | 603   | 603      | 0   | 0      | 0         | 0     | 0   | 0      | 0   | 0    | 0     | 0       | 0      | 0      | 0       | 0      | 0      | 0        |             |       | TRANSBAY DOWNTOWN RESIDENTIAL        | TB DTR     | 50/85/550-TB | Financial District  | South of Market | SUPERVISORIAL DISTRICT 6  | PERMIT TRACKING |          |                     |         |         |           |          |         |        |         | 
```