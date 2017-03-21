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
| Created | 2016-08-04T23:03:39Z |
| Publication Date | 2016-08-15T05:41:53Z |
| Rows Updated | 2016-08-15T05:39:33Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | neighborhood         | NEIGHBORHOOD         | text          | text          |
| Yes      | series tag     | apn                  | APN                  | text          | text          |
| Yes      | numeric metric | entitlement          | Entitlement          | number        | number        |
| Yes      | series tag     | beststat             | BESTSTAT             | text          | text          |
| Yes      | time           | bestdate             | BESTDATE             | calendar_date | calendar_date |
| Yes      | series tag     | nameaddr             | NAMEADDR             | text          | text          |
| Yes      | series tag     | alias                | Alias                | text          | text          |
| Yes      | series tag     | pln_caseno           | PLN_CASENO           | text          | text          |
| Yes      | numeric metric | bpapplno             | BPAPPLNO             | number        | text          |
| Yes      | numeric metric | bp_form              | BP_FORM              | number        | number        |
| Yes      | numeric metric | units                | UNITS                | number        | number        |
| Yes      | numeric metric | unitsnet             | UNITSNET             | number        | number        |
| Yes      | numeric metric | aff                  | AFF                  | number        | number        |
| Yes      | numeric metric | affnet               | AFFNET               | number        | number        |
| Yes      | series tag     | section415           | SECTION415           | text          | text          |
| Yes      | series tag     | sec415_ten           | SEC415_TENURE        | text          | text          |
| Yes      | numeric metric | senior_hsg           | SENIOR_HSG           | number        | number        |
| Yes      | numeric metric | student_hs           | STUDENT_HSG          | number        | number        |
| Yes      | numeric metric | additions            | ADDITIONS            | number        | number        |
| Yes      | numeric metric | newconstru           | NEWCONSTRUCTION      | number        | number        |
| Yes      | numeric metric | demolition           | DEMOLITION           | number        | number        |
| Yes      | numeric metric | changeofus           | CHANGEOFUSE          | number        | number        |
| Yes      | numeric metric | cost                 | COST                 | money         | money         |
| Yes      | series tag     | bldguse              | BldgUse              | text          | text          |
| Yes      | numeric metric | total_gsf            | TOTAL_GSF            | number        | number        |
| Yes      | numeric metric | net_gsf              | NET_GSF              | number        | number        |
| Yes      | numeric metric | cie                  | CIE                  | number        | number        |
| Yes      | numeric metric | cienet               | CIENET               | number        | number        |
| Yes      | numeric metric | med                  | MED                  | number        | number        |
| Yes      | numeric metric | mednet               | MEDNET               | number        | number        |
| Yes      | numeric metric | mips                 | MIPS                 | number        | number        |
| Yes      | numeric metric | mipsnet              | MIPSNET              | number        | number        |
| Yes      | numeric metric | pdr                  | PDR                  | number        | number        |
| Yes      | numeric metric | pdrnet               | PDRNET               | number        | number        |
| Yes      | numeric metric | ret                  | RET                  | number        | number        |
| Yes      | numeric metric | retnet               | RETNET               | number        | number        |
| Yes      | numeric metric | visit                | VISIT                | number        | number        |
| Yes      | numeric metric | visitnet             | VISITNET             | number        | number        |
| Yes      | numeric metric | hotelrm              | HOTELRM              | number        | number        |
| Yes      | numeric metric | hotelrmnet           | HOTELRMNET           | number        | number        |
| No       |                | firstfiled           | FirstFiled           | calendar_date | calendar_date |
| Yes      | numeric metric | multi                | MULTI                | number        | number        |
| Yes      | series tag     | pln_desc             | PLN_DESC             | text          | text          |
| Yes      | series tag     | dbi_desc             | DBI_DESC             | text          | text          |
| Yes      | series tag     | planner              | PLANNER              | text          | text          |
| Yes      | numeric metric | easternnbrhood       | EasternNbrhood       | number        | number        |
| Yes      | series tag     | pln_area             | PLN_AREA             | text          | text          |
| Yes      | series tag     | pln_district         | PLN_DISTRICT         | text          | text          |
| Yes      | series tag     | height               | HEIGHT               | text          | text          |
| Yes      | series tag     | zoning_sim           | ZONING_SIM           | text          | text          |
| Yes      | series tag     | zoning_district_name | ZONING_DISTRICT_NAME | text          | text          |
| Yes      | series tag     | supe_dist            | Supervisorial        | text          | text          |
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
series e:g5sr-9nhs d:2015-12-17T00:00:00.000Z t:supe_dist="SUPERVISORIAL DISTRICT 10" t:dbi_desc="ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER.
** MAHER: N/A **" t:neighborhood=Bayview t:bldguse="RECREATION BLDG" t:zoning_sim=RH-2 t:pln_area="Bayview Hunters Point" t:pln_caseno=2015-003310PRJ t:pln_district="South Bayshore" t:height=40-X t:nameaddr="1 ARDATH COURT (COMMUNITY CENTER)" t:pln_desc="New construction of a community center to be located on an empty patch of land on the corner of Harbor Road and Ingalls Street." t:planner=JDISALVO t:zoning_district_name="RESIDENTIAL- HOUSE, TWO FAMILY" t:apn="APN 4712008" t:beststat="BP FILED" m:med=0 m:ret=0 m:cienet=5588 m:hotelrm=0 m:demolition=0 m:aff=0 m:visit=0 m:pdr=0 m:visitnet=0 m:newconstru=1 m:additions=0 m:mips=0 m:entitlement=0 m:changeofus=0 m:mednet=0 m:bpapplno=201512175326 m:cie=5588 m:mipsnet=0 m:cost=600000 m:units=0 m:unitsnet=0 m:easternnbrhood=0 m:total_gsf=5588 m:bp_form=2 m:pdrnet=0 m:multi=0 m:student_hs=0 m:senior_hsg=0 m:affnet=0 m:retnet=0 m:hotelrmnet=0 m:net_gsf=5588

