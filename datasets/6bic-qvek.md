# Zip code breakdowns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zip-code-breakdowns-0cfc4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6bic-qvek) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6bic-qvek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6bic-qvek/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6bic-qvek |
| Name | Zip code breakdowns |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | City Government |
| Tags | boundary, district, community, demography, demographic, statistic, youth, development, zip, code, zip code, area, lifelong learning |
| Created | 2011-10-10T23:47:45Z |
| Publication Date | 2013-06-26T17:13:10Z |

## Description

Demographic statistics broken down by zip code Update Schedule: As required

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | numeric metric | jurisdiction_name                   | JURISDICTION NAME                   | number    | number      |
| Yes      | numeric metric | count_participants                  | COUNT PARTICIPANTS                  | number    | number      |
| Yes      | numeric metric | count_female                        | COUNT FEMALE                        | number    | number      |
| Yes      | numeric metric | percent_female                      | PERCENT FEMALE                      | number    | number      |
| Yes      | numeric metric | count_male                          | COUNT MALE                          | number    | number      |
| Yes      | numeric metric | percent_male                        | PERCENT MALE                        | number    | number      |
| Yes      | numeric metric | count_gender_unknown                | COUNT GENDER UNKNOWN                | number    | number      |
| Yes      | numeric metric | percent_gender_unknown              | PERCENT GENDER UNKNOWN              | number    | number      |
| Yes      | numeric metric | count_gender_total                  | COUNT GENDER TOTAL                  | number    | number      |
| Yes      | numeric metric | percent_gender_total                | PERCENT GENDER TOTAL                | number    | number      |
| Yes      | numeric metric | count_pacific_islander              | COUNT PACIFIC ISLANDER              | number    | number      |
| Yes      | numeric metric | percent_pacific_islander            | PERCENT PACIFIC ISLANDER            | number    | number      |
| Yes      | numeric metric | count_hispanic_latino               | COUNT HISPANIC LATINO               | number    | number      |
| Yes      | numeric metric | percent_hispanic_latino             | PERCENT HISPANIC LATINO             | number    | number      |
| Yes      | numeric metric | count_american_indian               | COUNT AMERICAN INDIAN               | number    | number      |
| Yes      | numeric metric | percent_american_indian             | PERCENT AMERICAN INDIAN             | number    | number      |
| Yes      | numeric metric | count_asian_non_hispanic            | COUNT ASIAN NON HISPANIC            | number    | number      |
| Yes      | numeric metric | percent_asian_non_hispanic          | PERCENT ASIAN NON HISPANIC          | number    | number      |
| Yes      | numeric metric | count_white_non_hispanic            | COUNT WHITE NON HISPANIC            | number    | number      |
| Yes      | numeric metric | percent_white_non_hispanic          | PERCENT WHITE NON HISPANIC          | number    | number      |
| Yes      | numeric metric | count_black_non_hispanic            | COUNT BLACK NON HISPANIC            | number    | number      |
| Yes      | numeric metric | percent_black_non_hispanic          | PERCENT BLACK NON HISPANIC          | number    | number      |
| Yes      | numeric metric | count_other_ethnicity               | COUNT OTHER ETHNICITY               | number    | number      |
| Yes      | numeric metric | percent_other_ethnicity             | PERCENT OTHER ETHNICITY             | number    | number      |
| Yes      | numeric metric | count_ethnicity_unknown             | COUNT ETHNICITY UNKNOWN             | number    | number      |
| Yes      | numeric metric | percent_ethnicity_unknown           | PERCENT ETHNICITY UNKNOWN           | number    | number      |
| Yes      | numeric metric | count_ethnicity_total               | COUNT ETHNICITY TOTAL               | number    | number      |
| Yes      | numeric metric | percent_ethnicity_total             | PERCENT ETHNICITY TOTAL             | number    | number      |
| Yes      | numeric metric | count_permanent_resident_alien      | COUNT PERMANENT RESIDENT ALIEN      | number    | number      |
| Yes      | numeric metric | percent_permanent_resident_alien    | PERCENT PERMANENT RESIDENT ALIEN    | number    | number      |
| Yes      | numeric metric | count_us_citizen                    | COUNT US CITIZEN                    | number    | number      |
| Yes      | numeric metric | percent_us_citizen                  | PERCENT US CITIZEN                  | number    | number      |
| Yes      | series tag     | count_other_citizen_status          | COUNT OTHER CITIZEN STATUS          | text      | number      |
| Yes      | series tag     | percent_other_citizen_status        | PERCENT OTHER CITIZEN STATUS        | text      | number      |
| Yes      | numeric metric | count_citizen_status_unknown        | COUNT CITIZEN STATUS UNKNOWN        | number    | number      |
| Yes      | numeric metric | percent_citizen_status_unknown      | PERCENT CITIZEN STATUS UNKNOWN      | number    | number      |
| Yes      | numeric metric | count_citizen_status_total          | COUNT CITIZEN STATUS TOTAL          | number    | number      |
| Yes      | numeric metric | percent_citizen_status_total        | PERCENT CITIZEN STATUS TOTAL        | number    | number      |
| Yes      | numeric metric | count_receives_public_assistance    | COUNT RECEIVES PUBLIC ASSISTANCE    | number    | number      |
| Yes      | numeric metric | percent_receives_public_assistance  | PERCENT RECEIVES PUBLIC ASSISTANCE  | number    | number      |
| Yes      | numeric metric | count_nreceives_public_assistance   | COUNT NRECEIVES PUBLIC ASSISTANCE   | number    | number      |
| Yes      | numeric metric | percent_nreceives_public_assistance | PERCENT NRECEIVES PUBLIC ASSISTANCE | number    | number      |
| Yes      | numeric metric | count_public_assistance_unknown     | COUNT PUBLIC ASSISTANCE UNKNOWN     | number    | number      |
| Yes      | numeric metric | percent_public_assistance_unknown   | PERCENT PUBLIC ASSISTANCE UNKNOWN   | number    | number      |
| Yes      | numeric metric | count_public_assistance_total       | COUNT PUBLIC ASSISTANCE TOTAL       | number    | number      |
| Yes      | numeric metric | percent_public_assistance_total     | PERCENT PUBLIC ASSISTANCE TOTAL     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6bic-qvek d:2011-10-10T16:48:13.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=44 m:percent_nreceives_public_assistance=0.55 m:percent_asian_non_hispanic=0.07 m:count_asian_non_hispanic=3 m:percent_pacific_islander=0 m:count_us_citizen=42 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=44 m:percent_gender_unknown=0 m:count_other_ethnicity=3 m:jurisdiction_name=10001 m:percent_hispanic_latino=0.36 m:count_hispanic_latino=16 m:count_black_non_hispanic=21 m:count_participants=44 m:count_male=22 m:percent_public_assistance_unknown=0 m:count_gender_total=44 m:percent_male=0.5 m:percent_white_non_hispanic=0.02 m:percent_receives_public_assistance=0.45 m:count_american_indian=0 m:count_receives_public_assistance=20 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=2 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=1 m:percent_american_indian=0 m:count_nreceives_public_assistance=24 m:count_citizen_status_unknown=0 m:percent_female=0.5 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.48 m:percent_us_citizen=0.95 m:percent_other_ethnicity=0.07 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.05 m:count_female=22 m:count_public_assistance_total=44 m:percent_ethnicity_unknown=0

