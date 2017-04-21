# NNDSS - Table II. Rubella to Salmonellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-rubella-to-salmonellosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/4qb4-rsd8) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/4qb4-rsd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/4qb4-rsd8/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 4qb4-rsd8 |
| Name | NNDSS - Table II. Rubella to Salmonellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, rubella, congenital syndrome, salmonellosis |
| Created | 2016-01-12T06:18:18Z |
| Publication Date | 2017-01-05T17:29:07Z |

## Description

NNDSS - Table II. Rubella to Salmonellosis - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.   NP:  Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. 

 * Case counts for reporting year 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly.
? Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                      | Data Type | Render Type |
| ======== | ============== | ====================================================== | ========================================================= | ========= | =========== |
| Yes      | series tag     | reporting_area                                         | Reporting Area                                            | text      | text        |
| No       |                | mmwr_year                                              | MMWR Year                                                 | number    | number      |
| No       |                | mmwr_week                                              | MMWR Week                                                 | number    | number      |
| Yes      | numeric metric | rubella_current_week                                   | Rubella, Current week                                     | number    | number      |
| No       |                | rubella_current_week_flag                              | Rubella, Current week, flag                               | text      | text        |
| Yes      | numeric metric | rubella_previous_52_weeks_med                          | Rubella, Previous 52 weeks Med                            | number    | number      |
| No       |                | rubella_previous_52_weeks_med_flag                     | Rubella, Previous 52 weeks Med, flag                      | text      | text        |
| Yes      | numeric metric | rubella_previous_52_weeks_max                          | Rubella, Previous 52 weeks Max                            | number    | number      |
| No       |                | rubella_previous_52_weeks_max_flag                     | Rubella, Previous 52 weeks Max, flag                      | text      | text        |
| Yes      | numeric metric | rubella_cum_2016                                       | Rubella, Cum 2016                                         | number    | number      |
| No       |                | rubella_cum_2016_flag                                  | Rubella, Cum 2016, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_cum_2015                                       | Rubella, Cum 2015                                         | number    | number      |
| No       |                | rubella_cum_2015_flag                                  | Rubella, Cum 2015, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_current_week               | Rubella, congenital syndrome, Current week                | number    | number      |
| No       |                | rubella_congenital_syndrome_current_week_flag          | Rubella, congenital syndrome, Current week, flag          | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_med      | Rubella, congenital syndrome, Previous 52 weeks Med       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_med_flag | Rubella, congenital syndrome, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_max      | Rubella, congenital syndrome, Previous 52 weeks Max       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_max_flag | Rubella, congenital syndrome, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2016                   | Rubella, congenital syndrome, Cum 2016                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2016_flag              | Rubella, congenital syndrome, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2015                   | Rubella, congenital syndrome, Cum 2015                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2015_flag              | Rubella, congenital syndrome, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | salmonellosis_current_week                             | Salmonellosis, Current week                               | number    | number      |
| No       |                | salmonellosis_current_week_flag                        | Salmonellosis, Current week, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_med                    | Salmonellosis, Previous 52 weeks Med                      | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_med_flag               | Salmonellosis, Previous 52 weeks Med, flag                | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_max                    | Salmonellosis, Previous 52 weeks Max                      | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_max_flag               | Salmonellosis, Previous 52 weeks Max, flag                | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2016                                 | Salmonellosis, Cum 2016                                   | number    | number      |
| No       |                | salmonellosis_cum_2016_flag                            | Salmonellosis, Cum 2016, flag                             | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2015                                 | Salmonellosis, Cum 2015                                   | number    | number      |
| No       |                | salmonellosis_cum_2015_flag                            | Salmonellosis, Cum 2015, flag                             | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = rubella_current_week_flag,rubella_previous_52_weeks_med_flag,rubella_previous_52_weeks_max_flag,rubella_cum_2016_flag,rubella_cum_2015_flag,rubella_congenital_syndrome_current_week_flag,rubella_congenital_syndrome_previous_52_weeks_med_flag,rubella_congenital_syndrome_previous_52_weeks_max_flag,rubella_congenital_syndrome_cum_2016_flag,rubella_congenital_syndrome_cum_2015_flag,salmonellosis_current_week_flag,salmonellosis_previous_52_weeks_med_flag,salmonellosis_previous_52_weeks_max_flag,salmonellosis_cum_2016_flag,salmonellosis_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:4qb4-rsd8 d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=1629 m:rubella_congenital_syndrome_previous_52_weeks_max=1 m:salmonellosis_cum_2016=285 m:salmonellosis_cum_2015=571 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=2 m:salmonellosis_previous_52_weeks_med=928 m:salmonellosis_current_week=285

series e:4qb4-rsd8 d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=87 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:salmonellosis_cum_2016=11 m:salmonellosis_cum_2015=24 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=0 m:salmonellosis_previous_52_weeks_med=33 m:salmonellosis_current_week=11

