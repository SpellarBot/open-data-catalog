# Pet Data - 2015 Foster

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-data-2015-foster) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/izuy-zuze) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/izuy-zuze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/izuy-zuze/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | izuy-zuze |
| Name | Pet Data - 2015 Foster |
| Category | Government |
| Created | 2015-02-06T20:05:43Z |
| Publication Date | 2016-02-03T17:42:34Z |
| Rows Updated | 2016-02-03T17:42:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | month            | Month            | text      | text        |
| Yes      | numeric metric | animals_fostered | Animals Fostered | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:izuy-zuze d:2015-01-01T00:00:00.000Z t:month=Feb m:animals_fostered=34

series e:izuy-zuze d:2015-01-01T00:00:00.000Z t:month=Apr m:animals_fostered=54

series e:izuy-zuze d:2015-01-01T00:00:00.000Z t:month=May m:animals_fostered=135
```

## Meta Commands

```ls
metric m:animals_fostered p:integer l:"Animals Fostered" t:dataTypeName=number

entity e:izuy-zuze l:"Pet Data - 2015 Foster" t:url=https://data.kingcounty.gov/api/views/izuy-zuze

property e:izuy-zuze t:meta.view v:id=izuy-zuze v:category=Government v:averageRating=0 v:name="Pet Data - 2015 Foster"

property e:izuy-zuze t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:izuy-zuze t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```