series e:6bic-qvek d:2011-10-10T16:48:13.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=35 m:percent_nreceives_public_assistance=0.94 m:percent_asian_non_hispanic=0.8 m:count_asian_non_hispanic=28 m:percent_pacific_islander=0 m:count_us_citizen=33 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=35 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:jurisdiction_name=10002 m:percent_hispanic_latino=0.03 m:count_hispanic_latino=1 m:count_black_non_hispanic=0 m:count_participants=35 m:count_male=16 m:percent_public_assistance_unknown=0 m:count_gender_total=35 m:percent_male=0.46 m:percent_white_non_hispanic=0.17 m:percent_receives_public_assistance=0.06 m:count_american_indian=0 m:count_receives_public_assistance=2 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=2 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=6 m:percent_american_indian=0 m:count_nreceives_public_assistance=33 m:count_citizen_status_unknown=0 m:percent_female=0.54 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0 m:percent_us_citizen=0.94 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.06 m:count_female=19 m:count_public_assistance_total=35 m:percent_ethnicity_unknown=0

series e:6bic-qvek d:2011-10-10T16:48:13.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=1 m:percent_nreceives_public_assistance=1 m:percent_asian_non_hispanic=1 m:count_asian_non_hispanic=1 m:percent_pacific_islander=0 m:count_us_citizen=1 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=1 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:jurisdiction_name=10003 m:percent_hispanic_latino=0 m:count_hispanic_latino=0 m:count_black_non_hispanic=0 m:count_participants=1 m:count_male=0 m:percent_public_assistance_unknown=0 m:count_gender_total=1 m:percent_male=0 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0 m:count_american_indian=0 m:count_receives_public_assistance=0 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=0 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=1 m:count_citizen_status_unknown=0 m:percent_female=1 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0 m:percent_us_citizen=1 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0 m:count_female=1 m:count_public_assistance_total=1 m:percent_ethnicity_unknown=0
```

## Meta Commands

```ls
metric m:jurisdiction_name p:integer l:"JURISDICTION NAME" t:dataTypeName=number

