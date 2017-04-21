# Stop Signs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stop-signs) |
| Metadata | [Link](https://data.sfgov.org/api/views/wmdf-5y3x) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wmdf-5y3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wmdf-5y3x/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wmdf-5y3x |
| Name | Stop Signs |
| Category | Transportation |
| Tags | signals, stop signs, mta |
| Created | 2016-04-28T16:24:49Z |
| Publication Date | 2016-05-21T00:20:33Z |

## Description

Location of stop signs for operational and planning purposes.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | object_id        | Object ID        | text      | number      |
| Yes      | series tag  | street           | Street           | text      | text        |
| Yes      | series tag  | cross_street     | Cross Street     | text      | text        |
| Yes      | series tag  | direction        | Direction        | text      | text        |
| Yes      | series tag  | facing_street    | Facing Street    | text      | text        |
| Yes      | series tag  | distance         | Distance         | text      | text        |
| Yes      | series tag  | cnn_segment_id   | CNN Segment ID   | text      | number      |
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
series e:wmdf-5y3x d:2017-04-15T16:38:19.000Z t:cnn_segment_id=23253000 t:cross_street=ULLOA t:street="28TH AVE" t:object_id=1 t:facing_street=SB m:row_number.wmdf-5y3x=1

series e:wmdf-5y3x d:2017-04-15T16:38:19.000Z t:cnn_segment_id=27921000 t:cross_street=ORTEGA t:street="46TH AVE" t:object_id=2 t:facing_street=NB m:row_number.wmdf-5y3x=2

series e:wmdf-5y3x d:2017-04-15T16:38:19.000Z t:cnn_segment_id=27921000 t:cross_street=ORTEGA t:street="46TH AVE" t:object_id=3 t:facing_street=SB m:row_number.wmdf-5y3x=3
```

## Meta Commands

```ls
metric m:row_number.wmdf-5y3x p:long l:"Row Number"

entity e:wmdf-5y3x l:"Stop Signs" t:url=https://data.sfgov.org/api/views/wmdf-5y3x

property e:wmdf-5y3x t:meta.view v:id=wmdf-5y3x v:category=Transportation v:averageRating=0 v:name="Stop Signs"

property e:wmdf-5y3x t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wmdf-5y3x t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wmdf-5y3x t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | object_id | street   | cross_street | direction | facing_street | distance | cnn_segment_id | last_edited_date | 
| =========== | ========= | ======== | ============ | ========= | ============= | ======== | ============== | ================ | 
| 1492274299  | 1         | 28TH AVE | ULLOA        |           | SB            |          | 23253000       |                  | 
| 1492274299  | 2         | 46TH AVE | ORTEGA       |           | NB            |          | 27921000       |                  | 
| 1492274299  | 3         | 46TH AVE | ORTEGA       |           | SB            |          | 27921000       |                  | 
| 1492274299  | 4         | 42ND AVE | ORTEGA       |           | SB            |          | 27764000       |                  | 
| 1492274299  | 5         | 44TH AVE | ORTEGA       |           | EB            |          | 27768000       |                  | 
| 1492274299  | 6         | 44TH AVE | ORTEGA       |           | WB            |          | 27768000       |                  | 
| 1492274299  | 7         | ITALY    | LISBON       |           | NB            |          | 21728000       |                  | 
| 1492274299  | 8         | HURON    | LAWRENCE     |           | NB            |          | 21553000       |                  | 
| 1492274299  | 9         | HURON    | LAWRENCE     |           | SB            |          | 21553000       |                  | 
| 1492274299  | 10        | 23RD AVE | KIRKHAM      |           | EB            |          | 27410000       |                  | 
```