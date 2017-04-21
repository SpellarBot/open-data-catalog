# NNDSS - Table II. Tetanus to Vibriosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-tetanus-to-vibriosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/tj26-bdgd) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/tj26-bdgd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/tj26-bdgd/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | tj26-bdgd |
| Name | NNDSS - Table II. Tetanus to Vibriosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, tetanus, varicella, vibriosis |
| Created | 2016-01-12T13:57:50Z |
| Publication Date | 2017-01-05T17:39:57Z |

## Description

NNDSS - Table II. Tetanus to Vibriosis - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.  NP:  Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.

* Case counts for reporting year 2016 are provisional and subject to change.  For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf.  Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table II to facilitate case count verification with reporting jurisdictions. 
? Any species of the family Vibrionaceae, other than toxigenic Vibrio cholerae O1 or O139.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                                | Data Type | Render Type |
| ======== | ============== | =============================================== | =================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                  | Reporting Area                                      | text      | text        |
| No       |                | mmwr_year                                       | MMWR Year                                           | number    | number      |
| No       |                | mmwr_week                                       | MMWR Week                                           | number    | number      |
| Yes      | numeric metric | tetanus_current_week                            | Tetanus, Current week                               | number    | number      |
| No       |                | tetanus_current_week_flag                       | Tetanus, Current week, flag                         | text      | text        |
| Yes      | numeric metric | tetanus_previous_52_weeks_med                   | Tetanus, Previous 52 weeks Med                      | number    | number      |
| No       |                | tetanus_previous_52_weeks_med_flag              | Tetanus, Previous 52 weeks Med, flag                | text      | text        |
| Yes      | numeric metric | tetanus_previous_52_weeks_max                   | Tetanus, Previous 52 weeks Max                      | number    | number      |
| No       |                | tetanus_previous_52_weeks_max_flag              | Tetanus, Previous 52 weeks Max, flag                | text      | text        |
| Yes      | numeric metric | tetanus_cum_2016                                | Tetanus, Cum 2016                                   | number    | number      |
| No       |                | tetanus_cum_2016_flag                           | Tetanus, Cum 2016, flag                             | text      | text        |
| Yes      | numeric metric | tetanus_cum_2015                                | Tetanus, Cum 2015                                   | number    | number      |
| No       |                | tetanus_cum_2015_flag                           | Tetanus, Cum 2015, flag                             | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_current_week               | Varicella (chickenpox), Current week                | number    | number      |
| No       |                | varicella_chickenpox_current_week_flag          | Varicella (chickenpox), Current week, flag          | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_previous_52_weeks_med      | Varicella (chickenpox), Previous 52 weeks Med       | number    | number      |
| No       |                | varicella_chickenpox_previous_52_weeks_med_flag | Varicella (chickenpox), Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_previous_52_weeks_max      | Varicella (chickenpox), Previous 52 weeks Max       | number    | number      |
| No       |                | varicella_chickenpox_previous_52_weeks_max_flag | Varicella (chickenpox), Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_cum_2016                   | Varicella (chickenpox), Cum 2016                    | number    | number      |
| No       |                | varicella_chickenpox_cum_2016_flag              | Varicella (chickenpox), Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_cum_2015                   | Varicella (chickenpox), Cum 2015                    | number    | number      |
| No       |                | varicella_chickenpox_cum_2015_flag              | Varicella (chickenpox), Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | vibriosis_current_week                          | Vibriosis?, Current week                            | number    | number      |
| No       |                | vibriosis_current_week_flag                     | Vibriosis?, Current week, flag                      | text      | text        |
| Yes      | numeric metric | vibriosis_previous_52_weeks_med                 | Vibriosis?, Previous 52 weeks Med                   | number    | number      |
| No       |                | vibriosis_previous_52_weeks_med_flag            | Vibriosis?, Previous 52 weeks Med, flag             | text      | text        |
| Yes      | numeric metric | vibriosis_previous_52_weeks_max                 | Vibriosis?, Previous 52 weeks Max                   | number    | number      |
| No       |                | vibriosis_previous_52_weeks_max_flag            | Vibriosis?, Previous 52 weeks Max, flag             | text      | text        |
| Yes      | numeric metric | vibriosis_cum_2016                              | Vibriosis?, Cum 2016                                | number    | number      |
| No       |                | vibriosis_cum_2016_flag                         | Vibriosis?, Cum 2016, flag                          | text      | text        |
| Yes      | numeric metric | vibriosis_cum_2015                              | Vibriosis?, Cum 2015                                | number    | number      |
| No       |                | vibriosis_cum_2015_flag                         | Vibriosis?, Cum 2015, flag                          | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = tetanus_current_week_flag,tetanus_previous_52_weeks_med_flag,tetanus_previous_52_weeks_max_flag,tetanus_cum_2016_flag,tetanus_cum_2015_flag,varicella_chickenpox_current_week_flag,varicella_chickenpox_previous_52_weeks_med_flag,varicella_chickenpox_previous_52_weeks_max_flag,varicella_chickenpox_cum_2016_flag,varicella_chickenpox_cum_2015_flag,vibriosis_current_week_flag,vibriosis_previous_52_weeks_med_flag,vibriosis_previous_52_weeks_max_flag,vibriosis_cum_2016_flag,vibriosis_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:tj26-bdgd d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:tetanus_previous_52_weeks_max=3 m:vibriosis_previous_52_weeks_med=15 m:varicella_chickenpox_cum_2015=154 m:vibriosis_previous_52_weeks_max=68 m:tetanus_previous_52_weeks_med=0 m:varicella_chickenpox_current_week=78 m:varicella_chickenpox_previous_52_weeks_max=227 m:varicella_chickenpox_cum_2016=78 m:varicella_chickenpox_previous_52_weeks_med=172 m:tetanus_cum_2015=1 m:vibriosis_cum_2015=11

