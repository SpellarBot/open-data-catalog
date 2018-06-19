# Final Harvest - Distribution All 10252016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/final-harvest-distribution-all-11182014) |
| Metadata | [Link](https://data.wa.gov/api/views/qb6f-d9a6) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qb6f-d9a6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qb6f-d9a6/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qb6f-d9a6 |
| Name | Final Harvest - Distribution All 10252016 |
| Tags | state-of-the-salmon |
| Created | 2014-11-06T20:38:31Z |
| Publication Date | 2016-10-25T18:13:41Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | esu         | ESU        | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| No       |             | _           | %          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:qb6f-d9a6 d:2016-10-25T18:13:24.000Z t:category=Alaska t:esu="Lower Columbia All Chinook" m:row_number.qb6f-d9a6=1

series e:qb6f-d9a6 d:2016-10-25T18:13:24.000Z t:category=Canada t:esu="Lower Columbia All Chinook" m:row_number.qb6f-d9a6=2

series e:qb6f-d9a6 d:2016-10-25T18:13:24.000Z t:category="S. US Marine" t:esu="Lower Columbia All Chinook" m:row_number.qb6f-d9a6=3
```

## Meta Commands

```ls
metric m:row_number.qb6f-d9a6 p:long l:"Row Number"

entity e:qb6f-d9a6 l:"Final Harvest - Distribution All 10252016" t:url=https://data.wa.gov/api/views/qb6f-d9a6

property e:qb6f-d9a6 t:meta.view v:id=qb6f-d9a6 v:averageRating=0 v:name="Final Harvest - Distribution All 10252016"

property e:qb6f-d9a6 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:qb6f-d9a6 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                                | category         | _ | 
| =========== | ================================== | ================ | = | 
| 1477419204  | Lower Columbia All Chinook         | Alaska           |   | 
| 1477419204  | Lower Columbia All Chinook         | Canada           |   | 
| 1477419204  | Lower Columbia All Chinook         | S. US Marine     |   | 
| 1477419204  | Lower Columbia All Chinook         | River            |   | 
| 1477419204  | Lower Columbia Coho                | Alaska           |   | 
| 1477419204  | Lower Columbia Coho                | Canada           |   | 
| 1477419204  | Lower Columbia Coho                | S. US Marine     |   | 
| 1477419204  | Lower Columbia Coho                | S. US Freshwater |   | 
| 1477419204  | Lower Columbia Fall Bright Chinook | Alaska           |   | 
| 1477419204  | Lower Columbia Fall Bright Chinook | Canada           |   | 
```