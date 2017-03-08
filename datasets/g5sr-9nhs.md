# SF Development Pipeline 2016 Q2

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/g5sr-9nhs/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/pipeline-q2-2016)
* [Metadata URL](https://data.sfgov.org/api/views/g5sr-9nhs)
* Id = g5sr-9nhs
* Name = SF Development Pipeline 2016 Q2
* Category = Housing and Buildings
* Created = 2016-08-04T23:03:39Z
* Publication Date = 2016-08-15T05:41:53Z
* Rows Updated = 2016-08-15T05:39:33Z

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Department of Building Inspection's Permit Tracking and the Planning Department's Project & Permit Tracking System, processed quarterly.

## Columns

```ls
| Name                 | Field Name           | Data Type     | Render Type   | Schema Type    | Included | 
| ==================== | ==================== | ============= | ============= | ============== | ======== | 
| NEIGHBORHOOD         | neighborhood         | text          | text          | series tag     | Yes      | 
| APN                  | apn                  | text          | text          | series tag     | Yes      | 
| Entitlement          | entitlement          | number        | number        | numeric metric | Yes      | 
| BESTSTAT             | beststat             | text          | text          | series tag     | Yes      | 
| BESTDATE             | bestdate             | calendar_date | calendar_date | time           | Yes      | 
| NAMEADDR             | nameaddr             | text          | text          | series tag     | Yes      | 
| Alias                | alias                | text          | text          | series tag     | Yes      | 
| PLN_CASENO           | pln_caseno           | text          | text          | series tag     | Yes      | 
| BPAPPLNO             | bpapplno             | number        | text          | numeric metric | Yes      | 
| BP_FORM              | bp_form              | number        | number        | numeric metric | Yes      | 
| UNITS                | units                | number        | number        | numeric metric | Yes      | 
| UNITSNET             | unitsnet             | number        | number        | numeric metric | Yes      | 
| AFF                  | aff                  | number        | number        | numeric metric | Yes      | 
| AFFNET               | affnet               | number        | number        | numeric metric | Yes      | 
| SECTION415           | section415           | text          | text          | series tag     | Yes      | 
| SEC415_TENURE        | sec415_ten           | text          | text          | series tag     | Yes      | 
| SENIOR_HSG           | senior_hsg           | number        | number        | numeric metric | Yes      | 
| STUDENT_HSG          | student_hs           | number        | number        | numeric metric | Yes      | 
| ADDITIONS            | additions            | number        | number        | numeric metric | Yes      | 
| NEWCONSTRUCTION      | newconstru           | number        | number        | numeric metric | Yes      | 
| DEMOLITION           | demolition           | number        | number        | numeric metric | Yes      | 
| CHANGEOFUSE          | changeofus           | number        | number        | numeric metric | Yes      | 
| COST                 | cost                 | money         | money         | numeric metric | Yes      | 
| BldgUse              | bldguse              | text          | text          | series tag     | Yes      | 
| TOTAL_GSF            | total_gsf            | number        | number        | numeric metric | Yes      | 
| NET_GSF              | net_gsf              | number        | number        | numeric metric | Yes      | 
| CIE                  | cie                  | number        | number        | numeric metric | Yes      | 
| CIENET               | cienet               | number        | number        | numeric metric | Yes      | 
| MED                  | med                  | number        | number        | numeric metric | Yes      | 
| MEDNET               | mednet               | number        | number        | numeric metric | Yes      | 
| MIPS                 | mips                 | number        | number        | numeric metric | Yes      | 
| MIPSNET              | mipsnet              | number        | number        | numeric metric | Yes      | 
| PDR                  | pdr                  | number        | number        | numeric metric | Yes      | 
| PDRNET               | pdrnet               | number        | number        | numeric metric | Yes      | 
| RET                  | ret                  | number        | number        | numeric metric | Yes      | 
| RETNET               | retnet               | number        | number        | numeric metric | Yes      | 
| VISIT                | visit                | number        | number        | numeric metric | Yes      | 
| VISITNET             | visitnet             | number        | number        | numeric metric | Yes      | 
| HOTELRM              | hotelrm              | number        | number        | numeric metric | Yes      | 
| HOTELRMNET           | hotelrmnet           | number        | number        | numeric metric | Yes      | 
| FirstFiled           | firstfiled           | calendar_date | calendar_date |                | No       | 
| MULTI                | multi                | number        | number        | numeric metric | Yes      | 
| PLN_DESC             | pln_desc             | text          | text          | series tag     | Yes      | 
| DBI_DESC             | dbi_desc             | text          | text          | series tag     | Yes      | 
| PLANNER              | planner              | text          | text          | series tag     | Yes      | 
| EasternNbrhood       | easternnbrhood       | number        | number        | numeric metric | Yes      | 
| PLN_AREA             | pln_area             | text          | text          | series tag     | Yes      | 
| PLN_DISTRICT         | pln_district         | text          | text          | series tag     | Yes      | 
| HEIGHT               | height               | text          | text          | series tag     | Yes      | 
| ZONING_SIM           | zoning_sim           | text          | text          | series tag     | Yes      | 
| ZONING_DISTRICT_NAME | zoning_district_name | text          | text          | series tag     | Yes      | 
| Supervisorial        | supe_dist            | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = firstfiled
Annotation Fields = 
```

## Data Commands

```ls
series e:g5sr-9nhs d:2015-12-17T00:00:00.000Z t:supe_dist="SUPERVISORIAL DISTRICT 10" t:dbi_desc="ERECT 1-STORY, NO BASEMENT, TYPE 5-1, COMMUNITY CENTER.

series e:g5sr-9nhs d:2015-05-08T00:00:00.000Z t:supe_dist="SUPERVISORIAL DISTRICT 11" t:dbi_desc="CONSTRUCT (N) 3-STORY SINGLE FAMILY DWELLING UNIT" t:height=40-X t:pln_district=Ingleside t:neighborhood="Ocean View" t:nameaddr="1 EDGAR AV" t:planner=FLORESVE t:zoning_district_name="RESIDENTIAL- HOUSE, ONE FAMILY" t:zoning_sim=RH-1 t:bldguse="1 FAMILY DWELLING" t:apn="APN 6978069" t:beststat="BP FILED" m:med=0 m:ret=0 m:cienet=0 m:hotelrm=0 m:demolition=0 m:aff=0 m:visit=0 m:pdr=0 m:visitnet=0 m:newconstru=0 m:additions=0 m:mips=0 m:entitlement=0 m:changeofus=0 m:mednet=0 m:bpapplno=201505085755 m:cie=0 m:mipsnet=0 m:cost=300000 m:units=1 m:unitsnet=1 m:easternnbrhood=0 m:total_gsf=0 m:bp_form=1 m:pdrnet=0 m:multi=0 m:student_hs=0 m:senior_hsg=0 m:affnet=0 m:retnet=0 m:hotelrmnet=0 m:net_gsf=0


```

## Meta Commands

```ls
metric m:entitlement p:integer l:Entitlement t:dataTypeName=number

metric m:bpapplno p:long l:BPAPPLNO t:dataTypeName=number

metric m:bp_form p:integer l:BP_FORM t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:unitsnet l:UNITSNET t:dataTypeName=number

metric m:aff p:integer l:AFF t:dataTypeName=number

metric m:affnet l:AFFNET t:dataTypeName=number

metric m:senior_hsg p:integer l:SENIOR_HSG t:dataTypeName=number

metric m:student_hs p:integer l:STUDENT_HSG t:dataTypeName=number

metric m:additions p:integer l:ADDITIONS t:dataTypeName=number

metric m:newconstru p:integer l:NEWCONSTRUCTION t:dataTypeName=number

metric m:demolition p:integer l:DEMOLITION t:dataTypeName=number

metric m:changeofus p:integer l:CHANGEOFUSE t:dataTypeName=number

metric m:total_gsf p:integer l:TOTAL_GSF t:dataTypeName=number

metric m:net_gsf l:NET_GSF t:dataTypeName=number

metric m:cie p:integer l:CIE t:dataTypeName=number

metric m:cienet l:CIENET t:dataTypeName=number

metric m:med p:integer l:MED t:dataTypeName=number

metric m:mednet l:MEDNET t:dataTypeName=number

metric m:mips p:integer l:MIPS t:dataTypeName=number

metric m:mipsnet l:MIPSNET t:dataTypeName=number

metric m:pdr p:integer l:PDR t:dataTypeName=number

metric m:pdrnet l:PDRNET t:dataTypeName=number

metric m:ret p:integer l:RET t:dataTypeName=number

metric m:retnet l:RETNET t:dataTypeName=number

metric m:visit p:integer l:VISIT t:dataTypeName=number

metric m:visitnet l:VISITNET t:dataTypeName=number

metric m:hotelrm p:integer l:HOTELRM t:dataTypeName=number

metric m:hotelrmnet l:HOTELRMNET t:dataTypeName=number

metric m:multi p:integer l:MULTI d:"project with multiple building permits; part of a phased project" t:dataTypeName=number

metric m:easternnbrhood p:integer l:EasternNbrhood t:dataTypeName=number

entity e:g5sr-9nhs l:"SF Development Pipeline 2016 Q2" t:url=https://data.sfgov.org/api/views/g5sr-9nhs

property e:g5sr-9nhs t:meta.view d:2017-03-07T17:13:52.579Z v:id=g5sr-9nhs v:category="Housing and Buildings" v:averageRating=0 v:name="SF Development Pipeline 2016 Q2"

property e:g5sr-9nhs t:meta.view.license d:2017-03-07T17:13:52.579Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:g5sr-9nhs t:meta.view.owner d:2017-03-07T17:13:52.579Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:g5sr-9nhs t:meta.view.tableauthor d:2017-03-07T17:13:52.579Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```