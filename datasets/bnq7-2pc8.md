# Transit Communities Funding Toolkit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transit-communities-funding-toolkit-a7336) |
| Metadata | [Link](https://data.seattle.gov/api/views/bnq7-2pc8) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/bnq7-2pc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/bnq7-2pc8/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | bnq7-2pc8 |
| Name | Transit Communities Funding Toolkit |
| Attribution | City of Seattle, Seattle Planning Commission |
| Category | Community |
| Tags | funding, levies, community development, economic development |
| Created | 2011-02-14T19:47:12Z |
| Publication Date | 2011-04-17T00:03:09Z |
| Rows Updated | 2011-08-21T02:48:35Z |

## Description

The funding toolkit identifies funding sources for three broad categories of livability elements: infrastructure investments, which may include right-of-way improvements, sidewalks, Green Streets, or bike lanes/facilities; community development, such as affordable housing, public services, schools, historic preservation; and parks and open space, which includes parks, playfields, plazas, and p-patches.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | administrator         | administrator         | text      | text        |
| Yes      | series tag  | program               | program               | text      | text        |
| Yes      | series tag  | infrastructure        | infrastructure        | checkbox  | checkbox    |
| Yes      | series tag  | community_development | community development | checkbox  | checkbox    |
| Yes      | series tag  | open_space            | open space            | checkbox  | checkbox    |
| Yes      | series tag  | funding_amount        | funding amount        | text      | text        |
| Yes      | series tag  | funding_type          | funding type          | text      | text        |
| Yes      | series tag  | description           | description           | text      | text        |
| Yes      | series tag  | opportunities         | opportunities         | text      | text        |
| Yes      | series tag  | challenges            | challenges            | text      | text        |
| Yes      | series tag  | website               | website               | url       | url         |
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
entity e:bnq7-2pc8 l:"Transit Communities Funding Toolkit" t:attribution="City of Seattle, Seattle Planning Commission" t:url=https://data.seattle.gov/api/views/bnq7-2pc8

property e:bnq7-2pc8 t:meta.view v:id=bnq7-2pc8 v:category=Community v:averageRating=0 v:name="Transit Communities Funding Toolkit" v:attribution="City of Seattle, Seattle Planning Commission"

property e:bnq7-2pc8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bnq7-2pc8 t:meta.view.owner v:id=9vuc-jwdr v:profileImageUrlMedium=/api/users/9vuc-jwdr/profile_images/THUMB v:profileImageUrlLarge=/api/users/9vuc-jwdr/profile_images/LARGE v:screenName="Sheehy, Katie" v:profileImageUrlSmall=/api/users/9vuc-jwdr/profile_images/TINY v:displayName="Sheehy, Katie"

property e:bnq7-2pc8 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```