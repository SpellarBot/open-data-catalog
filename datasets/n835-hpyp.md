# NNDSS - Table II. Chlamydia to Coccidioidomycosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-chlamydia-to-coccidioidomycosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/n835-hpyp) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/n835-hpyp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/n835-hpyp/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | n835-hpyp |
| Name | NNDSS - Table II. Chlamydia to Coccidioidomycosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, chlamydia trachomatis infection, coccidioidomycosis |
| Created | 2016-01-11T20:25:34Z |
| Publication Date | 2017-01-05T16:51:31Z |

## Description

NNDSS - Table II. Chlamydia to Coccidioidomycosis - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.    NP:  Nationally notifiable but not published.  Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.

* Case counts for reporting year 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions.

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
| Yes      | numeric metric | chlamydia_trachomatis_infection_cum_2016                   | Chlamydia trachomatis infection, Cum 2016                    | number    | number      |
| No       |                | chlamydia_trachomatis_infection_cum_2016_flag              | Chlamydia trachomatis infection, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | chlamydia_trachomatis_infection_cum_2015                   | Chlamydia trachomatis infection, Cum 2015                    | number    | number      |
| No       |                | chlamydia_trachomatis_infection_cum_2015_flag              | Chlamydia trachomatis infection, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_current_week                            | Coccidioidomycosis, Current week                             | number    | number      |
| No       |                | coccidioidomycosis_current_week_flag                       | Coccidioidomycosis, Current week, flag                       | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_previous_52_weeks_med                   | Coccidioidomycosis, Previous 52 weeks Med                    | number    | number      |
| No       |                | coccidioidomycosis_previous_52_weeks_med_flag              | Coccidioidomycosis, Previous 52 weeks Med, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_previous_52_weeks_max                   | Coccidioidomycosis, Previous 52 weeks Max                    | number    | number      |
| No       |                | coccidioidomycosis_previous_52_weeks_max_flag              | Coccidioidomycosis, Previous 52 weeks Max, flag              | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_cum_2016                                | Coccidioidomycosis, Cum 2016                                 | number    | number      |
| No       |                | coccidioidomycosis_cum_2016_flag                           | Coccidioidomycosis, Cum 2016, flag                           | text      | text        |
| Yes      | numeric metric | coccidioidomycosis_cum_2015                                | Coccidioidomycosis, Cum 2015                                 | number    | number      |
| No       |                | coccidioidomycosis_cum_2015_flag                           | Coccidioidomycosis, Cum 2015, flag                           | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = chlamydia_trachomatis_infection_current_week_flag,chlamydia_trachomatis_infection_previous_52_weeks_med_flag,chlamydia_trachomatis_infection_previous_52_weeks_max_flag,chlamydia_trachomatis_infection_cum_2016_flag,chlamydia_trachomatis_infection_cum_2015_flag,coccidioidomycosis_current_week_flag,coccidioidomycosis_previous_52_weeks_med_flag,coccidioidomycosis_previous_52_weeks_max_flag,coccidioidomycosis_cum_2016_flag,coccidioidomycosis_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:n835-hpyp d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:coccidioidomycosis_cum_2016=139 m:chlamydia_trachomatis_infection_cum_2015=25886 m:coccidioidomycosis_previous_52_weeks_med=208 m:chlamydia_trachomatis_infection_previous_52_weeks_med=28656 m:chlamydia_trachomatis_infection_current_week=11455 m:coccidioidomycosis_current_week=139 m:chlamydia_trachomatis_infection_cum_2016=11455 m:coccidioidomycosis_previous_52_weeks_max=353 m:chlamydia_trachomatis_infection_previous_52_weeks_max=31128 m:coccidioidomycosis_cum_2015=176

series e:n835-hpyp d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:chlamydia_trachomatis_infection_cum_2015=857 m:coccidioidomycosis_previous_52_weeks_med=0 m:chlamydia_trachomatis_infection_previous_52_weeks_med=935 m:chlamydia_trachomatis_infection_current_week=360 m:chlamydia_trachomatis_infection_cum_2016=360 m:coccidioidomycosis_previous_52_weeks_max=0 m:chlamydia_trachomatis_infection_previous_52_weeks_max=1429

series e:n835-hpyp d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:chlamydia_trachomatis_infection_cum_2015=3095 m:coccidioidomycosis_previous_52_weeks_med=0 m:chlamydia_trachomatis_infection_previous_52_weeks_med=3589 m:chlamydia_trachomatis_infection_current_week=1735 m:chlamydia_trachomatis_infection_cum_2016=1735 m:coccidioidomycosis_previous_52_weeks_max=0 m:chlamydia_trachomatis_infection_previous_52_weeks_max=4220
```

## Meta Commands

```ls
metric m:chlamydia_trachomatis_infection_current_week p:integer l:"Chlamydia trachomatis infection, Current week" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_previous_52_weeks_med p:integer l:"Chlamydia trachomatis infection, Previous 52 weeks Med" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_previous_52_weeks_max p:integer l:"Chlamydia trachomatis infection, Previous 52 weeks Max" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_cum_2016 p:integer l:"Chlamydia trachomatis infection, Cum 2016" t:dataTypeName=number

