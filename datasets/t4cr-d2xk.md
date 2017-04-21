# Fiscal Year 2017 Preliminary Budget - Special Purpose Fund Outlook

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-preliminary-budget-special-purpose-fund-outlook) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/t4cr-d2xk) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t4cr-d2xk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/t4cr-d2xk/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | t4cr-d2xk |
| Name | Fiscal Year 2017 Preliminary Budget - Special Purpose Fund Outlook |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | fy2017, 2017 budget |
| Created | 2016-07-15T19:33:26Z |
| Publication Date | 2016-07-15T19:37:49Z |

## Description

Special Purpose Fund Outlook for Fiscal Year 2017. FY17 Ending Fund Balance Estimate calculated in accordance to FY17 Executive Expenditure Estimate. This data was released as part of the Fiscal Year 2017 Budget Preliminary Forecast. For more information see https://www.cookcountyil.gov/Budget

The County?s Annual Appropriation Bill contains Special Purpose
Funds in addition to the General Fund, Health Fund and the Debt
Service Fund. Special Purpose Funds are established for a special
and dedicated purpose, and are considered to be self-balancing.
Self-balancing means that the appropriated revenues for each of
the special purpose funds supports the required expenditures for
the budgeted fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | department_number                     | Department Number                     | text      | number      |
| Yes      | series tag     | description                           | Description                           | text      | text        |
| Yes      | numeric metric | fy15_ending_fund_balance              | FY15 Ending Fund Balance              | money     | money       |
| Yes      | numeric metric | fy16_revised_revenue_projection       | FY16 Revised Revenue Projection       | money     | money       |
| Yes      | numeric metric | fy16_estimated_total_resources        | FY16 Estimated Total Resources        | money     | money       |
| Yes      | numeric metric | fy16_projected_expenditures           | FY16 Projected Expenditures           | money     | money       |
| Yes      | numeric metric | fy16_projected_ending_fund_balance    | FY16 Projected Ending Fund Balance    | money     | money       |
| Yes      | numeric metric | fy17_revenue_estimate                 | FY17 Revenue Estimate                 | money     | money       |
| Yes      | numeric metric | fy17_total_resources                  | FY17 Total Resources                  | money     | money       |
| Yes      | numeric metric | fy17_executive_estimated_expenditures | FY17 Executive Estimated Expenditures | money     | money       |
| Yes      | numeric metric | fy17_ending_fund_balance_estimate     | FY17 Ending Fund Balance Estimate     | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t4cr-d2xk d:2017-01-01T00:00:00.000Z t:description="MFT Illinois First (1st)" t:department_number=501 m:fy16_projected_ending_fund_balance=5368307 m:fy17_revenue_estimate=45465702 m:fy16_estimated_total_resources=30221906 m:fy17_total_resources=50834009 m:fy16_projected_expenditures=24853599 m:fy15_ending_fund_balance=4296671 m:fy17_ending_fund_balance_estimate=5368307 m:fy16_revised_revenue_projection=25925235 m:fy17_executive_estimated_expenditures=45465702

series e:t4cr-d2xk d:2017-01-01T00:00:00.000Z t:description="Animal Control Department" t:department_number=510 m:fy16_projected_ending_fund_balance=8675668 m:fy17_revenue_estimate=3750000 m:fy16_estimated_total_resources=12209396 m:fy17_total_resources=12425668 m:fy16_projected_expenditures=3533728 m:fy15_ending_fund_balance=8832644 m:fy17_ending_fund_balance_estimate=8589614 m:fy16_revised_revenue_projection=3376752 m:fy17_executive_estimated_expenditures=3836054

series e:t4cr-d2xk d:2017-01-01T00:00:00.000Z t:description="County Clerk-Election Division Fund" t:department_number=524 m:fy17_revenue_estimate=21291521 m:fy16_estimated_total_resources=25186174 m:fy17_total_resources=21291521 m:fy16_projected_expenditures=25186174 m:fy17_ending_fund_balance_estimate=0 m:fy16_revised_revenue_projection=25186174 m:fy17_executive_estimated_expenditures=21291521
```

## Meta Commands

```ls
metric m:fy15_ending_fund_balance p:integer l:"FY15 Ending Fund Balance" t:dataTypeName=money

