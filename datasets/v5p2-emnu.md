# San Francisco Development Pipeline 2012 Quarter 1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-e6bc8) |
| Metadata | [Link](https://data.sfgov.org/api/views/v5p2-emnu) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/v5p2-emnu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/v5p2-emnu/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | v5p2-emnu |
| Name | San Francisco Development Pipeline 2012 Quarter 1 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Created | 2012-04-12T21:27:43Z |
| Publication Date | 2012-04-13T06:29:52Z |
| Rows Updated | 2012-04-12T21:27:53Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | block_lot                    | block lot                    | text      | text        |
| Yes      | series tag     | planning_neighborhood        | planning neighborhood        | text      | text        |
| Yes      | series tag     | project_status               | project status               | text      | text        |
| Yes      | time           | project_date                 | project date                 | date      | date        |
| Yes      | numeric metric | units                        | units                        | number    | number      |
| Yes      | series tag     | planning_project_description | planning project description | text      | text        |
| Yes      | series tag     | dbi_project_description      | dbi project description      | text      | text        |
| Yes      | series tag     | zoning_generalized           | zoning_generalized           | text      | text        |
| Yes      | series tag     | zoning_simplified            | zoning_simplified            | text      | text        |
| Yes      | numeric metric | taz                          | taz                          | number    | number      |
| Yes      | numeric metric | total_gsf_commercial         | total gsf (commercial)       | number    | number      |
| Yes      | numeric metric | office                       | office                       | number    | number      |
| Yes      | numeric metric | cult_inst_educ               | cult, inst, educ             | number    | number      |
| Yes      | numeric metric | medical                      | medical                      | number    | number      |
| Yes      | numeric metric | prod_dist_rep                | prod, dist, rep              | number    | number      |
| Yes      | numeric metric | ret_ent                      | ret, ent                     | number    | number      |
| Yes      | numeric metric | visitor                      | visitor                      | number    | number      |
| Yes      | numeric metric | dbi_permit                   | dbi permit                   | number    | number      |
| No       |                | planning_filed               | planning filed               | date      | date        |
| No       |                | dbi_filed                    | dbi filed                    | date      | date        |
| Yes      | series tag     | landuse                      | landuse                      | text      | text        |
| Yes      | series tag     | status_group                 | status group                 | text      | text        |
| Yes      | numeric metric | net_added_units              | net added units              | number    | number      |
| Yes      | numeric metric | net_added_sf                 | net added sf                 | number    | number      |
| Yes      | numeric metric | net_cult_inst_educ           | net cult, inst, educ         | number    | number      |
| Yes      | numeric metric | net_medical                  | net medical                  | number    | number      |
| Yes      | numeric metric | net_office                   | net office                   | number    | number      |
| Yes      | numeric metric | net_prod_dist_rep            | net prod, dist, rep          | number    | number      |
| Yes      | numeric metric | net_ret_ent                  | net ret, ent                 | number    | number      |
| Yes      | numeric metric | net_visitor                  | net visitor                  | number    | number      |
| Yes      | numeric metric | sitearea                     | sitearea                     | number    | number      |
| Yes      | series tag     | block                        | block                        | text      | text        |
| Yes      | series tag     | lot                          | lot                          | text      | text        |
| Yes      | series tag     | zoning                       | zoning                       | text      | text        |
| Yes      | series tag     | heightlimit                  | heightlimit                  | text      | text        |
| Yes      | numeric metric | supdist                      | supdist                      | number    | number      |
```

## Time Field

```ls
Value = project_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = planning_filed,dbi_filed
```

## Data Commands

```ls
series e:v5p2-emnu d:2009-11-03T08:00:00.000Z t:project_status="BP REINSTATED" t:zoning_generalized="Mixed Use" t:block_lot=4172053 t:lot=053 t:zoning_simplified=NCT-2 t:block=4172 t:status_group="BP Approved/Issued/Re-Instated" t:landuse=Resident t:heightlimit=40-X t:planning_neighborhood="Central Waterfront" t:zoning=NCT-2 t:dbi_project_description="ERECT A FOUR STORY EIGHT UNIT RESIDENTIAL BLDG WITH COML" m:office=0 m:prod_dist_rep=0 m:supdist=10 m:net_medical=0 m:net_office=0 m:units=8 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=521 m:medical=0 m:net_added_sf=0 m:dbi_permit=9902819 m:sitearea=6090 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=8 m:net_visitor=0

series e:v5p2-emnu d:2007-04-11T07:00:00.000Z t:project_status="BP ISSUED" t:block_lot=0492025 t:block=0492 t:status_group="BP Approved/Issued/Re-Instated" t:planning_neighborhood=Marina t:heightlimit=40-X t:zoning_generalized="Mixed Use" t:planning_project_description="The proposed project involves the demolition of an 8,630 gsf, two-story (over grade parking) 30-room motel and construction of a 49,001gsf, 4-story hotel containing 97 rooms." t:lot=025 t:zoning_simplified=NC-3 t:landuse=Visitor t:zoning=NC-3 t:dbi_project_description="ERECT A NEW 4 STORY 89 UNIT TOURIST HOTEL W/ GARAGE" m:office=0 m:prod_dist_rep=0 m:supdist=2 m:net_medical=0 m:net_office=0 m:units=0 m:visitor=40370 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=819 m:medical=0 m:net_added_sf=40370 m:dbi_permit=200606023107 m:sitearea=13612 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=40370 m:net_cult_inst_educ=0 m:net_added_units=0 m:net_visitor=40370

series e:v5p2-emnu d:2007-11-28T08:00:00.000Z t:project_status="BP ISSUED" t:block_lot=2676030 t:block=2676 t:status_group="BP Approved/Issued/Re-Instated" t:planning_neighborhood="Inner Sunset" t:heightlimit=40-X t:zoning_generalized=Residential t:planning_project_description="Construct a new single-family dwelling on a vacant parcel in an RH-1(D) (Residential, House, One-Family, Detached) District and a 40-X Height and Bulk District." t:lot=030 t:zoning_simplified=RH-1(D) t:landuse=Resident t:zoning=RH-1(D) t:dbi_project_description="ERECT 3 STORIES, 1 DWELLING UNIT WITH 1 BASEMENT BLDG." m:office=0 m:prod_dist_rep=0 m:supdist=7 m:net_medical=0 m:net_office=0 m:units=1 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=545 m:medical=0 m:net_added_sf=0 m:dbi_permit=200212042761 m:sitearea=6418 m:ret_ent=0 m:net_ret_ent=0 m:total_gsf_commercial=0 m:net_cult_inst_educ=0 m:net_added_units=1 m:net_visitor=0
```

## Meta Commands

```ls
metric m:units p:integer l:units t:dataTypeName=number

metric m:taz p:integer l:taz t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"total gsf (commercial)" t:dataTypeName=number

metric m:office p:integer l:office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"cult, inst, educ" t:dataTypeName=number

metric m:medical p:integer l:medical t:dataTypeName=number

metric m:prod_dist_rep p:integer l:"prod, dist, rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"ret, ent" t:dataTypeName=number

metric m:visitor p:integer l:visitor t:dataTypeName=number

metric m:dbi_permit p:long l:"dbi permit" t:dataTypeName=number

metric m:net_added_units p:integer l:"net added units" t:dataTypeName=number

metric m:net_added_sf p:integer l:"net added sf" t:dataTypeName=number

metric m:net_cult_inst_educ p:integer l:"net cult, inst, educ" t:dataTypeName=number

metric m:net_medical p:integer l:"net medical" t:dataTypeName=number

metric m:net_office p:integer l:"net office" t:dataTypeName=number

metric m:net_prod_dist_rep p:integer l:"net prod, dist, rep" t:dataTypeName=number

metric m:net_ret_ent p:integer l:"net ret, ent" t:dataTypeName=number

metric m:net_visitor p:integer l:"net visitor" t:dataTypeName=number

metric m:sitearea p:integer l:sitearea t:dataTypeName=number

metric m:supdist p:integer l:supdist t:dataTypeName=number

entity e:v5p2-emnu l:"San Francisco Development Pipeline 2012 Quarter 1" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/v5p2-emnu

property e:v5p2-emnu t:meta.view v:id=v5p2-emnu v:category="Housing and Buildings" v:attributionLink=http://sfplanning.org v:averageRating=0 v:name="San Francisco Development Pipeline 2012 Quarter 1" v:attribution="San Francisco Planning Department"

property e:v5p2-emnu t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:v5p2-emnu t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:v5p2-emnu t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```