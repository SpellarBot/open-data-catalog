# Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Expenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-preliminary-budget-fiscal-year-2017-projected-expenses) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/vahr-6ny2) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vahr-6ny2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/vahr-6ny2/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | vahr-6ny2 |
| Name | Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Expenses |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | fy2017, 2017 budget |
| Created | 2016-07-15T19:29:32Z |
| Publication Date | 2016-07-15T19:32:18Z |

## Description

Projected expenses for Fiscal Year 2017. This data was released as part of the Fiscal Year 2017 Budget Preliminary Forecast. For more information see https://www.cookcountyil.gov/Budget

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | fund                                     | Fund                                     | text      | text        |
| Yes      | series tag     | department_number                        | Department Number                        | text      | number      |
| Yes      | series tag     | description                              | Description                              | text      | text        |
| Yes      | numeric metric | fy2016_approved_adopted_expenditures     | FY2016 Approved & Adopted Expenditures   | money     | money       |
| Yes      | numeric metric | fy2016_estimated_expenditures            | FY2016 Estimated Expenditures            | money     | money       |
| Yes      | series tag     | department_estimated_fy2017_expenditures | Department Estimated FY2017 Expenditures | text      | money       |
| Yes      | numeric metric | executive_fy2017_estimate_expenditures   | Executive FY2017 Estimate Expenditures   | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vahr-6ny2 d:2017-01-01T00:00:00.000Z t:description="Department of Human Rights and Ethics" t:department_number=2 t:department_estimated_fy2017_expenditures=838636 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=815762 m:fy2016_estimated_expenditures=755597 m:executive_fy2017_estimate_expenditures=839459

series e:vahr-6ny2 d:2017-01-01T00:00:00.000Z t:description=Revenue t:department_number=7 t:department_estimated_fy2017_expenditures=7478575 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=7044988 m:fy2016_estimated_expenditures=6866606 m:executive_fy2017_estimate_expenditures=7345644

series e:vahr-6ny2 d:2017-01-01T00:00:00.000Z t:description="Risk Management" t:department_number=8 t:department_estimated_fy2017_expenditures=1673704 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=1606087 m:fy2016_estimated_expenditures=1621067 m:executive_fy2017_estimate_expenditures=1671629
```

## Meta Commands

```ls
metric m:fy2016_approved_adopted_expenditures p:integer l:"FY2016 Approved & Adopted Expenditures" t:dataTypeName=money

metric m:fy2016_estimated_expenditures p:integer l:"FY2016 Estimated Expenditures" t:dataTypeName=money

metric m:executive_fy2017_estimate_expenditures p:integer l:"Executive FY2017 Estimate Expenditures" t:dataTypeName=money

entity e:vahr-6ny2 l:"Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Expenses" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/vahr-6ny2

property e:vahr-6ny2 t:meta.view v:id=vahr-6ny2 v:category="Finance & Administration" v:averageRating=0 v:name="Fiscal Year 2017 Preliminary Budget - Fiscal Year 2017 Projected Expenses" v:attribution="Cook County Department of Budget and Management Services"

property e:vahr-6ny2 t:meta.view.license v:name="Public Domain"

property e:vahr-6ny2 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:vahr-6ny2 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| fund         | department_number | description                                           | fy2016_approved_adopted_expenditures | fy2016_estimated_expenditures | department_estimated_fy2017_expenditures | executive_fy2017_estimate_expenditures | 
| ============ | ================= | ===================================================== | ==================================== | ============================= | ======================================== | ====================================== | 
| General Fund | 2                 | Department of Human Rights and Ethics                 | 815762                               | 755597                        | 838636                                   | 839459                                 | 
| General Fund | 7                 | Revenue                                               | 7044988                              | 6866606                       | 7478575                                  | 7345644                                | 
| General Fund | 8                 | Risk Management                                       | 1606087                              | 1621067                       | 1673704                                  | 1671629                                | 
| General Fund | 9                 | Enterprise Technology                                 | 14057116                             | 13578813                      | 25675873                                 | 25675946                               | 
| General Fund | 10                | Office of the President                               | 1982892                              | 1923274                       | 2047953                                  | 2047953                                | 
| General Fund | 11                | Office of the Chief Administrative Officer            | 2401356                              | 2474759                       | 2521825                                  | 2521825                                | 
| General Fund | 13                | Planning and Development                              | 1023036                              | 1063969                       | 1124257                                  | 1124894                                | 
| General Fund | 14                | Budget and Management Services                        | 1629836                              | 1708531                       | 1723692                                  | 1723692                                | 
| General Fund | 18                | Office of the Secretary to the Board of Commissioners | 908996                               | 897961                        | 921357                                   | 921357                                 | 
| General Fund | 19                | Employee Appeals Board                                | 100870                               | 92445                         | 98445                                    | 98445                                  | 
```