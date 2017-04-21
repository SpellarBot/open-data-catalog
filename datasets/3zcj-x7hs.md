# Facilities Management - Electrical Usage at 5600 Old Orchard Facility - Fiscal Year 2008 through February 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-electrical-usage-at-5600-old-orchard-facility-fiscal-year-2008-thr-2-d1837) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3zcj-x7hs) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3zcj-x7hs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3zcj-x7hs/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3zcj-x7hs |
| Name | Facilities Management - Electrical Usage at 5600 Old Orchard Facility - Fiscal Year 2008 through February 2012 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2012-03-20T19:17:17Z |
| Publication Date | 2014-10-09T22:10:44Z |

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
series e:3zcj-x7hs d:2009-03-01T00:00:00.000Z m:usage_kwh=537760.21 m:cost=57364.11

series e:3zcj-x7hs d:2012-01-01T00:00:00.000Z m:usage_kwh=1006141.92 m:cost=69759.06

series e:3zcj-x7hs d:2011-10-01T00:00:00.000Z m:usage_kwh=398070.13 m:cost=40973.85
```

## Meta Commands

```ls
metric m:usage_kwh p:double l:"Usage (kWh)" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:3zcj-x7hs l:"Facilities Management - Electrical Usage at 5600 Old Orchard Facility - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/3zcj-x7hs

property e:3zcj-x7hs t:meta.view v:id=3zcj-x7hs v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Electrical Usage at 5600 Old Orchard Facility - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management"

property e:3zcj-x7hs t:meta.view.license v:name="Public Domain"

property e:3zcj-x7hs t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:3zcj-x7hs t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month    | fiscal_year | usage_kwh    | cost     | 
| ======== | =========== | ============ | ======== | 
| March    | 2009        | 537,760.21   | 57364.11 | 
| January  | 2012        | 1,006,141.92 | 69759.06 | 
| October  | 2011        | 398,070.13   | 40973.85 | 
| June     | 2009        | 502,739.40   | 50484.68 | 
| June     | 2011        | 429,795.13   | 37918.59 | 
| January  | 2009        | 892,775.86   | 85073.42 | 
| January  | 2010        | 1,272,246.87 | 99541.05 | 
| August   | 2009        | 564,739.25   | 53961.37 | 
| February | 2011        | 825,991.26   | 66233.15 | 
| May      | 2010        | 415,178.03   | 47411.05 | 
```