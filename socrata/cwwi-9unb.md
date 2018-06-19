# Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Expenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fiscal-year-2017-preliminary-budget-fiscal-year-2016-projected-expenses) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cwwi-9unb) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cwwi-9unb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cwwi-9unb/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cwwi-9unb |
| Name | Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Expenses |
| Attribution | Cook County Department of Budget and Management Services |
| Category | Finance & Administration |
| Tags | fy2016, fy2017, 2017 budget |
| Created | 2016-07-15T19:23:25Z |
| Publication Date | 2016-07-15T19:27:13Z |

## Description

Projected expenses for Fiscal Year 2016. This data was released as part of the Fiscal Year 2017 Budget Preliminary Forecast. For more information see https://www.cookcountyil.gov/Budget

## Columns

```ls
| Included | Schema Type    | Field Name                                            | Name                                                         | Data Type | Render Type |
| ======== | ============== | ===================================================== | ============================================================ | ========= | =========== |
| Yes      | series tag     | fund                                                  | Fund                                                         | text      | text        |
| Yes      | series tag     | dept                                                  | Department Number                                            | text      | number      |
| Yes      | series tag     | description                                           | Description                                                  | text      | text        |
| Yes      | numeric metric | fy2016_approved_adopted_expenditures                  | FY2016 Approved & Adopted Expenditures                       | money     | money       |
| Yes      | numeric metric | fy2016_adjusted_appropriation                         | FY2016 Adjusted Appropriation                                | money     | money       |
| Yes      | numeric metric | fy2016_december_may_expenditures                      | FY2016 December - May Expenditures                           | money     | money       |
| Yes      | numeric metric | june_november_estimated_expenditures_and_encumbrances | FY2016 June - November Estimated Expenditures & Encumbrances | money     | money       |
| Yes      | numeric metric | total_fy2016_estimated_expenditures                   | Total FY2016 Estimated Expenditures                          | money     | money       |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cwwi-9unb d:2017-01-01T00:00:00.000Z t:description="Department of Human Rights and Ethics" t:dept=2 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=815762 m:fy2016_adjusted_appropriation=809712 m:june_november_estimated_expenditures_and_encumbrances=439758 m:fy2016_december_may_expenditures=315839 m:total_fy2016_estimated_expenditures=755597

series e:cwwi-9unb d:2017-01-01T00:00:00.000Z t:description=Revenue t:dept=7 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=7044988 m:fy2016_adjusted_appropriation=6995823 m:june_november_estimated_expenditures_and_encumbrances=4333592 m:fy2016_december_may_expenditures=2533014 m:total_fy2016_estimated_expenditures=6866606

series e:cwwi-9unb d:2017-01-01T00:00:00.000Z t:description="Risk Management" t:dept=8 t:fund="General Fund" m:fy2016_approved_adopted_expenditures=1606087 m:fy2016_adjusted_appropriation=1599137 m:june_november_estimated_expenditures_and_encumbrances=877320 m:fy2016_december_may_expenditures=743747 m:total_fy2016_estimated_expenditures=1621067
```

## Meta Commands

```ls
metric m:fy2016_approved_adopted_expenditures p:integer l:"FY2016 Approved & Adopted Expenditures" t:dataTypeName=money

metric m:fy2016_adjusted_appropriation p:integer l:"FY2016 Adjusted Appropriation" t:dataTypeName=money

metric m:fy2016_december_may_expenditures p:integer l:"FY2016 December - May Expenditures" t:dataTypeName=money

metric m:june_november_estimated_expenditures_and_encumbrances p:integer l:"FY2016 June - November Estimated Expenditures & Encumbrances" t:dataTypeName=money

metric m:total_fy2016_estimated_expenditures p:integer l:"Total FY2016 Estimated Expenditures" t:dataTypeName=money

entity e:cwwi-9unb l:"Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Expenses" t:attribution="Cook County Department of Budget and Management Services" t:url=https://datacatalog.cookcountyil.gov/api/views/cwwi-9unb

property e:cwwi-9unb t:meta.view v:id=cwwi-9unb v:category="Finance & Administration" v:averageRating=0 v:name="Fiscal Year 2017 Preliminary Budget - Fiscal Year 2016 Projected Expenses" v:attribution="Cook County Department of Budget and Management Services"

property e:cwwi-9unb t:meta.view.license v:name="Public Domain"

property e:cwwi-9unb t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:cwwi-9unb t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| fund         | dept | description                                           | fy2016_approved_adopted_expenditures | fy2016_adjusted_appropriation | fy2016_december_may_expenditures | june_november_estimated_expenditures_and_encumbrances | total_fy2016_estimated_expenditures | 
| ============ | ==== | ===================================================== | ==================================== | ============================= | ================================ | ===================================================== | =================================== | 
| General Fund | 2    | Department of Human Rights and Ethics                 | 815762                               | 809712                        | 315839                           | 439758                                                | 755597                              | 
| General Fund | 7    | Revenue                                               | 7044988                              | 6995823                       | 2533014                          | 4333592                                               | 6866606                             | 
| General Fund | 8    | Risk Management                                       | 1606087                              | 1599137                       | 743747                           | 877320                                                | 1621067                             | 
| General Fund | 9    | Enterprise Technology                                 | 14057116                             | 13950162                      | 6541537                          | 7037276                                               | 13578813                            | 
| General Fund | 10   | Office of the President                               | 1982892                              | 1972705                       | 968774                           | 954500                                                | 1923274                             | 
| General Fund | 11   | Office of the Chief Administrative Officer            | 2401356                              | 2385269                       | 1061183                          | 1413576                                               | 2474759                             | 
| General Fund | 13   | Planning and Development                              | 1023036                              | 1008930                       | 508529                           | 555440                                                | 1063969                             | 
| General Fund | 14   | Budget and Management Services                        | 1629836                              | 1632839                       | 834928                           | 873603                                                | 1708531                             | 
| General Fund | 18   | Office of the Secretary to the Board of Commissioners | 908996                               | 898759                        | 594509                           | 303451                                                | 897961                              | 
| General Fund | 19   | Employee Appeals Board                                | 100870                               | 98584                         | 30390                            | 62055                                                 | 92445                               | 
```