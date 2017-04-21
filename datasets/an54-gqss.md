# Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-preliminary-budget-fiscal-year-2017-projected-revenue) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/an54-gqss) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/an54-gqss/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/an54-gqss/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | an54-gqss |
| Name | Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Revenue |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | fy2016, fy2017, 2017 budget |
| Created | 2016-07-15T19:18:19Z |
| Publication Date | 2016-07-15T19:21:42Z |

## Description

Projected revenues for Fiscal Year 2017. This data was released as part of the Fiscal Year 2017 Budget Preliminary Forecast. For more information see https://www.cookcountyil.gov/Budget

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                          | Data Type | Render Type |
| ======== | ============== | ============================================================= | ============================================================= | ========= | =========== |
| Yes      | series tag     | fund                                                          | Fund                                                          | text      | text        |
| Yes      | series tag     | type                                                          | Type                                                          | text      | text        |
| Yes      | series tag     | revenue_source                                                | Revenue Source                                                | text      | text        |
| Yes      | numeric metric | fy2016_adopted_revenue                                        | FY2016 Adopted Revenue                                        | money     | money       |
| Yes      | numeric metric | fy2016_year_end_estimated_revenue                             | FY2016 Year End Estimated Revenue                             | money     | money       |
| Yes      | numeric metric | fy2017_preliminary_revenue_estimate                           | FY2017 Preliminary Revenue Estimate                           | money     | money       |
| Yes      | numeric metric | fy2017_preliminary_estimate_vs_fy2016_adopted_revenue         | FY2017 Preliminary Estimate vs FY2016 Adopted Revenue         | money     | money       |
| Yes      | numeric metric | fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent | FY2017 Preliminary Estimate vs FY2016 Adopted Revenue Percent | percent   | percent     |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:an54-gqss d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Property Taxes" t:revenue_source="Property Tax - Tax Levy" m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent=-13 m:fy2016_adopted_revenue=189087546 m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue=-24147052.8 m:fy2016_year_end_estimated_revenue=189087546 m:fy2017_preliminary_revenue_estimate=164940493.2

series e:an54-gqss d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Property Taxes" t:revenue_source="Property Tax - Tax Increment Financing Surplus" m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent=-56 m:fy2016_adopted_revenue=11266000 m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue=-6266000 m:fy2016_year_end_estimated_revenue=11266000 m:fy2017_preliminary_revenue_estimate=5000000

series e:an54-gqss d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Non-Property Taxes" t:revenue_source="Home Rule Sales Tax" m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent=26 m:fy2016_adopted_revenue=663500000 m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue=169200000 m:fy2016_year_end_estimated_revenue=648722000 m:fy2017_preliminary_revenue_estimate=832700000
```

## Meta Commands

```ls
metric m:fy2016_adopted_revenue p:double l:"FY2016 Adopted Revenue" t:dataTypeName=money

metric m:fy2016_year_end_estimated_revenue p:double l:"FY2016 Year End Estimated Revenue" t:dataTypeName=money

metric m:fy2017_preliminary_revenue_estimate p:double l:"FY2017 Preliminary Revenue Estimate" t:dataTypeName=money

metric m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue p:double l:"FY2017 Preliminary Estimate vs FY2016 Adopted Revenue" t:dataTypeName=money

metric m:fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent p:integer l:"FY2017 Preliminary Estimate vs FY2016 Adopted Revenue Percent" t:dataTypeName=percent

entity e:an54-gqss l:"Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Revenue" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/an54-gqss

property e:an54-gqss t:meta.view v:id=an54-gqss v:category="Finance & Administration" v:averageRating=0 v:name="Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Revenue" v:attribution="Cook County Department of Budget and Management Services"

property e:an54-gqss t:meta.view.license v:name="Public Domain"

property e:an54-gqss t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:an54-gqss t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| fund         | type               | revenue_source                                 | fy2016_adopted_revenue | fy2016_year_end_estimated_revenue | fy2017_preliminary_revenue_estimate | fy2017_preliminary_estimate_vs_fy2016_adopted_revenue | fy2017_preliminary_estimate_vs_fy2016_adopted_revenue_percent | 
| ============ | ================== | ============================================== | ====================== | ================================= | =================================== | ===================================================== | ============================================================= | 
| General Fund | Property Taxes     | Property Tax - Tax Levy                        | 189087546.00           | 189087546.00                      | 164940493.20                        | -24147052.80                                          | -13                                                           | 
| General Fund | Property Taxes     | Property Tax - Tax Increment Financing Surplus | 11266000.00            | 11266000.00                       | 5000000.00                          | -6266000.00                                           | -56                                                           | 
| General Fund | Non-Property Taxes | Home Rule Sales Tax                            | 663500000.00           | 648722000.00                      | 832700000.00                        | 169200000.00                                          | 26                                                            | 
| General Fund | Non-Property Taxes | County Use Tax                                 | 77000000.00            | 80363987.00                       | 80000000.00                         | 3000000.00                                            | 4                                                             | 
| General Fund | Non-Property Taxes | Off Track Betting Commission                   | 1150000.00             | 1201387.00                        | 1000000.00                          | -150000.00                                            | -13                                                           | 
| General Fund | Non-Property Taxes | Illinois Gaming - Casino                       | 8450000.00             | 8516954.00                        | 8500000.00                          | 50000.00                                              | 1                                                             | 
| General Fund | Non-Property Taxes | Retail Sale of Motor Vehicles Tax              | 3200000.00             | 3389396.00                        | 3400000.00                          | 200000.00                                             | 6                                                             | 
| General Fund | Non-Property Taxes | Retailer's Occupation Tax                      | 2440000.00             | 2998000.00                        | 3030000.00                          | 590000.00                                             | 24                                                            | 
| General Fund | Non-Property Taxes | Wheel Tax                                      | 4100000.00             | 4094270.00                        | 4200000.00                          | 100000.00                                             | 2                                                             | 
| General Fund | Non-Property Taxes | State Income Tax                               | 13900000.00            | 12927999.00                       | 13280000.00                         | -620000.00                                            | -4                                                            | 
```