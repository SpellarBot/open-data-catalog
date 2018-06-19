# NNDSS - Table II. Rubella to Salmonellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-rubella-to-salmonellosis-6d572) |
| Metadata | [Link](https://data.cdc.gov/api/views/d6kj-devz) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/d6kj-devz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/d6kj-devz/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | d6kj-devz |
| Name | NNDSS - Table II. Rubella to Salmonellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, rubella, congenital syndrome, salmonellosis |
| Created | 2015-01-13T19:52:05Z |
| Publication Date | 2016-01-07T15:55:25Z |

## Description

NNDSS - Table II. Rubella to Salmonellosis - 2015.In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP: Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table 2 to facilitate case count verification with reporting jurisdictions. ??? Case counts for reporting year 2015 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly.

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
| Yes      | numeric metric | rubella_cum_2015                                       | Rubella, Cum 2015                                         | number    | number      |
| No       |                | rubella_cum_2015_flag                                  | Rubella, Cum 2015, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_cum_2014                                       | Rubella, Cum 2014                                         | number    | number      |
| No       |                | rubella_cum_2014_flag                                  | Rubella, Cum 2014, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_current_week               | Rubella, congenital syndrome, Current week                | number    | number      |
| No       |                | rubella_congenital_syndrome_current_week_flag          | Rubella, congenital syndrome, Current week, flag          | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_med      | Rubella, congenital syndrome, Previous 52 weeks Med       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_med_flag | Rubella, congenital syndrome, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_max      | Rubella, congenital syndrome, Previous 52 weeks Max       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_max_flag | Rubella, congenital syndrome, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2015                   | Rubella, congenital syndrome, Cum 2015                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2015_flag              | Rubella, congenital syndrome, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2014                   | Rubella, congenital syndrome, Cum 2014                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2014_flag              | Rubella, congenital syndrome, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | salmonellosis_current_week                             | Salmonellosis, Current week                               | number    | number      |
| No       |                | salmonellosis_current_week_flag                        | Salmonellosis, Current week, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_med                    | Salmonellosis, Previous 52 weeks Med                      | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_med_flag               | Salmonellosis, Previous 52 weeks Med, flag                | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_max                    | Salmonellosis, Previous 52 weeks Max                      | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_max_flag               | Salmonellosis, Previous 52 weeks Max, flag                | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2015                                 | Salmonellosis, Cum 2015                                   | number    | number      |
| No       |                | salmonellosis_cum_2015_flag                            | Salmonellosis, Cum 2015, flag                             | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2014                                 | Salmonellosis, Cum 2014                                   | number    | number      |
| No       |                | salmonellosis_cum_2014_flag                            | Salmonellosis, Cum 2014, flag                             | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = rubella_current_week_flag,rubella_previous_52_weeks_med_flag,rubella_previous_52_weeks_max_flag,rubella_cum_2015_flag,rubella_cum_2014_flag,rubella_congenital_syndrome_current_week_flag,rubella_congenital_syndrome_previous_52_weeks_med_flag,rubella_congenital_syndrome_previous_52_weeks_max_flag,rubella_congenital_syndrome_cum_2015_flag,rubella_congenital_syndrome_cum_2014_flag,salmonellosis_current_week_flag,salmonellosis_previous_52_weeks_med_flag,salmonellosis_previous_52_weeks_max_flag,salmonellosis_cum_2015_flag,salmonellosis_cum_2014_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:d6kj-devz d:2014-12-28T00:00:00.000Z t:reporting_area="UNITED STATES" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=1594 m:salmonellosis_cum_2014=412 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:salmonellosis_cum_2015=302 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=2 m:salmonellosis_previous_52_weeks_med=819 m:salmonellosis_current_week=302

series e:d6kj-devz d:2014-12-28T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=86 m:salmonellosis_cum_2014=16 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:salmonellosis_cum_2015=1 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=0 m:salmonellosis_previous_52_weeks_med=39 m:salmonellosis_current_week=1

series e:d6kj-devz d:2014-12-28T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:salmonellosis_previous_52_weeks_max=185 m:salmonellosis_cum_2014=50 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:salmonellosis_cum_2015=28 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=1 m:salmonellosis_previous_52_weeks_med=71 m:salmonellosis_current_week=28
```

## Meta Commands

```ls
metric m:rubella_current_week p:integer l:"Rubella, Current week" t:dataTypeName=number

metric m:rubella_previous_52_weeks_med p:integer l:"Rubella, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_previous_52_weeks_max p:integer l:"Rubella, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_cum_2015 p:integer l:"Rubella, Cum 2015" t:dataTypeName=number

metric m:rubella_cum_2014 p:integer l:"Rubella, Cum 2014" t:dataTypeName=number

metric m:rubella_congenital_syndrome_current_week p:long l:"Rubella, congenital syndrome, Current week" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_med p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_max p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2015 p:integer l:"Rubella, congenital syndrome, Cum 2015" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2014 p:integer l:"Rubella, congenital syndrome, Cum 2014" t:dataTypeName=number

metric m:salmonellosis_current_week p:integer l:"Salmonellosis, Current week" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_med p:integer l:"Salmonellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_max p:integer l:"Salmonellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:salmonellosis_cum_2015 p:integer l:"Salmonellosis, Cum 2015" t:dataTypeName=number

metric m:salmonellosis_cum_2014 p:integer l:"Salmonellosis, Cum 2014" t:dataTypeName=number

entity e:d6kj-devz l:"NNDSS - Table II. Rubella to Salmonellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/d6kj-devz

property e:d6kj-devz t:meta.view v:id=d6kj-devz v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Rubella to Salmonellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:d6kj-devz t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:d6kj-devz t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:d6kj-devz t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | rubella_current_week | rubella_current_week_flag | rubella_previous_52_weeks_med | rubella_previous_52_weeks_med_flag | rubella_previous_52_weeks_max | rubella_previous_52_weeks_max_flag | rubella_cum_2015 | rubella_cum_2015_flag | rubella_cum_2014 | rubella_cum_2014_flag | rubella_congenital_syndrome_current_week | rubella_congenital_syndrome_current_week_flag | rubella_congenital_syndrome_previous_52_weeks_med | rubella_congenital_syndrome_previous_52_weeks_med_flag | rubella_congenital_syndrome_previous_52_weeks_max | rubella_congenital_syndrome_previous_52_weeks_max_flag | rubella_congenital_syndrome_cum_2015 | rubella_congenital_syndrome_cum_2015_flag | rubella_congenital_syndrome_cum_2014 | rubella_congenital_syndrome_cum_2014_flag | salmonellosis_current_week | salmonellosis_current_week_flag | salmonellosis_previous_52_weeks_med | salmonellosis_previous_52_weeks_med_flag | salmonellosis_previous_52_weeks_max | salmonellosis_previous_52_weeks_max_flag | salmonellosis_cum_2015 | salmonellosis_cum_2015_flag | salmonellosis_cum_2014 | salmonellosis_cum_2014_flag | 
| ============== | ========= | ========= | ==================== | ========================= | ============================= | ================================== | ============================= | ================================== | ================ | ===================== | ================ | ===================== | ======================================== | ============================================= | ================================================= | ====================================================== | ================================================= | ====================================================== | ==================================== | ========================================= | ==================================== | ========================================= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2015      | 1         |                      | -                         | 0                             |                                    | 2                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 302                        |                                 | 819                                 |                                          | 1594                                |                                          | 302                    |                             | 412                    |                             | 
| NEW ENGLAND    | 2015      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 1                          |                                 | 39                                  |                                          | 86                                  |                                          | 1                      |                             | 16                     |                             | 
| MID. ATLANTIC  | 2015      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 28                         |                                 | 71                                  |                                          | 185                                 |                                          | 28                     |                             | 50                     |                             | 
| E.N. CENTRAL   | 2015      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 27                         |                                 | 95                                  |                                          | 203                                 |                                          | 27                     |                             | 49                     |                             | 
| W.N. CENTRAL   | 2015      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 14                         |                                 | 40                                  |                                          | 79                                  |                                          | 14                     |                             | 24                     |                             | 
| S. ATLANTIC    | 2015      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 152                        |                                 | 229                                 |                                          | 550                                 |                                          | 152                    |                             | 127                    |                             | 
| DIST. OF COL.  | 2015      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         |                            | -                               | 0                                   |                                          | 5                                   |                                          |                        | -                           |                        | -                           | 
| E.S. CENTRAL   | 2015      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 6                          |                                 | 57                                  |                                          | 157                                 |                                          | 6                      |                             | 30                     |                             | 
| W.S. CENTRAL   | 2015      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 32                         |                                 | 138                                 |                                          | 251                                 |                                          | 32                     |                             | 16                     |                             | 
| MOUNTAIN       | 2015      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                          | -                                             | 0                                                 |                                                        | 0                                                 |                                                        |                                      | -                                         |                                      | -                                         | 7                          |                                 | 58                                  |                                          | 91                                  |                                          | 7                      |                             | 33                     |                             | 
```