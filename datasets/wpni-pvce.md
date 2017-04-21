# Facilities Management - Electrical Usage at 1500 Maybrook Facility, by Month - Fiscal Year 2008 through February 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-electrical-usage-at-1500-maybrook-facility-by-month-fiscal-year-20-2-e22c8) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wpni-pvce) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wpni-pvce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wpni-pvce/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wpni-pvce |
| Name | Facilities Management - Electrical Usage at 1500 Maybrook Facility, by Month - Fiscal Year 2008 through February 2012 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2012-03-20T19:51:24Z |
| Publication Date | 2014-10-09T22:27:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       |                | month       | Month       | text      | text        |
| No       |                | fiscal_year | Fiscal Year | number    | text        |
| Yes      | numeric metric | usage_kwh   | Usage (kWh) | number    | text        |
| Yes      | numeric metric | cost        | Cost        | money     | money       |
```

## Time Field

```ls
Value = fiscal_year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = fiscal_year,month
```

## Data Commands

```ls
series e:wpni-pvce d:2010-08-01T00:00:00.000Z m:usage_kwh=680251.16 m:cost=63068.03

series e:wpni-pvce d:2009-04-01T00:00:00.000Z m:usage_kwh=541528.73 m:cost=56857.24

series e:wpni-pvce d:2008-01-01T00:00:00.000Z m:usage_kwh=1065418.13 m:cost=82053.45
```

## Meta Commands

```ls
metric m:usage_kwh p:double l:"Usage (kWh)" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:wpni-pvce l:"Facilities Management - Electrical Usage at 1500 Maybrook Facility, by Month - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/wpni-pvce

property e:wpni-pvce t:meta.view v:id=wpni-pvce v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Electrical Usage at 1500 Maybrook Facility, by Month - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management"

property e:wpni-pvce t:meta.view.license v:name="Public Domain"

property e:wpni-pvce t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:wpni-pvce t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month     | fiscal_year | usage_kwh    | cost     | 
| ========= | =========== | ============ | ======== | 
| August    | 2010        | 680,251.16   | 63068.03 | 
| April     | 2009        | 541,528.73   | 56857.24 | 
| January   | 2008        | 1,065,418.13 | 82053.45 | 
| June      | 2010        | 703,772.92   | 65491.68 | 
| December  | 2010        | 1,181,843.40 | 93663.48 | 
| September | 2011        | 435,654.65   | 40892.18 | 
| December  | 2011        | 1,138,484.81 | 83162.97 | 
| July      | 2011        | 719,988.32   | 56283.61 | 
| September | 2010        | 534,569.79   | 53762.54 | 
| December  | 2012        | 1,212,343.67 | 81425.93 | 
```