metric m:count_participants p:integer l:"COUNT PARTICIPANTS" t:dataTypeName=number

metric m:count_female p:integer l:"COUNT FEMALE" t:dataTypeName=number

metric m:percent_female p:double l:"PERCENT FEMALE" t:dataTypeName=number

metric m:count_male p:integer l:"COUNT MALE" t:dataTypeName=number

metric m:percent_male p:double l:"PERCENT MALE" t:dataTypeName=number

metric m:count_gender_unknown p:integer l:"COUNT GENDER UNKNOWN" t:dataTypeName=number

metric m:percent_gender_unknown p:integer l:"PERCENT GENDER UNKNOWN" t:dataTypeName=number

metric m:count_gender_total p:integer l:"COUNT GENDER TOTAL" t:dataTypeName=number

metric m:percent_gender_total p:integer l:"PERCENT GENDER TOTAL" t:dataTypeName=number

metric m:count_pacific_islander p:integer l:"COUNT PACIFIC ISLANDER" t:dataTypeName=number

metric m:percent_pacific_islander p:float l:"PERCENT PACIFIC ISLANDER" t:dataTypeName=number

metric m:count_hispanic_latino p:integer l:"COUNT HISPANIC LATINO" t:dataTypeName=number

metric m:percent_hispanic_latino p:double l:"PERCENT HISPANIC LATINO" t:dataTypeName=number

metric m:count_american_indian p:integer l:"COUNT AMERICAN INDIAN" t:dataTypeName=number

metric m:percent_american_indian p:float l:"PERCENT AMERICAN INDIAN" t:dataTypeName=number

metric m:count_asian_non_hispanic p:integer l:"COUNT ASIAN NON HISPANIC" t:dataTypeName=number

metric m:percent_asian_non_hispanic p:double l:"PERCENT ASIAN NON HISPANIC" t:dataTypeName=number

metric m:count_white_non_hispanic p:integer l:"COUNT WHITE NON HISPANIC" t:dataTypeName=number

metric m:percent_white_non_hispanic p:double l:"PERCENT WHITE NON HISPANIC" t:dataTypeName=number

metric m:count_black_non_hispanic p:integer l:"COUNT BLACK NON HISPANIC" t:dataTypeName=number

metric m:percent_black_non_hispanic p:double l:"PERCENT BLACK NON HISPANIC" t:dataTypeName=number

metric m:count_other_ethnicity p:integer l:"COUNT OTHER ETHNICITY" t:dataTypeName=number

metric m:percent_other_ethnicity p:float l:"PERCENT OTHER ETHNICITY" t:dataTypeName=number

metric m:count_ethnicity_unknown p:integer l:"COUNT ETHNICITY UNKNOWN" t:dataTypeName=number

metric m:percent_ethnicity_unknown p:float l:"PERCENT ETHNICITY UNKNOWN" t:dataTypeName=number

metric m:count_ethnicity_total p:integer l:"COUNT ETHNICITY TOTAL" t:dataTypeName=number

metric m:percent_ethnicity_total p:integer l:"PERCENT ETHNICITY TOTAL" t:dataTypeName=number

metric m:count_permanent_resident_alien p:integer l:"COUNT PERMANENT RESIDENT ALIEN" t:dataTypeName=number

