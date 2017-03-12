# Housing Balance March 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-balance-march-2016) |
| Metadata | [Link](https://data.sfgov.org/api/views/8iri-b2sz) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/8iri-b2sz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/8iri-b2sz/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 8iri-b2sz |
| Name | Housing Balance March 2016 |
| Category | Housing and Buildings |
| Tags | development, housing, residential |
| Created | 2016-05-25T21:39:23Z |
| Publication Date | 2016-05-25T21:44:21Z |
| Rows Updated | 2016-05-25T21:39:54Z |

## Description

The Board of Supervisors passed Ordinance No. 53-15 requiring the San Francisco Planning Department to monitor and report bi-annually on the Housing Balance between new market rate housing and new affordable housing production.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | numeric metric | st_num              | ST_NUM              | number        | text          |
| Yes      | series tag     | st_name             | ST_NAME             | text          | text          |
| Yes      | series tag     | st_type             | ST_TYPE             | text          | text          |
| Yes      | series tag     | apn                 | APN                 | text          | text          |
| Yes      | numeric metric | units               | UNITS               | number        | number        |
| Yes      | numeric metric | netunits_c          | NETUNITS_C          | number        | number        |
| Yes      | numeric metric | aff_hsg             | AFF_HSG             | number        | number        |
| Yes      | series tag     | aff_target          | AFF_TARGET          | text          | text          |
| Yes      | series tag     | app_no              | APP_NO              | text          | text          |
| Yes      | numeric metric | form                | FORM                | number        | number        |
| Yes      | series tag     | ext_use             | EXT_USE             | text          | text          |
| Yes      | series tag     | prop_use            | PROP_USE            | text          | text          |
| Yes      | series tag     | action              | ACTION              | text          | text          |
| Yes      | time           | action_date         | ACTION_DATE         | calendar_date | calendar_date |
| Yes      | series tag     | bp_descript         | BP_DESCRIPT         | text          | text          |
| Yes      | series tag     | staff               | STAFF               | text          | text          |
| No       |                | year                | YEAR                | number        | number        |
| Yes      | series tag     | yr_qtr              | YR_QTR              | text          | text          |
| Yes      | series tag     | pln_district_name   | PLN_DISTRICT_NAME   | text          | text          |
| Yes      | series tag     | supdist             | SUPDIST             | text          | text          |
| Yes      | numeric metric | supervisor          | SUPERVISOR          | number        | number        |
| Yes      | series tag     | height              | HEIGHT              | text          | text          |
| Yes      | series tag     | zoning_sim          | ZONING_SIM          | text          | text          |
| Yes      | series tag     | zoning_districtname | ZONING_DISTRICTNAME | text          | text          |
```

## Time Field

```ls
Value = action_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:8iri-b2sz d:2005-11-15T00:00:00.000Z t:height=40-X t:app_no=20000112908 t:action="CFC ISSUED" t:pln_district_name="Inner Sunset" t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 7" t:st_name=KIRKHAM t:zoning_sim=RH-2 t:zoning_districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:apn="APN 1855052" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORY 2 FAMILY DWELLING UNIT" m:netunits_c=2 m:aff_hsg=0 m:form=2 m:st_num=507 m:supervisor=7 m:units=0

series e:8iri-b2sz d:2005-03-08T00:00:00.000Z t:height=40-X t:app_no=200002293001 t:action="CFC ISSUED" t:pln_district_name=Richmond t:st_type=AV t:supdist="SUPERVISORIAL DISTRICT 1" t:st_name=02ND t:zoning_sim=RM-1 t:zoning_districtname="RESIDENTIAL- MIXED, LOW DENSITY" t:apn="APN 1433062" t:yr_qtr=2005_Q1 t:bp_descript="ERECT A THREE STORY THREE UNIT RESIDENTIAL BLDG" m:netunits_c=3 m:aff_hsg=0 m:form=2 m:st_num=330 m:supervisor=1 m:units=0

series e:8iri-b2sz d:2005-12-06T00:00:00.000Z t:height=65-X t:app_no=200003073664 t:action="CFC ISSUED" t:pln_district_name=Mission t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 10" t:st_name=24TH t:zoning_sim=NCT t:zoning_districtname="24TH-MISSION NEIGHBORHOOD COMMERCIAL TRANSIT" t:apn="APN 4264025" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORIES, 6 UNITS DWELLING APARTMENTS" m:netunits_c=6 m:aff_hsg=0 m:form=2 m:st_num=2637 m:supervisor=10 m:units=0
```

## Meta Commands

```ls
metric m:st_num p:integer l:ST_NUM t:dataTypeName=number

metric m:units l:UNITS t:dataTypeName=number

metric m:netunits_c l:NETUNITS_C t:dataTypeName=number

metric m:aff_hsg l:AFF_HSG t:dataTypeName=number

metric m:form p:integer l:FORM t:dataTypeName=number

metric m:supervisor p:integer l:SUPERVISOR t:dataTypeName=number

entity e:8iri-b2sz l:"Housing Balance March 2016" t:url=https://data.sfgov.org/api/views/8iri-b2sz

property e:8iri-b2sz t:meta.view v:id=8iri-b2sz v:category="Housing and Buildings" v:averageRating=0 v:name="Housing Balance March 2016"

property e:8iri-b2sz t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8iri-b2sz t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:8iri-b2sz t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```