series e:4qb4-rsd8 d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=167 m:rubella_congenital_syndrome_previous_52_weeks_max=1 m:salmonellosis_cum_2016=26 m:salmonellosis_cum_2015=43 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=0 m:salmonellosis_previous_52_weeks_med=85 m:salmonellosis_current_week=26
```

## Meta Commands

```ls
metric m:rubella_current_week p:integer l:"Rubella, Current week" t:dataTypeName=number

metric m:rubella_previous_52_weeks_med p:integer l:"Rubella, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_previous_52_weeks_max p:integer l:"Rubella, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_cum_2016 p:integer l:"Rubella, Cum 2016" t:dataTypeName=number

metric m:rubella_cum_2015 p:integer l:"Rubella, Cum 2015" t:dataTypeName=number

metric m:rubella_congenital_syndrome_current_week p:long l:"Rubella, congenital syndrome, Current week" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_med p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_max p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2016 p:integer l:"Rubella, congenital syndrome, Cum 2016" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2015 p:integer l:"Rubella, congenital syndrome, Cum 2015" t:dataTypeName=number

metric m:salmonellosis_current_week p:integer l:"Salmonellosis, Current week" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_med p:integer l:"Salmonellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_max p:integer l:"Salmonellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:salmonellosis_cum_2016 p:integer l:"Salmonellosis, Cum 2016" t:dataTypeName=number

metric m:salmonellosis_cum_2015 p:integer l:"Salmonellosis, Cum 2015" t:dataTypeName=number

entity e:4qb4-rsd8 l:"NNDSS - Table II. Rubella to Salmonellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/4qb4-rsd8

property e:4qb4-rsd8 t:meta.view v:id=4qb4-rsd8 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Rubella to Salmonellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:4qb4-rsd8 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:4qb4-rsd8 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:4qb4-rsd8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | rubella_current_week | rubella_current_week_flag | rubella_previous_52_weeks_med | rubella_previous_52_weeks_med_flag | rubella_previous_52_weeks_max | rubella_previous_52_weeks_max_flag | rubella_cum_2016 | rubella_cum_2016_flag | rubella_cum_2015 | rubella_cum_2015_flag | rubella_congenital_syndrome_current_week | rubella_congenital_syndrome_current_week_flag | rubella_congenital_syndrome_previous_52_weeks_med | rubella_congenital_syndrome_previous_52_weeks_med_flag | rubella_congenital_syndrome_previous_52_weeks_max | rubella_congenital_syndrome_previous_52_weeks_max_flag | rubella_congenital_syndrome_cum_2016 | rubella_congenital_syndrome_cum_2016_flag | rubella_congenital_syndrome_cum_2015 | rubella_congenital_syndrome_cum_2015_flag | salmonellosis_current_week | salmonellosis_current_week_flag | salmonellosis_previous_52_weeks_med | salmonellosis_previous_52_weeks_med_flag | salmonellosis_previous_52_weeks_max | salmonellosis_previous_52_weeks_max_flag | salmonellosis_cum_2016 | salmonellosis_cum_2016_flag | salmonellosis_cum_2015 | salmonellosis_cum_2015_flag | 
| ============== | ========= | ========= | ==================== | ========================= | ============================= | ================================== | ============================= | ================================== | ================ | ===================== | ================ | ===================== | ======================================== | ============================================= | ================================================= | ====================================================== | ================================================= | ====================================================== | ==================================== | ========================================= | ==================================== | ========================================= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2016      | 1         |                      | -                         | 0                             |                                    | 2                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 1                                                 |                                                        |                                      | -                                         |                                      | -                                         | 285                        |                                 | 928                                 |                                          | 1629                                |                                          | 285                    |                             | 571                    |                             | 
| NEW ENGLAND    | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 11                         |                                 | 33                                  |                                          | 87                                  |                                          | 11                     |                             | 24                     |                             | 
| MID. ATLANTIC  | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 1                                                 |                                                        |                                      | -                                         |                                      | -                                         | 26                         |                                 | 85                                  |                                          | 167                                 |                                          | 26                     |                             | 43                     |                             | 
| NEW YORK CITY  | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 1                                                 |                                                        |                                      | -                                         |                                      | -                                         | 14                         |                                 | 16                                  |                                          | 37                                  |                                          | 14                     |                             | 16                     |                             | 
| E.N. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 31                         |                                 | 98                                  |                                          | 192                                 |                                          | 31                     |                             | 85                     |                             | 
| W.N. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 13                         |                                 | 33                                  |                                          | 59                                  |                                          | 13                     |                             | 28                     |                             | 
| S. ATLANTIC    | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 126                        |                                 | 248                                 |                                          | 484                                 |                                          | 126                    |                             | 190                    |                             | 
| DIST. OF COL.  | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         |                            | -                               | 0                                   |                                          | 2                                   |                                          |                        | -                           |                        | -                           | 
| E.S. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 16                         |                                 | 66                                  |                                          | 136                                 |                                          | 16                     |                             | 34                     |                             | 
| W.S. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 23                         |                                 | 150                                 |                                          | 335                                 |                                          | 23                     |                             | 30                     |                             | 
```