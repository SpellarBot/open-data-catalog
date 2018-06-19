# Pet Data - 2016 Pets Fostered

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-pets-fostered) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/qpfe-9x7r) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/qpfe-9x7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/qpfe-9x7r/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | qpfe-9x7r |
| Name | Pet Data - 2016 Pets Fostered |
| Category | Pets |
| Created | 2015-12-11T16:19:49Z |
| Publication Date | 2017-01-18T16:51:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | month         | Month         | text      | text        |
| Yes      | numeric metric | pets_fostered | Pets Fostered | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qpfe-9x7r d:2016-01-01T00:00:00.000Z t:month=Jan m:pets_fostered=48

series e:qpfe-9x7r d:2016-01-01T00:00:00.000Z t:month=Mar m:pets_fostered=37

series e:qpfe-9x7r d:2016-01-01T00:00:00.000Z t:month=Feb m:pets_fostered=37
```

## Meta Commands

```ls
metric m:pets_fostered p:integer l:"Pets Fostered" t:dataTypeName=number

entity e:qpfe-9x7r l:"Pet Data - 2016 Pets Fostered" t:url=https://data.kingcounty.gov/api/views/qpfe-9x7r

property e:qpfe-9x7r t:meta.view v:id=qpfe-9x7r v:category=Pets v:averageRating=0 v:name="Pet Data - 2016 Pets Fostered"

property e:qpfe-9x7r t:meta.view.license v:name="Public Domain"

property e:qpfe-9x7r t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:qpfe-9x7r t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | pets_fostered | 
| ===== | ============= | 
| Jan   | 48            | 
| Mar   | 37            | 
| Feb   | 37            | 
| Apr   | 78            | 
| May   | 159           | 
| Jun   | 215           | 
| Jul   | 211           | 
| Aug   | 149           | 
| Sep   | 164           | 
| Oct   | 152           | 
```