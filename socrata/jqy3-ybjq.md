# Council district breakdown

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/council-district-breakdown-10c2a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jqy3-ybjq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jqy3-ybjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jqy3-ybjq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jqy3-ybjq |
| Name | Council district breakdown |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | City Government |
| Tags | boundary, district, council, community, demography, demographic, statistic, youth, development, lifelong learning |
| Created | 2011-10-10T23:45:47Z |
| Publication Date | 2013-06-26T17:14:13Z |

## Description

Demographic statistics broken down by council districts Update Schedule: As required

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | jurisdiction_name                   | JURISDICTION NAME                   | text      | text        |
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
series e:jqy3-ybjq d:2011-10-10T16:45:56.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="Council District 001 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=56 m:percent_nreceives_public_assistance=0.88 m:percent_asian_non_hispanic=0.84 m:count_asian_non_hispanic=47 m:percent_pacific_islander=0 m:count_us_citizen=52 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=56 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0.05 m:count_hispanic_latino=3 m:count_black_non_hispanic=6 m:count_participants=56 m:count_male=26 m:percent_public_assistance_unknown=0 m:count_gender_total=56 m:percent_male=0.46 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0.13 m:count_american_indian=0 m:count_receives_public_assistance=7 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=4 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=49 m:count_citizen_status_unknown=0 m:percent_female=0.54 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.11 m:percent_us_citizen=0.93 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.07 m:count_female=30 m:count_public_assistance_total=56 m:percent_ethnicity_unknown=0

series e:jqy3-ybjq d:2011-10-10T16:45:56.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="Council District 002 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=9 m:percent_nreceives_public_assistance=1 m:percent_asian_non_hispanic=0.33 m:count_asian_non_hispanic=3 m:percent_pacific_islander=0 m:count_us_citizen=9 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=9 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0 m:count_hispanic_latino=0 m:count_black_non_hispanic=0 m:count_participants=9 m:count_male=6 m:percent_public_assistance_unknown=0 m:count_gender_total=9 m:percent_male=0.67 m:percent_white_non_hispanic=0.67 m:percent_receives_public_assistance=0 m:count_american_indian=0 m:count_receives_public_assistance=0 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=0 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=6 m:percent_american_indian=0 m:count_nreceives_public_assistance=9 m:count_citizen_status_unknown=0 m:percent_female=0.33 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0 m:percent_us_citizen=1 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0 m:count_female=3 m:count_public_assistance_total=9 m:percent_ethnicity_unknown=0

series e:jqy3-ybjq d:2011-10-10T16:45:56.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="Council District 003 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=69 m:percent_nreceives_public_assistance=0.55 m:percent_asian_non_hispanic=0.1 m:count_asian_non_hispanic=7 m:percent_pacific_islander=0 m:count_us_citizen=66 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=69 m:percent_gender_unknown=0 m:count_other_ethnicity=4 m:percent_hispanic_latino=0.38 m:count_hispanic_latino=26 m:count_black_non_hispanic=31 m:count_participants=69 m:count_male=29 m:percent_public_assistance_unknown=0 m:count_gender_total=69 m:percent_male=0.42 m:percent_white_non_hispanic=0.01 m:percent_receives_public_assistance=0.45 m:count_american_indian=0 m:count_receives_public_assistance=31 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=3 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=1 m:percent_american_indian=0 m:count_nreceives_public_assistance=38 m:count_citizen_status_unknown=0 m:percent_female=0.58 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.45 m:percent_us_citizen=0.96 m:percent_other_ethnicity=0.06 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.04 m:count_female=40 m:count_public_assistance_total=69 m:percent_ethnicity_unknown=0
```

## Meta Commands

```ls
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

metric m:percent_hispanic_latino p:float l:"PERCENT HISPANIC LATINO" t:dataTypeName=number

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

entity e:jqy3-ybjq l:"Council district breakdown" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/jqy3-ybjq

