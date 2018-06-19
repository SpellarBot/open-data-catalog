# NNDSS - Table II. Cryptosporidiosis to Dengue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-cryptosporidiosis-to-dengue) |
| Metadata | [Link](https://data.cdc.gov/api/views/kikd-77zw) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/kikd-77zw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/kikd-77zw/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | kikd-77zw |
| Name | NNDSS - Table II. Cryptosporidiosis to Dengue |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, cryptosporidiosis, dengue virus infection, dengue, severe dengue |
| Created | 2016-01-11T20:40:30Z |
| Publication Date | 2017-01-05T16:53:38Z |

## Description

NNDSS - Table II. Cryptosporidiosis to Dengue - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP:  Nationally notifiable but not published.  Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.

* Case counts for reporting year 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf.   Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 
? Includes data for dengue and dengue-like illness. Office of Management and Budget approval of the NNDSS Revision #0920-0728 on January 21, 2016, authorized CDC to receive data for these conditions. CDC is in the process of soliciting data for these conditions.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                               | Reporting Area                                 | text      | text        |
| No       |                | mmwryear                                     | MMWR Year                                      | number    | number      |
| No       |                | mmwrweek                                     | MMWR Week                                      | number    | number      |
| Yes      | numeric metric | cryptosporidiosis_current_week               | Cryptosporidiosis, Current week                | number    | number      |
| No       |                | cryptosporidiosis_current_week_flag          | Cryptosporidiosis, Current week, flag          | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_med      | Cryptosporidiosis, Previous 52 weeks Med       | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_med_flag | Cryptosporidiosis, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_previous_52_weeks_max      | Cryptosporidiosis, Previous 52 weeks Max       | number    | number      |
| No       |                | cryptosporidiosis_previous_52_weeks_max_flag | Cryptosporidiosis, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2016                   | Cryptosporidiosis, Cum 2016                    | number    | number      |
| No       |                | cryptosporidiosis_cum_2016_flag              | Cryptosporidiosis, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | cryptosporidiosis_cum_2015                   | Cryptosporidiosis, Cum 2015                    | number    | number      |
| No       |                | cryptosporidiosis_cum_2015_flag              | Cryptosporidiosis, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | dengue_current_week                          | Dengue?, Current week                          | number    | number      |
| No       |                | dengue_current_week_flag                     | Dengue?, Current week, flag                    | text      | text        |
| Yes      | numeric metric | dengue_previous_52_weeks_med                 | Dengue?, Previous 52 weeks Med                 | number    | number      |
| No       |                | dengue_previous_52_weeks_med_flag            | Dengue?, Previous 52 weeks Med, flag           | text      | text        |
| Yes      | numeric metric | dengue_previous_52_weeks_max                 | Dengue?, Previous 52 weeks Max                 | number    | number      |
| No       |                | dengue_previous_52_weeks_max_flag            | Dengue?, Previous 52 weeks Max, flag           | text      | text        |
| Yes      | numeric metric | dengue_cum_2016                              | Dengue?, Cum 2016                              | number    | number      |
| No       |                | dengue_cum_2016_flag                         | Dengue?, Cum 2016, flag                        | text      | text        |
| Yes      | numeric metric | dengue_cum_2015                              | Dengue?, Cum 2015                              | number    | number      |
| No       |                | dengue_cum_2015_flag                         | Dengue?, Cum 2015, flag                        | text      | text        |
| Yes      | numeric metric | dengue_severe_current_week                   | Dengue Severe, Current week                    | number    | number      |
| No       |                | dengue_severe_current_week_flag              | Dengue Severe, Current week, flag              | text      | text        |
| Yes      | numeric metric | dengue_severe_previous_52_weeks_med          | Dengue Severe, Previous 52 weeks Med           | number    | number      |
| No       |                | dengue_severe_previous_52_weeks_med_flag     | Dengue Severe, Previous 52 weeks Med, flag     | text      | text        |
| Yes      | numeric metric | dengue_severe_previous_52_weeks_max          | Dengue Severe, Previous 52 weeks Max           | number    | number      |
| No       |                | dengue_severe_previous_52_weeks_max_flag     | Dengue Severe, Previous 52 weeks Max, flag     | text      | text        |
| Yes      | numeric metric | dengue_severe_cum_2016                       | Dengue Severe, Cum 2016                        | number    | number      |
| No       |                | dengue_severe_cum_2016_flag                  | Dengue Severe, Cum 2016, flag                  | text      | text        |
| Yes      | numeric metric | dengue_severe_cum_2015                       | Dengue Severe, Cum 2015                        | number    | number      |
| No       |                | dengue_severe_cum_2015_flag                  | Dengue Severe, Cum 2015, flag                  | text      | text        |
```

## Time Field

```ls
Value = mmwryear-mmwrweek
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = cryptosporidiosis_current_week_flag,cryptosporidiosis_previous_52_weeks_med_flag,cryptosporidiosis_previous_52_weeks_max_flag,cryptosporidiosis_cum_2016_flag,cryptosporidiosis_cum_2015_flag,dengue_current_week_flag,dengue_previous_52_weeks_med_flag,dengue_previous_52_weeks_max_flag,dengue_cum_2016_flag,dengue_cum_2015_flag,dengue_severe_current_week_flag,dengue_severe_previous_52_weeks_med_flag,dengue_severe_previous_52_weeks_max_flag,dengue_severe_cum_2016_flag,dengue_severe_cum_2015_flag,mmwryear,mmwrweek
```

## Data Commands

```ls
series e:kikd-77zw d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:cryptosporidiosis_previous_52_weeks_med=118 m:cryptosporidiosis_current_week=59 m:dengue_severe_previous_52_weeks_med=0 m:dengue_cum_2015=1 m:cryptosporidiosis_previous_52_weeks_max=373 m:cryptosporidiosis_cum_2015=112 m:cryptosporidiosis_cum_2016=59 m:dengue_previous_52_weeks_med=1 m:dengue_previous_52_weeks_max=6 m:dengue_severe_previous_52_weeks_max=0

series e:kikd-77zw d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:cryptosporidiosis_previous_52_weeks_med=6 m:cryptosporidiosis_current_week=1 m:dengue_severe_previous_52_weeks_med=0 m:cryptosporidiosis_previous_52_weeks_max=21 m:cryptosporidiosis_cum_2015=4 m:cryptosporidiosis_cum_2016=1 m:dengue_previous_52_weeks_med=0 m:dengue_previous_52_weeks_max=1 m:dengue_severe_previous_52_weeks_max=0

series e:kikd-77zw d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:cryptosporidiosis_previous_52_weeks_med=11 m:cryptosporidiosis_current_week=8 m:dengue_severe_previous_52_weeks_med=0 m:cryptosporidiosis_previous_52_weeks_max=42 m:cryptosporidiosis_cum_2015=4 m:cryptosporidiosis_cum_2016=8 m:dengue_previous_52_weeks_med=0 m:dengue_previous_52_weeks_max=1 m:dengue_severe_previous_52_weeks_max=0
```

## Meta Commands

```ls
metric m:cryptosporidiosis_current_week p:integer l:"Cryptosporidiosis, Current week" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_med p:integer l:"Cryptosporidiosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:cryptosporidiosis_previous_52_weeks_max p:integer l:"Cryptosporidiosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2016 p:integer l:"Cryptosporidiosis, Cum 2016" t:dataTypeName=number

metric m:cryptosporidiosis_cum_2015 p:integer l:"Cryptosporidiosis, Cum 2015" t:dataTypeName=number

metric m:dengue_current_week p:integer l:"Dengue?, Current week" t:dataTypeName=number

metric m:dengue_previous_52_weeks_med p:integer l:"Dengue?, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_previous_52_weeks_max p:integer l:"Dengue?, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_cum_2016 p:integer l:"Dengue?, Cum 2016" t:dataTypeName=number

metric m:dengue_cum_2015 p:integer l:"Dengue?, Cum 2015" t:dataTypeName=number

metric m:dengue_severe_current_week p:long l:"Dengue Severe, Current week" t:dataTypeName=number

metric m:dengue_severe_previous_52_weeks_med p:integer l:"Dengue Severe, Previous 52 weeks Med" t:dataTypeName=number

metric m:dengue_severe_previous_52_weeks_max p:integer l:"Dengue Severe, Previous 52 weeks Max" t:dataTypeName=number

metric m:dengue_severe_cum_2016 p:integer l:"Dengue Severe, Cum 2016" t:dataTypeName=number

metric m:dengue_severe_cum_2015 p:integer l:"Dengue Severe, Cum 2015" t:dataTypeName=number

entity e:kikd-77zw l:"NNDSS - Table II. Cryptosporidiosis to Dengue" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/kikd-77zw

property e:kikd-77zw t:meta.view v:id=kikd-77zw v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Cryptosporidiosis to Dengue" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:kikd-77zw t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:kikd-77zw t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:kikd-77zw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwryear | mmwrweek | cryptosporidiosis_current_week | cryptosporidiosis_current_week_flag | cryptosporidiosis_previous_52_weeks_med | cryptosporidiosis_previous_52_weeks_med_flag | cryptosporidiosis_previous_52_weeks_max | cryptosporidiosis_previous_52_weeks_max_flag | cryptosporidiosis_cum_2016 | cryptosporidiosis_cum_2016_flag | cryptosporidiosis_cum_2015 | cryptosporidiosis_cum_2015_flag | dengue_current_week | dengue_current_week_flag | dengue_previous_52_weeks_med | dengue_previous_52_weeks_med_flag | dengue_previous_52_weeks_max | dengue_previous_52_weeks_max_flag | dengue_cum_2016 | dengue_cum_2016_flag | dengue_cum_2015 | dengue_cum_2015_flag | dengue_severe_current_week | dengue_severe_current_week_flag | dengue_severe_previous_52_weeks_med | dengue_severe_previous_52_weeks_med_flag | dengue_severe_previous_52_weeks_max | dengue_severe_previous_52_weeks_max_flag | dengue_severe_cum_2016 | dengue_severe_cum_2016_flag | dengue_severe_cum_2015 | dengue_severe_cum_2015_flag | 
| ============== | ======== | ======== | ============================== | =================================== | ======================================= | ============================================ | ======================================= | ============================================ | ========================== | =============================== | ========================== | =============================== | =================== | ======================== | ============================ | ================================= | ============================ | ================================= | =============== | ==================== | =============== | ==================== | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | 
| UNITED STATES  | 2016     | 1        | 59                             |                                     | 118                                     |                                              | 373                                     |                                              | 59                         |                                 | 112                        |                                 |                     | -                        | 1                            |                                   | 6                            |                                   |                 | -                    | 1               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| NEW ENGLAND    | 2016     | 1        | 1                              |                                     | 6                                       |                                              | 21                                      |                                              | 1                          |                                 | 4                          |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| MID. ATLANTIC  | 2016     | 1        | 8                              |                                     | 11                                      |                                              | 42                                      |                                              | 8                          |                                 | 4                          |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| NEW YORK CITY  | 2016     | 1        | 4                              |                                     | 1                                       |                                              | 13                                      |                                              | 4                          |                                 |                            | -                               |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| E.N. CENTRAL   | 2016     | 1        | 13                             |                                     | 24                                      |                                              | 84                                      |                                              | 13                         |                                 | 15                         |                                 |                     | -                        | 0                            |                                   | 4                            |                                   |                 | -                    | 1               |                      |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| W.N. CENTRAL   | 2016     | 1        | 5                              |                                     | 13                                      |                                              | 55                                      |                                              | 5                          |                                 | 10                         |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| S. ATLANTIC    | 2016     | 1        | 13                             |                                     | 28                                      |                                              | 95                                      |                                              | 13                         |                                 | 48                         |                                 |                     | -                        | 0                            |                                   | 2                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| DIST. OF COL.  | 2016     | 1        |                                | -                                   | 0                                       |                                              | 2                                       |                                              |                            | -                               |                            | -                               |                     | -                        | 0                            |                                   | 0                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| E.S. CENTRAL   | 2016     | 1        | 3                              |                                     | 10                                      |                                              | 66                                      |                                              | 3                          |                                 | 14                         |                                 |                     | -                        | 0                            |                                   | 1                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
| W.S. CENTRAL   | 2016     | 1        | 2                              |                                     | 16                                      |                                              | 45                                      |                                              | 2                          |                                 | 7                          |                                 |                     | -                        | 0                            |                                   | 0                            |                                   |                 | -                    |                 | -                    |                            | -                               | 0                                   |                                          | 0                                   |                                          |                        | -                           |                        | -                           | 
```