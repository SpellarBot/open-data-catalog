# Pet Data - 2016 Pets Returned to Owner

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2016-pets-returned-to-owner) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fjsj-3cuv) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fjsj-3cuv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fjsj-3cuv/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fjsj-3cuv |
| Name | Pet Data - 2016 Pets Returned to Owner |
| Attribution | King County |
| Category | Pets |
| Created | 2015-12-11T16:17:17Z |
| Publication Date | 2017-01-18T16:46:39Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | month                  | Month                  | text      | text        |
| Yes      | numeric metric | pets_returned_to_owner | Pets Returned to Owner | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fjsj-3cuv d:2016-01-01T00:00:00.000Z t:month=Jan m:pets_returned_to_owner=38

series e:fjsj-3cuv d:2016-01-01T00:00:00.000Z t:month=Mar m:pets_returned_to_owner=53

series e:fjsj-3cuv d:2016-01-01T00:00:00.000Z t:month=Feb m:pets_returned_to_owner=50
```

## Meta Commands

```ls
metric m:pets_returned_to_owner p:integer l:"Pets Returned to Owner" t:dataTypeName=number

entity e:fjsj-3cuv l:"Pet Data - 2016 Pets Returned to Owner" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/fjsj-3cuv

property e:fjsj-3cuv t:meta.view v:id=fjsj-3cuv v:category=Pets v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="Pet Data - 2016 Pets Returned to Owner" v:attribution="King County"

property e:fjsj-3cuv t:meta.view.license v:name="Public Domain"

property e:fjsj-3cuv t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:fjsj-3cuv t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | pets_returned_to_owner | 
| ===== | ====================== | 
| Jan   | 38                     | 
| Mar   | 53                     | 
| Feb   | 50                     | 
| Apr   | 57                     | 
| May   | 65                     | 
| Jun   | 77                     | 
| Jul   | 100                    | 
| Aug   | 79                     | 
| Sep   | 78                     | 
| Oct   | 62                     | 
```