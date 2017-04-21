# State Tax Receipts and Refunds FY 1992 through Most Recent Quarter, in Millions of Dollars

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-tax-receipts-and-refunds-fy-1992-through-most-recent-quarter-in-millions-of-dollars) |
| Metadata | [Link](https://data.iowa.gov/api/views/s98w-ib9t) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/s98w-ib9t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/s98w-ib9t/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | s98w-ib9t |
| Name | State Tax Receipts and Refunds FY 1992 through Most Recent Quarter, in Millions of Dollars |
| Attribution | Iowa Department of Revenue |
| Category | Government |
| Tags | state taxes |
| Created | 2015-01-13T14:53:14Z |
| Publication Date | 2016-01-04T22:00:30Z |

## Description

Monthly State revenue collections for FY 1992 through most recent quarter, in millions of dollars. Receipts are reported on a cash basis. Refunds are reported on an accrual basis.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                       | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================================================================================================ | ================================================== | ========= | =========== |
| Yes      | time           | fiscal_year                                                                                                                      | Fiscal Year                                        | number    | number      |
| Yes      | series tag     | fiscal_month                                                                                                                     | Fiscal Month                                       | text      | text        |
| Yes      | numeric metric | receipts_individual_income_tax_withholding                                                                                       | Receipts - Individual Income Tax Withholding       | number    | number      |
| Yes      | numeric metric | receipts_individual_income_tax_estimate_payments                                                                                 | Receipts - Individual Income Tax Estimate Payments | number    | number      |
| Yes      | numeric metric | receipts_individual_income_tax_returns                                                                                           | Receipts - Individual Income Tax Returns           | number    | number      |
| Yes      | numeric metric | receipts_sales_tax                                                                                                               | Receipts - Sales Tax                               | number    | number      |
| Yes      | numeric metric | receipts_use_tax                                                                                                                 | Receipts - Use Tax                                 | number    | number      |
| Yes      | numeric metric | receipts_corporation_income_tax                                                                                                  | Receipts - Corporation Income tax                  | number    | number      |
| Yes      | numeric metric | receipts_inheritance_tax                                                                                                         | Receipts - Inheritance Tax                         | number    | number      |
| Yes      | numeric metric | receipts_insurance_premium_tax                                                                                                   | Receipts - Insurance Premium Tax                   | number    | number      |
| Yes      | numeric metric | receipts_beer_tax                                                                                                                | Receipts - Beer Tax                                | number    | number      |
| Yes      | numeric metric | receipts_franchise_tax                                                                                                           | Receipts - Franchise Tax                           | number    | number      |
| Yes      | numeric metric | receipts_miscellaneous_taxes                                                                                                     | Receipts - Miscellaneous Taxes                     | number    | number      |
| Yes      | numeric metric | receipts_cigarette_tax                                                                                                           | Receipts - Cigarette Tax                           | number    | number      |
| Yes      | numeric metric | receipts_tobacco_tax                                                                                                             | Receipts - Tobacco Tax                             | number    | number      |
| Yes      | numeric metric | refunds_individual_income_tax                                                                                                    | Refunds - Individual Income Tax                    | number    | number      |
| Yes      | numeric metric | refunds_sales_tax                                                                                                                | Refunds - Sales Tax                                | number    | number      |
| Yes      | numeric metric | refunds_use_tax                                                                                                                  | Refunds - Use Tax                                  | number    | number      |
| Yes      | numeric metric | refunds_corporation_income_tax                                                                                                   | Refunds - Corporation Income Tax                   | number    | number      |
| Yes      | numeric metric | refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous | Refunds - Other Taxes                              | number    | number      |
| Yes      | numeric metric | refunds_motor_vehicle_fuel_tax                                                                                                   | Refunds - Motor Vehicle Fuel Tax                   | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s98w-ib9t d:1992-01-01T00:00:00.000Z t:fiscal_month=01-JUL m:receipts_cigarette_tax=7.76 m:receipts_use_tax=11.06 m:receipts_individual_income_tax_returns=0.85 m:refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous=0 m:receipts_individual_income_tax_withholding=71.19 m:refunds_use_tax=0.24 m:receipts_franchise_tax=2.36 m:receipts_individual_income_tax_estimate_payments=19.39 m:refunds_corporation_income_tax=5.38 m:refunds_motor_vehicle_fuel_tax=0.67 m:receipts_miscellaneous_taxes=4.7 m:receipts_beer_tax=1.12 m:receipts_inheritance_tax=7.19 m:refunds_sales_tax=3.37 m:receipts_tobacco_tax=0.3 m:receipts_corporation_income_tax=22.24 m:refunds_individual_income_tax=13.51 m:receipts_sales_tax=39.42 m:receipts_insurance_premium_tax=0.01

series e:s98w-ib9t d:1992-01-01T00:00:00.000Z t:fiscal_month=02-AUG m:receipts_cigarette_tax=8.82 m:receipts_use_tax=13.46 m:receipts_individual_income_tax_returns=4.05 m:refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous=0 m:receipts_individual_income_tax_withholding=109.99 m:refunds_use_tax=0.02 m:receipts_franchise_tax=0.09 m:receipts_individual_income_tax_estimate_payments=1.42 m:refunds_corporation_income_tax=2.65 m:refunds_motor_vehicle_fuel_tax=0.33 m:receipts_miscellaneous_taxes=-3.11 m:receipts_beer_tax=1.31 m:receipts_inheritance_tax=6.77 m:refunds_sales_tax=1.35 m:receipts_tobacco_tax=0.38 m:receipts_corporation_income_tax=8.38 m:refunds_individual_income_tax=4.89 m:receipts_sales_tax=100.78 m:receipts_insurance_premium_tax=0.01

series e:s98w-ib9t d:1992-01-01T00:00:00.000Z t:fiscal_month=03-SEP m:receipts_cigarette_tax=7.69 m:receipts_use_tax=4.81 m:receipts_individual_income_tax_returns=6.02 m:refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous=-0.2 m:receipts_individual_income_tax_withholding=92.69 m:refunds_use_tax=0.05 m:receipts_franchise_tax=3.11 m:receipts_individual_income_tax_estimate_payments=28.21 m:refunds_corporation_income_tax=3.67 m:refunds_motor_vehicle_fuel_tax=0.26 m:receipts_miscellaneous_taxes=-0.28 m:receipts_beer_tax=1.28 m:receipts_inheritance_tax=5.7 m:refunds_sales_tax=1.27 m:receipts_tobacco_tax=0.32 m:receipts_corporation_income_tax=16.44 m:refunds_individual_income_tax=2.71 m:receipts_sales_tax=64.91 m:receipts_insurance_premium_tax=0.01
```

## Meta Commands

```ls
metric m:receipts_individual_income_tax_withholding p:float l:"Receipts - Individual Income Tax Withholding" t:dataTypeName=number

metric m:receipts_individual_income_tax_estimate_payments p:float l:"Receipts - Individual Income Tax Estimate Payments" t:dataTypeName=number

metric m:receipts_individual_income_tax_returns p:float l:"Receipts - Individual Income Tax Returns" t:dataTypeName=number

metric m:receipts_sales_tax p:float l:"Receipts - Sales Tax" t:dataTypeName=number

metric m:receipts_use_tax p:float l:"Receipts - Use Tax" t:dataTypeName=number

metric m:receipts_corporation_income_tax p:float l:"Receipts - Corporation Income tax" t:dataTypeName=number

metric m:receipts_inheritance_tax p:float l:"Receipts - Inheritance Tax" t:dataTypeName=number

metric m:receipts_insurance_premium_tax p:float l:"Receipts - Insurance Premium Tax" t:dataTypeName=number

metric m:receipts_beer_tax p:float l:"Receipts - Beer Tax" t:dataTypeName=number

metric m:receipts_franchise_tax p:float l:"Receipts - Franchise Tax" t:dataTypeName=number

metric m:receipts_miscellaneous_taxes p:float l:"Receipts - Miscellaneous Taxes" d:"Miscellaneous taxes include multiple tax suspense, moneys and credits, drug stamps, and statewide property tax." t:dataTypeName=number

metric m:receipts_cigarette_tax p:float l:"Receipts - Cigarette Tax" t:dataTypeName=number

metric m:receipts_tobacco_tax p:float l:"Receipts - Tobacco Tax" t:dataTypeName=number

metric m:refunds_individual_income_tax p:float l:"Refunds - Individual Income Tax" t:dataTypeName=number

metric m:refunds_sales_tax p:float l:"Refunds - Sales Tax" t:dataTypeName=number

metric m:refunds_use_tax p:float l:"Refunds - Use Tax" t:dataTypeName=number

metric m:refunds_corporation_income_tax p:float l:"Refunds - Corporation Income Tax" t:dataTypeName=number

metric m:refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous p:float l:"Refunds - Other Taxes" d:"Includes refunds for the following taxes: Cigarette, Franchise, Inheritance, Insurance, Tobacco, and Miscellaneous" t:dataTypeName=number

metric m:refunds_motor_vehicle_fuel_tax p:float l:"Refunds - Motor Vehicle Fuel Tax" t:dataTypeName=number

entity e:s98w-ib9t l:"State Tax Receipts and Refunds FY 1992 through Most Recent Quarter, in Millions of Dollars" t:attribution="Iowa Department of Revenue" t:url=https://data.iowa.gov/api/views/s98w-ib9t

property e:s98w-ib9t t:meta.view v:id=s98w-ib9t v:category=Government v:attributionLink=https://tax.iowa.gov/ v:averageRating=0 v:name="State Tax Receipts and Refunds FY 1992 through Most Recent Quarter, in Millions of Dollars" v:attribution="Iowa Department of Revenue"

property e:s98w-ib9t t:meta.view.license v:name="Public Domain"

property e:s98w-ib9t t:meta.view.owner v:id=i3mx-stuy v:profileImageUrlMedium=/api/users/i3mx-stuy/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3mx-stuy/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/i3mx-stuy/profile_images/TINY v:displayName="Revenue, Research and Analysis"

property e:s98w-ib9t t:meta.view.tableauthor v:id=i3mx-stuy v:profileImageUrlMedium=/api/users/i3mx-stuy/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3mx-stuy/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/i3mx-stuy/profile_images/TINY v:roleName=editor v:displayName="Revenue, Research and Analysis"
```

## Top Records

```ls
| fiscal_year | fiscal_month | receipts_individual_income_tax_withholding | receipts_individual_income_tax_estimate_payments | receipts_individual_income_tax_returns | receipts_sales_tax | receipts_use_tax | receipts_corporation_income_tax | receipts_inheritance_tax | receipts_insurance_premium_tax | receipts_beer_tax | receipts_franchise_tax | receipts_miscellaneous_taxes | receipts_cigarette_tax | receipts_tobacco_tax | refunds_individual_income_tax | refunds_sales_tax | refunds_use_tax | refunds_corporation_income_tax | refunds_other_taxes_includes_refunds_for_the_following_taxes_cigarette_franchise_inheritance_insurance_tobacco_and_miscellaneous | refunds_motor_vehicle_fuel_tax | 
| =========== | ============ | ========================================== | ================================================ | ====================================== | ================== | ================ | =============================== | ======================== | ============================== | ================= | ====================== | ============================ | ====================== | ==================== | ============================= | ================= | =============== | ============================== | ================================================================================================================================ | ============================== | 
| 1992        | 01-JUL       | 71.19                                      | 19.39                                            | 0.85                                   | 39.42              | 11.06            | 22.24                           | 7.19                     | 0.01                           | 1.12              | 2.36                   | 4.70                         | 7.76                   | 0.30                 | 13.51                         | 3.37              | 0.24            | 5.38                           | 0.00                                                                                                                             | 0.67                           | 
| 1992        | 02-AUG       | 109.99                                     | 1.42                                             | 4.05                                   | 100.78             | 13.46            | 8.38                            | 6.77                     | 0.01                           | 1.31              | 0.09                   | -3.11                        | 8.82                   | 0.38                 | 4.89                          | 1.35              | 0.02            | 2.65                           | 0.00                                                                                                                             | 0.33                           | 
| 1992        | 03-SEP       | 92.69                                      | 28.21                                            | 6.02                                   | 64.91              | 4.81             | 16.44                           | 5.70                     | 0.01                           | 1.28              | 3.11                   | -0.28                        | 7.69                   | 0.32                 | 2.71                          | 1.27              | 0.05            | 3.67                           | -0.20                                                                                                                            | 0.26                           | 
| 1992        | 04-OCT       | 74.94                                      | 22.82                                            | 2.00                                   | 42.74              | 11.97            | 29.62                           | 7.44                     | 0.00                           | 0.97              | 2.75                   | 0.29                         | 8.37                   | 0.35                 | 4.36                          | 1.40              | 0.16            | 2.87                           | -0.02                                                                                                                            | 0.32                           | 
| 1992        | 05-NOV       | 113.45                                     | 1.06                                             | 1.27                                   | 91.88              | 13.13            | 12.33                           | 5.51                     | 0.03                           | 1.07              | 0.06                   | 0.37                         | 7.22                   | 0.32                 | 2.34                          | 1.52              | 0.06            | 2.64                           | 0.00                                                                                                                             | 0.24                           | 
| 1992        | 06-DEC       | 91.94                                      | 16.09                                            | 2.42                                   | 68.88              | 5.49             | 16.07                           | 5.52                     | 0.01                           | 0.89              | 2.88                   | -0.19                        | 7.40                   | 0.33                 | 2.84                          | 0.25              | 0.02            | 4.17                           | -0.07                                                                                                                            | 0.29                           | 
| 1992        | 07-JAN       | 89.81                                      | 53.66                                            | 4.19                                   | 43.07              | 13.41            | 28.17                           | 8.13                     | 0.03                           | 1.09              | 2.86                   | -0.17                        | 8.05                   | 0.35                 | 3.20                          | 1.37              | 0.04            | 5.56                           | -0.01                                                                                                                            | 0.21                           | 
| 1992        | 08-FEB       | 124.26                                     | 12.27                                            | 10.26                                  | 91.40              | 14.47            | 9.18                            | 5.01                     | 20.59                          | 0.90              | 0.31                   | -0.20                        | 6.46                   | 0.26                 | 13.45                         | 1.73              | 0.05            | 10.18                          | 0.00                                                                                                                             | 0.27                           | 
| 1992        | 09-MAR       | 92.82                                      | 3.09                                             | 48.63                                  | 59.56              | 4.73             | 12.69                           | 6.33                     | 28.94                          | 0.82              | 0.96                   | 0.25                         | 8.07                   | 0.27                 | 37.46                         | 1.43              | 0.03            | 4.09                           | 0.00                                                                                                                             | 0.20                           | 
| 1992        | 10-APR       | 76.11                                      | 22.95                                            | 61.48                                  | 39.20              | 11.76            | 22.21                           | 5.67                     | 0.24                           | 0.98              | 3.34                   | 0.26                         | 7.22                   | 0.31                 | 55.82                         | 0.74              | 0.07            | 1.49                           | -0.43                                                                                                                            | 0.23                           | 
```