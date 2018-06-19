# NNDSS - Table II. West Nile virus disease

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-west-nile-virus-disease) |
| Metadata | [Link](https://data.cdc.gov/api/views/sd5c-m3g5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/sd5c-m3g5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/sd5c-m3g5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | sd5c-m3g5 |
| Name | NNDSS - Table II. West Nile virus disease |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, west nile virus |
| Created | 2016-01-12T14:14:32Z |
| Publication Date | 2017-01-05T17:41:39Z |

## Description

NNDSS - Table II. West Nile virus disease - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.  The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.   NP:  Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. 

* Case counts for reporting year 2016 are provisional and subject to change.   For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table II to facilitate case count verification with reporting jurisdictions. 
? Updated weekly from the Division of Vector-Borne Diseases, National Center for Emerging and Zoonotic Infectious Diseases (ArboNET Surveillance).  Data for Jamestown Canyon virus, La Crosse virus, Chikungunya virus, Eastern equine encephalitis virus, Powassan virus, St. Louis virus, and Western equine encephalitis virus diseases are available in Table I. 
? Not reportable in all states. Reporting exceptions are available at http://wwwn.cdc.gov/nndss/downloads.html.

## Columns

```ls
| Included | Schema Type    | Field Name                                                          | Name                                                                     | Data Type | Render Type |
| ======== | ============== | =================================================================== | ======================================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                                      | Reporting Area                                                           | text      | text        |
| No       |                | mmwr_year                                                           | MMWR Year                                                                | number    | number      |
| No       |                | mmwr_week                                                           | MMWR Week                                                                | number    | number      |
| Yes      | numeric metric | west_nile_virus_disease_neuroinvasive_current_week                  | West Nile virus disease?, Neuroinvasive, Current week                    | number    | number      |
| No       |                | west_nile_virus_disease_neuroinvasive_current_week_flag             | West Nile virus disease?, Neuroinvasive, Current week, flag              | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_neuroinvasive_previous_52_weeks_med         | West Nile virus disease?, Neuroinvasive, Previous 52 weeks Med           | number    | number      |
| No       |                | west_nile_virus_disease_neuroinvasive_previous_52_weeks_med_flag    | West Nile virus disease?, Neuroinvasive, Previous 52 weeks Med, flag     | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_neuroinvasive_previous_52_weeks_max         | West Nile virus disease?, Neuroinvasive, Previous 52 weeks Max           | number    | number      |
| No       |                | west_nile_virus_disease_neuroinvasive_previous_52_weeks_max_flag    | West Nile virus disease?, Neuroinvasive, Previous 52 weeks Max, flag     | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_neuroinvasive_cum_2016                      | West Nile virus disease?, Neuroinvasive, Cum 2016                        | number    | number      |
| No       |                | west_nile_virus_disease_neuroinvasive_cum_2016_flag                 | West Nile virus disease?, Neuroinvasive, Cum 2016, flag                  | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_neuroinvasive_cum_2015                      | West Nile virus disease?, Neuroinvasive, Cum 2015                        | number    | number      |
| No       |                | west_nile_virus_disease_neuroinvasive_cum_2015_flag                 | West Nile virus disease?, Neuroinvasive, Cum 2015, flag                  | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_nonneuroinvasive_current_week               | West Nile virus disease?, Nonneuroinvasive?, Current week                | number    | number      |
| No       |                | west_nile_virus_disease_nonneuroinvasive_current_week_flag          | West Nile virus disease?, Nonneuroinvasive?, Current week, flag          | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med      | West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Med       | number    | number      |
| No       |                | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med_flag | West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max      | West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Max       | number    | number      |
| No       |                | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max_flag | West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_nonneuroinvasive_cum_2016                   | West Nile virus disease?, Nonneuroinvasive?, Cum 2016                    | number    | number      |
| No       |                | west_nile_virus_disease_nonneuroinvasive_cum_2016_flag              | West Nile virus disease?, Nonneuroinvasive?, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | west_nile_virus_disease_nonneuroinvasive_cum_2015                   | West Nile virus disease?, Nonneuroinvasive?, Cum 2015                    | number    | number      |
| No       |                | west_nile_virus_disease_nonneuroinvasive_cum_2015_flag              | West Nile virus disease?, Nonneuroinvasive?, Cum 2015, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = west_nile_virus_disease_neuroinvasive_current_week_flag,west_nile_virus_disease_neuroinvasive_previous_52_weeks_med_flag,west_nile_virus_disease_neuroinvasive_previous_52_weeks_max_flag,west_nile_virus_disease_neuroinvasive_cum_2016_flag,west_nile_virus_disease_neuroinvasive_cum_2015_flag,west_nile_virus_disease_nonneuroinvasive_current_week_flag,west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med_flag,west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max_flag,west_nile_virus_disease_nonneuroinvasive_cum_2016_flag,west_nile_virus_disease_nonneuroinvasive_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:sd5c-m3g5 d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_med=1 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med=1 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max=89 m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_max=149

series e:sd5c-m3g5 d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_med=0 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med=0 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max=2 m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_max=3

series e:sd5c-m3g5 d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_med=0 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med=0 m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max=6 m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_max=10
```

## Meta Commands

```ls
metric m:west_nile_virus_disease_neuroinvasive_current_week p:integer l:"West Nile virus disease?, Neuroinvasive, Current week" t:dataTypeName=number

metric m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_med p:integer l:"West Nile virus disease?, Neuroinvasive, Previous 52 weeks Med" t:dataTypeName=number

metric m:west_nile_virus_disease_neuroinvasive_previous_52_weeks_max p:integer l:"West Nile virus disease?, Neuroinvasive, Previous 52 weeks Max" t:dataTypeName=number

metric m:west_nile_virus_disease_neuroinvasive_cum_2016 p:integer l:"West Nile virus disease?, Neuroinvasive, Cum 2016" t:dataTypeName=number

metric m:west_nile_virus_disease_neuroinvasive_cum_2015 p:integer l:"West Nile virus disease?, Neuroinvasive, Cum 2015" t:dataTypeName=number

metric m:west_nile_virus_disease_nonneuroinvasive_current_week p:integer l:"West Nile virus disease?, Nonneuroinvasive?, Current week" t:dataTypeName=number

metric m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med p:integer l:"West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Med" t:dataTypeName=number

metric m:west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max p:integer l:"West Nile virus disease?, Nonneuroinvasive?, Previous 52 weeks Max" t:dataTypeName=number

metric m:west_nile_virus_disease_nonneuroinvasive_cum_2016 p:integer l:"West Nile virus disease?, Nonneuroinvasive?, Cum 2016" t:dataTypeName=number

metric m:west_nile_virus_disease_nonneuroinvasive_cum_2015 p:integer l:"West Nile virus disease?, Nonneuroinvasive?, Cum 2015" t:dataTypeName=number

entity e:sd5c-m3g5 l:"NNDSS - Table II. West Nile virus disease" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/sd5c-m3g5

property e:sd5c-m3g5 t:meta.view v:id=sd5c-m3g5 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. West Nile virus disease" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:sd5c-m3g5 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:sd5c-m3g5 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:sd5c-m3g5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | west_nile_virus_disease_neuroinvasive_current_week | west_nile_virus_disease_neuroinvasive_current_week_flag | west_nile_virus_disease_neuroinvasive_previous_52_weeks_med | west_nile_virus_disease_neuroinvasive_previous_52_weeks_med_flag | west_nile_virus_disease_neuroinvasive_previous_52_weeks_max | west_nile_virus_disease_neuroinvasive_previous_52_weeks_max_flag | west_nile_virus_disease_neuroinvasive_cum_2016 | west_nile_virus_disease_neuroinvasive_cum_2016_flag | west_nile_virus_disease_neuroinvasive_cum_2015 | west_nile_virus_disease_neuroinvasive_cum_2015_flag | west_nile_virus_disease_nonneuroinvasive_current_week | west_nile_virus_disease_nonneuroinvasive_current_week_flag | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_med_flag | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max | west_nile_virus_disease_nonneuroinvasive_previous_52_weeks_max_flag | west_nile_virus_disease_nonneuroinvasive_cum_2016 | west_nile_virus_disease_nonneuroinvasive_cum_2016_flag | west_nile_virus_disease_nonneuroinvasive_cum_2015 | west_nile_virus_disease_nonneuroinvasive_cum_2015_flag | 
| ============== | ========= | ========= | ================================================== | ======================================================= | =========================================================== | ================================================================ | =========================================================== | ================================================================ | ============================================== | =================================================== | ============================================== | =================================================== | ===================================================== | ========================================================== | ============================================================== | =================================================================== | ============================================================== | =================================================================== | ================================================= | ====================================================== | ================================================= | ====================================================== | 
| UNITED STATES  | 2016      | 1         |                                                    | -                                                       | 1                                                           |                                                                  | 149                                                         |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 1                                                              |                                                                     | 89                                                             |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| NEW ENGLAND    | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 3                                                           |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 2                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| MID. ATLANTIC  | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 10                                                          |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 6                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| NEW YORK CITY  | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 5                                                           |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 2                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| E.N. CENTRAL   | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 21                                                          |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 8                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| W.N. CENTRAL   | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 11                                                          |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 23                                                             |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| S. ATLANTIC    | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 11                                                          |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 8                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| DIST. OF COL.  | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 1                                                           |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 1                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| E.S. CENTRAL   | 2016      | 1         |                                                    | -                                                       | 0                                                           |                                                                  | 5                                                           |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 3                                                              |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
| W.S. CENTRAL   | 2016      | 1         |                                                    | -                                                       | 1                                                           |                                                                  | 34                                                          |                                                                  |                                                | -                                                   |                                                | -                                                   |                                                       | -                                                          | 0                                                              |                                                                     | 17                                                             |                                                                     |                                                   | -                                                      |                                                   | -                                                      | 
```