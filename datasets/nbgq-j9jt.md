# Fair Student Funding Budget Detail 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fair-student-funding-budget-detail-2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nbgq-j9jt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nbgq-j9jt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nbgq-j9jt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nbgq-j9jt |
| Name | Fair Student Funding Budget Detail 2 |
| Category | Education |
| Created | 2015-10-19T19:23:23Z |
| Publication Date | 2015-10-19T19:30:25Z |

## Description

Fair Student Funding Budget Detail FY 2015 - Part II This detail data contains one row for each school's data and calculations displayed on the Details screen starting from the "TOTAL FAIR STUDENT FUNDING WEIGHTED REGISTER AND FORMULA" to the bottom of the page.
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Included | Schema Type    | Field Name                                                                  | Name                                                                          | Data Type     | Render Type   |
| ======== | ============== | =========================================================================== | ============================================================================= | ============= | ============= |
| Yes      | time           | fiscal_year                                                                 | Fiscal_Year                                                                   | number        | text          |
| Yes      | series tag     | location                                                                    | Location                                                                      | text          | text          |
| Yes      | numeric metric | total_column_n_fy14_actual_registers                                        | Total Column N: FY14 Actual Registers                                         | number        | number        |
| Yes      | numeric metric | total_column_o_projected_register                                           | Total Column O: Projected Register                                            | number        | number        |
| Yes      | numeric metric | total_column_p_projected_formula                                            | Total Column P: Projected Formula                                             | money         | money         |
| Yes      | numeric metric | total_column_q_register_change                                              | Total Column Q: Register Change                                               | number        | number        |
| Yes      | numeric metric | total_column_r_register_dollar_change                                       | Total Column R: Register Dollar Change                                        | money         | money         |
| Yes      | numeric metric | weighted_register                                                           | Weighted Register                                                             | number        | number        |
| Yes      | numeric metric | system_wide_teacher_salary_growth                                           | System-wide Teacher Salary Growth                                             | money         | money         |
| Yes      | numeric metric | label_g_teacher_salary_growth                                               | Label g: Teacher Salary Growth                                                | money         | money         |
| Yes      | numeric metric | foundation                                                                  | Foundation                                                                    | money         | money         |
| Yes      | numeric metric | label_j_fy15_fair_student_formula_at_100                                    | Label j: FY15 Fair Student Formula at 100%                                    | money         | money         |
| Yes      | numeric metric | label_a_fy14_revised_based_allocations                                      | Label a: FY14 Revised Based Allocations                                       | money         | money         |
| Yes      | numeric metric | label_s_fair_student_funding_register_formula                               | Label s: Fair Student Funding Register Formula                                | money         | money         |
| Yes      | numeric metric | label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100 | Label t: Change to Preliminary Fair Student Funding Percentage Capped at 100% | number        | number        |
| Yes      | numeric metric | label_f_register_change_allocation_based_on_school_s_percent_of_formula     | Label f: Register Change Allocation Based on School's Percent of Formula      | money         | money         |
| Yes      | numeric metric | label_g_teacher_salary_growth_2                                             | Label g: Teacher Salary Growth 2                                              | money         | money         |
| Yes      | numeric metric | label_h_foundation_for_new_schools                                          | Label h: Foundation for New Schools                                           | money         | money         |
| Yes      | numeric metric | label_d_initial_fair_student_funding_allocations_total                      | Label d: Initial Fair Student Funding Allocations Total                       | money         | money         |
| Yes      | numeric metric | calculation_j_initial_fair_student_funding_allocations_total                | Calculation j: Initial Fair Student Funding Allocations Total                 | money         | money         |
| Yes      | numeric metric | calculation_j_foundation                                                    | Calculation j: Foundation                                                     | money         | money         |
| Yes      | numeric metric | label_w_final_school_fsf_percent                                            | Label w: Final School FSF Percent                                             | number        | number        |
| Yes      | numeric metric | calculation_j_fsf_formula_at_100                                            | Calculation j: FSF Formula at 100%                                            | money         | money         |
| No       |                | as_of_date                                                                  | As_Of_Date                                                                    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = as_of_date
```

## Data Commands

```ls
series e:nbgq-j9jt d:2015-01-01T00:00:00.000Z t:location=K001 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-99126.82 m:label_d_initial_fair_student_funding_allocations_total=5858476.18 m:total_column_q_register_change=-29.26 m:total_column_n_fy14_actual_registers=1692.42 m:calculation_j_fsf_formula_at_100=7081416.99 m:label_j_fy15_fair_student_formula_at_100=7081416.99 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-120645.73 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=6856416.99 m:total_column_o_projected_register=1663.15 m:label_a_fy14_revised_based_allocations=5957603 m:foundation=225000 m:calculation_j_initial_fair_student_funding_allocations_total=5858476.18 m:calculation_j_foundation=225000 m:label_g_teacher_salary_growth_2=0 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8216 m:total_column_r_register_dollar_change=-120645.73 m:label_w_final_school_fsf_percent=0.8216 m:weighted_register=1663.15

