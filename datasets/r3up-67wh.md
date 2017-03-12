# Feed-in Tariff Solar Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/feed-in-tariff-solar-program-b2309) |
| Metadata | [Link](https://data.lacity.org/api/views/r3up-67wh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/r3up-67wh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/r3up-67wh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | r3up-67wh |
| Name | Feed-in Tariff Solar Program |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | feed-in tariff, local solar, fit |
| Created | 2014-05-14T00:07:57Z |
| Publication Date | 2014-05-19T20:39:21Z |
| Rows Updated | 2014-05-19T20:39:18Z |

## Description

Quarter-Year	Installed Capacity from the Feed-in Tariff (FiT) Program in Kilowatts. The FiT program enables third parties to develop solar or other renewable energy and sell the power to the utility.  This is a relatively new program with projects in the beginning stages.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | quarter_year                   | Quarter-Year                     | text      | text        |
| Yes      | numeric metric | installed_capacity_from_fit_kw | Installed Capacity from FiT (kW) | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r3up-67wh d:2014-05-13T17:07:59.000Z t:quarter_year=Q1-2014 m:installed_capacity_from_fit_kw=700
```

## Meta Commands

```ls
metric m:installed_capacity_from_fit_kw p:integer l:"Installed Capacity from FiT (kW)" t:dataTypeName=number

entity e:r3up-67wh l:"Feed-in Tariff Solar Program" t:attribution=LADWP t:url=https://data.lacity.org/api/views/r3up-67wh

property e:r3up-67wh t:meta.view v:id=r3up-67wh v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Feed-in Tariff Solar Program" v:attribution=LADWP

property e:r3up-67wh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r3up-67wh t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"

property e:r3up-67wh t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```