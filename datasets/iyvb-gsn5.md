# Maryland Department of Health and Mental Hygiene (DHMH) Dashboard Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-department-of-health-and-mental-hygiene-dhmh-dashboard-measures) |
| Metadata | [Link](https://data.maryland.gov/api/views/iyvb-gsn5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iyvb-gsn5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iyvb-gsn5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iyvb-gsn5 |
| Name | Maryland Department of Health and Mental Hygiene (DHMH) Dashboard Measures |
| Category | Health and Human Services |
| Tags | public health, managing for results, mfr, heroin, lead, immun, vac, mortality, hiv, dhmh |
| Created | 2016-06-30T17:37:23Z |
| Publication Date | 2017-02-08T20:34:22Z |

## Description

Data sources: heroin overdose deaths/infant mortality-Vital Statistics Administration; lead-Medicaid; HIV diagnoses-Prevention and Health Promotion Administration; and immunizations-National Immunization Survey.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                                    | Data Type     | Render Type   |
| ======== | ============== | ============================================================= | ======================================================================= | ============= | ============= |
| Yes      | time           | date                                                          | Date                                                                    | calendar_date | calendar_date |
| No       |                | year                                                          | Year                                                                    | number        | text          |
| Yes      | numeric metric | total_drug_alcohol_related_deaths                             | Total Drug & Alcohol Related Deaths                                     | number        | number        |
| Yes      | numeric metric | heroin_overdose_deaths_n                                      | Heroin Deaths                                                           | number        | number        |
| Yes      | numeric metric | prescription_opioid_deaths                                    | Prescription Opioid Deaths                                              | number        | number        |
| Yes      | numeric metric | fentanyl_deaths                                               | Fentanyl Deaths                                                         | number        | number        |
| Yes      | numeric metric | cocaine_deaths                                                | Cocaine Deaths                                                          | number        | number        |
| Yes      | numeric metric | alcohol_deaths                                                | Alcohol Deaths                                                          | number        | number        |
| Yes      | numeric metric | healthchoice_children_12_23_months_receiving_a_lead_test      | Percent of HealthChoice Children (12 - 23 months) Receiving a Lead Test | percent       | percent       |
| Yes      | numeric metric | maryland_children_fully_immunized_by_24_months                | Percent of Maryland Children Fully Immunized by 24 Months               | percent       | percent       |
| Yes      | numeric metric | infant_mortality_rate_for_all_races_per_1_000_live_births     | Infant Mortality Rate for All Races (per 1,000 live births)             | number        | number        |
| Yes      | numeric metric | rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population | Rate of Age-Adjusted New HIV Diagnoses (per 100,000 population)         | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:iyvb-gsn5 d:2011-12-31T00:00:00.000Z m:maryland_children_fully_immunized_by_24_months=74 m:cocaine_deaths=148 m:healthchoice_children_12_23_months_receiving_a_lead_test=58 m:alcohol_deaths=161 m:rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population=25.7 m:fentanyl_deaths=26 m:infant_mortality_rate_for_all_races_per_1_000_live_births=6.7 m:heroin_overdose_deaths_n=247 m:prescription_opioid_deaths=342 m:total_drug_alcohol_related_deaths=671

series e:iyvb-gsn5 d:2012-12-31T00:00:00.000Z m:maryland_children_fully_immunized_by_24_months=67 m:cocaine_deaths=153 m:healthchoice_children_12_23_months_receiving_a_lead_test=58 m:alcohol_deaths=195 m:rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population=24.9 m:fentanyl_deaths=29 m:infant_mortality_rate_for_all_races_per_1_000_live_births=6.7 m:heroin_overdose_deaths_n=392 m:prescription_opioid_deaths=311 m:total_drug_alcohol_related_deaths=799

series e:iyvb-gsn5 d:2013-12-31T00:00:00.000Z m:maryland_children_fully_immunized_by_24_months=76 m:cocaine_deaths=154 m:healthchoice_children_12_23_months_receiving_a_lead_test=59 m:alcohol_deaths=239 m:rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population=24.4 m:fentanyl_deaths=58 m:infant_mortality_rate_for_all_races_per_1_000_live_births=6.6 m:heroin_overdose_deaths_n=464 m:prescription_opioid_deaths=316 m:total_drug_alcohol_related_deaths=858
```

## Meta Commands

```ls
metric m:total_drug_alcohol_related_deaths p:integer l:"Total Drug & Alcohol Related Deaths" d:"Total Drug & Alcohol Related Deaths" t:dataTypeName=number

metric m:heroin_overdose_deaths_n p:integer l:"Heroin Deaths" d:"Total deaths related to heroin overdose" t:dataTypeName=number

metric m:prescription_opioid_deaths p:integer l:"Prescription Opioid Deaths" d:"Total deaths from prescription opioid-related overdose" t:dataTypeName=number

metric m:fentanyl_deaths p:integer l:"Fentanyl Deaths" d:"Total deaths related to fentanyl overdose" t:dataTypeName=number

metric m:cocaine_deaths p:integer l:"Cocaine Deaths" d:"Total deaths related to cocaine overdose" t:dataTypeName=number

metric m:alcohol_deaths p:integer l:"Alcohol Deaths" d:"Total deaths related to alcohol overdose" t:dataTypeName=number

metric m:healthchoice_children_12_23_months_receiving_a_lead_test p:integer l:"Percent of HealthChoice Children (12 - 23 months) Receiving a Lead Test" t:dataTypeName=percent

metric m:maryland_children_fully_immunized_by_24_months p:integer l:"Percent of Maryland Children Fully Immunized by 24 Months" t:dataTypeName=percent

metric m:infant_mortality_rate_for_all_races_per_1_000_live_births p:float l:"Infant Mortality Rate for All Races (per 1,000 live births)" t:dataTypeName=number

metric m:rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population p:float l:"Rate of Age-Adjusted New HIV Diagnoses (per 100,000 population)" t:dataTypeName=number

entity e:iyvb-gsn5 l:"Maryland Department of Health and Mental Hygiene (DHMH) Dashboard Measures" t:url=https://data.maryland.gov/api/views/iyvb-gsn5

property e:iyvb-gsn5 t:meta.view v:id=iyvb-gsn5 v:category="Health and Human Services" v:averageRating=0 v:name="Maryland Department of Health and Mental Hygiene (DHMH) Dashboard Measures"

property e:iyvb-gsn5 t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:iyvb-gsn5 t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| date                | year | total_drug_alcohol_related_deaths | heroin_overdose_deaths_n | prescription_opioid_deaths | fentanyl_deaths | cocaine_deaths | alcohol_deaths | healthchoice_children_12_23_months_receiving_a_lead_test | maryland_children_fully_immunized_by_24_months | infant_mortality_rate_for_all_races_per_1_000_live_births | rate_of_age_adjusted_new_hiv_diagnoses_per_100_000_population | 
| =================== | ==== | ================================= | ======================== | ========================== | =============== | ============== | ============== | ======================================================== | ============================================== | ========================================================= | ============================================================= | 
| 2011-12-31T00:00:00 | 2011 | 671                               | 247                      | 342                        | 26              | 148            | 161            | 58                                                       | 74                                             | 6.7                                                       | 25.7                                                          | 
| 2012-12-31T00:00:00 | 2012 | 799                               | 392                      | 311                        | 29              | 153            | 195            | 58                                                       | 67                                             | 6.7                                                       | 24.9                                                          | 
| 2013-12-31T00:00:00 | 2013 | 858                               | 464                      | 316                        | 58              | 154            | 239            | 59                                                       | 76                                             | 6.6                                                       | 24.4                                                          | 
| 2014-12-31T00:00:00 | 2014 | 1041                              | 578                      | 330                        | 186             | 198            | 270            | 60                                                       | 74                                             | 6.5                                                       | 18.8                                                          | 
| 2015-12-31T00:00:00 | 2015 | 1259                              | 748                      | 351                        | 340             | 220            | 309            | 61                                                       | 77                                             | 6.7                                                       |                                                               | 
| 2016-12-31T00:00:00 |      | 1468                              | 918                      | 317                        | 738             | 323            | 417            |                                                          |                                                |                                                           |                                                               | 
```