series e:nbgq-j9jt d:2015-01-01T00:00:00.000Z t:location=K002 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-51499.38 m:label_d_initial_fair_student_funding_allocations_total=2514000.62 m:total_column_q_register_change=-15.35 m:total_column_n_fy14_actual_registers=697.52 m:calculation_j_fsf_formula_at_100=3037276.59 m:label_j_fy15_fair_student_formula_at_100=3037276.59 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-63272.37 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2812276.59 m:total_column_o_projected_register=682.17 m:label_a_fy14_revised_based_allocations=2565500 m:foundation=225000 m:calculation_j_initial_fair_student_funding_allocations_total=2514000.62 m:calculation_j_foundation=225000 m:label_g_teacher_salary_growth_2=0 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8139 m:total_column_r_register_dollar_change=-63272.37 m:label_w_final_school_fsf_percent=0.8139 m:weighted_register=682.17

series e:nbgq-j9jt d:2015-01-01T00:00:00.000Z t:location=K003 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-188271.84 m:label_d_initial_fair_student_funding_allocations_total=2176535.16 m:total_column_q_register_change=-52.07 m:total_column_n_fy14_actual_registers=591.84 m:calculation_j_fsf_formula_at_100=2450195.3 m:label_j_fy15_fair_student_formula_at_100=2450195.3 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-214672.83 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2225195.3 m:total_column_o_projected_register=539.76 m:label_a_fy14_revised_based_allocations=2364807 m:foundation=225000 m:calculation_j_initial_fair_student_funding_allocations_total=2176535.16 m:calculation_j_foundation=225000 m:label_g_teacher_salary_growth_2=0 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.877 m:total_column_r_register_dollar_change=-214672.83 m:label_w_final_school_fsf_percent=0.877 m:weighted_register=539.76
```

## Meta Commands

```ls
metric m:total_column_n_fy14_actual_registers p:float l:"Total Column N: FY14 Actual Registers" t:dataTypeName=number

metric m:total_column_o_projected_register p:float l:"Total Column O: Projected Register" t:dataTypeName=number

metric m:total_column_p_projected_formula p:double l:"Total Column P: Projected Formula" t:dataTypeName=money

metric m:total_column_q_register_change p:float l:"Total Column Q: Register Change" t:dataTypeName=number

metric m:total_column_r_register_dollar_change p:double l:"Total Column R: Register Dollar Change" t:dataTypeName=money

metric m:weighted_register p:float l:"Weighted Register" t:dataTypeName=number

metric m:system_wide_teacher_salary_growth p:double l:"System-wide Teacher Salary Growth" t:dataTypeName=money

metric m:label_g_teacher_salary_growth p:double l:"Label g: Teacher Salary Growth" t:dataTypeName=money

metric m:foundation p:double l:Foundation t:dataTypeName=money

metric m:label_j_fy15_fair_student_formula_at_100 p:double l:"Label j: FY15 Fair Student Formula at 100%" t:dataTypeName=money

