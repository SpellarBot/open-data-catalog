# NNDSS - Table II. Mumps to Rabies, animal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-mumps-to-rabies-animal-2c751) |
| Metadata | [Link](https://data.cdc.gov/api/views/8rkx-vimh) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8rkx-vimh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8rkx-vimh/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8rkx-vimh |
| Name | NNDSS - Table II. Mumps to Rabies, animal |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2014, mmwr, nndss, wonder, nedss, netss, mumps, pertussis, rabies animal |
| Created | 2014-03-09T22:02:02Z |
| Publication Date | 2015-01-08T16:40:36Z |

## Description

NNDSS - Table II. Mumps to Rabies, animal - 2014.In this Table, all conditions with a 5-year average annual national total of more than or equals 1,000 cases but less than or equals 10,000 cases will be displayed (??? 1,000 and ??_ 10,000). The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Case counts for reporting years 2013 and 2014 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly.More information on NNDSS is available at http://wwwn.cdc.gov/nndss/.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                        | Data Type | Render Type |
| ======== | ============== | ======================================== | =========================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                           | Reporting Area                              | text      | text        |
| No       |                | mmwr_year                                | MMWR Year                                   | number    | number      |
| No       |                | mmwr_week                                | MMWR Week                                   | number    | number      |
| Yes      | numeric metric | mumps_current_week                       | Mumps, Current week                         | number    | number      |
| No       |                | mumps_current_week_flag                  | Mumps, Current week, flag                   | text      | text        |
| Yes      | numeric metric | mumps_previous_52_weeks_med              | Mumps, Previous 52 weeks Med                | number    | number      |
| No       |                | mumps_previous_52_weeks_med_flag         | Mumps, Previous 52 weeks Med, flag          | text      | text        |
| Yes      | numeric metric | mumps_previous_52_weeks_max              | Mumps, Previous 52 weeks Max                | number    | number      |
| No       |                | mumps_previous_52_weeks_max_flag         | Mumps, Previous 52 weeks Max, flag          | text      | text        |
| Yes      | numeric metric | mumps_cum_2014                           | Mumps, Cum 2014                             | number    | number      |
| No       |                | mumps_cum_2014_flag                      | Mumps, Cum 2014, flag                       | text      | text        |
| Yes      | numeric metric | mumps_cum_2013                           | Mumps, Cum 2013                             | number    | number      |
| No       |                | mumps_cum_2013_flag                      | Mumps, Cum 2013, flag                       | text      | text        |
| Yes      | numeric metric | pertussis_current_week                   | Pertussis, Current week                     | number    | number      |
| No       |                | pertussis_current_week_flag              | Pertussis, Current week, flag               | text      | text        |
| Yes      | numeric metric | pertussis_previous_52_weeks_med          | Pertussis, Previous 52 weeks Med            | number    | number      |
| No       |                | pertussis_previous_52_weeks_med_flag     | Pertussis, Previous 52 weeks Med, flag      | text      | text        |
| Yes      | numeric metric | pertussis_previous_52_weeks_max          | Pertussis, Previous 52 weeks Max            | number    | number      |
| No       |                | pertussis_previous_52_weeks_max_flag     | Pertussis, Previous 52 weeks Max, flag      | text      | text        |
| Yes      | numeric metric | pertussis_cum_2014                       | Pertussis, Cum 2014                         | number    | number      |
| No       |                | pertussis_cum_2014_flag                  | Pertussis, Cum 2014, flag                   | text      | text        |
| Yes      | numeric metric | pertussis_cum_2013                       | Pertussis, Cum 2013                         | number    | number      |
| No       |                | pertussis_cum_2013_flag                  | Pertussis, Cum 2013, flag                   | text      | text        |
| Yes      | numeric metric | rabies_animal_current_week               | Rabies, animal, Current week                | number    | number      |
| No       |                | rabies_animal_current_week_flag          | Rabies, animal, Current week, flag          | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_med      | Rabies, animal, Previous 52 weeks Med       | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_med_flag | Rabies, animal, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_max      | Rabies, animal, Previous 52 weeks Max       | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_max_flag | Rabies, animal, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2014                   | Rabies, animal, Cum 2014                    | number    | number      |
| No       |                | rabies_animal_cum_2014_flag              | Rabies, animal, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2013                   | Rabies, animal, Cum 2013                    | number    | number      |
| No       |                | rabies_animal_cum_2013_flag              | Rabies, animal, Cum 2013, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = mumps_current_week_flag,mumps_previous_52_weeks_med_flag,mumps_previous_52_weeks_max_flag,mumps_cum_2014_flag,mumps_cum_2013_flag,pertussis_current_week_flag,pertussis_previous_52_weeks_med_flag,pertussis_previous_52_weeks_max_flag,pertussis_cum_2014_flag,pertussis_cum_2013_flag,rabies_animal_current_week_flag,rabies_animal_previous_52_weeks_med_flag,rabies_animal_previous_52_weeks_max_flag,rabies_animal_cum_2014_flag,rabies_animal_cum_2013_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:8rkx-vimh d:2013-12-29T00:00:00.000Z t:reporting_area="UNITED STATES" m:rabies_animal_cum_2014=7 m:rabies_animal_cum_2013=36 m:pertussis_previous_52_weeks_max=630 m:mumps_previous_52_weeks_max=44 m:rabies_animal_previous_52_weeks_med=62 m:pertussis_previous_52_weeks_med=476 m:mumps_cum_2013=5 m:pertussis_cum_2014=80 m:pertussis_cum_2013=387 m:rabies_animal_previous_52_weeks_max=130 m:pertussis_current_week=80 m:mumps_previous_52_weeks_med=6 m:rabies_animal_current_week=7

series e:8rkx-vimh d:2013-12-29T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:pertussis_cum_2014=1 m:pertussis_cum_2013=28 m:rabies_animal_previous_52_weeks_max=12 m:pertussis_current_week=1 m:rabies_animal_cum_2013=1 m:mumps_previous_52_weeks_med=0 m:pertussis_previous_52_weeks_max=40 m:mumps_previous_52_weeks_max=24 m:rabies_animal_previous_52_weeks_med=6 m:pertussis_previous_52_weeks_med=20

series e:8rkx-vimh d:2013-12-29T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:rabies_animal_cum_2014=2 m:rabies_animal_cum_2013=3 m:pertussis_previous_52_weeks_max=66 m:mumps_previous_52_weeks_max=20 m:rabies_animal_previous_52_weeks_med=6 m:pertussis_previous_52_weeks_med=32 m:mumps_cum_2013=1 m:pertussis_cum_2014=2 m:pertussis_cum_2013=38 m:rabies_animal_previous_52_weeks_max=19 m:pertussis_current_week=2 m:mumps_previous_52_weeks_med=1 m:rabies_animal_current_week=2
```

## Meta Commands

```ls
metric m:mumps_current_week p:integer l:"Mumps, Current week" t:dataTypeName=number

metric m:mumps_previous_52_weeks_med p:integer l:"Mumps, Previous 52 weeks Med" t:dataTypeName=number

metric m:mumps_previous_52_weeks_max p:integer l:"Mumps, Previous 52 weeks Max" t:dataTypeName=number

metric m:mumps_cum_2014 p:integer l:"Mumps, Cum 2014" t:dataTypeName=number

metric m:mumps_cum_2013 p:integer l:"Mumps, Cum 2013" t:dataTypeName=number

metric m:pertussis_current_week p:integer l:"Pertussis, Current week" t:dataTypeName=number

metric m:pertussis_previous_52_weeks_med p:integer l:"Pertussis, Previous 52 weeks Med" t:dataTypeName=number

metric m:pertussis_previous_52_weeks_max p:integer l:"Pertussis, Previous 52 weeks Max" t:dataTypeName=number

metric m:pertussis_cum_2014 p:integer l:"Pertussis, Cum 2014" t:dataTypeName=number

metric m:pertussis_cum_2013 p:integer l:"Pertussis, Cum 2013" t:dataTypeName=number

metric m:rabies_animal_current_week p:integer l:"Rabies, animal, Current week" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_med p:integer l:"Rabies, animal, Previous 52 weeks Med" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_max p:integer l:"Rabies, animal, Previous 52 weeks Max" t:dataTypeName=number

metric m:rabies_animal_cum_2014 p:integer l:"Rabies, animal, Cum 2014" t:dataTypeName=number

metric m:rabies_animal_cum_2013 p:integer l:"Rabies, animal, Cum 2013" t:dataTypeName=number

entity e:8rkx-vimh l:"NNDSS - Table II. Mumps to Rabies, animal" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/8rkx-vimh

property e:8rkx-vimh t:meta.view v:id=8rkx-vimh v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Mumps to Rabies, animal" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:8rkx-vimh t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:8rkx-vimh t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:8rkx-vimh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | mumps_current_week | mumps_current_week_flag | mumps_previous_52_weeks_med | mumps_previous_52_weeks_med_flag | mumps_previous_52_weeks_max | mumps_previous_52_weeks_max_flag | mumps_cum_2014 | mumps_cum_2014_flag | mumps_cum_2013 | mumps_cum_2013_flag | pertussis_current_week | pertussis_current_week_flag | pertussis_previous_52_weeks_med | pertussis_previous_52_weeks_med_flag | pertussis_previous_52_weeks_max | pertussis_previous_52_weeks_max_flag | pertussis_cum_2014 | pertussis_cum_2014_flag | pertussis_cum_2013 | pertussis_cum_2013_flag | rabies_animal_current_week | rabies_animal_current_week_flag | rabies_animal_previous_52_weeks_med | rabies_animal_previous_52_weeks_med_flag | rabies_animal_previous_52_weeks_max | rabies_animal_previous_52_weeks_max_flag | rabies_animal_cum_2014 | rabies_animal_cum_2014_flag | rabies_animal_cum_2013 | rabies_animal_cum_2013_flag | 
| ============== | ========= | ========= | ================== | ======================= | =========================== | ================================ | =========================== | ================================ | ============== | =================== | ============== | =================== | ====================== | =========================== | =============================== | ==================================== | =============================== | ==================================== | ================== | ======================= | ================== | ======================= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2014      | 1         |                    | -                       | 6                           |                                  | 44                          |                                  |                | -                   | 5              |                     | 80                     |                             | 476                             |                                      | 630                             |                                      | 80                 |                         | 387                |                         | 7                          |                                 | 62                                  |                                          | 130                                 |                                          | 7                      |                             | 36                     |                             | 
| NEW ENGLAND    | 2014      | 1         |                    | -                       | 0                           |                                  | 24                          |                                  |                | -                   |                | -                   | 1                      |                             | 20                              |                                      | 40                              |                                      | 1                  |                         | 28                 |                         |                            | -                               | 6                                   |                                          | 12                                  |                                          |                        | -                           | 1                      |                             | 
| MID. ATLANTIC  | 2014      | 1         |                    | -                       | 1                           |                                  | 20                          |                                  |                | -                   | 1              |                     | 2                      |                             | 32                              |                                      | 66                              |                                      | 2                  |                         | 38                 |                         | 2                          |                                 | 6                                   |                                          | 19                                  |                                          | 2                      |                             | 3                      |                             | 
| E.N. CENTRAL   | 2014      | 1         |                    | -                       | 1                           |                                  | 6                           |                                  |                | -                   | 1              |                     | 27                     |                             | 88                              |                                      | 162                             |                                      | 27                 |                         | 115                |                         |                            | -                               | 2                                   |                                          | 24                                  |                                          |                        | -                           | 1                      |                             | 
| W.N. CENTRAL   | 2014      | 1         |                    | -                       | 0                           |                                  | 2                           |                                  |                | -                   |                | -                   | 13                     |                             | 40                              |                                      | 86                              |                                      | 13                 |                         | 65                 |                         |                            | -                               | 2                                   |                                          | 9                                   |                                          |                        | -                           | 2                      |                             | 
| S. ATLANTIC    | 2014      | 1         |                    | -                       | 0                           |                                  | 26                          |                                  |                | -                   |                | -                   | 23                     |                             | 39                              |                                      | 92                              |                                      | 23                 |                         | 12                 |                         | 5                          |                                 | 18                                  |                                          | 44                                  |                                          | 5                      |                             | 27                     |                             | 
| E.S. CENTRAL   | 2014      | 1         |                    | -                       | 0                           |                                  | 3                           |                                  |                | -                   | 2              |                     | 7                      |                             | 15                              |                                      | 35                              |                                      | 7                  |                         | 17                 |                         |                            | -                               | 1                                   |                                          | 7                                   |                                          |                        | -                           |                        | -                           | 
| W.S. CENTRAL   | 2014      | 1         |                    | -                       | 0                           |                                  | 3                           |                                  |                | -                   | 1              |                     | 1                      |                             | 81                              |                                      | 186                             |                                      | 1                  |                         | 2                  |                         |                            | -                               | 17                                  |                                          | 75                                  |                                          |                        | -                           | 2                      |                             | 
| MOUNTAIN       | 2014      | 1         |                    | -                       | 0                           |                                  | 2                           |                                  |                | -                   |                | -                   | 4                      |                             | 96                              |                                      | 174                             |                                      | 4                  |                         | 61                 |                         |                            | -                               | 0                                   |                                          | 9                                   |                                          |                        | -                           |                        | -                           | 
| PACIFIC        | 2014      | 1         |                    | -                       | 0                           |                                  | 4                           |                                  |                | -                   |                | -                   | 2                      |                             | 57                              |                                      | 110                             |                                      | 2                  |                         | 49                 |                         |                            | -                               | 3                                   |                                          | 12                                  |                                          |                        | -                           |                        | -                           | 
```