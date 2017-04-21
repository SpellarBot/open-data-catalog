# City Budget Revenues by Fund by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-budget-revenues-by-fund-by-fiscal-year) |
| Metadata | [Link](https://data.iowa.gov/api/views/ecwz-7g9c) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ecwz-7g9c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ecwz-7g9c/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ecwz-7g9c |
| Name | City Budget Revenues by Fund by Fiscal Year |
| Category | Government |
| Tags | city, revenue, budget, fiscal year, line item |
| Created | 2015-08-14T19:35:28Z |
| Publication Date | 2016-12-28T14:11:03Z |

## Description

Revenue line item data extracted from the yearly certified budget of Iowa cities.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | code              | Code              | text      | text        |
| Yes      | series tag     | gnis_feature_id   | GNIS Feature ID   | text      | text        |
| Yes      | series tag     | unique_line_id    | Unique Line ID    | text      | text        |
| Yes      | series tag     | city_name         | City Name         | text      | text        |
| Yes      | time           | fiscal_year       | Fiscal Year       | number    | text        |
| Yes      | series tag     | revenue_line_item | Revenue Line Item | text      | text        |
| Yes      | series tag     | revenue_type      | Revenue Type      | text      | text        |
| Yes      | series tag     | fund              | Fund              | text      | text        |
| Yes      | numeric metric | value             | Value             | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ecwz-7g9c d:2016-01-01T00:00:00.000Z t:city_name=ADAIR t:unique_line_id=01G001-REVENUES-C-1-2016 t:gnis_feature_id=454088 t:revenue_type="Property Tax" t:fund="General Fund" t:code=01G001 t:revenue_line_item="Taxes Levied on Property" m:value=234862

series e:ecwz-7g9c d:2016-01-01T00:00:00.000Z t:city_name=BRIDGEWATER t:unique_line_id=01G002-REVENUES-C-1-2016 t:gnis_feature_id=454823 t:revenue_type="Property Tax" t:fund="General Fund" t:code=01G002 t:revenue_line_item="Taxes Levied on Property" m:value=19222

series e:ecwz-7g9c d:2016-01-01T00:00:00.000Z t:city_name=FONTANELLE t:unique_line_id=01G003-REVENUES-C-1-2016 t:gnis_feature_id=456661 t:revenue_type="Property Tax" t:fund="General Fund" t:code=01G003 t:revenue_line_item="Taxes Levied on Property" m:value=113706
```

## Meta Commands

```ls
metric m:value p:integer l:Value t:dataTypeName=number

entity e:ecwz-7g9c l:"City Budget Revenues by Fund by Fiscal Year" t:url=https://data.iowa.gov/api/views/ecwz-7g9c

property e:ecwz-7g9c t:meta.view v:id=ecwz-7g9c v:category=Government v:averageRating=0 v:name="City Budget Revenues by Fund by Fiscal Year"

property e:ecwz-7g9c t:meta.view.license v:name="Public Domain"

property e:ecwz-7g9c t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:ecwz-7g9c t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| code   | gnis_feature_id | unique_line_id           | city_name     | fiscal_year | revenue_line_item        | revenue_type | fund         | value  | 
| ====== | =============== | ======================== | ============= | =========== | ======================== | ============ | ============ | ====== | 
| 01G001 | 454088          | 01G001-REVENUES-C-1-2016 | ADAIR         | 2016        | Taxes Levied on Property | Property Tax | General Fund | 234862 | 
| 01G002 | 454823          | 01G002-REVENUES-C-1-2016 | BRIDGEWATER   | 2016        | Taxes Levied on Property | Property Tax | General Fund | 19222  | 
| 01G003 | 456661          | 01G003-REVENUES-C-1-2016 | FONTANELLE    | 2016        | Taxes Levied on Property | Property Tax | General Fund | 113706 | 
| 01G004 | 457121          | 01G004-REVENUES-C-1-2016 | GREENFIELD    | 2016        | Taxes Levied on Property | Property Tax | General Fund | 437368 | 
| 01G005 | 459893          | 01G005-REVENUES-C-1-2016 | ORIENT        | 2016        | Taxes Levied on Property | Property Tax | General Fund | 57482  | 
| 02G006 | 455158          | 02G006-REVENUES-C-1-2016 | CARBON        | 2016        | Taxes Levied on Property | Property Tax | General Fund | 4024   | 
| 02G007 | 455634          | 02G007-REVENUES-C-1-2016 | CORNING       | 2016        | Taxes Levied on Property | Property Tax | General Fund | 315889 | 
| 02G008 | 459537          | 02G008-REVENUES-C-1-2016 | NODAWAY       | 2016        | Taxes Levied on Property | Property Tax | General Fund | 16257  | 
| 02G009 | 460439          | 02G009-REVENUES-C-1-2016 | PRESCOTT      | 2016        | Taxes Levied on Property | Property Tax | General Fund | 31981  | 
| 03G010 | 457276          | 03G010-REVENUES-C-1-2016 | HARPERS FERRY | 2016        | Taxes Levied on Property | Property Tax | General Fund | 193164 | 
```