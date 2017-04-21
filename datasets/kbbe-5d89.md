# Pet Data - 2014 Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2014-intakes-ade82) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kbbe-5d89) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kbbe-5d89/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kbbe-5d89/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kbbe-5d89 |
| Name | Pet Data - 2014 Intakes |
| Attribution | King County |
| Created | 2014-03-26T16:09:57Z |
| Publication Date | 2015-01-12T16:40:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | month          | Month          | text      | text        |
| Yes      | numeric metric | animal_intakes | Animal Intakes | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kbbe-5d89 d:2014-01-01T00:00:00.000Z t:month=Jan m:animal_intakes=417

series e:kbbe-5d89 d:2014-01-01T00:00:00.000Z t:month=Feb m:animal_intakes=326

series e:kbbe-5d89 d:2014-01-01T00:00:00.000Z t:month=Mar m:animal_intakes=301
```

## Meta Commands

```ls
metric m:animal_intakes p:integer l:"Animal Intakes" t:dataTypeName=number

entity e:kbbe-5d89 l:"Pet Data - 2014 Intakes" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/kbbe-5d89

property e:kbbe-5d89 t:meta.view v:id=kbbe-5d89 v:attributionLink=http://www.kingcounty.gov/pets v:averageRating=0 v:name="Pet Data - 2014 Intakes" v:attribution="King County"

property e:kbbe-5d89 t:meta.view.license v:name="Public Domain"

property e:kbbe-5d89 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:kbbe-5d89 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animal_intakes | 
| ===== | ============== | 
| Jan   | 417            | 
| Feb   | 326            | 
| Mar   | 301            | 
| Apr   | 388            | 
| May   | 494            | 
| Jun   | 588            | 
| Jul   | 625            | 
| Aug   | 619            | 
| Sep   | 557            | 
| Oct   | 536            | 
```