metric m:fy16_revised_revenue_projection p:integer l:"FY16 Revised Revenue Projection" t:dataTypeName=money

metric m:fy16_estimated_total_resources p:integer l:"FY16 Estimated Total Resources" t:dataTypeName=money

metric m:fy16_projected_expenditures p:integer l:"FY16 Projected Expenditures" t:dataTypeName=money

metric m:fy16_projected_ending_fund_balance p:integer l:"FY16 Projected Ending Fund Balance" t:dataTypeName=money

metric m:fy17_revenue_estimate p:integer l:"FY17 Revenue Estimate" t:dataTypeName=money

metric m:fy17_total_resources p:integer l:"FY17 Total Resources" t:dataTypeName=money

metric m:fy17_executive_estimated_expenditures p:integer l:"FY17 Executive Estimated Expenditures" t:dataTypeName=money

metric m:fy17_ending_fund_balance_estimate p:integer l:"FY17 Ending Fund Balance Estimate" t:dataTypeName=money

entity e:t4cr-d2xk l:"Fiscal Year 2017 Preliminary Budget - Special Purpose Fund Outlook" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/t4cr-d2xk

property e:t4cr-d2xk t:meta.view v:id=t4cr-d2xk v:category="Finance & Administration" v:averageRating=0 v:name="Fiscal Year 2017 Preliminary Budget - Special Purpose Fund Outlook" v:attribution="Cook County Department of Budget and Management Services"

property e:t4cr-d2xk t:meta.view.license v:name="Public Domain"

property e:t4cr-d2xk t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:t4cr-d2xk t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| department_number | description                                      | fy15_ending_fund_balance | fy16_revised_revenue_projection | fy16_estimated_total_resources | fy16_projected_expenditures | fy16_projected_ending_fund_balance | fy17_revenue_estimate | fy17_total_resources | fy17_executive_estimated_expenditures | fy17_ending_fund_balance_estimate | 
| ================= | ================================================ | ======================== | =============================== | ============================== | =========================== | ================================== | ===================== | ==================== | ===================================== | ================================= | 
| 501               | MFT Illinois First (1st)                         | 4296671                  | 25925235                        | 30221906                       | 24853599                    | 5368307                            | 45465702              | 50834009             | 45465702                              | 5368307                           | 
| 510               | Animal Control Department                        | 8832644                  | 3376752                         | 12209396                       | 3533728                     | 8675668                            | 3750000               | 12425668             | 3836054                               | 8589614                           | 
| 524               | County Clerk-Election Division Fund              |                          | 25186174                        | 25186174                       | 25186174                    |                                    | 21291521              | 21291521             | 21291521                              | 0                                 | 
| 525               | Board of Election Commissioners-Election Fund    |                          | 18882955                        | 18882955                       | 18882955                    |                                    | 1081992               | 1081992              | 1081992                               | 0                                 | 
| 527               | County Recorder Document Storage System Fund     | 1302363                  | 2999928                         | 4302291                        | 4845274                     | -542983                            | 3059927               | 2516944              | 5012708                               | -2495764                          | 
| 528               | Circuit Court Automation Fund                    | -9789575                 | 11419000                        | 1629425                        | 9372683                     | -7743258                           | 10400000              | 2656742              | 10300000                              | -7643258                          | 
| 529               | Clerk of the Circuit Court Document Storage Fund | -7585339                 | 10372000                        | 2786661                        | 8278132                     | -5491471                           | 9100000               | 3608529              | 9000000                               | -5391471                          | 
| 530               | Cook County Law Library                          | -956792                  | 5000000                         | 4043208                        | 4862261                     | -819054                            | 5000000               | 4180946              | 4884721                               | -703774                           | 
| 531               | Circuit Court-Illinois Dispute Resolution Fund   | 101323                   | 165000                          | 266323                         | 192553                      | 73770                              | 165000                | 238770               | 221678                                | 17092                             | 
| 532               | Adult Probation/Probation Service Fee Fund       | 1621088                  | 3854592                         | 5475680                        | 3857572                     | 1618108                            | 3854000               | 5472108              | 4103037                               | 1369071                           | 
```