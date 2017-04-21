# Industrial Engineers--Natural Gas Usage by Facility, by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/industrial-engineers-natural-gas-usage-by-facility-by-month-d8d7a) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8xzh-zvsn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8xzh-zvsn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8xzh-zvsn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8xzh-zvsn |
| Name | Industrial Engineers--Natural Gas Usage by Facility, by Month |
| Attribution | Cook County Department of Industrial Engineers |
| Category | Finance & Administration |
| Created | 2011-09-07T20:01:12Z |
| Publication Date | 2014-10-27T16:41:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       |                | facility_address | Facility Address | text      | text        |
| Yes      | series tag     | month            | Month            | text      | text        |
| Yes      | time           | fiscal_year      | Fiscal Year      | number    | text        |
| Yes      | numeric metric | gas_cost         | Gas Cost         | money     | money       |
| Yes      | numeric metric | usage            | Usage            | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = facility_address
```

## Data Commands

```ls
series e:8xzh-zvsn d:2010-01-01T00:00:00.000Z t:month=November m:gas_cost=317.56 m:usage=399.77

series e:8xzh-zvsn d:2011-01-01T00:00:00.000Z t:month=December m:gas_cost=725.62 m:usage=876.09

series e:8xzh-zvsn d:2011-01-01T00:00:00.000Z t:month=January m:gas_cost=726.19 m:usage=882
```

## Meta Commands

```ls
metric m:gas_cost p:double l:"Gas Cost" t:dataTypeName=money

metric m:usage p:double l:Usage t:dataTypeName=number

entity e:8xzh-zvsn l:"Industrial Engineers--Natural Gas Usage by Facility, by Month" t:attribution="Cook County Department of Industrial Engineers" t:url=https://datacatalog.cookcountyil.gov/api/views/8xzh-zvsn

property e:8xzh-zvsn t:meta.view v:id=8xzh-zvsn v:category="Finance & Administration" v:averageRating=0 v:name="Industrial Engineers--Natural Gas Usage by Facility, by Month" v:attribution="Cook County Department of Industrial Engineers"

property e:8xzh-zvsn t:meta.view.license v:name="Public Domain"

property e:8xzh-zvsn t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:8xzh-zvsn t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| facility_address          | month    | fiscal_year | gas_cost | usage   | 
| ========================= | ======== | =========== | ======== | ======= | 
| 7556 Jackson Blvd. Garage | November | 2010        | 317.56   | 399.77  | 
| 7556 Jackson Blvd. Garage | December | 2011        | 725.62   | 876.09  | 
| 7556 Jackson Blvd. Garage | January  | 2011        | 726.19   | 882     | 
| 7556 Jackson Blvd. Garage | February | 2011        | 612.29   | 718.7   | 
| 855 26th Street           | January  | 2006        | 19917.64 | 9175.80 | 
| 855 26th Street           | January  | 2006        | 27714.43 | 8735.61 | 
| 855 26th Street           | March    | 2006        | 8073.19  | 9642.12 | 
| 1720 Cherry Street        | January  | 2006        | 25.74    | 4.05    | 
| 1720 Cherry Street        | February | 2006        | 21.79    | 1.01    | 
| 2325 S. Meacham           | December | 2006        | 16151.20 | 9101.92 | 
```