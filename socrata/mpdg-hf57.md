# NNDSS - Table II. Giardiasis to Haemophilus influenza

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-giardiasis-to-haemophilus-influenza-5cf59) |
| Metadata | [Link](https://data.cdc.gov/api/views/mpdg-hf57) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/mpdg-hf57/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/mpdg-hf57/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | mpdg-hf57 |
| Name | NNDSS - Table II. Giardiasis to Haemophilus influenza |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, giardiasis, gonorrhea, haemophilus influenzae |
| Created | 2015-01-13T19:13:48Z |
| Publication Date | 2016-01-07T15:36:10Z |

## Description

NNDSS - Table II. Giardiasis to Haemophilus influenza - 2015.In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP: Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table 2 to facilitate case count verification with reporting jurisdictions. ??? Case counts for reporting year 2015 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. ?? Data for H. influenzae (age <5 years for serotype b, nonserotype b, and unknown serotype) are available in Table I.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                        | Name                                                                                    | Data Type | Render Type |
| ======== | ============== | ================================================================================= | ======================================================================================= | ========= | =========== |
| Yes      | series tag     | reporting_area                                                                    | Reporting Area                                                                          | text      | text        |
| No       |                | mmwr_year                                                                         | MMWR Year                                                                               | number    | number      |
| No       |                | mmwr_week                                                                         | MMWR Week                                                                               | number    | number      |
| Yes      | numeric metric | giardiasis_current_week                                                           | Giardiasis, Current week                                                                | number    | number      |
| No       |                | giardiasis_current_week_flag                                                      | Giardiasis, Current week, flag                                                          | text      | text        |
| Yes      | numeric metric | giardiasis_previous_52_weeks_med                                                  | Giardiasis, Previous 52 weeks Med                                                       | number    | number      |
| Yes      | numeric metric | giardiasis_previous_52_weeks_max                                                  | Giardiasis, Previous 52 weeks Max                                                       | number    | number      |
| No       |                | giardiasis_previous_52_weeks_med_flag                                             | Giardiasis, Previous 52 weeks Med, flag                                                 | text      | text        |
| No       |                | giardiasis_previous_52_weeks_max_flag                                             | Giardiasis, Previous 52 weeks Max, flag                                                 | text      | text        |
| Yes      | numeric metric | giardiasis_cum_2015                                                               | Giardiasis, Cum 2015                                                                    | number    | number      |
| No       |                | giardiasis_cum_2015_flag                                                          | Giardiasis, Cum 2015, flag                                                              | text      | text        |
| Yes      | numeric metric | giardiasis_cum_2014                                                               | Giardiasis, Cum 2014                                                                    | number    | number      |
| No       |                | giardiasis_cum_2014_flag                                                          | Giardiasis, Cum 2014, flag                                                              | text      | text        |
| Yes      | numeric metric | gonorrhea_current_week                                                            | Gonorrhea,Current week                                                                  | number    | number      |
| No       |                | gonorrhea_current_week_flag                                                       | Gonorrhea,Current week, flag                                                            | text      | text        |
| Yes      | numeric metric | gonorrhea_previous_52_weeks_med                                                   | Gonorrhea,Previous 52 weeks Med                                                         | number    | number      |
| No       |                | gonorrhea_previous_52_weeks_med_flag                                              | Gonorrhea,Previous 52 weeks Med, flag                                                   | text      | text        |
| Yes      | numeric metric | gonorrhea_previous_52_weeks_max                                                   | Gonorrhea, Previous 52 weeks Max                                                        | number    | number      |
| No       |                | gonorrhea_previous_52_weeks_max_flag                                              | Gonorrhea, Previous 52 weeks Max, flag                                                  | text      | text        |
| Yes      | numeric metric | gonorrhea_cum_2015                                                                | Gonorrhea, Cum 2015                                                                     | number    | number      |
| No       |                | gonorrhea_cum_2015_flag                                                           | Gonorrhea, Cum 2015, flag                                                               | text      | text        |
| Yes      | numeric metric | gonorrhea_cum_2014                                                                | Gonorrhea, Cum 2014                                                                     | number    | number      |
| No       |                | gonorrhea_cum_2014_flag                                                           | Gonorrhea, Cum 2014, flag                                                               | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week               | Haemophilus influenzae, invasive?, All ages, all serotypes,Current week                 | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag          | Haemophilus influenzae, invasive?, All ages, all serotypes,Current week, flag           | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med      | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med       | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max      | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max       | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015                   | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015                    | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag              | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014                   | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2014                    | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014_flag              | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2014, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = giardiasis_current_week_flag,giardiasis_previous_52_weeks_med_flag,giardiasis_previous_52_weeks_max_flag,giardiasis_cum_2015_flag,giardiasis_cum_2014_flag,gonorrhea_current_week_flag,gonorrhea_previous_52_weeks_med_flag,gonorrhea_previous_52_weeks_max_flag,gonorrhea_cum_2015_flag,gonorrhea_cum_2014_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:mpdg-hf57 d:2014-12-28T00:00:00.000Z t:reporting_area="UNITED STATES" m:gonorrhea_cum_2015=2906 m:gonorrhea_cum_2014=5371 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=90 m:gonorrhea_current_week=2906 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014=85 m:giardiasis_previous_52_weeks_med=234 m:giardiasis_cum_2014=156 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=51 m:giardiasis_previous_52_weeks_max=390 m:giardiasis_current_week=89 m:giardiasis_cum_2015=89 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=60 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=51 m:gonorrhea_previous_52_weeks_max=7209 m:gonorrhea_previous_52_weeks_med=6438

series e:mpdg-hf57 d:2014-12-28T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:gonorrhea_cum_2015=1 m:gonorrhea_cum_2014=170 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=10 m:gonorrhea_current_week=1 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014=4 m:giardiasis_previous_52_weeks_med=25 m:giardiasis_cum_2014=13 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=1 m:giardiasis_previous_52_weeks_max=49 m:giardiasis_current_week=2 m:giardiasis_cum_2015=2 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=4 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=1 m:gonorrhea_previous_52_weeks_max=190 m:gonorrhea_previous_52_weeks_med=133

series e:mpdg-hf57 d:2014-12-28T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:gonorrhea_cum_2015=301 m:gonorrhea_cum_2014=477 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=19 m:gonorrhea_current_week=301 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014=16 m:giardiasis_previous_52_weeks_med=47 m:giardiasis_cum_2014=36 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=11 m:giardiasis_previous_52_weeks_max=75 m:giardiasis_current_week=23 m:giardiasis_cum_2015=23 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=10 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=11 m:gonorrhea_previous_52_weeks_max=952 m:gonorrhea_previous_52_weeks_med=746
```

## Meta Commands

```ls
metric m:giardiasis_current_week p:integer l:"Giardiasis, Current week" t:dataTypeName=number

metric m:giardiasis_previous_52_weeks_med p:integer l:"Giardiasis, Previous 52 weeks Med" t:dataTypeName=number

metric m:giardiasis_previous_52_weeks_max p:integer l:"Giardiasis, Previous 52 weeks Max" t:dataTypeName=number

metric m:giardiasis_cum_2015 p:integer l:"Giardiasis, Cum 2015" t:dataTypeName=number

metric m:giardiasis_cum_2014 p:integer l:"Giardiasis, Cum 2014" t:dataTypeName=number

metric m:gonorrhea_current_week p:integer l:"Gonorrhea,Current week" t:dataTypeName=number

metric m:gonorrhea_previous_52_weeks_med p:integer l:"Gonorrhea,Previous 52 weeks Med" t:dataTypeName=number

metric m:gonorrhea_previous_52_weeks_max p:integer l:"Gonorrhea, Previous 52 weeks Max" t:dataTypeName=number

metric m:gonorrhea_cum_2015 p:integer l:"Gonorrhea, Cum 2015" t:dataTypeName=number

metric m:gonorrhea_cum_2014 p:integer l:"Gonorrhea, Cum 2014" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes,Current week" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015 p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014 p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2014" t:dataTypeName=number

entity e:mpdg-hf57 l:"NNDSS - Table II. Giardiasis to Haemophilus influenza" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/mpdg-hf57

property e:mpdg-hf57 t:meta.view v:id=mpdg-hf57 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Giardiasis to Haemophilus influenza" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:mpdg-hf57 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:mpdg-hf57 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:mpdg-hf57 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | giardiasis_current_week | giardiasis_current_week_flag | giardiasis_previous_52_weeks_med | giardiasis_previous_52_weeks_max | giardiasis_previous_52_weeks_med_flag | giardiasis_previous_52_weeks_max_flag | giardiasis_cum_2015 | giardiasis_cum_2015_flag | giardiasis_cum_2014 | giardiasis_cum_2014_flag | gonorrhea_current_week | gonorrhea_current_week_flag | gonorrhea_previous_52_weeks_med | gonorrhea_previous_52_weeks_med_flag | gonorrhea_previous_52_weeks_max | gonorrhea_previous_52_weeks_max_flag | gonorrhea_cum_2015 | gonorrhea_cum_2015_flag | gonorrhea_cum_2014 | gonorrhea_cum_2014_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015 | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014 | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2014_flag | 
| ============== | ========= | ========= | ======================= | ============================ | ================================ | ================================ | ===================================== | ===================================== | =================== | ======================== | =================== | ======================== | ====================== | =========================== | =============================== | ==================================== | =============================== | ==================================== | ================== | ======================= | ================== | ======================= | =================================================================== | ======================================================================== | ============================================================================ | ================================================================================= | ============================================================================ | ================================================================================= | =============================================================== | ==================================================================== | =============================================================== | ==================================================================== | 
| UNITED STATES  | 2015      | 1         | 89                      |                              | 234                              | 390                              |                                       |                                       | 89                  |                          | 156                 |                          | 2906                   |                             | 6438                            |                                      | 7209                            |                                      | 2906               |                         | 5371               |                         | 51                                                                  |                                                                          | 60                                                                           |                                                                                   | 90                                                                           |                                                                                   | 51                                                              |                                                                      | 85                                                              |                                                                      | 
| NEW ENGLAND    | 2015      | 1         | 2                       |                              | 25                               | 49                               |                                       |                                       | 2                   |                          | 13                  |                          | 1                      |                             | 133                             |                                      | 190                             |                                      | 1                  |                         | 170                |                         | 1                                                                   |                                                                          | 4                                                                            |                                                                                   | 10                                                                           |                                                                                   | 1                                                               |                                                                      | 4                                                               |                                                                      | 
| MID. ATLANTIC  | 2015      | 1         | 23                      |                              | 47                               | 75                               |                                       |                                       | 23                  |                          | 36                  |                          | 301                    |                             | 746                             |                                      | 952                             |                                      | 301                |                         | 477                |                         | 11                                                                  |                                                                          | 10                                                                           |                                                                                   | 19                                                                           |                                                                                   | 11                                                              |                                                                      | 16                                                              |                                                                      | 
| E.N. CENTRAL   | 2015      | 1         | 10                      |                              | 27                               | 53                               |                                       |                                       | 10                  |                          | 22                  |                          | 332                    |                             | 911                             |                                      | 1196                            |                                      | 332                |                         | 620                |                         | 13                                                                  |                                                                          | 8                                                                            |                                                                                   | 19                                                                           |                                                                                   | 13                                                              |                                                                      | 14                                                              |                                                                      | 
| W.N. CENTRAL   | 2015      | 1         | 3                       |                              | 15                               | 38                               |                                       |                                       | 3                   |                          | 8                   |                          | 186                    |                             | 355                             |                                      | 416                             |                                      | 186                |                         | 262                |                         |                                                                     | -                                                                        | 5                                                                            |                                                                                   | 10                                                                           |                                                                                   |                                                                 | -                                                                    | 14                                                              |                                                                      | 
| S. ATLANTIC    | 2015      | 1         | 23                      |                              | 47                               | 89                               |                                       |                                       | 23                  |                          | 36                  |                          | 781                    |                             | 1390                            |                                      | 1759                            |                                      | 781                |                         | 1190               |                         | 15                                                                  |                                                                          | 15                                                                           |                                                                                   | 26                                                                           |                                                                                   | 15                                                              |                                                                      | 14                                                              |                                                                      | 
| DIST. OF COL.  | 2015      | 1         |                         | -                            | 1                                | 3                                |                                       |                                       |                     | -                        |                     | -                        |                        | -                           | 0                               |                                      | 0                               |                                      |                    | -                       |                    | -                       |                                                                     | -                                                                        | 0                                                                            |                                                                                   | 1                                                                            |                                                                                   |                                                                 | -                                                                    |                                                                 | -                                                                    | 
| E.S. CENTRAL   | 2015      | 1         |                         | -                            | 3                                | 10                               |                                       |                                       |                     | -                        |                     | -                        | 70                     |                             | 463                             |                                      | 649                             |                                      | 70                 |                         | 526                |                         | 7                                                                   |                                                                          | 4                                                                            |                                                                                   | 9                                                                            |                                                                                   | 7                                                               |                                                                      | 7                                                               |                                                                      | 
| W.S. CENTRAL   | 2015      | 1         | 3                       |                              | 6                                | 19                               |                                       |                                       | 3                   |                          | 3                   |                          | 924                    |                             | 1026                            |                                      | 1363                            |                                      | 924                |                         | 800                |                         | 3                                                                   |                                                                          | 4                                                                            |                                                                                   | 10                                                                           |                                                                                   | 3                                                               |                                                                      | 2                                                               |                                                                      | 
| MOUNTAIN       | 2015      | 1         | 3                       |                              | 20                               | 43                               |                                       |                                       | 3                   |                          | 10                  |                          | 86                     |                             | 338                             |                                      | 436                             |                                      | 86                 |                         | 365                |                         |                                                                     | -                                                                        | 6                                                                            |                                                                                   | 13                                                                           |                                                                                   |                                                                 | -                                                                    | 11                                                              |                                                                      | 
```