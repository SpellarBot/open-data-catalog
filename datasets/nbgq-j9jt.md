# Fair Student Funding Budget Detail 2

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/nbgq-j9jt/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/fair-student-funding-budget-detail-2)
* Id = nbgq-j9jt
* Name = Fair Student Funding Budget Detail 2
* Category = Education
* Created = 2015-10-19T19:23:23Z
* Publication Date = 2015-10-19T19:30:25Z
* Rows Updated = 2015-10-19T19:25:07Z

## Description

Fair Student Funding Budget Detail FY 2015 - Part II This detail data contains one row for each school's data and calculations displayed on the Details screen starting from the "TOTAL FAIR STUDENT FUNDING WEIGHTED REGISTER AND FORMULA" to the bottom of the page.
Click Here for further information- http://schools.nyc.gov/offices/d_chanc_oper/budget/dbor/allocationmemo/fy14_15/Fair_School_Funding_FY2015.html

## Columns

```ls
| Name                                                                          | Field Name                                                                  | Data Type     | Render Type   | Schema Type    | Included | 
| ============================================================================= | =========================================================================== | ============= | ============= | ============== | ======== | 
| Fiscal_Year                                                                   | fiscal_year                                                                 | number        | text          |                | No       | 
| Location                                                                      | location                                                                    | text          | text          | series tag     | Yes      | 
| Total Column N: FY14 Actual Registers                                         | total_column_n_fy14_actual_registers                                        | number        | number        | numeric metric | Yes      | 
| Total Column O: Projected Register                                            | total_column_o_projected_register                                           | number        | number        | numeric metric | Yes      | 
| Total Column P: Projected Formula                                             | total_column_p_projected_formula                                            | money         | money         | numeric metric | Yes      | 
| Total Column Q: Register Change                                               | total_column_q_register_change                                              | number        | number        | numeric metric | Yes      | 
| Total Column R: Register Dollar Change                                        | total_column_r_register_dollar_change                                       | money         | money         | numeric metric | Yes      | 
| Weighted Register                                                             | weighted_register                                                           | number        | number        | numeric metric | Yes      | 
| System-wide Teacher Salary Growth                                             | system_wide_teacher_salary_growth                                           | money         | money         | numeric metric | Yes      | 
| Label g: Teacher Salary Growth                                                | label_g_teacher_salary_growth                                               | money         | money         | numeric metric | Yes      | 
| Foundation                                                                    | foundation                                                                  | money         | money         | numeric metric | Yes      | 
| Label j: FY15 Fair Student Formula at 100%                                    | label_j_fy15_fair_student_formula_at_100                                    | money         | money         | numeric metric | Yes      | 
| Label a: FY14 Revised Based Allocations                                       | label_a_fy14_revised_based_allocations                                      | money         | money         | numeric metric | Yes      | 
| Label s: Fair Student Funding Register Formula                                | label_s_fair_student_funding_register_formula                               | money         | money         | numeric metric | Yes      | 
| Label t: Change to Preliminary Fair Student Funding Percentage Capped at 100% | label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100 | number        | number        | numeric metric | Yes      | 
| Label f: Register Change Allocation Based on School's Percent of Formula      | label_f_register_change_allocation_based_on_school_s_percent_of_formula     | money         | money         | numeric metric | Yes      | 
| Label g: Teacher Salary Growth 2                                              | label_g_teacher_salary_growth_2                                             | money         | money         | numeric metric | Yes      | 
| Label h: Foundation for New Schools                                           | label_h_foundation_for_new_schools                                          | money         | money         | numeric metric | Yes      | 
| Label d: Initial Fair Student Funding Allocations Total                       | label_d_initial_fair_student_funding_allocations_total                      | money         | money         | numeric metric | Yes      | 
| Calculation j: Initial Fair Student Funding Allocations Total                 | calculation_j_initial_fair_student_funding_allocations_total                | money         | money         | numeric metric | Yes      | 
| Calculation j: Foundation                                                     | calculation_j_foundation                                                    | money         | money         | numeric metric | Yes      | 
| Label w: Final School FSF Percent                                             | label_w_final_school_fsf_percent                                            | number        | number        | numeric metric | Yes      | 
| Calculation j: FSF Formula at 100%                                            | calculation_j_fsf_formula_at_100                                            | money         | money         | numeric metric | Yes      | 
| As_Of_Date                                                                    | as_of_date                                                                  | calendar_date | calendar_date | time           | Yes      | 
```

## Time Field

```ls
Value = as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = fiscal_year
Annotation Fields = 
```

