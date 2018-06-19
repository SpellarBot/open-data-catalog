# Golf Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/golf-location) |
| Metadata | [Link](https://data.austintexas.gov/api/views/rd5n-3pmq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/rd5n-3pmq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/rd5n-3pmq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | rd5n-3pmq |
| Name | Golf Location |
| Attribution | City of Austin |
| Created | 2015-04-14T20:38:44Z |
| Publication Date | 2015-04-14T20:40:44Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | golf_courses | GOLF COURSES | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rd5n-3pmq d:2015-04-14T13:38:58.000Z t:golf_courses="The Leadbetter  Golf Academy Central" m:row_number.rd5n-3pmq=1

series e:rd5n-3pmq d:2015-04-14T13:38:58.000Z t:golf_courses="Grey Rock Golf Club" m:row_number.rd5n-3pmq=2

series e:rd5n-3pmq d:2015-04-14T13:38:58.000Z t:golf_courses="Butler Pitch and Putt" m:row_number.rd5n-3pmq=3
```

## Meta Commands

```ls
metric m:row_number.rd5n-3pmq p:long l:"Row Number"

entity e:rd5n-3pmq l:"Golf Location" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/rd5n-3pmq

property e:rd5n-3pmq t:meta.view v:id=rd5n-3pmq v:attributionLink=http://www.austintexas.gov/department/golf v:averageRating=0 v:name="Golf Location" v:attribution="City of Austin"

property e:rd5n-3pmq t:meta.view.license v:name="Public Domain"

property e:rd5n-3pmq t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:rd5n-3pmq t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| :updated_at | golf_courses                         | 
| =========== | ==================================== | 
| 1429018738  | The Leadbetter  Golf Academy Central | 
| 1429018738  | Grey Rock Golf Club                  | 
| 1429018738  | Butler Pitch and Putt                | 
| 1429018738  | Jimmy Clay Golf Course               | 
| 1429018738  | Lions Municipal Golf Course          | 
| 1429018738  | Morris Williams Golf Course          | 
| 1429018738  | Hancock Golf Course                  | 
| 1429018738  | Roy Kizer Golf Course                | 
```