series e:tj26-bdgd d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:tetanus_previous_52_weeks_max=1 m:vibriosis_previous_52_weeks_med=1 m:varicella_chickenpox_cum_2015=20 m:vibriosis_previous_52_weeks_max=13 m:tetanus_previous_52_weeks_med=0 m:varicella_chickenpox_current_week=8 m:varicella_chickenpox_previous_52_weeks_max=27 m:varicella_chickenpox_cum_2016=8 m:varicella_chickenpox_previous_52_weeks_med=15 m:vibriosis_cum_2015=1

series e:tj26-bdgd d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:tetanus_previous_52_weeks_max=1 m:vibriosis_previous_52_weeks_med=1 m:varicella_chickenpox_cum_2015=23 m:vibriosis_previous_52_weeks_max=7 m:tetanus_previous_52_weeks_med=0 m:varicella_chickenpox_current_week=6 m:varicella_chickenpox_previous_52_weeks_max=38 m:varicella_chickenpox_cum_2016=6 m:varicella_chickenpox_previous_52_weeks_med=22 m:vibriosis_cum_2015=1
```

## Meta Commands

```ls
metric m:tetanus_current_week p:integer l:"Tetanus, Current week" t:dataTypeName=number

metric m:tetanus_previous_52_weeks_med p:integer l:"Tetanus, Previous 52 weeks Med" t:dataTypeName=number

metric m:tetanus_previous_52_weeks_max p:integer l:"Tetanus, Previous 52 weeks Max" t:dataTypeName=number

metric m:tetanus_cum_2016 p:integer l:"Tetanus, Cum 2016" t:dataTypeName=number

metric m:tetanus_cum_2015 p:integer l:"Tetanus, Cum 2015" t:dataTypeName=number

metric m:varicella_chickenpox_current_week p:integer l:"Varicella (chickenpox), Current week" t:dataTypeName=number

metric m:varicella_chickenpox_previous_52_weeks_med p:integer l:"Varicella (chickenpox), Previous 52 weeks Med" t:dataTypeName=number

metric m:varicella_chickenpox_previous_52_weeks_max p:integer l:"Varicella (chickenpox), Previous 52 weeks Max" t:dataTypeName=number

metric m:varicella_chickenpox_cum_2016 p:integer l:"Varicella (chickenpox), Cum 2016" t:dataTypeName=number

metric m:varicella_chickenpox_cum_2015 p:integer l:"Varicella (chickenpox), Cum 2015" t:dataTypeName=number

metric m:vibriosis_current_week p:integer l:"Vibriosis?, Current week" t:dataTypeName=number

metric m:vibriosis_previous_52_weeks_med p:integer l:"Vibriosis?, Previous 52 weeks Med" t:dataTypeName=number

metric m:vibriosis_previous_52_weeks_max p:integer l:"Vibriosis?, Previous 52 weeks Max" t:dataTypeName=number

metric m:vibriosis_cum_2016 p:integer l:"Vibriosis?, Cum 2016" t:dataTypeName=number

metric m:vibriosis_cum_2015 p:integer l:"Vibriosis?, Cum 2015" t:dataTypeName=number

entity e:tj26-bdgd l:"NNDSS - Table II. Tetanus to Vibriosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/tj26-bdgd