## Data Commands

```ls
series e:nbgq-j9jt d:2017-03-03T14:40:41.906Z t:location=K001 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-99126.82 m:label_d_initial_fair_student_funding_allocations_total=5858476.18 m:total_column_q_register_change=-29.26 m:calculation_j_fsf_formula_at_100=7081416.99 m:total_column_n_fy14_actual_registers=1692.42 m:label_j_fy15_fair_student_formula_at_100=7081416.99 m:label_h_foundation_for_new_schools=0 m:label_s_fair_student_funding_register_formula=-120645.73 m:system_wide_teacher_salary_growth=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=6856416.99 m:total_column_o_projected_register=1663.15 m:foundation=225000 m:label_a_fy14_revised_based_allocations=5957603 m:calculation_j_initial_fair_student_funding_allocations_total=5858476.18 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-120645.73 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8216 m:label_g_teacher_salary_growth_2=0 m:weighted_register=1663.15 m:label_w_final_school_fsf_percent=0.8216

series e:nbgq-j9jt d:2017-03-03T14:40:41.906Z t:location=K002 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-51499.38 m:label_d_initial_fair_student_funding_allocations_total=2514000.62 m:total_column_q_register_change=-15.35 m:calculation_j_fsf_formula_at_100=3037276.59 m:total_column_n_fy14_actual_registers=697.52 m:label_j_fy15_fair_student_formula_at_100=3037276.59 m:label_h_foundation_for_new_schools=0 m:label_s_fair_student_funding_register_formula=-63272.37 m:system_wide_teacher_salary_growth=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2812276.59 m:total_column_o_projected_register=682.17 m:foundation=225000 m:label_a_fy14_revised_based_allocations=2565500 m:calculation_j_initial_fair_student_funding_allocations_total=2514000.62 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-63272.37 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.8139 m:label_g_teacher_salary_growth_2=0 m:weighted_register=682.17 m:label_w_final_school_fsf_percent=0.8139

series e:nbgq-j9jt d:2017-03-03T14:40:41.906Z t:location=K003 m:label_f_register_change_allocation_based_on_school_s_percent_of_formula=-188271.84 m:label_d_initial_fair_student_funding_allocations_total=2176535.16 m:total_column_q_register_change=-52.07 m:calculation_j_fsf_formula_at_100=2450195.3 m:total_column_n_fy14_actual_registers=591.84 m:label_j_fy15_fair_student_formula_at_100=2450195.3 m:label_h_foundation_for_new_schools=0 m:label_s_fair_student_funding_register_formula=-214672.83 m:system_wide_teacher_salary_growth=0 m:label_g_teacher_salary_growth=0 m:total_column_p_projected_formula=2225195.3 m:total_column_o_projected_register=539.76 m:foundation=225000 m:label_a_fy14_revised_based_allocations=2364807 m:calculation_j_initial_fair_student_funding_allocations_total=2176535.16 m:calculation_j_foundation=225000 m:total_column_r_register_dollar_change=-214672.83 m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100=0.877 m:label_g_teacher_salary_growth_2=0 m:weighted_register=539.76 m:label_w_final_school_fsf_percent=0.877
```

## Meta Commands

```ls
metric m:total_column_n_fy14_actual_registers l:"Total Column N: FY14 Actual Registers" t:dataTypeName=number

metric m:total_column_o_projected_register l:"Total Column O: Projected Register" t:dataTypeName=number

metric m:total_column_q_register_change l:"Total Column Q: Register Change" t:dataTypeName=number

metric m:weighted_register l:"Weighted Register" t:dataTypeName=number

metric m:label_t_change_to_preliminary_fair_student_funding_percentage_capped_at_100 l:"Label t: Change to Preliminary Fair Student Funding Percentage Capped at 100%" t:dataTypeName=number

metric m:label_w_final_school_fsf_percent l:"Label w: Final School FSF Percent" t:dataTypeName=number

entity e:nbgq-j9jt l:"Fair Student Funding Budget Detail 2" t:url=https://data.cityofnewyork.us/api/views/nbgq-j9jt

property e:nbgq-j9jt t:meta.view d:2017-03-03T14:40:41.906Z v:id=nbgq-j9jt v:category=Education v:averageRating=0 v:name="Fair Student Funding Budget Detail 2"

property e:nbgq-j9jt t:meta.view.owner d:2017-03-03T14:40:41.906Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:nbgq-j9jt t:meta.view.tableauthor d:2017-03-03T14:40:41.906Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```