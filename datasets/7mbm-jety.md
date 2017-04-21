# NNDSS - Table II. Chlamydia to Coccidioidomycosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-chlamydia-to-coccidioidomycosis-0fe8b) |
| Metadata | [Link](https://data.cdc.gov/api/views/7mbm-jety) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/7mbm-jety/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/7mbm-jety/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 7mbm-jety |
| Name | NNDSS - Table II. Chlamydia to Coccidioidomycosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, chlamydia trachomatis infection, coccidioidomycosis |
| Created | 2017-01-12T18:53:36Z |
| Publication Date | 2017-04-20T18:24:14Z |

## Description

NNDSS - Table II. Chlamydia to Coccidioidomycosis - 2017.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

U: Unavailable. ?: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

* Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

? Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                         | Data Type | Render Type |
| ======== | ============== | ========================================================== | ============================================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                                             | Reporting Area                                               | text      | text        |
| No       |                | mmwr_year                                                  | MMWR Year                                                    | number    | number      |
| No       |                | mmwr_week                                                  | MMWR Week                                                    | number    | number      |
| Yes      | numeric metric | chlamydia_trachomatis_infection_current_week               | Chlamydia trachomatis infection, Current week                | number    | number      |
| No       |                | chlamydia_trachomatis_infection_current_week_flag          | Chlamydia trachomatis infection, Current week, flag          | text      | text        |
| Yes      | numeric metric | chlamydia_trachomatis_infection_previous_52_weeks_med      | Chlamydia trachomatis infection, Previous 52 weeks Med       | number    | number      |
| No       |                | chlamydia_trachomatis_infection_previous_52_weeks_med_flag | Chlamydia trachomatis infection, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | chlamydia_trachomatis_infection_previous_52_weeks_max      | Chlamydia trachomatis infection, Previous 52 weeks Max       | number    | number      |
| No       |                | chlamydia_trachomatis_infection_previous_52_weeks_max_flag | Chlamydia trachomatis infection, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | chlamydia_trachomatis_infection_cum_2017                   | Chlamydia trachomatis infection, Cum 2017                    | number    | number      |
| No       |                | chlamydia_trachomatis_infection_cum_2017_flag              | Chlamydia trachomatis infection, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | chlamydia_trachomatis_infection_cum_2016                   | Chlamydia trachomatis infection, Cum 2016                    | number    | number      |
| No       |                | chlamydia_trachomatis_infection_cum_2016_flag              | Chlamydia trachomatis infection, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_current_week                            | Coccidioidomycosis, Current week                             | number    | number      |
| No       |                | coccidioidomycosis_current_week_flag                       | Coccidioidomycosis, Current week, flag                       | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_previous_52_weeks_med                   | Coccidioidomycosis, Previous 52 weeks Med                    | number    | number      |
| No       |                | coccidioidomycosis_previous_52_weeks_med_flag              | Coccidioidomycosis, Previous 52 weeks Med, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_previous_52_weeks_max                   | Coccidioidomycosis, Previous 52 weeks Max                    | number    | number      |
| No       |                | coccidioidomycosis_previous_52_weeks_max_flag              | Coccidioidomycosis, Previous 52 weeks Max, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_cum_2017                                | Coccidioidomycosis, Cum 2017                                 | number    | number      |
| No       |                | coccidioidomycosis_cum_2017_flag                           | Coccidioidomycosis, Cum 2017, flag                           | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_cum_2016                                | Coccidioidomycosis, Cum 2016                                 | number    | number      |
| No       |                | coccidioidomycosis_cum_2016_flag                           | Coccidioidomycosis, Cum 2016, flag                           | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = chlamydia_trachomatis_infection_current_week_flag,chlamydia_trachomatis_infection_previous_52_weeks_med_flag,chlamydia_trachomatis_infection_previous_52_weeks_max_flag,chlamydia_trachomatis_infection_cum_2017_flag,chlamydia_trachomatis_infection_cum_2016_flag,coccidioidomycosis_current_week_flag,coccidioidomycosis_previous_52_weeks_med_flag,coccidioidomycosis_previous_52_weeks_max_flag,coccidioidomycosis_cum_2017_flag,coccidioidomycosis_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:7mbm-jety d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:coccidioidomycosis_cum_2017=148 m:coccidioidomycosis_cum_2016=201 m:chlamydia_trachomatis_infection_cum_2017=8286 m:coccidioidomycosis_previous_52_weeks_med=208 m:chlamydia_trachomatis_infection_previous_52_weeks_med=29056 m:chlamydia_trachomatis_infection_current_week=8286 m:coccidioidomycosis_current_week=148 m:chlamydia_trachomatis_infection_cum_2016=25647 m:coccidioidomycosis_previous_52_weeks_max=269 m:chlamydia_trachomatis_infection_previous_52_weeks_max=32594

series e:7mbm-jety d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:chlamydia_trachomatis_infection_cum_2017=534 m:coccidioidomycosis_previous_52_weeks_med=0 m:chlamydia_trachomatis_infection_previous_52_weeks_med=1044 m:chlamydia_trachomatis_infection_current_week=534 m:chlamydia_trachomatis_infection_cum_2016=806 m:coccidioidomycosis_previous_52_weeks_max=1 m:chlamydia_trachomatis_infection_previous_52_weeks_max=1296

series e:7mbm-jety d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:chlamydia_trachomatis_infection_cum_2017=1598 m:coccidioidomycosis_previous_52_weeks_med=0 m:chlamydia_trachomatis_infection_previous_52_weeks_med=3918 m:chlamydia_trachomatis_infection_current_week=1598 m:chlamydia_trachomatis_infection_cum_2016=4060 m:coccidioidomycosis_previous_52_weeks_max=0 m:chlamydia_trachomatis_infection_previous_52_weeks_max=4284
```

## Meta Commands

```ls
metric m:chlamydia_trachomatis_infection_current_week p:long l:"Chlamydia trachomatis infection, Current week" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_previous_52_weeks_med p:long l:"Chlamydia trachomatis infection, Previous 52 weeks Med" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_previous_52_weeks_max p:long l:"Chlamydia trachomatis infection, Previous 52 weeks Max" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_cum_2017 p:long l:"Chlamydia trachomatis infection, Cum 2017" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_cum_2016 p:long l:"Chlamydia trachomatis infection, Cum 2016" t:dataTypeName=number

metric m:coccidioidomycosis_current_week p:long l:"Coccidioidomycosis, Current week" t:dataTypeName=number

metric m:coccidioidomycosis_previous_52_weeks_med p:long l:"Coccidioidomycosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:coccidioidomycosis_previous_52_weeks_max p:long l:"Coccidioidomycosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:coccidioidomycosis_cum_2017 p:long l:"Coccidioidomycosis, Cum 2017" t:dataTypeName=number

metric m:coccidioidomycosis_cum_2016 p:long l:"Coccidioidomycosis, Cum 2016" t:dataTypeName=number

entity e:7mbm-jety l:"NNDSS - Table II. Chlamydia to Coccidioidomycosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/7mbm-jety

property e:7mbm-jety t:meta.view v:id=7mbm-jety v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Chlamydia to Coccidioidomycosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:7mbm-jety t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:7mbm-jety t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:7mbm-jety t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | chlamydia_trachomatis_infection_current_week | chlamydia_trachomatis_infection_current_week_flag | chlamydia_trachomatis_infection_previous_52_weeks_med | chlamydia_trachomatis_infection_previous_52_weeks_med_flag | chlamydia_trachomatis_infection_previous_52_weeks_max | chlamydia_trachomatis_infection_previous_52_weeks_max_flag | chlamydia_trachomatis_infection_cum_2017 | chlamydia_trachomatis_infection_cum_2017_flag | chlamydia_trachomatis_infection_cum_2016 | chlamydia_trachomatis_infection_cum_2016_flag | coccidioidomycosis_current_week | coccidioidomycosis_current_week_flag | coccidioidomycosis_previous_52_weeks_med | coccidioidomycosis_previous_52_weeks_med_flag | coccidioidomycosis_previous_52_weeks_max | coccidioidomycosis_previous_52_weeks_max_flag | coccidioidomycosis_cum_2017 | coccidioidomycosis_cum_2017_flag | coccidioidomycosis_cum_2016 | coccidioidomycosis_cum_2016_flag | 
| ============== | ========= | ========= | ============================================ | ================================================= | ===================================================== | ========================================================== | ===================================================== | ========================================================== | ======================================== | ============================================= | ======================================== | ============================================= | =============================== | ==================================== | ======================================== | ============================================= | ======================================== | ============================================= | =========================== | ================================ | =========================== | ================================ | 
| UNITED STATES  | 2017      | 1         | 8286                                         |                                                   | 29056                                                 |                                                            | 32594                                                 |                                                            | 8286                                     |                                               | 25647                                    |                                               | 148                             |                                      | 208                                      |                                               | 269                                      |                                               | 148                         |                                  | 201                         |                                  | 
| NEW ENGLAND    | 2017      | 1         | 534                                          |                                                   | 1044                                                  |                                                            | 1296                                                  |                                                            | 534                                      |                                               | 806                                      |                                               |                                 | -                                    | 0                                        |                                               | 1                                        |                                               |                             | -                                |                             | -                                | 
| MID. ATLANTIC  | 2017      | 1         | 1598                                         |                                                   | 3918                                                  |                                                            | 4284                                                  |                                                            | 1598                                     |                                               | 4060                                     |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| NEW YORK CITY  | 2017      | 1         | 530                                          |                                                   | 1297                                                  |                                                            | 1520                                                  |                                                            | 530                                      |                                               | 1402                                     |                                               |                                 | N                                    | 0                                        |                                               | 0                                        |                                               |                             | N                                |                             | N                                | 
| E.N. CENTRAL   | 2017      | 1         | 1094                                         |                                                   | 4221                                                  |                                                            | 4909                                                  |                                                            | 1094                                     |                                               | 4744                                     |                                               | 2                               |                                      | 1                                        |                                               | 7                                        |                                               | 2                           |                                  |                             | -                                | 
| W.N. CENTRAL   | 2017      | 1         | 248                                          |                                                   | 1841                                                  |                                                            | 2070                                                  |                                                            | 248                                      |                                               | 1930                                     |                                               |                                 | -                                    | 2                                        |                                               | 9                                        |                                               |                             | -                                | 1                           |                                  | 
| S. ATLANTIC    | 2017      | 1         | 1014                                         |                                                   | 5590                                                  |                                                            | 7038                                                  |                                                            | 1014                                     |                                               | 3471                                     |                                               |                                 | -                                    | 0                                        |                                               | 2                                        |                                               |                             | -                                |                             | -                                | 
| E.S. CENTRAL   | 2017      | 1         | 45                                           |                                                   | 1483                                                  |                                                            | 2262                                                  |                                                            | 45                                       |                                               | 1050                                     |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| W.S. CENTRAL   | 2017      | 1         | 2125                                         |                                                   | 3969                                                  |                                                            | 5427                                                  |                                                            | 2125                                     |                                               | 3231                                     |                                               |                                 | -                                    | 0                                        |                                               | 1                                        |                                               |                             | -                                | 1                           |                                  | 
| MOUNTAIN       | 2017      | 1         | 233                                          |                                                   | 1998                                                  |                                                            | 2636                                                  |                                                            | 233                                      |                                               | 1492                                     |                                               | 140                             |                                      | 123                                      |                                               | 161                                      |                                               | 140                         |                                  | 126                         |                                  | 
```