metric m:percent_permanent_resident_alien p:double l:"PERCENT PERMANENT RESIDENT ALIEN" t:dataTypeName=number

metric m:count_us_citizen p:integer l:"COUNT US CITIZEN" t:dataTypeName=number

metric m:percent_us_citizen p:double l:"PERCENT US CITIZEN" t:dataTypeName=number

metric m:count_citizen_status_unknown p:integer l:"COUNT CITIZEN STATUS UNKNOWN" t:dataTypeName=number

metric m:percent_citizen_status_unknown p:integer l:"PERCENT CITIZEN STATUS UNKNOWN" t:dataTypeName=number

metric m:count_citizen_status_total p:integer l:"COUNT CITIZEN STATUS TOTAL" t:dataTypeName=number

metric m:percent_citizen_status_total p:integer l:"PERCENT CITIZEN STATUS TOTAL" t:dataTypeName=number

metric m:count_receives_public_assistance p:integer l:"COUNT RECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:percent_receives_public_assistance p:double l:"PERCENT RECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_nreceives_public_assistance p:integer l:"COUNT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:percent_nreceives_public_assistance p:double l:"PERCENT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_public_assistance_unknown p:integer l:"COUNT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:percent_public_assistance_unknown p:integer l:"PERCENT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:count_public_assistance_total p:integer l:"COUNT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

metric m:percent_public_assistance_total p:integer l:"PERCENT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

entity e:6bic-qvek l:"Zip code breakdowns" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/6bic-qvek

property e:6bic-qvek t:meta.view v:id=6bic-qvek v:category="City Government" v:averageRating=0 v:name="Zip code breakdowns" v:attribution="Department of Youth and Community Development (DYCD)"

