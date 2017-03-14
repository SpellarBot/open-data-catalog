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
| Rows Updated | 2015-10-19T19:25:07Z |

## Description

Fair Student Funding Budget Detail FY 2015 - Part II This detail data contains one row for each school's data and calculations displayed on the Details screen starting from the "TOTAL FAIR STUDENT FUNDING WEIGHTED REGISTER AND FORMULA" to the bottom of the page.
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Included | Schema Type    | Field Name                                                                  | Name                                                                          | Data Type     | Render Type   |
| ======== | ============== | =========================================================================== | ============================================================================= | ============= | ============= |
| No       |                | fiscal_year                                                                 | Fiscal_Year                                                                   | number        | text          |
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
| Yes      | time           | as_of_date                                                                  | As_Of_Date                                                                    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:nbgq-j9jt d:2017-03-14T12:24:37.261Z t:location=K001 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-99126.82 m:label_d_initial_fair_student_funding_allocations_total=5858476.18 m:total_column_q_register_change=-29.26 m:total_column_n_fy14_actual_registers=1692.42 m:calculation_j_fsf_formula_at_100=7081416.99 m:label_j_fy15_fair_student_formula_at_100=7081416.99 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-120645.73 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=6856416.99 m:total_column_o_projected_register=1663.15 m:foundation=225000 m:label_a_fy14_revised_based_allocations=5957603 m:calculation_j_initial_fair_student_funding_allocations_total=5858476.18 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-120645.73 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8216 m:label_g_teacher_salary_growth_2=0 m:weighted_register=1663.15 m:label_w_final_school_fsf_percent=0.8216

series e:nbgq-j9jt d:2017-03-14T12:24:37.261Z t:location=K002 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-51499.38 m:label_d_initial_fair_student_funding_allocations_total=2514000.62 m:total_column_q_register_change=-15.35 m:total_column_n_fy14_actual_registers=697.52 m:calculation_j_fsf_formula_at_100=3037276.59 m:label_j_fy15_fair_student_formula_at_100=3037276.59 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-63272.37 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2812276.59 m:total_column_o_projected_register=682.17 m:foundation=225000 m:label_a_fy14_revised_based_allocations=2565500 m:calculation_j_initial_fair_student_funding_allocations_total=2514000.62 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-63272.37 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8139 m:label_g_teacher_salary_growth_2=0 m:weighted_register=682.17 m:label_w_final_school_fsf_percent=0.8139

series e:nbgq-j9jt d:2017-03-14T12:24:37.261Z t:location=K003 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-188271.84 m:label_d_initial_fair_student_funding_allocations_total=2176535.16 m:total_column_q_register_change=-52.07 m:total_column_n_fy14_actual_registers=591.84 m:calculation_j_fsf_formula_at_100=2450195.3 m:label_j_fy15_fair_student_formula_at_100=2450195.3 m:system_wide_teacher_salary_growth=0 m:label_s_fair_student_funding_register_formula=-214672.83 m:label_h_foundation_for_new_schools=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2225195.3 m:total_column_o_projected_register=539.76 m:foundation=225000 m:label_a_fy14_revised_based_allocations=2364807 m:calculation_j_initial_fair_student_funding_allocations_total=2176535.16 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-214672.83 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.877 m:label_g_teacher_salary_growth_2=0 m:weighted_register=539.76 m:label_w_final_school_fsf_percent=0.877
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

property e:nbgq-j9jt t:meta.view v:id=nbgq-j9jt v:category=Education v:averageRating=0 v:name="Fair Student Funding Budget Detail 2"

property e:nbgq-j9jt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:nbgq-j9jt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```