# Statewide Harvest-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-harvest-2-a2c51) |
| Metadata | [Link](https://data.wa.gov/api/views/2e6z-nsu4) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/2e6z-nsu4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/2e6z-nsu4/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 2e6z-nsu4 |
| Name | Statewide Harvest-2 |
| Created | 2012-12-05T06:27:21Z |
| Publication Date | 2012-12-05T06:29:20Z |

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
series e:2e6z-nsu4 d:2012-12-04T22:27:23.000Z t:esu="Upper Columbia Spring Chinook" m:success=83

series e:2e6z-nsu4 d:2012-12-04T22:27:23.000Z t:esu="Snake River Spring/Summer Chinook" m:success=88

series e:2e6z-nsu4 d:2012-12-04T22:27:23.000Z t:esu="Snake River Fall Chinook" m:success=91
```

## Meta Commands

```ls
metric m:success p:integer l:"% Success" t:dataTypeName=number

entity e:2e6z-nsu4 l:"Statewide Harvest-2" t:url=https://data.wa.gov/api/views/2e6z-nsu4

property e:2e6z-nsu4 t:meta.view v:id=2e6z-nsu4 v:averageRating=0 v:name="Statewide Harvest-2"

property e:2e6z-nsu4 t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:2e6z-nsu4 t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                                | success | 
| =========== | ================================== | ======= | 
| 1354660043  | Upper Columbia Spring Chinook      | 83      | 
| 1354660043  | Snake River Spring/Summer Chinook  | 88      | 
| 1354660043  | Snake River Fall Chinook           | 91      | 
| 1354660043  | Lower Columbia Fall Tule Chinook   | 78      | 
| 1354660043  | Lower Columbia Fall Bright Chinook | 73      | 
| 1354660043  | Lower Columbia Spring Chinook      | 100     | 
| 1354660043  | Lower Columbia Coho                | 83      | 
| 1354660043  | Juan de Fuca Chinook               | 97      | 
| 1354660043  | Hood Canald Chinook                | 95      | 
| 1354660043  | Central/South Puget Sound Chinook  | 70      | 
```