# Public Assistance and SNAP Fraud Prevention Performance Measures: Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-assistance-and-snap-fraud-prevention-performance-measures-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/uubd-eei2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/uubd-eei2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/uubd-eei2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | uubd-eei2 |
| Name | Public Assistance and SNAP Fraud Prevention Performance Measures: Beginning 2013 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | welfare, fraud, public assistance, snap |
| Created | 2016-05-09T16:54:14Z |
| Publication Date | 2017-04-17T22:00:47Z |

## Description

This dataset from the New York State Office of Temporary and Disability Assistance contains the results of several local district investigations initiated by flagged cases of the State?s cash public assistance programs and the Supplemental Nutrition Assistance Program (SNAP).  It includes information from the Front End Detection System (FEDS), from Intentional Program Violations (IPVs), from Prison matches and from the Public Assistance Reporting Information System (PARIS).

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                                                                 | Data Type | Render Type |
| ======== | ============== | =============================== | ==================================================================== | ========= | =========== |
| No       |                | year                            | Year                                                                 | number    | number      |
| No       |                | quarter                         | Quarter                                                              | number    | number      |
| Yes      | series tag     | district_cd                     | District Code                                                        | text      | text        |
| Yes      | series tag     | district                        | District                                                             | text      | text        |
| Yes      | numeric metric | feds_cases_referred             | Front End Detection System (FEDS) Cases Referred                     | percent   | percent     |
| Yes      | numeric metric | feds_total_investigated         | FEDS Total Investigated                                              | number    | number      |
| Yes      | numeric metric | feds_cases_denied_grant_reduced | FEDS Cases Denied/Grant Reduced                                      | percent   | percent     |
| Yes      | numeric metric | feds_cases_no_impact            | FEDS Cases No Impact                                                 | percent   | percent     |
| Yes      | numeric metric | feds_cases_no_errors            | FEDS Cases No Errors                                                 | percent   | percent     |
| Yes      | numeric metric | ipv_positive_investigations     | Intentional Program Violation (IPV) Positive Investigations          | number    | number      |
| Yes      | numeric metric | total_ipvs                      | Total IPVs                                                           | percent   | percent     |
| Yes      | numeric metric | prison_total_matches            | Prison Total Matches                                                 | number    | number      |
| Yes      | numeric metric | prison_closed_prior_resolved    | Prison Closed Prior Resolved                                         | percent   | percent     |
| Yes      | numeric metric | prison_closed_resolved          | Prison Closed Resolved                                               | percent   | percent     |
| Yes      | numeric metric | prison_exonerated_resolved      | Prison Exonerated Resolved                                           | percent   | percent     |
| Yes      | numeric metric | prison_unresolved               | Prison Unresolved                                                    | percent   | percent     |
| Yes      | numeric metric | paris_total_matches             | Public Assistance Reporting Information System (PARIS) Total Matches | number    | number      |
| Yes      | numeric metric | paris_closed_prior_resolved     | PARIS Closed Prior Resolved                                          | percent   | percent     |
| Yes      | numeric metric | paris_closed_resolved           | PARIS Closed Resolved                                                | percent   | percent     |
| Yes      | numeric metric | paris_exonerated_resolved       | PARIS Exonerated Resolved                                            | percent   | percent     |
| Yes      | numeric metric | paris_unresolved                | PARIS Unresolved                                                     | percent   | percent     |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:uubd-eei2 d:2013-01-01T00:00:00.000Z t:district_cd=01 t:district=Albany m:prison_unresolved=0 m:prison_closed_resolved=75 m:feds_total_investigated=33 m:prison_exonerated_resolved=25 m:total_ipvs=24 m:paris_closed_resolved=30 m:feds_cases_no_impact=0 m:paris_total_matches=215 m:ipv_positive_investigations=17 m:feds_cases_no_errors=39 m:paris_exonerated_resolved=60 m:paris_unresolved=0 m:prison_total_matches=65 m:prison_closed_prior_resolved=0 m:feds_cases_referred=1 m:feds_cases_denied_grant_reduced=61 m:paris_closed_prior_resolved=9

