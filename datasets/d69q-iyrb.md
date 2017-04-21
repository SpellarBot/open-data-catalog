# NNDSS - Table II. Mumps to Rabies, animal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-mumps-to-rabies-animal-134f2) |
| Metadata | [Link](https://data.cdc.gov/api/views/d69q-iyrb) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/d69q-iyrb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/d69q-iyrb/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | d69q-iyrb |
| Name | NNDSS - Table II. Mumps to Rabies, animal |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, mumps, pertussis, rabies animal |
| Created | 2015-01-13T19:44:58Z |
| Publication Date | 2016-01-07T15:52:24Z |

## Description

NNDSS - Table II. Mumps to Rabies, animal - 2015.In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP: Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table 2 to facilitate case count verification with reporting jurisdictions. ??? Case counts for reporting year 2015 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly.

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
| Yes      | numeric metric | mumps_cum_2015                           | Mumps, Cum 2015                             | number    | number      |
| No       |                | mumps_cum_2015_flag                      | Mumps, Cum 2015, flag                       | text      | text        |
| Yes      | numeric metric | mumps_cum_2014                           | Mumps, Cum 2014                             | number    | number      |
| No       |                | mumps_cum_2014_flag                      | Mumps, Cum 2014, flag                       | text      | text        |
| Yes      | numeric metric | pertussis_current_week                   | Pertussis, Current week                     | number    | number      |
| No       |                | pertussis_current_week_flag              | Pertussis, Current week, flag               | text      | text        |
| Yes      | numeric metric | pertussis_previous_52_weeks_med          | Pertussis, Previous 52 weeks Med            | number    | number      |
| No       |                | pertussis_previous_52_weeks_med_flag     | Pertussis, Previous 52 weeks Med, flag      | text      | text        |
| Yes      | numeric metric | pertussis_previous_52_weeks_max          | Pertussis, Previous 52 weeks Max            | number    | number      |
| No       |                | pertussis_previous_52_weeks_max_flag     | Pertussis, Previous 52 weeks Max, flag      | text      | text        |
| Yes      | numeric metric | pertussis_cum_2015                       | Pertussis, Cum 2015                         | number    | number      |
| No       |                | pertussis_cum_2015_flag                  | Pertussis, Cum 2015, flag                   | text      | text        |
| Yes      | numeric metric | pertussis_cum_2014                       | Pertussis, Cum 2014                         | number    | number      |
| No       |                | pertussis_cum_2014_flag                  | Pertussis, Cum 2014, flag                   | text      | text        |
| Yes      | numeric metric | rabies_animal_current_week               | Rabies, animal, Current week                | number    | number      |
| No       |                | rabies_animal_current_week_flag          | Rabies, animal, Current week, flag          | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_med      | Rabies, animal, Previous 52 weeks Med       | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_med_flag | Rabies, animal, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_max      | Rabies, animal, Previous 52 weeks Max       | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_max_flag | Rabies, animal, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2015                   | Rabies, animal, Cum 2015                    | number    | number      |
| No       |                | rabies_animal_cum_2015_flag              | Rabies, animal, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2014                   | Rabies, animal, Cum 2014                    | number    | number      |
| No       |                | rabies_animal_cum_2014_flag              | Rabies, animal, Cum 2014, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = mumps_current_week_flag,mumps_previous_52_weeks_med_flag,mumps_previous_52_weeks_max_flag,mumps_cum_2015_flag,mumps_cum_2014_flag,pertussis_current_week_flag,pertussis_previous_52_weeks_med_flag,pertussis_previous_52_weeks_max_flag,pertussis_cum_2015_flag,pertussis_cum_2014_flag,rabies_animal_current_week_flag,rabies_animal_previous_52_weeks_med_flag,rabies_animal_previous_52_weeks_max_flag,rabies_animal_cum_2015_flag,rabies_animal_cum_2014_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:d69q-iyrb d:2014-12-28T00:00:00.000Z t:reporting_area="UNITED STATES" m:rabies_animal_cum_2014=9 m:rabies_animal_cum_2015=8 m:pertussis_previous_52_weeks_max=773 m:mumps_previous_52_weeks_max=117 m:rabies_animal_previous_52_weeks_med=56 m:pertussis_previous_52_weeks_med=513 m:pertussis_cum_2015=153 m:pertussis_cum_2014=416 m:rabies_animal_previous_52_weeks_max=114 m:mumps_cum_2015=2 m:mumps_cum_2014=4 m:pertussis_current_week=153 m:mumps_current_week=2 m:mumps_previous_52_weeks_med=11 m:rabies_animal_current_week=8

series e:d69q-iyrb d:2014-12-28T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:pertussis_cum_2015=2 m:pertussis_cum_2014=9 m:rabies_animal_previous_52_weeks_max=16 m:pertussis_current_week=2 m:rabies_animal_cum_2014=3 m:rabies_animal_cum_2015=1 m:mumps_previous_52_weeks_med=0 m:rabies_animal_current_week=1 m:pertussis_previous_52_weeks_max=45 m:mumps_previous_52_weeks_max=2 m:rabies_animal_previous_52_weeks_med=6 m:pertussis_previous_52_weeks_med=19

series e:d69q-iyrb d:2014-12-28T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:pertussis_cum_2015=19 m:pertussis_cum_2014=26 m:rabies_animal_previous_52_weeks_max=15 m:pertussis_current_week=19 m:mumps_cum_2014=1 m:rabies_animal_cum_2014=2 m:mumps_previous_52_weeks_med=2 m:pertussis_previous_52_weeks_max=80 m:mumps_previous_52_weeks_max=25 m:rabies_animal_previous_52_weeks_med=6 m:pertussis_previous_52_weeks_med=37
```

## Meta Commands

```ls
metric m:mumps_current_week p:integer l:"Mumps, Current week" t:dataTypeName=number

metric m:mumps_previous_52_weeks_med p:integer l:"Mumps, Previous 52 weeks Med" t:dataTypeName=number

metric m:mumps_previous_52_weeks_max p:integer l:"Mumps, Previous 52 weeks Max" t:dataTypeName=number

metric m:mumps_cum_2015 p:integer l:"Mumps, Cum 2015" t:dataTypeName=number

metric m:mumps_cum_2014 p:integer l:"Mumps, Cum 2014" t:dataTypeName=number

metric m:pertussis_current_week p:integer l:"Pertussis, Current week" t:dataTypeName=number

metric m:pertussis_previous_52_weeks_med p:integer l:"Pertussis, Previous 52 weeks Med" t:dataTypeName=number

metric m:pertussis_previous_52_weeks_max p:integer l:"Pertussis, Previous 52 weeks Max" t:dataTypeName=number

metric m:pertussis_cum_2015 p:integer l:"Pertussis, Cum 2015" t:dataTypeName=number

metric m:pertussis_cum_2014 p:integer l:"Pertussis, Cum 2014" t:dataTypeName=number

metric m:rabies_animal_current_week p:integer l:"Rabies, animal, Current week" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_med p:integer l:"Rabies, animal, Previous 52 weeks Med" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_max p:integer l:"Rabies, animal, Previous 52 weeks Max" t:dataTypeName=number

metric m:rabies_animal_cum_2015 p:integer l:"Rabies, animal, Cum 2015" t:dataTypeName=number

metric m:rabies_animal_cum_2014 p:integer l:"Rabies, animal, Cum 2014" t:dataTypeName=number

entity e:d69q-iyrb l:"NNDSS - Table II. Mumps to Rabies, animal" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/d69q-iyrb

property e:d69q-iyrb t:meta.view v:id=d69q-iyrb v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Mumps to Rabies, animal" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:d69q-iyrb t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:d69q-iyrb t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:d69q-iyrb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | mumps_current_week | mumps_current_week_flag | mumps_previous_52_weeks_med | mumps_previous_52_weeks_med_flag | mumps_previous_52_weeks_max | mumps_previous_52_weeks_max_flag | mumps_cum_2015 | mumps_cum_2015_flag | mumps_cum_2014 | mumps_cum_2014_flag | pertussis_current_week | pertussis_current_week_flag | pertussis_previous_52_weeks_med | pertussis_previous_52_weeks_med_flag | pertussis_previous_52_weeks_max | pertussis_previous_52_weeks_max_flag | pertussis_cum_2015 | pertussis_cum_2015_flag | pertussis_cum_2014 | pertussis_cum_2014_flag | rabies_animal_current_week | rabies_animal_current_week_flag | rabies_animal_previous_52_weeks_med | rabies_animal_previous_52_weeks_med_flag | rabies_animal_previous_52_weeks_max | rabies_animal_previous_52_weeks_max_flag | rabies_animal_cum_2015 | rabies_animal_cum_2015_flag | rabies_animal_cum_2014 | rabies_animal_cum_2014_flag | 
| ============== | ========= | ========= | ================== | ======================= | =========================== | ================================ | =========================== | ================================ | ============== | =================== | ============== | =================== | ====================== | =========================== | =============================== | ==================================== | =============================== | ==================================== | ================== | ======================= | ================== | ======================= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2015      | 1         | 2                  |                         | 11                          |                                  | 117                         |                                  | 2              |                     | 4              |                     | 153                    |                             | 513                             |                                      | 773                             |                                      | 153                |                         | 416                |                         | 8                          |                                 | 56                                  |                                          | 114                                 |                                          | 8                      |                             | 9                      |                             | 
| NEW ENGLAND    | 2015      | 1         |                    | -                       | 0                           |                                  | 2                           |                                  |                | -                   |                | -                   | 2                      |                             | 19                              |                                      | 45                              |                                      | 2                  |                         | 9                  |                         | 1                          |                                 | 6                                   |                                          | 16                                  |                                          | 1                      |                             | 3                      |                             | 
| MID. ATLANTIC  | 2015      | 1         |                    | -                       | 2                           |                                  | 25                          |                                  |                | -                   | 1              |                     | 19                     |                             | 37                              |                                      | 80                              |                                      | 19                 |                         | 26                 |                         |                            | -                               | 6                                   |                                          | 15                                  |                                          |                        | -                           | 2                      |                             | 
| E.N. CENTRAL   | 2015      | 1         | 2                  |                         | 6                           |                                  | 107                         |                                  | 2              |                     | 3              |                     | 44                     |                             | 87                              |                                      | 164                             |                                      | 44                 |                         | 109                |                         | 1                          |                                 | 1                                   |                                          | 12                                  |                                          | 1                      |                             |                        | -                           | 
| W.N. CENTRAL   | 2015      | 1         |                    | -                       | 0                           |                                  | 6                           |                                  |                | -                   |                | -                   | 42                     |                             | 39                              |                                      | 69                              |                                      | 42                 |                         | 55                 |                         | 1                          |                                 | 2                                   |                                          | 8                                   |                                          | 1                      |                             |                        | -                           | 
| S. ATLANTIC    | 2015      | 1         |                    | -                       | 0                           |                                  | 9                           |                                  |                | -                   |                | -                   | 28                     |                             | 55                              |                                      | 102                             |                                      | 28                 |                         | 42                 |                         | 2                          |                                 | 7                                   |                                          | 92                                  |                                          | 2                      |                             | 2                      |                             | 
| DIST. OF COL.  | 2015      | 1         |                    | -                       | 0                           |                                  | 4                           |                                  |                | -                   |                | -                   |                        | -                           | 0                               |                                      | 3                               |                                      |                    | -                       |                    | -                       |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| E.S. CENTRAL   | 2015      | 1         |                    | -                       | 0                           |                                  | 2                           |                                  |                | -                   |                | -                   | 13                     |                             | 18                              |                                      | 30                              |                                      | 13                 |                         | 16                 |                         |                            | -                               | 1                                   |                                          | 7                                   |                                          |                        | -                           | 1                      |                             | 
| W.S. CENTRAL   | 2015      | 1         |                    | -                       | 0                           |                                  | 3                           |                                  |                | -                   |                | -                   | 2                      |                             | 56                              |                                      | 92                              |                                      | 2                  |                         | 4                  |                         | 3                          |                                 | 22                                  |                                          | 59                                  |                                          | 3                      |                             | 1                      |                             | 
| MOUNTAIN       | 2015      | 1         |                    | -                       | 0                           |                                  | 4                           |                                  |                | -                   |                | -                   | 1                      |                             | 72                              |                                      | 114                             |                                      | 1                  |                         | 78                 |                         |                            | -                               | 0                                   |                                          | 7                                   |                                          |                        | -                           |                        | -                           | 
```