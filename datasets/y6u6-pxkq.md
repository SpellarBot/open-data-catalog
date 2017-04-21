# Pet Data - 2017 Returns to Owner

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2017-returns-to-owner) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/y6u6-pxkq) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/y6u6-pxkq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/y6u6-pxkq/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | y6u6-pxkq |
| Name | Pet Data - 2017 Returns to Owner |
| Created | 2017-01-18T21:12:24Z |
| Publication Date | 2017-03-03T19:42:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | month         | Month         | text      | text        |
| Yes      | numeric metric | pets_returned | Pets Returned | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y6u6-pxkq d:2017-01-01T00:00:00.000Z t:month=Mar m:pets_returned=0

series e:y6u6-pxkq d:2017-01-01T00:00:00.000Z t:month=Apr m:pets_returned=0

series e:y6u6-pxkq d:2017-01-01T00:00:00.000Z t:month=May m:pets_returned=0
```

## Meta Commands

```ls
metric m:pets_returned p:integer l:"Pets Returned" t:dataTypeName=number

entity e:y6u6-pxkq l:"Pet Data - 2017 Returns to Owner" t:url=https://data.kingcounty.gov/api/views/y6u6-pxkq

property e:y6u6-pxkq t:meta.view v:id=y6u6-pxkq v:averageRating=0 v:name="Pet Data - 2017 Returns to Owner"

property e:y6u6-pxkq t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:y6u6-pxkq t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | pets_returned | 
| ===== | ============= | 
| Mar   | 0             | 
| Apr   | 0             | 
| May   | 0             | 
| Jun   | 0             | 
| Jul   | 0             | 
| Aug   | 0             | 
| Sep   | 0             | 
| Oct   | 0             | 
| Nov   | 0             | 
| Dec   | 0             | 
```