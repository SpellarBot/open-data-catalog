# Facilities Management - Elecricity Usage, All Facilities, by Month - Fiscal Year 2008 through February 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-elecricity-usage-all-facilities-by-month-fiscal-year-2008-through-20-c2507) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/q6pg-yrhf) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/q6pg-yrhf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/q6pg-yrhf/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | q6pg-yrhf |
| Name | Facilities Management - Elecricity Usage, All Facilities, by Month - Fiscal Year 2008 through February 2012 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2012-03-20T20:09:00Z |
| Publication Date | 2014-10-09T22:29:42Z |

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
series e:q6pg-yrhf d:2008-12-01T00:00:00.000Z m:usage_kwh=853844.32 m:cost=65869.9

series e:q6pg-yrhf d:2008-01-01T00:00:00.000Z m:usage_kwh=851045.58 m:cost=64964.98

series e:q6pg-yrhf d:2008-02-01T00:00:00.000Z m:usage_kwh=799673.4 m:cost=67520.82
```

## Meta Commands

```ls
metric m:usage_kwh p:double l:"Usage (kWh)" t:dataTypeName=number

metric m:cost p:double l:Cost t:dataTypeName=money

entity e:q6pg-yrhf l:"Facilities Management - Elecricity Usage, All Facilities, by Month - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/q6pg-yrhf

property e:q6pg-yrhf t:meta.view v:id=q6pg-yrhf v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Elecricity Usage, All Facilities, by Month - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management"

property e:q6pg-yrhf t:meta.view.license v:name="Public Domain"

property e:q6pg-yrhf t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:q6pg-yrhf t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month     | fiscal_year | usage_kwh  | cost     | 
| ========= | =========== | ========== | ======== | 
| December  | 2008        | 853,844.32 | 65869.90 | 
| January   | 2008        | 851,045.58 | 64964.98 | 
| February  | 2008        | 799,673.40 | 67520.82 | 
| March     | 2008        | 666,659.67 | 60030.12 | 
| April     | 2008        | 474,090.91 | 45977.48 | 
| May       | 2008        | 432,984.83 | 38927.95 | 
| June      | 2008        | 533,147.91 | 55500.75 | 
| July      | 2008        | 671,494.13 | 67346.95 | 
| August    | 2008        | 668,235.35 | 65269.81 | 
| September | 2008        | 515,380.91 | 53335.90 | 
```