property e:jqy3-ybjq t:meta.view v:id=jqy3-ybjq v:category="City Government" v:averageRating=0 v:name="Council district breakdown" v:attribution="Department of Youth and Community Development (DYCD)"

property e:jqy3-ybjq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jqy3-ybjq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jurisdiction_name              | count_participants | count_female | percent_female | count_male | percent_male | count_gender_unknown | percent_gender_unknown | count_gender_total | percent_gender_total | count_pacific_islander | percent_pacific_islander | count_hispanic_latino | percent_hispanic_latino | count_american_indian | percent_american_indian | count_asian_non_hispanic | percent_asian_non_hispanic | count_white_non_hispanic | percent_white_non_hispanic | count_black_non_hispanic | percent_black_non_hispanic | count_other_ethnicity | percent_other_ethnicity | count_ethnicity_unknown | percent_ethnicity_unknown | count_ethnicity_total | percent_ethnicity_total | count_permanent_resident_alien | percent_permanent_resident_alien | count_us_citizen | percent_us_citizen | count_other_citizen_status | percent_other_citizen_status | count_citizen_status_unknown | percent_citizen_status_unknown | count_citizen_status_total | percent_citizen_status_total | count_receives_public_assistance | percent_receives_public_assistance | count_nreceives_public_assistance | percent_nreceives_public_assistance | count_public_assistance_unknown | percent_public_assistance_unknown | count_public_assistance_total | percent_public_assistance_total | 
| =========== | ============================== | ================== | ============ | ============== | ========== | ============ | ==================== | ====================== | ================== | ==================== | ====================== | ======================== | ===================== | ======================= | ===================== | ======================= | ======================== | ========================== | ======================== | ========================== | ======================== | ========================== | ===================== | ======================= | ======================= | ========================= | ===================== | ======================= | ============================== | ================================ | ================ | ================== | ========================== | ============================ | ============================ | ============================== | ========================== | ============================ | ================================ | ================================== | ================================= | =================================== | =============================== | ================================= | ============================= | =============================== | 
| 1318265156  | Council District 001 Manhattan | 56                 | 30           | 0.54           | 26         | 0.46         | 0                    | 0                      | 56                 | 100                  | 0                      | 0                        | 3                     | 0.05                    | 0                     | 0                       | 47                       | 0.84                       | 0                        | 0                          | 6                        | 0.11                       | 0                     | 0                       | 0                       | 0                         | 56                    | 100                     | 4                              | 0.07                             | 52               | 0.93               | 0                          | 0                            | 0                            | 0                              | 56                         | 100                          | 7                                | 0.13                               | 49                                | 0.88                                | 0                               | 0                                 | 56                            | 100                             | 
| 1318265156  | Council District 002 Manhattan | 9                  | 3            | 0.33           | 6          | 0.67         | 0                    | 0                      | 9                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 3                        | 0.33                       | 6                        | 0.67                       | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 9                     | 100                     | 0                              | 0                                | 9                | 1                  | 0                          | 0                            | 0                            | 0                              | 9                          | 100                          | 0                                | 0                                  | 9                                 | 1                                   | 0                               | 0                                 | 9                             | 100                             | 
| 1318265156  | Council District 003 Manhattan | 69                 | 40           | 0.58           | 29         | 0.42         | 0                    | 0                      | 69                 | 100                  | 0                      | 0                        | 26                    | 0.38                    | 0                     | 0                       | 7                        | 0.1                        | 1                        | 0.01                       | 31                       | 0.45                       | 4                     | 0.06                    | 0                       | 0                         | 69                    | 100                     | 3                              | 0.04                             | 66               | 0.96               | 0                          | 0                            | 0                            | 0                              | 69                         | 100                          | 31                               | 0.45                               | 38                                | 0.55                                | 0                               | 0                                 | 69                            | 100                             | 
| 1318265156  | Council District 004 Manhattan | 1                  | 1            | 1              | 0          | 0            | 0                    | 0                      | 1                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 1                        | 1                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 1                     | 100                     | 0                              | 0                                | 1                | 1                  | 0                          | 0                            | 0                            | 0                              | 1                          | 100                          | 0                                | 0                                  | 1                                 | 1                                   | 0                               | 0                                 | 1                             | 100                             | 
| 1318265156  | Council District 005 Manhattan | 0                  | 0            | 0              | 0          | 0            | 0                    | 0                      | 0                  | 0                    | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 0                     | 0                       | 0                              | 0                                | 0                | 0                  | 0                          | 0                            | 0                            | 0                              | 0                          | 0                            | 0                                | 0                                  | 0                                 | 0                                   | 0                               | 0                                 | 0                             | 0                               | 
| 1318265156  | Council District 006 Manhattan | 11                 | 9            | 0.82           | 2          | 0.18         | 0                    | 0                      | 11                 | 100                  | 0                      | 0                        | 3                     | 0.27                    | 0                     | 0                       | 1                        | 0.09                       | 3                        | 0.27                       | 3                        | 0.27                       | 0                     | 0                       | 1                       | 0.09                      | 11                    | 99                      | 0                              | 0                                | 11               | 1                  | 0                          | 0                            | 0                            | 0                              | 11                         | 100                          | 6                                | 0.55                               | 5                                 | 0.45                                | 0                               | 0                                 | 11                            | 100                             | 
| 1318265156  | Council District 007 Manhattan | 10                 | 6            | 0.6            | 4          | 0.4          | 0                    | 0                      | 10                 | 100                  | 0                      | 0                        | 3                     | 0.3                     | 0                     | 0                       | 2                        | 0.2                        | 0                        | 0                          | 4                        | 0.4                        | 1                     | 0.1                     | 0                       | 0                         | 10                    | 100                     | 1                              | 0.1                              | 9                | 0.9                | 0                          | 0                            | 0                            | 0                              | 10                         | 100                          | 1                                | 0.1                                | 9                                 | 0.9                                 | 0                               | 0                                 | 10                            | 100                             | 
| 1318265156  | Council District 008 Manhattan | 32                 | 19           | 0.59           | 13         | 0.41         | 0                    | 0                      | 32                 | 100                  | 0                      | 0                        | 16                    | 0.5                     | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 15                       | 0.47                       | 1                     | 0.03                    | 0                       | 0                         | 32                    | 100                     | 3                              | 0.09                             | 29               | 0.91               | 0                          | 0                            | 0                            | 0                              | 32                         | 100                          | 12                               | 0.38                               | 20                                | 0.63                                | 0                               | 0                                 | 32                            | 100                             | 
| 1318265156  | Council District 009 Manhattan | 15                 | 11           | 0.73           | 4          | 0.27         | 0                    | 0                      | 15                 | 100                  | 0                      | 0                        | 3                     | 0.2                     | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 11                       | 0.73                       | 1                     | 0.07                    | 0                       | 0                         | 15                    | 100                     | 0                              | 0                                | 15               | 1                  | 0                          | 0                            | 0                            | 0                              | 15                         | 100                          | 4                                | 0.27                               | 11                                | 0.73                                | 0                               | 0                                 | 15                            | 100                             | 
| 1318265156  | Council District 010 Manhattan | 15                 | 6            | 0.4            | 9          | 0.6          | 0                    | 0                      | 15                 | 100                  | 0                      | 0                        | 10                    | 0.67                    | 0                     | 0                       | 1                        | 0.07                       | 0                        | 0                          | 3                        | 0.2                        | 1                     | 0.07                    | 0                       | 0                         | 15                    | 100                     | 1                              | 0.07                             | 14               | 0.93               | 0                          | 0                            | 0                            | 0                              | 15                         | 100                          | 7                                | 0.47                               | 8                                 | 0.53                                | 0                               | 0                                 | 15                            | 100                             | 
```