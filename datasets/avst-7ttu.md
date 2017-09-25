# Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-electricity-usage-2121-euclid-av-facility-by-month-fiscal-year-200-2-bd509) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/avst-7ttu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/avst-7ttu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/avst-7ttu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | avst-7ttu |
| Name | Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2012-03-20T20:02:50Z |
| Publication Date | 2014-10-09T22:33:33Z |

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
series e:avst-7ttu d:2011-04-01T00:00:00.000Z m:cost=49837.92 m:usage_kwh=546355.2

series e:avst-7ttu d:2008-01-01T00:00:00.000Z m:cost=68450.91 m:usage_kwh=880914.24

series e:avst-7ttu d:2010-08-01T00:00:00.000Z m:cost=64074.54 m:usage_kwh=683354.61
```

## Meta Commands

```ls
metric m:usage_kwh p:double l:"Usage (kWh)" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:avst-7ttu l:"Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/avst-7ttu

property e:avst-7ttu t:meta.view d:2017-09-25T07:24:37.404Z v:averageRating=0 v:name="Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:id=avst-7ttu v:category="Finance & Administration"

property e:avst-7ttu t:meta.view.license d:2017-09-25T07:24:37.404Z v:name="Public Domain"

property e:avst-7ttu t:meta.view.owner d:2017-09-25T07:24:37.404Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB

property e:avst-7ttu t:meta.view.tableauthor d:2017-09-25T07:24:37.404Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB
```

## Top Records

```ls
| month    | fiscal_year | usage_kwh    | cost     | 
| ======== | =========== | ============ | ======== | 
| April    | 2011        | 546,355.20   | 49837.92 | 
| January  | 2008        | 880,914.24   | 68450.91 | 
| August   | 2010        | 683,354.61   | 64074.54 | 
| June     | 2009        | 619,755.97   | 65204.46 | 
| May      | 2009        | 507,749.19   | 55342.34 | 
| January  | 2010        | 854,762.23   | 73719.88 | 
| December | 2010        | 1,037,424.92 | 87141.69 | 
| December | 2008        | 936,858.41   | 72332.97 | 
| August   | 2008        | 724,067.95   | 75816.17 | 
| July     | 2008        | 807,472.07   | 83070.69 | 
```