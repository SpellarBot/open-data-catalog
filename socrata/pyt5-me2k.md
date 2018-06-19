# Pet Data - 2016 Animal Intakes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-animal-intakes) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/pyt5-me2k) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/pyt5-me2k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/pyt5-me2k/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | pyt5-me2k |
| Name | Pet Data - 2016 Animal Intakes |
| Attribution | King County |
| Category | Pets |
| Created | 2015-12-11T16:08:27Z |
| Publication Date | 2017-01-18T16:43:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | month          | Month          | text      | text        |
| Yes      | numeric metric | animal_intakes | Animal Intakes | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pyt5-me2k d:2016-01-01T00:00:00.000Z t:month=Jan m:animal_intakes=323

series e:pyt5-me2k d:2016-01-01T00:00:00.000Z t:month=Mar m:animal_intakes=435

series e:pyt5-me2k d:2016-01-01T00:00:00.000Z t:month=Feb m:animal_intakes=392
```

## Meta Commands

```ls
metric m:animal_intakes p:integer l:"Animal Intakes" t:dataTypeName=number

entity e:pyt5-me2k l:"Pet Data - 2016 Animal Intakes" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/pyt5-me2k

property e:pyt5-me2k t:meta.view v:id=pyt5-me2k v:category=Pets v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="Pet Data - 2016 Animal Intakes" v:attribution="King County"

property e:pyt5-me2k t:meta.view.license v:name="Public Domain"

property e:pyt5-me2k t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:pyt5-me2k t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animal_intakes | 
| ===== | ============== | 
| Jan   | 323            | 
| Mar   | 435            | 
| Feb   | 392            | 
| Apr   | 504            | 
| May   | 586            | 
| Jun   | 737            | 
| Jul   | 930            | 
| Aug   | 790            | 
| Sep   | 702            | 
| Oct   | 719            | 
```