property e:tj26-bdgd t:meta.view v:id=tj26-bdgd v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Tetanus to Vibriosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:tj26-bdgd t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:tj26-bdgd t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:tj26-bdgd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | tetanus_current_week | tetanus_current_week_flag | tetanus_previous_52_weeks_med | tetanus_previous_52_weeks_med_flag | tetanus_previous_52_weeks_max | tetanus_previous_52_weeks_max_flag | tetanus_cum_2016 | tetanus_cum_2016_flag | tetanus_cum_2015 | tetanus_cum_2015_flag | varicella_chickenpox_current_week | varicella_chickenpox_current_week_flag | varicella_chickenpox_previous_52_weeks_med | varicella_chickenpox_previous_52_weeks_med_flag | varicella_chickenpox_previous_52_weeks_max | varicella_chickenpox_previous_52_weeks_max_flag | varicella_chickenpox_cum_2016 | varicella_chickenpox_cum_2016_flag | varicella_chickenpox_cum_2015 | varicella_chickenpox_cum_2015_flag | vibriosis_current_week | vibriosis_current_week_flag | vibriosis_previous_52_weeks_med | vibriosis_previous_52_weeks_med_flag | vibriosis_previous_52_weeks_max | vibriosis_previous_52_weeks_max_flag | vibriosis_cum_2016 | vibriosis_cum_2016_flag | vibriosis_cum_2015 | vibriosis_cum_2015_flag | 
| ============== | ========= | ========= | ==================== | ========================= | ============================= | ================================== | ============================= | ================================== | ================ | ===================== | ================ | ===================== | ================================= | ====================================== | ========================================== | =============================================== | ========================================== | =============================================== | ============================= | ================================== | ============================= | ================================== | ====================== | =========================== | =============================== | ==================================== | =============================== | ==================================== | ================== | ======================= | ================== | ======================= | 
| UNITED STATES  | 2016      | 1         |                      | -                         | 0                             |                                    | 3                             |                                    |                  | -                     | 1                |                       | 78                                |                                        | 172                                        |                                                 | 227                                        |                                                 | 78                            |                                    | 154                           |                                    |                        | -                           | 15                              |                                      | 68                              |                                      |                    | -                       | 11                 |                         | 
| NEW ENGLAND    | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 8                                 |                                        | 15                                         |                                                 | 27                                         |                                                 | 8                             |                                    | 20                            |                                    |                        | -                           | 1                               |                                      | 13                              |                                      |                    | -                       | 1                  |                         | 
| MID. ATLANTIC  | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 6                                 |                                        | 22                                         |                                                 | 38                                         |                                                 | 6                             |                                    | 23                            |                                    |                        | -                           | 1                               |                                      | 7                               |                                      |                    | -                       | 1                  |                         | 
| NEW YORK CITY  | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                   | -                                      | 0                                          |                                                 | 0                                          |                                                 |                               | -                                  |                               | -                                  |                        | -                           | 0                               |                                      | 3                               |                                      |                    | -                       | 1                  |                         | 
| E.N. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 35                                |                                        | 36                                         |                                                 | 65                                         |                                                 | 35                            |                                    | 37                            |                                    |                        | -                           | 1                               |                                      | 6                               |                                      |                    | -                       | 1                  |                         | 
| W.N. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 7                                 |                                        | 10                                         |                                                 | 23                                         |                                                 | 7                             |                                    | 14                            |                                    |                        | -                           | 0                               |                                      | 2                               |                                      |                    | -                       |                    | -                       | 
| S. ATLANTIC    | 2016      | 1         |                      | -                         | 0                             |                                    | 2                             |                                    |                  | -                     | 1                |                       | 12                                |                                        | 29                                         |                                                 | 50                                         |                                                 | 12                            |                                    | 34                            |                                    |                        | -                           | 7                               |                                      | 14                              |                                      |                    | -                       | 5                  |                         | 
| DIST. OF COL.  | 2016      | 1         |                      | -                         | 0                             |                                    | 0                             |                                    |                  | -                     |                  | -                     |                                   | -                                      | 0                                          |                                                 | 0                                          |                                                 |                               | -                                  |                               | -                                  |                        | -                           | 0                               |                                      | 0                               |                                      |                    | -                       |                    | -                       | 
| E.S. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                   | -                                      | 3                                          |                                                 | 11                                         |                                                 |                               | -                                  | 5                             |                                    |                        | -                           | 0                               |                                      | 4                               |                                      |                    | -                       |                    | -                       | 
| W.S. CENTRAL   | 2016      | 1         |                      | -                         | 0                             |                                    | 2                             |                                    |                  | -                     |                  | -                     | 4                                 |                                        | 31                                         |                                                 | 76                                         |                                                 | 4                             |                                    | 6                             |                                    |                        | -                           | 2                               |                                      | 8                               |                                      |                    | -                       | 1                  |                         | 
```