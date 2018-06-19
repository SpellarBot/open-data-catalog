# Collection Size and Cardholders at the Austin Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/collection-size-and-cardholders-at-the-austin-public-library) |
| Metadata | [Link](https://data.austintexas.gov/api/views/krg6-2bs5) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/krg6-2bs5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/krg6-2bs5/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | krg6-2bs5 |
| Name | Collection Size and Cardholders at the Austin Public Library |
| Attribution | Austin Public Library |
| Category | Business |
| Tags | library, collection, accounts |
| Created | 2015-07-08T17:01:25Z |
| Publication Date | 2017-04-03T19:52:06Z |

## Description

Monthly statistics on the collection size, excluding archival materials at the Austin History Center, and the number of registered Library card holders.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| No       |                | date                            | Date                            | text      | text        |
| Yes      | numeric metric | collection_size                 | Collection Size                 | number    | number      |
| Yes      | numeric metric | registered_library_card_holders | Registered Library Card Holders | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:krg6-2bs5 d:2017-04-03T19:51:39.000Z m:collection_size=1414509 m:registered_library_card_holders=511429

series e:krg6-2bs5 d:2017-04-03T19:51:39.000Z m:collection_size=1421709 m:registered_library_card_holders=513722

series e:krg6-2bs5 d:2017-04-03T19:51:39.000Z m:collection_size=1424352 m:registered_library_card_holders=515814
```

## Meta Commands

```ls
metric m:collection_size p:integer l:"Collection Size" t:dataTypeName=number

metric m:registered_library_card_holders p:integer l:"Registered Library Card Holders" t:dataTypeName=number

entity e:krg6-2bs5 l:"Collection Size and Cardholders at the Austin Public Library" t:attribution="Austin Public Library" t:url=https://data.austintexas.gov/api/views/krg6-2bs5

property e:krg6-2bs5 t:meta.view v:id=krg6-2bs5 v:category=Business v:averageRating=0 v:name="Collection Size and Cardholders at the Austin Public Library" v:attribution="Austin Public Library"

property e:krg6-2bs5 t:meta.view.license v:name="Public Domain"

property e:krg6-2bs5 t:meta.view.owner v:id=knx5-5zd7 v:screenName=Sarah v:displayName=Sarah

property e:krg6-2bs5 t:meta.view.tableauthor v:id=knx5-5zd7 v:screenName=Sarah v:roleName=editor_stories v:displayName=Sarah
```

## Top Records

```ls
| :updated_at | date   | collection_size | registered_library_card_holders | 
| =========== | ====== | =============== | =============================== | 
| 1491249099  | Oct-14 | 1414509         | 511429                          | 
| 1491249099  | Nov-14 | 1421709         | 513722                          | 
| 1491249099  | Dec-14 | 1424352         | 515814                          | 
| 1491249099  | Jan-15 | 1409501         | 518800                          | 
| 1491249099  | Feb-15 | 1404791         | 521127                          | 
| 1491249099  | Mar-15 | 1422455         | 523671                          | 
| 1491249099  | Apr-15 | 1430411         | 526089                          | 
| 1491249099  | May-15 | 1437704         | 528521                          | 
| 1491249099  | Jun-15 | 1439874         | 532273                          | 
| 1491249099  | Jul-15 | 1442277         | 535347                          | 
```