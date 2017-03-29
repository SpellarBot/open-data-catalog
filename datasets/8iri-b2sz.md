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
| Yes      | series tag     | supervisor          | SUPERVISOR          | text          | number        |
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
series e:8iri-b2sz d:2005-11-15T00:00:00.000Z t:height=40-X t:app_no=20000112908 t:supervisor=7 t:action="CFC ISSUED" t:pln_district_name="Inner Sunset" t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 7" t:st_name=KIRKHAM t:zoning_sim=RH-2 t:zoning_districtname="RESIDENTIAL- HOUSE, TWO FAMILY" t:apn="APN 1855052" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORY 2 FAMILY DWELLING UNIT" m:netunits_c=2 m:aff_hsg=0 m:form=2 m:st_num=507 m:units=0

series e:8iri-b2sz d:2005-03-08T00:00:00.000Z t:height=40-X t:app_no=200002293001 t:supervisor=1 t:action="CFC ISSUED" t:pln_district_name=Richmond t:st_type=AV t:supdist="SUPERVISORIAL DISTRICT 1" t:st_name=02ND t:zoning_sim=RM-1 t:zoning_districtname="RESIDENTIAL- MIXED, LOW DENSITY" t:apn="APN 1433062" t:yr_qtr=2005_Q1 t:bp_descript="ERECT A THREE STORY THREE UNIT RESIDENTIAL BLDG" m:netunits_c=3 m:aff_hsg=0 m:form=2 m:st_num=330 m:units=0

series e:8iri-b2sz d:2005-12-06T00:00:00.000Z t:height=65-X t:app_no=200003073664 t:supervisor=10 t:action="CFC ISSUED" t:pln_district_name=Mission t:st_type=ST t:supdist="SUPERVISORIAL DISTRICT 10" t:st_name=24TH t:zoning_sim=NCT t:zoning_districtname="24TH-MISSION NEIGHBORHOOD COMMERCIAL TRANSIT" t:apn="APN 4264025" t:yr_qtr=2005_Q4 t:bp_descript="ERECT 4 STORIES, 6 UNITS DWELLING APARTMENTS" m:netunits_c=6 m:aff_hsg=0 m:form=2 m:st_num=2637 m:units=0
```

## Meta Commands

```ls
metric m:st_num p:integer l:ST_NUM t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:netunits_c p:integer l:NETUNITS_C t:dataTypeName=number

metric m:aff_hsg p:integer l:AFF_HSG t:dataTypeName=number

metric m:form p:integer l:FORM t:dataTypeName=number

entity e:8iri-b2sz l:"Housing Balance March 2016" t:url=https://data.sfgov.org/api/views/8iri-b2sz

property e:8iri-b2sz t:meta.view v:id=8iri-b2sz v:category="Housing and Buildings" v:averageRating=0 v:name="Housing Balance March 2016"

