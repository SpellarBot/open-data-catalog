# 2015 Central Line-Associated Bloodstream Infections (CLABSI) Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-central-line-associated-bloodstream-infections-clabsi-table) |
| Metadata | [Link](https://data.oregon.gov/api/views/4arj-uxbw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/4arj-uxbw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/4arj-uxbw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 4arj-uxbw |
| Name | 2015 Central Line-Associated Bloodstream Infections (CLABSI) Table |
| Attribution | Oregon Healthcare-Associated Infections Program |
| Category | Health & Human Services |
| Tags | 2015 hai report |
| Created | 2016-06-24T19:17:15Z |
| Publication Date | 2016-09-23T20:11:17Z |

## Description

Oregon hospitals report CLABSIs from all adult and pediatric ICUs, NICUs, and adult and pediatric medical, surgical, and medical/surgical wards as part of Oregon's mandatory healthcare-associated infections reporting program.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | series tag     | hospital_name                                | Hospital Name                                | text      | text        |
| Yes      | series tag     | hospital_location                            | Hospital Location                            | text      | text        |
| Yes      | numeric metric | central_line_days                            | Central Line Days                            | number    | number      |
| Yes      | numeric metric | observed_infections                          | Observed Infections                          | number    | number      |
| Yes      | numeric metric | predicted_infections                         | Predicted Infections                         | number    | number      |
| Yes      | numeric metric | 2015_sir                                     | 2015 SIR                                     | number    | text        |
| Yes      | series tag     | sir_95_ci                                    | SIR 95% CI                                   | text      | text        |
| Yes      | series tag     | sir_interpretation_2006_08_us_baseline       | SIR Interpretation (2006-08 US baseline)     | text      | text        |
| Yes      | series tag     | sir_icon                                     | SIR Icon                                     | photo     | photo       |
| Yes      | series tag     | 2013_hhs_targets                             | 2013 HHS Targets                             | text      | text        |
| Yes      | series tag     | benchmark_icon                               | Benchmark Icon                               | photo     | photo       |
| Yes      | series tag     | percentile_on_2014_national_sir_distribution | Percentile on 2014 National SIR Distribution | text      | text        |
| Yes      | series tag     | county                                       | County                                       | text      | text        |
| Yes      | series tag     | hpp_region                                   | HPP Region                                   | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4arj-uxbw d:2015-01-01T00:00:00.000Z t:percentile_on_2014_national_sir_distribution=71-75% t:hospital_name="1. All Oregon" t:2013_hhs_targets="Target Not Met" t:hospital_location="All Neonatal ICUs Combined*" t:sir_95_ci="0.405, 1.272" t:sir_interpretation_2006_08_us_baseline="Fewer infections" t:sir_icon=e0e40dd5-b42e-4307-9694-036e3de5e97b m:observed_infections=12 m:central_line_days=7622 m:2015_sir=0.748 m:predicted_infections=16.04

series e:4arj-uxbw d:2015-01-01T00:00:00.000Z t:percentile_on_2014_national_sir_distribution=51-55% t:hospital_name="1. All Oregon" t:2013_hhs_targets="SIR Target (<0.5) Met" t:hospital_location="Pediatric Medical/Surgical ICUs" t:benchmark_icon=66774521-f9b0-44d9-a51a-38a456fe8eb1 t:sir_95_ci="0.138, 0.834" t:sir_interpretation_2006_08_us_baseline="Statistically fewer infections" t:sir_icon=b4c19d36-b11f-4e7e-9b8f-26700befc155 m:observed_infections=5 m:central_line_days=4431 m:2015_sir=0.376 m:predicted_infections=13.29

series e:4arj-uxbw d:2015-01-01T00:00:00.000Z t:percentile_on_2014_national_sir_distribution=46-50% t:hospital_name="1. All Oregon" t:2013_hhs_targets="SIR Target (<0.5) Met" t:hospital_location="Adult Medical/Surgical ICUs" t:benchmark_icon=7e92188a-06c4-4bf9-9b61-6322e49e7530 t:sir_95_ci="0.227, 0.492" t:sir_interpretation_2006_08_us_baseline="Statistically fewer infections" t:sir_icon=a2e1da10-7875-4022-a182-50db6c84f0b8 m:observed_infections=26 m:central_line_days=45068 m:2015_sir=0.341 m:predicted_infections=76.28
```

## Meta Commands

```ls
metric m:central_line_days p:integer l:"Central Line Days" t:dataTypeName=number

metric m:observed_infections p:integer l:"Observed Infections" t:dataTypeName=number

metric m:predicted_infections p:float l:"Predicted Infections" t:dataTypeName=number

entity e:4arj-uxbw l:"2015 Central Line-Associated Bloodstream Infections (CLABSI) Table" t:attribution="Oregon Healthcare-Associated Infections Program" t:url=https://data.oregon.gov/api/views/4arj-uxbw

property e:4arj-uxbw t:meta.view v:id=4arj-uxbw v:category="Health & Human Services" v:attributionLink=http://healthoregon.org/hai-reports v:averageRating=0 v:name="2015 Central Line-Associated Bloodstream Infections (CLABSI) Table" v:attribution="Oregon Healthcare-Associated Infections Program"

property e:4arj-uxbw t:meta.view.owner v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:displayName="Kate Ellingson"

property e:4arj-uxbw t:meta.view.tableauthor v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:roleName=editor v:displayName="Kate Ellingson"
```

## Top Records

```ls
| hospital_name                        | hospital_location                           | central_line_days | observed_infections | predicted_infections | 2015_sir | sir_95_ci    | sir_interpretation_2006_08_us_baseline | sir_icon                             | 2013_hhs_targets      | benchmark_icon                       | percentile_on_2014_national_sir_distribution | county  | hpp_region | 
| ==================================== | =========================================== | ================= | =================== | ==================== | ======== | ============ | ====================================== | ==================================== | ===================== | ==================================== | ============================================ | ======= | ========== | 
| 1. All Oregon                        | All Neonatal ICUs Combined*                 | 7622              | 12                  | 16.04                | 0.748    | 0.405, 1.272 | Fewer infections                       | e0e40dd5-b42e-4307-9694-036e3de5e97b | Target Not Met        |                                      | 71-75%                                       |         |            | 
| 1. All Oregon                        | Pediatric Medical/Surgical ICUs             | 4431              | 5                   | 13.29                | 0.376    | 0.138, 0.834 | Statistically fewer infections         | b4c19d36-b11f-4e7e-9b8f-26700befc155 | SIR Target (<0.5) Met | 66774521-f9b0-44d9-a51a-38a456fe8eb1 | 51-55%                                       |         |            | 
| 1. All Oregon                        | Adult Medical/Surgical ICUs                 | 45068             | 26                  | 76.28                | 0.341    | 0.227, 0.492 | Statistically fewer infections         | a2e1da10-7875-4022-a182-50db6c84f0b8 | SIR Target (<0.5) Met | 7e92188a-06c4-4bf9-9b61-6322e49e7530 | 46-50%                                       |         |            | 
| 1. All Oregon                        | Adult Medical ICUs                          | 4850              | 4                   | 11.08                | 0.361    | 0.115, 0.871 | Statistically fewer infections         | 030d8ace-2ccd-41d4-bebe-ed67295f6a87 | SIR Target (<0.5) Met | 533350bb-07ad-4854-aeac-6e0b8eda3037 | 51-55%                                       |         |            | 
| 1. All Oregon                        | Adult Cardiothoracic ICUs                   | 8466              | 5                   | 11.85                | 0.422    | 0.155, 0.935 | Statistically fewer infections         | 218e4d6f-3c28-4913-9a1a-4504cfa56826 | SIR Target (<0.5) Met | eaf8588d-7983-4751-9adf-2582100563ce | 56-60%                                       |         |            | 
| Asante Rogue Regional Medical Center | All Neonatal ICUs Combined*                 | 309               | 1                   | 0.64                 | *        | *            | #s too small to calculate              |                                      |                       |                                      | *                                            | JACKSON | Region5    | 
| Asante Rogue Regional Medical Center | NICU Level II/III                           | 309               | 1                   | 0.64                 | *        | *            | #s too small to calculate              |                                      |                       |                                      | *                                            | JACKSON | Region5    | 
| Ashland Community Hospital           | All Adult/Ped ICUs & M/S/MS Wards Combined* | 230               | 1                   | 0.29                 | *        | *            | #s too small to calculate              |                                      |                       |                                      | *                                            | JACKSON | Region5    | 
| Ashland Community Hospital           | Adult Medical/Surgical Wards                | 187               | 1                   | 0.22                 | *        | *            | #s too small to calculate              |                                      |                       |                                      | *                                            | JACKSON | Region5    | 
| Bay Area Hospital                    | Adult Surgical Wards                        | 675               | 1                   | 0.95                 | *        | *            | #s too small to calculate              |                                      |                       |                                      | *                                            | COOS    | Region3    | 
```