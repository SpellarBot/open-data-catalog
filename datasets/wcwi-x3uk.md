# NNDSS - Table I. infrequently reported notifiable diseases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-i-infrequently-reported-notifiable-diseases-d8610) |
| Metadata | [Link](https://data.cdc.gov/api/views/wcwi-x3uk) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/wcwi-x3uk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/wcwi-x3uk/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | wcwi-x3uk |
| Name | NNDSS - Table I. infrequently reported notifiable diseases |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2014, mmwr, nndss, wonder, nedss, netss, anthrax, arboviral diseases, california serogroup virus disease, encephalitis, eastern equinevirus disease, powassan virus disease, st. louis virus disease... |
| Created | 2014-03-10T00:22:47Z |
| Publication Date | 2015-01-12T19:15:18Z |

## Description

NNDSS - Table I. infrequently reported notifiable diseases - 2014.In this Table, provisional cases of selected infrequently reported notifiable diseases (<1,000 cases reported during the preceding year) are displayed.  Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in these tables are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnote:-: No reported cases    N: Not reportable    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts. * Case counts for reporting year 2014 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. ??? Calculated by summing the incidence counts for the current week, the 2 weeks preceding the current week, and the 2 weeks following the current week, for a total of 5 preceding years. The total sum of incident cases is then divided by 25 weeks. Additional information is available at http://wwwn.cdc.gov/nndss/document/5yearweeklyaverage.pdf. ?? Not reportable in all states. Data from states where the condition is not reportable are excluded from this table except starting in 2007 for the Arboviral diseases, STD data, TB data, and influenza-associated pediatric mortality, and in 2003 for SARS-CoV. Reporting exceptions are available at http://wwwn.cdc.gov/nndss/document/SRCA_FINAL_REPORT_2006-2012_final.xlsx. ?? Includes both neuroinvasive and nonneuroinvasive. Updated weekly from reports to the Division of Vector-Borne Infectious Diseases, National Center for Zoonotic, Vector-Borne, and Enteric Diseases (ArboNET Surveillance). Data for West Nile virus are available in Table II. ** Data for H. influenzae (all ages, all serotypes) are available in Table II. ????? Updated weekly from reports to the Influenza Division, National Center for Immunization and Respiratory Diseases. Please refer to the MMWR publication for weekly updates to the footnote for this condition. ???? Please refer to the MMWR publication for weekly updates to the footnote for this condition. ???? Data for meningococcal disease (all serogroups) are available in Table II. *** Please refer to the MMWR publication for weekly updates to the footnote for this condition. ??????? Please refer to the MMWR publication for weekly updates to the footnote for this condition. ?????? Updated weekly from reports to the Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention. ?????? Please refer to the MMWR publication for weekly updates to the footnote for this condition. See Table II for Dengue Hemorrhagic Fever.More information on NNDSS is available at http://wwwn.cdc.gov/nndss/.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                             | Data Type | Render Type |
| ======== | ============== | ============================================= | ================================================ | ========= | =========== |
| Yes      | series tag     | disease                                       | Disease                                          | text      | text        |
| No       |                | mmwr_year                                     | MMWR year                                        | number    | number      |
| No       |                | mmwr_week                                     | MMWR week                                        | number    | number      |
| Yes      | numeric metric | current_week                                  | Current week                                     | number    | number      |
| No       |                | current_week_flag                             | Current week, flag                               | text      | text        |
| Yes      | numeric metric | cum_2014                                      | Cum 2014                                         | number    | number      |
| No       |                | cum_2014_flag                                 | Cum 2014, flag                                   | text      | text        |
| Yes      | numeric metric | 5_year_weekly_average                         | 5-year weekly average?                           | number    | number      |
| No       |                | 5_year_weekly_average_flag                    | 5-year weekly average?, flag                     | text      | text        |
| Yes      | numeric metric | total_cases_reported_2013                     | Total cases reported 2013                        | number    | number      |
| No       |                | total_cases_reported_2013_flag                | Total cases reported 2013, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2012                     | Total cases reported 2012                        | number    | number      |
| No       |                | total_cases_reported_2012_flag                | Total cases reported 2012, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2011                     | Total cases reported 2011                        | number    | number      |
| No       |                | total_cases_reported_2011_flag                | Total cases reported 2011, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2010                     | Total cases reported 2010                        | number    | number      |
| No       |                | total_cases_reported_2010_flag                | Total cases reported 2010, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2009                     | Total cases reported 2009                        | number    | number      |
| No       |                | total_cases_reported_2009_flag                | Total cases reported 2009, flag                  | text      | text        |
| Yes      | series tag     | states_reporting_cases_during_current_week_no | States reporting cases during current week (No.) | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = current_week_flag,cum_2014_flag,5_year_weekly_average_flag,total_cases_reported_2013_flag,total_cases_reported_2012_flag,total_cases_reported_2011_flag,total_cases_reported_2010_flag,total_cases_reported_2009_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:wcwi-x3uk d:2013-12-29T00:00:00.000Z t:disease=Anthrax m:total_cases_reported_2011=1 m:total_cases_reported_2009=1

series e:wcwi-x3uk d:2013-12-29T00:00:00.000Z t:disease="Arboviral diseases, California serogroup virus disease?,?" m:total_cases_reported_2011=137 m:total_cases_reported_2010=75 m:total_cases_reported_2013=81 m:total_cases_reported_2012=81 m:total_cases_reported_2009=55

series e:wcwi-x3uk d:2013-12-29T00:00:00.000Z t:disease="Arboviral diseases, Eastern equine encephalitis virus disease?,?" m:total_cases_reported_2011=4 m:total_cases_reported_2010=10 m:5_year_weekly_average=0 m:total_cases_reported_2013=6 m:total_cases_reported_2012=15 m:total_cases_reported_2009=4
```

## Meta Commands

```ls
metric m:current_week p:integer l:"Current week" t:dataTypeName=number

metric m:cum_2014 p:integer l:"Cum 2014" t:dataTypeName=number

metric m:5_year_weekly_average p:integer l:"5-year weekly average?" t:dataTypeName=number

metric m:total_cases_reported_2013 p:integer l:"Total cases reported 2013" t:dataTypeName=number

metric m:total_cases_reported_2012 p:integer l:"Total cases reported 2012" t:dataTypeName=number

metric m:total_cases_reported_2011 p:integer l:"Total cases reported 2011" t:dataTypeName=number

metric m:total_cases_reported_2010 p:integer l:"Total cases reported 2010" t:dataTypeName=number

metric m:total_cases_reported_2009 p:integer l:"Total cases reported 2009" t:dataTypeName=number

entity e:wcwi-x3uk l:"NNDSS - Table I. infrequently reported notifiable diseases" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/wcwi-x3uk

property e:wcwi-x3uk t:meta.view v:id=wcwi-x3uk v:category=NNDSS v:averageRating=100 v:name="NNDSS - Table I. infrequently reported notifiable diseases" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:wcwi-x3uk t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:wcwi-x3uk t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:wcwi-x3uk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| disease                                                          | mmwr_year | mmwr_week | current_week | current_week_flag | cum_2014 | cum_2014_flag | 5_year_weekly_average | 5_year_weekly_average_flag | total_cases_reported_2013 | total_cases_reported_2013_flag | total_cases_reported_2012 | total_cases_reported_2012_flag | total_cases_reported_2011 | total_cases_reported_2011_flag | total_cases_reported_2010 | total_cases_reported_2010_flag | total_cases_reported_2009 | total_cases_reported_2009_flag | states_reporting_cases_during_current_week_no | 
| ================================================================ | ========= | ========= | ============ | ================= | ======== | ============= | ===================== | ========================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ============================================= | 
| Anthrax                                                          | 2014      | 1         |              | -                 |          | -             |                       | -                          |                           | -                              |                           | -                              | 1                         |                                |                           | -                              | 1                         |                                |                                               | 
| Arboviral diseases, California serogroup virus disease?,?        | 2014      | 1         |              | -                 |          | -             |                       | -                          | 81                        |                                | 81                        |                                | 137                       |                                | 75                        |                                | 55                        |                                |                                               | 
| Arboviral diseases, Eastern equine encephalitis virus disease?,? | 2014      | 1         |              | -                 |          | -             | 0                     |                            | 6                         |                                | 15                        |                                | 4                         |                                | 10                        |                                | 4                         |                                |                                               | 
| Arboviral diseases, Powassan virus disease?,?                    | 2014      | 1         |              | -                 |          | -             | 0                     |                            | 12                        |                                | 7                         |                                | 16                        |                                | 8                         |                                | 6                         |                                |                                               | 
| Arboviral diseases, St. Louis encephalitis virus disease?,?      | 2014      | 1         |              | -                 |          | -             | 0                     |                            |                           | -                              | 3                         |                                | 6                         |                                | 10                        |                                | 12                        |                                |                                               | 
| Arboviral diseases, Western equine encephalitis virus disease?,? | 2014      | 1         |              | -                 |          | -             |                       | -                          |                           | -                              |                           | -                              |                           | -                              |                           | -                              |                           | -                              |                                               | 
| Botulism, total                                                  | 2014      | 1         | 1            |                   | 1        |               | 3                     |                            | 131                       |                                | 168                       |                                | 153                       |                                | 112                       |                                | 118                       |                                |                                               | 
| Botulism, foodborne                                              | 2014      | 1         |              | -                 |          | -             | 0                     |                            | 5                         |                                | 27                        |                                | 24                        |                                | 7                         |                                | 10                        |                                |                                               | 
| Botulism, infant                                                 | 2014      | 1         |              | -                 |          | -             | 2                     |                            | 115                       |                                | 123                       |                                | 97                        |                                | 80                        |                                | 83                        |                                |                                               | 
| Botulism, other (wound and unspecified)                          | 2014      | 1         | 1            |                   | 1        |               | 1                     |                            | 11                        |                                | 18                        |                                | 32                        |                                | 25                        |                                | 25                        |                                | CA (1 )                                       | 
```