# WA ARTS grants impact

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wa-arts-grants-impact) |
| Metadata | [Link](https://data.wa.gov/api/views/h95v-nqyw) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/h95v-nqyw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/h95v-nqyw/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | h95v-nqyw |
| Name | WA ARTS grants impact |
| Attribution | WA Arts commisison |
| Category | Education |
| Tags | arts, art, grants |
| Created | 2016-03-09T01:13:35Z |
| Publication Date | 2016-03-09T01:33:54Z |

## Description

Grants awarded by the WA State Arts Commission, FY15

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                | Name                                                                                                          | Data Type | Render Type |
| ======== | ============== | ========================================================================================================= | ============================================================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                                               | updated_at                                                                                                    | meta_data | meta_data   |
| Yes      | series tag     | 1_applicant_name                                                                                          | 1. Applicant Name                                                                                             | text      | text        |
| Yes      | series tag     | 2_applicant_street                                                                                        | 2. Applicant Street                                                                                           | text      | text        |
| Yes      | series tag     | 3_applicant_city                                                                                          | 3. Applicant City                                                                                             | text      | text        |
| Yes      | series tag     | 4_applicant_state                                                                                         | 4. Applicant State                                                                                            | text      | text        |
| Yes      | series tag     | 5_applicant_zip                                                                                           | 5. Applicant Zip                                                                                              | text      | text        |
| Yes      | series tag     | 7_applicant_status                                                                                        | 7.Applicant Status                                                                                            | text      | number      |
| Yes      | numeric metric | 8_duns_more_info                                                                                          | 8. DUNS# More Info                                                                                            | number    | number      |
| Yes      | numeric metric | 9_applicant_institution                                                                                   | 9. Applicant Institution                                                                                      | number    | number      |
| Yes      | series tag     | 10_applicant_discipline                                                                                   | 10. Applicant Discipline                                                                                      | text      | text        |
| Yes      | series tag     | 11_nea_primary_strategic_outcome                                                                          | 11. NEA Primary Strategic Outcome                                                                             | text      | text        |
| Yes      | series tag     | 13_project_discipline                                                                                     | 13. Project Discipline                                                                                        | text      | text        |
| Yes      | series tag     | 14_activity_type                                                                                          | 14. Activity Type                                                                                             | text      | number      |
| Yes      | series tag     | 15_project_descriptors_accessibility_international_presenting_touring_technology_youth_at_risk            | 15. Project Descriptors (Accessibility, International, Presenting/Touring, Technology, Youth at Risk)         | text      | text        |
| Yes      | numeric metric | 16_arts_education                                                                                         | 16. Arts Education                                                                                            | number    | number      |
| Yes      | series tag     | 17_project_race                                                                                           | 17. Project Race                                                                                              | text      | text        |
| Yes      | numeric metric | 18_total_individuals_bene_ting                                                                            | 18. Total Individuals Bene?ting                                                                               | number    | number      |
| Yes      | numeric metric | 19_artists_participating                                                                                  | 19. Artists Participating                                                                                     | number    | number      |
| Yes      | numeric metric | 20_children_youth_bene_ting                                                                               | 20. Children/Youth Bene?ting                                                                                  | number    | number      |
| Yes      | numeric metric | 23_amount_requested                                                                                       | 23. Amount Requested                                                                                          | money     | money       |
| Yes      | numeric metric | 24_amount_awarded                                                                                         | 24. Amount Awarded                                                                                            | money     | money       |
| Yes      | numeric metric | 25_amount_spent                                                                                           | 25. Amount Spent                                                                                              | money     | money       |
| Yes      | numeric metric | 26_total_cash_expenses                                                                                    | 26. Total Cash Expenses                                                                                       | money     | money       |
| Yes      | numeric metric | 27_total_project_cash_income                                                                              | 27. Total Project Cash Income                                                                                 | money     | money       |
| Yes      | numeric metric | 28_total_project_in_kind                                                                                  | 28. Total Project In-kind                                                                                     | money     | money       |
| Yes      | numeric metric | 29_nea_share                                                                                              | 29. NEA Share                                                                                                 | money     | money       |
| Yes      | numeric metric | 30_saa_share                                                                                              | 30. SAA Share                                                                                                 | money     | money       |
| Yes      | numeric metric | 31_other_share                                                                                            | 31. Other Share                                                                                               | money     | money       |
| Yes      | series tag     | 32_saa_unique_identifier                                                                                  | 32. SAA Unique Identifier                                                                                     | text      | number      |
| Yes      | series tag     | constituent_id                                                                                            | Constituent ID                                                                                                | text      | text        |
| Yes      | series tag     | custom_project_descriptors_cultural_heritage_toursim_economic_development_health_healing_and_older_adults | Custom Project Descriptors (Cultural Heritage Toursim, Economic Development, Health/Healing and Older Adults) | text      | text        |
| Yes      | series tag     | artswa_program                                                                                            | ArtsWA Program                                                                                                | text      | text        |
| Yes      | series tag     | sub_program_code                                                                                          | Sub Program Code                                                                                              | text      | text        |
| Yes      | series tag     | congressional_district                                                                                    | Congressional District                                                                                        | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h95v-nqyw d:2016-03-08T17:13:46.000Z t:13_project_discipline=03 t:14_activity_type=5 t:3_applicant_city="Federal Way" t:2_applicant_street="PO Box 4513" t:constituent_id=23-7310860 t:congressional_district=9 t:15_project_descriptors_accessibility_international_presenting_touring_technology_youth_at_risk="P, T" t:11_nea_primary_strategic_outcome=B t:artswa_program=GO t:32_saa_unique_identifier=2015024 t:4_applicant_state=Washington t:custom_project_descriptors_cultural_heritage_toursim_economic_development_health_healing_and_older_adults="C, O" t:17_project_race=G t:1_applicant_name="Federal Way Symphony" t:5_applicant_zip=98003 t:10_applicant_discipline=02 t:7_applicant_status=2 t:sub_program_code=PSA m:16_arts_education=2 m:25_amount_spent=2000 m:18_total_individuals_bene_ting=300 m:8_duns_more_info=19026405 m:19_artists_participating=56 m:23_amount_requested=2500 m:27_total_project_cash_income=76892 m:20_children_youth_bene_ting=69 m:26_total_cash_expenses=201004 m:24_amount_awarded=2000 m:9_applicant_institution=3 m:29_nea_share=2000 m:28_total_project_in_kind=3000 m:31_other_share=0 m:30_saa_share=0

series e:h95v-nqyw d:2016-03-08T17:13:46.000Z t:13_project_discipline=09 t:14_activity_type=12 t:3_applicant_city=Morton t:2_applicant_street="233 W. Main" t:constituent_id=42-1571555 t:11_nea_primary_strategic_outcome=C t:32_saa_unique_identifier=2015026 t:artswa_program=GO t:4_applicant_state=Washington t:17_project_race=G t:1_applicant_name="Fire Mountain Arts Council" t:5_applicant_zip=98356 t:10_applicant_discipline=04E t:7_applicant_status=2 t:sub_program_code=PSA m:16_arts_education=1 m:25_amount_spent=1000 m:18_total_individuals_bene_ting=140 m:8_duns_more_info=142426290 m:19_artists_participating=4 m:23_amount_requested=2500 m:27_total_project_cash_income=6803 m:20_children_youth_bene_ting=65 m:26_total_cash_expenses=6803 m:24_amount_awarded=1000 m:9_applicant_institution=16 m:29_nea_share=1000 m:28_total_project_in_kind=98012 m:31_other_share=0 m:30_saa_share=0

series e:h95v-nqyw d:2016-03-08T17:13:46.000Z t:13_project_discipline=02C t:14_activity_type=5 t:3_applicant_city=Olympia t:2_applicant_street="PO Box 1091" t:constituent_id=91-1240717 t:congressional_district=10 t:11_nea_primary_strategic_outcome=D t:32_saa_unique_identifier=2015029 t:artswa_program=GO t:4_applicant_state=Washington t:17_project_race=G t:1_applicant_name="Masterworks Choral Ensemble" t:5_applicant_zip=98507 t:7_applicant_status=2 t:sub_program_code=PSA m:16_arts_education=2 m:25_amount_spent=1000 m:18_total_individuals_bene_ting=470 m:8_duns_more_info=10170756 m:19_artists_participating=58 m:23_amount_requested=1800 m:27_total_project_cash_income=16705 m:20_children_youth_bene_ting=15 m:26_total_cash_expenses=16705 m:24_amount_awarded=1000 m:9_applicant_institution=3 m:29_nea_share=1000 m:28_total_project_in_kind=550 m:31_other_share=0 m:30_saa_share=0
```

## Meta Commands

```ls
metric m:8_duns_more_info p:long l:"8. DUNS# More Info" t:dataTypeName=number

metric m:9_applicant_institution p:integer l:"9. Applicant Institution" t:dataTypeName=number

metric m:16_arts_education p:integer l:"16. Arts Education" t:dataTypeName=number

metric m:18_total_individuals_bene_ting p:float l:"18. Total Individuals Bene?ting" t:dataTypeName=number

metric m:19_artists_participating p:integer l:"19. Artists Participating" t:dataTypeName=number

metric m:20_children_youth_bene_ting p:integer l:"20. Children/Youth Bene?ting" t:dataTypeName=number

metric m:23_amount_requested p:double l:"23. Amount Requested" t:dataTypeName=money

metric m:24_amount_awarded p:integer l:"24. Amount Awarded" t:dataTypeName=money

metric m:25_amount_spent p:integer l:"25. Amount Spent" t:dataTypeName=money

metric m:26_total_cash_expenses p:integer l:"26. Total Cash Expenses" t:dataTypeName=money

metric m:27_total_project_cash_income p:integer l:"27. Total Project Cash Income" t:dataTypeName=money

metric m:28_total_project_in_kind p:double l:"28. Total Project In-kind" t:dataTypeName=money

metric m:29_nea_share p:integer l:"29. NEA Share" t:dataTypeName=money

metric m:30_saa_share p:double l:"30. SAA Share" t:dataTypeName=money

metric m:31_other_share p:integer l:"31. Other Share" t:dataTypeName=money

entity e:h95v-nqyw l:"WA ARTS grants impact" t:attribution="WA Arts commisison" t:url=https://data.wa.gov/api/views/h95v-nqyw

property e:h95v-nqyw t:meta.view v:id=h95v-nqyw v:category=Education v:averageRating=0 v:name="WA ARTS grants impact" v:attribution="WA Arts commisison"

property e:h95v-nqyw t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:h95v-nqyw t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | 1_applicant_name                           | 2_applicant_street   | 3_applicant_city | 4_applicant_state | 5_applicant_zip | 7_applicant_status | 8_duns_more_info | 9_applicant_institution | 10_applicant_discipline | 11_nea_primary_strategic_outcome | 13_project_discipline | 14_activity_type | 15_project_descriptors_accessibility_international_presenting_touring_technology_youth_at_risk | 16_arts_education | 17_project_race | 18_total_individuals_bene_ting | 19_artists_participating | 20_children_youth_bene_ting | 23_amount_requested | 24_amount_awarded | 25_amount_spent | 26_total_cash_expenses | 27_total_project_cash_income | 28_total_project_in_kind | 29_nea_share | 30_saa_share | 31_other_share | 32_saa_unique_identifier | constituent_id | custom_project_descriptors_cultural_heritage_toursim_economic_development_health_healing_and_older_adults | artswa_program | sub_program_code | congressional_district | 
| =========== | ========================================== | ==================== | ================ | ================= | =============== | ================== | ================ | ======================= | ======================= | ================================ | ===================== | ================ | ============================================================================================== | ================= | =============== | ============================== | ======================== | =========================== | =================== | ================= | =============== | ====================== | ============================ | ======================== | ============ | ============ | ============== | ======================== | ============== | ========================================================================================================= | ============== | ================ | ====================== | 
| 1457457226  | PSC                                        |                      |                  |                   |                 |                    |                  |                         |                         |                                  |                       |                  |                                                                                                |                   |                 |                                |                          |                             |                     |                   |                 |                        |                              |                          |              |              |                |                          |                |                                                                                                           |                |                  |                        | 
| 1457457226  | Final Report AIE FY 15 Grant #14-6100-2043 |                      |                  |                   |                 |                    |                  |                         |                         |                                  |                       |                  |                                                                                                |                   |                 |                                |                          |                             |                     |                   |                 |                        |                              |                          |              |              |                |                          |                |                                                                                                           |                |                  |                        | 
| 1457457225  | PSA                                        |                      |                  |                   |                 |                    |                  |                         |                         |                                  |                       |                  |                                                                                                |                   |                 |                                |                          |                             |                     |                   |                 |                        |                              |                          |              |              |                |                          |                |                                                                                                           |                |                  |                        | 
| 1457457226  | Federal Way Symphony                       | PO Box 4513          | Federal Way      | Washington        | 98003           | 2                  | 19026405         | 3                       | 02                      | B                                | 03                    | 5                | P, T                                                                                           | 2                 | G               | 300                            | 56                       | 69                          | 2500                | 2000              | 2000            | 201004                 | 76892                        | 3000                     | 2000         | 0            | 0              | 2015024                  | 23-7310860     | C, O                                                                                                      | GO             | PSA              | 9                      | 
| 1457457226  | Fire Mountain Arts Council                 | 233 W. Main          | Morton           | Washington        | 98356           | 2                  | 142426290        | 16                      | 04E                     | C                                | 09                    | 12               |                                                                                                | 1                 | G               | 140                            | 4                        | 65                          | 2500                | 1000              | 1000            | 6803                   | 6803                         | 98012                    | 1000         | 0            | 0              | 2015026                  | 42-1571555     |                                                                                                           | GO             | PSA              |                        | 
| 1457457226  | Masterworks Choral Ensemble                | PO Box 1091          | Olympia          | Washington        | 98507           | 2                  | 10170756         | 3                       |                         | D                                | 02C                   | 5                |                                                                                                | 2                 | G               | 470                            | 58                       | 15                          | 1800                | 1000              | 1000            | 16705                  | 16705                        | 550                      | 1000         | 0            | 0              | 2015029                  | 91-1240717     |                                                                                                           | GO             | PSA              | 10                     | 
| 1457457226  | Mid-Columbia Mastersingers                 | PO Box 461           | Richland         | Washington        | 99352           | 2                  | 78452165         | 5                       |                         | B                                | 02C                   | 5                |                                                                                                | 2                 | G               | 1275                           | 175                      | 250                         | 2500                | 3000              | 3000            | 19765                  | 19765                        | 0                        | 3000         | 0            | 0              | 2015030                  | 91-1362433     |                                                                                                           | GO             | PSA              | 4                      | 
| 1457457226  |                                            |                      |                  |                   |                 |                    |                  |                         |                         |                                  |                       |                  |                                                                                                |                   |                 |                                |                          |                             |                     |                   |                 |                        |                              |                          |              |              |                |                          |                |                                                                                                           |                |                  |                        | 
| 1457458189  | Northwind Arts Center                      | 2409 Jefferson St.   | Port Townsend    | Washington        | 98368           | 2                  | 145699398        | 15                      |                         | E                                | 05                    | 15               |                                                                                                | 2                 | G               | 2500                           | 150                      | 700                         | 2500                | 2000              | 2000            | 1001012                | 12840                        | 14700                    | 2000         | 0            | 0              | 2015037                  | 02-0584427     |                                                                                                           | GO             | PSA              | 6                      | 
| 1457458189  | Eastside Nihon Matsuri Association         | 17419 NE 126th Place | Redmond          | Washington        | 98052           | 2                  | 912043299        | 14                      | 12                      | C                                | 12                    | 8                | A                                                                                              | 1                 | A               | 22000                          | 325                      | 4000                        | 2500                | 2000              | 2000            | 732010                 | 19654                        | 3000                     | 2000         | 0            | 0              | 2015021                  | 912043299      | C                                                                                                         | GO             | PSA              | 1                      | 
```