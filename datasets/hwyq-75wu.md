# NNDSS - Table II. Salmonellosis to Shigellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-salmonellosis-to-shigellosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/hwyq-75wu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hwyq-75wu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hwyq-75wu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hwyq-75wu |
| Name | NNDSS - Table II. Salmonellosis to Shigellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, salmonellosis, shiga toxin-producing e. coli, stec, shigellosis |
| Created | 2017-01-12T20:29:44Z |
| Publication Date | 2017-04-20T18:40:36Z |

## Description

NNDSS - Table II. Salmonellosis to Shigellosis - 2017.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

 U: Unavailable. ?: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

*Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

? Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

$ Includes E. coli O157:H7, Shiga toxin-positive, serogroup non-O157, and Shiga toxin-positive, not serogrouped.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                               | Data Type | Render Type |
| ======== | ============== | ============================================================ | ================================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                               | Reporting Area                                                     | text      | text        |
| No       |                | mmwr_year                                                    | MMWR Year                                                          | number    | number      |
| No       |                | mmwr_week                                                    | MMWR Week                                                          | number    | number      |
| Yes      | numeric metric | salmonellosis_current_week                                   | Salmonellosis, Current week                                        | number    | number      |
| No       |                | salmonellosis_current_week_flag                              | Salmonellosis, Current week, flag                                  | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_med                          | Salmonellosis, Previous 52 weeks Med                               | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_med_flag                     | Salmonellosis, Previous 52 weeks Med, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_max                          | Salmonellosis, Previous 52 weeks Max                               | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_max_flag                     | Salmonellosis, Previous 52 weeks Max, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2017                                       | Salmonellosis, Cum 2017                                            | number    | number      |
| No       |                | salmonellosis_cum_2017_flag                                  | Salmonellosis, Cum 2017, flag                                      | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2016                                       | Salmonellosis, Cum 2016                                            | number    | number      |
| No       |                | salmonellosis_cum_2016_flag                                  | Salmonellosis, Cum 2016, flag                                      | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_current_week               | Shiga toxin-producing E. coli (STEC)?, Current week                | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_current_week_flag          | Shiga toxin-producing E. coli (STEC)?, Current week, flag          | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2017                   | Shiga toxin-producing E. coli (STEC)?, Cum 2017                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2017_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2016                   | Shiga toxin-producing E. coli (STEC)?, Cum 2016                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2016_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | shigellosis_current_week                                     | Shigellosis, Current week                                          | number    | number      |
| No       |                | shigellosis_current_week_flag                                | Shigellosis, Current week, flag                                    | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_med                            | Shigellosis, Previous 52 weeks Med                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_med_flag                       | Shigellosis, Previous 52 weeks Med, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_max                            | Shigellosis, Previous 52 weeks Max                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_max_flag                       | Shigellosis, Previous 52 weeks Max, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2017                                         | Shigellosis, Cum 2017                                              | number    | number      |
| No       |                | shigellosis_cum_2017_flag                                    | Shigellosis, Cum 2017, flag                                        | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2016                                         | Shigellosis, Cum 2016                                              | number    | number      |
| No       |                | shigellosis_cum_2016_flag                                    | Shigellosis, Cum 2016, flag                                        | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = salmonellosis_current_week_flag,salmonellosis_previous_52_weeks_med_flag,salmonellosis_previous_52_weeks_max_flag,salmonellosis_cum_2017_flag,salmonellosis_cum_2016_flag,shiga_toxin_producing_e_coli_stec_current_week_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag,shiga_toxin_producing_e_coli_stec_cum_2017_flag,shiga_toxin_producing_e_coli_stec_cum_2016_flag,shigellosis_current_week_flag,shigellosis_previous_52_weeks_med_flag,shigellosis_previous_52_weeks_max_flag,shigellosis_cum_2017_flag,shigellosis_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:hwyq-75wu d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:shiga_toxin_producing_e_coli_stec_current_week=12 m:shiga_toxin_producing_e_coli_stec_cum_2016=81 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=250 m:salmonellosis_previous_52_weeks_max=1615 m:shigellosis_current_week=74 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=129 m:shiga_toxin_producing_e_coli_stec_cum_2017=12 m:shigellosis_previous_52_weeks_med=370 m:shigellosis_previous_52_weeks_max=479 m:salmonellosis_cum_2016=623 m:salmonellosis_previous_52_weeks_med=834 m:salmonellosis_cum_2017=150 m:salmonellosis_current_week=150 m:shigellosis_cum_2016=358 m:shigellosis_cum_2017=74