metric m:label_a_fy14_revised_based_allocations p:double l:"Label a: FY14 Revised Based Allocations" t:dataTypeName=money

metric m:label_s_fair_student_funding_register_formula p:double l:"Label s: Fair Student Funding Register Formula" t:dataTypeName=money

metric m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100 p:double l:"Label t: Change to Preliminary Fair Student Funding Percentage Capped at 100%" t:dataTypeName=number

metric m:label_f_register_change_allocation_based_on_school_s_percent_of_formula p:double l:"Label f: Register Change Allocation Based on School's Percent of Formula" t:dataTypeName=money

metric m:label_g_teacher_salary_growth_2 p:double l:"Label g: Teacher Salary Growth 2" t:dataTypeName=money

metric m:label_h_foundation_for_new_schools p:double l:"Label h: Foundation for New Schools" t:dataTypeName=money

metric m:label_d_initial_fair_student_funding_allocations_total p:double l:"Label d: Initial Fair Student Funding Allocations Total" t:dataTypeName=money

metric m:calculation_j_initial_fair_student_funding_allocations_total p:double l:"Calculation j: Initial Fair Student Funding Allocations Total" t:dataTypeName=money

metric m:calculation_j_foundation p:double l:"Calculation j: Foundation" t:dataTypeName=money

metric m:label_w_final_school_fsf_percent p:float l:"Label w: Final School FSF Percent" t:dataTypeName=number

metric m:calculation_j_fsf_formula_at_100 p:double l:"Calculation j: FSF Formula at 100%" t:dataTypeName=money

entity e:nbgq-j9jt l:"Fair Student Funding Budget Detail 2" t:url=https://data.cityofnewyork.us/api/views/nbgq-j9jt

property e:nbgq-j9jt t:meta.view d:2017-06-09T13:53:32.926Z v:id=nbgq-j9jt v:category=Education v:averageRating=0 v:name="Fair Student Funding Budget Detail 2"

