# Dialysis Facility Compare - National Averages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dialysis-facility-compare-national-averages-eaa7c) |
| Metadata | [Link](https://data.medicare.gov/api/views/2rkq-ygai) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/2rkq-ygai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/2rkq-ygai/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | 2rkq-ygai |
| Name | Dialysis Facility Compare - National Averages |
| Category | Dialysis Facility Compare |
| Tags | dfc, dialysis, medicare, comparison, statistics, national, quality measures |
| Created | 2013-01-09T16:23:37Z |
| Publication Date | 2017-01-26T01:48:59Z |

## Description

National averages of common dialysis quality measures.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                 | Name                                                                                    | Data Type | Render Type |
| ======== | ============== | ========================================================================================================== | ======================================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                                                                | updated_at                                                                              | meta_data | meta_data   |
| Yes      | series tag     | country                                                                                                    | Country                                                                                 | text      | text        |
| Yes      | numeric metric | percentage_of_patients_with_hgb_10_g_dl                                                                    | Percentage of patients with Hgb<10 g/dL                                                 | percent   | percent     |
| Yes      | numeric metric | percentage_of_patients_with_hgb_12_g_dl                                                                    | Percentage of patients with Hgb> 12 g/dL                                                | percent   | percent     |
| Yes      | numeric metric | transfusion_rate_us                                                                                        | Transfusion Rate (US)                                                                   | number    | text        |
| Yes      | numeric metric | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_better_than_expected | Transfusions- Better than expected (US)                                                 | number    | number      |
| Yes      | numeric metric | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_as_expected          | Transfusions- As expected (US)                                                          | number    | number      |
| Yes      | numeric metric | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_worse_than_expected  | Transfusions- Worse than expected (US)                                                  | number    | number      |
| Yes      | numeric metric | percentage_of_adult_hd_patients_with_kt_v_1_2                                                              | Percentage of Adult HD patients with Kt/V >=1.2                                         | percent   | percent     |
| Yes      | numeric metric | percentage_of_adult_pd_pts_with_kt_v_1_7                                                                   | Percentage of Adult PD PTS with Kt/V >=1.7                                              | percent   | percent     |
| Yes      | numeric metric | percentage_of_pediatric_hd_patients_with_kt_v_1_2                                                          | Percentage of Pediatric HD patients with Kt/V >=1.2                                     | percent   | percent     |
| Yes      | numeric metric | percentage_of_pediatric_pd_patients_with_kt_v_1_8                                                          | Percentage of pediatric PD patients with Kt/V>=1.8                                      | number    | text        |
| Yes      | numeric metric | percentage_of_patients_with_arteriovenous_fistulae_in_place                                                | Percentage of patients with arteriovenous fistulae in place                             | percent   | percent     |
| Yes      | numeric metric | percentage_of_patients_with_vascular_catheter_in_use_for_90_days_or_longer                                 | Percentage of patients with vascular catheter in use for 90 days or longer              | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_hypercalcemia_serum_calcium_greater_than_10_2_mg_dl            | Percentage of Adult patients with hypercalcemia (serum calcium greater than 10.2 mg/dL) | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_serum_phosphorus_less_than_3_5_mg_dl                           | Percentage of Adult patients with serum phosphorus less than 3.5 mg/dL                  | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_3_5_4_5_mg_dl                         | Percentage of Adult patients with serum phosphorus between 3.5-4.5 mg/dL                | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_4_6_5_5_mg_dl                         | Percentage of Adult patients with serum phosphorus between 4.6-5.5 mg/dL                | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_5_6_7_0_mg_dl                         | Percentage of Adult patients with serum phosphorus between 5.6-7.0 mg/dL                | percent   | percent     |
| Yes      | numeric metric | lists_the_percentage_of_adult_patients_with_serum_phosphorus_greater_than_7_0_mg_dl                        | Percentage of Adult patients with serum phosphorus greater than 7.0 mg/dL               | percent   | percent     |
| Yes      | numeric metric | hospitalizations_better_than_expected                                                                      | Hospitalizations- Better than expected (US)                                             | number    | text        |
| Yes      | numeric metric | hospitalizations_as_expected                                                                               | Hospitalizations- As expected (US)                                                      | number    | text        |
| Yes      | numeric metric | hospitalizations_worse_than_expected                                                                       | Hospitalizations- Worse than expected (US)                                              | number    | text        |
| Yes      | numeric metric | readmission_rate_us                                                                                        | Readmission Rate (US)                                                                   | number    | text        |
| Yes      | numeric metric | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_better_than_expected  | Hospital Readmission- Better than expected (US)                                         | number    | number      |
| Yes      | numeric metric | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_as_expected           | Hospital Readmission- As expected (US)                                                  | number    | number      |
| Yes      | numeric metric | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_worse_than_expected   | Hospital Readmission- Worse than expected (US)                                          | number    | number      |
| Yes      | numeric metric | survival_better_than_expected                                                                              | Survival- Better than expected (US)                                                     | number    | text        |
| Yes      | numeric metric | survival_as_expected                                                                                       | Survival- As expected (US)                                                              | number    | text        |
| Yes      | numeric metric | survival_worse_than_expected                                                                               | Survival- Worse than expected (US)                                                      | number    | text        |
| Yes      | numeric metric | mortality_rate_us                                                                                          | Mortality Rate (US)                                                                     | number    | text        |
| Yes      | numeric metric | hospitalization_rate_us                                                                                    | Hospitalization Rate (US)                                                               | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2rkq-ygai d:2017-01-09T17:49:40.000Z t:country=NATION m:transfusion_rate_us=39.4 m:hospitalizations_better_than_expected=66 m:percentage_of_adult_hd_patients_with_kt_v_1_2=94 m:survival_better_than_expected=511 m:percentage_of_patients_with_hgb_12_g_dl=0 m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_better_than_expected=19 m:mortality_rate_us=17.5 m:percentage_of_adult_pd_pts_with_kt_v_1_7=85 m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_5_6_7_0_mg_dl=22 m:lists_the_percentage_of_adult_patients_with_hypercalcemia_serum_calcium_greater_than_10_2_mg_dl=1 m:percentage_of_pediatric_pd_patients_with_kt_v_1_8=58 m:survival_as_expected=5192 m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_worse_than_expected=363 m:readmission_rate_us=25.3 m:percentage_of_patients_with_vascular_catheter_in_use_for_90_days_or_longer=11 m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_worse_than_expected=152 m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_less_than_3_5_mg_dl=9 m:percentage_of_patients_with_hgb_10_g_dl=16 m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_better_than_expected=112 m:percentage_of_patients_with_arteriovenous_fistulae_in_place=66 m:hospitalizations_worse_than_expected=313 m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_as_expected=5325 m:survival_worse_than_expected=451 m:hospitalization_rate_us=180.4 m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_greater_than_7_0_mg_dl=13 m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_4_6_5_5_mg_dl=30 m:hospitalizations_as_expected=5848 m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_3_5_4_5_mg_dl=26 m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_as_expected=5899 m:percentage_of_pediatric_hd_patients_with_kt_v_1_2=91
```

## Meta Commands

```ls
metric m:percentage_of_patients_with_hgb_10_g_dl p:integer l:"Percentage of patients with Hgb<10 g/dL" t:dataTypeName=percent

metric m:percentage_of_patients_with_hgb_12_g_dl p:integer l:"Percentage of patients with Hgb> 12 g/dL" t:dataTypeName=percent

metric m:transfusion_rate_us p:float l:"Transfusion Rate (US)" t:dataTypeName=number

metric m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_better_than_expected p:integer l:"Transfusions- Better than expected (US)" t:dataTypeName=number

metric m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_as_expected p:integer l:"Transfusions- As expected (US)" t:dataTypeName=number

metric m:lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_worse_than_expected p:integer l:"Transfusions- Worse than expected (US)" t:dataTypeName=number

metric m:percentage_of_adult_hd_patients_with_kt_v_1_2 p:integer l:"Percentage of Adult HD patients with Kt/V >=1.2" t:dataTypeName=percent

metric m:percentage_of_adult_pd_pts_with_kt_v_1_7 p:integer l:"Percentage of Adult PD PTS with Kt/V >=1.7" t:dataTypeName=percent

metric m:percentage_of_pediatric_hd_patients_with_kt_v_1_2 p:integer l:"Percentage of Pediatric HD patients with Kt/V >=1.2" t:dataTypeName=percent

metric m:percentage_of_pediatric_pd_patients_with_kt_v_1_8 p:integer l:"Percentage of pediatric PD patients with Kt/V>=1.8" t:dataTypeName=number

metric m:percentage_of_patients_with_arteriovenous_fistulae_in_place p:integer l:"Percentage of patients with arteriovenous fistulae in place" t:dataTypeName=percent

metric m:percentage_of_patients_with_vascular_catheter_in_use_for_90_days_or_longer p:integer l:"Percentage of patients with vascular catheter in use for 90 days or longer" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_hypercalcemia_serum_calcium_greater_than_10_2_mg_dl p:integer l:"Percentage of Adult patients with hypercalcemia (serum calcium greater than 10.2 mg/dL)" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_less_than_3_5_mg_dl p:integer l:"Percentage of Adult patients with serum phosphorus less than 3.5 mg/dL" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_3_5_4_5_mg_dl p:integer l:"Percentage of Adult patients with serum phosphorus between 3.5-4.5 mg/dL" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_4_6_5_5_mg_dl p:integer l:"Percentage of Adult patients with serum phosphorus between 4.6-5.5 mg/dL" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_5_6_7_0_mg_dl p:integer l:"Percentage of Adult patients with serum phosphorus between 5.6-7.0 mg/dL" t:dataTypeName=percent

metric m:lists_the_percentage_of_adult_patients_with_serum_phosphorus_greater_than_7_0_mg_dl p:integer l:"Percentage of Adult patients with serum phosphorus greater than 7.0 mg/dL" t:dataTypeName=percent

metric m:hospitalizations_better_than_expected p:integer l:"Hospitalizations- Better than expected (US)" t:dataTypeName=number

metric m:hospitalizations_as_expected p:integer l:"Hospitalizations- As expected (US)" t:dataTypeName=number

metric m:hospitalizations_worse_than_expected p:integer l:"Hospitalizations- Worse than expected (US)" t:dataTypeName=number

metric m:readmission_rate_us p:float l:"Readmission Rate (US)" t:dataTypeName=number

metric m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_better_than_expected p:integer l:"Hospital Readmission- Better than expected (US)" t:dataTypeName=number

metric m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_as_expected p:integer l:"Hospital Readmission- As expected (US)" t:dataTypeName=number

metric m:number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_worse_than_expected p:integer l:"Hospital Readmission- Worse than expected (US)" t:dataTypeName=number

metric m:survival_better_than_expected p:integer l:"Survival- Better than expected (US)" t:dataTypeName=number

metric m:survival_as_expected p:integer l:"Survival- As expected (US)" t:dataTypeName=number

metric m:survival_worse_than_expected p:integer l:"Survival- Worse than expected (US)" t:dataTypeName=number

metric m:mortality_rate_us p:float l:"Mortality Rate (US)" t:dataTypeName=number

metric m:hospitalization_rate_us p:float l:"Hospitalization Rate (US)" t:dataTypeName=number

entity e:2rkq-ygai l:"Dialysis Facility Compare - National Averages" t:url=https://data.medicare.gov/api/views/2rkq-ygai

property e:2rkq-ygai t:meta.view v:id=2rkq-ygai v:category="Dialysis Facility Compare" v:averageRating=0 v:name="Dialysis Facility Compare - National Averages"

property e:2rkq-ygai t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:2rkq-ygai t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:2rkq-ygai t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=DialysisData@umich.edu v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | country | percentage_of_patients_with_hgb_10_g_dl | percentage_of_patients_with_hgb_12_g_dl | transfusion_rate_us | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_better_than_expected | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_as_expected | lists_the_number_of_facilities_in_the_nation_with_patient_transfusions_categorized_as_worse_than_expected | percentage_of_adult_hd_patients_with_kt_v_1_2 | percentage_of_adult_pd_pts_with_kt_v_1_7 | percentage_of_pediatric_hd_patients_with_kt_v_1_2 | percentage_of_pediatric_pd_patients_with_kt_v_1_8 | percentage_of_patients_with_arteriovenous_fistulae_in_place | percentage_of_patients_with_vascular_catheter_in_use_for_90_days_or_longer | lists_the_percentage_of_adult_patients_with_hypercalcemia_serum_calcium_greater_than_10_2_mg_dl | lists_the_percentage_of_adult_patients_with_serum_phosphorus_less_than_3_5_mg_dl | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_3_5_4_5_mg_dl | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_4_6_5_5_mg_dl | lists_the_percentage_of_adult_patients_with_serum_phosphorus_between_5_6_7_0_mg_dl | lists_the_percentage_of_adult_patients_with_serum_phosphorus_greater_than_7_0_mg_dl | hospitalizations_better_than_expected | hospitalizations_as_expected | hospitalizations_worse_than_expected | readmission_rate_us | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_better_than_expected | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_as_expected | number_of_facilities_in_the_nation_with_patient_hospital_readmissions_categorized_as_worse_than_expected | survival_better_than_expected | survival_as_expected | survival_worse_than_expected | mortality_rate_us | hospitalization_rate_us | 
| =========== | ======= | ======================================= | ======================================= | =================== | ========================================================================================================== | ================================================================================================= | ========================================================================================================= | ============================================= | ======================================== | ================================================= | ================================================= | =========================================================== | ========================================================================== | =============================================================================================== | ================================================================================ | ================================================================================== | ================================================================================== | ================================================================================== | =================================================================================== | ===================================== | ============================ | ==================================== | =================== | ========================================================================================================= | ================================================================================================ | ======================================================================================================== | ============================= | ==================== | ============================ | ================= | ======================= | 
| 1483984180  | NATION  | 16                                      | 0                                       | 39.4                | 19                                                                                                         | 5325                                                                                              | 363                                                                                                       | 94                                            | 85                                       | 91                                                | 58                                                | 66                                                          | 11                                                                         | 1                                                                                               | 9                                                                                | 26                                                                                 | 30                                                                                 | 22                                                                                 | 13                                                                                  | 66                                    | 5848                         | 313                                  | 25.3                | 112                                                                                                       | 5899                                                                                             | 152                                                                                                      | 511                           | 5192                 | 451                          | 17.5              | 180.4                   | 
```