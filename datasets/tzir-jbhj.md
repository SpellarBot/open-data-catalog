# Department Open Data Inventory and Plan Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-open-data-inventory-and-plan-status) |
| Metadata | [Link](https://data.sfgov.org/api/views/tzir-jbhj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tzir-jbhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tzir-jbhj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tzir-jbhj |
| Name | Department Open Data Inventory and Plan Status |
| Category | City Management and Ethics |
| Tags | inventory, publishing plans, open data program |
| Created | 2015-07-13T18:57:52Z |
| Publication Date | 2017-08-14T18:46:04Z |

## Description

This dataset tracks the status of departments as they move through the inventory process. The dataset will be maintained until all departments are complete, at which point tracking of departmental publishing can be done in the companion dataset inventory.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | department_code                 | Department Code                 | text      | text        |
| Yes      | series tag     | department_or_division          | Department or Division          | text      | text        |
| Yes      | series tag     | inventory_status                | Inventory Status                | text      | text        |
| Yes      | series tag     | publishing_plan_status          | Publishing Plan Status          | text      | text        |
| Yes      | numeric metric | target_december_2015            | Target December 2015            | number    | number      |
| Yes      | numeric metric | published_through_december_2015 | Published through December 2015 | number    | number      |
| Yes      | numeric metric | target_june_2016                | Target June 2016                | number    | number      |
| Yes      | numeric metric | published_through_june_2016     | Published Through June 2016     | number    | number      |
| Yes      | numeric metric | target_december_2016            | Target December 2016            | number    | number      |
| Yes      | numeric metric | published_through_december_2016 | Published through December 2016 | number    | number      |
| Yes      | numeric metric | target_december_2017            | Target December 2017            | number    | number      |
| Yes      | numeric metric | published_through_december_2017 | Published Through December 2017 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tzir-jbhj d:2017-08-14T18:45:32.000Z t:department_code=311 t:publishing_plan_status=Complete t:department_or_division=311 t:inventory_status=Complete m:target_december_2016=0 m:target_december_2015=0 m:published_through_june_2016=0 m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:target_december_2017=0 m:published_through_december_2017=0

series e:tzir-jbhj d:2017-08-14T18:45:32.000Z t:department_code=ADP t:publishing_plan_status=Complete t:department_or_division="Adult Probation" t:inventory_status=Complete m:target_december_2016=0 m:target_december_2015=2 m:published_through_june_2016=0 m:target_june_2016=2 m:published_through_december_2015=0 m:published_through_december_2016=0 m:target_december_2017=0 m:published_through_december_2017=0

series e:tzir-jbhj d:2017-08-14T18:45:32.000Z t:department_code=AIR t:publishing_plan_status=Incomplete t:department_or_division=Airport t:inventory_status=Complete m:target_december_2016=0 m:target_december_2015=15 m:published_through_june_2016=5 m:target_june_2016=19 m:published_through_december_2015=4 m:published_through_december_2016=0 m:target_december_2017=0 m:published_through_december_2017=0
```

## Meta Commands

```ls
metric m:target_december_2015 p:integer l:"Target December 2015" d:"The department target set for publishing through end of 2015." t:dataTypeName=number

metric m:published_through_december_2015 p:integer l:"Published through December 2015" d:"Number of datasets published through the end of 2015. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_june_2016 p:integer l:"Target June 2016" d:"The department target set for publishing through end of June 2016" t:dataTypeName=number

metric m:published_through_june_2016 p:integer l:"Published Through June 2016" d:"Number of datasets published through the end of June 2016. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_december_2016 p:integer l:"Target December 2016" d:"The department target set for publishing through end of 2016." t:dataTypeName=number

metric m:published_through_december_2016 p:integer l:"Published through December 2016" d:"Number of datasets published through the end of 2016. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_december_2017 p:integer l:"Target December 2017" d:"The department target set for end of 2017" t:dataTypeName=number

metric m:published_through_december_2017 p:integer l:"Published Through December 2017" d:"The number of datasets published by the department through 2017" t:dataTypeName=number

entity e:tzir-jbhj l:"Department Open Data Inventory and Plan Status" t:url=https://data.sfgov.org/api/views/tzir-jbhj

property e:tzir-jbhj t:meta.view d:2017-09-25T07:26:48.049Z v:averageRating=0 v:name="Department Open Data Inventory and Plan Status" v:id=tzir-jbhj v:category="City Management and Ethics"

property e:tzir-jbhj t:meta.view.license d:2017-09-25T07:26:48.049Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tzir-jbhj t:meta.view.owner d:2017-09-25T07:26:48.049Z v:displayName=OpenData v:id=dbag-6qd9 v:screenName=OpenData

property e:tzir-jbhj t:meta.view.tableauthor d:2017-09-25T07:26:48.049Z v:displayName=OpenData v:roleName=publisher v:id=dbag-6qd9 v:screenName=OpenData
```

## Top Records

```ls
| :updated_at | department_code | department_or_division           | inventory_status | publishing_plan_status | target_december_2015 | published_through_december_2015 | target_june_2016 | published_through_june_2016 | target_december_2016 | published_through_december_2016 | target_december_2017 | published_through_december_2017 | 
| =========== | =============== | ================================ | ================ | ====================== | ==================== | =============================== | ================ | =========================== | ==================== | =============================== | ==================== | =============================== | 
| 1502736332  | 311             | 311                              | Complete         | Complete               | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | ADP             | Adult Probation                  | Complete         | Complete               | 2                    | 0                               | 2                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | AIR             | Airport                          | Complete         | Incomplete             | 15                   | 4                               | 19               | 5                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | ART             | Arts Commission                  | Complete         | Complete               | 1                    | 1                               | 0                | 0                           | 0                    | 0                               | 2                    | 0                               | 
| 1502736332  | AAM             | Asian Art Museum                 | Complete         | Incomplete             | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | ASR             | Assessor-Recorder                | Complete         | Incomplete             | 0                    | 0                               | 1                | 2                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | BOA             | Board of Appeals                 | Complete         | Complete               | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | BOS             | Board of Supervisors             | Complete         | Incomplete             | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | CSS             | Child Support Services           | Complete         | Complete               | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1502736332  | CFC             | Children and Families Commission | Complete         | Incomplete             | 4                    | 0                               | 4                | 0                           | 4                    | 0                               | 0                    | 0                               | 
```