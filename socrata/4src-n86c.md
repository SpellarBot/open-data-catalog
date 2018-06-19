# Pet Data - 2014 Adoptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2014-adoptions-84ff5) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4src-n86c) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4src-n86c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4src-n86c/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4src-n86c |
| Name | Pet Data - 2014 Adoptions |
| Created | 2014-03-26T16:15:40Z |
| Publication Date | 2015-01-12T16:39:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | month           | Month           | text      | text        |
| Yes      | numeric metric | animals_adopted | Animals Adopted | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4src-n86c d:2014-01-01T00:00:00.000Z t:month=May m:animals_adopted=138

series e:4src-n86c d:2014-01-01T00:00:00.000Z t:month=Jan m:animals_adopted=152

series e:4src-n86c d:2014-01-01T00:00:00.000Z t:month=Feb m:animals_adopted=104
```

## Meta Commands

```ls
metric m:animals_adopted p:integer l:"Animals Adopted" t:dataTypeName=number

entity e:4src-n86c l:"Pet Data - 2014 Adoptions" t:url=https://data.kingcounty.gov/api/views/4src-n86c

property e:4src-n86c t:meta.view v:id=4src-n86c v:averageRating=0 v:name="Pet Data - 2014 Adoptions"

property e:4src-n86c t:meta.view.license v:name="Public Domain"

property e:4src-n86c t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:4src-n86c t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_adopted | 
| ===== | =============== | 
| May   | 138             | 
| Jan   | 152             | 
| Feb   | 104             | 
| Mar   | 136             | 
| Apr   | 101             | 
| Jun   | 152             | 
| Jul   | 174             | 
| Aug   | 226             | 
| Sep   | 168             | 
| Oct   | 202             | 
```