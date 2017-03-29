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
| Publication Date | 2017-03-24T17:45:24Z |

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
series e:tzir-jbhj d:2017-03-24T17:44:56.000Z t:inventory_status=Complete t:publishing_plan_status=Complete t:department_code=311 t:department_or_division=311 m:target_december_2017=0 m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_december_2017=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-03-24T17:44:56.000Z t:inventory_status=Incomplete t:publishing_plan_status=Incomplete t:department_code=SCI t:department_or_division="Academy of Sciences" m:target_december_2017=0 m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_december_2017=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-03-24T17:44:56.000Z t:inventory_status=Complete t:publishing_plan_status=Complete t:department_code=ADP t:department_or_division="Adult Probation" m:target_december_2017=0 m:target_june_2016=2 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_december_2017=0 m:published_through_june_2016=0 m:target_december_2015=2 m:target_december_2016=0
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

property e:tzir-jbhj t:meta.view v:id=tzir-jbhj v:category="City Management and Ethics" v:averageRating=0 v:name="Department Open Data Inventory and Plan Status"

property e:tzir-jbhj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tzir-jbhj t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:tzir-jbhj t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | department_code | department_or_division | inventory_status | publishing_plan_status | target_december_2015 | published_through_december_2015 | target_june_2016 | published_through_june_2016 | target_december_2016 | published_through_december_2016 | target_december_2017 | published_through_december_2017 | 
| =========== | =============== | ====================== | ================ | ====================== | ==================== | =============================== | ================ | =========================== | ==================== | =============================== | ==================== | =============================== | 
| 1490377496  | 311             | 311                    | Complete         | Complete               | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | SCI             | Academy of Sciences    | Incomplete       | Incomplete             | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | ADP             | Adult Probation        | Complete         | Complete               | 2                    | 0                               | 2                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | AIR             | Airport                | Complete         | Incomplete             | 15                   | 4                               | 19               | 5                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | ART             | Arts Commission        | Complete         | Complete               | 1                    | 1                               | 0                | 0                           | 0                    | 0                               | 2                    | 0                               | 
| 1490377496  | AAM             | Asian Art Museum       | Complete         | Incomplete             | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | ASR             | Assessor-Recorder      | Complete         | Incomplete             | 0                    | 0                               | 1                | 2                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | BOA             | Board of Appeals       | Complete         | Complete               | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | BOS             | Board of Supervisors   | Complete         | Incomplete             | 0                    | 0                               | 0                | 0                           | 0                    | 0                               | 0                    | 0                               | 
| 1490377496  | DBI             | Building Inspection    | Incomplete       | Incomplete             | 0                    | 0                               | 0                | 6                           | 0                    | 0                               | 0                    | 0                               | 
```