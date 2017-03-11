# Cook County Budget - 2013 - Preliminary Budget Revenues

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/55dk-ypji/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/cook-county-budget-2013-preliminary-budget-revenues-df945)
* [Metadata URL](https://datacatalog.cookcountyil.gov/api/views/55dk-ypji)
* Id = 55dk-ypji
* Name = Cook County Budget - 2013 - Preliminary Budget Revenues
* Attribution = Cook County Department of Budget and Management Services
* [Attribution Link](http://home.cookcountyil.gov/budget/)
* Category = Finance & Administration
* Created = 2012-09-04T17:37:02Z
* Publication Date = 2014-10-09T21:16:12Z
* Rows Updated = 2014-10-09T21:15:57Z

## Description



## Columns

```ls
| Name                                  | Field Name                          | Data Type | Render Type | Schema Type    | Included | 
| ===================================== | =================================== | ========= | =========== | ============== | ======== | 
| updated_at                            | :updated_at                         | meta_data | meta_data   | time           | No       | 
| Description                           | description                         | text      | text        | series tag     | Yes      | 
| FY 2012 Budgeted Revenue              | fy_2012_budgeted_revenue            | number    | number      | numeric metric | Yes      | 
| FY 2012 Actual, Dec-May*              | fy_2012_actual_dec_may              | number    | number      | numeric metric | Yes      | 
| FY 2012 Budgeted June-Nov (estimated) | fy_2012_budgeted_june_nov_estimated | number    | number      | numeric metric | Yes      | 
| Estimated 2012 Year-end               | estimated_2012_year_end             | number    | number      | numeric metric | Yes      | 
| FY 2013 Preliminary Estimate          | fy_2013_preliminary_estimate        | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:55dk-ypji d:2012-09-04T10:37:03.000Z t:description="Property Tax Revenue" m:fy_2012_budgeted_revenue=335209275 m:fy_2012_actual_dec_may=167604600 m:estimated_2012_year_end=335209200 m:fy_2013_preliminary_estimate=352918250 m:fy_2012_budgeted_june_nov_estimated=167604600

series e:55dk-ypji d:2012-09-04T10:37:03.000Z t:description="Interest on Penalties and Delinquent Taxes, Interest Earnings, and Special Fees" m:fy_2012_budgeted_revenue=56157000 m:fy_2012_actual_dec_may=26868000 m:estimated_2012_year_end=76000000 m:fy_2013_preliminary_estimate=76000000 m:fy_2012_budgeted_june_nov_estimated=49132000

series e:55dk-ypji d:2012-09-04T10:37:03.000Z t:description="Inheritance Taxes" m:fy_2012_budgeted_revenue=3850000 m:fy_2012_actual_dec_may=2000000 m:estimated_2012_year_end=2000000 m:fy_2013_preliminary_estimate=0 m:fy_2012_budgeted_june_nov_estimated=0
```

## Meta Commands

```ls
metric m:fy_2012_budgeted_revenue p:long l:"FY 2012 Budgeted Revenue" t:dataTypeName=number

metric m:fy_2012_actual_dec_may p:integer l:"FY 2012 Actual, Dec-May*" t:dataTypeName=number

metric m:fy_2012_budgeted_june_nov_estimated p:integer l:"FY 2012 Budgeted June-Nov (estimated)" t:dataTypeName=number

metric m:estimated_2012_year_end p:long l:"Estimated 2012 Year-end" t:dataTypeName=number

metric m:fy_2013_preliminary_estimate p:integer l:"FY 2013 Preliminary Estimate" t:dataTypeName=number

entity e:55dk-ypji l:"Cook County Budget - 2013 - Preliminary Budget Revenues" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/55dk-ypji

property e:55dk-ypji t:meta.view d:2017-03-07T16:12:46.715Z v:id=55dk-ypji v:category="Finance & Administration" v:attributionLink=http://home.cookcountyil.gov/budget/ v:averageRating=0 v:name="Cook County Budget - 2013 - Preliminary Budget Revenues" v:attribution="Cook County Department of Budget and Management Services"

property e:55dk-ypji t:meta.view.license d:2017-03-07T16:12:46.715Z v:name="Public Domain"

property e:55dk-ypji t:meta.view.owner d:2017-03-07T16:12:46.715Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:55dk-ypji t:meta.view.tableauthor d:2017-03-07T16:12:46.715Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```