property e:nbgq-j9jt t:meta.view.owner d:2017-06-09T13:53:32.926Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:nbgq-j9jt t:meta.view.tableauthor d:2017-06-09T13:53:32.926Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| fiscal_year | location | total_column_n_fy14_actual_registers | total_column_o_projected_register | total_column_p_projected_formula | total_column_q_register_change | total_column_r_register_dollar_change | weighted_register | system_wide_teacher_salary_growth | label_g_teacher_salary_growth | foundation | label_j_fy15_fair_student_formula_at_100 | label_a_fy14_revised_based_allocations | label_s_fair_student_funding_register_formula | label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100 | label_f_register_change_allocation_based_on_school_s_percent_of_formula | label_g_teacher_salary_growth_2 | label_h_foundation_for_new_schools | label_d_initial_fair_student_funding_allocations_total | calculation_j_initial_fair_student_funding_allocations_total | calculation_j_foundation | label_w_final_school_fsf_percent | calculation_j_fsf_formula_at_100 | as_of_date | 
| =========== | ======== | ==================================== | ================================= | ================================ | ============================== | ===================================== | ================= | ================================= | ============================= | ========== | ======================================== | ====================================== | ============================================= | =========================================================================== | ======================================================================= | =============================== | ================================== | ====================================================== | ============================================================ | ======================== | ================================ | ================================ | ========== | 
| 2015        | K001     | 1692.42                              | 1663.15                           | 6856416.99                       | -29.26                         | -120645.73                            | 1663.15           | 0.00                              | 0.00                          | 225000.00  | 7081416.99                               | 5957603.00                             | -120645.73                                    | 0.8216                                                                      | -99126.82                                                               | 0.00                            | 0.00                               | 5858476.18                                             | 5858476.18                                                   | 225000.00                | 0.8216                           | 7081416.99                       |            | 
| 2015        | K002     | 697.52                               | 682.17                            | 2812276.59                       | -15.35                         | -63272.37                             | 682.17            | 0.00                              | 0.00                          | 225000.00  | 3037276.59                               | 2565500.00                             | -63272.37                                     | 0.8139                                                                      | -51499.38                                                               | 0.00                            | 0.00                               | 2514000.62                                             | 2514000.62                                                   | 225000.00                | 0.8139                           | 3037276.59                       |            | 
| 2015        | K003     | 591.84                               | 539.76                            | 2225195.30                       | -52.07                         | -214672.83                            | 539.76            | 0.00                              | 0.00                          | 225000.00  | 2450195.30                               | 2364807.00                             | -214672.83                                    | 0.877                                                                       | -188271.84                                                              | 0.00                            | 0.00                               | 2176535.16                                             | 2176535.16                                                   | 225000.00                | 0.877                            | 2450195.30                       |            | 
| 2015        | K005     | 391.76                               | 359.56                            | 1482282.85                       | -32.20                         | -132749.12                            | 359.56            | 0.00                              | 0.00                          | 225000.00  | 1707282.85                               | 1711158.00                             | -132749.12                                    | 0.9202                                                                      | -122156.19                                                              | 0.00                            | 0.00                               | 1589001.81                                             | 1589001.81                                                   | 225000.00                | 0.9202                           | 1707282.85                       |            | 
| 2015        | K006     | 983.87                               | 945.96                            | 3899758.11                       | -37.91                         | -156293.07                            | 945.96            | 0.00                              | 0.00                          | 225000.00  | 4124758.11                               | 3771012.00                             | -156293.07                                    | 0.8743                                                                      | -136639.58                                                              | 0.00                            | 0.00                               | 3634372.42                                             | 3634372.42                                                   | 225000.00                | 0.8743                           | 4124758.11                       |            | 
| 2015        | K007     | 1347.09                              | 1343.51                           | 5538700.52                       | -3.57                          | -14729.76                             | 1343.51           | 0.00                              | 0.00                          | 225000.00  | 5763700.52                               | 4782292.00                             | -14729.76                                     | 0.8206                                                                      | -12087.64                                                               | 0.00                            | 0.00                               | 4770204.36                                             | 4770204.36                                                   | 225000.00                | 0.8206                           | 5763700.52                       |            | 
| 2015        | K008     | 960.89                               | 1085.78                           | 4476192.14                       | 124.90                         | 514895.10                             | 1085.78           | 0.00                              | 0.00                          | 225000.00  | 4701192.14                               | 3578829.00                             | 514895.10                                     | 0.8466                                                                      | 435935.53                                                               | 0.00                            | 0.00                               | 4014764.53                                             | 4014764.53                                                   | 225000.00                | 0.8466                           | 4701192.14                       |            | 
| 2015        | K009     | 821.84                               | 860.18                            | 3546140.74                       | 38.34                          | 158074.89                             | 860.18            | 0.00                              | 0.00                          | 225000.00  | 3771140.74                               | 3065347.00                             | 158074.89                                     | 0.8383                                                                      | 132520.30                                                               | 0.00                            | 0.00                               | 3197867.30                                             | 3197867.30                                                   | 225000.00                | 0.8383                           | 3771140.74                       |            | 
| 2015        | K010     | 1197.52                              | 1199.94                           | 4946803.29                       | 2.42                           | 9991.56                               | 1199.94           | 0.00                              | 0.00                          | 225000.00  | 5171803.29                               | 4345806.00                             | 9991.56                                       | 0.8347                                                                      | 8340.06                                                                 | 0.00                            | 0.00                               | 4354146.06                                             | 4354146.06                                                   | 225000.00                | 0.8347                           | 5171803.29                       |            | 
| 2015        | K011     | 777.14                               | 811.29                            | 3344565.49                       | 34.14                          | 140750.76                             | 811.29            | 0.00                              | 0.00                          | 225000.00  | 3569565.49                               | 3268172.00                             | 140750.76                                     | 0.9499                                                                      | 133693.35                                                               | 0.00                            | 0.00                               | 3401865.35                                             | 3401865.35                                                   | 225000.00                | 0.9499                           | 3569565.49                       |            | 
```