property e:6bic-qvek t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6bic-qvek t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jurisdiction_name | count_participants | count_female | percent_female | count_male | percent_male | count_gender_unknown | percent_gender_unknown | count_gender_total | percent_gender_total | count_pacific_islander | percent_pacific_islander | count_hispanic_latino | percent_hispanic_latino | count_american_indian | percent_american_indian | count_asian_non_hispanic | percent_asian_non_hispanic | count_white_non_hispanic | percent_white_non_hispanic | count_black_non_hispanic | percent_black_non_hispanic | count_other_ethnicity | percent_other_ethnicity | count_ethnicity_unknown | percent_ethnicity_unknown | count_ethnicity_total | percent_ethnicity_total | count_permanent_resident_alien | percent_permanent_resident_alien | count_us_citizen | percent_us_citizen | count_other_citizen_status | percent_other_citizen_status | count_citizen_status_unknown | percent_citizen_status_unknown | count_citizen_status_total | percent_citizen_status_total | count_receives_public_assistance | percent_receives_public_assistance | count_nreceives_public_assistance | percent_nreceives_public_assistance | count_public_assistance_unknown | percent_public_assistance_unknown | count_public_assistance_total | percent_public_assistance_total | 
| =========== | ================= | ================== | ============ | ============== | ========== | ============ | ==================== | ====================== | ================== | ==================== | ====================== | ======================== | ===================== | ======================= | ===================== | ======================= | ======================== | ========================== | ======================== | ========================== | ======================== | ========================== | ===================== | ======================= | ======================= | ========================= | ===================== | ======================= | ============================== | ================================ | ================ | ================== | ========================== | ============================ | ============================ | ============================== | ========================== | ============================ | ================================ | ================================== | ================================= | =================================== | =============================== | ================================= | ============================= | =============================== | 
| 1318265293  | 10001             | 44                 | 22           | 0.5            | 22         | 0.5          | 0                    | 0                      | 44                 | 100                  | 0                      | 0                        | 16                    | 0.36                    | 0                     | 0                       | 3                        | 0.07                       | 1                        | 0.02                       | 21                       | 0.48                       | 3                     | 0.07                    | 0                       | 0                         | 44                    | 100                     | 2                              | 0.05                             | 42               | 0.95               | 0                          | 0                            | 0                            | 0                              | 44                         | 100                          | 20                               | 0.45                               | 24                                | 0.55                                | 0                               | 0                                 | 44                            | 100                             | 
| 1318265293  | 10002             | 35                 | 19           | 0.54           | 16         | 0.46         | 0                    | 0                      | 35                 | 100                  | 0                      | 0                        | 1                     | 0.03                    | 0                     | 0                       | 28                       | 0.8                        | 6                        | 0.17                       | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 35                    | 100                     | 2                              | 0.06                             | 33               | 0.94               | 0                          | 0                            | 0                            | 0                              | 35                         | 100                          | 2                                | 0.06                               | 33                                | 0.94                                | 0                               | 0                                 | 35                            | 100                             | 
| 1318265293  | 10003             | 1                  | 1            | 1              | 0          | 0            | 0                    | 0                      | 1                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 1                        | 1                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 1                     | 100                     | 0                              | 0                                | 1                | 1                  | 0                          | 0                            | 0                            | 0                              | 1                          | 100                          | 0                                | 0                                  | 1                                 | 1                                   | 0                               | 0                                 | 1                             | 100                             | 
| 1318265293  | 10004             | 0                  | 0            | 0              | 0          | 0            | 0                    | 0                      | 0                  | 0                    | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 0                     | 0                       | 0                              | 0                                | 0                | 0                  | 0                          | 0                            | 0                            | 0                              | 0                          | 0                            | 0                                | 0                                  | 0                                 | 0                                   | 0                               | 0                                 | 0                             | 0                               | 
| 1318265293  | 10005             | 2                  | 2            | 1              | 0          | 0            | 0                    | 0                      | 2                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 1                        | 0.5                        | 0                        | 0                          | 1                        | 0.5                        | 0                     | 0                       | 0                       | 0                         | 2                     | 100                     | 1                              | 0.5                              | 1                | 0.5                | 0                          | 0                            | 0                            | 0                              | 2                          | 100                          | 0                                | 0                                  | 2                                 | 1                                   | 0                               | 0                                 | 2                             | 100                             | 
| 1318265293  | 10006             | 6                  | 2            | 0.33           | 4          | 0.67         | 0                    | 0                      | 6                  | 100                  | 0                      | 0                        | 2                     | 0.33                    | 0                     | 0                       | 0                        | 0                          | 1                        | 0.17                       | 3                        | 0.5                        | 0                     | 0                       | 0                       | 0                         | 6                     | 100                     | 0                              | 0                                | 6                | 1                  | 0                          | 0                            | 0                            | 0                              | 6                          | 100                          | 0                                | 0                                  | 6                                 | 1                                   | 0                               | 0                                 | 6                             | 100                             | 
| 1318265293  | 10007             | 1                  | 0            | 0              | 1          | 1            | 0                    | 0                      | 1                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 1                        | 1                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 1                     | 100                     | 0                              | 0                                | 1                | 1                  | 0                          | 0                            | 0                            | 0                              | 1                          | 100                          | 1                                | 1                                  | 0                                 | 0                                   | 0                               | 0                                 | 1                             | 100                             | 
| 1318265293  | 10009             | 2                  | 0            | 0              | 2          | 1            | 0                    | 0                      | 2                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 2                        | 1                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 2                     | 100                     | 0                              | 0                                | 2                | 1                  | 0                          | 0                            | 0                            | 0                              | 2                          | 100                          | 0                                | 0                                  | 2                                 | 1                                   | 0                               | 0                                 | 2                             | 100                             | 
| 1318265293  | 10010             | 0                  | 0            | 0              | 0          | 0            | 0                    | 0                      | 0                  | 0                    | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 0                     | 0                       | 0                              | 0                                | 0                | 0                  | 0                          | 0                            | 0                            | 0                              | 0                          | 0                            | 0                                | 0                                  | 0                                 | 0                                   | 0                               | 0                                 | 0                             | 0                               | 
| 1318265293  | 10011             | 3                  | 2            | 0.67           | 1          | 0.33         | 0                    | 0                      | 3                  | 100                  | 0                      | 0                        | 1                     | 0.33                    | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 1                        | 0.33                       | 1                     | 0.33                    | 0                       | 0                         | 3                     | 99                      | 0                              | 0                                | 3                | 1                  | 0                          | 0                            | 0                            | 0                              | 3                          | 100                          | 0                                | 0                                  | 3                                 | 1                                   | 0                               | 0                                 | 3                             | 100                             | 
```