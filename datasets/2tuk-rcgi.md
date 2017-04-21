# Home Performance Energy Efficiency Projects in Maryland

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-performance-energy-efficiency-projects-in-maryland-b79b9) |
| Metadata | [Link](https://data.maryland.gov/api/views/2tuk-rcgi) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2tuk-rcgi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2tuk-rcgi/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2tuk-rcgi |
| Name | Home Performance Energy Efficiency Projects in Maryland |
| Attribution | Maryland Energy Administration |
| Category | Energy and Environment |
| Tags | energy efficiency, energy savings, empower maryland, empower md, empower, energy efficiency grants, energy efficency loans, energy conservation, home performance rebate program, home performance u... |
| Created | 2012-08-09T17:41:44Z |
| Publication Date | 2013-09-16T15:18:00Z |

## Description

Through grants and loans, the Maryland Energy Administration has contributed to the growth of energy efficiency industries, and has helped reduce statewide energy consumption.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                                | Data Type | Render Type |
| ======== | ============== | ================================================ | =================================================== | ========= | =========== |
| No       | time           | :updated_at                                      | updated_at                                          | meta_data | meta_data   |
| Yes      | series tag     | program                                          | Program:                                            | text      | text        |
| Yes      | series tag     | program_link                                     | Program link:                                       | url       | url         |
| Yes      | series tag     | county                                           | County:                                             | text      | text        |
| Yes      | numeric metric | savings_electricity_consumption_reduction_in_kwh | Savings (electricity consumption reduction in kwh): | number    | number      |
| Yes      | numeric metric | mea_contribution                                 | MEA contribution:                                   | money     | money       |
| Yes      | numeric metric | total_project_cost                               | Total project cost:                                 | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2tuk-rcgi d:2012-08-09T14:51:59.000Z t:county=Howard t:program="Home Performance Rebate Program" t:program_link=http://energy.maryland.gov/homeperformance/index.html m:savings_electricity_consumption_reduction_in_kwh=0.767 m:total_project_cost=1095 m:mea_contribution=483.25

series e:2tuk-rcgi d:2012-08-09T14:52:04.000Z t:county="Prince George's" t:program="Home Performance Rebate Program" t:program_link=http://energy.maryland.gov/homeperformance/index.html m:savings_electricity_consumption_reduction_in_kwh=0.666 m:total_project_cost=952 m:mea_contribution=398.2

series e:2tuk-rcgi d:2012-08-09T14:52:04.000Z t:county="Anne Arundel" t:program="Home Performance Rebate Program" t:program_link=http://energy.maryland.gov/homeperformance/index.html m:savings_electricity_consumption_reduction_in_kwh=0.77 m:total_project_cost=1100 m:mea_contribution=485
```

## Meta Commands

```ls
metric m:savings_electricity_consumption_reduction_in_kwh p:float l:"Savings (electricity consumption reduction in kwh):" t:dataTypeName=number

metric m:mea_contribution p:double l:"MEA contribution:" t:dataTypeName=money

metric m:total_project_cost p:integer l:"Total project cost:" t:dataTypeName=money

entity e:2tuk-rcgi l:"Home Performance Energy Efficiency Projects in Maryland" t:attribution="Maryland Energy Administration" t:url=https://data.maryland.gov/api/views/2tuk-rcgi

property e:2tuk-rcgi t:meta.view v:id=2tuk-rcgi v:category="Energy and Environment" v:attributionLink=http://energy.maryland.gov/ v:averageRating=0 v:name="Home Performance Energy Efficiency Projects in Maryland" v:attribution="Maryland Energy Administration"

property e:2tuk-rcgi t:meta.view.owner v:id=rajf-egfu v:screenName=Dlauf v:displayName=Dlauf

property e:2tuk-rcgi t:meta.view.tableauthor v:id=rajf-egfu v:screenName=Dlauf v:roleName=editor v:displayName=Dlauf
```

## Top Records

```ls
| :updated_at | program                         | program_link                                                  | county          | savings_electricity_consumption_reduction_in_kwh | mea_contribution | total_project_cost | 
| =========== | =============================== | ============================================================= | =============== | ================================================ | ================ | ================== | 
| 1344523919  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Howard          | 0.76700000000000002                              | 483.25           | 1095               | 
| 1344523924  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Prince George's | 0.66600000000000004                              | 398.2            | 952                | 
| 1344523924  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Anne Arundel    | 0.77                                             | 485              | 1100               | 
| 1344523929  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Harford         | 0.81899999999999995                              | 412.5            | 1170.25            | 
| 1344523933  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Baltimore       | 0.79100000000000004                              | 495.5            | 1130               | 
| 1344523935  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Frederick       | 0.65900000000000003                              | 329.35           | 941                | 
| 1344523937  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Anne Arundel    | 0.83199999999999996                              | 516.15           | 1189               | 
| 1344523943  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Prince George's | 0.7                                              | 450              | 1000               | 
| 1344523948  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Prince George's | 0.74                                             | 434.77           | 1056.5             | 
| 1344523949  | Home Performance Rebate Program | [http://energy.maryland.gov/homeperformance/index.html, null] | Montgomery      | 0.68700000000000006                              | 443.35           | 981                | 
```