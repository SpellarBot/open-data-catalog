# NNDSS - Table II. Legionellosis to Malaria

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-legionellosis-to-malaria) |
| Metadata | [Link](https://data.cdc.gov/api/views/33kn-dpz2) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/33kn-dpz2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/33kn-dpz2/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 33kn-dpz2 |
| Name | NNDSS - Table II. Legionellosis to Malaria |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, legionellosis, malaria |
| Created | 2017-01-12T20:06:09Z |
| Publication Date | 2017-04-20T18:35:07Z |

## Description

NNDSS - Table II. Legionellosis to Malaria - 2017. In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

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
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                           | Reporting Area                             | text      | text        |
| No       |                | mmwr_year                                | MMWR Year                                  | number    | number      |
| No       |                | mmwr_week                                | MMWR Week                                  | number    | number      |
| Yes      | numeric metric | legionellosis_current_week               | Legionellosis, Current week                | number    | number      |
| No       |                | legionellosis_current_week_flag          | Legionellosis, Current week, flag          | text      | text        |
| Yes      | numeric metric | legionellosis_previous_52_weeks_med      | Legionellosis, Previous 52 weeks Med       | number    | number      |
| No       |                | legionellosis_previous_52_weeks_med_flag | Legionellosis, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | legionellosis_previous_52_weeks_max      | Legionellosis, Previous 52 weeks Max       | number    | number      |
| No       |                | legionellosis_previous_52_weeks_max_flag | Legionellosis, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | legionellosis_cum_2017                   | Legionellosis, Cum 2017                    | number    | number      |
| No       |                | legionellosis_cum_2017_flag              | Legionellosis, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | legionellosis_cum_2016                   | Legionellosis, Cum 2016                    | number    | number      |
| No       |                | legionellosis_cum_2016_flag              | Legionellosis, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | malaria_current_week                     | Malaria, Current week                      | number    | number      |
| No       |                | malaria_current_week_flag                | Malaria, Current week, flag                | text      | text        |
| Yes      | numeric metric | malaria_previous_52_weeks_med            | Malaria, Previous 52 weeks Med             | number    | number      |
| No       |                | malaria_previous_52_weeks_med_flag       | Malaria, Previous 52 weeks Med, flag       | text      | text        |
| Yes      | numeric metric | malaria_previous_52_weeks_max            | Malaria, Previous 52 weeks Max             | number    | number      |
| No       |                | malaria_previous_52_weeks_max_flag       | Malaria, Previous 52 weeks Max, flag       | text      | text        |
| Yes      | numeric metric | malaria_cum_2017                         | Malaria, Cum 2017                          | number    | number      |
| No       |                | malaria_cum_2017_flag                    | Malaria, Cum 2017, flag                    | text      | text        |
| Yes      | numeric metric | malaria_cum_2016                         | Malaria, Cum 2016                          | number    | number      |
| No       |                | malaria_cum_2016_flag                    | Malaria, Cum 2016, flag                    | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = legionellosis_current_week_flag,legionellosis_previous_52_weeks_med_flag,legionellosis_previous_52_weeks_max_flag,legionellosis_cum_2017_flag,legionellosis_cum_2016_flag,malaria_current_week_flag,malaria_previous_52_weeks_med_flag,malaria_previous_52_weeks_max_flag,malaria_cum_2017_flag,malaria_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:33kn-dpz2 d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:malaria_current_week=10 m:malaria_previous_52_weeks_med=31 m:legionellosis_previous_52_weeks_max=210 m:legionellosis_previous_52_weeks_med=97 m:malaria_cum_2017=10 m:legionellosis_cum_2017=43 m:legionellosis_cum_2016=85 m:malaria_previous_52_weeks_max=84 m:malaria_cum_2016=22 m:legionellosis_current_week=43

series e:33kn-dpz2 d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:malaria_previous_52_weeks_med=2 m:legionellosis_previous_52_weeks_max=21 m:legionellosis_previous_52_weeks_med=4 m:legionellosis_cum_2017=1 m:legionellosis_cum_2016=3 m:malaria_previous_52_weeks_max=7 m:malaria_cum_2016=1 m:legionellosis_current_week=1

series e:33kn-dpz2 d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:malaria_current_week=5 m:malaria_previous_52_weeks_med=8 m:legionellosis_previous_52_weeks_max=64 m:legionellosis_previous_52_weeks_med=20 m:malaria_cum_2017=5 m:legionellosis_cum_2017=13 m:legionellosis_cum_2016=23 m:malaria_previous_52_weeks_max=24 m:malaria_cum_2016=5 m:legionellosis_current_week=13
```

## Meta Commands

```ls
metric m:legionellosis_current_week p:long l:"Legionellosis, Current week" t:dataTypeName=number

metric m:legionellosis_previous_52_weeks_med p:long l:"Legionellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:legionellosis_previous_52_weeks_max p:long l:"Legionellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:legionellosis_cum_2017 p:long l:"Legionellosis, Cum 2017" t:dataTypeName=number

metric m:legionellosis_cum_2016 p:long l:"Legionellosis, Cum 2016" t:dataTypeName=number

metric m:malaria_current_week p:long l:"Malaria, Current week" t:dataTypeName=number

metric m:malaria_previous_52_weeks_med p:long l:"Malaria, Previous 52 weeks Med" t:dataTypeName=number

metric m:malaria_previous_52_weeks_max p:long l:"Malaria, Previous 52 weeks Max" t:dataTypeName=number

metric m:malaria_cum_2017 p:long l:"Malaria, Cum 2017" t:dataTypeName=number

metric m:malaria_cum_2016 p:long l:"Malaria, Cum 2016" t:dataTypeName=number

entity e:33kn-dpz2 l:"NNDSS - Table II. Legionellosis to Malaria" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/33kn-dpz2

property e:33kn-dpz2 t:meta.view v:id=33kn-dpz2 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Legionellosis to Malaria" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:33kn-dpz2 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:33kn-dpz2 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:33kn-dpz2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | legionellosis_current_week | legionellosis_current_week_flag | legionellosis_previous_52_weeks_med | legionellosis_previous_52_weeks_med_flag | legionellosis_previous_52_weeks_max | legionellosis_previous_52_weeks_max_flag | legionellosis_cum_2017 | legionellosis_cum_2017_flag | legionellosis_cum_2016 | legionellosis_cum_2016_flag | malaria_current_week | malaria_current_week_flag | malaria_previous_52_weeks_med | malaria_previous_52_weeks_med_flag | malaria_previous_52_weeks_max | malaria_previous_52_weeks_max_flag | malaria_cum_2017 | malaria_cum_2017_flag | malaria_cum_2016 | malaria_cum_2016_flag | 
| ============== | ========= | ========= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | ==================== | ========================= | ============================= | ================================== | ============================= | ================================== | ================ | ===================== | ================ | ===================== | 
| UNITED STATES  | 2017      | 1         | 43                         |                                 | 97                                  |                                          | 210                                 |                                          | 43                     |                             | 85                     |                             | 10                   |                           | 31                            |                                    | 84                            |                                    | 10               |                       | 22               |                       | 
| NEW ENGLAND    | 2017      | 1         | 1                          |                                 | 4                                   |                                          | 21                                  |                                          | 1                      |                             | 3                      |                             |                      | -                         | 2                             |                                    | 7                             |                                    |                  | -                     | 1                |                       | 
| MID. ATLANTIC  | 2017      | 1         | 13                         |                                 | 20                                  |                                          | 64                                  |                                          | 13                     |                             | 23                     |                             | 5                    |                           | 8                             |                                    | 24                            |                                    | 5                |                       | 5                |                       | 
| NEW YORK CITY  | 2017      | 1         | 11                         |                                 | 4                                   |                                          | 31                                  |                                          | 11                     |                             | 4                      |                             | 4                    |                           | 5                             |                                    | 17                            |                                    | 4                |                       | 5                |                       | 
| E.N. CENTRAL   | 2017      | 1         | 19                         |                                 | 17                                  |                                          | 71                                  |                                          | 19                     |                             | 22                     |                             | 1                    |                           | 3                             |                                    | 25                            |                                    | 1                |                       | 2                |                       | 
| W.N. CENTRAL   | 2017      | 1         | 1                          |                                 | 5                                   |                                          | 18                                  |                                          | 1                      |                             | 2                      |                             | 1                    |                           | 1                             |                                    | 5                             |                                    | 1                |                       | 1                |                       | 
| S. ATLANTIC    | 2017      | 1         | 5                          |                                 | 19                                  |                                          | 33                                  |                                          | 5                      |                             | 20                     |                             |                      | -                         | 8                             |                                    | 26                            |                                    |                  | -                     | 11               |                       | 
| E.S. CENTRAL   | 2017      | 1         | 3                          |                                 | 5                                   |                                          | 13                                  |                                          | 3                      |                             | 3                      |                             |                      | -                         | 1                             |                                    | 3                             |                                    |                  | -                     | 1                |                       | 
| W.S. CENTRAL   | 2017      | 1         |                            | -                               | 6                                   |                                          | 27                                  |                                          |                        | -                           | 1                      |                             |                      | -                         | 2                             |                                    | 10                            |                                    |                  | -                     | 1                |                       | 
| MOUNTAIN       | 2017      | 1         | 1                          |                                 | 3                                   |                                          | 10                                  |                                          | 1                      |                             | 1                      |                             | 1                    |                           | 1                             |                                    | 5                             |                                    | 1                |                       |                  | -                     | 
```