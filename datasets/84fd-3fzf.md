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
```

## Meta Commands

```ls
entity e:84fd-3fzf l:"Exceptional Trees On Oahu" t:attribution="C&C Honolulu" t:url=https://data.honolulu.gov/api/views/84fd-3fzf

property e:84fd-3fzf t:meta.view d:2017-03-10T16:23:09.878Z v:id=84fd-3fzf v:category=Recreation v:attributionLink=http://www1.honolulu.gov/parks/exceptionaltrees.htm v:averageRating=0 v:name="Exceptional Trees On Oahu" v:attribution="C&C Honolulu"

property e:84fd-3fzf t:meta.view.license d:2017-03-10T16:23:09.878Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:84fd-3fzf t:meta.view.owner d:2017-03-10T16:23:09.878Z v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"

property e:84fd-3fzf t:meta.view.tableauthor d:2017-03-10T16:23:09.878Z v:id=5vv3-gysc v:profileImageUrlMedium=/api/users/5vv3-gysc/profile_images/THUMB v:profileImageUrlLarge=/api/users/5vv3-gysc/profile_images/LARGE v:screenName="Burt Lum" v:profileImageUrlSmall=/api/users/5vv3-gysc/profile_images/TINY v:displayName="Burt Lum"
```