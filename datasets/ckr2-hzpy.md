# FY 2015 State and Federal Allocations to Iowa Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-and-federal-allocations-to-iowa-schools) |
| Metadata | [Link](https://data.iowa.gov/api/views/ckr2-hzpy) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ckr2-hzpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ckr2-hzpy/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ckr2-hzpy |
| Name | FY 2015 State and Federal Allocations to Iowa Schools |
| Attribution | Iowa Department of Education |
| Category | Education |
| Tags | education, school, funding |
| Created | 2015-10-07T14:59:08Z |
| Publication Date | 2016-01-28T17:48:27Z |

## Description

State and Federal Funding Allocations by District for Fiscal Year 2015 (year ending 6/30/2015).

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | district                                                   | District                                                   | text      | text        |
| Yes      | series tag     | district_name                                              | District Name                                              | text      | text        |
| Yes      | time           | fiscal_year                                                | Fiscal Year                                                | number    | text        |
| Yes      | numeric metric | budgeted_enrollment                                        | Budgeted Enrollment                                        | number    | number      |
| Yes      | numeric metric | regular_program                                            | Regular Program                                            | money     | money       |
| Yes      | numeric metric | budget_adjustment                                          | Budget Adjustment                                          | money     | money       |
| Yes      | series tag     | district_cost_for_supplementary_weighting                  | District Cost for Supplementary Weighting                  | text      | money       |
| Yes      | series tag     | special_education_instrustion_district_cost                | Special Education Instrustion District Cost                | text      | money       |
| Yes      | numeric metric | teacher_salary_supplement                                  | Teacher Salary Supplement                                  | money     | money       |
| Yes      | numeric metric | professional_development_supplement                        | Professional Development Supplement                        | money     | money       |
| Yes      | numeric metric | early_intervention_supplement                              | Early Intervention Supplement                              | money     | money       |
| Yes      | numeric metric | preschool                                                  | Preschool                                                  | money     | money       |
| Yes      | numeric metric | instructional_support_income_surtax                        | Instructional Support Income Surtax                        | money     | money       |
| Yes      | numeric metric | instructional_support_property_tax                         | Instructional Support Property Tax                         | money     | money       |
| Yes      | numeric metric | educational_improvement                                    | Educational Improvement                                    | money     | money       |
| Yes      | numeric metric | sbrc_modified_supplemental_amount_dropout                  | SBRC Modified Supplemental Amount Dropout                  | money     | money       |
| Yes      | numeric metric | management_levy                                            | Management Levy                                            | money     | money       |
| Yes      | numeric metric | regular_ppel                                               | Regular PPEL                                               | money     | money       |
| Yes      | numeric metric | voted_ppel_income_surtax                                   | Voted PPEL-Income Surtax                                   | money     | money       |
| Yes      | numeric metric | voted_ppel_property_tax                                    | Voted PPEL-Property Tax                                    | money     | money       |
| Yes      | numeric metric | perl                                                       | PERL                                                       | money     | money       |
| Yes      | numeric metric | modified_supplemental_amount_sbrc_approved                 | Modified Supplemental Amount - SBRC Approved               | money     | money       |
| Yes      | numeric metric | modified_supplemental_amount_for_special_education_deficit | Modified Supplemental Amount for Special Education Deficit | money     | money       |
| Yes      | numeric metric | successful_progression_for_early_readers                   | Successful Progression for Early Readers                   | money     | money       |
| Yes      | numeric metric | teacher_leadership_and_compensation_system_grants          | Teacher Leadership and Compensation System Grants          | money     | money       |
| Yes      | numeric metric | educator_mentoring_and_induction                           | Educator Mentoring and Induction                           | money     | money       |
| Yes      | numeric metric | title_i                                                    | Title I                                                    | money     | money       |
| Yes      | numeric metric | title_i_migrant                                            | Title I Migrant                                            | money     | money       |
| Yes      | numeric metric | title_i_neglected                                          | Title I Neglected                                          | money     | money       |
| Yes      | numeric metric | title_i_delinquent                                         | Title I Delinquent                                         | money     | money       |
| Yes      | numeric metric | title_ii_part_a                                            | Title II Part A                                            | money     | money       |
| Yes      | numeric metric | title_iii_english_language_acquisition                     | Title III English Language Acquisition                     | money     | money       |
| Yes      | numeric metric | 21st_century_learning_centers                              | 21st Century Learning Centers                              | money     | money       |
| Yes      | numeric metric | title_vi                                                   | Title VI                                                   | money     | money       |
| Yes      | numeric metric | small_rural_schools_achievement_program_reap               | Small Rural Schools Achievement Program (REAP)             | money     | money       |
| Yes      | numeric metric | rural_low_income_schools_rlis_program                      | Rural Low Income Schools (RLIS) Program                    | money     | money       |
| Yes      | numeric metric | idea_part_b                                                | IDEA Part B                                                | money     | money       |
| Yes      | numeric metric | carl_d_perkins                                             | Carl D. Perkins                                            | money     | money       |
| Yes      | numeric metric | total_funding_of_sources_shown                             | Total Funding of Sources Shown                             | money     | money       |
| Yes      | numeric metric | per_pupil_amount_of_funding_sources_shown                  | Per Pupil Amount of Funding Sources Shown                  | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ckr2-hzpy d:2015-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=484793 t:district_cost_for_supplementary_weighting=116859 t:district_name=AGWSR t:district=9 m:early_intervention_supplement=31903 m:instructional_support_property_tax=333866 m:modified_supplemental_amount_for_special_education_deficit=62381 m:sbrc_modified_supplemental_amount_dropout=94829 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=35162 m:teacher_salary_supplement=343638 m:per_pupil_amount_of_funding_sources_shown=10714 m:regular_program=3860991 m:teacher_leadership_and_compensation_system_grants=0 m:total_funding_of_sources_shown=6387886 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=57619 m:21st_century_learning_centers=0 m:preschool=79575 m:modified_supplemental_amount_sbrc_approved=78013 m:title_ii_part_a=25043 m:carl_d_perkins=0 m:budget_adjustment=20723 m:successful_progression_for_early_readers=16814 m:budgeted_enrollment=596.2 m:title_i_neglected=0 m:regular_ppel=109714 m:management_levy=100000 m:educational_improvement=0 m:instructional_support_income_surtax=0 m:title_i=74468 m:professional_development_supplement=36970 m:idea_part_b=28773 m:voted_ppel_income_surtax=387887 m:title_vi=2665 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=5200 m:title_i_delinquent=0

series e:ckr2-hzpy d:2015-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=289780 t:district_cost_for_supplementary_weighting=134284 t:district_name=Adair-Casey t:district=18 m:early_intervention_supplement=22574 m:instructional_support_property_tax=106578 m:modified_supplemental_amount_for_special_education_deficit=0 m:sbrc_modified_supplemental_amount_dropout=60406 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=21933 m:teacher_salary_supplement=207277 m:per_pupil_amount_of_funding_sources_shown=11527 m:regular_program=2090594 m:teacher_leadership_and_compensation_system_grants=0 m:total_funding_of_sources_shown=3785622 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=168025 m:21st_century_learning_centers=0 m:preschool=38196 m:modified_supplemental_amount_sbrc_approved=59410 m:title_ii_part_a=13009 m:carl_d_perkins=0 m:budget_adjustment=118309 m:successful_progression_for_early_readers=14577 m:budgeted_enrollment=328.4 m:title_i_neglected=0 m:regular_ppel=60316 m:management_levy=100000 m:educational_improvement=0 m:instructional_support_income_surtax=76893 m:title_i=80749 m:professional_development_supplement=20405 m:idea_part_b=14854 m:voted_ppel_income_surtax=76893 m:title_vi=1460 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=9100 m:title_i_delinquent=0

series e:ckr2-hzpy d:2015-01-01T00:00:00.000Z t:special_education_instrustion_district_cost=1071890 t:district_cost_for_supplementary_weighting=109143 t:district_name="Adel DeSoto Minburn" t:district=27 m:early_intervention_supplement=92799 m:instructional_support_property_tax=669603 m:modified_supplemental_amount_for_special_education_deficit=269926 m:sbrc_modified_supplemental_amount_dropout=241390 m:title_i_migrant=0 m:small_rural_schools_achievement_program_reap=0 m:teacher_salary_supplement=829197 m:per_pupil_amount_of_funding_sources_shown=9585 m:regular_program=9457666 m:teacher_leadership_and_compensation_system_grants=0 m:total_funding_of_sources_shown=14195919 m:perl=0 m:rural_low_income_schools_rlis_program=0 m:voted_ppel_property_tax=408638 m:21st_century_learning_centers=0 m:preschool=0 m:modified_supplemental_amount_sbrc_approved=183012 m:title_ii_part_a=26875 m:carl_d_perkins=0 m:budget_adjustment=0 m:successful_progression_for_early_readers=24204 m:budgeted_enrollment=1481 m:title_i_neglected=0 m:regular_ppel=134851 m:management_levy=400000 m:educational_improvement=0 m:instructional_support_income_surtax=0 m:title_i=97041 m:professional_development_supplement=89482 m:idea_part_b=66707 m:voted_ppel_income_surtax=0 m:title_vi=7895 m:title_iii_english_language_acquisition=0 m:educator_mentoring_and_induction=15600 m:title_i_delinquent=0
```

## Meta Commands

```ls
metric m:budgeted_enrollment p:float l:"Budgeted Enrollment" t:dataTypeName=number

metric m:regular_program p:integer l:"Regular Program" t:dataTypeName=money

metric m:budget_adjustment p:integer l:"Budget Adjustment" t:dataTypeName=money

metric m:teacher_salary_supplement p:integer l:"Teacher Salary Supplement" t:dataTypeName=money

metric m:professional_development_supplement p:integer l:"Professional Development Supplement" t:dataTypeName=money

metric m:early_intervention_supplement p:integer l:"Early Intervention Supplement" t:dataTypeName=money

metric m:preschool p:integer l:Preschool t:dataTypeName=money

metric m:instructional_support_income_surtax p:integer l:"Instructional Support Income Surtax" t:dataTypeName=money

metric m:instructional_support_property_tax p:integer l:"Instructional Support Property Tax" t:dataTypeName=money

metric m:educational_improvement p:integer l:"Educational Improvement" t:dataTypeName=money

metric m:sbrc_modified_supplemental_amount_dropout p:integer l:"SBRC Modified Supplemental Amount Dropout" t:dataTypeName=money

metric m:management_levy p:integer l:"Management Levy" t:dataTypeName=money

metric m:regular_ppel p:integer l:"Regular PPEL" t:dataTypeName=money

metric m:voted_ppel_income_surtax p:integer l:"Voted PPEL-Income Surtax" t:dataTypeName=money

metric m:voted_ppel_property_tax p:integer l:"Voted PPEL-Property Tax" t:dataTypeName=money

metric m:perl p:integer l:PERL t:dataTypeName=money

metric m:modified_supplemental_amount_sbrc_approved p:integer l:"Modified Supplemental Amount - SBRC Approved" t:dataTypeName=money

metric m:modified_supplemental_amount_for_special_education_deficit p:integer l:"Modified Supplemental Amount for Special Education Deficit" t:dataTypeName=money

metric m:successful_progression_for_early_readers p:integer l:"Successful Progression for Early Readers" t:dataTypeName=money

metric m:teacher_leadership_and_compensation_system_grants p:integer l:"Teacher Leadership and Compensation System Grants" t:dataTypeName=money

metric m:educator_mentoring_and_induction p:integer l:"Educator Mentoring and Induction" t:dataTypeName=money

metric m:title_i p:integer l:"Title I" t:dataTypeName=money

metric m:title_i_migrant p:integer l:"Title I Migrant" t:dataTypeName=money

metric m:title_i_neglected p:integer l:"Title I Neglected" t:dataTypeName=money

metric m:title_i_delinquent p:integer l:"Title I Delinquent" t:dataTypeName=money

metric m:title_ii_part_a p:integer l:"Title II Part A" t:dataTypeName=money

metric m:title_iii_english_language_acquisition p:integer l:"Title III English Language Acquisition" t:dataTypeName=money

metric m:21st_century_learning_centers p:integer l:"21st Century Learning Centers" t:dataTypeName=money

metric m:title_vi p:integer l:"Title VI" t:dataTypeName=money

metric m:small_rural_schools_achievement_program_reap p:integer l:"Small Rural Schools Achievement Program (REAP)" t:dataTypeName=money

metric m:rural_low_income_schools_rlis_program p:integer l:"Rural Low Income Schools (RLIS) Program" t:dataTypeName=money

metric m:idea_part_b p:integer l:"IDEA Part B" t:dataTypeName=money

metric m:carl_d_perkins p:integer l:"Carl D. Perkins" t:dataTypeName=money

metric m:total_funding_of_sources_shown p:integer l:"Total Funding of Sources Shown" t:dataTypeName=money

metric m:per_pupil_amount_of_funding_sources_shown p:integer l:"Per Pupil Amount of Funding Sources Shown" t:dataTypeName=money

entity e:ckr2-hzpy l:"FY 2015 State and Federal Allocations to Iowa Schools" t:attribution="Iowa Department of Education" t:url=https://data.iowa.gov/api/views/ckr2-hzpy

property e:ckr2-hzpy t:meta.view v:id=ckr2-hzpy v:category=Education v:attributionLink=https://www.educateiowa.gov/ v:averageRating=0 v:name="FY 2015 State and Federal Allocations to Iowa Schools" v:attribution="Iowa Department of Education"

property e:ckr2-hzpy t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:ckr2-hzpy t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| district | district_name         | fiscal_year | budgeted_enrollment | regular_program | budget_adjustment | district_cost_for_supplementary_weighting | special_education_instrustion_district_cost | teacher_salary_supplement | professional_development_supplement | early_intervention_supplement | preschool | instructional_support_income_surtax | instructional_support_property_tax | educational_improvement | sbrc_modified_supplemental_amount_dropout | management_levy | regular_ppel | voted_ppel_income_surtax | voted_ppel_property_tax | perl | modified_supplemental_amount_sbrc_approved | modified_supplemental_amount_for_special_education_deficit | successful_progression_for_early_readers | teacher_leadership_and_compensation_system_grants | educator_mentoring_and_induction | title_i | title_i_migrant | title_i_neglected | title_i_delinquent | title_ii_part_a | title_iii_english_language_acquisition | 21st_century_learning_centers | title_vi | small_rural_schools_achievement_program_reap | rural_low_income_schools_rlis_program | idea_part_b | carl_d_perkins | total_funding_of_sources_shown | per_pupil_amount_of_funding_sources_shown | 
| ======== | ===================== | =========== | =================== | =============== | ================= | ========================================= | =========================================== | ========================= | =================================== | ============================= | ========= | =================================== | ================================== | ======================= | ========================================= | =============== | ============ | ======================== | ======================= | ==== | ========================================== | ========================================================== | ======================================== | ================================================= | ================================ | ======= | =============== | ================= | ================== | =============== | ====================================== | ============================= | ======== | ============================================ | ===================================== | =========== | ============== | ============================== | ========================================= | 
|          |                       |             |                     |                 |                   |                                           |                                             |                           |                                     |                               |           |                                     |                                    |                         |                                           |                 |              |                          |                         |      |                                            |                                                            |                                          |                                                   |                                  |         |                 |                   |                    |                 |                                        |                               |          |                                              |                                       |             |                |                                |                                           | 
|          |                       |             |                     |                 |                   |                                           |                                             |                           |                                     |                               |           |                                     |                                    |                         |                                           |                 |              |                          |                         |      |                                            |                                                            |                                          |                                                   |                                  |         |                 |                   |                    |                 |                                        |                               |          |                                              |                                       |             |                |                                |                                           | 
|          |                       |             |                     |                 |                   |                                           |                                             |                           |                                     |                               |           |                                     |                                    |                         |                                           |                 |              |                          |                         |      |                                            |                                                            |                                          |                                                   |                                  |         |                 |                   |                    |                 |                                        |                               |          |                                              |                                       |             |                |                                |                                           | 
|          |                       |             |                     |                 |                   |                                           |                                             |                           |                                     |                               |           |                                     |                                    |                         |                                           |                 |              |                          |                         |      |                                            |                                                            |                                          |                                                   |                                  |         |                 |                   |                    |                 |                                        |                               |          |                                              |                                       |             |                |                                |                                           | 
|          |                       |             |                     |                 |                   |                                           |                                             |                           |                                     |                               |           |                                     |                                    |                         |                                           |                 |              |                          |                         |      |                                            |                                                            |                                          |                                                   |                                  |         |                 |                   |                    |                 |                                        |                               |          |                                              |                                       |             |                |                                |                                           | 
| 9        | AGWSR                 | 2015        | 596.2               | 3860991         | 20723             | 116859                                    | 484793                                      | 343638                    | 36970                               | 31903                         | 79575     | 0                                   | 333866                             | 0                       | 94829                                     | 100000          | 109714       | 387887                   | 57619                   | 0    | 78013                                      | 62381                                                      | 16814                                    | 0                                                 | 5200                             | 74468   | 0               | 0                 | 0                  | 25043           | 0                                      | 0                             | 2665     | 35162                                        | 0                                     | 28773       | 0              | 6387886                        | 10714                                     | 
| 18       | Adair-Casey           | 2015        | 328.4               | 2090594         | 118309            | 134284                                    | 289780                                      | 207277                    | 20405                               | 22574                         | 38196     | 76893                               | 106578                             | 0                       | 60406                                     | 100000          | 60316        | 76893                    | 168025                  | 0    | 59410                                      | 0                                                          | 14577                                    | 0                                                 | 9100                             | 80749   | 0               | 0                 | 0                  | 13009           | 0                                      | 0                             | 1460     | 21933                                        | 0                                     | 14854       | 0              | 3785622                        | 11527                                     | 
| 27       | Adel DeSoto Minburn   | 2015        | 1481.0              | 9457666         | 0                 | 109143                                    | 1071890                                     | 829197                    | 89482                               | 92799                         | 0         | 0                                   | 669603                             | 0                       | 241390                                    | 400000          | 134851       | 0                        | 408638                  | 0    | 183012                                     | 269926                                                     | 24204                                    | 0                                                 | 15600                            | 97041   | 0               | 0                 | 0                  | 26875           | 0                                      | 0                             | 7895     | 0                                            | 0                                     | 66707       | 0              | 14195919                       | 9585                                      | 
| 63       | Akron Westfield       | 2015        | 520.0               | 3336840         | 0                 | 164128                                    | 367181                                      | 306977                    | 35173                               | 33701                         | 38196     | 98058                               | 155842                             | 0                       | 141215                                    | 250000          | 57105        | 0                        | 173045                  | 0    | 61412                                      | 111390                                                     | 16177                                    | 0                                                 | 6500                             | 49317   | 0               | 0                 | 0                  | 13202           | 0                                      | 0                             | 2825     | 45060                                        | 0                                     | 24477       | 0              | 5487821                        | 10554                                     | 
| 72       | Albert City-Truesdale | 2015        | 202.0               | 1302294         | 31942             | 127399                                    | 144735                                      | 95247                     | 7838                                | 8096                          | 41379     | 0                                   | 118614                             | 0                       | 0                                         | 150000          | 45099        | 0                        | 183129                  | 0    | 54009                                      | 9005                                                       | 13521                                    | 0                                                 | 3900                             | 38787   | 0               | 0                 | 0                  | 4763            | 0                                      | 0                             | 480      | 14600                                        | 0                                     | 9598        | 0              | 2404436                        | 11903                                     | 
```