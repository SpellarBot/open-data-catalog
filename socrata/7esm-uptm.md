# TABLE III. Deaths in 122 U.S. cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-iii-deaths-in-122-u-s-cities-f81b8) |
| Metadata | [Link](https://data.cdc.gov/api/views/7esm-uptm) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/7esm-uptm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/7esm-uptm/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 7esm-uptm |
| Name | TABLE III. Deaths in 122 U.S. cities |
| Attribution | National Center for Immunization and Respiratory Diseases (NCIRD) |
| Category | NNDSS |
| Tags | 2015, 122 cities, mortality, death, pneumonia, influenza |
| Created | 2015-01-13T20:43:00Z |
| Publication Date | 2016-01-07T16:10:30Z |

## Description

TABLE III. Deaths in 122 U.S. cities - 2015122 Cities Mortality Reporting System ??? Each week, the vital statistics offices of 122 cities across the United States report the total number of death certificates processed and the number of those for which pneumonia or influenza was listed as the underlying or contributing cause of death by age group (Under 28 days, 28 days ???1 year, 1-14 years, 15-24 years, 25-44 years, 45-64 years, 65-74 years, 75-84 years, and ??? 85 years).FOOTNOTE:U: Unavailable      -: No reported cases * Mortality data in this table are voluntarily reported from 122 cities in the United States, most of which have populations of 100,000 or more. A death is reported by the place of its occurrence and by the week that the death certificate was filed. Fetal deaths are not included. ** Totals include unknown ages. *** Partial counts for this city.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                         | Data Type | Render Type |
| ======== | ============== | ===================================== | ============================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                        | Reporting Area                               | text      | text        |
| No       |                | mmwr_year                             | MMWR YEAR                                    | number    | number      |
| No       |                | mmwr_week                             | MMWR WEEK                                    | number    | number      |
| Yes      | numeric metric | all_causes_by_age_years_all_ages      | All causes, by age (years), All Ages**       | number    | number      |
| No       |                | all_causes_by_age_years_all_ages_flag | All causes, by age (years), All Ages**, flag | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_65            | All causes, by age (years), ?65              | number    | number      |
| No       |                | all_causes_by_age_years_65_flag       | All causes, by age (years), ?65, flag        | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_45_64         | All causes, by age (years), 45?64            | number    | number      |
| No       |                | all_causes_by_age_years_45_64_flag    | All causes, by age (years), 45?64, flag      | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_25_44         | All causes, by age (years), 25?44            | number    | number      |
| No       |                | all_causes_by_age_years_25_44_flag    | All causes, by age (years), 25?44, flag      | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_1_24          | All causes, by age (years), 1?24             | number    | number      |
| No       |                | all_causes_by_age_years_1_24_flag     | All causes, by age (years), 1?24, flag       | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_lt_1          | All causes, by age (years), LT 1             | number    | number      |
| No       |                | all_causes_by_age_years_lt_1_flag     | All causes, by age (years), LT 1, flag       | text      | text        |
| Yes      | numeric metric | p_i_total                             | P&I? Total                                   | number    | number      |
| No       |                | p_i_total_flag                        | P&I? Total, flag                             | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = all_causes_by_age_years_all_ages_flag,all_causes_by_age_years_65_flag,all_causes_by_age_years_45_64_flag,all_causes_by_age_years_25_44_flag,all_causes_by_age_years_1_24_flag,all_causes_by_age_years_lt_1_flag,p_i_total_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:7esm-uptm d:2014-12-28T00:00:00.000Z t:reporting_area="New England" m:all_causes_by_age_years_all_ages=695 m:p_i_total=68 m:all_causes_by_age_years_65=495 m:all_causes_by_age_years_1_24=11 m:all_causes_by_age_years_45_64=150 m:all_causes_by_age_years_lt_1=6 m:all_causes_by_age_years_25_44=33

series e:7esm-uptm d:2014-12-28T00:00:00.000Z t:reporting_area="Mid. Atlantic" m:all_causes_by_age_years_all_ages=1920 m:p_i_total=164 m:all_causes_by_age_years_65=1383 m:all_causes_by_age_years_1_24=24 m:all_causes_by_age_years_45_64=385 m:all_causes_by_age_years_lt_1=21 m:all_causes_by_age_years_25_44=107

series e:7esm-uptm d:2014-12-28T00:00:00.000Z t:reporting_area="E.N. Central" m:all_causes_by_age_years_all_ages=2952 m:p_i_total=307 m:all_causes_by_age_years_65=2074 m:all_causes_by_age_years_1_24=45 m:all_causes_by_age_years_45_64=632 m:all_causes_by_age_years_lt_1=46 m:all_causes_by_age_years_25_44=155
```

## Meta Commands

```ls
metric m:all_causes_by_age_years_all_ages p:integer l:"All causes, by age (years), All Ages**" t:dataTypeName=number

metric m:all_causes_by_age_years_65 p:integer l:"All causes, by age (years), ?65" t:dataTypeName=number

metric m:all_causes_by_age_years_45_64 p:integer l:"All causes, by age (years), 45?64" t:dataTypeName=number

metric m:all_causes_by_age_years_25_44 p:integer l:"All causes, by age (years), 25?44" t:dataTypeName=number

metric m:all_causes_by_age_years_1_24 p:integer l:"All causes, by age (years), 1?24" t:dataTypeName=number

metric m:all_causes_by_age_years_lt_1 p:integer l:"All causes, by age (years), LT 1" t:dataTypeName=number

metric m:p_i_total p:integer l:"P&I? Total" t:dataTypeName=number

entity e:7esm-uptm l:"TABLE III. Deaths in 122 U.S. cities" t:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)" t:url=https://data.cdc.gov/api/views/7esm-uptm

