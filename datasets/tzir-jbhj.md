# Department Open Data Inventory and Plan Status

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/tzir-jbhj/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/department-open-data-inventory-and-plan-status)
* [Metadata URL](https://data.sfgov.org/api/views/tzir-jbhj)
* Id = tzir-jbhj
* Name = Department Open Data Inventory and Plan Status
* Category = City Management and Ethics
* Tags = [inventory, publishing plans, open data program]
* Created = 2015-07-13T18:57:52Z
* Publication Date = 2017-02-14T19:27:31Z
* Rows Updated = 2017-02-14T19:27:15Z

## Description

This dataset tracks the status of departments as they move through the inventory process. The dataset will be maintained until all departments are complete, at which point tracking of departmental publishing can be done in the companion dataset inventory.

## Columns

```ls
| Name                            | Field Name                      | Data Type | Render Type | Schema Type    | Included | 
| =============================== | =============================== | ========= | =========== | ============== | ======== | 
| updated_at                      | :updated_at                     | meta_data | meta_data   | time           | No       | 
| Department Code                 | department_code                 | text      | text        | series tag     | Yes      | 
| Department or Division          | department_or_division          | text      | text        | series tag     | Yes      | 
| Inventory Status                | inventory_status                | text      | text        | series tag     | Yes      | 
| Publishing Plan Status          | publishing_plan_status          | text      | text        | series tag     | Yes      | 
| Target December 2015            | target_december_2015            | number    | number      | numeric metric | Yes      | 
| Published through December 2015 | published_through_december_2015 | number    | number      | numeric metric | Yes      | 
| Target June 2016                | target_june_2016                | number    | number      | numeric metric | Yes      | 
| Published Through June 2016     | published_through_june_2016     | number    | number      | numeric metric | Yes      | 
| Target December 2016            | target_december_2016            | number    | number      | numeric metric | Yes      | 
| Published through December 2016 | published_through_december_2016 | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Complete t:publishing_plan_status=Complete t:department_or_division=311 t:department_code=311 m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Incomplete t:publishing_plan_status=Incomplete t:department_or_division="Academy of Sciences" t:department_code=SCI m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Complete t:publishing_plan_status=Incomplete t:department_or_division="Adult Probation" t:department_code=ADP m:target_june_2016=2 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=2 m:target_december_2016=0
```

## Meta Commands

```ls
metric m:target_december_2015 p:integer l:"Target December 2015" d:"The department target set for publishing through end of 2015." t:dataTypeName=number

metric m:published_through_december_2015 p:integer l:"Published through December 2015" d:"Number of datasets published through the end of 2015. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_june_2016 p:integer l:"Target June 2016" d:"The department target set for publishing through end of June 2016" t:dataTypeName=number

metric m:published_through_june_2016 p:integer l:"Published Through June 2016" d:"Number of datasets published through the end of June 2016. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_december_2016 p:integer l:"Target December 2016" d:"The department target set for publishing through end of 2016." t:dataTypeName=number

metric m:published_through_december_2016 p:integer l:"Published through December 2016" d:"Number of datasets published through the end of 2016. This is variable until the end of the publishing period." t:dataTypeName=number

entity e:tzir-jbhj l:"Department Open Data Inventory and Plan Status" t:url=https://data.sfgov.org/api/views/tzir-jbhj

property e:tzir-jbhj t:meta.view d:2017-03-07T17:26:24.804Z v:id=tzir-jbhj v:category="City Management and Ethics" v:averageRating=0 v:name="Department Open Data Inventory and Plan Status"

property e:tzir-jbhj t:meta.view.license d:2017-03-07T17:26:24.804Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tzir-jbhj t:meta.view.owner d:2017-03-07T17:26:24.804Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:tzir-jbhj t:meta.view.tableauthor d:2017-03-07T17:26:24.804Z v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```