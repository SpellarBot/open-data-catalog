# 2014 CDI Example By HPP Region

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-cdi-example-by-hpp-region) |
| Metadata | [Link](https://data.oregon.gov/api/views/e6dv-uvan) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/e6dv-uvan/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/e6dv-uvan/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | e6dv-uvan |
| Name | 2014 CDI Example By HPP Region |
| Tags | 2014 hai |
| Created | 2016-07-14T22:37:54Z |
| Publication Date | 2016-07-26T23:55:48Z |

## Description

Example dataset for HAI data by HPP Region-2014 data

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                               | Data Type | Render Type |
| ======== | ============== | ================================================== | ================================================== | ========= | =========== |
| Yes      | series tag     | hospital_name                                      | Hospital Name                                      | text      | text        |
| Yes      | numeric metric | patient_days                                       | Patient Days                                       | number    | number      |
| Yes      | numeric metric | observed_infections                                | Observed Infections                                | number    | number      |
| Yes      | numeric metric | predicted_infections                               | Predicted Infections                               | number    | number      |
| Yes      | numeric metric | 2014_sir                                           | 2014 SIR                                           | number    | number      |
| Yes      | series tag     | sir_95_ci                                          | SIR 95% CI                                         | text      | text        |
| Yes      | series tag     | sir_interpretation_2010_11_us_baseline             | SIR Interpretation (2010-11 US baseline)           | text      | text        |
| Yes      | series tag     | sir_icon                                           | SIR Icon                                           | photo     | photo       |
| Yes      | series tag     | 2013_hhs_targets                                   | 2013 HHS Targets                                   | text      | text        |
| Yes      | series tag     | percentile_range_on_2013_national_sir_distribution | Percentile range on 2013 National SIR Distribution | text      | text        |
| Yes      | series tag     | county                                             | County                                             | text      | text        |
| Yes      | series tag     | hpp_region                                         | HPP Region                                         | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e6dv-uvan d:2014-01-01T00:00:00.000Z t:hospital_name="West Valley Hospital" t:hpp_region=Region2 t:county=POLK t:2013_hhs_targets="ZERO Infections" t:sir_interpretation_2010_11_us_baseline="#s too small to calculate" t:sir_95_ci=* m:observed_infections=0 m:patient_days=457 m:predicted_infections=0.25

series e:e6dv-uvan d:2014-01-01T00:00:00.000Z t:hospital_name="ALL REGION 2" t:percentile_range_on_2013_national_sir_distribution=26-50th t:hpp_region=Region2 t:2013_hhs_targets="SIR Target (<0.7) Met" t:sir_interpretation_2010_11_us_baseline="Statistically fewer infections" t:sir_95_ci="0.530, 0.811" t:sir_icon=4bb41a90-9061-4e3e-b7c6-d904a16262ad m:observed_infections=85 m:patient_days=190091 m:predicted_infections=128.98 m:2014_sir=0.66

series e:e6dv-uvan d:2014-01-01T00:00:00.000Z t:hospital_name="Blue Mountain Hospital" t:hpp_region=Region7 t:county=GRANT t:2013_hhs_targets="ZERO Infections" t:sir_interpretation_2010_11_us_baseline="#s too small to calculate" t:sir_95_ci=* m:observed_infections=0 m:patient_days=596 m:predicted_infections=0.26
```

## Meta Commands

```ls
metric m:patient_days p:integer l:"Patient Days" t:dataTypeName=number

metric m:observed_infections p:integer l:"Observed Infections" t:dataTypeName=number

metric m:predicted_infections p:float l:"Predicted Infections" t:dataTypeName=number

metric m:2014_sir p:float l:"2014 SIR" t:dataTypeName=number

entity e:e6dv-uvan l:"2014 CDI Example By HPP Region" t:url=https://data.oregon.gov/api/views/e6dv-uvan

property e:e6dv-uvan t:meta.view v:id=e6dv-uvan v:averageRating=0 v:name="2014 CDI Example By HPP Region"

property e:e6dv-uvan t:meta.view.owner v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:displayName="Lisa Takeuchi"

property e:e6dv-uvan t:meta.view.tableauthor v:id=jsgg-5kv8 v:screenName="Lisa Takeuchi" v:roleName=editor v:displayName="Lisa Takeuchi"
```

## Top Records

```ls
| hospital_name                              | patient_days | observed_infections | predicted_infections | 2014_sir | sir_95_ci    | sir_interpretation_2010_11_us_baseline                                                                          | sir_icon                             | 2013_hhs_targets      | percentile_range_on_2013_national_sir_distribution | county     | hpp_region | 
| ========================================== | ============ | =================== | ==================== | ======== | ============ | =============================================================================================================== | ==================================== | ===================== | ================================================== | ========== | ========== | 
| West Valley Hospital                       | 457          | 0                   | 0.25                 |          | *            | #s too small to calculate                                                                                       |                                      | ZERO Infections       |                                                    | POLK       | Region2    | 
| ALL REGION 2                               | 190091       | 85                  | 128.98               | 0.66     | 0.530, 0.811 | Statistically fewer infections                                                                                  | 4bb41a90-9061-4e3e-b7c6-d904a16262ad | SIR Target (<0.7) Met | 26-50th                                            |            | Region2    | 
| Blue Mountain Hospital                     | 596          | 0                   | 0.26                 |          | *            | #s too small to calculate                                                                                       |                                      | ZERO Infections       |                                                    | GRANT      | Region7    | 
| Coquille Valley Hospital District          | 1904         | 2                   |                      |          | ?            | Neither predicted number of infections nor SIRs were generated because hospital did not submit all data to NHSN |                                      |                       |                                                    | COOS       | Region3    | 
| Curry General Hospital                     | 407          | 0                   | 0.15                 |          | *            | #s too small to calculate                                                                                       |                                      | ZERO Infections       |                                                    | CURRY      | Region3    | 
| Harney District Hospital                   | 1409         | 1                   | 0.66                 |          | *            | #s too small to calculate                                                                                       |                                      |                       |                                                    | HARNEY     | Region7    | 
| Lake District Hospital                     | 2458         | 0                   | 1.00                 |          | *            | #s too small to calculate                                                                                       |                                      | ZERO Infections       |                                                    | LAKE       | Region7    | 
| 1. All Oregon                              | 1389712      | 710                 | 978.92               | 0.72     | 0.673, 0.780 | Statistically fewer infections                                                                                  | f4c1cc8b-b14f-43b9-bfcf-c3e71ef4cb00 | Target Not Met        | 26-50th                                            |            |            | 
| Kaiser Permanente Sunnyside Medical Center | 53930        | 49                  | 43.16                | 1.14     | 0.849, 1.488 | More infections                                                                                                 | 055e4be7-54ab-4b75-bbce-8099a60ccaa3 | Target Not Met        | 76-90th                                            | CLACKAMAS  | Region1    | 
| Kaiser Permanente Westside Medical Center  | 17921        | 17                  | 14.75                | 1.15     | 0.694, 1.807 | More infections                                                                                                 | 66e4154d-7e7e-4bf9-bca3-51d3acb3ea85 | Target Not Met        | 76-90th                                            | WASHINGTON | Region1    | 
```