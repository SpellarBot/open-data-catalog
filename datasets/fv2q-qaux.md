# San Francisco Development Pipeline 2014 Quarter 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-development-pipeline-q2-2014-f06f7) |
| Metadata | [Link](https://data.sfgov.org/api/views/fv2q-qaux) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fv2q-qaux/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fv2q-qaux/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fv2q-qaux |
| Name | San Francisco Development Pipeline 2014 Quarter 2 |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | pipeline, development, housing, construction |
| Created | 2014-09-12T17:43:20Z |
| Publication Date | 2014-09-12T17:45:55Z |
| Rows Updated | 2014-09-12T17:44:03Z |

## Description

Snapshot of San Francisco Development Pipeline. Tracking of construction and entitlement activity based on data from Dept of Building Inspection's Permit Tracking and the Planning Department's Case Tracking enterprise databases, processed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | block_lot                    | Block Lot                    | text          | text          |
| Yes      | series tag     | planning_neighborhood        | Planning Neighborhood        | text          | text          |
| Yes      | series tag     | best_stat                    | Best Stat                    | text          | text          |
| Yes      | time           | best_date                    | Best Date                    | calendar_date | calendar_date |
| Yes      | numeric metric | units                        | Units                        | number        | number        |
| Yes      | series tag     | planning_project_description | Planning Project Description | text          | text          |
| Yes      | series tag     | dbi_project_description      | DBI Project Description      | text          | text          |
| Yes      | series tag     | zoning_generalized           | Zoning_Generalized           | text          | text          |
| Yes      | series tag     | zoning_simplified            | Zoning_Simplified            | text          | text          |
| Yes      | numeric metric | taz                          | TAZ                          | number        | number        |
| Yes      | numeric metric | total_gsf_commercial         | Total GSF (Commercial)       | number        | number        |
| Yes      | numeric metric | office                       | Office                       | number        | number        |
| Yes      | numeric metric | cult_inst_educ               | Cult, Inst, Educ             | number        | number        |
| Yes      | numeric metric | medical                      | Medical                      | number        | number        |
| Yes      | numeric metric | prod_dist_rep                | Prod, Dist, Rep              | number        | number        |
| Yes      | numeric metric | ret_ent                      | Ret, Ent                     | number        | number        |
| Yes      | numeric metric | visitor                      | Visitor                      | number        | number        |
| Yes      | series tag     | planning_id                  | Planning ID                  | text          | text          |
| Yes      | series tag     | dbi_permit                   | DBI Permit                   | text          | text          |
| No       |                | planning_filed               | Planning Filed               | calendar_date | calendar_date |
| No       |                | dbi_filed                    | DBI Filed                    | calendar_date | calendar_date |
| Yes      | series tag     | heightlimit                  | HEIGHTLIMIT                  | text          | text          |
| Yes      | numeric metric | heightnum                    | HeightNum                    | number        | number        |
| Yes      | series tag     | zoning                       | ZONING                       | text          | text          |
| No       |                | firstfiled                   | FirstFiled                   | calendar_date | calendar_date |
| Yes      | series tag     | objectid                     | ObjectID                     | text          | number        |
| Yes      | series tag     | landuse                      | LANDUSE                      | text          | text          |
| Yes      | series tag     | sort                         | sort                         | text          | text          |
| Yes      | numeric metric | net_added_units              | Net Added Units              | number        | number        |
| Yes      | numeric metric | net_added_sf                 | Net Added SF                 | number        | number        |
| Yes      | numeric metric | net_cult_inst_educ           | Net Cult, Inst, Educ         | number        | number        |
| Yes      | numeric metric | net_medical                  | Net Medical                  | number        | number        |
| Yes      | numeric metric | net_office                   | Net Office                   | number        | number        |
| Yes      | numeric metric | net_prod_dist_rep            | Net Prod, Dist, Rep          | number        | number        |
| Yes      | numeric metric | net_ret_ent                  | Net Ret, Ent                 | number        | number        |
| Yes      | numeric metric | net_visitor                  | Net Visitor                  | number        | number        |
| Yes      | series tag     | planningdistrictscombo       | PlanningDistrictsCombo       | text          | text          |
| Yes      | numeric metric | affordable                   | AFFORDABLE                   | number        | number        |
| Yes      | numeric metric | affordablenet                | AFFORDABLENET                | number        | number        |
| Yes      | numeric metric | entitlementstatus            | EntitlementStatus            | number        | number        |
| Yes      | series tag     | sponsor_firm                 | Sponsor Firm                 | text          | text          |
| Yes      | series tag     | sponsor_name                 | Sponsor Name                 | text          | text          |
| Yes      | series tag     | contactphone                 | CONTACTPHONE                 | text          | text          |
| Yes      | series tag     | fullname                     | FULLNAME                     | text          | text          |
| Yes      | series tag     | contactcity                  | CONTACTCITY                  | text          | text          |
| Yes      | series tag     | contactadd                   | CONTACTADD                   | text          | text          |
```

## Time Field

```ls
Value = best_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = planning_filed,firstfiled,dbi_filed
```

## Data Commands

```ls
series e:fv2q-qaux d:2009-04-08T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort="Planning Filed" t:block_lot=3507042 t:sponsor_firm="Citizens Housing Corporation" t:heightlimit=150-S/200-S t:planning_neighborhood=Downtown t:planning_project_description="THC/Citizens Housing (MOH) proposal for 165-du 100% affordable housing project, 15-story, w/ 18 parking spaces and 3,640-gsf retail at ground level.  Related to Addendum 2003.0262E EIR." t:zoning_generalized=Commercial t:planning_id=2008.0553 t:sponsor_name="Jake Wegmann" t:contactphone=694-5841 t:zoning_simplified=C-3-G t:landuse=Mixres t:objectid=1 t:best_stat="PL FILED" t:contactadd="26 O'Farrell St., Suite 600" t:zoning=C-3-G t:fullname="Jake Wegmann 694-5841" t:contactcity="San Francisco, CA 94108" m:office=0 m:prod_dist_rep=0 m:heightnum=150 m:entitlementstatus=0 m:net_medical=0 m:affordable=165 m:net_office=0 m:units=165 m:visitor=0 m:net_prod_dist_rep=0 m:cult_inst_educ=0 m:taz=608 m:medical=0 m:net_added_sf=3640 m:ret_ent=3640 m:net_ret_ent=3640 m:total_gsf_commercial=3640 m:net_cult_inst_educ=0 m:net_added_units=165 m:affordablenet=165 m:net_visitor=0

series e:fv2q-qaux d:2013-02-28T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort="Planning Filed" t:block_lot=0331001A t:sponsor_firm="229 Ellis Street, LLC" t:heightlimit=80-130-T t:planning_neighborhood=Downtown t:planning_project_description="Interior structural improvements and addition of 4 stories to existing 3-story building. Revised application rec'd 7/25/11: reduced addition to 3 stories, total 77.5' in ht, 14 res units (11,720 sf), and 8,685 sf retail. Revised drawings rec'd 3/7/13: 18 res units (14,668 sf) and 5,704 sf retail." t:zoning_generalized="Mixed Use" t:planning_id=2009.0343 t:sponsor_name="Michael Wilk" t:contactphone=415-362-8900 t:zoning_simplified=RC-4 t:landuse=Mixres t:objectid=3 t:best_stat="PL Filed" t:contactadd="229 Ellis Street" t:zoning=RC-4 t:fullname="Michael Wilk 415-362-8900" t:contactcity="San Francisco, CA 94102" m:office=12460 m:taz=678 m:net_added_sf=0 m:heightnum=80 m:entitlementstatus=0 m:total_gsf_commercial=12460 m:net_added_units=4 m:units=7 m:net_office=0

series e:fv2q-qaux d:2014-06-17T00:00:00.000Z t:planningdistrictscombo=Downtown t:sort=Construction t:block_lot=3722027 t:sponsor_firm=SFMOMA t:heightlimit=320-I/500-I t:planning_neighborhood=Downtown t:planning_project_description="Expansion of SFMOMA to SE with 40,000-sf gallery wing at Natoma Street, acquisition and replacement of Heald College building on Howard Street with 62,000-sf new construction for back-of-house and admin functions, vacation of portion of Hunt Alley, and accomodation of W Hotel porte-cochere to continue through back of Heald site to Natoma Street. No new parking or loading for single building six story addition, 101,710-gsf." t:zoning_generalized=Commercial t:planning_id=2009.0291 t:dbi_permit=201211093897 t:sponsor_name="Ikuko Satoda" t:zoning_simplified=C-3-S t:landuse=CIE t:objectid=6 t:best_stat=CONSTRUCTION t:contactadd="151 Third Street" t:zoning=C-3-S t:fullname="Ikuko Satoda" t:contactcity="San Francisco, CA 94103" m:office=0 m:cult_inst_educ=298378 m:taz=743 m:net_added_sf=66685 m:heightnum=320 m:entitlementstatus=-1 m:total_gsf_commercial=298378 m:net_cult_inst_educ=101710 m:units=0 m:net_office=-35025
```

## Meta Commands

```ls
metric m:units p:integer l:Units t:dataTypeName=number

metric m:taz p:integer l:TAZ t:dataTypeName=number

metric m:total_gsf_commercial p:integer l:"Total GSF (Commercial)" t:dataTypeName=number

metric m:office p:integer l:Office t:dataTypeName=number

metric m:cult_inst_educ p:integer l:"Cult, Inst, Educ" t:dataTypeName=number

metric m:medical p:integer l:Medical t:dataTypeName=number

metric m:prod_dist_rep p:integer l:"Prod, Dist, Rep" t:dataTypeName=number

metric m:ret_ent p:integer l:"Ret, Ent" t:dataTypeName=number

metric m:visitor p:integer l:Visitor t:dataTypeName=number

metric m:heightnum p:integer l:HeightNum t:dataTypeName=number

metric m:net_added_units l:"Net Added Units" t:dataTypeName=number

metric m:net_added_sf l:"Net Added SF" t:dataTypeName=number

metric m:net_cult_inst_educ l:"Net Cult, Inst, Educ" t:dataTypeName=number

metric m:net_medical l:"Net Medical" t:dataTypeName=number

metric m:net_office l:"Net Office" t:dataTypeName=number

metric m:net_prod_dist_rep l:"Net Prod, Dist, Rep" t:dataTypeName=number

metric m:net_ret_ent l:"Net Ret, Ent" t:dataTypeName=number

metric m:net_visitor l:"Net Visitor" t:dataTypeName=number

metric m:affordable p:integer l:AFFORDABLE t:dataTypeName=number

metric m:affordablenet l:AFFORDABLENET t:dataTypeName=number

metric m:entitlementstatus l:EntitlementStatus t:dataTypeName=number

entity e:fv2q-qaux l:"San Francisco Development Pipeline 2014 Quarter 2" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/fv2q-qaux

property e:fv2q-qaux t:meta.view v:id=fv2q-qaux v:category="Housing and Buildings" v:averageRating=0 v:name="San Francisco Development Pipeline 2014 Quarter 2" v:attribution="San Francisco Planning Department"

property e:fv2q-qaux t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fv2q-qaux t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:fv2q-qaux t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```