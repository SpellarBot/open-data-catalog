# NNDSS - Table II. Cryptosporidiosis to Dengue Hemorrhagic Fever

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-cryptosporidiosis-to-dengue-hemorrhagic-fever-47c1e) |
| Metadata | [Link](https://data.cdc.gov/api/views/b36e-ru3r) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/b36e-ru3r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/b36e-ru3r/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | b36e-ru3r |
| Name | NNDSS - Table II. Cryptosporidiosis to Dengue Hemorrhagic Fever |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2014, mmwr, nndss, wonder, nedss, netss, cryptosporidiosis, dengue fever, dengue hemorrhagic fever |
| Created | 2014-03-04T20:09:59Z |
| Publication Date | 2015-01-08T16:27:31Z |

## Description

NNDSS - Table II. Cryptosporidiosis to Dengue Hemorrhagic Fever - 2014.In this Table, all conditions with a 5-year average annual national total of more than or equals 1,000 cases but less than or equals 10,000 cases will be displayed (??? 1,000 and ??_ 10,000). The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Case counts for reporting years 2013 and 2014 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. ??? Dengue Fever includes cases that meet criteria for Dengue Fever with hemorrhage, other clinical, and unknown case classifications. ?? DHF includes cases that meet criteria for dengue shock syndrome (DSS), a more severe form of DHF.More information on NNDSS is available at http://wwwn.cdc.gov/nndss/.

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                   | Data Type | Render Type |
| ======== | ============== | =================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                      | Reporting Area                                         | text      | text        |
| No       |                | mmwryear                                            | MMWRYear                                               | number    | number      |
| No       |                | mmwrweek                                            | MMWRWeek                                               | number    | number      |
| Yes      | numeric metric | cryptosporidiosis_current_week                      | Cryptosporidiosis, Current week                        | number    | number      |
| No       |                | cryptosporidiosis_current_week_flag                 | Cryptosporidiosis, Current week, flag                  | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_med             | Cryptosporidiosis, Previous 52 weeks Med               | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_med_flag        | Cryptosporidiosis, Previous 52 weeks Med, flag         | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_max             | Cryptosporidiosis, Previous 52 weeks Max               | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_max_flag        | Cryptosporidiosis, Previous 52 weeks Max, flag         | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2014                          | Cryptosporidiosis, Cum 2014                            | number    | number      |
| No       |                | cryptosporidiosis_cum_2014_flag                     | Cryptosporidiosis, Cum 2014, flag                      | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2013                          | Cryptosporidiosis, Cum 2013                            | number    | number      |
| No       |                | cryptosporidiosis_cum_2013_flag                     | Cryptosporidiosis, Cum 2013, flag                      | text      | text        |
| Yes      | numeric metric | dengue_fever_current_week                           | Dengue Fever?, Current week                            | number    | number      |
| No       |                | dengue_fever_current_week_flag                      | Dengue Fever?, Current week, flag                      | text      | text        |
| Yes      | numeric metric | dengue_fever_previous_52_weeks_med                  | Dengue Fever?, Previous 52 weeks Med                   | number    | number      |
| No       |                | dengue_fever_previous_52_weeks_med_flag             | Dengue Fever?, Previous 52 weeks Med, flag             | text      | text        |
| Yes      | numeric metric | dengue_fever_previous_52_weeks_max                  | Dengue Fever?, Previous 52 weeks Max                   | number    | number      |
| No       |                | dengue_fever_previous_52_weeks_max_flag             | Dengue Fever?, Previous 52 weeks Max, flag             | text      | text        |
| Yes      | numeric metric | dengue_fever_cum_2014                               | Dengue Fever?, Cum 2014                                | number    | number      |
| No       |                | dengue_fever_cum_2014_flag                          | Dengue Fever?, Cum 2014, flag                          | text      | text        |
| Yes      | numeric metric | dengue_fever_cum_2013                               | Dengue Fever?, Cum 2013                                | number    | number      |
| No       |                | dengue_fever_cum_2013_flag                          | Dengue Fever?, Cum 2013, flag                          | text      | text        |
| Yes      | numeric metric | dengue_hemorrhagic_fever_current_week               | Dengue Hemorrhagic Fever?, Current week                | number    | number      |
| No       |                | dengue_hemorrhagic_fever_current_week_flag          | Dengue Hemorrhagic Fever?, Current week, flag          | text      | text        |
| Yes      | numeric metric | dengue_hemorrhagic_fever_previous_52_weeks_med      | Dengue Hemorrhagic Fever?, Previous 52 weeks Med       | number    | number      |
| No       |                | dengue_hemorrhagic_fever_previous_52_weeks_med_flag | Dengue Hemorrhagic Fever?, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | dengue_hemorrhagic_fever_previous_52_weeks_max      | Dengue Hemorrhagic Fever?, Previous 52 weeks Max       | number    | number      |
| No       |                | dengue_hemorrhagic_fever_previous_52_weeks_max_flag | Dengue Hemorrhagic Fever?, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | dengue_hemorrhagic_fever_cum_2014                   | Dengue Hemorrhagic Fever?, Cum 2014                    | number    | number      |
| No       |                | dengue_hemorrhagic_fever_cum_2014_flag              | Dengue Hemorrhagic Fever?, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | dengue_hemorrhagic_fever_cum_2013                   | Dengue Hemorrhagic Fever?, Cum 2013                    | number    | number      |
| No       |                | dengue_hemorrhagic_fever_cum_2013_flag              | Dengue Hemorrhagic Fever?, Cum 2013, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwryear-mmwrweek
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = cryptosporidiosis_current_week_flag,cryptosporidiosis_previous_52_weeks_med_flag,cryptosporidiosis_previous_52_weeks_max_flag,cryptosporidiosis_cum_2014_flag,cryptosporidiosis_cum_2013_flag,dengue_fever_current_week_flag,dengue_fever_previous_52_weeks_med_flag,dengue_fever_previous_52_weeks_max_flag,dengue_fever_cum_2014_flag,dengue_fever_cum_2013_flag,dengue_hemorrhagic_fever_current_week_flag,dengue_hemorrhagic_fever_previous_52_weeks_med_flag,dengue_hemorrhagic_fever_previous_52_weeks_max_flag,dengue_hemorrhagic_fever_cum_2014_flag,dengue_hemorrhagic_fever_cum_2013_flag,mmwryear,mmwrweek
```

## Data Commands

```ls
series e:b36e-ru3r d:2013-12-29T00:00:00.000Z t:reporting_area="UNITED STATES" m:dengue_hemorrhagic_fever_previous_52_weeks_max=2 m:cryptosporidiosis_previous_52_weeks_med=102 m:cryptosporidiosis_current_week=32 m:cryptosporidiosis_previous_52_weeks_max=430 m:cryptosporidiosis_cum_2013=81 m:cryptosporidiosis_cum_2014=32 m:dengue_hemorrhagic_fever_previous_52_weeks_med=0 m:dengue_fever_previous_52_weeks_max=41 m:dengue_fever_previous_52_weeks_med=9 m:dengue_fever_cum_2013=20

series e:b36e-ru3r d:2013-12-29T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:dengue_hemorrhagic_fever_previous_52_weeks_max=0 m:cryptosporidiosis_previous_52_weeks_med=4 m:cryptosporidiosis_previous_52_weeks_max=14 m:cryptosporidiosis_cum_2013=1 m:dengue_hemorrhagic_fever_previous_52_weeks_med=0 m:dengue_fever_previous_52_weeks_max=3 m:dengue_fever_previous_52_weeks_med=0 m:dengue_fever_cum_2013=3

series e:b36e-ru3r d:2013-12-29T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:dengue_hemorrhagic_fever_previous_52_weeks_max=1 m:cryptosporidiosis_previous_52_weeks_med=12 m:cryptosporidiosis_current_week=3 m:cryptosporidiosis_previous_52_weeks_max=42 m:cryptosporidiosis_cum_2013=10 m:cryptosporidiosis_cum_2014=3 m:dengue_hemorrhagic_fever_previous_52_weeks_med=0 m:dengue_fever_previous_52_weeks_max=11 m:dengue_fever_previous_52_weeks_med=2 m:dengue_fever_cum_2013=8
```

## Meta Commands

```ls
metric m:cryptosporidiosis_current_week p:integer l:"Cryptosporidiosis, Current week" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_med p:integer l:"Cryptosporidiosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_max p:integer l:"Cryptosporidiosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2014 p:integer l:"Cryptosporidiosis, Cum 2014" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2013 p:integer l:"Cryptosporidiosis, Cum 2013" t:dataTypeName=number

metric m:dengue_fever_current_week p:integer l:"Dengue Fever?, Current week" t:dataTypeName=number

metric m:dengue_fever_previous_52_weeks_med p:integer l:"Dengue Fever?, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_fever_previous_52_weeks_max p:integer l:"Dengue Fever?, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_fever_cum_2014 p:integer l:"Dengue Fever?, Cum 2014" t:dataTypeName=number

metric m:dengue_fever_cum_2013 p:integer l:"Dengue Fever?, Cum 2013" t:dataTypeName=number

metric m:dengue_hemorrhagic_fever_current_week p:long l:"Dengue Hemorrhagic Fever?, Current week" t:dataTypeName=number

metric m:dengue_hemorrhagic_fever_previous_52_weeks_med p:integer l:"Dengue Hemorrhagic Fever?, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_hemorrhagic_fever_previous_52_weeks_max p:integer l:"Dengue Hemorrhagic Fever?, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_hemorrhagic_fever_cum_2014 p:integer l:"Dengue Hemorrhagic Fever?, Cum 2014" t:dataTypeName=number

metric m:dengue_hemorrhagic_fever_cum_2013 p:integer l:"Dengue Hemorrhagic Fever?, Cum 2013" t:dataTypeName=number

entity e:b36e-ru3r l:"NNDSS - Table II. Cryptosporidiosis to Dengue Hemorrhagic Fever" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/b36e-ru3r

property e:b36e-ru3r t:meta.view v:id=b36e-ru3r v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Cryptosporidiosis to Dengue Hemorrhagic Fever" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:b36e-ru3r t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:b36e-ru3r t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:b36e-ru3r t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwryear | mmwrweek | cryptosporidiosis_current_week | cryptosporidiosis_current_week_flag | cryptosporidiosis_previous_52_weeks_med | cryptosporidiosis_previous_52_weeks_med_flag | cryptosporidiosis_previous_52_weeks_max | cryptosporidiosis_previous_52_weeks_max_flag | cryptosporidiosis_cum_2014 | cryptosporidiosis_cum_2014_flag | cryptosporidiosis_cum_2013 | cryptosporidiosis_cum_2013_flag | dengue_fever_current_week | dengue_fever_current_week_flag | dengue_fever_previous_52_weeks_med | dengue_fever_previous_52_weeks_med_flag | dengue_fever_previous_52_weeks_max | dengue_fever_previous_52_weeks_max_flag | dengue_fever_cum_2014 | dengue_fever_cum_2014_flag | dengue_fever_cum_2013 | dengue_fever_cum_2013_flag | dengue_hemorrhagic_fever_current_week | dengue_hemorrhagic_fever_current_week_flag | dengue_hemorrhagic_fever_previous_52_weeks_med | dengue_hemorrhagic_fever_previous_52_weeks_med_flag | dengue_hemorrhagic_fever_previous_52_weeks_max | dengue_hemorrhagic_fever_previous_52_weeks_max_flag | dengue_hemorrhagic_fever_cum_2014 | dengue_hemorrhagic_fever_cum_2014_flag | dengue_hemorrhagic_fever_cum_2013 | dengue_hemorrhagic_fever_cum_2013_flag | 
| ============== | ======== | ======== | ============================== | =================================== | ======================================= | ============================================ | ======================================= | ============================================ | ========================== | =============================== | ========================== | =============================== | ========================= | ============================== | ================================== | ======================================= | ================================== | ======================================= | ===================== | ========================== | ===================== | ========================== | ===================================== | ========================================== | ============================================== | =================================================== | ============================================== | =================================================== | ================================= | ====================================== | ================================= | ====================================== | 
| UNITED STATES  | 2014     | 1        | 32                             |                                     | 102                                     |                                              | 430                                     |                                              | 32                         |                                 | 81                         |                                 |                           | -                              | 9                                  |                                         | 41                                 |                                         |                       | -                          | 20                    |                            |                                       | -                                          | 0                                              |                                                     | 2                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| NEW ENGLAND    | 2014     | 1        |                                | -                                   | 4                                       |                                              | 14                                      |                                              |                            | -                               | 1                          |                                 |                           | -                              | 0                                  |                                         | 3                                  |                                         |                       | -                          | 3                     |                            |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| MID. ATLANTIC  | 2014     | 1        | 3                              |                                     | 12                                      |                                              | 42                                      |                                              | 3                          |                                 | 10                         |                                 |                           | -                              | 2                                  |                                         | 11                                 |                                         |                       | -                          | 8                     |                            |                                       | -                                          | 0                                              |                                                     | 1                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| E.N. CENTRAL   | 2014     | 1        | 4                              |                                     | 24                                      |                                              | 60                                      |                                              | 4                          |                                 | 21                         |                                 |                           | -                              | 1                                  |                                         | 4                                  |                                         |                       | -                          |                       | -                          |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| W.N. CENTRAL   | 2014     | 1        | 2                              |                                     | 16                                      |                                              | 171                                     |                                              | 2                          |                                 | 5                          |                                 |                           | -                              | 1                                  |                                         | 3                                  |                                         |                       | -                          | 1                     |                            |                                       | -                                          | 0                                              |                                                     | 1                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| S. ATLANTIC    | 2014     | 1        | 16                             |                                     | 18                                      |                                              | 53                                      |                                              | 16                         |                                 | 12                         |                                 |                           | -                              | 1                                  |                                         | 13                                 |                                         |                       | -                          | 6                     |                            |                                       | -                                          | 0                                              |                                                     | 1                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| E.S. CENTRAL   | 2014     | 1        | 4                              |                                     | 6                                       |                                              | 17                                      |                                              | 4                          |                                 | 7                          |                                 |                           | -                              | 0                                  |                                         | 2                                  |                                         |                       | -                          |                       | -                          |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| W.S. CENTRAL   | 2014     | 1        |                                | -                                   | 10                                      |                                              | 39                                      |                                              |                            | -                               | 10                         |                                 |                           | -                              | 0                                  |                                         | 10                                 |                                         |                       | -                          |                       | -                          |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| MOUNTAIN       | 2014     | 1        | 2                              |                                     | 8                                       |                                              | 51                                      |                                              | 2                          |                                 | 8                          |                                 |                           | -                              | 0                                  |                                         | 1                                  |                                         |                       | -                          |                       | -                          |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
| PACIFIC        | 2014     | 1        | 1                              |                                     | 10                                      |                                              | 75                                      |                                              | 1                          |                                 | 7                          |                                 |                           | -                              | 1                                  |                                         | 7                                  |                                         |                       | -                          | 2                     |                            |                                       | -                                          | 0                                              |                                                     | 0                                              |                                                     |                                   | -                                      |                                   | -                                      | 
```