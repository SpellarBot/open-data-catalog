# Cook County Budget - 2013 - Preliminary Budget Revenues

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-budget-2013-preliminary-budget-revenues-df945) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/55dk-ypji) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/55dk-ypji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/55dk-ypji/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 55dk-ypji |
| Name | Cook County Budget - 2013 - Preliminary Budget Revenues |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Created | 2012-09-04T17:37:02Z |
| Publication Date | 2014-10-09T21:16:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type | Render Type |
| ======== | ============== | =================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | description                         | Description                           | text      | text        |
| Yes      | numeric metric | fy_2012_budgeted_revenue            | FY 2012 Budgeted Revenue              | number    | number      |
| Yes      | numeric metric | fy_2012_actual_dec_may              | FY 2012 Actual, Dec-May*              | number    | number      |
| Yes      | numeric metric | fy_2012_budgeted_june_nov_estimated | FY 2012 Budgeted June-Nov (estimated) | number    | number      |
| Yes      | numeric metric | estimated_2012_year_end             | Estimated 2012 Year-end               | number    | number      |
| Yes      | numeric metric | fy_2013_preliminary_estimate        | FY 2013 Preliminary Estimate          | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:55dk-ypji d:2013-01-01T00:00:00.000Z t:description="Property Tax Revenue" m:fy_2012_budgeted_revenue=335209275 m:fy_2012_actual_dec_may=167604600 m:estimated_2012_year_end=335209200 m:fy_2013_preliminary_estimate=352918250 m:fy_2012_budgeted_june_nov_estimated=167604600

series e:55dk-ypji d:2013-01-01T00:00:00.000Z t:description="Interest on Penalties and Delinquent Taxes, Interest Earnings, and Special Fees" m:fy_2012_budgeted_revenue=56157000 m:fy_2012_actual_dec_may=26868000 m:estimated_2012_year_end=76000000 m:fy_2013_preliminary_estimate=76000000 m:fy_2012_budgeted_june_nov_estimated=49132000

series e:55dk-ypji d:2013-01-01T00:00:00.000Z t:description="Inheritance Taxes" m:fy_2012_budgeted_revenue=3850000 m:fy_2012_actual_dec_may=2000000 m:estimated_2012_year_end=2000000 m:fy_2013_preliminary_estimate=0 m:fy_2012_budgeted_june_nov_estimated=0
```

## Meta Commands

```ls
metric m:fy_2012_budgeted_revenue p:long l:"FY 2012 Budgeted Revenue" t:dataTypeName=number

metric m:fy_2012_actual_dec_may p:integer l:"FY 2012 Actual, Dec-May*" t:dataTypeName=number

metric m:fy_2012_budgeted_june_nov_estimated p:integer l:"FY 2012 Budgeted June-Nov (estimated)" t:dataTypeName=number

metric m:estimated_2012_year_end p:long l:"Estimated 2012 Year-end" t:dataTypeName=number

metric m:fy_2013_preliminary_estimate p:integer l:"FY 2013 Preliminary Estimate" t:dataTypeName=number

entity e:55dk-ypji l:"Cook County Budget - 2013 - Preliminary Budget Revenues" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/55dk-ypji

property e:55dk-ypji t:meta.view v:id=55dk-ypji v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Cook County Budget - 2013 - Preliminary Budget Revenues" v:attribution="Cook County Department of Budget and Management Services"

property e:55dk-ypji t:meta.view.license v:name="Public Domain"

property e:55dk-ypji t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:55dk-ypji t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| description                                                                     | fy_2012_budgeted_revenue | fy_2012_actual_dec_may | fy_2012_budgeted_june_nov_estimated | estimated_2012_year_end | fy_2013_preliminary_estimate | 
| =============================================================================== | ======================== | ====================== | =================================== | ======================= | ============================ | 
| Property Tax Revenue                                                            | 335209275                | 167604600              | 167604600                           | 335209200               | 352918250                    | 
| Fees                                                                            |                          |                        |                                     |                         |                              | 
| Treasurer*                                                                      |                          |                        |                                     |                         |                              | 
| Interest on Penalties and Delinquent Taxes, Interest Earnings, and Special Fees | 56157000                 | 26868000               | 49132000                            | 76000000                | 76000000                     | 
| Inheritance Taxes                                                               | 3850000                  | 2000000                | 0                                   | 2000000                 | 0                            | 
| Total Budgeted                                                                  | 60007000                 | 28868000               | 49132000                            | 78000000                | 76000000                     | 
|                                                                                 |                          |                        |                                     |                         |                              | 
| County Clerk                                                                    |                          |                        |                                     |                         |                              | 
| Tax Estimates and Searches                                                      | 1600000                  | 281500                 | 1335000                             | 1616500                 | 1700000                      | 
| Redemption Fees                                                                 | 275000                   | 116400                 | 155000                              | 271400                  | 275000                       | 
```