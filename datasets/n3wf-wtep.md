# NNDSS - Table II. Shiga toxin to Shigellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-shiga-toxin-to-shigellosis-c44fc) |
| Metadata | [Link](https://data.cdc.gov/api/views/n3wf-wtep) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/n3wf-wtep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/n3wf-wtep/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | n3wf-wtep |
| Name | NNDSS - Table II. Shiga toxin to Shigellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, shiga toxin-producing e. coli, stec, shigellosis |
| Created | 2015-01-13T20:01:07Z |
| Publication Date | 2016-01-07T15:58:14Z |

## Description

NNDSS - Table II. Shiga toxin to Shigellosis - 2015.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP: Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table 2 to facilitate case count verification with reporting jurisdictions. ??? Case counts for reporting year 2015 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. ?? Includes E. coli O157:H7; Shiga toxin-positive, serogroup non-O157; and Shiga toxin-positive, not serogrouped.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                               | Data Type | Render Type |
| ======== | ============== | ============================================================ | ================================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                               | Reporting Area                                                     | text      | text        |
| No       |                | mmwr_year                                                    | MMWR Year                                                          | number    | number      |
| No       |                | mmwr_week                                                    | MMWR Week                                                          | number    | number      |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_current_week               | Shiga toxin-producing E. coli (STEC)?, Current week                | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_current_week_flag          | Shiga toxin-producing E. coli (STEC)?, Current week, flag          | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2015                   | Shiga toxin-producing E. coli (STEC)?, Cum 2015                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2015_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2014                   | Shiga toxin-producing E. coli (STEC)?, Cum 2014                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2014_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | shigellosis_current_week                                     | Shigellosis, Current week                                          | number    | number      |
| No       |                | shigellosis_current_week_flag                                | Shigellosis, Current week, flag                                    | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_med                            | Shigellosis, Previous 52 weeks Med                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_med_flag                       | Shigellosis, Previous 52 weeks Med, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_max                            | Shigellosis, Previous 52 weeks Max                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_max_flag                       | Shigellosis, Previous 52 weeks Max, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2015                                         | Shigellosis, Cum 2015                                              | number    | number      |
| No       |                | shigellosis_cum_2015_flag                                    | Shigellosis, Cum 2015, flag                                        | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2014                                         | Shigellosis, Cum 2014                                              | number    | number      |
| No       |                | shigellosis_cum_2014_flag                                    | Shigellosis, Cum 2014, flag                                        | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = shiga_toxin_producing_e_coli_stec_current_week_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag,shiga_toxin_producing_e_coli_stec_cum_2015_flag,shiga_toxin_producing_e_coli_stec_cum_2014_flag,shigellosis_current_week_flag,shigellosis_previous_52_weeks_med_flag,shigellosis_previous_52_weeks_max_flag,shigellosis_cum_2015_flag,shigellosis_cum_2014_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:n3wf-wtep d:2014-12-28T00:00:00.000Z t:reporting_area="UNITED STATES" m:shiga_toxin_producing_e_coli_stec_cum_2015=13 m:shiga_toxin_producing_e_coli_stec_current_week=13 m:shiga_toxin_producing_e_coli_stec_cum_2014=40 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=205 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=95 m:shigellosis_current_week=182 m:shigellosis_previous_52_weeks_med=390 m:shigellosis_previous_52_weeks_max=565 m:shigellosis_cum_2014=298 m:shigellosis_cum_2015=182

series e:n3wf-wtep d:2014-12-28T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:shiga_toxin_producing_e_coli_stec_cum_2014=3 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=15 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=3 m:shigellosis_previous_52_weeks_med=6 m:shigellosis_previous_52_weeks_max=14 m:shigellosis_cum_2014=2

series e:n3wf-wtep d:2014-12-28T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:shiga_toxin_producing_e_coli_stec_cum_2015=1 m:shiga_toxin_producing_e_coli_stec_current_week=1 m:shiga_toxin_producing_e_coli_stec_cum_2014=5 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=26 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=9 m:shigellosis_current_week=40 m:shigellosis_previous_52_weeks_med=18 m:shigellosis_previous_52_weeks_max=45 m:shigellosis_cum_2014=12 m:shigellosis_cum_2015=40
```

## Meta Commands

```ls
metric m:shiga_toxin_producing_e_coli_stec_current_week p:integer l:"Shiga toxin-producing E. coli (STEC)?, Current week" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2015 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2015" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2014 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2014" t:dataTypeName=number

metric m:shigellosis_current_week p:integer l:"Shigellosis, Current week" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_med p:integer l:"Shigellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_max p:integer l:"Shigellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:shigellosis_cum_2015 p:integer l:"Shigellosis, Cum 2015" t:dataTypeName=number

metric m:shigellosis_cum_2014 p:integer l:"Shigellosis, Cum 2014" t:dataTypeName=number

entity e:n3wf-wtep l:"NNDSS - Table II. Shiga toxin to Shigellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/n3wf-wtep

property e:n3wf-wtep t:meta.view v:id=n3wf-wtep v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Shiga toxin to Shigellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:n3wf-wtep t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:n3wf-wtep t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:n3wf-wtep t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | shiga_toxin_producing_e_coli_stec_current_week | shiga_toxin_producing_e_coli_stec_current_week_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | shiga_toxin_producing_e_coli_stec_cum_2015 | shiga_toxin_producing_e_coli_stec_cum_2015_flag | shiga_toxin_producing_e_coli_stec_cum_2014 | shiga_toxin_producing_e_coli_stec_cum_2014_flag | shigellosis_current_week | shigellosis_current_week_flag | shigellosis_previous_52_weeks_med | shigellosis_previous_52_weeks_med_flag | shigellosis_previous_52_weeks_max | shigellosis_previous_52_weeks_max_flag | shigellosis_cum_2015 | shigellosis_cum_2015_flag | shigellosis_cum_2014 | shigellosis_cum_2014_flag | 
| ============== | ========= | ========= | ============================================== | =================================================== | ======================================================= | ============================================================ | ======================================================= | ============================================================ | ========================================== | =============================================== | ========================================== | =============================================== | ======================== | ============================= | ================================= | ====================================== | ================================= | ====================================== | ==================== | ========================= | ==================== | ========================= | 
| UNITED STATES  | 2015      | 1         | 13                                             |                                                     | 95                                                      |                                                              | 205                                                     |                                                              | 13                                         |                                                 | 40                                         |                                                 | 182                      |                               | 390                               |                                        | 565                               |                                        | 182                  |                           | 298                  |                           | 
| NEW ENGLAND    | 2015      | 1         |                                                | -                                                   | 3                                                       |                                                              | 15                                                      |                                                              |                                            | -                                               | 3                                          |                                                 |                          | -                             | 6                                 |                                        | 14                                |                                        |                      | -                         | 2                    |                           | 
| MID. ATLANTIC  | 2015      | 1         | 1                                              |                                                     | 9                                                       |                                                              | 26                                                      |                                                              | 1                                          |                                                 | 5                                          |                                                 | 40                       |                               | 18                                |                                        | 45                                |                                        | 40                   |                           | 12                   |                           | 
| E.N. CENTRAL   | 2015      | 1         | 2                                              |                                                     | 11                                                      |                                                              | 38                                                      |                                                              | 2                                          |                                                 | 9                                          |                                                 | 14                       |                               | 60                                |                                        | 126                               |                                        | 14                   |                           | 25                   |                           | 
| W.N. CENTRAL   | 2015      | 1         |                                                | -                                                   | 10                                                      |                                                              | 35                                                      |                                                              |                                            | -                                               | 2                                          |                                                 | 25                       |                               | 47                                |                                        | 93                                |                                        | 25                   |                           | 28                   |                           | 
| S. ATLANTIC    | 2015      | 1         | 4                                              |                                                     | 10                                                      |                                                              | 24                                                      |                                                              | 4                                          |                                                 | 5                                          |                                                 | 40                       |                               | 84                                |                                        | 159                               |                                        | 40                   |                           | 148                  |                           | 
| DIST. OF COL.  | 2015      | 1         |                                                | -                                                   | 0                                                       |                                                              | 1                                                       |                                                              |                                            | -                                               |                                            | -                                               |                          | -                             | 0                                 |                                        | 4                                 |                                        |                      | -                         | 2                    |                           | 
| E.S. CENTRAL   | 2015      | 1         | 1                                              |                                                     | 4                                                       |                                                              | 15                                                      |                                                              | 1                                          |                                                 | 3                                          |                                                 | 20                       |                               | 30                                |                                        | 59                                |                                        | 20                   |                           | 50                   |                           | 
| W.S. CENTRAL   | 2015      | 1         | 3                                              |                                                     | 14                                                      |                                                              | 33                                                      |                                                              | 3                                          |                                                 | 1                                          |                                                 | 9                        |                               | 69                                |                                        | 249                               |                                        | 9                    |                           | 8                    |                           | 
| MOUNTAIN       | 2015      | 1         |                                                | -                                                   | 10                                                      |                                                              | 28                                                      |                                                              |                                            | -                                               | 5                                          |                                                 | 5                        |                               | 13                                |                                        | 24                                |                                        | 5                    |                           | 14                   |                           | 
```