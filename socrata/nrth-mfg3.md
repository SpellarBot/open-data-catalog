# Medicare Hospital Spending by Claim

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medicare-hospital-spending-by-claim-61b57) |
| Metadata | [Link](https://data.medicare.gov/api/views/nrth-mfg3) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/nrth-mfg3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/nrth-mfg3/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | nrth-mfg3 |
| Name | Medicare Hospital Spending by Claim |
| Category | Hospital Compare |
| Tags | hospital compare, medicare payment |
| Created | 2012-07-06T19:13:07Z |
| Publication Date | 2016-12-19T02:13:25Z |

## Description

Also known as Medicare Spending per Beneficiary (MSPB) Spending Breakdowns by Claim Type file. The data displayed here show average spending levels during hospitals? Medicare Spending per Beneficiary (MSPB) episodes. An MSPB episode includes all Medicare Part A and Part B claims paid during the period from 3 days prior to a hospital admission through 30 days after discharge.  These average Medicare payment amounts have been price-standardized to remove the effect of geographic payment differences and add-on payments for indirect medical education (IME) and disproportionate share hospitals (DSH). CMS uses the information on this webpage to calculate a hospital?s MSPB Measure value, which is reported on Hospital Compare. Specifically, the MSPB Measure methodology risk-adjusts the values on this webpage to account for beneficiary age and severity of illness. This webpage provides the pre-risk-adjusted values to help the public understand the MSPB Measure and its composition.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | hospital_name                     | Hospital_Name                     | text      | text        |
| Yes      | series tag     | provider_number                   | Provider_ID                       | text      | text        |
| Yes      | series tag     | state                             | State                             | text      | text        |
| Yes      | series tag     | period                            | Period                            | text      | text        |
| Yes      | series tag     | claim_type                        | Claim_Type                        | text      | text        |
| Yes      | numeric metric | avg_spending_per_episode_hospital | Avg_Spending_Per_Episode_Hospital | money     | money       |
| Yes      | numeric metric | avg_spending_per_episode_state    | Avg_Spending_Per_Episode_State    | money     | money       |
| Yes      | numeric metric | avg_spending_per_episode_nation   | Avg_Spending_Per_Episode_Nation   | money     | money       |
| Yes      | numeric metric | percent_of_spending_hospital      | Percent_of_Spending_Hospital      | percent   | percent     |
| Yes      | numeric metric | percent_of_spending_state         | Percent_of_Spending_State         | percent   | percent     |
| Yes      | numeric metric | percent_of_spending_nation        | Percent_of_Spending_Nation        | percent   | percent     |
| Yes      | time           | measure_start_date                | Start_Date                        | text      | text        |
| No       |                | measure_end_date                  | End_Date                          | text      | text        |
```

## Time Field

```ls
Value = measure_start_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = measure_end_date
```

## Data Commands

```ls
series e:nrth-mfg3 d:0102-08-15T00:00:00.000Z t:hospital_name="HELEN KELLER HOSPITAL" t:claim_type="Skilled Nursing Facility" t:provider_number=010019 t:state=AL t:period="During Index Hospital Admission" m:avg_spending_per_episode_state=0 m:avg_spending_per_episode_nation=0 m:percent_of_spending_hospital=0 m:percent_of_spending_nation=0 m:percent_of_spending_state=0 m:avg_spending_per_episode_hospital=0

series e:nrth-mfg3 d:0102-08-15T00:00:00.000Z t:hospital_name="HELEN KELLER HOSPITAL" t:claim_type="Durable Medical Equipment" t:provider_number=010019 t:state=AL t:period="During Index Hospital Admission" m:avg_spending_per_episode_state=31 m:avg_spending_per_episode_nation=24 m:percent_of_spending_hospital=0.1 m:percent_of_spending_nation=0.12 m:percent_of_spending_state=0.16 m:avg_spending_per_episode_hospital=18

series e:nrth-mfg3 d:0102-08-15T00:00:00.000Z t:hospital_name="HELEN KELLER HOSPITAL" t:claim_type=Carrier t:provider_number=010019 t:state=AL t:period="During Index Hospital Admission" m:avg_spending_per_episode_state=1480 m:avg_spending_per_episode_nation=1540 m:percent_of_spending_hospital=6.01 m:percent_of_spending_nation=7.52 m:percent_of_spending_state=7.71 m:avg_spending_per_episode_hospital=1062
```

## Meta Commands

```ls
metric m:avg_spending_per_episode_hospital p:integer l:Avg_Spending_Per_Episode_Hospital t:dataTypeName=money

metric m:avg_spending_per_episode_state p:integer l:Avg_Spending_Per_Episode_State t:dataTypeName=money

metric m:avg_spending_per_episode_nation p:integer l:Avg_Spending_Per_Episode_Nation t:dataTypeName=money

metric m:percent_of_spending_hospital p:float l:Percent_of_Spending_Hospital t:dataTypeName=percent

metric m:percent_of_spending_state p:float l:Percent_of_Spending_State t:dataTypeName=percent

metric m:percent_of_spending_nation p:float l:Percent_of_Spending_Nation t:dataTypeName=percent

entity e:nrth-mfg3 l:"Medicare Hospital Spending by Claim" t:url=https://data.medicare.gov/api/views/nrth-mfg3

property e:nrth-mfg3 t:meta.view v:id=nrth-mfg3 v:category="Hospital Compare" v:averageRating=0 v:name="Medicare Hospital Spending by Claim"

property e:nrth-mfg3 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:nrth-mfg3 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms
```

## Top Records

```ls
| hospital_name         | provider_number | state | period                                                          | claim_type                | avg_spending_per_episode_hospital | avg_spending_per_episode_state | avg_spending_per_episode_nation | percent_of_spending_hospital | percent_of_spending_state | percent_of_spending_nation | measure_start_date | measure_end_date | 
| ===================== | =============== | ===== | =============================================================== | ========================= | ================================= | ============================== | =============================== | ============================ | ========================= | ========================== | ================== | ================ | 
| HELEN KELLER HOSPITAL | 010019          | AL    | During Index Hospital Admission                                 | Skilled Nursing Facility  | 0                                 | 0                              | 0                               | 0.00                         | 0.00                      | 0.00                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | During Index Hospital Admission                                 | Durable Medical Equipment | 18                                | 31                             | 24                              | 0.10                         | 0.16                      | 0.12                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | During Index Hospital Admission                                 | Carrier                   | 1062                              | 1480                           | 1540                            | 6.01                         | 7.71                      | 7.52                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Home Health Agency        | 917                               | 948                            | 816                             | 5.19                         | 4.94                      | 3.98                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Hospice                   | 172                               | 154                            | 122                             | 0.97                         | 0.80                      | 0.60                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Inpatient                 | 2518                              | 2634                           | 2702                            | 14.25                        | 13.72                     | 13.18                      | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Outpatient                | 473                               | 596                            | 730                             | 2.68                         | 3.10                      | 3.56                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Skilled Nursing Facility  | 3544                              | 2626                           | 3319                            | 20.06                        | 13.67                     | 16.19                      | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Durable Medical Equipment | 79                                | 126                            | 103                             | 0.45                         | 0.66                      | 0.50                       | 01012015           | 12312015         | 
| HELEN KELLER HOSPITAL | 010019          | AL    | 1 through 30 days After Discharge from Index Hospital Admission | Carrier                   | 970                               | 1046                           | 1110                            | 5.49                         | 5.45                      | 5.42                       | 01012015           | 12312015         | 
```