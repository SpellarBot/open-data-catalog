# TABLE III. Deaths in 122 U.S. cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-iii-deaths-in-122-u-s-cities-a85f9) |
| Metadata | [Link](https://data.cdc.gov/api/views/qpap-3u8w) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/qpap-3u8w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/qpap-3u8w/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | qpap-3u8w |
| Name | TABLE III. Deaths in 122 U.S. cities |
| Attribution | National Center for Immunization and Respiratory Diseases (NCIRD) |
| Category | MMWR |
| Tags | 2014, 122 cities, mortality, death, pneumonia, influenza |
| Created | 2014-03-19T12:49:55Z |
| Publication Date | 2015-01-08T16:52:19Z |

## Description

TABLE III. Deaths in 122 U.S. cities - 2014.122 Cities Mortality Reporting System. Each week, the vital statistics offices of 122 cities across the United States report the total number of death certificates processed and the number of those for which pneumonia or influenza was listed as the underlying or contributing cause of death by age group (Under 28 days, 28 days - 1 year, 1-14 years, 15-24 years, 25-44 years, 45-64 years, 65-74 years, 75-84 years, and - 85 years).FOOTNOTE:U: Unavailable. ???: No reported cases.* Mortality data in this table are voluntarily reported from 122 cities in the United States, most of which have populations of >100,000. A death is reported by the place of its occurrence and by the week that the death certificate was filed. Fetal deaths are not included.??? Pneumonia and influenza.?? Because of changes in reporting methods in this Pennsylvania city, these numbers are partial counts for the current week. Complete counts will be available in 4 to 6 weeks.?? Total includes unknown ages.More information on  Flu Activity & Surveillance is available at http://www.cdc.gov/flu/weekly/fluactivitysurv.htm.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                       | Data Type | Render Type |
| ======== | ============== | ===================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                        | Reporting Area                             | text      | text        |
| No       |                | mmwr_year                             | MMWR YEAR                                  | number    | number      |
| No       |                | mmwr_week                             | MMWR WEEK                                  | number    | number      |
| Yes      | numeric metric | all_causes_by_age_years_all_ages      | All causes, by age (years), All Ages       | number    | number      |
| No       |                | all_causes_by_age_years_all_ages_flag | All causes, by age (years), All Ages, flag | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_65            | All causes, by age (years), GE 65          | number    | number      |
| No       |                | all_causes_by_age_years_65_flag       | All causes, by age (years), GE 65, flag    | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_45_64         | All causes, by age (years), 45?64          | number    | number      |
| No       |                | all_causes_by_age_years_45_64_flag    | All causes, by age (years), 45?64, flag    | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_25_44         | All causes, by age (years), 25?44          | number    | number      |
| No       |                | all_causes_by_age_years_25_44_flag    | All causes, by age (years), 25?44, flag    | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_1_24          | All causes, by age (years), 1?24           | number    | number      |
| No       |                | all_causes_by_age_years_1_24_flag     | All causes, by age (years), 1?24, flag     | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_lt_1          | All causes, by age (years), LT 1           | number    | number      |
| No       |                | all_causes_by_age_years_lt_1_flag     | All causes, by age (years), LT 1, flag     | text      | text        |
| Yes      | numeric metric | p_amp_i_total                         | P&I? Total                                 | number    | number      |
| No       |                | p_amp_i_total_flag                    | P&I? Total, flag                           | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = all_causes_by_age_years_all_ages_flag,all_causes_by_age_years_65_flag,all_causes_by_age_years_45_64_flag,all_causes_by_age_years_25_44_flag,all_causes_by_age_years_1_24_flag,all_causes_by_age_years_lt_1_flag,p_amp_i_total_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:qpap-3u8w d:2013-12-29T00:00:00.000Z t:reporting_area="New England" m:all_causes_by_age_years_all_ages=517 m:p_amp_i_total=36 m:all_causes_by_age_years_65=373 m:all_causes_by_age_years_1_24=5 m:all_causes_by_age_years_45_64=108 m:all_causes_by_age_years_lt_1=8 m:all_causes_by_age_years_25_44=23

series e:qpap-3u8w d:2013-12-29T00:00:00.000Z t:reporting_area="Mid. Atlantic" m:all_causes_by_age_years_all_ages=2026 m:p_amp_i_total=118 m:all_causes_by_age_years_65=1411 m:all_causes_by_age_years_1_24=34 m:all_causes_by_age_years_45_64=455 m:all_causes_by_age_years_lt_1=15 m:all_causes_by_age_years_25_44=110

series e:qpap-3u8w d:2013-12-29T00:00:00.000Z t:reporting_area="E.N. Central" m:all_causes_by_age_years_all_ages=1453 m:p_amp_i_total=89 m:all_causes_by_age_years_65=983 m:all_causes_by_age_years_1_24=27 m:all_causes_by_age_years_45_64=330 m:all_causes_by_age_years_lt_1=19 m:all_causes_by_age_years_25_44=94
```

## Meta Commands

```ls
metric m:all_causes_by_age_years_all_ages p:integer l:"All causes, by age (years), All Ages" t:dataTypeName=number

metric m:all_causes_by_age_years_65 p:integer l:"All causes, by age (years), GE 65" t:dataTypeName=number

metric m:all_causes_by_age_years_45_64 p:integer l:"All causes, by age (years), 45?64" t:dataTypeName=number

metric m:all_causes_by_age_years_25_44 p:integer l:"All causes, by age (years), 25?44" t:dataTypeName=number

metric m:all_causes_by_age_years_1_24 p:integer l:"All causes, by age (years), 1?24" t:dataTypeName=number

metric m:all_causes_by_age_years_lt_1 p:integer l:"All causes, by age (years), LT 1" t:dataTypeName=number

metric m:p_amp_i_total p:integer l:"P&I? Total" t:dataTypeName=number

entity e:qpap-3u8w l:"TABLE III. Deaths in 122 U.S. cities" t:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)" t:url=https://data.cdc.gov/api/views/qpap-3u8w

