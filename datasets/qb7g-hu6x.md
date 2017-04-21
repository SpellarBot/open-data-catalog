# Percents of Chronic Conditions among Fee-for-Service Medicare Beneficiaries, Washington State and Counties, 2007-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percents-of-chronic-conditions-among-fee-for-service-medicare-beneficiaries-washingto-2007-74bd4) |
| Metadata | [Link](https://data.wa.gov/api/views/qb7g-hu6x) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qb7g-hu6x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qb7g-hu6x/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qb7g-hu6x |
| Name | Percents of Chronic Conditions among Fee-for-Service Medicare Beneficiaries, Washington State and Counties, 2007-2014 |
| Attribution | Wei Yen, Washington State Office of Financial Management |
| Category | Health |
| Tags | medicare beneficiary chronic conditions |
| Created | 2016-05-12T23:03:31Z |
| Publication Date | 2016-05-12T23:10:26Z |

## Description

(Source: CMS Medicare Chronic Conditions Public Use File, January 2016)

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                                   | Data Type | Render Type |
| ======== | ============== | ================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | county                                             | County                                                 | text      | text        |
| Yes      | numeric metric | to_sort_by_county_and_year                         | (To sort by county and year)                           | number    | text        |
| Yes      | numeric metric | to_sort_by_year_and_county                         | (To sort by year and county)                           | number    | text        |
| Yes      | time           | year                                               | Year                                                   | number    | text        |
| Yes      | series tag     | state_and_county_fips_code                         | State and County FIPS Code                             | text      | text        |
| Yes      | numeric metric | alzheimer_s_disease_dementia_prevalence            | Alzheimer's Disease/Dementia Prevalence (%)            | number    | number      |
| Yes      | numeric metric | arthritis_prevalence                               | Arthritis Prevalence (%)                               | number    | number      |
| Yes      | numeric metric | asthma_prevalence                                  | Asthma Prevalence (%)                                  | number    | number      |
| Yes      | numeric metric | atrial_fibrillation_prevalence                     | Atrial Fibrillation Prevalence (%)                     | number    | number      |
| Yes      | numeric metric | autism_spectrum_disorders_prevalence               | Autism Spectrum Disorders Prevalence (%)               | number    | number      |
| Yes      | numeric metric | copd_prevalence                                    | COPD Prevalence (%)                                    | number    | number      |
| Yes      | numeric metric | cancer_prevalence                                  | Cancer Prevalence (%)                                  | number    | number      |
| Yes      | numeric metric | chronic_kidney_disease_prevalence                  | Chronic Kidney Disease Prevalence (%)                  | number    | number      |
| Yes      | numeric metric | depression_prevalence                              | Depression Prevalence (%)                              | number    | number      |
| Yes      | numeric metric | diabetes_prevalence                                | Diabetes Prevalence (%)                                | number    | number      |
| Yes      | numeric metric | hiv_aids_prevalence                                | HIV/AIDS Prevalence (%)                                | number    | number      |
| Yes      | numeric metric | heart_failure_prevalence                           | Heart Failure Prevalence (%)                           | number    | number      |
| Yes      | numeric metric | hepatitis_chronic_viral_b_c_prevalence             | Hepatitis (Chronic Viral B & C) Prevalence (%)         | number    | number      |
| Yes      | numeric metric | hyperlipidemia_prevalence                          | Hyperlipidemia Prevalence (%)                          | number    | number      |
| Yes      | numeric metric | hypertension_prevalence                            | Hypertension Prevalence (%)                            | number    | number      |
| Yes      | numeric metric | ischemic_heart_disease_prevalence                  | Ischemic Heart Disease Prevalence (%)                  | number    | number      |
| Yes      | numeric metric | osteoporosis_prevalence                            | Osteoporosis Prevalence (%)                            | number    | number      |
| Yes      | numeric metric | schizophrenia_other_psychotic_disorders_prevalence | Schizophrenia/Other Psychotic Disorders Prevalence (%) | number    | number      |
| Yes      | numeric metric | stroke_prevalence                                  | Stroke Prevalence (%)                                  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qb7g-hu6x d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=. t:county="STATE TOTAL" m:chronic_kidney_disease_prevalence=10 m:hiv_aids_prevalence=0.3 m:stroke_prevalence=3.2 m:alzheimer_s_disease_dementia_prevalence=9.1 m:hypertension_prevalence=42.1 m:autism_spectrum_disorders_prevalence=0.1 m:asthma_prevalence=3.5 m:hepatitis_chronic_viral_b_c_prevalence=0.8 m:osteoporosis_prevalence=4.9 m:schizophrenia_other_psychotic_disorders_prevalence=2.9 m:to_sort_by_county_and_year=0.2007 m:depression_prevalence=11.6 m:atrial_fibrillation_prevalence=7.7 m:arthritis_prevalence=20.3 m:cancer_prevalence=7.1 m:copd_prevalence=8.5 m:heart_failure_prevalence=13.6 m:diabetes_prevalence=20.9 m:to_sort_by_year_and_county=2007 m:hyperlipidemia_prevalence=32.5 m:ischemic_heart_disease_prevalence=21.7

series e:qb7g-hu6x d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=53001 t:county=ADAMS m:chronic_kidney_disease_prevalence=10.1 m:stroke_prevalence=2.6 m:alzheimer_s_disease_dementia_prevalence=8.8 m:hypertension_prevalence=47.8 m:autism_spectrum_disorders_prevalence=0 m:asthma_prevalence=3.2 m:osteoporosis_prevalence=4.2 m:schizophrenia_other_psychotic_disorders_prevalence=1.4 m:to_sort_by_county_and_year=530012007 m:depression_prevalence=11.4 m:atrial_fibrillation_prevalence=7.3 m:arthritis_prevalence=21.4 m:cancer_prevalence=6.7 m:copd_prevalence=9.1 m:heart_failure_prevalence=14.8 m:diabetes_prevalence=25.8 m:to_sort_by_year_and_county=200753001 m:hyperlipidemia_prevalence=37.6 m:ischemic_heart_disease_prevalence=26.8

series e:qb7g-hu6x d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=53003 t:county=ASOTIN m:chronic_kidney_disease_prevalence=9.9 m:stroke_prevalence=3.3 m:alzheimer_s_disease_dementia_prevalence=11 m:hypertension_prevalence=43.9 m:autism_spectrum_disorders_prevalence=0 m:asthma_prevalence=3.8 m:hepatitis_chronic_viral_b_c_prevalence=0.4 m:osteoporosis_prevalence=5.6 m:schizophrenia_other_psychotic_disorders_prevalence=2.4 m:to_sort_by_county_and_year=530032007 m:depression_prevalence=10.3 m:atrial_fibrillation_prevalence=8 m:arthritis_prevalence=25 m:cancer_prevalence=8.8 m:copd_prevalence=10.6 m:heart_failure_prevalence=16.2 m:diabetes_prevalence=23.3 m:to_sort_by_year_and_county=200753003 m:hyperlipidemia_prevalence=37.6 m:ischemic_heart_disease_prevalence=27.6
```

## Meta Commands

```ls
metric m:to_sort_by_county_and_year p:integer l:"(To sort by county and year)" t:dataTypeName=number

metric m:to_sort_by_year_and_county p:integer l:"(To sort by year and county)" t:dataTypeName=number

metric m:alzheimer_s_disease_dementia_prevalence p:float l:"Alzheimer's Disease/Dementia Prevalence (%)" t:dataTypeName=number

metric m:arthritis_prevalence p:float l:"Arthritis Prevalence (%)" t:dataTypeName=number

metric m:asthma_prevalence p:float l:"Asthma Prevalence (%)" t:dataTypeName=number

metric m:atrial_fibrillation_prevalence p:float l:"Atrial Fibrillation Prevalence (%)" t:dataTypeName=number

metric m:autism_spectrum_disorders_prevalence p:float l:"Autism Spectrum Disorders Prevalence (%)" t:dataTypeName=number

metric m:copd_prevalence p:float l:"COPD Prevalence (%)" t:dataTypeName=number

metric m:cancer_prevalence p:float l:"Cancer Prevalence (%)" t:dataTypeName=number

metric m:chronic_kidney_disease_prevalence p:float l:"Chronic Kidney Disease Prevalence (%)" t:dataTypeName=number

metric m:depression_prevalence p:float l:"Depression Prevalence (%)" t:dataTypeName=number

metric m:diabetes_prevalence p:float l:"Diabetes Prevalence (%)" t:dataTypeName=number

metric m:hiv_aids_prevalence p:float l:"HIV/AIDS Prevalence (%)" t:dataTypeName=number

metric m:heart_failure_prevalence p:float l:"Heart Failure Prevalence (%)" t:dataTypeName=number

metric m:hepatitis_chronic_viral_b_c_prevalence p:float l:"Hepatitis (Chronic Viral B & C) Prevalence (%)" t:dataTypeName=number

metric m:hyperlipidemia_prevalence p:float l:"Hyperlipidemia Prevalence (%)" t:dataTypeName=number

metric m:hypertension_prevalence p:float l:"Hypertension Prevalence (%)" t:dataTypeName=number

metric m:ischemic_heart_disease_prevalence p:float l:"Ischemic Heart Disease Prevalence (%)" t:dataTypeName=number

metric m:osteoporosis_prevalence p:float l:"Osteoporosis Prevalence (%)" t:dataTypeName=number

metric m:schizophrenia_other_psychotic_disorders_prevalence p:float l:"Schizophrenia/Other Psychotic Disorders Prevalence (%)" t:dataTypeName=number

metric m:stroke_prevalence p:float l:"Stroke Prevalence (%)" t:dataTypeName=number

entity e:qb7g-hu6x l:"Percents of Chronic Conditions among Fee-for-Service Medicare Beneficiaries, Washington State and Counties, 2007-2014" t:attribution="Wei Yen, Washington State Office of Financial Management" t:url=https://data.wa.gov/api/views/qb7g-hu6x

property e:qb7g-hu6x t:meta.view v:id=qb7g-hu6x v:category=Health v:averageRating=0 v:name="Percents of Chronic Conditions among Fee-for-Service Medicare Beneficiaries, Washington State and Counties, 2007-2014" v:attribution="Wei Yen, Washington State Office of Financial Management"

property e:qb7g-hu6x t:meta.view.license v:name="Public Domain"

property e:qb7g-hu6x t:meta.view.owner v:id=8ghr-nmpd v:screenName="Wei Yen" v:displayName="Wei Yen"

property e:qb7g-hu6x t:meta.view.tableauthor v:id=8ghr-nmpd v:screenName="Wei Yen" v:roleName=publisher v:displayName="Wei Yen"
```

## Top Records

```ls
| county      | to_sort_by_county_and_year | to_sort_by_year_and_county | year | state_and_county_fips_code | alzheimer_s_disease_dementia_prevalence | arthritis_prevalence | asthma_prevalence | atrial_fibrillation_prevalence | autism_spectrum_disorders_prevalence | copd_prevalence | cancer_prevalence | chronic_kidney_disease_prevalence | depression_prevalence | diabetes_prevalence | hiv_aids_prevalence | heart_failure_prevalence | hepatitis_chronic_viral_b_c_prevalence | hyperlipidemia_prevalence | hypertension_prevalence | ischemic_heart_disease_prevalence | osteoporosis_prevalence | schizophrenia_other_psychotic_disorders_prevalence | stroke_prevalence | 
| =========== | ========================== | ========================== | ==== | ========================== | ======================================= | ==================== | ================= | ============================== | ==================================== | =============== | ================= | ================================= | ===================== | =================== | =================== | ======================== | ====================================== | ========================= | ======================= | ================================= | ======================= | ================================================== | ================= | 
| STATE TOTAL | 0.2007                     | 2007                       | 2007 | .                          | 9.1                                     | 20.3                 | 3.5               | 7.7                            | 0.1                                  | 8.5             | 7.1               | 10.0                              | 11.6                  | 20.9                | 0.3                 | 13.6                     | 0.8                                    | 32.5                      | 42.1                    | 21.7                              | 4.9                     | 2.9                                                | 3.2               | 
| ADAMS       | 530012007                  | 200753001                  | 2007 | 53001                      | 8.8                                     | 21.4                 | 3.2               | 7.3                            | 0.0                                  | 9.1             | 6.7               | 10.1                              | 11.4                  | 25.8                |                     | 14.8                     |                                        | 37.6                      | 47.8                    | 26.8                              | 4.2                     | 1.4                                                | 2.6               | 
| ASOTIN      | 530032007                  | 200753003                  | 2007 | 53003                      | 11.0                                    | 25.0                 | 3.8               | 8.0                            | 0.0                                  | 10.6            | 8.8               | 9.9                               | 10.3                  | 23.3                |                     | 16.2                     | 0.4                                    | 37.6                      | 43.9                    | 27.6                              | 5.6                     | 2.4                                                | 3.3               | 
| BENTON      | 530052007                  | 200753005                  | 2007 | 53005                      | 10.5                                    | 22.7                 | 4.2               | 6.9                            |                                      | 10.1            | 7.9               | 9.5                               | 11.4                  | 24.9                | 0.1                 | 13.2                     | 0.6                                    | 41.9                      | 46.8                    | 26.9                              | 5.7                     | 2.4                                                | 4.4               | 
| CHELAN      | 530072007                  | 200753007                  | 2007 | 53007                      | 8.6                                     | 19.9                 | 3.0               | 8.4                            |                                      | 7.7             | 7.2               | 8.9                               | 12.3                  | 19.3                |                     | 10.9                     | 0.6                                    | 32.3                      | 40.4                    | 19.0                              | 3.9                     | 1.9                                                | 3.1               | 
| CLALLAM     | 530092007                  | 200753009                  | 2007 | 53009                      | 7.5                                     | 24.3                 | 3.5               | 8.0                            |                                      | 8.2             | 6.9               | 6.4                               | 9.3                   | 19.1                | 0.1                 | 12.5                     | 0.7                                    | 32.1                      | 40.2                    | 21.4                              | 5.4                     | 2.3                                                | 3.0               | 
| CLARK       | 530112007                  | 200753011                  | 2007 | 53011                      | 9.1                                     | 16.4                 | 3.8               | 7.3                            | 0.1                                  | 8.5             | 6.2               | 10.4                              | 12.7                  | 20.9                | 0.2                 | 13.5                     | 0.7                                    | 27.9                      | 39.1                    | 19.6                              | 3.6                     | 3.4                                                | 3.3               | 
| COLUMBIA    | 530132007                  | 200753013                  | 2007 | 53013                      | 8.5                                     | 19.9                 | 4.0               | 5.9                            | 0.0                                  | 12.1            | 7.9               | 9.2                               | 12.2                  | 23.3                |                     | 16.7                     | 0.0                                    | 32.5                      | 43.0                    | 27.8                              | 3.7                     | 3.8                                                | 2.7               | 
| COWLITZ     | 530152007                  | 200753015                  | 2007 | 53015                      | 8.8                                     | 20.6                 | 4.7               | 8.5                            |                                      | 12.5            | 6.3               | 11.7                              | 13.9                  | 22.7                | 0.3                 | 16.7                     | 0.6                                    | 31.9                      | 43.3                    | 22.5                              | 4.6                     | 4.0                                                | 3.1               | 
| DOUGLAS     | 530172007                  | 200753017                  | 2007 | 53017                      | 10.1                                    | 23.5                 | 2.7               | 8.9                            | 0.0                                  | 9.4             | 8.4               | 10.0                              | 14.4                  | 20.8                |                     | 13.2                     | 0.4                                    | 36.6                      | 44.1                    | 21.0                              | 4.8                     | 2.3                                                | 3.5               | 
```