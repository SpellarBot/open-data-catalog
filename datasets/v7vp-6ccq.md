# FY 2016 State and Federal Allocations to Iowa Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-2016-state-and-federal-allocations-to-iowa-schools) |
| Metadata | [Link](https://data.iowa.gov/api/views/v7vp-6ccq) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/v7vp-6ccq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/v7vp-6ccq/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | v7vp-6ccq |
| Name | FY 2016 State and Federal Allocations to Iowa Schools |
| Attribution | Iowa Department of Education |
| Category | Education |
| Tags | education, funding, 2016 |
| Created | 2016-08-08T20:19:56Z |
| Publication Date | 2016-08-08T20:44:42Z |

## Description

State and Federal Funding Allocations by District for Fiscal Year 2016 (year ending 6/30/2016).

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | district                                                   | District                                                   | text      | number      |
| Yes      | series tag     | district_name                                              | District Name                                              | text      | text        |
| Yes      | time           | fiscal_year                                                | Fiscal Year                                                | number    | number      |
| Yes      | numeric metric | budgeted_enrollment                                        | Budgeted Enrollment                                        | number    | number      |
| Yes      | numeric metric | regular_program                                            | Regular Program                                            | number    | number      |
| Yes      | numeric metric | budget_adjustment                                          | Budget Adjustment                                          | number    | number      |
| Yes      | series tag     | district_cost_for_supplementary_weighting                  | District Cost for Supplementary Weighting                  | text      | number      |
| Yes      | series tag     | special_education_instrustion_district_cost                | Special Education Instrustion District Cost                | text      | number      |
| Yes      | numeric metric | teacher_salary_supplement                                  | Teacher Salary Supplement                                  | number    | number      |
| Yes      | numeric metric | professional_development_supplement                        | Professional Development Supplement                        | number    | number      |
| Yes      | numeric metric | early_intervention_supplement                              | Early Intervention Supplement                              | number    | number      |
| Yes      | numeric metric | teacher_leadership_supplement_on_aid_and_levy              | Teacher Leadership Supplement on Aid and Levy              | number    | number      |
| Yes      | numeric metric | teacher_leadership_supplement_de_grants                    | Teacher Leadership Supplement DE Grants                    | number    | number      |
| Yes      | numeric metric | preschool                                                  | Preschool                                                  | number    | number      |
| Yes      | numeric metric | instructional_support_income_surtax                        | Instructional Support Income Surtax                        | number    | number      |
| Yes      | numeric metric | instructional_support_property_tax                         | Instructional Support Property Tax                         | number    | number      |
| Yes      | numeric metric | educational_improvement                                    | Educational Improvement                                    | number    | number      |
| Yes      | numeric metric | sbrc_modified_supplemental_amount_dropout                  | SBRC Modified Supplemental Amount Dropout                  | number    | number      |
| Yes      | numeric metric | management_levy                                            | Management Levy                                            | number    | number      |
| Yes      | numeric metric | regular_ppel                                               | Regular PPEL                                               | number    | number      |
| Yes      | numeric metric | voted_ppel_income_surtax                                   | Voted PPEL-Income Surtax                                   | number    | number      |
| Yes      | numeric metric | voted_ppel_property_tax                                    | Voted PPEL-Property Tax                                    | number    | number      |
| Yes      | numeric metric | perl                                                       | PERL                                                       | number    | number      |
| Yes      | numeric metric | modified_supplemental_amount_sbrc_approved                 | Modified Supplemental Amount - SBRC Approved               | number    | number      |
| Yes      | numeric metric | modified_supplemental_amount_for_special_education_deficit | Modified Supplemental Amount for Special Education Deficit | number    | number      |
| Yes      | numeric metric | successful_progression_for_early_readers                   | Successful Progression for Early Readers                   | number    | number      |
| Yes      | numeric metric | educator_mentoring_and_induction                           | Educator Mentoring and Induction                           | number    | number      |
| Yes      | numeric metric | title_i                                                    | Title I                                                    | number    | number      |
| Yes      | numeric metric | title_i_migrant                                            | Title I Migrant                                            | number    | number      |
| Yes      | numeric metric | title_i_neglected                                          | Title I Neglected                                          | number    | number      |
| Yes      | numeric metric | title_i_delinquent                                         | Title I Delinquent                                         | number    | number      |
| Yes      | numeric metric | title_ii_part_a                                            | Title II Part A                                            | number    | number      |
| Yes      | numeric metric | title_iii_english_language_acquisition                     | Title III English Language Acquisition                     | number    | number      |
| Yes      | numeric metric | 21st_century_learning_centers                              | 21st Century Learning Centers                              | number    | number      |
| Yes      | numeric metric | title_vi                                                   | Title VI                                                   | number    | number      |
| Yes      | series tag     | reap                                                       | REAP                                                       | text      | text        |
| Yes      | numeric metric | small_rural_schools_achievement_program_reap               | Small Rural Schools Achievement Program (REAP)             | number    | number      |
| Yes      | numeric metric | rural_low_income_schools_rlis_program                      | Rural Low Income Schools (RLIS) Program                    | number    | number      |
| Yes      | numeric metric | idea_part_b                                                | IDEA Part B                                                | number    | number      |
| Yes      | numeric metric | carl_d_perkins                                             | Carl D. Perkins                                            | number    | number      |
| Yes      | numeric metric | total_funding_of_sources_shown                             | Total Funding of Sources Shown                             | number    | number      |
| Yes      | numeric metric | per_pupil_amount_of_funding_sources_shown                  | Per Pupil Amount of Funding Sources Shown                  | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v7vp-6ccq d:2016-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=501600.00 t:district_cost_for_supplementary_weighting=122007.00 t:district_name=AGWSR t:district=9 m:early_intervention_supplement=33893 m:instructional_support_property_tax=349332 m:sbrc_modified_supplemental_amount_dropout=107594 m:modified_supplemental_amount_for_special_education_deficit=52789 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=34957 m:teacher_salary_supplement=363650 m:per_pupil_amount_of_funding_sources_shown=10982.38 m:regular_program=4087666 m:total_funding_of_sources_shown=6847511.51 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=130175 m:teacher_leadership_supplement_on_aid_and_levy=0 m:21st_century_learning_centers=0 m:preschool=116028 m:modified_supplemental_amount_sbrc_approved=307617 m:title_ii_part_a=24303.76 m:carl_d_perkins=0 m:budget_adjustment=0 m:successful_progression_for_early_readers=17092 m:budgeted_enrollment=623.5 m:title_i_neglected=0 m:regular_ppel=113231 m:management_levy=0 m:educational_improvement=0 m:instructional_support_income_surtax=0 m:title_i=82465 m:professional_development_supplement=39150 m:idea_part_b=29560 m:voted_ppel_income_surtax=329610 m:title_vi=2156 m:teacher_leadership_supplement_de_grants=0 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=2635.75 m:title_i_delinquent=0

series e:v7vp-6ccq d:2016-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=283753.00 t:district_cost_for_supplementary_weighting=101486.00 t:district_name=Adair-Casey t:district=18 m:early_intervention_supplement=21808 m:instructional_support_property_tax=103758 m:sbrc_modified_supplemental_amount_dropout=70842 m:modified_supplemental_amount_for_special_education_deficit=0 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=20632 m:teacher_salary_supplement=199025 m:per_pupil_amount_of_funding_sources_shown=11585.48 m:regular_program=2109776 m:total_funding_of_sources_shown=3791928.99 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=206975 m:teacher_leadership_supplement_on_aid_and_levy=0 m:21st_century_learning_centers=0 m:preschool=41899 m:modified_supplemental_amount_sbrc_approved=79573 m:title_ii_part_a=12692.39 m:carl_d_perkins=0 m:budget_adjustment=1724 m:successful_progression_for_early_readers=14628 m:budgeted_enrollment=327.3 m:title_i_neglected=0 m:regular_ppel=68891 m:management_levy=190000 m:educational_improvement=0 m:instructional_support_income_surtax=72763 m:title_i=81029 m:professional_development_supplement=19730 m:idea_part_b=14925 m:voted_ppel_income_surtax=72763 m:title_vi=1148 m:teacher_leadership_supplement_de_grants=0 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=2108.6 m:title_i_delinquent=0

series e:v7vp-6ccq d:2016-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=976431.00 t:district_cost_for_supplementary_weighting=87912.00 t:district_name="Adel DeSoto Minburn" t:district=27 m:early_intervention_supplement=97139 m:instructional_support_property_tax=691195 m:sbrc_modified_supplemental_amount_dropout=424057 m:modified_supplemental_amount_for_special_education_deficit=656287 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=0 m:teacher_salary_supplement=866844 m:per_pupil_amount_of_funding_sources_shown=10009.2 m:regular_program=9889747 m:total_funding_of_sources_shown=15309078.58 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=420435 m:teacher_leadership_supplement_on_aid_and_levy=0 m:21st_century_learning_centers=0 m:preschool=0 m:modified_supplemental_amount_sbrc_approved=311126 m:title_ii_part_a=27779.03 m:carl_d_perkins=0 m:budget_adjustment=0 m:successful_progression_for_early_readers=24630 m:budgeted_enrollment=1529.5 m:title_i_neglected=0 m:regular_ppel=138743 m:management_levy=410000 m:educational_improvement=0 m:instructional_support_income_surtax=0 m:title_i=109251 m:professional_development_supplement=93605 m:idea_part_b=68420 m:voted_ppel_income_surtax=0 m:title_vi=6516 m:teacher_leadership_supplement_de_grants=0 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=8961.55 m:title_i_delinquent=0
```

## Meta Commands

```ls
metric m:budgeted_enrollment p:double l:"Budgeted Enrollment" t:dataTypeName=number

metric m:regular_program p:double l:"Regular Program" t:dataTypeName=number

metric m:budget_adjustment p:float l:"Budget Adjustment" t:dataTypeName=number

metric m:teacher_salary_supplement p:double l:"Teacher Salary Supplement" t:dataTypeName=number

metric m:professional_development_supplement p:float l:"Professional Development Supplement" t:dataTypeName=number

metric m:early_intervention_supplement p:double l:"Early Intervention Supplement" t:dataTypeName=number

metric m:teacher_leadership_supplement_on_aid_and_levy p:double l:"Teacher Leadership Supplement on Aid and Levy" t:dataTypeName=number

metric m:teacher_leadership_supplement_de_grants p:double l:"Teacher Leadership Supplement DE Grants" t:dataTypeName=number

metric m:preschool p:double l:Preschool t:dataTypeName=number

metric m:instructional_support_income_surtax p:double l:"Instructional Support Income Surtax" t:dataTypeName=number

metric m:instructional_support_property_tax p:double l:"Instructional Support Property Tax" t:dataTypeName=number

metric m:educational_improvement p:float l:"Educational Improvement" t:dataTypeName=number

metric m:sbrc_modified_supplemental_amount_dropout p:double l:"SBRC Modified Supplemental Amount Dropout" t:dataTypeName=number

metric m:management_levy p:float l:"Management Levy" t:dataTypeName=number

metric m:regular_ppel p:float l:"Regular PPEL" t:dataTypeName=number

metric m:voted_ppel_income_surtax p:float l:"Voted PPEL-Income Surtax" t:dataTypeName=number

metric m:voted_ppel_property_tax p:double l:"Voted PPEL-Property Tax" t:dataTypeName=number

metric m:perl p:float l:PERL t:dataTypeName=number

metric m:modified_supplemental_amount_sbrc_approved p:double l:"Modified Supplemental Amount - SBRC Approved" t:dataTypeName=number

metric m:modified_supplemental_amount_for_special_education_deficit p:double l:"Modified Supplemental Amount for Special Education Deficit" t:dataTypeName=number

metric m:successful_progression_for_early_readers p:float l:"Successful Progression for Early Readers" t:dataTypeName=number

metric m:educator_mentoring_and_induction p:float l:"Educator Mentoring and Induction" t:dataTypeName=number

metric m:title_i p:double l:"Title I" t:dataTypeName=number

metric m:title_i_migrant p:float l:"Title I Migrant" t:dataTypeName=number

metric m:title_i_neglected p:float l:"Title I Neglected" t:dataTypeName=number

metric m:title_i_delinquent p:float l:"Title I Delinquent" t:dataTypeName=number

metric m:title_ii_part_a p:float l:"Title II Part A" t:dataTypeName=number

metric m:title_iii_english_language_acquisition p:float l:"Title III English Language Acquisition" t:dataTypeName=number

metric m:21st_century_learning_centers p:float l:"21st Century Learning Centers" t:dataTypeName=number

metric m:title_vi p:float l:"Title VI" t:dataTypeName=number

metric m:small_rural_schools_achievement_program_reap p:float l:"Small Rural Schools Achievement Program (REAP)" t:dataTypeName=number

metric m:rural_low_income_schools_rlis_program p:float l:"Rural Low Income Schools (RLIS) Program" t:dataTypeName=number

metric m:idea_part_b p:double l:"IDEA Part B" t:dataTypeName=number

metric m:carl_d_perkins p:float l:"Carl D. Perkins" t:dataTypeName=number

metric m:total_funding_of_sources_shown p:double l:"Total Funding of Sources Shown" t:dataTypeName=number

metric m:per_pupil_amount_of_funding_sources_shown p:float l:"Per Pupil Amount of Funding Sources Shown" t:dataTypeName=number

entity e:v7vp-6ccq l:"FY 2016 State and Federal Allocations to Iowa Schools" t:attribution="Iowa Department of Education" t:url=https://data.iowa.gov/api/views/v7vp-6ccq

property e:v7vp-6ccq t:meta.view v:id=v7vp-6ccq v:category=Education v:attributionLink=https://www.educateiowa.gov/pk-12/school-business-finance/accounting-reporting/allocation-summaries v:averageRating=0 v:name="FY 2016 State and Federal Allocations to Iowa Schools" v:attribution="Iowa Department of Education"

property e:v7vp-6ccq t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:v7vp-6ccq t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| district | district_name         | fiscal_year | budgeted_enrollment | regular_program | budget_adjustment | district_cost_for_supplementary_weighting | special_education_instrustion_district_cost | teacher_salary_supplement | professional_development_supplement | early_intervention_supplement | teacher_leadership_supplement_on_aid_and_levy | teacher_leadership_supplement_de_grants | preschool | instructional_support_income_surtax | instructional_support_property_tax | educational_improvement | sbrc_modified_supplemental_amount_dropout | management_levy | regular_ppel | voted_ppel_income_surtax | voted_ppel_property_tax | perl | modified_supplemental_amount_sbrc_approved | modified_supplemental_amount_for_special_education_deficit | successful_progression_for_early_readers | educator_mentoring_and_induction | title_i   | title_i_migrant | title_i_neglected | title_i_delinquent | title_ii_part_a | title_iii_english_language_acquisition | 21st_century_learning_centers | title_vi | reap | small_rural_schools_achievement_program_reap | rural_low_income_schools_rlis_program | idea_part_b | carl_d_perkins | total_funding_of_sources_shown | per_pupil_amount_of_funding_sources_shown | 
| ======== | ===================== | =========== | =================== | =============== | ================= | ========================================= | =========================================== | ========================= | =================================== | ============================= | ============================================= | ======================================= | ========= | =================================== | ================================== | ======================= | ========================================= | =============== | ============ | ======================== | ======================= | ==== | ========================================== | ========================================================== | ======================================== | ================================ | ========= | =============== | ================= | ================== | =============== | ====================================== | ============================= | ======== | ==== | ============================================ | ===================================== | =========== | ============== | ============================== | ========================================= | 
| 9        | AGWSR                 | 2016        | 623.5               | 4087666.00      | 0.00              | 122007.00                                 | 501600.00                                   | 363650.00                 | 39150.00                            | 33893.00                      | 0.00                                          | 0.00                                    | 116028.00 | 0.00                                | 349332.00                          | 0.00                    | 107594.00                                 | 0.00            | 113231.00    | 329610.00                | 130175.00               | 0.00 | 307617.00                                  | 52789.00                                                   | 17092.00                                 | 2635.75                          | 82465.00  | 0.00            | 0.00              | 0.00               | 24303.76        | 0.00                                   | 0.00                          | 2156.00  |      | 34957.00                                     | 0.00                                  | 29560.00    | 0.00           | 6847511.51                     | 10982.38                                  | 
| 18       | Adair-Casey           | 2016        | 327.3               | 2109776.00      | 1724.00           | 101486.00                                 | 283753.00                                   | 199025.00                 | 19730.00                            | 21808.00                      | 0.00                                          | 0.00                                    | 41899.00  | 72763.00                            | 103758.00                          | 0.00                    | 70842.00                                  | 190000.00       | 68891.00     | 72763.00                 | 206975.00               | 0.00 | 79573.00                                   | 0.00                                                       | 14628.00                                 | 2108.60                          | 81029.00  | 0.00            | 0.00              | 0.00               | 12692.39        | 0.00                                   | 0.00                          | 1148.00  |      | 20632.00                                     | 0.00                                  | 14925.00    | 0.00           | 3791928.99                     | 11585.48                                  | 
| 27       | Adel DeSoto Minburn   | 2016        | 1529.5              | 9889747.00      | 0.00              | 87912.00                                  | 976431.00                                   | 866844.00                 | 93605.00                            | 97139.00                      | 0.00                                          | 0.00                                    | 0.00      | 0.00                                | 691195.00                          | 0.00                    | 424057.00                                 | 410000.00       | 138743.00    | 0.00                     | 420435.00               | 0.00 | 311126.00                                  | 656287.00                                                  | 24630.00                                 | 8961.55                          | 109251.00 | 0.00            | 0.00              | 0.00               | 27779.03        | 0.00                                   | 0.00                          | 6516.00  |      | 0.00                                         | 0.00                                  | 68420.00    | 0.00           | 15309078.58                    | 10009.20                                  | 
| 63       | Akron Westfield       | 2016        | 498.5               | 3238755.00      | 131453.00         | 163835.00                                 | 367081.00                                   | 306977.00                 | 35173.00                            | 33701.00                      | 0.00                                          | 0.00                                    | 51568.00  | 102953.00                           | 158036.00                          | 0.00                    | 140750.00                                 | 320000.00       | 58308.00     | 0.00                     | 176690.00               | 0.00 | 12242.00                                   | 79337.00                                                   | 16052.00                                 | 2635.75                          | 49455.00  | 0.00            | 0.00              | 0.00               | 14869.54        | 0.00                                   | 0.00                          | 2208.00  |      | 46798.00                                     | 0.00                                  | 23531.00    | 0.00           | 5532408.29                     | 11098.11                                  | 
| 72       | Albert City-Truesdale | 2016        | 203.0               | 1324981.00      | 0.00              | 154507.00                                 | 151035.00                                   | 96451.00                  | 8035.00                             | 8309.00                       | 0.00                                          | 0.00                                    | 22561.00  | 0.00                                | 117526.00                          | 0.00                    | 0.00                                      | 100000.00       | 45329.00     | 0.00                     | 184065.00               | 0.00 | 43173.00                                   | 43884.00                                                   | 13594.00                                 | 527.15                           | 37379.00  | 0.00            | 0.00              | 0.00               | 4870.97         | 0.00                                   | 0.00                          | 396.00   |      | 14835.00                                     | 0.00                                  | 9785.00     | 0.00           | 2381243.12                     | 11730.26                                  | 
| 81       | Albia                 | 2016        | 1201.9              | 7747447.00      | 0.00              | 131028.00                                 | 757341.00                                   | 650925.00                 | 75443.00                            | 72679.00                      | 0.00                                          | 375810.00                               | 148258.00 | 462981.00                           | 25806.00                           | 0.00                    | 382565.00                                 | 275000.00       | 82176.00     | 0.00                     | 0.00                    | 0.00 | 122864.00                                  | 45429.00                                                   | 21904.00                                 | 3162.90                          | 189588.00 | 0.00            | 0.00              | 0.00               | 54995.82        | 0.00                                   | 0.00                          | 4668.00  |      | 0.00                                         | 0.00                                  | 56592.00    | 38558.00       | 11725220.72                    | 9755.57                                   | 
| 99       | Alburnett             | 2016        | 523.7               | 3375770.00      | 125180.00         | 85500.00                                  | 333387.00                                   | 302709.00                 | 34973.00                            | 28684.00                      | 0.00                                          | 0.00                                    | 87021.00  | 0.00                                | 274264.00                          | 0.00                    | 0.00                                      | 200000.00       | 61589.00     | 78060.00                 | 46984.00                | 0.00 | 66719.00                                   | 188024.00                                                  | 16262.00                                 | 3690.05                          | 32332.00  | 0.00            | 0.00              | 0.00               | 14211.23        | 0.00                                   | 0.00                          | 2488.00  |      | 0.00                                         | 0.00                                  | 23235.00    | 0.00           | 5381082.28                     | 10275.12                                  | 
| 108      | Alden                 | 2016        | 258.0               | 1663068.00      | 13144.00          | 137571.00                                 | 153802.00                                   | 154614.00                 | 14569.00                            | 19180.00                      | 0.00                                          | 0.00                                    | 58014.00  | 119048.00                           | 20346.00                           | 0.00                    | 82121.00                                  | 75000.00        | 39292.00     | 0.00                     | 79775.00                | 0.00 | 60598.00                                   | 0.00                                                       | 14051.00                                 | 2635.75                          | 38551.00  | 0.00            | 0.00              | 0.00               | 13971.80        | 0.00                                   | 0.00                          | 912.00   |      | 15597.00                                     | 0.00                                  | 12858.00    | 0.00           | 2788718.55                     | 10808.99                                  | 
| 126      | Algona                | 2016        | 1310.5              | 8490730.00      | 67562.00          | 919344.00                                 | 1322753.00                                  | 738676.00                 | 89586.00                            | 77529.00                      | 0.00                                          | 0.00                                    | 354530.00 | 653771.00                           | 72657.00                           | 0.00                    | 167881.00                                 | 400000.00       | 220882.00    | 0.00                     | 448457.00               | 0.00 | 71004.00                                   | 727912.00                                                  | 22808.00                                 | 2635.75                          | 176696.00 | 0.00            | 0.00              | 0.00               | 64688.61        | 0.00                                   | 0.00                          | 5432.00  |      | 0.00                                         | 0.00                                  | 73517.00    | 0.00           | 15169051.36                    | 11575.01                                  | 
| 135      | Allamakee             | 2016        | 1138.4              | 7431475.00      | 233063.00         | 241595.00                                 | 854385.00                                   | 635208.00                 | 66930.00                            | 73592.00                      | 0.00                                          | 0.00                                    | 215941.00 | 0.00                                | 0.00                               | 0.00                    | 93900.00                                  | 250000.00       | 156445.00    | 476078.00                | 45406.00                | 0.00 | 24484.00                                   | 0.00                                                       | 21376.00                                 | 2635.75                          | 249017.00 | 0.00            | 0.00              | 0.00               | 55039.59        | 0.00                                   | 200372.00                     | 4464.00  |      | 0.00                                         | 0.00                                  | 58887.00    | 0.00           | 11390293.34                    | 10005.53                                  | 
```