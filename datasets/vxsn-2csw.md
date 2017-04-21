# NNDSS - Table II. Hepatitis (viral, acute) A & B

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-hepatitis-viral-acute-a-amp-b) |
| Metadata | [Link](https://data.cdc.gov/api/views/vxsn-2csw) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vxsn-2csw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vxsn-2csw/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vxsn-2csw |
| Name | NNDSS - Table II. Hepatitis (viral, acute) A & B |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, hepatitis, hepatitis (viral acute), hepatitis (viral acute) type a, hepatitis (viral acute) type b |
| Created | 2017-01-12T19:33:39Z |
| Publication Date | 2017-04-20T18:29:56Z |

## Description

NNDSS - Table II. Hepatitis (viral, acute) A & B - 2017.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

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
| Included | Schema Type    | Field Name                                                 | Name                                                              | Data Type | Render Type |
| ======== | ============== | ========================================================== | ================================================================= | ========= | =========== |
| Yes      | series tag     | reporting_area                                             | Reporting Area                                                    | text      | text        |
| No       |                | mmwr_year                                                  | MMWR Year                                                         | number    | number      |
| No       |                | mmwr_week                                                  | MMWR Week                                                         | number    | number      |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_a_current_week               | Hepatitis (viral, acute, by type), A, Current week                | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_a_current_week_flag          | Hepatitis (viral, acute, by type), A, Current week, flag          | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_a_previous_52_weeks_med      | Hepatitis (viral, acute, by type), A, Previous 52 weeks Med       | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_a_previous_52_weeks_med_flag | Hepatitis (viral, acute, by type), A, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_a_previous_52_weeks_max      | Hepatitis (viral, acute, by type), A, Previous 52 weeks Max       | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_a_previous_52_weeks_max_flag | Hepatitis (viral, acute, by type), A, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_a_cum_2017                   | Hepatitis (viral, acute, by type), A, Cum 2017                    | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_a_cum_2017_flag              | Hepatitis (viral, acute, by type), A, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_a_cum_2016                   | Hepatitis (viral, acute, by type), A, Cum 2016                    | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_a_cum_2016_flag              | Hepatitis (viral, acute, by type), A, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_b_current_week               | Hepatitis (viral, acute, by type), B, Current week                | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_b_current_week_flag          | Hepatitis (viral, acute, by type), B, Current week, flag          | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_b_previous_52_weeks_med      | Hepatitis (viral, acute, by type), B, Previous 52 weeks Med       | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_b_previous_52_weeks_med_flag | Hepatitis (viral, acute, by type), B, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_b_previous_52_weeks_max      | Hepatitis (viral, acute, by type), B, Previous 52 weeks Max       | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_b_previous_52_weeks_max_flag | Hepatitis (viral, acute, by type), B, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_b_cum_2017                   | Hepatitis (viral, acute, by type), B, Cum 2017                    | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_b_cum_2017_flag              | Hepatitis (viral, acute, by type), B, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | hepatitis_viral_acute_by_type_b_cum_2016                   | Hepatitis (viral, acute, by type), B, Cum 2016                    | number    | number      |
| No       |                | hepatitis_viral_acute_by_type_b_cum_2016_flag              | Hepatitis (viral, acute, by type), B, Cum 2016, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = hepatitis_viral_acute_by_type_a_current_week_flag,hepatitis_viral_acute_by_type_a_previous_52_weeks_med_flag,hepatitis_viral_acute_by_type_a_previous_52_weeks_max_flag,hepatitis_viral_acute_by_type_a_cum_2017_flag,hepatitis_viral_acute_by_type_a_cum_2016_flag,hepatitis_viral_acute_by_type_b_current_week_flag,hepatitis_viral_acute_by_type_b_previous_52_weeks_med_flag,hepatitis_viral_acute_by_type_b_previous_52_weeks_max_flag,hepatitis_viral_acute_by_type_b_cum_2017_flag,hepatitis_viral_acute_by_type_b_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:vxsn-2csw d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:hepatitis_viral_acute_by_type_a_previous_52_weeks_max=100 m:hepatitis_viral_acute_by_type_b_cum_2016=58 m:hepatitis_viral_acute_by_type_b_cum_2017=13 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_med=54 m:hepatitis_viral_acute_by_type_b_current_week=13 m:hepatitis_viral_acute_by_type_a_previous_52_weeks_med=31 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_max=79 m:hepatitis_viral_acute_by_type_a_cum_2017=7 m:hepatitis_viral_acute_by_type_a_cum_2016=23 m:hepatitis_viral_acute_by_type_a_current_week=7

series e:vxsn-2csw d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:hepatitis_viral_acute_by_type_a_previous_52_weeks_max=4 m:hepatitis_viral_acute_by_type_b_cum_2016=1 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_med=1 m:hepatitis_viral_acute_by_type_a_previous_52_weeks_med=2 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_max=4 m:hepatitis_viral_acute_by_type_a_cum_2016=1

series e:vxsn-2csw d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:hepatitis_viral_acute_by_type_a_previous_52_weeks_max=10 m:hepatitis_viral_acute_by_type_b_cum_2016=4 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_med=4 m:hepatitis_viral_acute_by_type_a_previous_52_weeks_med=4 m:hepatitis_viral_acute_by_type_b_previous_52_weeks_max=7 m:hepatitis_viral_acute_by_type_a_cum_2017=1 m:hepatitis_viral_acute_by_type_a_cum_2016=4 m:hepatitis_viral_acute_by_type_a_current_week=1
```

## Meta Commands

```ls
metric m:hepatitis_viral_acute_by_type_a_current_week p:long l:"Hepatitis (viral, acute, by type), A, Current week" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_a_previous_52_weeks_med p:long l:"Hepatitis (viral, acute, by type), A, Previous 52 weeks Med" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_a_previous_52_weeks_max p:long l:"Hepatitis (viral, acute, by type), A, Previous 52 weeks Max" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_a_cum_2017 p:long l:"Hepatitis (viral, acute, by type), A, Cum 2017" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_a_cum_2016 p:long l:"Hepatitis (viral, acute, by type), A, Cum 2016" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_b_current_week p:long l:"Hepatitis (viral, acute, by type), B, Current week" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_b_previous_52_weeks_med p:long l:"Hepatitis (viral, acute, by type), B, Previous 52 weeks Med" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_b_previous_52_weeks_max p:long l:"Hepatitis (viral, acute, by type), B, Previous 52 weeks Max" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_b_cum_2017 p:long l:"Hepatitis (viral, acute, by type), B, Cum 2017" t:dataTypeName=number

metric m:hepatitis_viral_acute_by_type_b_cum_2016 p:long l:"Hepatitis (viral, acute, by type), B, Cum 2016" t:dataTypeName=number

entity e:vxsn-2csw l:"NNDSS - Table II. Hepatitis (viral, acute) A & B" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/vxsn-2csw

property e:vxsn-2csw t:meta.view v:id=vxsn-2csw v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Hepatitis (viral, acute) A & B" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:vxsn-2csw t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:vxsn-2csw t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:vxsn-2csw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | hepatitis_viral_acute_by_type_a_current_week | hepatitis_viral_acute_by_type_a_current_week_flag | hepatitis_viral_acute_by_type_a_previous_52_weeks_med | hepatitis_viral_acute_by_type_a_previous_52_weeks_med_flag | hepatitis_viral_acute_by_type_a_previous_52_weeks_max | hepatitis_viral_acute_by_type_a_previous_52_weeks_max_flag | hepatitis_viral_acute_by_type_a_cum_2017 | hepatitis_viral_acute_by_type_a_cum_2017_flag | hepatitis_viral_acute_by_type_a_cum_2016 | hepatitis_viral_acute_by_type_a_cum_2016_flag | hepatitis_viral_acute_by_type_b_current_week | hepatitis_viral_acute_by_type_b_current_week_flag | hepatitis_viral_acute_by_type_b_previous_52_weeks_med | hepatitis_viral_acute_by_type_b_previous_52_weeks_med_flag | hepatitis_viral_acute_by_type_b_previous_52_weeks_max | hepatitis_viral_acute_by_type_b_previous_52_weeks_max_flag | hepatitis_viral_acute_by_type_b_cum_2017 | hepatitis_viral_acute_by_type_b_cum_2017_flag | hepatitis_viral_acute_by_type_b_cum_2016 | hepatitis_viral_acute_by_type_b_cum_2016_flag | 
| ============== | ========= | ========= | ============================================ | ================================================= | ===================================================== | ========================================================== | ===================================================== | ========================================================== | ======================================== | ============================================= | ======================================== | ============================================= | ============================================ | ================================================= | ===================================================== | ========================================================== | ===================================================== | ========================================================== | ======================================== | ============================================= | ======================================== | ============================================= | 
| UNITED STATES  | 2017      | 1         | 7                                            |                                                   | 31                                                    |                                                            | 100                                                   |                                                            | 7                                        |                                               | 23                                       |                                               | 13                                           |                                                   | 54                                                    |                                                            | 79                                                    |                                                            | 13                                       |                                               | 58                                       |                                               | 
| NEW ENGLAND    | 2017      | 1         |                                              | -                                                 | 2                                                     |                                                            | 4                                                     |                                                            |                                          | -                                             | 1                                        |                                               |                                              | -                                                 | 1                                                     |                                                            | 4                                                     |                                                            |                                          | -                                             | 1                                        |                                               | 
| MID. ATLANTIC  | 2017      | 1         | 1                                            |                                                   | 4                                                     |                                                            | 10                                                    |                                                            | 1                                        |                                               | 4                                        |                                               |                                              | -                                                 | 4                                                     |                                                            | 7                                                     |                                                            |                                          | -                                             | 4                                        |                                               | 
| NEW YORK CITY  | 2017      | 1         |                                              | -                                                 | 1                                                     |                                                            | 3                                                     |                                                            |                                          | -                                             | 1                                        |                                               |                                              | -                                                 | 1                                                     |                                                            | 3                                                     |                                                            |                                          | -                                             | 1                                        |                                               | 
| E.N. CENTRAL   | 2017      | 1         |                                              | -                                                 | 3                                                     |                                                            | 8                                                     |                                                            |                                          | -                                             | 4                                        |                                               | 2                                            |                                                   | 11                                                    |                                                            | 20                                                    |                                                            | 2                                        |                                               | 13                                       |                                               | 
| W.N. CENTRAL   | 2017      | 1         |                                              | -                                                 | 1                                                     |                                                            | 5                                                     |                                                            |                                          | -                                             |                                          | -                                             |                                              | -                                                 | 1                                                     |                                                            | 7                                                     |                                                            |                                          | -                                             | 4                                        |                                               | 
| S. ATLANTIC    | 2017      | 1         | 3                                            |                                                   | 7                                                     |                                                            | 55                                                    |                                                            | 3                                        |                                               | 9                                        |                                               | 6                                            |                                                   | 19                                                    |                                                            | 34                                                    |                                                            | 6                                        |                                               | 17                                       |                                               | 
| MARYLAND       | 2017      | 1         |                                              | -                                                 | 0                                                     |                                                            | 5                                                     |                                                            |                                          | -                                             |                                          | -                                             |                                              | -                                                 | 0                                                     |                                                            | 3                                                     |                                                            |                                          | -                                             |                                          | -                                             | 
| E.S. CENTRAL   | 2017      | 1         |                                              | -                                                 | 1                                                     |                                                            | 4                                                     |                                                            |                                          | -                                             | 2                                        |                                               | 3                                            |                                                   | 9                                                     |                                                            | 18                                                    |                                                            | 3                                        |                                               | 13                                       |                                               | 
| W.S. CENTRAL   | 2017      | 1         |                                              | -                                                 | 3                                                     |                                                            | 7                                                     |                                                            |                                          | -                                             |                                          | -                                             | 1                                            |                                                   | 4                                                     |                                                            | 14                                                    |                                                            | 1                                        |                                               | 1                                        |                                               | 
```