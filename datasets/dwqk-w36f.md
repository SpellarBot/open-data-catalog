# NNDSS - Table I. infrequently reported notifiable diseases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-i-infrequently-reported-notifiable-diseases) |
| Metadata | [Link](https://data.cdc.gov/api/views/dwqk-w36f) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/dwqk-w36f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/dwqk-w36f/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | dwqk-w36f |
| Name | NNDSS - Table I. infrequently reported notifiable diseases |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, anthrax, arboviral diseases, chikungunya virus disease, eastern equine encephalitis virus disease, jamestown canyon virus, la crosse virus, powassan virus ... |
| Created | 2016-01-11T19:35:27Z |
| Publication Date | 2017-01-05T16:46:43Z |

## Description

NNDSS - Table I. infrequently reported notifiable diseases - 2016.  In this Table, provisional* cases of selected? infrequently reported notifiable diseases (<1,000 cases reported during the preceding year) are displayed.  
Note:

These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in these tables are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

?Symbols and footnotes changed in week #4, please refer to the MMWR publication for the symbols/footnotes for weeks 1, 2, and 3?.

Footnote:
-: No reported cases    N: Not reportable    NA: Not available NN: Not Nationally Notifiable.  NP:  Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.
* Case counts for reporting year 2016 are provisional and subject to change.  Data for years 2011 through 2015 are finalized. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. 
? This table does not include cases from the U.S. territories. Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions.  
? Calculated by summing the incidence counts for the current week, the 2 weeks preceding the current week, and the 2 weeks following the current week, for a total of 5 preceding years.  Additional information is available at http://wwwn.cdc.gov/nndss/document/5yearweeklyaverage.pdf. 
? Includes both neuroinvasive and nonneuroinvasive. Updated weekly reports from the Division of Vector-Borne Diseases, National Center for Emerging and Zoonotic Infectious Diseases (ArboNET Surveillance). Data for West Nile virus are available in Table II. 
** Not reportable in all reporting jurisdictions. Data from states where the condition is not reportable are excluded from this table, except for the arboviral diseases and influenza-associated pediatric mortality. Reporting exceptions are available at http://wwwn.cdc.gov/nndss/downloads.html.
?? Office of Management and Budget approval of the NNDSS Revision #0920-0728 on January 21, 2016, authorized CDC to receive data for these conditions. CDC is in the process
of soliciting data for these conditions (except Zika virus, congenital infection). CDC and the U.S. states are still modifying the technical infrastructure needed to collect and transmit data for Zika virus congenital infections.
?? Jamestown Canyon virus and Lacrosse virus have replaced California serogroup diseases.
?? Data for Haemophilus influenzae (all ages, all serotypes) are available in Table II.
***  Please refer to the MMWR publication for weekly updates to the footnote for this condition.  
??? Please refer to the MMWR publication for weekly updates to the footnote for this condition. 
??? Data for meningococcal disease (all serogroups) are available in Table II. 
??? Please refer to the MMWR publication for weekly updates to the footnote for this condition. 
**** Updated weekly from reports to the Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention. 
???? Please refer to the MMWR publication for weekly updates to the footnote for this condition. 
???? All cases reported have occurred in travelers returning from affected areas, with their sexual contacts, or infants infected in utero.

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                             | Data Type | Render Type |
| ======== | ============== | ============================================= | ================================================ | ========= | =========== |
| Yes      | series tag     | disease                                       | Disease                                          | text      | text        |
| No       |                | mmwr_year                                     | MMWR year                                        | number    | number      |
| No       |                | mmwr_week                                     | MMWR week                                        | number    | number      |
| Yes      | numeric metric | current_week                                  | Current week                                     | number    | number      |
| No       |                | current_week_flag                             | Current week, flag                               | text      | text        |
| Yes      | numeric metric | cum_2016                                      | Cum 2016                                         | number    | number      |
| No       |                | cum_2016_flag                                 | Cum 2016, flag                                   | text      | text        |
| Yes      | numeric metric | 5_year_weekly_average                         | 5-year weekly average?                           | number    | number      |
| No       |                | 5_year_weekly_average_flag                    | 5-year weekly average?, flag                     | text      | text        |
| Yes      | numeric metric | total_cases_reported_2015                     | Total cases reported 2015                        | number    | number      |
| No       |                | total_cases_reported_2015_flag                | Total cases reported 2015, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2014                     | Total cases reported 2014                        | number    | number      |
| No       |                | total_cases_reported_2014_flag                | Total cases reported 2014, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2013                     | Total cases reported 2013                        | number    | number      |
| No       |                | total_cases_reported_2013_flag                | Total cases reported 2013, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2012                     | Total cases reported 2012                        | number    | number      |
| No       |                | total_cases_reported_2012_flag                | Total cases reported 2012, flag                  | text      | text        |
| Yes      | numeric metric | total_cases_reported_2011                     | Total cases reported 2011                        | number    | number      |
| No       |                | total_cases_reported_2011_flag                | Total cases reported 2011, flag                  | text      | text        |
| Yes      | series tag     | states_reporting_cases_during_current_week_no | States reporting cases during current week (No.) | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = current_week_flag,cum_2016_flag,5_year_weekly_average_flag,total_cases_reported_2015_flag,total_cases_reported_2014_flag,total_cases_reported_2013_flag,total_cases_reported_2012_flag,total_cases_reported_2011_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:dwqk-w36f d:2015-12-27T00:00:00.000Z t:disease=Anthrax m:total_cases_reported_2011=1

series e:dwqk-w36f d:2015-12-27T00:00:00.000Z t:disease="Arboviral diseases?,** Eastern equine encephalitis virus" m:total_cases_reported_2011=4 m:5_year_weekly_average=0 m:total_cases_reported_2015=5 m:total_cases_reported_2014=8 m:total_cases_reported_2013=8 m:total_cases_reported_2012=15

series e:dwqk-w36f d:2015-12-27T00:00:00.000Z t:disease="Arboviral diseases?,** Jamestown Canyon virus??" m:total_cases_reported_2011=3 m:total_cases_reported_2015=7 m:total_cases_reported_2014=11 m:total_cases_reported_2013=22 m:total_cases_reported_2012=2
```

## Meta Commands

```ls
metric m:current_week p:integer l:"Current week" t:dataTypeName=number

metric m:cum_2016 p:integer l:"Cum 2016" t:dataTypeName=number

metric m:5_year_weekly_average p:integer l:"5-year weekly average?" t:dataTypeName=number

metric m:total_cases_reported_2015 p:integer l:"Total cases reported 2015" t:dataTypeName=number

metric m:total_cases_reported_2014 p:integer l:"Total cases reported 2014" t:dataTypeName=number

metric m:total_cases_reported_2013 p:integer l:"Total cases reported 2013" t:dataTypeName=number

metric m:total_cases_reported_2012 p:integer l:"Total cases reported 2012" t:dataTypeName=number

metric m:total_cases_reported_2011 p:integer l:"Total cases reported 2011" t:dataTypeName=number

entity e:dwqk-w36f l:"NNDSS - Table I. infrequently reported notifiable diseases" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/dwqk-w36f

property e:dwqk-w36f t:meta.view v:id=dwqk-w36f v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table I. infrequently reported notifiable diseases" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:dwqk-w36f t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:dwqk-w36f t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:dwqk-w36f t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| disease                                                  | mmwr_year | mmwr_week | current_week | current_week_flag | cum_2016 | cum_2016_flag | 5_year_weekly_average | 5_year_weekly_average_flag | total_cases_reported_2015 | total_cases_reported_2015_flag | total_cases_reported_2014 | total_cases_reported_2014_flag | total_cases_reported_2013 | total_cases_reported_2013_flag | total_cases_reported_2012 | total_cases_reported_2012_flag | total_cases_reported_2011 | total_cases_reported_2011_flag | states_reporting_cases_during_current_week_no | 
| ======================================================== | ========= | ========= | ============ | ================= | ======== | ============= | ===================== | ========================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ========================= | ============================== | ============================================= | 
| Anthrax                                                  | 2016      | 1         |              | -                 |          | -             |                       | -                          |                           | -                              |                           | -                              |                           | -                              |                           | -                              | 1                         |                                |                                               | 
| Arboviral diseases?,** Chikungunya virus??               | 2016      | 1         |              | NN                |          | NN            |                       | NN                         |                           | NN                             |                           | NN                             |                           | NN                             |                           | NN                             |                           | NN                             |                                               | 
| Arboviral diseases?,** Eastern equine encephalitis virus | 2016      | 1         |              | -                 |          | -             | 0                     |                            | 5                         |                                | 8                         |                                | 8                         |                                | 15                        |                                | 4                         |                                |                                               | 
| Arboviral diseases?,** Jamestown Canyon virus??          | 2016      | 1         |              | -                 |          | -             |                       | -                          | 7                         |                                | 11                        |                                | 22                        |                                | 2                         |                                | 3                         |                                |                                               | 
| Arboviral diseases?,** La Crosse virus??                 | 2016      | 1         |              | -                 |          | -             |                       | -                          | 48                        |                                | 80                        |                                | 85                        |                                | 78                        |                                | 130                       |                                |                                               | 
| Arboviral diseases?,** Powassan virus                    | 2016      | 1         |              | -                 |          | -             |                       | -                          | 6                         |                                | 8                         |                                | 12                        |                                | 7                         |                                | 16                        |                                |                                               | 
| Arboviral diseases?,** St. Louis encephalitis virus      | 2016      | 1         |              | -                 |          | -             | 0                     |                            | 19                        |                                | 10                        |                                | 1                         |                                | 3                         |                                | 6                         |                                |                                               | 
| Arboviral diseases?,** Western equine encephalitis virus | 2016      | 1         |              | -                 |          | -             |                       | -                          |                           | -                              |                           | -                              |                           | -                              |                           | -                              |                           | -                              |                                               | 
| Botulism, total                                          | 2016      | 1         |              | -                 |          | -             | 3                     |                            | 178                       |                                | 161                       |                                | 152                       |                                | 168                       |                                | 153                       |                                |                                               | 
| Botulism, foodborne                                      | 2016      | 1         |              | -                 |          | -             | 0                     |                            | 40                        |                                | 15                        |                                | 4                         |                                | 27                        |                                | 24                        |                                |                                               | 
```