series e:uubd-eei2 d:2013-01-01T00:00:00.000Z t:district_cd=02 t:district=Allegany m:prison_unresolved=0 m:prison_closed_resolved=23 m:feds_total_investigated=42 m:prison_exonerated_resolved=69 m:total_ipvs=26 m:paris_closed_resolved=3 m:feds_cases_no_impact=5 m:paris_total_matches=61 m:ipv_positive_investigations=23 m:feds_cases_no_errors=88 m:paris_exonerated_resolved=93 m:paris_unresolved=0 m:prison_total_matches=13 m:prison_closed_prior_resolved=8 m:feds_cases_referred=5 m:feds_cases_denied_grant_reduced=7 m:paris_closed_prior_resolved=3

series e:uubd-eei2 d:2013-01-01T00:00:00.000Z t:district_cd=03 t:district=Broome m:prison_unresolved=0 m:prison_closed_resolved=61 m:feds_total_investigated=525 m:prison_exonerated_resolved=33 m:total_ipvs=0 m:paris_closed_resolved=7 m:feds_cases_no_impact=5 m:paris_total_matches=307 m:ipv_positive_investigations=0 m:feds_cases_no_errors=83 m:paris_exonerated_resolved=90 m:paris_unresolved=0 m:prison_total_matches=18 m:prison_closed_prior_resolved=6 m:feds_cases_referred=22 m:feds_cases_denied_grant_reduced=12 m:paris_closed_prior_resolved=3
```

## Meta Commands

```ls
metric m:feds_cases_referred p:integer l:"Front End Detection System (FEDS) Cases Referred" d:"Percentage of Front End Detection System (FEDS) new Temporary Assistance / Supplemental Nutrition Assistance Program (TA/SNAP) case applications that were referred for investigation." t:dataTypeName=percent

metric m:feds_total_investigated p:double l:"FEDS Total Investigated" d:"Number of Front End Detection System (FEDS) TA/SNAP case referrals that were investigated during the reporting period." t:dataTypeName=number

metric m:feds_cases_denied_grant_reduced p:double l:"FEDS Cases Denied/Grant Reduced" d:"Percentage of investigated TA/SNAP cases that were either denied or grant reduced." t:dataTypeName=percent

metric m:feds_cases_no_impact p:double l:"FEDS Cases No Impact" d:"Percentage of investigated TA/SNAP cases where a discrepancy was identified but it had no effect on the case?s budget." t:dataTypeName=percent

metric m:feds_cases_no_errors p:double l:"FEDS Cases No Errors" d:"Percentage of investigated TA/SNAP cases where no discrepancy was identified." t:dataTypeName=percent

metric m:ipv_positive_investigations p:float l:"Intentional Program Violation (IPV) Positive Investigations" d:"Number of Intentional Program Violations (IPVs) on TA/SNAP cases that were investigated during the reporting period." t:dataTypeName=number

metric m:total_ipvs p:double l:"Total IPVs" d:"Percentage of TA/SNAP cases that were investigated and resulted in an Intentional Program Violation (IPV)." t:dataTypeName=percent

metric m:prison_total_matches p:integer l:"Prison Total Matches" d:"Number of TA/SNAP recipients potentially in prison to be investigated during the reporting period." t:dataTypeName=number

metric m:prison_closed_prior_resolved p:double l:"Prison Closed Prior Resolved" d:"Percentage of TA/SNAP recipients on the Prison match that were closed before the case was investigated." t:dataTypeName=percent

metric m:prison_closed_resolved p:double l:"Prison Closed Resolved" d:"Percentage of TA/SNAP recipients on the Prison match that were closed as a result of the investigation." t:dataTypeName=percent

metric m:prison_exonerated_resolved p:double l:"Prison Exonerated Resolved" d:"Percentage of TA/SNAP recipients on the Prison match that were eligible for benefits as a result of the investigation." t:dataTypeName=percent

metric m:prison_unresolved p:double l:"Prison Unresolved" d:"Percentage of TA/SNAP cases on the Prison match that were not investigated during the reporting period." t:dataTypeName=percent

metric m:paris_total_matches p:integer l:"Public Assistance Reporting Information System (PARIS) Total Matches" d:"Number of TA/SNAP recipients potentially receiving benefits in another state to be investigated during the reporting period." t:dataTypeName=number

metric m:paris_closed_prior_resolved p:double l:"PARIS Closed Prior Resolved" d:"Percentage of TA/SNAP recipients on the Public Assistance Reporting Information System (PARIS) match that were closed before the case was investigated." t:dataTypeName=percent

metric m:paris_closed_resolved p:double l:"PARIS Closed Resolved" d:"Percentage of TA/SNAP recipients on the Public Assistance Reporting Information System (PARIS) match that were closed as a result of the investigation." t:dataTypeName=percent

