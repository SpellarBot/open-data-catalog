# NNDSS - Table II. Babesiosis to Campylobacteriosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-babesiosis-to-campylobacteriosis-79dee) |
| Metadata | [Link](https://data.cdc.gov/api/views/xuah-ug7z) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/xuah-ug7z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/xuah-ug7z/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | xuah-ug7z |
| Name | NNDSS - Table II. Babesiosis to Campylobacteriosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, babesiosis, campylobacteriosis |
| Created | 2017-01-12T18:46:13Z |
| Publication Date | 2017-04-20T18:22:45Z |

## Description

NNDSS - Table II. Babesiosis to Campylobacteriosis - 2017. In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

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
| Included | Schema Type    | Field Name                                    | Name                                            | Data Type | Render Type |
| ======== | ============== | ============================================= | =============================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                | Reporting Area                                  | text      | text        |
| No       |                | mmwr_year                                     | MMWR Year                                       | number    | number      |
| No       |                | mmwr_week                                     | MMWR Week                                       | number    | number      |
| Yes      | numeric metric | babesiosis_current_week                       | Babesiosis, Current week                        | number    | number      |
| No       |                | babesiosis_current_week_flag                  | Babesiosis, Current week, flag                  | text      | text        |
| Yes      | numeric metric | babesiosis_previous_52_weeks_med              | Babesiosis, Previous 52 weeks Med               | number    | number      |
| No       |                | babesiosis_previous_52_weeks_med_flag         | Babesiosis, Previous 52 weeks Med, flag         | text      | text        |
| Yes      | numeric metric | babesiosis_previous_52_weeks_max              | Babesiosis, Previous 52 weeks Max               | number    | number      |
| No       |                | babesiosis_previous_52_weeks_max_flag         | Babesiosis, Previous 52 weeks Max, flag         | text      | text        |
| Yes      | numeric metric | babesiosis_cum_2017                           | Babesiosis, Cum 2017                            | number    | number      |
| No       |                | babesiosis_cum_2017_flag                      | Babesiosis, Cum 2017, flag                      | text      | text        |
| Yes      | numeric metric | babesiosis_cum_2016                           | Babesiosis, Cum 2016                            | number    | number      |
| No       |                | babesiosis_cum_2016_flag                      | Babesiosis, Cum 2016, flag                      | text      | text        |
| Yes      | numeric metric | campylobacteriosis_current_week               | Campylobacteriosis, Current week                | number    | number      |
| No       |                | campylobacteriosis_current_week_flag          | Campylobacteriosis, Current week, flag          | text      | text        |
| Yes      | numeric metric | campylobacteriosis_previous_52_weeks_med      | Campylobacteriosis, Previous 52 weeks Med       | number    | number      |
| No       |                | campylobacteriosis_previous_52_weeks_med_flag | Campylobacteriosis, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | campylobacteriosis_previous_52_weeks_max      | Campylobacteriosis, Previous 52 weeks Max       | number    | number      |
| No       |                | campylobacteriosis_previous_52_weeks_max_flag | Campylobacteriosis, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | campylobacteriosis_cum_2017                   | Campylobacteriosis, Cum 2017                    | number    | number      |
| No       |                | campylobacteriosis_cum_2017_flag              | Campylobacteriosis, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | campylobacteriosis_cum_2016                   | Campylobacteriosis, Cum 2016                    | number    | number      |
| No       |                | campylobacteriosis_cum_2016_flag              | Campylobacteriosis, Cum 2016, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = babesiosis_current_week_flag,babesiosis_previous_52_weeks_med_flag,babesiosis_previous_52_weeks_max_flag,babesiosis_cum_2017_flag,babesiosis_cum_2016_flag,campylobacteriosis_current_week_flag,campylobacteriosis_previous_52_weeks_med_flag,campylobacteriosis_previous_52_weeks_max_flag,campylobacteriosis_cum_2017_flag,campylobacteriosis_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:xuah-ug7z d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:babesiosis_previous_52_weeks_max=139 m:babesiosis_previous_52_weeks_med=11 m:campylobacteriosis_previous_52_weeks_med=961 m:campylobacteriosis_cum_2016=713 m:babesiosis_current_week=3 m:campylobacteriosis_current_week=256 m:campylobacteriosis_cum_2017=256 m:babesiosis_cum_2016=5 m:campylobacteriosis_previous_52_weeks_max=1519 m:babesiosis_cum_2017=3

series e:xuah-ug7z d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:babesiosis_previous_52_weeks_max=101 m:babesiosis_previous_52_weeks_med=4 m:campylobacteriosis_previous_52_weeks_med=51 m:campylobacteriosis_cum_2016=38 m:campylobacteriosis_current_week=4 m:campylobacteriosis_cum_2017=4 m:babesiosis_cum_2016=4 m:campylobacteriosis_previous_52_weeks_max=98

series e:xuah-ug7z d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:babesiosis_previous_52_weeks_max=38 m:babesiosis_previous_52_weeks_med=5 m:campylobacteriosis_previous_52_weeks_med=135 m:campylobacteriosis_cum_2016=113 m:babesiosis_current_week=2 m:campylobacteriosis_current_week=61 m:campylobacteriosis_cum_2017=61 m:babesiosis_cum_2016=1 m:campylobacteriosis_previous_52_weeks_max=232 m:babesiosis_cum_2017=2
```

## Meta Commands

```ls
metric m:babesiosis_current_week p:long l:"Babesiosis, Current week" t:dataTypeName=number

metric m:babesiosis_previous_52_weeks_med p:long l:"Babesiosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:babesiosis_previous_52_weeks_max p:long l:"Babesiosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:babesiosis_cum_2017 p:long l:"Babesiosis, Cum 2017" t:dataTypeName=number

metric m:babesiosis_cum_2016 p:long l:"Babesiosis, Cum 2016" t:dataTypeName=number

metric m:campylobacteriosis_current_week p:long l:"Campylobacteriosis, Current week" t:dataTypeName=number

metric m:campylobacteriosis_previous_52_weeks_med p:long l:"Campylobacteriosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:campylobacteriosis_previous_52_weeks_max p:long l:"Campylobacteriosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:campylobacteriosis_cum_2017 p:long l:"Campylobacteriosis, Cum 2017" t:dataTypeName=number

metric m:campylobacteriosis_cum_2016 p:long l:"Campylobacteriosis, Cum 2016" t:dataTypeName=number

entity e:xuah-ug7z l:"NNDSS - Table II. Babesiosis to Campylobacteriosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/xuah-ug7z

property e:xuah-ug7z t:meta.view v:id=xuah-ug7z v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Babesiosis to Campylobacteriosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:xuah-ug7z t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:xuah-ug7z t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:xuah-ug7z t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | babesiosis_current_week | babesiosis_current_week_flag | babesiosis_previous_52_weeks_med | babesiosis_previous_52_weeks_med_flag | babesiosis_previous_52_weeks_max | babesiosis_previous_52_weeks_max_flag | babesiosis_cum_2017 | babesiosis_cum_2017_flag | babesiosis_cum_2016 | babesiosis_cum_2016_flag | campylobacteriosis_current_week | campylobacteriosis_current_week_flag | campylobacteriosis_previous_52_weeks_med | campylobacteriosis_previous_52_weeks_med_flag | campylobacteriosis_previous_52_weeks_max | campylobacteriosis_previous_52_weeks_max_flag | campylobacteriosis_cum_2017 | campylobacteriosis_cum_2017_flag | campylobacteriosis_cum_2016 | campylobacteriosis_cum_2016_flag | 
| ============== | ========= | ========= | ======================= | ============================ | ================================ | ===================================== | ================================ | ===================================== | =================== | ======================== | =================== | ======================== | =============================== | ==================================== | ======================================== | ============================================= | ======================================== | ============================================= | =========================== | ================================ | =========================== | ================================ | 
| UNITED STATES  | 2017      | 1         | 3                       |                              | 11                               |                                       | 139                              |                                       | 3                   |                          | 5                   |                          | 256                             |                                      | 961                                      |                                               | 1519                                     |                                               | 256                         |                                  | 713                         |                                  | 
| NEW ENGLAND    | 2017      | 1         |                         | -                            | 4                                |                                       | 101                              |                                       |                     | -                        | 4                   |                          | 4                               |                                      | 51                                       |                                               | 98                                       |                                               | 4                           |                                  | 38                          |                                  | 
| MID. ATLANTIC  | 2017      | 1         | 2                       |                              | 5                                |                                       | 38                               |                                       | 2                   |                          | 1                   |                          | 61                              |                                      | 135                                      |                                               | 232                                      |                                               | 61                          |                                  | 113                         |                                  | 
| NEW YORK CITY  | 2017      | 1         | 1                       |                              | 0                                |                                       | 9                                |                                       | 1                   |                          |                     | -                        | 42                              |                                      | 33                                       |                                               | 54                                       |                                               | 42                          |                                  | 36                          |                                  | 
| E.N. CENTRAL   | 2017      | 1         | 1                       |                              | 1                                |                                       | 6                                |                                       | 1                   |                          |                     | -                        | 36                              |                                      | 140                                      |                                               | 249                                      |                                               | 36                          |                                  | 119                         |                                  | 
| W.N. CENTRAL   | 2017      | 1         |                         | -                            | 0                                |                                       | 1                                |                                       |                     | -                        |                     | -                        | 6                               |                                      | 72                                       |                                               | 155                                      |                                               | 6                           |                                  | 72                          |                                  | 
| S. ATLANTIC    | 2017      | 1         |                         | -                            | 0                                |                                       | 4                                |                                       |                     | -                        |                     | -                        | 41                              |                                      | 133                                      |                                               | 212                                      |                                               | 41                          |                                  | 103                         |                                  | 
| E.S. CENTRAL   | 2017      | 1         |                         | -                            | 0                                |                                       | 1                                |                                       |                     | -                        |                     | -                        | 13                              |                                      | 43                                       |                                               | 72                                       |                                               | 13                          |                                  | 44                          |                                  | 
| W.S. CENTRAL   | 2017      | 1         |                         | -                            | 0                                |                                       | 1                                |                                       |                     | -                        |                     | -                        | 8                               |                                      | 105                                      |                                               | 234                                      |                                               | 8                           |                                  | 8                           |                                  | 
| MOUNTAIN       | 2017      | 1         |                         | -                            | 0                                |                                       | 1                                |                                       |                     | -                        |                     | -                        | 30                              |                                      | 61                                       |                                               | 109                                      |                                               | 30                          |                                  | 56                          |                                  | 
```