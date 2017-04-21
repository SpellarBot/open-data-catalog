# NNDSS - Table II. Tetanus to Varicella

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-tetanus-to-varicella) |
| Metadata | [Link](https://data.cdc.gov/api/views/jz7r-jrma) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/jz7r-jrma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/jz7r-jrma/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | jz7r-jrma |
| Name | NNDSS - Table II. Tetanus to Varicella |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, tetanus, varicella |
| Created | 2017-01-12T20:47:01Z |
| Publication Date | 2017-04-20T18:44:55Z |

## Description

NNDSS - Table II. Tetanus to Varicella - 2017.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

 U: Unavailable. ?: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

*Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

? Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

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
| Yes      | numeric metric | tetanus_cum_2017                                | Tetanus, Cum 2017                                   | number    | number      |
| No       |                | tetanus_cum_2017_flag                           | Tetanus, Cum 2017, flag                             | text      | text        |
| Yes      | numeric metric | tetanus_cum_2016                                | Tetanus, Cum 2016                                   | number    | number      |
| No       |                | tetanus_cum_2016_flag                           | Tetanus, Cum 2016, flag                             | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_current_week               | Varicella (chickenpox), Current week                | number    | number      |
| No       |                | varicella_chickenpox_current_week_flag          | Varicella (chickenpox), Current week, flag          | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_previous_52_weeks_med      | Varicella (chickenpox), Previous 52 weeks Med       | number    | number      |
| No       |                | varicella_chickenpox_previous_52_weeks_med_flag | Varicella (chickenpox), Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_previous_52_weeks_max      | Varicella (chickenpox), Previous 52 weeks Max       | number    | number      |
| No       |                | varicella_chickenpox_previous_52_weeks_max_flag | Varicella (chickenpox), Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_cum_2017                   | Varicella (chickenpox), Cum 2017                    | number    | number      |
| No       |                | varicella_chickenpox_cum_2017_flag              | Varicella (chickenpox), Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | varicella_chickenpox_cum_2016                   | Varicella (chickenpox), Cum 2016                    | number    | number      |
| No       |                | varicella_chickenpox_cum_2016_flag              | Varicella (chickenpox), Cum 2016, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = tetanus_current_week_flag,tetanus_previous_52_weeks_med_flag,tetanus_previous_52_weeks_max_flag,tetanus_cum_2017_flag,tetanus_cum_2016_flag,varicella_chickenpox_current_week_flag,varicella_chickenpox_previous_52_weeks_med_flag,varicella_chickenpox_previous_52_weeks_max_flag,varicella_chickenpox_cum_2017_flag,varicella_chickenpox_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:jz7r-jrma d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:tetanus_previous_52_weeks_max=3 m:tetanus_previous_52_weeks_med=1 m:varicella_chickenpox_current_week=38 m:varicella_chickenpox_previous_52_weeks_max=205 m:varicella_chickenpox_previous_52_weeks_med=151 m:varicella_chickenpox_cum_2016=163 m:varicella_chickenpox_cum_2017=38

series e:jz7r-jrma d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:tetanus_previous_52_weeks_max=1 m:tetanus_previous_52_weeks_med=0 m:varicella_chickenpox_current_week=3 m:varicella_chickenpox_previous_52_weeks_max=27 m:varicella_chickenpox_previous_52_weeks_med=14 m:varicella_chickenpox_cum_2016=18 m:varicella_chickenpox_cum_2017=3

series e:jz7r-jrma d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:tetanus_previous_52_weeks_max=2 m:tetanus_previous_52_weeks_med=0 m:varicella_chickenpox_current_week=9 m:varicella_chickenpox_previous_52_weeks_max=39 m:varicella_chickenpox_previous_52_weeks_med=17 m:varicella_chickenpox_cum_2016=15 m:varicella_chickenpox_cum_2017=9
```

## Meta Commands

```ls
metric m:tetanus_current_week p:long l:"Tetanus, Current week" t:dataTypeName=number

metric m:tetanus_previous_52_weeks_med p:long l:"Tetanus, Previous 52 weeks Med" t:dataTypeName=number

metric m:tetanus_previous_52_weeks_max p:long l:"Tetanus, Previous 52 weeks Max" t:dataTypeName=number

metric m:tetanus_cum_2017 p:long l:"Tetanus, Cum 2017" t:dataTypeName=number

metric m:tetanus_cum_2016 p:long l:"Tetanus, Cum 2016" t:dataTypeName=number

metric m:varicella_chickenpox_current_week p:long l:"Varicella (chickenpox), Current week" t:dataTypeName=number

metric m:varicella_chickenpox_previous_52_weeks_med p:long l:"Varicella (chickenpox), Previous 52 weeks Med" t:dataTypeName=number

metric m:varicella_chickenpox_previous_52_weeks_max p:long l:"Varicella (chickenpox), Previous 52 weeks Max" t:dataTypeName=number

metric m:varicella_chickenpox_cum_2017 p:long l:"Varicella (chickenpox), Cum 2017" t:dataTypeName=number

metric m:varicella_chickenpox_cum_2016 p:long l:"Varicella (chickenpox), Cum 2016" t:dataTypeName=number

entity e:jz7r-jrma l:"NNDSS - Table II. Tetanus to Varicella" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/jz7r-jrma

property e:jz7r-jrma t:meta.view v:id=jz7r-jrma v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Tetanus to Varicella" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:jz7r-jrma t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:jz7r-jrma t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:jz7r-jrma t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | tetanus_current_week | tetanus_current_week_flag | tetanus_previous_52_weeks_med | tetanus_previous_52_weeks_med_flag | tetanus_previous_52_weeks_max | tetanus_previous_52_weeks_max_flag | tetanus_cum_2017 | tetanus_cum_2017_flag | tetanus_cum_2016 | tetanus_cum_2016_flag | varicella_chickenpox_current_week | varicella_chickenpox_current_week_flag | varicella_chickenpox_previous_52_weeks_med | varicella_chickenpox_previous_52_weeks_med_flag | varicella_chickenpox_previous_52_weeks_max | varicella_chickenpox_previous_52_weeks_max_flag | varicella_chickenpox_cum_2017 | varicella_chickenpox_cum_2017_flag | varicella_chickenpox_cum_2016 | varicella_chickenpox_cum_2016_flag | 
| ============== | ========= | ========= | ==================== | ========================= | ============================= | ================================== | ============================= | ================================== | ================ | ===================== | ================ | ===================== | ================================= | ====================================== | ========================================== | =============================================== | ========================================== | =============================================== | ============================= | ================================== | ============================= | ================================== | 
| UNITED STATES  | 2017      | 1         |                      | -                         | 1                             |                                    | 3                             |                                    |                  | -                     |                  | -                     | 38                                |                                        | 151                                        |                                                 | 205                                        |                                                 | 38                            |                                    | 163                           |                                    | 
| NEW ENGLAND    | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 3                                 |                                        | 14                                         |                                                 | 27                                         |                                                 | 3                             |                                    | 18                            |                                    | 
| MID. ATLANTIC  | 2017      | 1         |                      | -                         | 0                             |                                    | 2                             |                                    |                  | -                     |                  | -                     | 9                                 |                                        | 17                                         |                                                 | 39                                         |                                                 | 9                             |                                    | 15                            |                                    | 
| NEW YORK CITY  | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     |                                   | -                                      | 0                                          |                                                 | 0                                          |                                                 |                               | -                                  |                               | -                                  | 
| E.N. CENTRAL   | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 15                                |                                        | 35                                         |                                                 | 70                                         |                                                 | 15                            |                                    | 70                            |                                    | 
| W.N. CENTRAL   | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 1                                 |                                        | 11                                         |                                                 | 29                                         |                                                 | 1                             |                                    | 14                            |                                    | 
| S. ATLANTIC    | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 6                                 |                                        | 23                                         |                                                 | 54                                         |                                                 | 6                             |                                    | 18                            |                                    | 
| E.S. CENTRAL   | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 2                                 |                                        | 2                                          |                                                 | 6                                          |                                                 | 2                             |                                    | 4                             |                                    | 
| W.S. CENTRAL   | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 1                                 |                                        | 25                                         |                                                 | 52                                         |                                                 | 1                             |                                    | 6                             |                                    | 
| MOUNTAIN       | 2017      | 1         |                      | -                         | 0                             |                                    | 1                             |                                    |                  | -                     |                  | -                     | 1                                 |                                        | 12                                         |                                                 | 34                                         |                                                 | 1                             |                                    | 17                            |                                    | 
```