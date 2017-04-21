# Snake Harvest

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snake-harvest-debbf) |
| Metadata | [Link](https://data.wa.gov/api/views/ft5h-ftmv) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ft5h-ftmv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ft5h-ftmv/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ft5h-ftmv |
| Name | Snake Harvest |
| Created | 2012-12-05T06:33:37Z |
| Publication Date | 2012-12-05T06:40:28Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | esu         | ESU        | text      | text        |
| Yes      | numeric metric | success     | % Success  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ft5h-ftmv d:2012-12-04T22:39:59.000Z t:esu="Snake River Spring/Summer Chinook" m:success=88

series e:ft5h-ftmv d:2012-12-04T22:39:59.000Z t:esu="Snake River Fall Chinook" m:success=91
```

## Meta Commands

```ls
metric m:success p:integer l:"% Success" t:dataTypeName=number

entity e:ft5h-ftmv l:"Snake Harvest" t:url=https://data.wa.gov/api/views/ft5h-ftmv

property e:ft5h-ftmv t:meta.view v:id=ft5h-ftmv v:averageRating=0 v:name="Snake Harvest"

property e:ft5h-ftmv t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:ft5h-ftmv t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                               | success | 
| =========== | ================================= | ======= | 
| 1354660799  | Snake River Spring/Summer Chinook | 88      | 
| 1354660799  | Snake River Fall Chinook          | 91      | 
```