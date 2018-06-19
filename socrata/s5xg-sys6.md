# Inpatient Psychiatric Facility Quality Measure Data ? National

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-psychiatric-facility-quality-measure-data-national-b4c94) |
| Metadata | [Link](https://data.medicare.gov/api/views/s5xg-sys6) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/s5xg-sys6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/s5xg-sys6/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | s5xg-sys6 |
| Name | Inpatient Psychiatric Facility Quality Measure Data ? National |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care, psych, national |
| Created | 2014-01-28T14:49:33Z |
| Publication Date | 2016-12-19T02:10:40Z |

## Description

The Inpatient Psychiatric Facility Quality Reporting (IPFQR) program currently uses six measures. Psychiatric facilities that are eligible for this program may have their Medicare payments reduced if they do not report.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | series tag     | n_hbips_2_measure_description   | N_HBIPS-2_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_hbips_2_overall_rate_per_1000 | N_HBIPS-2_Overall_Rate_Per_1000 | number    | text        |
| Yes      | numeric metric | n_hbips_2_overall_num           | N_HBIPS-2_Overall_Num           | number    | text        |
| Yes      | numeric metric | n_hbips_2_overall_den           | N_HBIPS-2_Overall_Den           | number    | text        |
| Yes      | series tag     | n_hbips_3_measure_description   | N_HBIPS-3_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_hbips_3_overall_rate_per_1000 | N_HBIPS-3_Overall_Rate_Per_1000 | number    | text        |
| Yes      | numeric metric | n_hbips_3_overall_num           | N_HBIPS-3_Overall_Num           | number    | text        |
| Yes      | numeric metric | n_hbips_3_overall_den           | N_HBIPS-3_Overall_Den           | number    | text        |
| Yes      | series tag     | n_hbips_5_measure_description   | N_HBIPS-5_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_hbips_5_overall__of_total     | N_HBIPS-5_Overall_%_of_Total    | number    | text        |
| Yes      | numeric metric | n_hbips_5_overall_num           | N_HBIPS-5_Overall_Num           | number    | text        |
| Yes      | numeric metric | n_hbips_5_overall_den           | N_HBIPS-5_Overall_Den           | number    | text        |
| Yes      | series tag     | n_hbips_6_measure_description   | N_HBIPS-6_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_hbips_6_overall__of_total     | N_HBIPS-6_Overall_%_of_Total    | number    | text        |
| Yes      | numeric metric | n_hbips_6_overall_num           | N_HBIPS-6_Overall_Num           | number    | text        |
| Yes      | numeric metric | n_hbips_6_overall_den           | N_HBIPS-6_Overall_Den           | number    | text        |
| Yes      | series tag     | n_hbips_7_measure_description   | N_HBIPS-7_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_hbips_7_overall__of_total     | N_HBIPS-7_Overall_%_of_Total    | number    | text        |
| Yes      | numeric metric | n_hbips_7_overall_num           | N_HBIPS-7_Overall_Num           | number    | text        |
| Yes      | numeric metric | n_hbips_7_overall_den           | N_HBIPS-7_Overall_Den           | number    | text        |
| Yes      | series tag     | n_sub_1_measure_description     | N_SUB-1_Measure_Description     | text      | text        |
| Yes      | numeric metric | n_sub_1_                        | N_SUB-1_%                       | number    | text        |
| Yes      | numeric metric | n_sub_1_numerator               | N_SUB-1_Numerator               | number    | text        |
| Yes      | numeric metric | n_sub_1_denominator             | N_SUB-1_Denominator             | number    | text        |
| Yes      | series tag     | n_tob_1_                        | N_TOB-1_%                       | text      | text        |
| Yes      | numeric metric | n_tob_1_measure_description     | N_TOB-1_Measure_Description     | number    | text        |
| Yes      | numeric metric | n_tob_1_numerator               | N_TOB-1_Numerator               | number    | text        |
| Yes      | numeric metric | n_tob_1_denominator             | N_TOB-1_Denominator             | number    | text        |
| Yes      | series tag     | n_tob_2_2a_measure_desc         | N_TOB-2/-2a_Measure_Desc        | text      | text        |
| Yes      | numeric metric | n_tob_2_                        | N_TOB-2_%                       | number    | text        |
| Yes      | numeric metric | n_tob_2_numerator               | N_TOB-2_Numerator               | number    | text        |
| Yes      | numeric metric | n_tob_2_2a_denominator          | N_TOB-2/-2a_Denominator         | number    | text        |
| Yes      | numeric metric | n_tob_2a_                       | N_TOB-2a_%                      | number    | text        |
| Yes      | numeric metric | n_tob_2a_numerator              | N_TOB-2a_Numerator              | number    | text        |
| Yes      | numeric metric | n_tob_2_2a_denominator_1        | N_TOB-2/-2a__Denominator        | number    | text        |
| Yes      | series tag     | n_peoc_measure_description      | N_PEoC_Measure_Description      | text      | text        |
| Yes      | numeric metric | n_peoc_yes_count                | N_PEoC_Yes_Count                | number    | text        |
| Yes      | numeric metric | n_peoc_no_count                 | N_PEoC_No_Count                 | number    | text        |
| Yes      | numeric metric | n_peoc_yes_                     | N_PEoC_Yes_%                    | number    | text        |
| Yes      | numeric metric | n_peoc_no_                      | N_PEoC_No_%                     | number    | text        |
| Yes      | series tag     | n_ehr_use_measure_description   | N_EHR_Use_Measure_Description   | text      | text        |
| Yes      | numeric metric | n_ehr_paper_count               | N_EHR_Paper_Count               | number    | text        |
| Yes      | numeric metric | n_ehr_non_certified_count       | N_EHR_Non-Certified_Count       | number    | text        |
| Yes      | numeric metric | n_ehr_certified_count           | N_EHR_Certified_Count           | number    | text        |
| Yes      | numeric metric | n_ehr_paper_                    | N_EHR_Paper_%                   | number    | text        |
| Yes      | numeric metric | n_ehr_non_certified_            | N_EHR_Non-Certified_%           | number    | text        |
| Yes      | numeric metric | n_ehr_certified_                | N_EHR_Certified_%               | number    | text        |
| Yes      | series tag     | n_hie_measure_description       | N_HIE_Measure_Description       | text      | text        |
| Yes      | numeric metric | n_hie_yes_count                 | N_HIE_Yes_Count                 | number    | text        |
| Yes      | numeric metric | n_hie_no_count                  | N_HIE_No_Count                  | number    | text        |
| Yes      | numeric metric | n_hie_yes_                      | N_HIE_Yes_%                     | number    | text        |
| Yes      | numeric metric | n_hie_no_                       | N_HIE_No_%                      | number    | text        |
| Yes      | time           | start_date                      | Start_Date                      | text      | text        |
| No       |                | end_date                        | End_Date                        | text      | text        |
| Yes      | series tag     | n_fuh_measure_description       | N_FUH_Measure_Description       | text      | text        |
| Yes      | numeric metric | n_fuh_30_                       | N_FUH-30_%                      | number    | text        |
| Yes      | numeric metric | n_fuh_30_numerator              | N_FUH-30_Numerator              | number    | text        |
| Yes      | numeric metric | n_fuh_30_denominator            | N_FUH-30_Denominator            | number    | text        |
| Yes      | numeric metric | n_fuh_7_                        | N_FUH-7_%                       | number    | text        |
| Yes      | numeric metric | n_fuh_7_numerator               | N_FUH-7_Numerator               | number    | text        |
| Yes      | numeric metric | n_fuh_7_denominator             | N_FUH-7_Denominator             | number    | text        |
| No       |                | n_fuh_measure_start_date        | N_FUH_Measure_Start_Date        | text      | text        |
| No       |                | n_fuh_measure_end_date          | N_FUH_Measure_End_Date          | text      | text        |
| Yes      | series tag     | n_imm_2_measure_description     | N_IMM-2_Measure_Description     | text      | text        |
| Yes      | numeric metric | n_imm_2_                        | N_IMM-2_%                       | number    | text        |
| Yes      | numeric metric | n_imm_2_numerator               | N_IMM-2_Numerator               | number    | text        |
| Yes      | numeric metric | n_imm_2_denominator             | N_IMM-2_Denominator             | number    | text        |
| Yes      | series tag     | n_hcp_measure_description       | N_HCP_Measure_Description       | text      | text        |
| Yes      | numeric metric | n_hcp_                          | N_HCP_%                         | number    | text        |
| Yes      | numeric metric | n_hcp_numerator                 | N_HCP_Numerator                 | number    | text        |
| Yes      | numeric metric | n_hcp_denominator               | N_HCP_Denominator               | number    | text        |
| No       |                | n_flu_season_start_date         | N_Flu_Season_Start_Date         | text      | text        |
| No       |                | n_flu_season_end_date           | N_Flu_Season_End_Date           | text      | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = end_date,n_fuh_measure_start_date,n_fuh_measure_end_date,n_flu_season_start_date,n_flu_season_end_date
```

## Data Commands

```ls
series e:s5xg-sys6 d:2015-01-01T00:00:00.000Z t:n_tob_1_="Tobacco Use Screening" t:n_imm_2_measure_description="Influenza Immunization" t:n_hbips_6_measure_description="Post-discharge continuing care plan created" t:n_fuh_measure_description="Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness" t:n_hbips_2_measure_description="Hours of physical-restraint use" t:n_hbips_7_measure_description="Post-discharge continuing care plan transmitted to the next level of care provider upon discharge" t:n_peoc_measure_description="Assessment of Patient Experience of Care" t:n_hbips_3_measure_description="Hours of Seclusion" t:n_tob_2_2a_measure_desc="Tobacco Use Treatment (during the hospital stay)" t:n_hbips_5_measure_description="Patients discharged on multiple antipsychotic medications with appropriate justification" t:n_sub_1_measure_description="Alcohol Use Screening" t:n_hie_measure_description="Interoperable health information exchanged with HISP" t:n_ehr_use_measure_description="Highest level typical use of an EHR system" t:n_hcp_measure_description="Healthcare Personnel Influenza Vaccination" m:n_hbips_7_overall__of_total=78.74 m:n_tob_2_=62.07 m:n_tob_2_numerator=201628 m:n_hbips_2_overall_num=443956.97 m:n_hbips_6_overall_den=905232 m:n_ehr_non_certified_=2.4 m:n_peoc_yes_count=1243 m:n_hcp_numerator=3199522 m:n_hcp_denominator=3754090 m:n_hbips_7_overall_den=903510 m:n_fuh_7_numerator=57437 m:n_tob_1_measure_description=91.33 m:n_hie_yes_count=593 m:n_hbips_5_overall_num=31434 m:n_tob_2a_numerator=101039 m:n_hbips_3_overall_num=309951.85 m:n_hie_no_=63.57 m:n_ehr_certified_=38.02 m:n_hbips_5_overall__of_total=57.01 m:n_sub_1_denominator=685750 m:n_hbips_2_overall_rate_per_1000=0.68 m:n_tob_1_numerator=648899 m:n_imm_2_numerator=345665 m:n_ehr_paper_=59.58 m:n_fuh_30_=53.9 m:n_hbips_6_overall_num=765735 m:n_fuh_7_=30.79 m:n_hbips_3_overall_rate_per_1000=0.49 m:n_peoc_no_=23.65 m:n_tob_2a_=31.1 m:n_peoc_yes_=76.35 m:n_ehr_certified_count=619 m:n_tob_1_denominator=710481 m:n_sub_1_numerator=597943 m:n_imm_2_=70.71 m:n_hbips_6_overall__of_total=84.59 m:n_hbips_7_overall_num=711406 m:n_fuh_30_denominator=186537 m:n_hbips_3_overall_den=26480485 m:n_hbips_5_overall_den=55142 m:n_sub_1_=87.2 m:n_hbips_2_overall_den=27089864 m:n_ehr_paper_count=970 m:n_peoc_no_count=385 m:n_fuh_7_denominator=186537 m:n_hcp_=85 m:n_tob_2_2a_denominator=324847 m:n_tob_2_2a_denominator_1=324847 m:n_ehr_non_certified_count=39 m:n_fuh_30_numerator=100538 m:n_imm_2_denominator=488842 m:n_hie_yes_=36.43 m:n_hie_no_count=1035
```

## Meta Commands

```ls
metric m:n_hbips_2_overall_rate_per_1000 p:float l:N_HBIPS-2_Overall_Rate_Per_1000 t:dataTypeName=number

metric m:n_hbips_2_overall_num p:float l:N_HBIPS-2_Overall_Num t:dataTypeName=number

metric m:n_hbips_2_overall_den p:integer l:N_HBIPS-2_Overall_Den t:dataTypeName=number

metric m:n_hbips_3_overall_rate_per_1000 p:float l:N_HBIPS-3_Overall_Rate_Per_1000 t:dataTypeName=number

metric m:n_hbips_3_overall_num p:double l:N_HBIPS-3_Overall_Num t:dataTypeName=number

metric m:n_hbips_3_overall_den p:integer l:N_HBIPS-3_Overall_Den t:dataTypeName=number

metric m:n_hbips_5_overall__of_total p:float l:N_HBIPS-5_Overall_%_of_Total t:dataTypeName=number

metric m:n_hbips_5_overall_num p:integer l:N_HBIPS-5_Overall_Num t:dataTypeName=number

metric m:n_hbips_5_overall_den p:integer l:N_HBIPS-5_Overall_Den t:dataTypeName=number

metric m:n_hbips_6_overall__of_total p:float l:N_HBIPS-6_Overall_%_of_Total t:dataTypeName=number

metric m:n_hbips_6_overall_num p:integer l:N_HBIPS-6_Overall_Num t:dataTypeName=number

metric m:n_hbips_6_overall_den p:integer l:N_HBIPS-6_Overall_Den t:dataTypeName=number

metric m:n_hbips_7_overall__of_total p:float l:N_HBIPS-7_Overall_%_of_Total t:dataTypeName=number

metric m:n_hbips_7_overall_num p:integer l:N_HBIPS-7_Overall_Num t:dataTypeName=number

metric m:n_hbips_7_overall_den p:integer l:N_HBIPS-7_Overall_Den t:dataTypeName=number

metric m:n_sub_1_ p:float l:N_SUB-1_% t:dataTypeName=number

metric m:n_sub_1_numerator p:integer l:N_SUB-1_Numerator t:dataTypeName=number

metric m:n_sub_1_denominator p:integer l:N_SUB-1_Denominator t:dataTypeName=number

metric m:n_tob_1_measure_description p:float l:N_TOB-1_Measure_Description t:dataTypeName=number

metric m:n_tob_1_numerator p:integer l:N_TOB-1_Numerator t:dataTypeName=number

metric m:n_tob_1_denominator p:integer l:N_TOB-1_Denominator t:dataTypeName=number

metric m:n_tob_2_ p:float l:N_TOB-2_% t:dataTypeName=number

metric m:n_tob_2_numerator p:integer l:N_TOB-2_Numerator t:dataTypeName=number

metric m:n_tob_2_2a_denominator p:integer l:N_TOB-2/-2a_Denominator t:dataTypeName=number

metric m:n_tob_2a_ p:float l:N_TOB-2a_% t:dataTypeName=number

metric m:n_tob_2a_numerator p:integer l:N_TOB-2a_Numerator t:dataTypeName=number

metric m:n_tob_2_2a_denominator_1 p:integer l:N_TOB-2/-2a__Denominator t:dataTypeName=number

metric m:n_peoc_yes_count p:integer l:N_PEoC_Yes_Count t:dataTypeName=number

metric m:n_peoc_no_count p:integer l:N_PEoC_No_Count t:dataTypeName=number

metric m:n_peoc_yes_ p:float l:N_PEoC_Yes_% t:dataTypeName=number

metric m:n_peoc_no_ p:float l:N_PEoC_No_% t:dataTypeName=number

metric m:n_ehr_paper_count p:integer l:N_EHR_Paper_Count t:dataTypeName=number

metric m:n_ehr_non_certified_count p:integer l:N_EHR_Non-Certified_Count t:dataTypeName=number

metric m:n_ehr_certified_count p:integer l:N_EHR_Certified_Count t:dataTypeName=number

metric m:n_ehr_paper_ p:float l:N_EHR_Paper_% t:dataTypeName=number

metric m:n_ehr_non_certified_ p:float l:N_EHR_Non-Certified_% t:dataTypeName=number

metric m:n_ehr_certified_ p:float l:N_EHR_Certified_% t:dataTypeName=number

metric m:n_hie_yes_count p:integer l:N_HIE_Yes_Count t:dataTypeName=number

metric m:n_hie_no_count p:integer l:N_HIE_No_Count t:dataTypeName=number

metric m:n_hie_yes_ p:float l:N_HIE_Yes_% t:dataTypeName=number

metric m:n_hie_no_ p:float l:N_HIE_No_% t:dataTypeName=number

metric m:n_fuh_30_ p:float l:N_FUH-30_% t:dataTypeName=number

metric m:n_fuh_30_numerator p:integer l:N_FUH-30_Numerator t:dataTypeName=number

metric m:n_fuh_30_denominator p:integer l:N_FUH-30_Denominator t:dataTypeName=number

metric m:n_fuh_7_ p:float l:N_FUH-7_% t:dataTypeName=number

metric m:n_fuh_7_numerator p:integer l:N_FUH-7_Numerator t:dataTypeName=number

metric m:n_fuh_7_denominator p:integer l:N_FUH-7_Denominator t:dataTypeName=number

metric m:n_imm_2_ p:float l:N_IMM-2_% t:dataTypeName=number

metric m:n_imm_2_numerator p:integer l:N_IMM-2_Numerator t:dataTypeName=number

metric m:n_imm_2_denominator p:integer l:N_IMM-2_Denominator t:dataTypeName=number

metric m:n_hcp_ p:integer l:N_HCP_% t:dataTypeName=number

metric m:n_hcp_numerator p:integer l:N_HCP_Numerator t:dataTypeName=number

metric m:n_hcp_denominator p:integer l:N_HCP_Denominator t:dataTypeName=number

entity e:s5xg-sys6 l:"Inpatient Psychiatric Facility Quality Measure Data ? National" t:url=https://data.medicare.gov/api/views/s5xg-sys6

property e:s5xg-sys6 t:meta.view v:id=s5xg-sys6 v:category="Hospital Compare" v:averageRating=0 v:name="Inpatient Psychiatric Facility Quality Measure Data ? National"

property e:s5xg-sys6 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:s5xg-sys6 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:s5xg-sys6 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| n_hbips_2_measure_description   | n_hbips_2_overall_rate_per_1000 | n_hbips_2_overall_num | n_hbips_2_overall_den | n_hbips_3_measure_description | n_hbips_3_overall_rate_per_1000 | n_hbips_3_overall_num | n_hbips_3_overall_den | n_hbips_5_measure_description                                                            | n_hbips_5_overall__of_total | n_hbips_5_overall_num | n_hbips_5_overall_den | n_hbips_6_measure_description               | n_hbips_6_overall__of_total | n_hbips_6_overall_num | n_hbips_6_overall_den | n_hbips_7_measure_description                                                                     | n_hbips_7_overall__of_total | n_hbips_7_overall_num | n_hbips_7_overall_den | n_sub_1_measure_description | n_sub_1_ | n_sub_1_numerator | n_sub_1_denominator | n_tob_1_              | n_tob_1_measure_description | n_tob_1_numerator | n_tob_1_denominator | n_tob_2_2a_measure_desc                          | n_tob_2_ | n_tob_2_numerator | n_tob_2_2a_denominator | n_tob_2a_ | n_tob_2a_numerator | n_tob_2_2a_denominator_1 | n_peoc_measure_description               | n_peoc_yes_count | n_peoc_no_count | n_peoc_yes_ | n_peoc_no_ | n_ehr_use_measure_description              | n_ehr_paper_count | n_ehr_non_certified_count | n_ehr_certified_count | n_ehr_paper_ | n_ehr_non_certified_ | n_ehr_certified_ | n_hie_measure_description                            | n_hie_yes_count | n_hie_no_count | n_hie_yes_ | n_hie_no_ | start_date | end_date   | n_fuh_measure_description                                                                                                              | n_fuh_30_ | n_fuh_30_numerator | n_fuh_30_denominator | n_fuh_7_ | n_fuh_7_numerator | n_fuh_7_denominator | n_fuh_measure_start_date | n_fuh_measure_end_date | n_imm_2_measure_description | n_imm_2_ | n_imm_2_numerator | n_imm_2_denominator | n_hcp_measure_description                  | n_hcp_ | n_hcp_numerator | n_hcp_denominator | n_flu_season_start_date | n_flu_season_end_date | 
| =============================== | =============================== | ===================== | ===================== | ============================= | =============================== | ===================== | ===================== | ======================================================================================== | =========================== | ===================== | ===================== | =========================================== | =========================== | ===================== | ===================== | ================================================================================================= | =========================== | ===================== | ===================== | =========================== | ======== | ================= | =================== | ===================== | =========================== | ================= | =================== | ================================================ | ======== | ================= | ====================== | ========= | ================== | ======================== | ======================================== | ================ | =============== | =========== | ========== | ========================================== | ================= | ========================= | ===================== | ============ | ==================== | ================ | ==================================================== | =============== | ============== | ========== | ========= | ========== | ========== | ====================================================================================================================================== | ========= | ================== | ==================== | ======== | ================= | =================== | ======================== | ====================== | =========================== | ======== | ================= | =================== | ========================================== | ====== | =============== | ================= | ======================= | ===================== | 
| Hours of physical-restraint use | 0.68                            | 443956.97             | 27089864              | Hours of Seclusion            | 0.49                            | 309951.85             | 26480485              | Patients discharged on multiple antipsychotic medications with appropriate justification | 57.01                       | 31434                 | 55142                 | Post-discharge continuing care plan created | 84.59                       | 765735                | 905232                | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 78.74                       | 711406                | 903510                | Alcohol Use Screening       | 87.20    | 597943            | 685750              | Tobacco Use Screening | 91.33                       | 648899            | 710481              | Tobacco Use Treatment (during the hospital stay) | 62.07    | 201628            | 324847                 | 31.10     | 101039             | 324847                   | Assessment of Patient Experience of Care | 1243             | 385             | 76.35       | 23.65      | Highest level typical use of an EHR system | 970               | 39                        | 619                   | 59.58        | 2.40                 | 38.02            | Interoperable health information exchanged with HISP | 593             | 1035           | 36.43      | 63.57     | 01/01/2015 | 12/31/2015 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 53.90     | 100538             | 186537               | 30.79    | 57437             | 186537              | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 70.71    | 345665            | 488842              | Healthcare Personnel Influenza Vaccination | 85     | 3199522         | 3754090           | 10/01/2015              | 03/31/2016            | 
```