# Exceptional Trees On Oahu

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/exceptional-trees-on-oahu-9154e) |
| Metadata | [Link](https://data.honolulu.gov/api/views/84fd-3fzf) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/84fd-3fzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/84fd-3fzf/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 84fd-3fzf |
| Name | Exceptional Trees On Oahu |
| Attribution | C&C Honolulu |
| Category | Recreation |
| Created | 2013-04-30T20:41:02Z |
| Publication Date | 2013-04-30T20:43:32Z |
| Rows Updated | 2013-04-30T20:41:05Z |

## Description

City & County exceptional tree database

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | tmk                         | TMK                         | text      | text        |
| Yes      | series tag  | species_and_number_of_trees | Species and Number of Trees | text      | text        |
| Yes      | series tag  | common_name                 | Common Name                 | text      | text        |
| Yes      | series tag  | location                    | Location                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:84fd-3fzf d:2013-04-30T13:41:03.000Z t:location="Schofield Barracks, Ulrich S., w. of bldg. S2107" t:species_and_number_of_trees="Acrocarpus fraxinifolius (1)" t:common_name="Pink Cedar Tree" t:tmk=N/A m:row_number=1

series e:84fd-3fzf d:2013-04-30T13:41:03.000Z t:location="Queen's Medical Center, 1301 Punchbowl St." t:species_and_number_of_trees="Adansonia digitata (1)" t:common_name="Baobab Tree" t:tmk=2-1-035:003 m:row_number=2

series e:84fd-3fzf d:2013-04-30T13:41:03.000Z t:location="Foster Botanical Garden, 180 N. Vineyard Blvd." t:species_and_number_of_trees="Adansonia digitata (1)" t:common_name="Baobab Tree" t:tmk=1-7-007:002 m:row_number=3
```

## Meta Commands

```ls
metric m:row_number p:long l:"Row Number"

entity e:84fd-3fzf l:"Exceptional Trees On Oahu" t:attribution="C&C Honolulu" t:url=https://data.honolulu.gov/api/views/84fd-3fzf

property e:84fd-3fzf t:meta.view v:id=84fd-3fzf v:category=Recreation v:attributionLink=http://www1.honolulu.gov/parks/exceptionaltrees.htm v:averageRating=0 v:name="Exceptional Trees On Oahu" v:attribution="C&C Honolulu"

property e:84fd-3fzf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:84fd-3fzf t:meta.view.owner v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"

property e:84fd-3fzf t:meta.view.tableauthor v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"
```