# Recycle Collection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recycle-collection) |
| Metadata | [Link](https://data.ct.gov/api/views/2zji-5rpa) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2zji-5rpa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2zji-5rpa/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2zji-5rpa |
| Name | Recycle Collection |
| Category | Government |
| Tags | recycle collection |
| Created | 2015-07-16T14:58:11Z |
| Publication Date | 2015-07-16T15:00:12Z |

## Description

Recycle Collection Routes

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| No       |             | id          | ID          | text      | number      |
| Yes      | series tag  | street_name | Street Name | text      | text        |
| Yes      | series tag  | recycling   | RECYCLING   | text      | text        |
| Yes      | series tag  | range       | RANGE       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:2zji-5rpa d:2015-07-16T07:58:21.000Z t:recycling=WEDNESDAY t:street_name="ABEL AVE" m:row_number.2zji-5rpa=1

series e:2zji-5rpa d:2015-07-16T07:58:21.000Z t:recycling=TUESDAY t:street_name="ABERDEEN ST" m:row_number.2zji-5rpa=2

series e:2zji-5rpa d:2015-07-16T07:58:21.000Z t:recycling=TUESDAY t:street_name="ACOSTA ST" m:row_number.2zji-5rpa=3
```

## Meta Commands

```ls
metric m:row_number.2zji-5rpa p:long l:"Row Number"

entity e:2zji-5rpa l:"Recycle Collection" t:url=https://data.ct.gov/api/views/2zji-5rpa

property e:2zji-5rpa t:meta.view v:id=2zji-5rpa v:category=Government v:averageRating=0 v:name="Recycle Collection"

property e:2zji-5rpa t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:2zji-5rpa t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| :updated_at | id | street_name  | recycling | range | 
| =========== | == | ============ | ========= | ===== | 
| 1437033501  | 1  | ABEL AVE     | WEDNESDAY |       | 
| 1437033501  | 2  | ABERDEEN ST  | TUESDAY   |       | 
| 1437033501  | 3  | ACOSTA ST    | TUESDAY   |       | 
| 1437033501  | 4  | ACRE VIEW DR | FRIDAY    |       | 
| 1437033501  | 5  | ADAMS AVE    | TUESDAY   |       | 
| 1437033501  | 6  | AKBAR RD     | THURSDAY  |       | 
| 1437033501  | 7  | ALBERT PL    | THURSDAY  |       | 
| 1437033501  | 8  | ALBIN RD     | MONDAY    |       | 
| 1437033501  | 9  | ALDEN ST     | TUESDAY   |       | 
| 1437033501  | 10 | ALEXANDRA DR | FRIDAY    |       | 
```