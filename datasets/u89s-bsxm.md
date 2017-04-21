# Lobbyist Data Name Mapping

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-data-name-mapping-58241) |
| Metadata | [Link](https://data.sfgov.org/api/views/u89s-bsxm) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/u89s-bsxm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/u89s-bsxm/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | u89s-bsxm |
| Name | Lobbyist Data Name Mapping |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | lobbyist, lobbying, mapping, ethics, disclosure |
| Created | 2012-08-22T16:36:19Z |
| Publication Date | 2013-03-04T23:04:14Z |

## Description

Lobbyists are required to accurately self-report all information required under the Lobbyist Ordinance.  The Ethics Commission does not alter any entry except to correct typographical errors in order to facilitate the public's use of the reported information.  This includes correcting the spelling of public officials' names. However, the Commission retains the original filings in its office. The table below provides a list of typographical errors on lobbyist disclosure reports since January, 2010. The "Reported As" column indicates the name originally reported by the lobbyist. The "Display As" column indicates the corrections made on the lobbyist web site.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | reported_as | Reported As | text      | text        |
| Yes      | series tag  | display_as  | Display As  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u89s-bsxm d:2013-03-04T15:04:05.000Z t:reported_as="Alioto-Pier, Michaela" t:display_as="Alioto-Pier, Michela" m:row_number.u89s-bsxm=1

series e:u89s-bsxm d:2013-03-04T15:04:05.000Z t:reported_as="Alioto-Pier, Michele" t:display_as="Alioto-Pier, Michela" m:row_number.u89s-bsxm=2

series e:u89s-bsxm d:2013-03-04T15:04:05.000Z t:reported_as="Antonini, Mike" t:display_as="Antonini, Michael" m:row_number.u89s-bsxm=3
```

## Meta Commands

```ls
metric m:row_number.u89s-bsxm p:long l:"Row Number"

entity e:u89s-bsxm l:"Lobbyist Data Name Mapping" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/u89s-bsxm

property e:u89s-bsxm t:meta.view v:id=u89s-bsxm v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Lobbyist Data Name Mapping" v:attribution="San Francisco Ethics Commission"

property e:u89s-bsxm t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:u89s-bsxm t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:u89s-bsxm t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | reported_as           | display_as           | 
| =========== | ===================== | ==================== | 
| 1362409445  | Alioto-Pier, Michaela | Alioto-Pier, Michela | 
| 1362409445  | Alioto-Pier, Michele  | Alioto-Pier, Michela | 
| 1362409445  | Antonini, Mike        | Antonini, Michael    | 
| 1362409445  | Barnes , Bill         | Barnes, Bill         | 
| 1362409445  | Bmwl & Partners       | Bmwl & Partners, Inc | 
| 1362409445  | Borden, Gweneth       | Borden, Gwyneth      | 
| 1362409445  | Borden, Gwenyth       | Borden, Gwyneth      | 
| 1362409445  | Daly , Chris          | Daly, Chris          | 
| 1362409445  | Deberry, Christine    | Deberry, Cristine    | 
| 1362409445  | Dhiu, David           | Chiu, David          | 
```