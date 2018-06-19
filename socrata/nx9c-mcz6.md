# Pet Data - 2017 Adoptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2017-adoptions) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/nx9c-mcz6) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/nx9c-mcz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/nx9c-mcz6/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | nx9c-mcz6 |
| Name | Pet Data - 2017 Adoptions |
| Created | 2017-01-18T17:02:25Z |
| Publication Date | 2017-03-03T19:40:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | month      | Month     | text      | text        |
| Yes      | numeric metric | adoptions  | Adoptions | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nx9c-mcz6 d:2017-01-01T00:00:00.000Z t:month=Mar m:adoptions=0

series e:nx9c-mcz6 d:2017-01-01T00:00:00.000Z t:month=Apr m:adoptions=0

series e:nx9c-mcz6 d:2017-01-01T00:00:00.000Z t:month=May m:adoptions=0
```

## Meta Commands

```ls
metric m:adoptions p:integer l:Adoptions t:dataTypeName=number

entity e:nx9c-mcz6 l:"Pet Data - 2017 Adoptions" t:url=https://data.kingcounty.gov/api/views/nx9c-mcz6

property e:nx9c-mcz6 t:meta.view v:id=nx9c-mcz6 v:averageRating=0 v:name="Pet Data - 2017 Adoptions"

property e:nx9c-mcz6 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:nx9c-mcz6 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | adoptions | 
| ===== | ========= | 
| Mar   | 0         | 
| Apr   | 0         | 
| May   | 0         | 
| Jun   | 0         | 
| Jul   | 0         | 
| Aug   | 0         | 
| Sep   | 0         | 
| Oct   | 0         | 
| Nov   | 0         | 
| Dec   | 0         | 
```