# Pet Data - 2015 Adoptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-adoptions) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/sm23-uzbg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/sm23-uzbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/sm23-uzbg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | sm23-uzbg |
| Name | Pet Data - 2015 Adoptions |
| Category | Government |
| Created | 2015-02-06T20:01:56Z |
| Publication Date | 2016-02-03T17:37:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | month           | Month           | text      | text        |
| Yes      | numeric metric | animals_adopted | Animals Adopted | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sm23-uzbg d:2015-01-01T00:00:00.000Z t:month=Jan m:animals_adopted=141

series e:sm23-uzbg d:2015-01-01T00:00:00.000Z t:month=Feb m:animals_adopted=108

series e:sm23-uzbg d:2015-01-01T00:00:00.000Z t:month=May m:animals_adopted=123
```

## Meta Commands

```ls
metric m:animals_adopted p:integer l:"Animals Adopted" t:dataTypeName=number

entity e:sm23-uzbg l:"Pet Data - 2015 Adoptions" t:url=https://data.kingcounty.gov/api/views/sm23-uzbg

property e:sm23-uzbg t:meta.view v:id=sm23-uzbg v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Adoptions"

property e:sm23-uzbg t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:sm23-uzbg t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| month | animals_adopted | 
| ===== | =============== | 
| Jan   | 141             | 
| Feb   | 108             | 
| May   | 123             | 
| Aug   | 251             | 
| Sep   | 214             | 
| Nov   | 248             | 
| Dec   | 194             | 
| Mar   | 117             | 
| Apr   | 115             | 
| Jun   | 159             | 
```