property e:8iri-b2sz t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8iri-b2sz t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:8iri-b2sz t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| st_num | st_name   | st_type | apn         | units | netunits_c | aff_hsg | aff_target | app_no       | form | ext_use | prop_use | action               | action_date         | bp_descript                                                                             | staff | year | yr_qtr  | pln_district_name | supdist                   | supervisor | height | zoning_sim | zoning_districtname                          | 
| ====== | ========= | ======= | =========== | ===== | ========== | ======= | ========== | ============ | ==== | ======= | ======== | ==================== | =================== | ======================================================================================= | ===== | ==== | ======= | ================= | ========================= | ========== | ====== | ========== | ============================================ | 
| 507    | KIRKHAM   | ST      | APN 1855052 | 0     | 2          | 0       |            | 20000112908  | 2    |         |          | CFC ISSUED           | 2005-11-15T00:00:00 | ERECT 4 STORY 2 FAMILY DWELLING UNIT                                                    |       | 2005 | 2005_Q4 | Inner Sunset      | SUPERVISORIAL DISTRICT 7  | 7          | 40-X   | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY               | 
| 330    | 02ND      | AV      | APN 1433062 | 0     | 3          | 0       |            | 200002293001 | 2    |         |          | CFC ISSUED           | 2005-03-08T00:00:00 | ERECT A THREE STORY THREE UNIT RESIDENTIAL BLDG                                         |       | 2005 | 2005_Q1 | Richmond          | SUPERVISORIAL DISTRICT 1  | 1          | 40-X   | RM-1       | RESIDENTIAL- MIXED, LOW DENSITY              | 
| 2637   | 24TH      | ST      | APN 4264025 | 0     | 6          | 0       |            | 200003073664 | 2    |         |          | CFC ISSUED           | 2005-12-06T00:00:00 | ERECT 4 STORIES, 6 UNITS DWELLING APARTMENTS                                            |       | 2005 | 2005_Q4 | Mission           | SUPERVISORIAL DISTRICT 10 | 10         | 65-X   | NCT        | 24TH-MISSION NEIGHBORHOOD COMMERCIAL TRANSIT | 
| 1350   | THOMAS    | AV      | APN 4791037 | 0     | 1          | 0       |            | 200005160089 | 2    |         |          | CFC ISSUED           | 2005-02-25T00:00:00 | ERECT A THREE STORY SINGLE FAMILY DWELLING                                              |       | 2005 | 2005_Q1 | South Bayshore    | SUPERVISORIAL DISTRICT 10 | 10         | 40-X   | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY               | 
| 1352   | THOMAS    | AV      | APN 4791036 | 0     | 1          | 0       |            | 200005160095 | 2    |         |          | CFC ISSUED           | 2005-02-25T00:00:00 | ERECT A TWO STORIES SINGLE FAMILY DWELLING                                              |       | 2005 | 2005_Q1 | South Bayshore    | SUPERVISORIAL DISTRICT 10 | 10         | 40-X   | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY               | 
| 318    | 27TH      | ST      | APN 6579009 | 0     | -1         | 0       |            | 200007074508 | 6    |         |          | FINAL INSPECT/APPRVD | 2005-02-01T00:00:00 | DEMOLISH A ONE STORY SINGLE FAMILY DWELLING                                             |       | 2005 | 2005_Q1 | Central           | SUPERVISORIAL DISTRICT 8  | 8          | 40-X   | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY               | 
| 1117   | OCEAN     | AV      | APN 6944041 | 0     | 9          | 0       |            | 200007256060 | 2    |         |          | OK                   | 2005-12-31T00:00:00 | ERECT 4 STORIES OF 9 DWELLING UNITS.                                                    |       | 2005 | 2005_Q4 | Ingleside         | SUPERVISORIAL DISTRICT 7  | 7          | 45-X   | NCT        | OCEAN AVENUE NEIGHBORHOOD COMMERCIAL TRANSIT | 
| 2837   | GREENWICH | ST      | APN 0941029 | 0     | 1          | 0       |            | 200008077151 | 2    |         |          | CFC ISSUED           | 2005-09-02T00:00:00 | ERECT THREE STORY SINGLE FAMILY DWELLING                                                |       | 2005 | 2005_Q3 | Marina            | SUPERVISORIAL DISTRICT 2  | 2          | 40-X   | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY               | 
| 626    | 29TH      | ST      | APN 7536009 | 0     | 3          | 0       |            | 200008107566 | 2    |         |          | CFC ISSUED           | 2005-05-20T00:00:00 | ERECT ONE-FAMILY DWELLING UNIT, ONE 4-STORIES, TYPE-V STRUCTURE.                        |       | 2005 | 2005_Q2 | Central           | SUPERVISORIAL DISTRICT 8  | 8          | 40-X   | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY               | 
| 125    | 03RD      | ST      | APN 3722082 | 0     | 93         | 0       | MOD        | 200008309233 | 1    |         |          | PRE-FINAL            | 2005-09-29T00:00:00 | SITE WORK AT STREET LEVEL OUTSIDE OF BLDG PROPERTY LINES-HORIZONTAL & VERTICAL ADDITION |       | 2005 | 2005_Q3 | Downtown          | SUPERVISORIAL DISTRICT 6  | 6          | 500-I  | C-3-O      | DOWNTOWN- OFFICE                             | 
```