series e:hwyq-75wu d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:shiga_toxin_producing_e_coli_stec_cum_2016=2 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=38 m:salmonellosis_previous_52_weeks_max=78 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=5 m:shigellosis_previous_52_weeks_med=5 m:shigellosis_previous_52_weeks_max=13 m:salmonellosis_cum_2016=25 m:salmonellosis_previous_52_weeks_med=38 m:shigellosis_cum_2016=5

series e:hwyq-75wu d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:shiga_toxin_producing_e_coli_stec_current_week=6 m:shiga_toxin_producing_e_coli_stec_cum_2016=14 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=30 m:salmonellosis_previous_52_weeks_max=195 m:shigellosis_current_week=12 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=14 m:shiga_toxin_producing_e_coli_stec_cum_2017=6 m:shigellosis_previous_52_weeks_med=26 m:shigellosis_previous_52_weeks_max=49 m:salmonellosis_cum_2016=59 m:salmonellosis_previous_52_weeks_med=81 m:salmonellosis_cum_2017=27 m:salmonellosis_current_week=27 m:shigellosis_cum_2016=24 m:shigellosis_cum_2017=12
```

## Meta Commands

```ls
metric m:salmonellosis_current_week p:long l:"Salmonellosis, Current week" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_med p:long l:"Salmonellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_max p:long l:"Salmonellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:salmonellosis_cum_2017 p:long l:"Salmonellosis, Cum 2017" t:dataTypeName=number

metric m:salmonellosis_cum_2016 p:long l:"Salmonellosis, Cum 2016" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_current_week p:long l:"Shiga toxin-producing E. coli (STEC)?, Current week" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med p:long l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max p:long l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2017 p:long l:"Shiga toxin-producing E. coli (STEC)?, Cum 2017" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2016 p:long l:"Shiga toxin-producing E. coli (STEC)?, Cum 2016" t:dataTypeName=number

metric m:shigellosis_current_week p:long l:"Shigellosis, Current week" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_med p:long l:"Shigellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_max p:long l:"Shigellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:shigellosis_cum_2017 p:long l:"Shigellosis, Cum 2017" t:dataTypeName=number

metric m:shigellosis_cum_2016 p:long l:"Shigellosis, Cum 2016" t:dataTypeName=number

entity e:hwyq-75wu l:"NNDSS - Table II. Salmonellosis to Shigellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/hwyq-75wu