property e:7esm-uptm t:meta.view v:id=7esm-uptm v:category=NNDSS v:averageRating=0 v:name="TABLE III. Deaths in 122 U.S. cities" v:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)"

property e:7esm-uptm t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:7esm-uptm t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:7esm-uptm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | all_causes_by_age_years_all_ages | all_causes_by_age_years_all_ages_flag | all_causes_by_age_years_65 | all_causes_by_age_years_65_flag | all_causes_by_age_years_45_64 | all_causes_by_age_years_45_64_flag | all_causes_by_age_years_25_44 | all_causes_by_age_years_25_44_flag | all_causes_by_age_years_1_24 | all_causes_by_age_years_1_24_flag | all_causes_by_age_years_lt_1 | all_causes_by_age_years_lt_1_flag | p_i_total | p_i_total_flag | 
| ============== | ========= | ========= | ================================ | ===================================== | ========================== | =============================== | ============================= | ================================== | ============================= | ================================== | ============================ | ================================= | ============================ | ================================= | ========= | ============== | 
| New England    | 2015      | 1         | 695                              |                                       | 495                        |                                 | 150                           |                                    | 33                            |                                    | 11                           |                                   | 6                            |                                   | 68        |                | 
| Mid. Atlantic  | 2015      | 1         | 1920                             |                                       | 1383                       |                                 | 385                           |                                    | 107                           |                                    | 24                           |                                   | 21                           |                                   | 164       |                | 
| E.N. Central   | 2015      | 1         | 2952                             |                                       | 2074                       |                                 | 632                           |                                    | 155                           |                                    | 45                           |                                   | 46                           |                                   | 307       |                | 
| W.N. Central   | 2015      | 1         | 850                              |                                       | 555                        |                                 | 204                           |                                    | 53                            |                                    | 18                           |                                   | 18                           |                                   | 81        |                | 
| S. Atlantic    | 2015      | 1         | 1416                             |                                       | 933                        |                                 | 342                           |                                    | 85                            |                                    | 29                           |                                   | 27                           |                                   | 124       |                | 
| E.S. Central   | 2015      | 1         | 1292                             |                                       | 874                        |                                 | 305                           |                                    | 72                            |                                    | 18                           |                                   | 23                           |                                   | 102       |                | 
| W.S. Central   | 2015      | 1         | 2078                             |                                       | 1368                       |                                 | 513                           |                                    | 130                           |                                    | 37                           |                                   | 30                           |                                   | 139       |                | 
| Mountain       | 2015      | 1         | 1710                             |                                       | 1197                       |                                 | 358                           |                                    | 100                           |                                    | 31                           |                                   | 22                           |                                   | 127       |                | 
| Pacific        | 2015      | 1         | 2348                             |                                       | 1690                       |                                 | 472                           |                                    | 123                           |                                    | 41                           |                                   | 22                           |                                   | 189       |                | 
| Total?         | 2015      | 1         | 15261                            |                                       | 10569                      |                                 | 3361                          |                                    | 858                           |                                    | 254                          |                                   | 215                          |                                   | 1301      |                | 
```