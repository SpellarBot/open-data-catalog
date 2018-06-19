# Neighborhood Development Area Breakdowns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-development-area-breakdowns-76274) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/urvc-2kdr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/urvc-2kdr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/urvc-2kdr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | urvc-2kdr |
| Name | Neighborhood Development Area Breakdowns |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Housing & Development |
| Tags | boundary, district, community, demography, demographic, statistic, youth, development, neighborhood, lifelong learning |
| Created | 2011-07-27T14:11:57Z |
| Publication Date | 2013-06-26T17:19:06Z |

## Description

Demographic statistics broken down by neighborhood development areas

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
series e:urvc-2kdr d:2011-07-27T07:12:00.000Z t:percent_other_citizen_status=0.02 t:count_other_citizen_status=1 t:jurisdiction_name="Bronx Neighborhood Development Area 001" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=59 m:percent_nreceives_public_assistance=0.66 m:percent_asian_non_hispanic=0.02 m:count_asian_non_hispanic=1 m:percent_pacific_islander=0 m:count_us_citizen=55 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=59 m:percent_gender_unknown=0 m:count_other_ethnicity=4 m:percent_hispanic_latino=0.36 m:count_hispanic_latino=21 m:count_black_non_hispanic=32 m:count_participants=59 m:count_male=28 m:percent_public_assistance_unknown=0 m:count_gender_total=59 m:percent_male=0.47 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0.34 m:count_american_indian=0 m:count_receives_public_assistance=20 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=3 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=39 m:count_citizen_status_unknown=0 m:percent_female=0.53 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.54 m:percent_us_citizen=0.93 m:percent_other_ethnicity=0.07 m:count_ethnicity_unknown=1 m:percent_permanent_resident_alien=0.05 m:count_female=31 m:count_public_assistance_total=59 m:percent_ethnicity_unknown=0.02

series e:urvc-2kdr d:2011-07-27T07:12:00.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="Bronx Neighborhood Development Area 002" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=7 m:percent_nreceives_public_assistance=0.57 m:percent_asian_non_hispanic=0 m:count_asian_non_hispanic=0 m:percent_pacific_islander=0 m:count_us_citizen=5 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=7 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0.43 m:count_hispanic_latino=3 m:count_black_non_hispanic=4 m:count_participants=7 m:count_male=2 m:percent_public_assistance_unknown=0 m:count_gender_total=7 m:percent_male=0.29 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0.43 m:count_american_indian=0 m:count_receives_public_assistance=3 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=2 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=4 m:count_citizen_status_unknown=0 m:percent_female=0.71 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.57 m:percent_us_citizen=0.71 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.29 m:count_female=5 m:count_public_assistance_total=7 m:percent_ethnicity_unknown=0

series e:urvc-2kdr d:2011-07-27T07:12:00.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="Bronx Neighborhood Development Area 003" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=15 m:percent_nreceives_public_assistance=0.6 m:percent_asian_non_hispanic=0 m:count_asian_non_hispanic=0 m:percent_pacific_islander=0 m:count_us_citizen=13 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=15 m:percent_gender_unknown=0 m:count_other_ethnicity=1 m:percent_hispanic_latino=0.4 m:count_hispanic_latino=6 m:count_black_non_hispanic=8 m:count_participants=15 m:count_male=3 m:percent_public_assistance_unknown=0 m:count_gender_total=15 m:percent_male=0.2 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0.4 m:count_american_indian=0 m:count_receives_public_assistance=6 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=2 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=9 m:count_citizen_status_unknown=0 m:percent_female=0.8 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.53 m:percent_us_citizen=0.87 m:percent_other_ethnicity=0.07 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.13 m:count_female=12 m:count_public_assistance_total=15 m:percent_ethnicity_unknown=0
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

metric m:percent_black_non_hispanic p:float l:"PERCENT BLACK NON HISPANIC" t:dataTypeName=number

metric m:count_other_ethnicity p:integer l:"COUNT OTHER ETHNICITY" t:dataTypeName=number

metric m:percent_other_ethnicity p:float l:"PERCENT OTHER ETHNICITY" t:dataTypeName=number

metric m:count_ethnicity_unknown p:integer l:"COUNT ETHNICITY UNKNOWN" t:dataTypeName=number

metric m:percent_ethnicity_unknown p:float l:"PERCENT ETHNICITY UNKNOWN" t:dataTypeName=number

metric m:count_ethnicity_total p:integer l:"COUNT ETHNICITY TOTAL" t:dataTypeName=number

metric m:percent_ethnicity_total p:integer l:"PERCENT ETHNICITY TOTAL" t:dataTypeName=number

