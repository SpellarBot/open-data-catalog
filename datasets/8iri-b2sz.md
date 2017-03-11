# Housing Balance March 2016

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/8iri-b2sz/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/housing-balance-march-2016)
* Id = 8iri-b2sz
* Name = Housing Balance March 2016
* Category = Housing and Buildings
* Tags = [development, housing, residential]
* Created = 2016-05-25T21:39:23Z
* Publication Date = 2016-05-25T21:44:21Z
* Rows Updated = 2016-05-25T21:39:54Z

## Description

The Board of Supervisors passed Ordinance No. 53-15 requiring the San Francisco Planning Department to monitor and report bi-annually on the Housing Balance between new market rate housing and new affordable housing production.

## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | =================== | ============= | ============= | ============== | ======== | 
| ST_NUM              | st_num              | number        | text          | numeric metric | Yes      | 
| ST_NAME             | st_name             | text          | text          | series tag     | Yes      | 
| ST_TYPE             | st_type             | text          | text          | series tag     | Yes      | 
| APN                 | apn                 | text          | text          | series tag     | Yes      | 
| UNITS               | units               | number        | number        | numeric metric | Yes      | 
| NETUNITS_C          | netunits_c          | number        | number        | numeric metric | Yes      | 
| AFF_HSG             | aff_hsg             | number        | number        | numeric metric | Yes      | 
| AFF_TARGET          | aff_target          | text          | text          | series tag     | Yes      | 
| APP_NO              | app_no              | text          | text          | series tag     | Yes      | 
| FORM                | form                | number        | number        | numeric metric | Yes      | 
| EXT_USE             | ext_use             | text          | text          | series tag     | Yes      | 
| PROP_USE            | prop_use            | text          | text          | series tag     | Yes      | 
| ACTION              | action              | text          | text          | series tag     | Yes      | 
| ACTION_DATE         | action_date         | calendar_date | calendar_date | time           | Yes      | 
| BP_DESCRIPT         | bp_descript         | text          | text          | series tag     | Yes      | 
| STAFF               | staff               | text          | text          | series tag     | Yes      | 
| YEAR                | year                | number        | number        |                | No       | 
| YR_QTR              | yr_qtr              | text          | text          | series tag     | Yes      | 
| PLN_DISTRICT_NAME   | pln_district_name   | text          | text          | series tag     | Yes      | 
| SUPDIST             | supdist             | text          | text          | series tag     | Yes      | 
| SUPERVISOR          | supervisor          | number        | number        | numeric metric | Yes      | 
| HEIGHT              | height              | text          | text          | series tag     | Yes      | 
| ZONING_SIM          | zoning_sim          | text          | text          | series tag     | Yes      | 
| ZONING_DISTRICTNAME | zoning_districtname | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = action_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = year
Annotation Fields = 
```

## Data Commands

```ls
series e:8iri-b2sz d:2005-11-15T00:00:00.000Z t:height=40-X t:app_no=20000112908 t:action="CFC ISSUED" t:pln_district_name="Inner Sunset" t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 7" t:st_name=KIRKHAM t:zoning_sim=RH-2 t:zoning_districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:apn="APN 1855052" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORY 2 FAMILY DWELLING UNIT" m:netunits_c=2 m:aff_hsg=0 m:form=2 m:st_num=507 m:supervisor=7 m:units=0

series e:8iri-b2sz d:2005-03-08T00:00:00.000Z t:height=40-X t:app_no=200002293001 t:action="CFC ISSUED" t:pln_district_name=Richmond t:st_type=AV t:supdist="SUPERVISORIAL DISTRICT 1" t:st_name=02ND t:zoning_sim=RM-1 t:zoning_districtname="RESIDENTIAL- MIXED, LOW DENSITY" t:apn="APN 1433062" t:yr_qtr=2005_Q1 t:bp_descript="ERECT A THREE STORY THREE UNIT RESIDENTIAL BLDG" m:netunits_c=3 m:aff_hsg=0 m:form=2 m:st_num=330 m:supervisor=1 m:units=0

series e:8iri-b2sz d:2005-12-06T00:00:00.000Z t:height=65-X t:app_no=200003073664 t:action="CFC ISSUED" t:pln_district_name=Mission t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 10" t:st_name=24TH t:zoning_sim=NCT t:zoning_districtname="24TH-MISSION NEIGHBORHOOD COMMERCIAL TRANSIT" t:apn="APN 4264025" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORIES, 6 UNITS DWELLING APARTMENTS" m:netunits_c=6 m:aff_hsg=0 m:form=2 m:st_num=2637 m:supervisor=10 m:units=0
```

## Meta Commands

```ls
200101240457" t:action=OK t:pln_district_name="Outer Sunset" t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 4" t:st_name=19TH t:zoning_sim=RH-2 t:zoning_districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:apn="APN 2056007" t:yr_qtr=2005_Q4 t:bp_descript="TO ERECT 3 STORY 2 FAMILY DWELLING" m:netunits_c=2 m:aff_hsg=0 m:form=2 m:st_num=1835 m:supervisor=4 m:units=0

metric m:st_num p:integer l:ST_NUM t:dataTypeName=number

metric m:units l:UNITS t:dataTypeName=number

metric m:netunits_c l:NETUNITS_C t:dataTypeName=number

metric m:aff_hsg l:AFF_HSG t:dataTypeName=number

metric m:form p:integer l:FORM t:dataTypeName=number

metric m:supervisor p:integer l:SUPERVISOR t:dataTypeName=number

entity e:8iri-b2sz l:"Housing Balance March 2016" t:url=https://data.sfgov.org/api/views/8iri-b2sz

property e:8iri-b2sz t:meta.view d:2017-03-03T14:27:02.316Z v:id=8iri-b2sz v:category="Housing and Buildings" v:averageRating=0 v:name="Housing Balance March 2016"

property e:8iri-b2sz t:meta.view.license d:2017-03-03T14:27:02.316Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8iri-b2sz t:meta.view.owner d:2017-03-03T14:27:02.316Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:8iri-b2sz t:meta.view.tableauthor d:2017-03-03T14:27:02.316Z v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```