metric m:paris_exonerated_resolved p:double l:"PARIS Exonerated Resolved" d:"Percentage of TA/SNAP recipients on the Public Assistance Reporting Information System (PARIS) match that were eligible for benefits as a result of the investigation." t:dataTypeName=percent

metric m:paris_unresolved p:double l:"PARIS Unresolved" d:"Percentage of TA/SNAP cases on the Public Assistance Reporting Information System (PARIS) match that were not investigated during the reporting period." t:dataTypeName=percent

entity e:uubd-eei2 l:"Public Assistance and SNAP Fraud Prevention Performance Measures:  Beginning 2013" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/uubd-eei2

property e:uubd-eei2 t:meta.view v:id=uubd-eei2 v:category="Human Services" v:attributionLink=https://otda.ny.gov/resources/welfare-fraud/ v:averageRating=0 v:name="Public Assistance and SNAP Fraud Prevention Performance Measures:  Beginning 2013" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)"

property e:uubd-eei2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:uubd-eei2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | quarter | district_cd | district    | feds_cases_referred | feds_total_investigated | feds_cases_denied_grant_reduced | feds_cases_no_impact | feds_cases_no_errors | ipv_positive_investigations | total_ipvs | prison_total_matches | prison_closed_prior_resolved | prison_closed_resolved | prison_exonerated_resolved | prison_unresolved | paris_total_matches | paris_closed_prior_resolved | paris_closed_resolved | paris_exonerated_resolved | paris_unresolved | 
| ==== | ======= | =========== | =========== | =================== | ======================= | =============================== | ==================== | ==================== | =========================== | ========== | ==================== | ============================ | ====================== | ========================== | ================= | =================== | =========================== | ===================== | ========================= | ================ | 
| 2013 | 1       | 01          | Albany      | 1                   | 33                      | 61                              | 0                    | 39                   | 17                          | 24         | 65                   | 0                            | 75                     | 25                         | 0                 | 215                 | 9                           | 30                    | 60                        | 0                | 
| 2013 | 1       | 02          | Allegany    | 5                   | 42                      | 7                               | 5                    | 88                   | 23                          | 26         | 13                   | 8                            | 23                     | 69                         | 0                 | 61                  | 3                           | 3                     | 93                        | 0                | 
| 2013 | 1       | 03          | Broome      | 22                  | 525                     | 12                              | 5                    | 83                   | 0                           | 0          | 18                   | 6                            | 61                     | 33                         | 0                 | 307                 | 3                           | 7                     | 90                        | 0                | 
| 2013 | 1       | 04          | Cattaraugus | 16                  | 196                     | 62                              | 0                    | 38                   | 16                          | 100        | 22                   | 43                           | 36                     | 21                         | 36                | 65                  | 15                          | 6                     | 79                        | 5                | 
| 2013 | 1       | 05          | Cayuga      | 51                  | 240                     | 19                              | 5                    | 76                   | 82                          | 27         | 33                   | 6                            | 48                     | 45                         | 0                 | 62                  | 3                           | 10                    | 87                        | 0                | 
| 2013 | 1       | 06          | Chautauqua  | 20                  | 397                     | 60                              | 2                    | 38                   | 20                          | 20         | 36                   | 3                            | 58                     | 39                         | 0                 | 690                 | 3                           | 11                    | 86                        | 23               | 
| 2013 | 1       | 07          | Chemung     | 26                  | 145                     | 54                              | 0                    | 46                   | 11                          | 82         | 39                   | 10                           | 64                     | 26                         | 0                 | 193                 | 10                          | 7                     | 83                        | 0                | 
| 2013 | 1       | 08          | Chenango    | 13                  | 122                     | 29                              | 0                    | 71                   | 4                           | 0          | 31                   | 0                            | 29                     | 71                         | 0                 | 49                  | 0                           | 4                     | 96                        | 0                | 
| 2013 | 1       | 09          | Clinton     | 4                   | 27                      | 44                              | 26                   | 30                   | 1                           | 0          | 19                   | 5                            | 53                     | 42                         | 0                 | 82                  | 0                           | 24                    | 76                        | 0                | 
| 2013 | 1       | 10          | Columbia    | 1                   | 10                      | 30                              | 10                   | 60                   | 0                           | 0          | 1                    | 0                            | 0                      | 100                        | 0                 | 42                  | 5                           | 21                    | 74                        | 0                | 
```