metric m:count_permanent_resident_alien p:integer l:"COUNT PERMANENT RESIDENT ALIEN" t:dataTypeName=number

metric m:percent_permanent_resident_alien p:float l:"PERCENT PERMANENT RESIDENT ALIEN" t:dataTypeName=number

metric m:count_us_citizen p:integer l:"COUNT US CITIZEN" t:dataTypeName=number

metric m:percent_us_citizen p:double l:"PERCENT US CITIZEN" t:dataTypeName=number

metric m:count_citizen_status_unknown p:integer l:"COUNT CITIZEN STATUS UNKNOWN" t:dataTypeName=number

metric m:percent_citizen_status_unknown p:integer l:"PERCENT CITIZEN STATUS UNKNOWN" t:dataTypeName=number

metric m:count_citizen_status_total p:integer l:"COUNT CITIZEN STATUS TOTAL" t:dataTypeName=number

metric m:percent_citizen_status_total p:integer l:"PERCENT CITIZEN STATUS TOTAL" t:dataTypeName=number

metric m:count_receives_public_assistance p:integer l:"COUNT RECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:percent_receives_public_assistance p:float l:"PERCENT RECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_nreceives_public_assistance p:integer l:"COUNT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:percent_nreceives_public_assistance p:double l:"PERCENT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_public_assistance_unknown p:integer l:"COUNT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:percent_public_assistance_unknown p:integer l:"PERCENT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:count_public_assistance_total p:integer l:"COUNT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

metric m:percent_public_assistance_total p:integer l:"PERCENT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

entity e:urvc-2kdr l:"Neighborhood Development Area Breakdowns" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/urvc-2kdr

property e:urvc-2kdr t:meta.view v:id=urvc-2kdr v:category="Housing & Development" v:averageRating=0 v:name="Neighborhood Development Area Breakdowns" v:attribution="Department of Youth and Community Development (DYCD)"

