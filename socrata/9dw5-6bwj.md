# Pet Data - 2014 Foster

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2014-foster-3624d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/9dw5-6bwj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/9dw5-6bwj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/9dw5-6bwj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 9dw5-6bwj |
| Name | Pet Data - 2014 Foster |
| Created | 2014-03-26T16:17:58Z |
| Publication Date | 2015-01-12T16:39:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | month            | Month            | text      | text        |
| Yes      | numeric metric | animals_fostered | Animals Fostered | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9dw5-6bwj d:2014-01-01T00:00:00.000Z t:month=May m:animals_fostered=146

series e:9dw5-6bwj d:2014-01-01T00:00:00.000Z t:month=Jan m:animals_fostered=49

series e:9dw5-6bwj d:2014-01-01T00:00:00.000Z t:month=Feb m:animals_fostered=20
```

## Meta Commands

```ls
metric m:animals_fostered p:integer l:"Animals Fostered" t:dataTypeName=number

entity e:9dw5-6bwj l:"Pet Data - 2014 Foster" t:url=https://data.kingcounty.gov/api/views/9dw5-6bwj

property e:9dw5-6bwj t:meta.view v:id=9dw5-6bwj v:averageRating=0 v:name="Pet Data - 2014 Foster"

property e:9dw5-6bwj t:meta.view.license v:name="Public Domain"

property e:9dw5-6bwj t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:9dw5-6bwj t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_fostered | 
| ===== | ================ | 
| May   | 146              | 
| Jan   | 49               | 
| Feb   | 20               | 
| Mar   | 26               | 
| Apr   | 104              | 
| Jun   | 123              | 
| Jul   | 171              | 
| Aug   | 136              | 
| Sep   | 167              | 
| Oct   | 122              | 
```