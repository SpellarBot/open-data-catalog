# Inpatient Psychiatric Facility Quality Measure Data ? by State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inpatient-psychiatric-facility-quality-measure-data-by-state-90ebf) |
| Metadata | [Link](https://data.medicare.gov/api/views/dc76-gh7x) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/dc76-gh7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/dc76-gh7x/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | dc76-gh7x |
| Name | Inpatient Psychiatric Facility Quality Measure Data ? by State |
| Category | Hospital Compare |
| Tags | hospital compare, timely and effective care, psych, state |
| Created | 2014-01-28T14:50:08Z |
| Publication Date | 2016-12-19T02:11:36Z |

## Description

The Inpatient Psychiatric Facility Quality Reporting (IPFQR) program currently uses six measures. Psychiatric facilities that are eligible for this program may have their Medicare payments reduced if they do not report.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | state                           | State                           | text          | text          |
| Yes      | series tag     | s_hbips_2_measure_description   | S_HBIPS-2_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_hbips_2_overall_rate_per_1000 | S_HBIPS-2_Overall_Rate_Per_1000 | number        | number        |
| Yes      | series tag     | s_hbips_2_overall_num           | S_HBIPS-2_Overall_Num           | text          | number        |
| Yes      | numeric metric | s_hbips_2_overall_den           | S_HBIPS-2_Overall_Den           | number        | number        |
| Yes      | series tag     | s_hbips_3_measure_description   | S_HBIPS-3_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_hbips_3_overall_rate_per_1000 | S_HBIPS-3_Overall_Rate_Per_1000 | number        | number        |
| Yes      | series tag     | s_hbips_3_overall_num           | S_HBIPS-3_Overall_Num           | text          | number        |
| Yes      | numeric metric | s_hbips_3_overall_den           | S_HBIPS-3_Overall_Den           | number        | number        |
| Yes      | series tag     | s_hbips_5_measure_description   | S_HBIPS-5_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_hbips_5__of_total             | S_HBIPS-5_%_of_Total            | number        | number        |
| Yes      | series tag     | s_hbips_5_overall_num           | S_HBIPS-5_Overall_Num           | text          | number        |
| Yes      | numeric metric | s_hbips_5_overall_den           | S_HBIPS-5_Overall_Den           | number        | number        |
| Yes      | series tag     | s_hbips_6_measure_description   | S_HBIPS-6_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_hbips_6__of_total             | S_HBIPS-6_%_of_Total            | number        | number        |
| Yes      | series tag     | s_hbips_6_overall_num           | S_HBIPS-6_Overall_Num           | text          | number        |
| Yes      | numeric metric | s_hbips_6_overall_den           | S_HBIPS-6_Overall_Den           | number        | number        |
| Yes      | series tag     | s_hbips_7_measure_description   | S_HBIPS-7_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_hbips_7_overall__of_total     | S_HBIPS-7_Overall_%_of_Total    | number        | number        |
| Yes      | series tag     | s_hbips_7_overall_num           | S_HBIPS-7_Overall_Num           | text          | number        |
| Yes      | numeric metric | s_hbips_7_overall_den           | S_HBIPS-7_Overall_Den           | number        | number        |
| Yes      | series tag     | s_sub_1_measure_description     | S_SUB-1_Measure_Description     | text          | text          |
| Yes      | numeric metric | s_sub_1_                        | S_SUB-1_%                       | number        | text          |
| Yes      | numeric metric | s_sub_1_numerator               | S_SUB-1_Numerator               | number        | text          |
| Yes      | numeric metric | s_sub_1_denominator             | S_SUB-1_Denominator             | number        | text          |
| Yes      | series tag     | s_tob_1_measure_description     | S_TOB-1_Measure_Description     | text          | text          |
| Yes      | numeric metric | s_tob_1_                        | S_TOB-1_%                       | number        | text          |
| Yes      | numeric metric | s_tob_1_numerator               | S_TOB-1_Numerator               | number        | text          |
| Yes      | numeric metric | s_tob_1_denominator             | S_TOB-1_Denominator             | number        | text          |
| Yes      | series tag     | s_tob_2_2a_measure_desc         | S_TOB-2/-2a_Measure_Desc        | text          | text          |
| Yes      | numeric metric | s_tob_2_                        | S_TOB-2_%                       | number        | text          |
| Yes      | numeric metric | s_tob_2_numerator               | S_TOB-2_Numerator               | number        | text          |
| Yes      | numeric metric | s_tob_2_2a_denominator          | S_TOB-2/-2a_Denominator         | number        | text          |
| Yes      | numeric metric | s_tob_2a_                       | S_TOB-2a_%                      | number        | text          |
| Yes      | numeric metric | s_tob_2a_numerator              | S_TOB-2a_Numerator              | number        | text          |
| Yes      | numeric metric | s_tob_2_2a_denominator_1        | S_TOB-2/-2a__Denominator        | number        | text          |
| Yes      | series tag     | s_peoc_measure_description      | S_PEoC_Measure_Description      | text          | text          |
| Yes      | numeric metric | s_peoc_yes_count                | S_PEoC_Yes_Count                | number        | text          |
| Yes      | numeric metric | s_peoc_no_count                 | S_PEoC_No_Count                 | number        | text          |
| Yes      | numeric metric | s_peoc_yes_                     | S_PEoC_Yes_%                    | number        | text          |
| Yes      | numeric metric | s_peoc_no_                      | S_PEoC_No_%                     | number        | text          |
| Yes      | series tag     | s_ehr_use_measure_description   | S_EHR_Use_Measure_Description   | text          | text          |
| Yes      | numeric metric | s_ehr_paper_count               | S_EHR_Paper_Count               | number        | text          |
| Yes      | numeric metric | s_ehr_non_certified_count       | S_EHR_Non-Certified_Count       | number        | text          |
| Yes      | numeric metric | s_ehr_certified_count           | S_EHR_Certified_Count           | number        | text          |
| Yes      | numeric metric | s_ehr_paper_                    | S_EHR_Paper_%                   | number        | text          |
| Yes      | numeric metric | s_ehr_non_certified_            | S_EHR_Non-Certified_%           | number        | text          |
| Yes      | numeric metric | s_ehr_certified_                | S_EHR_Certified_%               | number        | text          |
| Yes      | series tag     | s_hie_measure_description       | S_HIE_Measure_Description       | text          | text          |
| Yes      | numeric metric | s_hie_yes_count                 | S_HIE_Yes_Count                 | number        | text          |
| Yes      | numeric metric | s_hie_no_count                  | S_HIE_No_Count                  | number        | text          |
| Yes      | numeric metric | s_hie_yes_                      | S_HIE_Yes_%                     | number        | text          |
| Yes      | numeric metric | s_hie_no_                       | S_HIE_No_%                      | number        | text          |
| Yes      | time           | start_date                      | Start_Date                      | calendar_date | calendar_date |
| No       |                | end_date                        | End_Date                        | calendar_date | calendar_date |
| Yes      | series tag     | s_fuh_measure_description       | S_FUH_Measure_Description       | text          | text          |
| Yes      | numeric metric | s_fuh_30_                       | S_FUH-30_%                      | number        | text          |
| Yes      | numeric metric | s_fuh_30_numerator              | S_FUH-30_Numerator              | number        | text          |
| Yes      | numeric metric | s_fuh_30_denominator            | S_FUH-30_Denominator            | number        | text          |
| Yes      | numeric metric | s_fuh_7_                        | S_FUH-7_%                       | number        | text          |
| Yes      | numeric metric | s_fuh_7_numerator               | S_FUH-7_Numerator               | number        | text          |
| Yes      | numeric metric | s_fuh_7_denominator             | S_FUH-7_Denominator             | number        | text          |
| No       |                | s_fuh_measure_start_date        | S_FUH_Measure_Start_Date        | text          | text          |
| No       |                | s_fuh_measure_end_date          | S_FUH_Measure_End_Date          | text          | text          |
| Yes      | series tag     | s_imm_2_measure_description     | S_IMM-2_Measure_Description     | text          | text          |
| Yes      | numeric metric | s_imm_2_                        | S_IMM-2_%                       | number        | text          |
| Yes      | numeric metric | s_imm_2_numerator               | S_IMM-2_Numerator               | number        | text          |
| Yes      | numeric metric | s_imm_2_denominator             | S_IMM-2_Denominator             | number        | text          |
| Yes      | series tag     | s_hcp_measure_description       | S_HCP_Measure_Description       | text          | text          |
| Yes      | numeric metric | s_hcp_                          | S_HCP_%                         | number        | text          |
| Yes      | numeric metric | s_hcp_numerator                 | S_HCP_Numerator                 | number        | text          |
| Yes      | numeric metric | s_hcp_denominator               | S_HCP_Denominator               | number        | text          |
| No       |                | s_flu_season_start_date         | S_Flu_Season_Start_Date         | text          | text          |
| No       |                | s_flu_season_end_date           | S_Flu_Season_End_Date           | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,s_fuh_measure_end_date,s_flu_season_start_date,s_flu_season_end_date,s_fuh_measure_start_date
```

## Data Commands

```ls
series e:dc76-gh7x d:2015-01-01T00:00:00.000Z t:s_hbips_2_overall_num=2476.16 t:s_hcp_measure_description="Healthcare Personnel Influenza Vaccination" t:s_hbips_5_measure_description="Patients discharged on multiple antipsychotic medications with appropriate justification" t:s_hbips_7_measure_description="Post-discharge continuing care plan transmitted to the next level of care provider upon discharge" t:s_peoc_measure_description="Assessment of Patient Experience of Care" t:state=AK t:s_hbips_2_measure_description="Hours of physical-restraint use" t:s_imm_2_measure_description="Influenza Immunization" t:s_fuh_measure_description="Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness" t:s_tob_2_2a_measure_desc="Tobacco Use Treatment Provided or Offered" t:s_hbips_3_measure_description="Hours of Seclusion" t:s_hbips_6_measure_description="Post-discharge continuing care plan created" t:s_hie_measure_description="Interoperable health information exchanged with HISP" t:s_ehr_use_measure_description="Highest level typical use of an EHR system" t:s_hbips_5_overall_num=14 t:s_sub_1_measure_description="Alcohol Use Screening" t:s_hbips_6_overall_num=2296 t:s_hbips_7_overall_num=2076 t:s_tob_1_measure_description="Tobacco Use Screening" t:s_hbips_3_overall_num=1083.38 m:s_hie_yes_count=0 m:s_ehr_non_certified_=33.33 m:s_fuh_30_numerator=86 m:s_ehr_certified_count=0 m:s_hbips_3_overall_rate_per_1000=0.79 m:s_hcp_numerator=12075 m:s_hbips_2_overall_rate_per_1000=1.81 m:s_sub_1_=79.39 m:s_hbips_5_overall_den=67 m:s_hbips_6_overall_den=2344 m:s_hcp_=63 m:s_imm_2_numerator=807 m:s_tob_2_numerator=134 m:s_tob_1_denominator=1286 m:s_sub_1_numerator=986 m:s_tob_1_=81.88 m:s_peoc_no_=0 m:s_hie_no_count=3 m:s_hbips_3_overall_den=56880 m:s_hbips_5__of_total=20.9 m:s_sub_1_denominator=1242 m:s_hbips_6__of_total=97.95 m:s_peoc_no_count=0 m:s_hie_yes_=0 m:s_ehr_non_certified_count=1 m:s_fuh_7_denominator=197 m:s_ehr_paper_count=2 m:s_imm_2_denominator=1118 m:s_hbips_7_overall_den=2344 m:s_hbips_7_overall__of_total=88.57 m:s_fuh_30_=43.65 m:s_peoc_yes_count=3 m:s_ehr_certified_=0 m:s_fuh_30_denominator=197 m:s_ehr_paper_=66.67 m:s_tob_2a_numerator=93 m:s_imm_2_=72.18 m:s_tob_2_2a_denominator_1=659 m:s_tob_2a_=14.11 m:s_tob_2_=20.33 m:s_hbips_2_overall_den=56880 m:s_hcp_denominator=19023 m:s_tob_2_2a_denominator=659 m:s_fuh_7_numerator=39 m:s_fuh_7_=19.8 m:s_peoc_yes_=100 m:s_tob_1_numerator=1053 m:s_hie_no_=100

series e:dc76-gh7x d:2015-01-01T00:00:00.000Z t:s_hbips_2_overall_num=2891.1 t:s_hcp_measure_description="Healthcare Personnel Influenza Vaccination" t:s_hbips_5_measure_description="Patients discharged on multiple antipsychotic medications with appropriate justification" t:s_hbips_7_measure_description="Post-discharge continuing care plan transmitted to the next level of care provider upon discharge" t:s_peoc_measure_description="Assessment of Patient Experience of Care" t:state=AL t:s_hbips_2_measure_description="Hours of physical-restraint use" t:s_imm_2_measure_description="Influenza Immunization" t:s_fuh_measure_description="Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness" t:s_tob_2_2a_measure_desc="Tobacco Use Treatment Provided or Offered" t:s_hbips_3_measure_description="Hours of Seclusion" t:s_hbips_6_measure_description="Post-discharge continuing care plan created" t:s_hie_measure_description="Interoperable health information exchanged with HISP" t:s_ehr_use_measure_description="Highest level typical use of an EHR system" t:s_hbips_5_overall_num=620 t:s_sub_1_measure_description="Alcohol Use Screening" t:s_hbips_6_overall_num=15482 t:s_hbips_7_overall_num=14842 t:s_tob_1_measure_description="Tobacco Use Screening" t:s_hbips_3_overall_num=1700.54 m:s_hie_yes_count=17 m:s_ehr_non_certified_=6.82 m:s_fuh_30_numerator=1335 m:s_ehr_certified_count=15 m:s_hbips_3_overall_rate_per_1000=0.16 m:s_hcp_numerator=103414 m:s_hbips_2_overall_rate_per_1000=0.27 m:s_sub_1_=88.87 m:s_hbips_5_overall_den=1268 m:s_hbips_6_overall_den=19734 m:s_hcp_=76 m:s_imm_2_numerator=5694 m:s_tob_2_numerator=3139 m:s_tob_1_denominator=13981 m:s_sub_1_numerator=12464 m:s_tob_1_=82.92 m:s_peoc_no_=52.27 m:s_hie_no_count=27 m:s_hbips_3_overall_den=440766 m:s_hbips_5__of_total=48.9 m:s_sub_1_denominator=14025 m:s_hbips_6__of_total=78.45 m:s_peoc_no_count=23 m:s_hie_yes_=38.64 m:s_ehr_non_certified_count=3 m:s_fuh_7_denominator=2977 m:s_ehr_paper_count=26 m:s_imm_2_denominator=7953 m:s_hbips_7_overall_den=19736 m:s_hbips_7_overall__of_total=75.2 m:s_fuh_30_=44.84 m:s_peoc_yes_count=21 m:s_ehr_certified_=34.09 m:s_fuh_30_denominator=2977 m:s_ehr_paper_=59.09 m:s_tob_2a_numerator=2059 m:s_imm_2_=71.6 m:s_tob_2_2a_denominator_1=6721 m:s_tob_2a_=30.64 m:s_tob_2_=46.7 m:s_hbips_2_overall_den=440765 m:s_hcp_denominator=136152 m:s_tob_2_2a_denominator=6721 m:s_fuh_7_numerator=648 m:s_fuh_7_=21.77 m:s_peoc_yes_=47.73 m:s_tob_1_numerator=11593 m:s_hie_no_=61.36

series e:dc76-gh7x d:2015-01-01T00:00:00.000Z t:s_hbips_2_overall_num=844.77 t:s_hcp_measure_description="Healthcare Personnel Influenza Vaccination" t:s_hbips_5_measure_description="Patients discharged on multiple antipsychotic medications with appropriate justification" t:s_hbips_7_measure_description="Post-discharge continuing care plan transmitted to the next level of care provider upon discharge" t:s_peoc_measure_description="Assessment of Patient Experience of Care" t:state=AR t:s_hbips_2_measure_description="Hours of physical-restraint use" t:s_imm_2_measure_description="Influenza Immunization" t:s_fuh_measure_description="Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness" t:s_tob_2_2a_measure_desc="Tobacco Use Treatment (during the hospital stay)" t:s_hbips_3_measure_description="Hours of Seclusion" t:s_hbips_6_measure_description="Post-discharge continuing care plan created" t:s_hie_measure_description="Interoperable health information exchanged with HISP" t:s_ehr_use_measure_description="Highest level typical use of an EHR system" t:s_hbips_5_overall_num=330 t:s_sub_1_measure_description="Alcohol Use Screening" t:s_hbips_6_overall_num=11784 t:s_hbips_7_overall_num=11504 t:s_tob_1_measure_description="Tobacco Use Screening" t:s_hbips_3_overall_num=1654.79 m:s_hie_yes_count=10 m:s_ehr_non_certified_=0 m:s_fuh_30_numerator=1006 m:s_ehr_certified_count=10 m:s_hbips_3_overall_rate_per_1000=0.23 m:s_hcp_numerator=77698 m:s_hbips_2_overall_rate_per_1000=0.12 m:s_sub_1_=86.23 m:s_hbips_5_overall_den=529 m:s_hbips_6_overall_den=12547 m:s_hcp_=85 m:s_imm_2_numerator=4321 m:s_tob_2_numerator=1675 m:s_tob_1_denominator=7623 m:s_sub_1_numerator=6465 m:s_tob_1_=95.95 m:s_peoc_no_=48.39 m:s_hie_no_count=21 m:s_hbips_3_overall_den=295387 m:s_hbips_5__of_total=62.38 m:s_sub_1_denominator=7497 m:s_hbips_6__of_total=93.92 m:s_peoc_no_count=15 m:s_hie_yes_=32.26 m:s_ehr_non_certified_count=0 m:s_fuh_7_denominator=2081 m:s_ehr_paper_count=21 m:s_imm_2_denominator=5953 m:s_hbips_7_overall_den=12519 m:s_hbips_7_overall__of_total=91.89 m:s_fuh_30_=48.34 m:s_peoc_yes_count=16 m:s_ehr_certified_=32.26 m:s_fuh_30_denominator=2081 m:s_ehr_paper_=67.74 m:s_tob_2a_numerator=692 m:s_imm_2_=72.59 m:s_tob_2_2a_denominator_1=2363 m:s_tob_2a_=29.28 m:s_tob_2_=70.88 m:s_hbips_2_overall_den=296387 m:s_hcp_denominator=91639 m:s_tob_2_2a_denominator=2363 m:s_fuh_7_numerator=491 m:s_fuh_7_=23.59 m:s_peoc_yes_=51.61 m:s_tob_1_numerator=7314 m:s_hie_no_=67.74
```

## Meta Commands

```ls
metric m:s_hbips_2_overall_rate_per_1000 p:float l:S_HBIPS-2_Overall_Rate_Per_1000 t:dataTypeName=number

metric m:s_hbips_2_overall_den p:integer l:S_HBIPS-2_Overall_Den t:dataTypeName=number

metric m:s_hbips_3_overall_rate_per_1000 p:float l:S_HBIPS-3_Overall_Rate_Per_1000 t:dataTypeName=number

metric m:s_hbips_3_overall_den p:integer l:S_HBIPS-3_Overall_Den t:dataTypeName=number

metric m:s_hbips_5__of_total p:float l:S_HBIPS-5_%_of_Total t:dataTypeName=number

metric m:s_hbips_5_overall_den p:integer l:S_HBIPS-5_Overall_Den t:dataTypeName=number

metric m:s_hbips_6__of_total p:float l:S_HBIPS-6_%_of_Total t:dataTypeName=number

metric m:s_hbips_6_overall_den p:integer l:S_HBIPS-6_Overall_Den t:dataTypeName=number

metric m:s_hbips_7_overall__of_total p:float l:S_HBIPS-7_Overall_%_of_Total t:dataTypeName=number

metric m:s_hbips_7_overall_den p:integer l:S_HBIPS-7_Overall_Den t:dataTypeName=number

metric m:s_sub_1_ p:float l:S_SUB-1_% t:dataTypeName=number

metric m:s_sub_1_numerator p:integer l:S_SUB-1_Numerator t:dataTypeName=number

metric m:s_sub_1_denominator p:integer l:S_SUB-1_Denominator t:dataTypeName=number

metric m:s_tob_1_ p:float l:S_TOB-1_% t:dataTypeName=number

metric m:s_tob_1_numerator p:integer l:S_TOB-1_Numerator t:dataTypeName=number

metric m:s_tob_1_denominator p:integer l:S_TOB-1_Denominator t:dataTypeName=number

metric m:s_tob_2_ p:float l:S_TOB-2_% t:dataTypeName=number

metric m:s_tob_2_numerator p:integer l:S_TOB-2_Numerator t:dataTypeName=number

metric m:s_tob_2_2a_denominator p:integer l:S_TOB-2/-2a_Denominator t:dataTypeName=number

metric m:s_tob_2a_ p:float l:S_TOB-2a_% t:dataTypeName=number

metric m:s_tob_2a_numerator p:integer l:S_TOB-2a_Numerator t:dataTypeName=number

metric m:s_tob_2_2a_denominator_1 p:integer l:S_TOB-2/-2a__Denominator t:dataTypeName=number

metric m:s_peoc_yes_count p:integer l:S_PEoC_Yes_Count t:dataTypeName=number

metric m:s_peoc_no_count p:integer l:S_PEoC_No_Count t:dataTypeName=number

metric m:s_peoc_yes_ p:float l:S_PEoC_Yes_% t:dataTypeName=number

metric m:s_peoc_no_ p:float l:S_PEoC_No_% t:dataTypeName=number

metric m:s_ehr_paper_count p:integer l:S_EHR_Paper_Count t:dataTypeName=number

metric m:s_ehr_non_certified_count p:integer l:S_EHR_Non-Certified_Count t:dataTypeName=number

metric m:s_ehr_certified_count p:integer l:S_EHR_Certified_Count t:dataTypeName=number

metric m:s_ehr_paper_ p:float l:S_EHR_Paper_% t:dataTypeName=number

metric m:s_ehr_non_certified_ p:float l:S_EHR_Non-Certified_% t:dataTypeName=number

metric m:s_ehr_certified_ p:float l:S_EHR_Certified_% t:dataTypeName=number

metric m:s_hie_yes_count p:integer l:S_HIE_Yes_Count t:dataTypeName=number

metric m:s_hie_no_count p:integer l:S_HIE_No_Count t:dataTypeName=number

metric m:s_hie_yes_ p:float l:S_HIE_Yes_% t:dataTypeName=number

metric m:s_hie_no_ p:float l:S_HIE_No_% t:dataTypeName=number

metric m:s_fuh_30_ p:float l:S_FUH-30_% t:dataTypeName=number

metric m:s_fuh_30_numerator p:integer l:S_FUH-30_Numerator t:dataTypeName=number

metric m:s_fuh_30_denominator p:integer l:S_FUH-30_Denominator t:dataTypeName=number

metric m:s_fuh_7_ p:float l:S_FUH-7_% t:dataTypeName=number

metric m:s_fuh_7_numerator p:integer l:S_FUH-7_Numerator t:dataTypeName=number

metric m:s_fuh_7_denominator p:integer l:S_FUH-7_Denominator t:dataTypeName=number

metric m:s_imm_2_ p:float l:S_IMM-2_% t:dataTypeName=number

metric m:s_imm_2_numerator p:integer l:S_IMM-2_Numerator t:dataTypeName=number

metric m:s_imm_2_denominator p:integer l:S_IMM-2_Denominator t:dataTypeName=number

metric m:s_hcp_ p:integer l:S_HCP_% t:dataTypeName=number

metric m:s_hcp_numerator p:integer l:S_HCP_Numerator t:dataTypeName=number

metric m:s_hcp_denominator p:integer l:S_HCP_Denominator t:dataTypeName=number

entity e:dc76-gh7x l:"Inpatient Psychiatric Facility Quality Measure Data ? by State" t:url=https://data.medicare.gov/api/views/dc76-gh7x

property e:dc76-gh7x t:meta.view v:id=dc76-gh7x v:category="Hospital Compare" v:averageRating=0 v:name="Inpatient Psychiatric Facility Quality Measure Data ? by State"

property e:dc76-gh7x t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:dc76-gh7x t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:dc76-gh7x t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| state | s_hbips_2_measure_description   | s_hbips_2_overall_rate_per_1000 | s_hbips_2_overall_num | s_hbips_2_overall_den | s_hbips_3_measure_description | s_hbips_3_overall_rate_per_1000 | s_hbips_3_overall_num | s_hbips_3_overall_den | s_hbips_5_measure_description                                                            | s_hbips_5__of_total | s_hbips_5_overall_num | s_hbips_5_overall_den | s_hbips_6_measure_description               | s_hbips_6__of_total | s_hbips_6_overall_num | s_hbips_6_overall_den | s_hbips_7_measure_description                                                                     | s_hbips_7_overall__of_total | s_hbips_7_overall_num | s_hbips_7_overall_den | s_sub_1_measure_description | s_sub_1_ | s_sub_1_numerator | s_sub_1_denominator | s_tob_1_measure_description | s_tob_1_ | s_tob_1_numerator | s_tob_1_denominator | s_tob_2_2a_measure_desc                          | s_tob_2_ | s_tob_2_numerator | s_tob_2_2a_denominator | s_tob_2a_ | s_tob_2a_numerator | s_tob_2_2a_denominator_1 | s_peoc_measure_description               | s_peoc_yes_count | s_peoc_no_count | s_peoc_yes_ | s_peoc_no_ | s_ehr_use_measure_description              | s_ehr_paper_count | s_ehr_non_certified_count | s_ehr_certified_count | s_ehr_paper_ | s_ehr_non_certified_ | s_ehr_certified_ | s_hie_measure_description                            | s_hie_yes_count | s_hie_no_count | s_hie_yes_ | s_hie_no_ | start_date          | end_date            | s_fuh_measure_description                                                                                                              | s_fuh_30_ | s_fuh_30_numerator | s_fuh_30_denominator | s_fuh_7_ | s_fuh_7_numerator | s_fuh_7_denominator | s_fuh_measure_start_date | s_fuh_measure_end_date | s_imm_2_measure_description | s_imm_2_ | s_imm_2_numerator | s_imm_2_denominator | s_hcp_measure_description                  | s_hcp_ | s_hcp_numerator | s_hcp_denominator | s_flu_season_start_date | s_flu_season_end_date | 
| ===== | =============================== | =============================== | ===================== | ===================== | ============================= | =============================== | ===================== | ===================== | ======================================================================================== | =================== | ===================== | ===================== | =========================================== | =================== | ===================== | ===================== | ================================================================================================= | =========================== | ===================== | ===================== | =========================== | ======== | ================= | =================== | =========================== | ======== | ================= | =================== | ================================================ | ======== | ================= | ====================== | ========= | ================== | ======================== | ======================================== | ================ | =============== | =========== | ========== | ========================================== | ================= | ========================= | ===================== | ============ | ==================== | ================ | ==================================================== | =============== | ============== | ========== | ========= | =================== | =================== | ====================================================================================================================================== | ========= | ================== | ==================== | ======== | ================= | =================== | ======================== | ====================== | =========================== | ======== | ================= | =================== | ========================================== | ====== | =============== | ================= | ======================= | ===================== | 
| AK    | Hours of physical-restraint use | 1.81                            | 2476.16               | 56880                 | Hours of Seclusion            | 0.79                            | 1083.38               | 56880                 | Patients discharged on multiple antipsychotic medications with appropriate justification | 20.90               | 14                    | 67                    | Post-discharge continuing care plan created | 97.95               | 2296                  | 2344                  | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 88.57                       | 2076                  | 2344                  | Alcohol Use Screening       | 79.39    | 986               | 1242                | Tobacco Use Screening       | 81.88    | 1053              | 1286                | Tobacco Use Treatment Provided or Offered        | 20.33    | 134               | 659                    | 14.11     | 93                 | 659                      | Assessment of Patient Experience of Care | 3                | 0               | 100.00      | 0.00       | Highest level typical use of an EHR system | 2                 | 1                         | 0                     | 66.67        | 33.33                | 0.00             | Interoperable health information exchanged with HISP | 0               | 3              | 0.00       | 100.00    | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 43.65     | 86                 | 197                  | 19.80    | 39                | 197                 | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 72.18    | 807               | 1118                | Healthcare Personnel Influenza Vaccination | 63     | 12075           | 19023             | 10/01/2015              | 03/31/2016            | 
| AL    | Hours of physical-restraint use | 0.27                            | 2891.1                | 440765                | Hours of Seclusion            | 0.16                            | 1700.54               | 440766                | Patients discharged on multiple antipsychotic medications with appropriate justification | 48.90               | 620                   | 1268                  | Post-discharge continuing care plan created | 78.45               | 15482                 | 19734                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 75.20                       | 14842                 | 19736                 | Alcohol Use Screening       | 88.87    | 12464             | 14025               | Tobacco Use Screening       | 82.92    | 11593             | 13981               | Tobacco Use Treatment Provided or Offered        | 46.70    | 3139              | 6721                   | 30.64     | 2059               | 6721                     | Assessment of Patient Experience of Care | 21               | 23              | 47.73       | 52.27      | Highest level typical use of an EHR system | 26                | 3                         | 15                    | 59.09        | 6.82                 | 34.09            | Interoperable health information exchanged with HISP | 17              | 27             | 38.64      | 61.36     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 44.84     | 1335               | 2977                 | 21.77    | 648               | 2977                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 71.60    | 5694              | 7953                | Healthcare Personnel Influenza Vaccination | 76     | 103414          | 136152            | 10/01/2015              | 03/31/2016            | 
| AR    | Hours of physical-restraint use | 0.12                            | 844.77                | 296387                | Hours of Seclusion            | 0.23                            | 1654.79               | 295387                | Patients discharged on multiple antipsychotic medications with appropriate justification | 62.38               | 330                   | 529                   | Post-discharge continuing care plan created | 93.92               | 11784                 | 12547                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 91.89                       | 11504                 | 12519                 | Alcohol Use Screening       | 86.23    | 6465              | 7497                | Tobacco Use Screening       | 95.95    | 7314              | 7623                | Tobacco Use Treatment (during the hospital stay) | 70.88    | 1675              | 2363                   | 29.28     | 692                | 2363                     | Assessment of Patient Experience of Care | 16               | 15              | 51.61       | 48.39      | Highest level typical use of an EHR system | 21                | 0                         | 10                    | 67.74        | 0.00                 | 32.26            | Interoperable health information exchanged with HISP | 10              | 21             | 32.26      | 67.74     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 48.34     | 1006               | 2081                 | 23.59    | 491               | 2081                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 72.59    | 4321              | 5953                | Healthcare Personnel Influenza Vaccination | 85     | 77698           | 91639             | 10/01/2015              | 03/31/2016            | 
| AZ    | Hours of physical-restraint use | 0.44                            | 4981.36               | 476264                | Hours of Seclusion            | 0.25                            | 2855.43               | 476293                | Patients discharged on multiple antipsychotic medications with appropriate justification | 46.81               | 440                   | 940                   | Post-discharge continuing care plan created | 69.75               | 12888                 | 18477                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 67.77                       | 12523                 | 18479                 | Alcohol Use Screening       | 66.08    | 11046             | 16715               | Tobacco Use Screening       | 74.49    | 11966             | 16064               | Tobacco Use Treatment Provided or Offered        | 59.76    | 3229              | 5403                   | 30.35     | 1640               | 5403                     | Assessment of Patient Experience of Care | 23               | 4               | 85.19       | 14.81      | Highest level typical use of an EHR system | 10                | 2                         | 15                    | 37.04        | 7.41                 | 55.56            | Interoperable health information exchanged with HISP | 14              | 13             | 51.85      | 48.15     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 50.09     | 1154               | 2304                 | 32.42    | 747               | 2304                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 54.49    | 5259              | 9651                | Healthcare Personnel Influenza Vaccination | 85     | 139680          | 164426            | 10/01/2015              | 03/31/2016            | 
| CA    | Hours of physical-restraint use | 0.38                            | 18278.66              | 2003041               | Hours of Seclusion            | 0.25                            | 12152.1               | 2003050               | Patients discharged on multiple antipsychotic medications with appropriate justification | 58.29               | 2116                  | 3630                  | Post-discharge continuing care plan created | 84.49               | 48013                 | 56824                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 75.81                       | 43495                 | 57375                 | Alcohol Use Screening       | 77.83    | 37021             | 47567               | Tobacco Use Screening       | 84.93    | 39598             | 46624               | Tobacco Use Treatment (during the hospital stay) | 56.61    | 10581             | 18692                  | 25.68     | 4801               | 18692                    | Assessment of Patient Experience of Care | 66               | 23              | 74.16       | 25.84      | Highest level typical use of an EHR system | 51                | 0                         | 38                    | 57.30        | 0.00                 | 42.70            | Interoperable health information exchanged with HISP | 30              | 59             | 33.71      | 66.29     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 48.67     | 6498               | 13352                | 29.80    | 3979              | 13352               | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 64.27    | 21456             | 33383               | Healthcare Personnel Influenza Vaccination | 82     | 763090          | 929584            | 10/01/2015              | 03/31/2016            | 
| CO    | Hours of physical-restraint use | 0.53                            | 4103.85               | 325641                | Hours of Seclusion            | 1.18                            | 9190.04               | 325641                | Patients discharged on multiple antipsychotic medications with appropriate justification | 61.71               | 311                   | 504                   | Post-discharge continuing care plan created | 81.48               | 7212                  | 8851                  | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 73.25                       | 6483                  | 8851                  | Alcohol Use Screening       | 69.60    | 4263              | 6125                | Tobacco Use Screening       | 93.90    | 5760              | 6134                | Tobacco Use Treatment Provided or Offered        | 43.51    | 1063              | 2443                   | 19.69     | 481                | 2443                     | Assessment of Patient Experience of Care | 14               | 1               | 93.33       | 6.67       | Highest level typical use of an EHR system | 9                 | 2                         | 4                     | 60.00        | 13.33                | 26.67            | Interoperable health information exchanged with HISP | 6               | 9              | 40.00      | 60.00     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 53.58     | 1070               | 1997                 | 31.70    | 633               | 1997                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 62.94    | 2923              | 4644                | Healthcare Personnel Influenza Vaccination | 97     | 148405          | 153185            | 10/01/2015              | 03/31/2016            | 
| CT    | Hours of physical-restraint use | 0.57                            | 6123.8                | 447465                | Hours of Seclusion            | 0.34                            | 3206.93               | 391518                | Patients discharged on multiple antipsychotic medications with appropriate justification | 67.89               | 461                   | 679                   | Post-discharge continuing care plan created | 85.73               | 11938                 | 13925                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 81.30                       | 11321                 | 13925                 | Alcohol Use Screening       | 92.59    | 13227             | 14285               | Tobacco Use Screening       | 95.81    | 13719             | 14319               | Tobacco Use Treatment Provided or Offered        | 68.14    | 4592              | 6739                   | 40.44     | 2725               | 6739                     | Assessment of Patient Experience of Care | 20               | 8               | 71.43       | 28.57      | Highest level typical use of an EHR system | 16                | 1                         | 11                    | 57.14        | 3.57                 | 39.29            | Interoperable health information exchanged with HISP | 11              | 17             | 39.29      | 60.71     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 66.07     | 1990               | 3012                 | 41.90    | 1262              | 3012                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 88.68    | 7748              | 8737                | Healthcare Personnel Influenza Vaccination | 88     | 99595           | 113388            | 10/01/2015              | 03/31/2016            | 
| DC    | Hours of physical-restraint use | 0.09                            | 374.1                 | 167566                | Hours of Seclusion            | 0.09                            | 375.39                | 167566                | Patients discharged on multiple antipsychotic medications with appropriate justification | 55.23               | 132                   | 239                   | Post-discharge continuing care plan created | 74.16               | 2218                  | 2991                  | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 48.78                       | 1459                  | 2991                  | Alcohol Use Screening       | 78.85    | 2233              | 2832                | Tobacco Use Screening       | 84.98    | 2399              | 2823                | Tobacco Use Treatment Provided or Offered        | 23.12    | 255               | 1103                   | 13.24     | 146                | 1103                     | Assessment of Patient Experience of Care | 4                | 3               | 57.14       | 42.86      | Highest level typical use of an EHR system | 6                 | 0                         | 1                     | 85.71        | 0.00                 | 14.29            | Interoperable health information exchanged with HISP | 3               | 4              | 42.86      | 57.14     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 36.50     | 273                | 748                  | 16.71    | 125               | 748                 | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 83.87    | 1732              | 2065                | Healthcare Personnel Influenza Vaccination | 94     | 37532           | 39759             | 10/01/2015              | 03/31/2016            | 
| DE    | Hours of physical-restraint use | 0.03                            | 96.02                 | 124842                | Hours of Seclusion            | 0.04                            | 133.38                | 124842                | Patients discharged on multiple antipsychotic medications with appropriate justification | 68.00               | 136                   | 200                   | Post-discharge continuing care plan created | 98.54               | 4055                  | 4115                  | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 94.82                       | 3902                  | 4115                  | Alcohol Use Screening       | 98.69    | 3002              | 3042                | Tobacco Use Screening       | 95.17    | 2899              | 3046                | Tobacco Use Treatment Provided or Offered        | 91.93    | 1435              | 1561                   | 34.02     | 531                | 1561                     | Assessment of Patient Experience of Care | 5                | 0               | 100.00      | 0.00       | Highest level typical use of an EHR system | 4                 | 0                         | 1                     | 80.00        | 0.00                 | 20.00            | Interoperable health information exchanged with HISP | 2               | 3              | 40.00      | 60.00     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 48.95     | 511                | 1044                 | 30.94    | 323               | 1044                | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 79.07    | 1470              | 1859                | Healthcare Personnel Influenza Vaccination | 89     | 34245           | 38264             | 10/01/2015              | 03/31/2016            | 
| FL    | Hours of physical-restraint use | 0.57                            | 20678.9               | 1518623               | Hours of Seclusion            | 0.13                            | 3078.31               | 1024793               | Patients discharged on multiple antipsychotic medications with appropriate justification | 60.52               | 1136                  | 1877                  | Post-discharge continuing care plan created | 92.08               | 44259                 | 48064                 | Post-discharge continuing care plan transmitted to the next level of care provider upon discharge | 83.02                       | 39812                 | 47952                 | Alcohol Use Screening       | 88.28    | 32542             | 36863               | Tobacco Use Screening       | 93.68    | 34085             | 36384               | Tobacco Use Treatment Provided or Offered        | 70.06    | 11928             | 17026                  | 21.88     | 3725               | 17026                    | Assessment of Patient Experience of Care | 60               | 10              | 85.71       | 14.29      | Highest level typical use of an EHR system | 31                | 1                         | 38                    | 44.29        | 1.43                 | 54.29            | Interoperable health information exchanged with HISP | 44              | 26             | 62.86      | 37.14     | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | Percent of patients receiving follow-up care within 30 days (FUH-30) or within 7 days (FUH-7) after hospitalization for mental illness | 45.38     | 6816               | 15020                | 23.97    | 3600              | 15020               | 07/01/2014               | 06/30/2015             | Influenza Immunization      | 71.61    | 18500             | 25834               | Healthcare Personnel Influenza Vaccination | 76     | 419113          | 552948            | 10/01/2015              | 03/31/2016            | 
```