# 2015 Complex SSI Table for All Reportable Surgical Procedures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-complex-ssi-table-for-all-reportable-surgical-procedures) |
| Metadata | [Link](https://data.oregon.gov/api/views/95xd-7hgm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/95xd-7hgm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/95xd-7hgm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 95xd-7hgm |
| Name | 2015 Complex SSI Table for All Reportable Surgical Procedures |
| Category | Health & Human Services |
| Tags | 2015 hai report |
| Created | 2016-06-25T13:41:54Z |
| Publication Date | 2016-09-23T20:12:36Z |

## Description

In 2015, Oregon hospitals reported surgical site infections for CBGB, COLO, HYST, HPRO, KPRO, and LAM procedures. This table contains only "complex" infections, defined as deep incisional/organ space infections. Superficial infections are not reported because of inconsistency in reporting.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| Yes      | series tag     | hospital_name                                | Hospital Name                                | text      | text        |
| Yes      | numeric metric | procedure_name                               | Procedure Name                               | number    | number      |
| Yes      | series tag     | procedure_type                               | Procedure Type                               | text      | text        |
| Yes      | numeric metric | complex_ssis                                 | Complex SSIs                                 | number    | number      |
| Yes      | numeric metric | predicted_ssis                               | Predicted SSIs                               | number    | number      |
| Yes      | numeric metric | sir                                          | SIR                                          | number    | number      |
| Yes      | series tag     | sir_95_ci                                    | SIR 95% CI                                   | text      | text        |
| Yes      | series tag     | sir_icon                                     | SIR Icon                                     | photo     | photo       |
| Yes      | series tag     | sir_interpretation_2006_08_us_baseline       | SIR Interpretation (2006-08 US baseline)     | text      | text        |
| Yes      | series tag     | 2013_hhs_targets                             | 2013 HHS Targets                             | text      | text        |
| Yes      | series tag     | benchmark_icons                              | Benchmark Icon                               | photo     | photo       |
| Yes      | series tag     | percentile_on_2014_national_sir_distribution | Percentile on 2014 National SIR Distribution | text      | text        |
| Yes      | series tag     | county                                       | County                                       | text      | text        |
| Yes      | series tag     | hpp_region                                   | HPP Region                                   | text      | text        |
| No       |                | location                                     | Location                                     | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = location
```

## Data Commands

```ls
series e:95xd-7hgm d:2015-01-01T00:00:00.000Z t:hospital_name="Adventist Medical Center" t:hpp_region=Region1 t:county=MULTNOMAH t:procedure_type=HYST t:sir_interpretation_2006_08_us_baseline="#s too small to calculate" m:procedure_name=111 m:complex_ssis=1 m:predicted_ssis=0.86

series e:95xd-7hgm d:2015-01-01T00:00:00.000Z t:hospital_name="Asante Rogue Regional Medical Center" t:hpp_region=Region5 t:county=JACKSON t:procedure_type=HYST t:sir_interpretation_2006_08_us_baseline="#s too small to calculate" m:procedure_name=95 m:complex_ssis=1 m:predicted_ssis=0.58

series e:95xd-7hgm d:2015-01-01T00:00:00.000Z t:hospital_name="Asante Three Rivers Medical Center" t:hpp_region=Region5 t:county=JOSEPHINE t:procedure_type=HPRO t:sir_interpretation_2006_08_us_baseline="#s too small to calculate" m:procedure_name=116 m:complex_ssis=2 m:predicted_ssis=0.84
```

## Meta Commands

```ls
metric m:procedure_name p:integer l:"Procedure Name" t:dataTypeName=number

metric m:complex_ssis p:integer l:"Complex SSIs" t:dataTypeName=number

metric m:predicted_ssis p:double l:"Predicted SSIs" t:dataTypeName=number

metric m:sir p:float l:SIR t:dataTypeName=number

entity e:95xd-7hgm l:"2015 Complex SSI Table for All Reportable Surgical Procedures" t:url=https://data.oregon.gov/api/views/95xd-7hgm

property e:95xd-7hgm t:meta.view v:id=95xd-7hgm v:category="Health & Human Services" v:averageRating=0 v:name="2015 Complex SSI Table for All Reportable Surgical Procedures"

property e:95xd-7hgm t:meta.view.owner v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:displayName="Kate Ellingson"

property e:95xd-7hgm t:meta.view.tableauthor v:id=i3hy-atyi v:profileImageUrlMedium=/api/users/i3hy-atyi/profile_images/THUMB v:profileImageUrlLarge=/api/users/i3hy-atyi/profile_images/LARGE v:screenName="Kate Ellingson" v:profileImageUrlSmall=/api/users/i3hy-atyi/profile_images/TINY v:roleName=editor v:displayName="Kate Ellingson"
```

## Top Records

```ls
| hospital_name                        | procedure_name | procedure_type | complex_ssis | predicted_ssis | sir | sir_95_ci | sir_icon | sir_interpretation_2006_08_us_baseline | 2013_hhs_targets | benchmark_icons                      | percentile_on_2014_national_sir_distribution | county    | hpp_region | location                   | 
| ==================================== | ============== | ============== | ============ | ============== | === | ========= | ======== | ====================================== | ================ | ==================================== | ============================================ | ========= | ========== | ========================== | 
| Adventist Medical Center             | 111            | HYST           | 1            | 0.86           |     |           |          | #s too small to calculate              |                  |                                      |                                              | MULTNOMAH | Region1    | (45.512666, -122.5585885)  | 
| Asante Rogue Regional Medical Center | 95             | HYST           | 1            | 0.58           |     |           |          | #s too small to calculate              |                  |                                      |                                              | JACKSON   | Region5    | (42.3174104, -122.8302961) | 
| Asante Three Rivers Medical Center   | 116            | HPRO           | 2            | 0.84           |     |           |          | #s too small to calculate              |                  |                                      |                                              | JOSEPHINE | Region5    | (42.4212882, -123.3428747) | 
| Adventist Medical Center             | 306            | LAM            | 0            | 0.9            |     |           |          | #s too small to calculate              | ZERO Infections  | 8db6ab3d-1295-481d-b723-acd7b00a0b2f |                                              | MULTNOMAH | Region1    | (45.512666, -122.5585885)  | 
| Asante Three Rivers Medical Center   | 14             | HYST           | 0            | 0.17           |     |           |          | #s too small to calculate              | ZERO Infections  | cec2cee5-94a2-4877-af4f-703179654c89 |                                              | JOSEPHINE | Region5    | (42.4212882, -123.3428747) | 
| Adventist Medical Center             | 57             | CBGB           | 0            | 0.83           |     |           |          | #s too small to calculate              | ZERO Infections  | 700ac9a8-cf99-4162-94ed-f63e6936a8c6 |                                              | MULTNOMAH | Region1    | (45.512666, -122.5585885)  | 
| Ashland Community Hospital           | 13             | COLO           | 0            | 0.36           |     |           |          | #s too small to calculate              | ZERO Infections  | 5dab61f6-382b-462a-86f2-f665eb4934ca |                                              | JACKSON   | Region5    | (42.2057909, -122.7247932) | 
| Ashland Community Hospital           | 44             | HPRO           | 0            | 0.25           |     |           |          | #s too small to calculate              | ZERO Infections  | 5b4aa8fe-a84d-4c89-875c-223dcc9db8a3 |                                              | JACKSON   | Region5    | (42.2057909, -122.7247932) | 
| Ashland Community Hospital           | 5              | HYST           | 0            | 0.02           |     |           |          | #s too small to calculate              | ZERO Infections  | e043b47e-6758-4375-8051-375b71c0cf87 |                                              | JACKSON   | Region5    | (42.2057909, -122.7247932) | 
| Ashland Community Hospital           | 76             | KPRO           | 0            | 0.33           |     |           |          | #s too small to calculate              | ZERO Infections  | 8a4dcd8e-f981-4524-939c-2636511ec19f |                                              | JACKSON   | Region5    | (42.2057909, -122.7247932) | 
```