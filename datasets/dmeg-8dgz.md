# Old Style Speed Bumps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/old-style-speed-bumps) |
| Metadata | [Link](https://data.sfgov.org/api/views/dmeg-8dgz) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dmeg-8dgz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dmeg-8dgz/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dmeg-8dgz |
| Name | Old Style Speed Bumps |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | speed bumps |
| Created | 2016-08-18T20:52:10Z |
| Publication Date | 2016-10-12T00:49:39Z |

## Description

Location of "old style" speed bumps.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | object_id        | Object ID        | text      | number      |
| Yes      | series tag  | street_name      | Street Name      | text      | text        |
| Yes      | series tag  | from_street      | From Street      | text      | text        |
| Yes      | series tag  | to_street        | To Street        | text      | text        |
| Yes      | series tag  | cnn_id           | CNN ID           | text      | number      |
| No       |             | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = last_edited_date
```

## Data Commands

```ls
series e:dmeg-8dgz d:2017-04-15T16:41:35.000Z t:to_street="5TH ST END" t:street_name="5TH AVE" t:cnn_id=275000 t:from_street="LAKE ST" m:row_number.dmeg-8dgz=1

series e:dmeg-8dgz d:2017-04-15T16:41:35.000Z t:to_street="7TH AVE END" t:street_name="7TH AVE" t:cnn_id=349000 t:from_street="LAKE ST" m:row_number.dmeg-8dgz=2

series e:dmeg-8dgz d:2017-04-15T16:41:35.000Z t:to_street="21ST AVE END" t:street_name="21ST AVE" t:cnn_id=1071000 t:from_street="LAKE ST" m:row_number.dmeg-8dgz=3
```

## Meta Commands

```ls
metric m:row_number.dmeg-8dgz p:long l:"Row Number"

entity e:dmeg-8dgz l:"Old Style Speed Bumps" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/dmeg-8dgz

property e:dmeg-8dgz t:meta.view v:id=dmeg-8dgz v:category=Transportation v:attributionLink=http://sfgov.org/ v:averageRating=0 v:name="Old Style Speed Bumps" v:attribution="City and County of San Francisco"

property e:dmeg-8dgz t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dmeg-8dgz t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:dmeg-8dgz t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | street_name | from_street       | to_street       | cnn_id  | last_edited_date | 
| =========== | ========= | =========== | ================= | =============== | ======= | ================ | 
| 1492274495  |           | 5TH AVE     | LAKE ST           | 5TH ST END      | 275000  |                  | 
| 1492274495  |           | 7TH AVE     | LAKE ST           | 7TH AVE END     | 349000  |                  | 
| 1492274495  |           | 21ST AVE    | LAKE ST           | 21ST AVE END    | 1071000 |                  | 
| 1492274495  |           | 21ST ST     | GUERRERO ST       | VALENCIA ST     | 1113000 |                  | 
| 1492274495  |           | ATHENS ST   | MADISON ST        | PERU AVE        | 2531000 |                  | 
| 1492274495  |           | BALDWIN CT  | OAKDALE AVE       | BALDWIN CT END  | 2697000 |                  | 
| 1492274495  |           | BEACON ST   | MIGUEL ST         | DIAMOND ST      | 2861000 |                  | 
| 1492274495  |           | BERTHA LN   | HUDSON AVE        | HARBOR RD       | 2958000 |                  | 
| 1492274495  |           | BOCANA ST   | HOLLY PARK CIRCLE | ELLERT ST       | 3007000 |                  | 
| 1492274495  |           | CASHMERE ST | HUDSON AVE        | CASHMERE ST END | 3760201 |                  | 
```