property e:urvc-2kdr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:urvc-2kdr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jurisdiction_name                       | count_participants | count_female | percent_female | count_male | percent_male | count_gender_unknown | percent_gender_unknown | count_gender_total | percent_gender_total | count_pacific_islander | percent_pacific_islander | count_hispanic_latino | percent_hispanic_latino | count_american_indian | percent_american_indian | count_asian_non_hispanic | percent_asian_non_hispanic | count_white_non_hispanic | percent_white_non_hispanic | count_black_non_hispanic | percent_black_non_hispanic | count_other_ethnicity | percent_other_ethnicity | count_ethnicity_unknown | percent_ethnicity_unknown | count_ethnicity_total | percent_ethnicity_total | count_permanent_resident_alien | percent_permanent_resident_alien | count_us_citizen | percent_us_citizen | count_other_citizen_status | percent_other_citizen_status | count_citizen_status_unknown | percent_citizen_status_unknown | count_citizen_status_total | percent_citizen_status_total | count_receives_public_assistance | percent_receives_public_assistance | count_nreceives_public_assistance | percent_nreceives_public_assistance | count_public_assistance_unknown | percent_public_assistance_unknown | count_public_assistance_total | percent_public_assistance_total | 
| =========== | ======================================= | ================== | ============ | ============== | ========== | ============ | ==================== | ====================== | ================== | ==================== | ====================== | ======================== | ===================== | ======================= | ===================== | ======================= | ======================== | ========================== | ======================== | ========================== | ======================== | ========================== | ===================== | ======================= | ======================= | ========================= | ===================== | ======================= | ============================== | ================================ | ================ | ================== | ========================== | ============================ | ============================ | ============================== | ========================== | ============================ | ================================ | ================================== | ================================= | =================================== | =============================== | ================================= | ============================= | =============================== | 
| 1311750720  | Bronx Neighborhood Development Area 001 | 59                 | 31           | 0.53           | 28         | 0.47         | 0                    | 0                      | 59                 | 100                  | 0                      | 0                        | 21                    | 0.36                    | 0                     | 0                       | 1                        | 0.02                       | 0                        | 0                          | 32                       | 0.54                       | 4                     | 0.07                    | 1                       | 0.02                      | 59                    | 100                     | 3                              | 0.05                             | 55               | 0.93               | 1                          | 0.02                         | 0                            | 0                              | 59                         | 100                          | 20                               | 0.34                               | 39                                | 0.66                                | 0                               | 0                                 | 59                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 002 | 7                  | 5            | 0.71           | 2          | 0.29         | 0                    | 0                      | 7                  | 100                  | 0                      | 0                        | 3                     | 0.43                    | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 4                        | 0.57                       | 0                     | 0                       | 0                       | 0                         | 7                     | 100                     | 2                              | 0.29                             | 5                | 0.71               | 0                          | 0                            | 0                            | 0                              | 7                          | 100                          | 3                                | 0.43                               | 4                                 | 0.57                                | 0                               | 0                                 | 7                             | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 003 | 15                 | 12           | 0.8            | 3          | 0.2          | 0                    | 0                      | 15                 | 100                  | 0                      | 0                        | 6                     | 0.4                     | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 8                        | 0.53                       | 1                     | 0.07                    | 0                       | 0                         | 15                    | 100                     | 2                              | 0.13                             | 13               | 0.87               | 0                          | 0                            | 0                            | 0                              | 15                         | 100                          | 6                                | 0.4                                | 9                                 | 0.6                                 | 0                               | 0                                 | 15                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 004 | 44                 | 27           | 0.61           | 17         | 0.39         | 0                    | 0                      | 44                 | 100                  | 1                      | 0.02                     | 24                    | 0.55                    | 1                     | 0.02                    | 0                        | 0                          | 0                        | 0                          | 16                       | 0.36                       | 1                     | 0.02                    | 1                       | 0.02                      | 44                    | 99                      | 2                              | 0.05                             | 42               | 0.95               | 0                          | 0                            | 0                            | 0                              | 44                         | 100                          | 13                               | 0.3                                | 31                                | 0.7                                 | 0                               | 0                                 | 44                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 005 | 25                 | 9            | 0.36           | 16         | 0.64         | 0                    | 0                      | 25                 | 100                  | 0                      | 0                        | 11                    | 0.44                    | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 13                       | 0.52                       | 1                     | 0.04                    | 0                       | 0                         | 25                    | 100                     | 3                              | 0.12                             | 22               | 0.88               | 0                          | 0                            | 0                            | 0                              | 25                         | 100                          | 12                               | 0.48                               | 13                                | 0.52                                | 0                               | 0                                 | 25                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 006 | 15                 | 5            | 0.33           | 10         | 0.67         | 0                    | 0                      | 15                 | 100                  | 0                      | 0                        | 6                     | 0.4                     | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 9                        | 0.6                        | 0                     | 0                       | 0                       | 0                         | 15                    | 100                     | 0                              | 0                                | 15               | 1                  | 0                          | 0                            | 0                            | 0                              | 15                         | 100                          | 5                                | 0.33                               | 10                                | 0.67                                | 0                               | 0                                 | 15                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 007 | 207                | 125          | 0.6            | 82         | 0.4          | 0                    | 0                      | 207                | 100                  | 0                      | 0                        | 99                    | 0.48                    | 1                     | 0                       | 6                        | 0.03                       | 1                        | 0                          | 88                       | 0.43                       | 12                    | 0.06                    | 0                       | 0                         | 207                   | 100                     | 15                             | 0.07                             | 190              | 0.92               | 2                          | 0.01                         | 0                            | 0                              | 207                        | 100                          | 67                               | 0.32                               | 140                               | 0.68                                | 0                               | 0                                 | 207                           | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 008 | 61                 | 39           | 0.64           | 22         | 0.36         | 0                    | 0                      | 61                 | 100                  | 0                      | 0                        | 38                    | 0.62                    | 0                     | 0                       | 0                        | 0                          | 2                        | 0.03                       | 19                       | 0.31                       | 2                     | 0.03                    | 0                       | 0                         | 61                    | 99                      | 2                              | 0.03                             | 57               | 0.93               | 2                          | 0.03                         | 0                            | 0                              | 61                         | 99                           | 21                               | 0.34                               | 40                                | 0.66                                | 0                               | 0                                 | 61                            | 100                             | 
| 1311750720  | Bronx Neighborhood Development Area 009 | 0                  | 0            | 0              | 0          | 0            | 0                    | 0                      | 0                  | 0                    | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 0                     | 0                       | 0                              | 0                                | 0                | 0                  | 0                          | 0                            | 0                            | 0                              | 0                          | 0                            | 0                                | 0                                  | 0                                 | 0                                   | 0                               | 0                                 | 0                             | 0                               | 
| 1311750720  | Bronx Neighborhood Development Area 010 | 33                 | 29           | 0.88           | 4          | 0.12         | 0                    | 0                      | 33                 | 100                  | 1                      | 0.03                     | 19                    | 0.58                    | 1                     | 0.03                    | 1                        | 0.03                       | 4                        | 0.12                       | 6                        | 0.18                       | 1                     | 0.03                    | 0                       | 0                         | 33                    | 100                     | 2                              | 0.06                             | 30               | 0.91               | 1                          | 0.03                         | 0                            | 0                              | 33                         | 100                          | 13                               | 0.39                               | 20                                | 0.61                                | 0                               | 0                                 | 33                            | 100                             | 
```