# Final Harvest -- Distribution 01042013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/final-harvest-distribution-01042013-7fb79) |
| Metadata | [Link](https://data.wa.gov/api/views/qgrr-phnh) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qgrr-phnh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qgrr-phnh/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qgrr-phnh |
| Name | Final Harvest -- Distribution 01042013 |
| Tags | state-of-the-salmon |
| Created | 2013-01-04T01:15:43Z |
| Publication Date | 2013-01-04T22:53:17Z |

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
series e:qgrr-phnh d:2013-01-04T14:52:31.000Z t:category=Alaska t:esu="Snake River Spring/Summer Chinook" m:row_number.qgrr-phnh=1

series e:qgrr-phnh d:2013-01-04T14:52:31.000Z t:category=Canada t:esu="Snake River Spring/Summer Chinook" m:row_number.qgrr-phnh=2

series e:qgrr-phnh d:2013-01-04T14:52:31.000Z t:category="S. US Ocean" t:esu="Snake River Spring/Summer Chinook" m:row_number.qgrr-phnh=3
```

## Meta Commands

```ls
metric m:row_number.qgrr-phnh p:long l:"Row Number"

entity e:qgrr-phnh l:"Final Harvest -- Distribution 01042013" t:url=https://data.wa.gov/api/views/qgrr-phnh

property e:qgrr-phnh t:meta.view v:id=qgrr-phnh v:averageRating=0 v:name="Final Harvest -- Distribution 01042013"

property e:qgrr-phnh t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:qgrr-phnh t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                               | category    | _   | 
| =========== | ================================= | =========== | === | 
| 1357311151  | Snake River Spring/Summer Chinook | Alaska      | 0   | 
| 1357311151  | Snake River Spring/Summer Chinook | Canada      | 0   | 
| 1357311151  | Snake River Spring/Summer Chinook | S. US Ocean | 0   | 
| 1357311151  | Snake River Spring/Summer Chinook | River       | 100 | 
| 1357311151  | Snake River Fall Chinook          | Alaska      | 2   | 
| 1357311151  | Snake River Fall Chinook          | Canada      | 20  | 
| 1357311151  | Snake River Fall Chinook          | S. US Ocean | 31  | 
| 1357311151  | Snake River Fall Chinook          | River       | 47  | 
| 1357311151  | Upper Columbia Spring Chinook     | Alaska      | 0   | 
| 1357311151  | Upper Columbia Spring Chinook     | Canada      | 0   | 
```