# 3-Year Recidivism for Offenders Admitted to Probation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/3-year-recidivism-for-offenders-admitted-to-probation) |
| Metadata | [Link](https://data.iowa.gov/api/views/e9zy-uibf) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/e9zy-uibf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/e9zy-uibf/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | e9zy-uibf |
| Name | 3-Year Recidivism for Offenders Admitted to Probation |
| Attribution | Iowa Department of Corrections |
| Category | Public Safety |
| Tags | probation, recidivism |
| Created | 2016-06-01T20:53:12Z |
| Publication Date | 2016-09-22T21:30:57Z |

## Description

This dataset reports whether an offender is re-admitted to prison or not within three years from their admission to probation.  The recidivism reporting year is the fiscal year (year ending June 30) marking the end of the three year tracking period.  The Department of Corrections uses recidivism as an indicator on whether strategies are reducing offenders relapse into criminal behavior.  A three year time frame is used as studies have shown if an offender relapses into criminal behavior it is most likely to happen within three years.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                              | Data Type | Render Type |
| ======== | ============== | ============================ | ================================= | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                        | meta_data | meta_data   |
| Yes      | numeric metric | offender                     | Offender                          | number    | number      |
| Yes      | series tag     | region_cd                    | Region Code                       | text      | text        |
| Yes      | series tag     | recidivism_reporting_year    | Recidivism Reporting Year         | text      | text        |
| Yes      | series tag     | convicting_offense_class     | Convicting Offense Classification | text      | text        |
| Yes      | series tag     | convicting_offense_type      | Convicting Offense Type           | text      | text        |
| Yes      | series tag     | convicting_offense_subtype   | Convicting Offense Subtype        | text      | text        |
| Yes      | series tag     | race_ethnicity_abbr          | Race - Ethnicity                  | text      | text        |
| Yes      | series tag     | sex                          | Sex                               | text      | text        |
| Yes      | series tag     | levelofsupervision           | Level of Supervision              | text      | text        |
| Yes      | series tag     | recidivism_prison_admission  | Recidivism - Prison Admission     | text      | text        |
| Yes      | series tag     | recidivism_type              | Recidivism Type                   | text      | text        |
| Yes      | series tag     | new_conviction_offense_class | New Conviction Offense Class      | text      | text        |
| Yes      | series tag     | new_conviction_type          | New Conviction Offense Type       | text      | text        |
| Yes      | series tag     | new_convictionsubtype        | New Conviction Offense SubType    | text      | text        |
| Yes      | numeric metric | days_to_recidivism           | Days to Recidivism                | number    | number      |
| Yes      | series tag     | part_of_target_population    | Part of Target Population         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e9zy-uibf d:2016-09-22T21:28:17.000Z t:recidivism_type=New t:convicting_offense_class="Serious Misdemeanor" t:sex=Male t:convicting_offense_type=Drug t:race_ethnicity_abbr="American Indian or Alaska Native - Hispanic" t:new_conviction_type=Drug t:new_convictionsubtype=Trafficking t:new_conviction_offense_class="D Felony" t:convicting_offense_subtype="Drug Possession" t:levelofsupervision="Low Normal" t:recidivism_prison_admission=Yes t:recidivism_reporting_year=FY13 t:part_of_target_population=No m:offender=1 m:days_to_recidivism=722

series e:e9zy-uibf d:2016-09-22T21:28:17.000Z t:recidivism_type="No Recidivism" t:convicting_offense_class="Serious Misdemeanor" t:sex=Male t:convicting_offense_type=Property t:race_ethnicity_abbr="American Indian or Alaska Native - Hispanic" t:convicting_offense_subtype=Theft t:levelofsupervision=Intensive t:recidivism_prison_admission=No t:recidivism_reporting_year=FY13 t:part_of_target_population=Yes m:offender=1

series e:e9zy-uibf d:2016-09-22T21:28:17.000Z t:recidivism_type="No Recidivism" t:convicting_offense_class="Serious Misdemeanor" t:sex=Female t:convicting_offense_type=Property t:race_ethnicity_abbr="American Indian or Alaska Native - Hispanic" t:convicting_offense_subtype=Theft t:levelofsupervision=Minimum t:recidivism_prison_admission=No t:recidivism_reporting_year=FY13 t:part_of_target_population=No m:offender=1
```

## Meta Commands

```ls
metric m:offender p:integer l:Offender d:"Each offender is counted once in this column for use in creating visualizations." t:dataTypeName=number

metric m:days_to_recidivism p:integer l:"Days to Recidivism" d:"Number of days it took before the offender returned to prison." t:dataTypeName=number

entity e:e9zy-uibf l:"3-Year Recidivism for Offenders Admitted to Probation" t:attribution="Iowa Department of Corrections" t:url=https://data.iowa.gov/api/views/e9zy-uibf

property e:e9zy-uibf t:meta.view v:id=e9zy-uibf v:category="Public Safety" v:averageRating=0 v:name="3-Year Recidivism for Offenders Admitted to Probation" v:attribution="Iowa Department of Corrections"

property e:e9zy-uibf t:meta.view.owner v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:displayName="Iowa Department of Corrections"

property e:e9zy-uibf t:meta.view.tableauthor v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Corrections"
```

## Top Records

```ls
| :updated_at | offender | region_cd | recidivism_reporting_year | convicting_offense_class | convicting_offense_type | convicting_offense_subtype | race_ethnicity_abbr                             | sex    | levelofsupervision | recidivism_prison_admission | recidivism_type | new_conviction_offense_class | new_conviction_type | new_convictionsubtype | days_to_recidivism | part_of_target_population | 
| =========== | ======== | ========= | ========================= | ======================== | ======================= | ========================== | =============================================== | ====== | ================== | =========================== | =============== | ============================ | =================== | ===================== | ================== | ========================= | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Drug                    | Drug Possession            | American Indian or Alaska Native - Hispanic     | Male   | Low Normal         | Yes                         | New             | D Felony                     | Drug                | Trafficking           | 722                | No                        | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Property                | Theft                      | American Indian or Alaska Native - Hispanic     | Male   | Intensive          | No                          | No Recidivism   |                              |                     |                       |                    | Yes                       | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Property                | Theft                      | American Indian or Alaska Native - Hispanic     | Female | Minimum            | No                          | No Recidivism   |                              |                     |                       |                    | No                        | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Drug                    | Other Drug                 | American Indian or Alaska Native - Hispanic     | Female | Low Risk Probation | No                          | No Recidivism   |                              |                     |                       |                    | No                        | 
| 1474579697  | 1        |           | FY13                      | Aggravated Misdemeanor   | Property                | Theft                      | American Indian or Alaska Native - Non-Hispanic | Male   | Intensive          | Yes                         | New             | Serious Misdemeanor          | Violent             | Assault               | 190                | Yes                       | 
| 1474579697  | 1        |           | FY13                      | Aggravated Misdemeanor   | Drug                    | Drug Possession            | American Indian or Alaska Native - Non-Hispanic | Male   | Unknown            | No                          | No Recidivism   |                              |                     |                       |                    | No                        | 
| 1474579697  | 1        |           | FY13                      | D Felony                 | Public Order            | Flight/Escape              | American Indian or Alaska Native - Non-Hispanic | Male   | Intensive          | Yes                         | New             | D Felony                     | Public Order        | OWI                   | 342                | Yes                       | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Drug                    | Drug Possession            | American Indian or Alaska Native - Non-Hispanic | Male   | Intensive          | Yes                         | New             | D Felony                     | Violent             | Assault               | 1024               | Yes                       | 
| 1474579697  | 1        |           | FY13                      | Serious Misdemeanor      | Public Order            | Traffic                    | American Indian or Alaska Native - Non-Hispanic | Male   | Intensive          | Yes                         | New             | D Felony                     | Violent             | Assault               | 114                | Yes                       | 
| 1474579697  | 1        |           | FY13                      | Aggravated Misdemeanor   | Public Order            | Alcohol                    | American Indian or Alaska Native - Non-Hispanic | Male   | Intensive          | Yes                         | New             | Aggravated Misdemeanor       | Public Order        | Alcohol               | 362                | Yes                       | 
```