# Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-preliminary-budget-fiscal-year-2016-projected-revenue) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ubkc-mnqr) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ubkc-mnqr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ubkc-mnqr/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ubkc-mnqr |
| Name | Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Revenue |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | fy2016, fy2017, 2017 budget |
| Created | 2016-07-15T18:47:30Z |
| Publication Date | 2016-07-15T19:09:15Z |

## Description

Projected year end revenues for Fiscal Year 2016. This data was released as part of the Fiscal Year 2017 Budget Preliminary Forecast. For more information see https://www.cookcountyil.gov/Budget

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | fund                                        | Fund                                        | text      | text        |
| Yes      | series tag     | type                                        | Type                                        | text      | text        |
| Yes      | series tag     | revenue_source                              | Revenue Source                              | text      | text        |
| Yes      | numeric metric | fy2016_adopted_revenue                      | FY2016 Adopted Revenue                      | money     | money       |
| Yes      | numeric metric | fy2016_dec_may_actual_revenue               | FY2016 Dec ? May Actual Revenue             | money     | money       |
| Yes      | numeric metric | fy2016_jun_nov_estimated_revenue            | FY2016 Jun ? Nov Estimated Revenue          | money     | money       |
| Yes      | numeric metric | fy2016_year_end_estimated_revenue           | FY2016 Year End Estimated Revenue           | money     | money       |
| Yes      | numeric metric | fy2016_estimated_vs_adopted_revenue         | FY2016 Estimated vs Adopted Revenue         | money     | money       |
| Yes      | numeric metric | fy2016_estimated_vs_adopted_revenue_percent | FY2016 Estimated vs Adopted Revenue Percent | percent   | percent     |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ubkc-mnqr d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Property Taxes" t:revenue_source="Property Tax - Tax Levy" m:fy2016_estimated_vs_adopted_revenue=0 m:fy2016_dec_may_actual_revenue=33808577 m:fy2016_estimated_vs_adopted_revenue_percent=0 m:fy2016_adopted_revenue=188852350 m:fy2016_jun_nov_estimated_revenue=33808577 m:fy2016_year_end_estimated_revenue=188852350

series e:ubkc-mnqr d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Property Taxes" t:revenue_source="Property Tax - Tax Increment Financing Surplus" m:fy2016_estimated_vs_adopted_revenue=0 m:fy2016_dec_may_actual_revenue=10034000 m:fy2016_estimated_vs_adopted_revenue_percent=0 m:fy2016_adopted_revenue=11266000 m:fy2016_jun_nov_estimated_revenue=1232000 m:fy2016_year_end_estimated_revenue=11266000

series e:ubkc-mnqr d:2017-01-01T00:00:00.000Z t:fund="General Fund" t:type="Non-Property Taxes" t:revenue_source="Home Rule Sales Tax" m:fy2016_estimated_vs_adopted_revenue=-14778000 m:fy2016_dec_may_actual_revenue=233280540 m:fy2016_estimated_vs_adopted_revenue_percent=-2 m:fy2016_adopted_revenue=663500000 m:fy2016_jun_nov_estimated_revenue=415441460 m:fy2016_year_end_estimated_revenue=648722000
```

## Meta Commands

```ls
metric m:fy2016_adopted_revenue p:integer l:"FY2016 Adopted Revenue" t:dataTypeName=money

metric m:fy2016_dec_may_actual_revenue p:integer l:"FY2016 Dec ? May Actual Revenue" t:dataTypeName=money

metric m:fy2016_jun_nov_estimated_revenue p:integer l:"FY2016 Jun ? Nov Estimated Revenue" t:dataTypeName=money

metric m:fy2016_year_end_estimated_revenue p:integer l:"FY2016 Year End Estimated Revenue" t:dataTypeName=money

metric m:fy2016_estimated_vs_adopted_revenue p:double l:"FY2016 Estimated vs Adopted Revenue" t:dataTypeName=money

metric m:fy2016_estimated_vs_adopted_revenue_percent p:integer l:"FY2016 Estimated vs Adopted Revenue Percent" t:dataTypeName=percent

entity e:ubkc-mnqr l:"Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Revenue" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/ubkc-mnqr

property e:ubkc-mnqr t:meta.view v:id=ubkc-mnqr v:category="Finance & Administration" v:averageRating=0 v:name="Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Revenue" v:attribution="Cook County Department of Budget and Management Services"

property e:ubkc-mnqr t:meta.view.license v:name="Public Domain"

property e:ubkc-mnqr t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:ubkc-mnqr t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| fund         | type               | revenue_source                                 | fy2016_adopted_revenue | fy2016_dec_may_actual_revenue | fy2016_jun_nov_estimated_revenue | fy2016_year_end_estimated_revenue | fy2016_estimated_vs_adopted_revenue | fy2016_estimated_vs_adopted_revenue_percent | 
| ============ | ================== | ============================================== | ====================== | ============================= | ================================ | ================================= | =================================== | =========================================== | 
| General Fund | Property Taxes     | Property Tax - Tax Levy                        | 188852350              | 33808577                      | 33808577                         | 188852350                         | 0.00                                | 0                                           | 
| General Fund | Property Taxes     | Property Tax - Tax Increment Financing Surplus | 11266000               | 10034000                      | 1232000                          | 11266000                          | 0.00                                | 0                                           | 
| General Fund | Non-Property Taxes | Home Rule Sales Tax                            | 663500000              | 233280540                     | 415441460                        | 648722000                         | -14778000.00                        | -2                                          | 
| General Fund | Non-Property Taxes | County Use Tax                                 | 77000000               | 39973472                      | 40390515                         | 80363987                          | 3363987.00                          | 4                                           | 
| General Fund | Non-Property Taxes | Off Track Betting Commission                   | 1150000                | 751387                        | 450000                           | 1201387                           | 51387.00                            | 4                                           | 
| General Fund | Non-Property Taxes | Illinois Gaming - Casino                       | 8450000                | 4216954                       | 4300000                          | 8516954                           | 66954.00                            | 1                                           | 
| General Fund | Non-Property Taxes | Retail Sale of Motor Vehicles Tax              | 3200000                | 1626541                       | 1762855                          | 3389396                           | 189396.00                           | 6                                           | 
| General Fund | Non-Property Taxes | Retailer's Occupation Tax                      | 2440000                | 1456915                       | 1541085                          | 2998000                           | 558000.00                           | 23                                          | 
| General Fund | Non-Property Taxes | Wheel Tax                                      | 4100000                | 242595                        | 3851675                          | 4094270                           | -5730.00                            | 0                                           | 
| General Fund | Non-Property Taxes | State Income Tax                               | 13900000               | 7075444                       | 5852555                          | 12927999                          | -972001.00                          | -7                                          | 
```