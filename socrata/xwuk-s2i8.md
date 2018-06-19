# Tax Returns Processed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-returns-processed-055ba) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xwuk-s2i8) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xwuk-s2i8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xwuk-s2i8/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xwuk-s2i8 |
| Name | Tax Returns Processed |
| Created | 2013-01-06T07:50:13Z |
| Publication Date | 2013-01-06T07:53:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | mo          | mo         | number    | number      |
| No       |                | wk          | wk         | number    | number      |
| No       |                | yr          | yr         | number    | number      |
| Yes      | series tag     | type        | type       | text      | text        |
| Yes      | numeric metric | paper       | paper      | number    | number      |
| Yes      | numeric metric | electronic  | electronic | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mo,wk,yr
```

## Data Commands

```ls
series e:xwuk-s2i8 d:2013-01-05T23:50:15.000Z t:type=income m:paper=9002 m:electronic=6

series e:xwuk-s2i8 d:2013-01-05T23:50:15.000Z t:type=business m:paper=20775 m:electronic=1416

series e:xwuk-s2i8 d:2013-01-05T23:50:15.000Z t:type=other m:paper=0 m:electronic=210
```

## Meta Commands

```ls
metric m:paper p:integer l:paper t:dataTypeName=number

metric m:electronic p:integer l:electronic t:dataTypeName=number

entity e:xwuk-s2i8 l:"Tax Returns Processed" t:url=https://data.hawaii.gov/api/views/xwuk-s2i8

property e:xwuk-s2i8 t:meta.view v:id=xwuk-s2i8 v:averageRating=0 v:name="Tax Returns Processed"

property e:xwuk-s2i8 t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:xwuk-s2i8 t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | mo | wk | yr | type     | paper | electronic | 
| =========== | == | == | == | ======== | ===== | ========== | 
| 1357429815  | 1  | 1  | 11 | income   | 9002  | 6          | 
| 1357429815  | 1  | 1  | 11 | business | 20775 | 1416       | 
| 1357429815  | 1  | 1  | 11 | other    | 0     | 210        | 
| 1357429815  | 1  | 1  | 11 | misc     | 0     | 0          | 
| 1357429815  | 1  | 8  | 11 | income   | 2260  | 0          | 
| 1357429815  | 1  | 8  | 11 | business | 16705 | 0          | 
| 1357429815  | 1  | 8  | 11 | other    | 0     | 102        | 
| 1357429815  | 1  | 8  | 11 | misc     | 0     | 0          | 
| 1357429815  | 1  | 15 | 11 | income   | 19    | 4          | 
| 1357429815  | 1  | 15 | 11 | business | 98    | 42         | 
```