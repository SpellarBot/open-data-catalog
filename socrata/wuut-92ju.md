# Statewide Harvest

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-harvest-1897f) |
| Metadata | [Link](https://data.wa.gov/api/views/wuut-92ju) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/wuut-92ju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/wuut-92ju/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | wuut-92ju |
| Name | Statewide Harvest |
| Created | 2012-12-05T05:39:01Z |
| Publication Date | 2012-12-05T05:39:54Z |

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
series e:wuut-92ju d:2012-12-04T21:39:03.000Z t:esu="Upper Columbia Spring Chinook" m:success=83

series e:wuut-92ju d:2012-12-04T21:39:03.000Z t:esu="Snake River Spring/Summer Chinook" m:success=88

series e:wuut-92ju d:2012-12-04T21:39:03.000Z t:esu="Snake River Fall Chinook" m:success=91
```

## Meta Commands

```ls
metric m:success p:integer l:"% Success" t:dataTypeName=number

entity e:wuut-92ju l:"Statewide Harvest" t:url=https://data.wa.gov/api/views/wuut-92ju

property e:wuut-92ju t:meta.view v:id=wuut-92ju v:averageRating=0 v:name="Statewide Harvest"

property e:wuut-92ju t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:wuut-92ju t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                                | success | 
| =========== | ================================== | ======= | 
| 1354657143  | Upper Columbia Spring Chinook      | 83      | 
| 1354657143  | Snake River Spring/Summer Chinook  | 88      | 
| 1354657143  | Snake River Fall Chinook           | 91      | 
| 1354657143  | Lower Columbia Fall Tule Chinook   | 78      | 
| 1354657143  | Lower Columbia Fall Bright Chinook | 73      | 
| 1354657143  | Lower Columbia Spring Chinook      | 100     | 
| 1354657143  | Lower Columbia Coho                | 83      | 
| 1354657143  | Juan de Fuca Chinook               | 97      | 
| 1354657143  | Hood Canald Chinook                | 95      | 
| 1354657143  | Central/South Puget Sound Chinook  | 70      | 
```