series e:g5sr-9nhs d:2015-05-08T00:00:00.000Z t:supe_dist="SUPERVISORIAL DISTRICT 11" t:dbi_desc="CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT" t:height=40-X t:pln_district=Ingleside t:neighborhood="Ocean View" t:nameaddr="1 EDGAR AV" t:planner=FLORESVE t:zoning_district_name="RESIDENTIAL- HOUSE, ONE FAMILY" t:zoning_sim=RH-1 t:bldguse="1 FAMILY DWELLING" t:apn="APN 6978069" t:beststat="BP FILED" m:med=0 m:ret=0 m:cienet=0 m:hotelrm=0 m:demolition=0 m:aff=0 m:visit=0 m:pdr=0 m:visitnet=0 m:newconstru=0 m:additions=0 m:mips=0 m:entitlement=0 m:changeofus=0 m:mednet=0 m:bpapplno=201505085755 m:cie=0 m:mipsnet=0 m:cost=300000 m:units=1 m:unitsnet=1 m:easternnbrhood=0 m:total_gsf=0 m:bp_form=1 m:pdrnet=0 m:multi=0 m:student_hs=0 m:senior_hsg=0 m:affnet=0 m:retnet=0 m:hotelrmnet=0 m:net_gsf=0

series e:g5sr-9nhs d:2016-06-16T00:00:00.000Z t:supe_dist="SUPERVISORIAL DISTRICT 5" t:dbi_desc="CONSTRUCTION OF 8-STORY 35 DWELLING UNITS W/RETAIL & PARKING." t:neighborhood="Downtown/Civic Center" t:bldguse=APARTMENTS t:zoning_sim=NCT-3 t:section415="On-site BMR Project" t:pln_area="Market and Octavia" t:pln_caseno=2010 t:sec415_ten=Ownership t:pln_district="Buena Vista" t:height=85-X t:nameaddr="1 FRANKLIN ST" t:pln_desc="Construct a new 8-story, 35-unit mixed-use building with ground-floor commercial.  See 2008.1328" t:planner=TFRYE t:zoning_district_name="MODERATE SCALE NEIGHBORHOOD COMMERCIAL TRANSIT DISTRICT" t:apn="APN 0837003" t:beststat=CONSTRUCTION m:med=0 m:ret=2384 m:cienet=0 m:hotelrm=0 m:demolition=0 m:aff=5 m:visit=0 m:pdr=0 m:visitnet=0 m:newconstru=0 m:additions=0 m:mips=0 m:entitlement=1 m:changeofus=0 m:mednet=0 m:bpapplno=200912032516 m:cie=0 m:mipsnet=0 m:cost=10050000 m:units=35 m:unitsnet=35 m:easternnbrhood=0 m:total_gsf=2384 m:bp_form=1 m:pdrnet=0 m:multi=0 m:student_hs=0 m:senior_hsg=0 m:affnet=5 m:retnet=2384 m:hotelrmnet=0 m:net_gsf=2384
```

## Meta Commands

```ls
metric m:entitlement p:integer l:Entitlement t:dataTypeName=number

metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:bp_form p:integer l:BP_FORM t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet p:integer l:UNITSNET t:dataTypeName=number

metric m:aff p:integer l:AFF t:dataTypeName=number

metric m:affnet p:integer l:AFFNET t:dataTypeName=number

metric m:senior_hsg p:integer l:SENIOR_HSG t:dataTypeName=number

metric m:student_hs p:integer l:STUDENT_HSG t:dataTypeName=number

metric m:additions p:integer l:ADDITIONS t:dataTypeName=number

metric m:newconstru p:integer l:NEWCONSTRUCTION t:dataTypeName=number

metric m:demolition p:integer l:DEMOLITION t:dataTypeName=number

metric m:changeofus p:integer l:CHANGEOFUSE t:dataTypeName=number

metric m:cost p:double l:COST t:dataTypeName=money

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

metric m:hotelrm p:integer l:HOTELRM t:dataTypeName=number

metric m:hotelrmnet p:integer l:HOTELRMNET t:dataTypeName=number

metric m:multi p:integer l:MULTI d:"project with multiple building permits; part of a phased project" t:dataTypeName=number

metric m:easternnbrhood p:integer l:EasternNbrhood t:dataTypeName=number

entity e:g5sr-9nhs l:"SF Development Pipeline 2016 Q2" t:url=https://data.sfgov.org/api/views/g5sr-9nhs

property e:g5sr-9nhs t:meta.view v:id=g5sr-9nhs v:category="Housing and Buildings" v:averageRating=0 v:name="SF Development Pipeline 2016 Q2"

property e:g5sr-9nhs t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:g5sr-9nhs t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:g5sr-9nhs t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```