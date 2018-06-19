# Pet Data - 2015 Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-intakes) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/92q4-apgq) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/92q4-apgq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/92q4-apgq/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 92q4-apgq |
| Name | Pet Data - 2015 Intakes |
| Category | Government |
| Created | 2015-02-06T19:59:31Z |
| Publication Date | 2016-02-03T17:33:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | month          | Month          | text      | text        |
| Yes      | numeric metric | animal_intakes | Animal Intakes | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:92q4-apgq d:2015-01-01T00:00:00.000Z t:month=Jan m:animal_intakes=304

series e:92q4-apgq d:2015-01-01T00:00:00.000Z t:month=Feb m:animal_intakes=265

series e:92q4-apgq d:2015-01-01T00:00:00.000Z t:month=Mar m:animal_intakes=322
```

## Meta Commands

```ls
metric m:animal_intakes p:integer l:"Animal Intakes" t:dataTypeName=number

entity e:92q4-apgq l:"Pet Data - 2015 Intakes" t:url=https://data.kingcounty.gov/api/views/92q4-apgq

property e:92q4-apgq t:meta.view v:id=92q4-apgq v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Intakes"

property e:92q4-apgq t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:92q4-apgq t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animal_intakes | 
| ===== | ============== | 
| Jan   | 304            | 
| Feb   | 265            | 
| Mar   | 322            | 
| Apr   | 333            | 
| May   | 341            | 
| Jun   | 543            | 
| Jul   | 511            | 
| Aug   | 573            | 
| Sep   | 500            | 
| Oct   | 509            | 
```