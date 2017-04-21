# Facilities Management - Electrical Usage at 10290 S 76th Facility, by Month - Fiscal Year 2008 through February 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-electrical-usage-at-10290-s-76th-facility-by-month-fiscal-year-200-2-0d10c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xgw3-66ja) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xgw3-66ja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xgw3-66ja/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xgw3-66ja |
| Name | Facilities Management - Electrical Usage at 10290 S 76th Facility, by Month - Fiscal Year 2008 through February 2012 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2012-03-20T19:43:48Z |
| Publication Date | 2014-10-09T22:24:29Z |

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
series e:xgw3-66ja d:2008-06-01T00:00:00.000Z m:usage_kwh=10221 m:cost=1014.97

series e:xgw3-66ja d:2011-04-01T00:00:00.000Z m:usage_kwh=7503 m:cost=587.2

series e:xgw3-66ja d:2008-03-01T00:00:00.000Z m:usage_kwh=6965 m:cost=574.79
```

## Meta Commands

```ls
metric m:usage_kwh p:long l:"Usage (kWh)" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:xgw3-66ja l:"Facilities Management - Electrical Usage at 10290 S 76th Facility, by Month - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/xgw3-66ja

property e:xgw3-66ja t:meta.view v:id=xgw3-66ja v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Electrical Usage at 10290 S 76th Facility, by Month - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management"

property e:xgw3-66ja t:meta.view.license v:name="Public Domain"

property e:xgw3-66ja t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:xgw3-66ja t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month     | fiscal_year | usage_kwh | cost    | 
| ========= | =========== | ========= | ======= | 
| June      | 2008        | 10,221.00 | 1014.97 | 
| April     | 2011        | 7,503.00  | 587.20  | 
| March     | 2008        | 6,965.00  | 574.79  | 
| September | 2009        | 7,959.00  | 732.84  | 
| May       | 2008        | 8,724.00  | 767.41  | 
| April     | 2008        | 7,312.00  | 625.02  | 
| June      | 2011        | 9,222.00  | 665.04  | 
| November  | 2011        | 7,721.00  | 567.74  | 
| July      | 2009        | 9,304.00  | 852.15  | 
| September | 2010        | 10,570.00 | 852.31  | 
```