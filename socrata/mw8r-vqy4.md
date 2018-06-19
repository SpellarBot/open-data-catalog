# 3-Year Recidivism for Offenders Released from Prison

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/3-year-recidivism-for-offenders-released-from-prison) |
| Metadata | [Link](https://data.iowa.gov/api/views/mw8r-vqy4) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/mw8r-vqy4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/mw8r-vqy4/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | mw8r-vqy4 |
| Name | 3-Year Recidivism for Offenders Released from Prison |
| Attribution | Iowa Department of Corrections |
| Category | Public Safety |
| Tags | prison, parole, recidivism |
| Created | 2016-06-01T20:02:35Z |
| Publication Date | 2016-09-23T13:09:49Z |

## Description

This dataset reports whether an offender is re-admitted to prison or not within three years from their release from prison.  The recidivism reporting year is the fiscal year (year ending June 30) marking the end of the three year tracking period.  The Department of Corrections uses recidivism as an indicator on whether strategies are reducing offenders relapse into criminal behavior.  A three year time frame is used as studies have shown if an offender relapses into criminal behavior it is most likely to happen within three years of being released.

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                  | Data Type | Render Type |
| ======== | ============== | ====================================== | ===================================== | ========= | =========== |
| No       | time           | :updated_at                            | updated_at                            | meta_data | meta_data   |
| Yes      | numeric metric | offender                               | Offender                              | number    | number      |
| Yes      | series tag     | recidivism_reporting_year              | Recidivism Reporting Year             | text      | text        |
| Yes      | series tag     | race_ethnicity                         | Race - Ethnicity                      | text      | text        |
| Yes      | series tag     | sex                                    | Sex                                   | text      | text        |
| Yes      | series tag     | age_at_release                         | Age At Release                        | text      | text        |
| Yes      | series tag     | crime_code_classification              | Convicting Offense Classification     | text      | text        |
| Yes      | series tag     | crime_code_offensetype                 | Convicting Offense Type               | text      | text        |
| Yes      | series tag     | crime_code_offense_sub_type            | Convicting Offense Subtype            | text      | text        |
| Yes      | series tag     | release_type                           | Release Type                          | text      | text        |
| Yes      | series tag     | main_supervising_district              | Main Supervising District             | text      | text        |
| Yes      | series tag     | recidivism_return_to_prison            | Recidivism - Return to Prison         | text      | text        |
| Yes      | series tag     | new_or_technical_charge                | Recidivism Type                       | text      | text        |
| Yes      | numeric metric | days_to_recidivism                     | Days to Recidivism                    | number    | number      |
| Yes      | series tag     | recidivism_crime_code_classification   | New Conviction Offense Classification | text      | text        |
| Yes      | series tag     | recidivism_crime_code_offense_type     | New Conviction Offense Type           | text      | text        |
| Yes      | series tag     | recidivism_crime_code_offense_sub_type | New Conviction Offense Sub Type       | text      | text        |
| Yes      | series tag     | part_of_target_population              | Part of Target Population             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mw8r-vqy4 d:2016-09-22T21:01:38.000Z t:crime_code_classification="D Felony" t:sex=M t:crime_code_offensetype=Violent t:recidivism_return_to_prison=Yes t:crime_code_offense_sub_type=Assault t:race_ethnicity="White - Non-Hispanic" t:release_type=Parole t:main_supervising_district=4JD t:recidivism_reporting_year=FY13 t:part_of_target_population=Yes t:age_at_release="Under 25" t:new_or_technical_charge=Tech m:offender=1 m:days_to_recidivism=16

series e:mw8r-vqy4 d:2016-09-22T21:01:38.000Z t:crime_code_classification="D Felony" t:sex=M t:crime_code_offensetype="Public Order" t:recidivism_return_to_prison=Yes t:crime_code_offense_sub_type=OWI t:race_ethnicity="White - Non-Hispanic" t:release_type=Parole t:main_supervising_district=7JD t:recidivism_reporting_year=FY13 t:part_of_target_population=Yes t:age_at_release="55 and Older" t:new_or_technical_charge=Tech m:offender=1 m:days_to_recidivism=19

series e:mw8r-vqy4 d:2016-09-22T21:01:38.000Z t:crime_code_classification="D Felony" t:sex=M t:crime_code_offensetype=Property t:recidivism_return_to_prison=Yes t:crime_code_offense_sub_type=Burglary t:race_ethnicity="White - Non-Hispanic" t:release_type=Parole t:main_supervising_district=5JD t:recidivism_reporting_year=FY13 t:part_of_target_population=Yes t:age_at_release=25-34 t:new_or_technical_charge=Tech m:offender=1 m:days_to_recidivism=22
```

## Meta Commands

```ls
metric m:offender p:integer l:Offender d:"Each offender is counted once in this column for use in creating visualizations." t:dataTypeName=number

metric m:days_to_recidivism p:integer l:"Days to Recidivism" d:"Number of days it took before the offender returned to prison." t:dataTypeName=number

entity e:mw8r-vqy4 l:"3-Year Recidivism for Offenders Released from Prison" t:attribution="Iowa Department of Corrections" t:url=https://data.iowa.gov/api/views/mw8r-vqy4

property e:mw8r-vqy4 t:meta.view v:id=mw8r-vqy4 v:category="Public Safety" v:averageRating=0 v:name="3-Year Recidivism for Offenders Released from Prison" v:attribution="Iowa Department of Corrections"

property e:mw8r-vqy4 t:meta.view.owner v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:displayName="Iowa Department of Corrections"

property e:mw8r-vqy4 t:meta.view.tableauthor v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Corrections"
```

## Top Records

```ls
| :updated_at | offender | recidivism_reporting_year | race_ethnicity       | sex | age_at_release | crime_code_classification | crime_code_offensetype | crime_code_offense_sub_type     | release_type                 | main_supervising_district | recidivism_return_to_prison | new_or_technical_charge | days_to_recidivism | recidivism_crime_code_classification | recidivism_crime_code_offense_type | recidivism_crime_code_offense_sub_type | part_of_target_population | 
| =========== | ======== | ========================= | ==================== | === | ============== | ========================= | ====================== | =============================== | ============================ | ========================= | =========================== | ======================= | ================== | ==================================== | ================================== | ====================================== | ========================= | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | Under 25       | D Felony                  | Violent                | Assault                         | Parole                       | 4JD                       | Yes                         | Tech                    | 16                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 55 and Older   | D Felony                  | Public Order           | OWI                             | Parole                       | 7JD                       | Yes                         | Tech                    | 19                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 25-34          | D Felony                  | Property               | Burglary                        | Parole                       | 5JD                       | Yes                         | Tech                    | 22                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 55 and Older   | C Felony                  | Drug                   | Trafficking                     | Parole                       | 8JD                       | Yes                         | Tech                    | 25                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | Black - Non-Hispanic | M   | 25-34          | D Felony                  | Drug                   | Trafficking                     | Parole                       | 3JD                       | Yes                         | Tech                    | 26                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | Under 25       | D Felony                  | Property               | Burglary                        | Discharged ? End of Sentence |                           | Yes                         | Tech                    | 27                 |                                      |                                    |                                        | No                        | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 45-54          | Aggravated Misdemeanor    | Public Order           | Sex Offender Registry/Residency | Parole                       | 3JD                       | Yes                         | New                     | 28                 | D Felony                             | Property                           | Theft                                  | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 45-54          | D Felony                  | Property               | Burglary                        | Parole                       | 1JD                       | Yes                         | Tech                    | 41                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 45-54          | Aggravated Misdemeanor    | Violent                | Other Violent                   | Parole                       | 5JD                       | Yes                         | Tech                    | 44                 |                                      |                                    |                                        | Yes                       | 
| 1474578098  | 1        | FY13                      | White - Non-Hispanic | M   | 45-54          | C Felony                  | Violent                | Robbery                         | Parole                       | 8JD                       | Yes                         | Tech                    | 46                 |                                      |                                    |                                        | Yes                       | 
```