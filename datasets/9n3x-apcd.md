# NNDSS - Table II. Cryptosporidiosis to Dengue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-cryptosporidiosis-to-dengue-97c83) |
| Metadata | [Link](https://data.cdc.gov/api/views/9n3x-apcd) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/9n3x-apcd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/9n3x-apcd/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 9n3x-apcd |
| Name | NNDSS - Table II. Cryptosporidiosis to Dengue |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, cryptosporidiosis, dengue virus infection, dengue, severe dengue |
| Created | 2015-01-13T18:58:12Z |
| Publication Date | 2016-01-07T15:26:59Z |

## Description

NNDSS - Table II. Cryptosporidiosis to Dengue - 2015.In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP: Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table 2 to facilitate case count verification with reporting jurisdictions. ??? Case counts for reporting year 2015 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. ?? Data for dengue-like illness will be included in this table after the CDC obtains Office of Management and Budget (OMB) Paperwork Reduction Act (PRA) to receive data for this condition.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                               | Reporting Area                                 | text      | text        |
| No       |                | mmwryear                                     | MMWRYear                                       | number    | number      |
| No       |                | mmwrweek                                     | MMWRWeek                                       | number    | number      |
| Yes      | numeric metric | cryptosporidiosis_current_week               | Cryptosporidiosis, Current week                | number    | number      |
| No       |                | cryptosporidiosis_current_week_flag          | Cryptosporidiosis, Current week, flag          | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_med      | Cryptosporidiosis, Previous 52 weeks Med       | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_med_flag | Cryptosporidiosis, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_max      | Cryptosporidiosis, Previous 52 weeks Max       | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_max_flag | Cryptosporidiosis, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2015                   | Cryptosporidiosis, Cum 2015                    | number    | number      |
| No       |                | cryptosporidiosis_cum_2015_flag              | Cryptosporidiosis, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2014                   | Cryptosporidiosis, Cum 2014                    | number    | number      |
| No       |                | cryptosporidiosis_cum_2014_flag              | Cryptosporidiosis, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | dengue_current_week                          | Dengue?, Current week                          | number    | number      |
| No       |                | dengue_current_week_flag                     | Dengue?, Current week, flag                    | text      | text        |
| Yes      | numeric metric | dengue_previous_52_weeks_med                 | Dengue?, Previous 52 weeks Med                 | number    | number      |
| No       |                | dengue_previous_52_weeks_med_flag            | Dengue?, Previous 52 weeks Med, flag           | text      | text        |
| Yes      | numeric metric | dengue_previous_52_weeks_max                 | Dengue?, Previous 52 weeks Max                 | number    | number      |
| No       |                | dengue_previous_52_weeks_max_flag            | Dengue?, Previous 52 weeks Max, flag           | text      | text        |
| Yes      | numeric metric | dengue_cum_2015                              | Dengue?, Cum 2015                              | number    | number      |
| No       |                | dengue_cum_2015_flag                         | Dengue?, Cum 2015, flag                        | text      | text        |
| Yes      | numeric metric | dengue_cum_2014                              | Dengue?, Cum 2014                              | number    | number      |
| No       |                | dengue_cum_2014_flag                         | Dengue?, Cum 2014, flag                        | text      | text        |
| Yes      | numeric metric | dengue_severe_current_week                   | Dengue Severe, Current week                    | number    | number      |
| No       |                | dengue_severe_current_week_flag              | Dengue Severe, Current week, flag              | text      | text        |
| Yes      | numeric metric | dengue_severe_previous_52_weeks_med          | Dengue Severe, Previous 52 weeks Med           | number    | number      |
| No       |                | dengue_severe_previous_52_weeks_med_flag     | Dengue Severe, Previous 52 weeks Med, flag     | text      | text        |
| Yes      | numeric metric | dengue_severe_previous_52_weeks_max          | Dengue Severe, Previous 52 weeks Max           | number    | number      |
| No       |                | dengue_severe_previous_52_weeks_max_flag     | Dengue Severe, Previous 52 weeks Max, flag     | text      | text        |
| Yes      | numeric metric | dengue_severe_cum_2015                       | Dengue Severe, Cum 2015                        | number    | number      |
| No       |                | dengue_severe_cum_2015_flag                  | Dengue Severe, Cum 2015, flag                  | text      | text        |
| Yes      | numeric metric | dengue_severe_cum_2014                       | Dengue Severe, Cum 2014                        | number    | number      |
| No       |                | dengue_severe_cum_2014_flag                  | Dengue Severe, Cum 2014, flag                  | text      | text        |
```

## Time Field

```ls
Value = mmwryear-mmwrweek
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = cryptosporidiosis_current_week_flag,cryptosporidiosis_previous_52_weeks_med_flag,cryptosporidiosis_previous_52_weeks_max_flag,cryptosporidiosis_cum_2015_flag,cryptosporidiosis_cum_2014_flag,dengue_current_week_flag,dengue_previous_52_weeks_med_flag,dengue_previous_52_weeks_max_flag,dengue_cum_2015_flag,dengue_cum_2014_flag,dengue_severe_current_week_flag,dengue_severe_previous_52_weeks_med_flag,dengue_severe_previous_52_weeks_max_flag,dengue_severe_cum_2015_flag,dengue_severe_cum_2014_flag,mmwryear,mmwrweek
```

## Data Commands

```ls
series e:9n3x-apcd d:2014-12-28T00:00:00.000Z t:reporting_area="UNITED STATES" m:cryptosporidiosis_previous_52_weeks_med=112 m:cryptosporidiosis_current_week=75 m:dengue_severe_previous_52_weeks_med=0 m:dengue_cum_2014=9 m:cryptosporidiosis_previous_52_weeks_max=334 m:cryptosporidiosis_cum_2015=75 m:dengue_previous_52_weeks_med=8 m:cryptosporidiosis_cum_2014=61 m:dengue_previous_52_weeks_max=23 m:dengue_severe_previous_52_weeks_max=0

series e:9n3x-apcd d:2014-12-28T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:cryptosporidiosis_previous_52_weeks_med=5 m:dengue_severe_previous_52_weeks_med=0 m:cryptosporidiosis_previous_52_weeks_max=17 m:dengue_previous_52_weeks_med=0 m:cryptosporidiosis_cum_2014=4 m:dengue_previous_52_weeks_max=3 m:dengue_severe_previous_52_weeks_max=0

series e:9n3x-apcd d:2014-12-28T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:cryptosporidiosis_previous_52_weeks_med=11 m:cryptosporidiosis_current_week=3 m:dengue_severe_previous_52_weeks_med=0 m:dengue_cum_2014=1 m:cryptosporidiosis_previous_52_weeks_max=34 m:cryptosporidiosis_cum_2015=3 m:dengue_previous_52_weeks_med=2 m:cryptosporidiosis_cum_2014=7 m:dengue_previous_52_weeks_max=9 m:dengue_severe_previous_52_weeks_max=0
```

## Meta Commands

```ls
metric m:cryptosporidiosis_current_week p:integer l:"Cryptosporidiosis, Current week" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_med p:integer l:"Cryptosporidiosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_max p:integer l:"Cryptosporidiosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2015 p:integer l:"Cryptosporidiosis, Cum 2015" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2014 p:integer l:"Cryptosporidiosis, Cum 2014" t:dataTypeName=number

metric m:dengue_current_week p:integer l:"Dengue?, Current week" t:dataTypeName=number

metric m:dengue_previous_52_weeks_med p:integer l:"Dengue?, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_previous_52_weeks_max p:integer l:"Dengue?, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_cum_2015 p:integer l:"Dengue?, Cum 2015" t:dataTypeName=number

metric m:dengue_cum_2014 p:integer l:"Dengue?, Cum 2014" t:dataTypeName=number

metric m:dengue_severe_current_week p:long l:"Dengue Severe, Current week" t:dataTypeName=number

metric m:dengue_severe_previous_52_weeks_med p:integer l:"Dengue Severe, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_severe_previous_52_weeks_max p:integer l:"Dengue Severe, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_severe_cum_2015 p:long l:"Dengue Severe, Cum 2015" t:dataTypeName=number

metric m:dengue_severe_cum_2014 p:integer l:"Dengue Severe, Cum 2014" t:dataTypeName=number

entity e:9n3x-apcd l:"NNDSS - Table II. Cryptosporidiosis to Dengue" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/9n3x-apcd

property e:9n3x-apcd t:meta.view v:id=9n3x-apcd v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Cryptosporidiosis to Dengue" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:9n3x-apcd t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:9n3x-apcd t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:9n3x-apcd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwryear | mmwrweek | cryptosporidiosis_current_week | cryptosporidiosis_current_week_flag | cryptosporidiosis_previous_52_weeks_med | cryptosporidiosis_previous_52_weeks_med_flag | cryptosporidiosis_previous_52_weeks_max | cryptosporidiosis_previous_52_weeks_max_flag | cryptosporidiosis_cum_2015 | cryptosporidiosis_cum_2015_flag | cryptosporidiosis_cum_2014 | cryptosporidiosis_cum_2014_flag | dengue_current_week | dengue_current_week_flag | dengue_previous_52_weeks_med | dengue_previous_52_weeks_med_flag | dengue_previous_52_weeks_max | dengue_previous_52_weeks_max_flag | dengue_cum_2015 | dengue_cum_2015_flag | dengue_cum_2014 | dengue_cum_2014_flag | dengue_severe_current_week | dengue_severe_current_week_flag | dengue_severe_previous_52_weeks_med | dengue_severe_previous_52_weeks_med_flag | dengue_severe_previous_52_weeks_max | dengue_severe_previous_52_weeks_max_flag | dengue_severe_cum_2015 | dengue_severe_cum_2015_flag | dengue_severe_cum_2014 | dengue_severe_cum_2014_flag | 
| ============== | ======== | ======== | ============================== | =================================== | ======================================= | ============================================ | ======================================= | ============================================ | ========================== | =============================== | ========================== | =============================== | =================== | ======================== | ============================ | ================================= | ============================ | ================================= | =============== | ==================== | =============== | ==================== | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2015     | 1        | 75                             |                                     | 112                                     |                                              | 334                                     |                                              | 75                         |                                 | 61                         |                                 |                     | -                        | 8                            |                                   | 23                           |                                   |                 | -                    | 9               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| NEW ENGLAND    | 2015     | 1        |                                | -                                   | 5                                       |                                              | 17                                      |                                              |                            | -                               | 4                          |                                 |                     | -                        | 0                            |                                   | 3                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| MID. ATLANTIC  | 2015     | 1        | 3                              |                                     | 11                                      |                                              | 34                                      |                                              | 3                          |                                 | 7                          |                                 |                     | -                        | 2                            |                                   | 9                            |                                   |                 | -                    | 1               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| E.N. CENTRAL   | 2015     | 1        | 6                              |                                     | 21                                      |                                              | 69                                      |                                              | 6                          |                                 | 16                         |                                 |                     | -                        | 0                            |                                   | 3                            |                                   |                 | -                    | 1               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| W.N. CENTRAL   | 2015     | 1        | 5                              |                                     | 14                                      |                                              | 39                                      |                                              | 5                          |                                 | 7                          |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| S. ATLANTIC    | 2015     | 1        | 45                             |                                     | 29                                      |                                              | 150                                     |                                              | 45                         |                                 | 12                         |                                 |                     | -                        | 2                            |                                   | 6                            |                                   |                 | -                    | 3               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| DIST. OF COL.  | 2015     | 1        |                                | -                                   | 0                                       |                                              | 1                                       |                                              |                            | -                               |                            | -                               |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| E.S. CENTRAL   | 2015     | 1        | 11                             |                                     | 6                                       |                                              | 17                                      |                                              | 11                         |                                 | 5                          |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| W.S. CENTRAL   | 2015     | 1        | 3                              |                                     | 12                                      |                                              | 31                                      |                                              | 3                          |                                 | 2                          |                                 |                     | -                        | 0                            |                                   | 3                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| MOUNTAIN       | 2015     | 1        | 2                              |                                     | 7                                       |                                              | 21                                      |                                              | 2                          |                                 | 4                          |                                 |                     | -                        | 0                            |                                   | 11                           |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
```