property e:hwyq-75wu t:meta.view v:id=hwyq-75wu v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Salmonellosis to Shigellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:hwyq-75wu t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:hwyq-75wu t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:hwyq-75wu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | salmonellosis_current_week | salmonellosis_current_week_flag | salmonellosis_previous_52_weeks_med | salmonellosis_previous_52_weeks_med_flag | salmonellosis_previous_52_weeks_max | salmonellosis_previous_52_weeks_max_flag | salmonellosis_cum_2017 | salmonellosis_cum_2017_flag | salmonellosis_cum_2016 | salmonellosis_cum_2016_flag | shiga_toxin_producing_e_coli_stec_current_week | shiga_toxin_producing_e_coli_stec_current_week_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | shiga_toxin_producing_e_coli_stec_cum_2017 | shiga_toxin_producing_e_coli_stec_cum_2017_flag | shiga_toxin_producing_e_coli_stec_cum_2016 | shiga_toxin_producing_e_coli_stec_cum_2016_flag | shigellosis_current_week | shigellosis_current_week_flag | shigellosis_previous_52_weeks_med | shigellosis_previous_52_weeks_med_flag | shigellosis_previous_52_weeks_max | shigellosis_previous_52_weeks_max_flag | shigellosis_cum_2017 | shigellosis_cum_2017_flag | shigellosis_cum_2016 | shigellosis_cum_2016_flag | 
| ============== | ========= | ========= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | ============================================== | =================================================== | ======================================================= | ============================================================ | ======================================================= | ============================================================ | ========================================== | =============================================== | ========================================== | =============================================== | ======================== | ============================= | ================================= | ====================================== | ================================= | ====================================== | ==================== | ========================= | ==================== | ========================= | 
| UNITED STATES  | 2017      | 1         | 150                        |                                 | 834                                 |                                          | 1615                                |                                          | 150                    |                             | 623                    |                             | 12                                             |                                                     | 129                                                     |                                                              | 250                                                     |                                                              | 12                                         |                                                 | 81                                         |                                                 | 74                       |                               | 370                               |                                        | 479                               |                                        | 74                   |                           | 358                  |                           | 
| NEW ENGLAND    | 2017      | 1         |                            | -                               | 38                                  |                                          | 78                                  |                                          |                        | -                           | 25                     |                             |                                                | -                                                   | 5                                                       |                                                              | 38                                                      |                                                              |                                            | -                                               | 2                                          |                                                 |                          | -                             | 5                                 |                                        | 13                                |                                        |                      | -                         | 5                    |                           | 
| MID. ATLANTIC  | 2017      | 1         | 27                         |                                 | 81                                  |                                          | 195                                 |                                          | 27                     |                             | 59                     |                             | 6                                              |                                                     | 14                                                      |                                                              | 30                                                      |                                                              | 6                                          |                                                 | 14                                         |                                                 | 12                       |                               | 26                                |                                        | 49                                |                                        | 12                   |                           | 24                   |                           | 
| NEW YORK CITY  | 2017      | 1         | 8                          |                                 | 19                                  |                                          | 42                                  |                                          | 8                      |                             | 14                     |                             | 4                                              |                                                     | 2                                                       |                                                              | 9                                                       |                                                              | 4                                          |                                                 | 1                                          |                                                 | 7                        |                               | 8                                 |                                        | 17                                |                                        | 7                    |                           | 7                    |                           | 
| E.N. CENTRAL   | 2017      | 1         | 21                         |                                 | 101                                 |                                          | 195                                 |                                          | 21                     |                             | 73                     |                             |                                                | -                                                   | 15                                                      |                                                              | 85                                                      |                                                              |                                            | -                                               | 16                                         |                                                 | 23                       |                               | 63                                |                                        | 120                               |                                        | 23                   |                           | 74                   |                           | 
| W.N. CENTRAL   | 2017      | 1         | 5                          |                                 | 48                                  |                                          | 202                                 |                                          | 5                      |                             | 51                     |                             | 1                                              |                                                     | 17                                                      |                                                              | 41                                                      |                                                              | 1                                          |                                                 | 11                                         |                                                 | 1                        |                               | 30                                |                                        | 98                                |                                        | 1                    |                           | 64                   |                           | 
| S. ATLANTIC    | 2017      | 1         | 54                         |                                 | 207                                 |                                          | 476                                 |                                          | 54                     |                             | 174                    |                             | 2                                              |                                                     | 11                                                      |                                                              | 29                                                      |                                                              | 2                                          |                                                 | 13                                         |                                                 | 18                       |                               | 51                                |                                        | 78                                |                                        | 18                   |                           | 70                   |                           | 
| E.S. CENTRAL   | 2017      | 1         | 10                         |                                 | 72                                  |                                          | 205                                 |                                          | 10                     |                             | 62                     |                             |                                                | -                                                   | 6                                                       |                                                              | 14                                                      |                                                              |                                            | -                                               | 10                                         |                                                 | 9                        |                               | 14                                |                                        | 28                                |                                        | 9                    |                           | 28                   |                           | 
| W.S. CENTRAL   | 2017      | 1         | 7                          |                                 | 144                                 |                                          | 272                                 |                                          | 7                      |                             | 43                     |                             | 1                                              |                                                     | 22                                                      |                                                              | 38                                                      |                                                              | 1                                          |                                                 | 2                                          |                                                 | 2                        |                               | 103                               |                                        | 162                               |                                        | 2                    |                           | 25                   |                           | 
| MOUNTAIN       | 2017      | 1         | 14                         |                                 | 41                                  |                                          | 71                                  |                                          | 14                     |                             | 42                     |                             | 2                                              |                                                     | 12                                                      |                                                              | 25                                                      |                                                              | 2                                          |                                                 | 2                                          |                                                 | 7                        |                               | 31                                |                                        | 54                                |                                        | 7                    |                           | 32                   |                           | 
```