property e:qpap-3u8w t:meta.view v:id=qpap-3u8w v:category=MMWR v:averageRating=0 v:name="TABLE III. Deaths in 122 U.S. cities" v:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)"

property e:qpap-3u8w t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:qpap-3u8w t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:qpap-3u8w t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | all_causes_by_age_years_all_ages | all_causes_by_age_years_all_ages_flag | all_causes_by_age_years_65 | all_causes_by_age_years_65_flag | all_causes_by_age_years_45_64 | all_causes_by_age_years_45_64_flag | all_causes_by_age_years_25_44 | all_causes_by_age_years_25_44_flag | all_causes_by_age_years_1_24 | all_causes_by_age_years_1_24_flag | all_causes_by_age_years_lt_1 | all_causes_by_age_years_lt_1_flag | p_amp_i_total | p_amp_i_total_flag | 
| ============== | ========= | ========= | ================================ | ===================================== | ========================== | =============================== | ============================= | ================================== | ============================= | ================================== | ============================ | ================================= | ============================ | ================================= | ============= | ================== | 
| New England    | 2014      | 1         | 517                              |                                       | 373                        |                                 | 108                           |                                    | 23                            |                                    | 5                            |                                   | 8                            |                                   | 36            |                    | 
| Mid. Atlantic  | 2014      | 1         | 2026                             |                                       | 1411                       |                                 | 455                           |                                    | 110                           |                                    | 34                           |                                   | 15                           |                                   | 118           |                    | 
| E.N. Central   | 2014      | 1         | 1453                             |                                       | 983                        |                                 | 330                           |                                    | 94                            |                                    | 27                           |                                   | 19                           |                                   | 89            |                    | 
| W.N. Central   | 2014      | 1         | 543                              |                                       | 354                        |                                 | 131                           |                                    | 32                            |                                    | 11                           |                                   | 15                           |                                   | 51            |                    | 
| S. Atlantic    | 2014      | 1         | 966                              |                                       | 610                        |                                 | 252                           |                                    | 66                            |                                    | 14                           |                                   | 24                           |                                   | 73            |                    | 
| E.S. Central   | 2014      | 1         | 753                              |                                       | 462                        |                                 | 205                           |                                    | 52                            |                                    | 20                           |                                   | 14                           |                                   | 61            |                    | 
| W.S. Central   | 2014      | 1         | 1267                             |                                       | 824                        |                                 | 317                           |                                    | 89                            |                                    | 23                           |                                   | 14                           |                                   | 69            |                    | 
| Mountain       | 2014      | 1         | 1135                             |                                       | 809                        |                                 | 240                           |                                    | 60                            |                                    | 18                           |                                   | 8                            |                                   | 75            |                    | 
| Pacific        | 2014      | 1         | 1649                             |                                       | 1181                       |                                 | 337                           |                                    | 80                            |                                    | 36                           |                                   | 15                           |                                   | 139           |                    | 
| Total?         | 2014      | 1         | 10309                            |                                       | 7007                       |                                 | 2375                          |                                    | 606                           |                                    | 188                          |                                   | 132                          |                                   | 711           |                    | 
```