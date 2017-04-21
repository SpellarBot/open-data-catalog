# Industrial Engineers--Natural Gas Usage, by Cook County Government facility, month and year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/industrial-engineers-natural-gas-usage-by-cook-county-government-facility-month-and-year-4e31c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hkhn-a2ua) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hkhn-a2ua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hkhn-a2ua/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hkhn-a2ua |
| Name | Industrial Engineers--Natural Gas Usage, by Cook County Government facility, month and year |
| Attribution | Cook County Department of Industrial Engineers |
| Category | Finance & Administration |
| Created | 2011-11-01T20:24:02Z |
| Publication Date | 2014-10-27T16:40:32Z |

## Description

Updated 10/31/2011.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | service_address | Service Address | text      | text        |
| Yes      | series tag     | service_town    | Service Town    | text      | text        |
| No       |                | month           | Month           | text      | text        |
| No       |                | fiscal_year     | Fiscal Year     | number    | text        |
| Yes      | numeric metric | usage_therms_   | Usage (Therms)  | number    | number      |
| Yes      | numeric metric | total_cost      | Total Cost      | money     | money       |
```

## Time Field

```ls
Value = fiscal_year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = service_address,fiscal_year,month
```

## Data Commands

```ls
series e:hkhn-a2ua d:2007-08-01T00:00:00.000Z t:service_town=Bridgeview m:usage_therms_=1.13 m:total_cost=21.77

series e:hkhn-a2ua d:2007-03-01T00:00:00.000Z t:service_town=Bridgeview m:usage_therms_=1.13 m:total_cost=21.92

series e:hkhn-a2ua d:2007-11-01T00:00:00.000Z t:service_town=Bridgeview m:usage_therms_=2.27 m:total_cost=22.73
```

## Meta Commands

```ls
metric m:usage_therms_ p:double l:"Usage (Therms)" t:dataTypeName=number

metric m:total_cost p:double l:"Total Cost" t:dataTypeName=money

entity e:hkhn-a2ua l:"Industrial Engineers--Natural Gas Usage, by Cook County Government facility, month and year" t:attribution="Cook County Department of Industrial Engineers" t:url=https://datacatalog.cookcountyil.gov/api/views/hkhn-a2ua

property e:hkhn-a2ua t:meta.view v:id=hkhn-a2ua v:category="Finance & Administration" v:averageRating=0 v:name="Industrial Engineers--Natural Gas Usage, by Cook County Government facility, month and year" v:attribution="Cook County Department of Industrial Engineers"

property e:hkhn-a2ua t:meta.view.license v:name="Public Domain"

property e:hkhn-a2ua t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:hkhn-a2ua t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| service_address    | service_town | month     | fiscal_year | usage_therms_ | total_cost | 
| ================== | ============ | ========= | =========== | ============= | ========== | 
| 10220 S. 76th Ave. | Bridgeview   | August    | 2007        | 1.13          | 21.77      | 
| 10220 S. 76th Ave. | Bridgeview   | March     | 2007        | 1.13          | 21.92      | 
| 10220 S. 76th Ave. | Bridgeview   | November  | 2007        | 2.27          | 22.73      | 
| 10220 S. 76th Ave. | Bridgeview   | July      | 2007        | 2.26          | 22.96      | 
| 10220 S. 76th Ave. | Bridgeview   | September | 2007        | 2.26          | 22.62      | 
| 10220 S. 76th Ave. | Bridgeview   | January   | 2007        | 2.26          | 22.68      | 
| 10220 S. 76th Ave. | Bridgeview   | May       | 2007        | 2.26          | 23.10      | 
| 10220 S. 76th Ave. | Bridgeview   | October   | 2007        | 1.13          | 21.75      | 
| 10220 S. 76th Ave. | Bridgeview   | December  | 2008        | 2.27          | 22.64      | 
| 10220 S. 76th Ave. | Bridgeview   | June      | 2007        | 1.13          | 21.96      | 
```