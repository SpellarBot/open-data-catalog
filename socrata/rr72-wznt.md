# 2015 Methicillin-resistant Staphylococcus aureus (MRSA) bloodstream Events Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-methicillin-resistant-staphylococcus-aureus-mrsa-bloodstream-events-table) |
| Metadata | [Link](https://data.oregon.gov/api/views/rr72-wznt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rr72-wznt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rr72-wznt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rr72-wznt |
| Name | 2015 Methicillin-resistant Staphylococcus aureus (MRSA) bloodstream Events Table |
| Attribution | Oregon HAI Program |
| Category | Health & Human Services |
| Tags | 2015 hai report |
| Created | 2016-06-25T12:50:04Z |
| Publication Date | 2016-09-23T19:39:52Z |

## Description

Hospitals in Oregon report facility-wide Methicillin-resistant Staphylococcus aureus (MRSA) bloodstream LabID events as part of the mandatory reporting program. Hospital-onset MRSA bloodstream infections are reported in this table.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | series tag     | hospital_name                                | Hospital Name                                | text      | text        |
| Yes      | numeric metric | patient_days                                 | Patient Days                                 | number    | number      |
| Yes      | numeric metric | observed_infections                          | Observed Infections                          | number    | number      |
| Yes      | numeric metric | predicted_infections                         | Predicted Infections                         | number    | number      |
| Yes      | series tag     | 2015_sir                                     | 2015 SIR                                     | text      | text        |
| Yes      | series tag     | sir_95_ci                                    | SIR 95% CI                                   | text      | text        |
| Yes      | series tag     | sir_icon                                     | SIR Icon                                     | photo     | photo       |
| Yes      | series tag     | sir_interpretation_2010_11_us_baseline       | SIR Interpretation (2010-11 US baseline)     | text      | text        |
| Yes      | series tag     | 2013_hhs_targets                             | 2013 HHS Targets                             | text      | text        |
| Yes      | series tag     | benchmark_icon                               | Benchmark Icon                               | photo     | photo       |
| Yes      | series tag     | percentile_on_2014_national_sir_distribution | Percentile on 2014 National SIR Distribution | text      | text        |
| Yes      | series tag     | county                                       | County                                       | text      | text        |
| Yes      | series tag     | hpp_region                                   | HPP Region                                   | text      | text        |
| Yes      | series tag     | none                                         | (none)                                       | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rr72-wznt d:2015-01-01T00:00:00.000Z t:hospital_name="Peace Harbor Hospital" t:hpp_region=Region3 t:county=LANE t:none=(43.973100 t:2015_sir=* t:sir_interpretation_2010_11_us_baseline="#s too small to calculate" t:sir_95_ci=* m:observed_infections=1 m:patient_days=3729 m:predicted_infections=0.16

series e:rr72-wznt d:2015-01-01T00:00:00.000Z t:hospital_name="Willamette Valley Medical Center" t:hpp_region=Region2 t:county=YAMHILL t:2013_hhs_targets="ZERO Infections" t:benchmark_icon=97af772f-e586-4aee-aff6-fc406e6aae16 t:none=(45.199000 t:2015_sir=* t:sir_interpretation_2010_11_us_baseline="#s too small to calculate" t:sir_95_ci=* m:observed_infections=0 m:patient_days=13321 m:predicted_infections=0.86

series e:rr72-wznt d:2015-01-01T00:00:00.000Z t:percentile_on_2014_national_sir_distribution=0-15% t:hospital_name="Adventist Medical Center" t:hpp_region=Region1 t:county=MULTNOMAH t:2013_hhs_targets="SIR Target (<0.75) Met & ZERO Infections" t:benchmark_icon=e980d961-0568-4fb8-bcfc-e22452ccd8c3 t:none=(45.512666 t:2015_sir=0 t:sir_interpretation_2010_11_us_baseline="Fewer infections" t:sir_95_ci=", 1.504" t:sir_icon=363c3262-efc7-4a8d-980b-98ccd72f9275 m:observed_infections=0 m:patient_days=32124 m:predicted_infections=1.99
```

## Meta Commands

```ls
metric m:patient_days p:integer l:"Patient Days" t:dataTypeName=number

metric m:observed_infections p:integer l:"Observed Infections" t:dataTypeName=number

metric m:predicted_infections p:float l:"Predicted Infections" t:dataTypeName=number

entity e:rr72-wznt l:"2015  Methicillin-resistant Staphylococcus aureus (MRSA) bloodstream Events Table" t:attribution="Oregon HAI Program" t:url=https://data.oregon.gov/api/views/rr72-wznt

property e:rr72-wznt t:meta.view v:id=rr72-wznt v:category="Health & Human Services" v:averageRating=0 v:name="2015  Methicillin-resistant Staphylococcus aureus (MRSA) bloodstream Events Table" v:attribution="Oregon HAI Program"

property e:rr72-wznt t:meta.view.owner v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:displayName="Kate Ellingson"

property e:rr72-wznt t:meta.view.tableauthor v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:roleName=editor v:displayName="Kate Ellingson"
```

## Top Records

```ls
| hospital_name                             | patient_days | observed_infections | predicted_infections | 2015_sir | sir_95_ci    | sir_icon                             | sir_interpretation_2010_11_us_baseline | 2013_hhs_targets                         | benchmark_icon                       | percentile_on_2014_national_sir_distribution | county     | hpp_region | none       | 
| ========================================= | ============ | =================== | ==================== | ======== | ============ | ==================================== | ====================================== | ======================================== | ==================================== | ============================================ | ========== | ========== | ========== | 
| Peace Harbor Hospital                     | 3729         | 1                   | 0.16                 | *        | *            |                                      | #s too small to calculate              |                                          |                                      |                                              | LANE       | Region3    | (43.973100 | 
| Willamette Valley Medical Center          | 13321        | 0                   | 0.86                 | *        | *            |                                      | #s too small to calculate              | ZERO Infections                          | 97af772f-e586-4aee-aff6-fc406e6aae16 |                                              | YAMHILL    | Region2    | (45.199000 | 
| Adventist Medical Center                  | 32124        | 0                   | 1.99                 | 0        | , 1.504      | 363c3262-efc7-4a8d-980b-98ccd72f9275 | Fewer infections                       | SIR Target (<0.75) Met & ZERO Infections | e980d961-0568-4fb8-bcfc-e22452ccd8c3 | 0-15%                                        | MULTNOMAH  | Region1    | (45.512666 | 
| Kaiser Permanente Westside Medical Center | 25842        | 1                   | 1.05                 | 0.949    | 0.047, 4.680 | 477debbc-bcc7-44f9-8c72-dc6c347252b7 | Fewer infections                       | Target Not Met                           |                                      | 61-65%                                       | WASHINGTON | Region1    | (45.539113 | 
| Asante Rogue Regional Medical Center      | 76888        | 8                   | 3.05                 | 2.622    | 1.218, 4.978 | 6e1565e7-55e5-4431-9492-a56709ffd4a5 | Statistically more infections          | Target Not Met                           |                                      | 96-100%                                      | JACKSON    | Region5    | (42.317410 | 
| Legacy Mount Hood Medical Center          | 26099        | 1                   | 1.03                 | 0.968    | 0.048, 4.774 | dcfbf2ee-ba0c-4761-8dd4-b630c50db8f4 | Fewer infections                       | Target Not Met                           |                                      | 61-65%                                       | MULTNOMAH  | Region1    | (45.516626 | 
| Legacy Good Samaritan Medical Center      | 41365        | 3                   | 2.21                 | 1.356    | 0.345, 3.691 | 29168b06-285f-4e32-a1fe-0eb8c98257b6 | More infections                        | Target Not Met                           |                                      | 76-80%                                       | MULTNOMAH  | Region1    | (45.530221 | 
| Mercy Medical Center                      | 30224        | 0                   | 1.71                 | 0        | , 1.755      | 3909683d-3496-4680-97ba-28d07cca395a | Fewer infections                       | SIR Target (<0.75) Met & ZERO Infections | a60f78a2-cdbd-4933-ae84-643e5dac0fb2 | 0-15%                                        | DOUGLAS    | Region3    | (43.241453 | 
| Asante Three Rivers Medical Center        | 29020        | 0                   | 1.07                 | 0        | , 2.798      | 83eddaf9-6465-465c-8477-75f38cd16180 | Fewer infections                       | SIR Target (<0.75) Met & ZERO Infections | 1cb14138-2bb5-4312-9aab-bd779ad7e9dd | 0-15%                                        | JOSEPHINE  | Region5    | (42.421288 | 
| Sacred Heart Medical Center - Riverbend   | 118240       | 5                   | 5.83                 | 0.858    | 0.314, 1.901 | c183486f-f199-4fbc-92c5-7ad02ac7920e | Fewer infections                       | Target Not Met                           |                                      | 51-55%                                       | LANE       | Region3    | (44.080908 | 
```