metric m:chlamydia_trachomatis_infection_cum_2015 p:integer l:"Chlamydia trachomatis infection, Cum 2015" t:dataTypeName=number

metric m:coccidioidomycosis_current_week p:integer l:"Coccidioidomycosis, Current week" t:dataTypeName=number

metric m:coccidioidomycosis_previous_52_weeks_med p:integer l:"Coccidioidomycosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:coccidioidomycosis_previous_52_weeks_max p:integer l:"Coccidioidomycosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:coccidioidomycosis_cum_2016 p:integer l:"Coccidioidomycosis, Cum 2016" t:dataTypeName=number

metric m:coccidioidomycosis_cum_2015 p:integer l:"Coccidioidomycosis, Cum 2015" t:dataTypeName=number

entity e:n835-hpyp l:"NNDSS - Table II. Chlamydia to Coccidioidomycosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/n835-hpyp

property e:n835-hpyp t:meta.view v:id=n835-hpyp v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Chlamydia to Coccidioidomycosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:n835-hpyp t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:n835-hpyp t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:n835-hpyp t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | chlamydia_trachomatis_infection_current_week | chlamydia_trachomatis_infection_current_week_flag | chlamydia_trachomatis_infection_previous_52_weeks_med | chlamydia_trachomatis_infection_previous_52_weeks_med_flag | chlamydia_trachomatis_infection_previous_52_weeks_max | chlamydia_trachomatis_infection_previous_52_weeks_max_flag | chlamydia_trachomatis_infection_cum_2016 | chlamydia_trachomatis_infection_cum_2016_flag | chlamydia_trachomatis_infection_cum_2015 | chlamydia_trachomatis_infection_cum_2015_flag | coccidioidomycosis_current_week | coccidioidomycosis_current_week_flag | coccidioidomycosis_previous_52_weeks_med | coccidioidomycosis_previous_52_weeks_med_flag | coccidioidomycosis_previous_52_weeks_max | coccidioidomycosis_previous_52_weeks_max_flag | coccidioidomycosis_cum_2016 | coccidioidomycosis_cum_2016_flag | coccidioidomycosis_cum_2015 | coccidioidomycosis_cum_2015_flag | 
| ============== | ========= | ========= | ============================================ | ================================================= | ===================================================== | ========================================================== | ===================================================== | ========================================================== | ======================================== | ============================================= | ======================================== | ============================================= | =============================== | ==================================== | ======================================== | ============================================= | ======================================== | ============================================= | =========================== | ================================ | =========================== | ================================ | 
| UNITED STATES  | 2016      | 1         | 11455                                        |                                                   | 28656                                                 |                                                            | 31128                                                 |                                                            | 11455                                    |                                               | 25886                                    |                                               | 139                             |                                      | 208                                      |                                               | 353                                      |                                               | 139                         |                                  | 176                         |                                  | 
| NEW ENGLAND    | 2016      | 1         | 360                                          |                                                   | 935                                                   |                                                            | 1429                                                  |                                                            | 360                                      |                                               | 857                                      |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| MID. ATLANTIC  | 2016      | 1         | 1735                                         |                                                   | 3589                                                  |                                                            | 4220                                                  |                                                            | 1735                                     |                                               | 3095                                     |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| NEW YORK CITY  | 2016      | 1         | 266                                          |                                                   | 1193                                                  |                                                            | 1353                                                  |                                                            | 266                                      |                                               | 1295                                     |                                               |                                 | N                                    | 0                                        |                                               | 0                                        |                                               |                             | N                                |                             | N                                | 
| W.N. CENTRAL   | 2016      | 1         | 343                                          |                                                   | 1686                                                  |                                                            | 1934                                                  |                                                            | 343                                      |                                               | 1748                                     |                                               |                                 | -                                    | 2                                        |                                               | 7                                        |                                               |                             | -                                |                             | -                                | 
| S. ATLANTIC    | 2016      | 1         | 1360                                         |                                                   | 6039                                                  |                                                            | 7647                                                  |                                                            | 1360                                     |                                               | 4754                                     |                                               |                                 | -                                    | 0                                        |                                               | 1                                        |                                               |                             | -                                |                             | -                                | 
| DIST. OF COL.  | 2016      | 1         |                                              | -                                                 | 132                                                   |                                                            | 403                                                   |                                                            |                                          | -                                             | 133                                      |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| E.S. CENTRAL   | 2016      | 1         | 161                                          |                                                   | 1472                                                  |                                                            | 2600                                                  |                                                            | 161                                      |                                               | 1107                                     |                                               |                                 | -                                    | 0                                        |                                               | 0                                        |                                               |                             | -                                |                             | -                                | 
| W.S. CENTRAL   | 2016      | 1         | 2897                                         |                                                   | 3720                                                  |                                                            | 6545                                                  |                                                            | 2897                                     |                                               | 3481                                     |                                               |                                 | -                                    | 0                                        |                                               | 2                                        |                                               |                             | -                                |                             | -                                | 
| MOUNTAIN       | 2016      | 1         | 567                                          |                                                   | 1844                                                  |                                                            | 2514                                                  |                                                            | 567                                      |                                               | 1798                                     |                                               | 139                             |                                      | 149                                      |                                               | 284                                      |                                               | 139                         |                                  | 89                          |                                  | 
```