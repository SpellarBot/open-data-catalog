# School District Breakdowns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-district-breakdowns-aa622) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g3vh-kbnw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g3vh-kbnw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g3vh-kbnw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g3vh-kbnw |
| Name | School District Breakdowns |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | boundary, district, community, demography, demographic, statistic, youth, development, neighborhood, school, education, lifelong learning |
| Created | 2011-07-27T14:09:55Z |
| Publication Date | 2011-10-08T23:26:59Z |

## Description

Demographic statistics broken down by school districts

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
series e:g3vh-kbnw d:2011-07-27T07:09:58.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="CSD 01 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=11 m:percent_nreceives_public_assistance=1 m:percent_asian_non_hispanic=0.36 m:count_asian_non_hispanic=4 m:count_us_citizen=11 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=11 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0.09 m:count_hispanic_latino=1 m:count_black_non_hispanic=0 m:count_participants=11 m:count_male=7 m:percent_public_assistance_unknown=0 m:count_gender_total=11 m:percent_male=0.64 m:percent_white_non_hispanic=0.55 m:percent_receives_public_assistance=0 m:count_american_indian=0 m:count_receives_public_assistance=0 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=0 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=6 m:percent_american_indian=0 m:count_nreceives_public_assistance=11 m:count_citizen_status_unknown=0 m:percent_female=0.36 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0 m:percent_us_citizen=1 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0 m:count_female=4 m:count_public_assistance_total=11 m:percent_ethnicity_unknown=0

series e:g3vh-kbnw d:2011-07-27T07:09:58.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="CSD 02 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=124 m:percent_nreceives_public_assistance=0.69 m:percent_asian_non_hispanic=0.44 m:count_asian_non_hispanic=54 m:count_us_citizen=117 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=124 m:percent_gender_unknown=0 m:count_other_ethnicity=4 m:percent_hispanic_latino=0.23 m:count_hispanic_latino=28 m:count_black_non_hispanic=37 m:count_participants=124 m:count_male=54 m:percent_public_assistance_unknown=0 m:count_gender_total=124 m:percent_male=0.44 m:percent_white_non_hispanic=0.01 m:percent_receives_public_assistance=0.31 m:count_american_indian=0 m:count_receives_public_assistance=38 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=7 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=1 m:percent_american_indian=0 m:count_nreceives_public_assistance=86 m:count_citizen_status_unknown=0 m:percent_female=0.56 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.3 m:percent_us_citizen=0.94 m:percent_other_ethnicity=0.03 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.06 m:count_female=70 m:count_public_assistance_total=124 m:percent_ethnicity_unknown=0

series e:g3vh-kbnw d:2011-07-27T07:09:58.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="CSD 03 Manhattan" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=38 m:percent_nreceives_public_assistance=0.63 m:percent_asian_non_hispanic=0.03 m:count_asian_non_hispanic=1 m:count_us_citizen=35 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=38 m:percent_gender_unknown=0 m:count_other_ethnicity=1 m:percent_hispanic_latino=0.47 m:count_hispanic_latino=18 m:count_black_non_hispanic=14 m:count_participants=38 m:count_male=12 m:percent_public_assistance_unknown=0 m:count_gender_total=38 m:percent_male=0.32 m:percent_white_non_hispanic=0.08 m:percent_receives_public_assistance=0.37 m:count_american_indian=0 m:count_receives_public_assistance=14 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=3 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=3 m:percent_american_indian=0 m:count_nreceives_public_assistance=24 m:count_citizen_status_unknown=0 m:percent_female=0.68 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.37 m:percent_us_citizen=0.92 m:percent_other_ethnicity=0.03 m:count_ethnicity_unknown=1 m:percent_permanent_resident_alien=0.08 m:count_female=26 m:count_public_assistance_total=38 m:percent_ethnicity_unknown=0.03
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

metric m:count_hispanic_latino p:integer l:"COUNT HISPANIC LATINO" t:dataTypeName=number

metric m:percent_hispanic_latino p:float l:"PERCENT HISPANIC LATINO" t:dataTypeName=number

metric m:count_american_indian p:integer l:"COUNT AMERICAN INDIAN" t:dataTypeName=number

metric m:percent_american_indian p:float l:"PERCENT AMERICAN INDIAN" t:dataTypeName=number

metric m:count_asian_non_hispanic p:integer l:"COUNT ASIAN NON HISPANIC" t:dataTypeName=number

metric m:percent_asian_non_hispanic p:double l:"PERCENT ASIAN NON HISPANIC" t:dataTypeName=number

metric m:count_white_non_hispanic p:integer l:"COUNT WHITE NON HISPANIC" t:dataTypeName=number

metric m:percent_white_non_hispanic p:float l:"PERCENT WHITE NON HISPANIC" t:dataTypeName=number

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

metric m:percent_receives_public_assistance p:float l:"PERCENT RECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_nreceives_public_assistance p:integer l:"COUNT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:percent_nreceives_public_assistance p:double l:"PERCENT NRECEIVES PUBLIC ASSISTANCE" t:dataTypeName=number

metric m:count_public_assistance_unknown p:integer l:"COUNT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:percent_public_assistance_unknown p:integer l:"PERCENT PUBLIC ASSISTANCE UNKNOWN" t:dataTypeName=number

metric m:count_public_assistance_total p:integer l:"COUNT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

metric m:percent_public_assistance_total p:integer l:"PERCENT PUBLIC ASSISTANCE TOTAL" t:dataTypeName=number

entity e:g3vh-kbnw l:"School District Breakdowns" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/g3vh-kbnw

property e:g3vh-kbnw t:meta.view v:id=g3vh-kbnw v:category=Education v:averageRating=0 v:name="School District Breakdowns" v:attribution="Department of Youth and Community Development (DYCD)"

property e:g3vh-kbnw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g3vh-kbnw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jurisdiction_name | count_participants | count_female | percent_female | count_male | percent_male | count_gender_unknown | percent_gender_unknown | count_gender_total | percent_gender_total | count_pacific_islander | count_hispanic_latino | percent_hispanic_latino | count_american_indian | percent_american_indian | count_asian_non_hispanic | percent_asian_non_hispanic | count_white_non_hispanic | percent_white_non_hispanic | count_black_non_hispanic | percent_black_non_hispanic | count_other_ethnicity | percent_other_ethnicity | count_ethnicity_unknown | percent_ethnicity_unknown | count_ethnicity_total | percent_ethnicity_total | count_permanent_resident_alien | percent_permanent_resident_alien | count_us_citizen | percent_us_citizen | count_other_citizen_status | percent_other_citizen_status | count_citizen_status_unknown | percent_citizen_status_unknown | count_citizen_status_total | percent_citizen_status_total | count_receives_public_assistance | percent_receives_public_assistance | count_nreceives_public_assistance | percent_nreceives_public_assistance | count_public_assistance_unknown | percent_public_assistance_unknown | count_public_assistance_total | percent_public_assistance_total | 
| =========== | ================= | ================== | ============ | ============== | ========== | ============ | ==================== | ====================== | ================== | ==================== | ====================== | ===================== | ======================= | ===================== | ======================= | ======================== | ========================== | ======================== | ========================== | ======================== | ========================== | ===================== | ======================= | ======================= | ========================= | ===================== | ======================= | ============================== | ================================ | ================ | ================== | ========================== | ============================ | ============================ | ============================== | ========================== | ============================ | ================================ | ================================== | ================================= | =================================== | =============================== | ================================= | ============================= | =============================== | 
| 1311750598  | CSD 01 Manhattan  | 11                 | 4            | 0.36           | 7          | 0.64         | 0                    | 0                      | 11                 | 100                  | 0                      | 1                     | 0.09                    | 0                     | 0                       | 4                        | 0.36                       | 6                        | 0.55                       | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 11                    | 100                     | 0                              | 0                                | 11               | 1                  | 0                          | 0                            | 0                            | 0                              | 11                         | 100                          | 0                                | 0                                  | 11                                | 1                                   | 0                               | 0                                 | 11                            | 100                             | 
| 1311750598  | CSD 02 Manhattan  | 124                | 70           | 0.56           | 54         | 0.44         | 0                    | 0                      | 124                | 100                  | 0                      | 28                    | 0.23                    | 0                     | 0                       | 54                       | 0.44                       | 1                        | 0.01                       | 37                       | 0.3                        | 4                     | 0.03                    | 0                       | 0                         | 124                   | 100                     | 7                              | 0.06                             | 117              | 0.94               | 0                          | 0                            | 0                            | 0                              | 124                        | 100                          | 38                               | 0.31                               | 86                                | 0.69                                | 0                               | 0                                 | 124                           | 100                             | 
| 1311750598  | CSD 03 Manhattan  | 38                 | 26           | 0.68           | 12         | 0.32         | 0                    | 0                      | 38                 | 100                  | 0                      | 18                    | 0.47                    | 0                     | 0                       | 1                        | 0.03                       | 3                        | 0.08                       | 14                       | 0.37                       | 1                     | 0.03                    | 1                       | 0.03                      | 38                    | 100                     | 3                              | 0.08                             | 35               | 0.92               | 0                          | 0                            | 0                            | 0                              | 38                         | 100                          | 14                               | 0.37                               | 24                                | 0.63                                | 0                               | 0                                 | 38                            | 100                             | 
| 1311750598  | CSD 04 Manhattan  | 20                 | 13           | 0.65           | 7          | 0.35         | 0                    | 0                      | 20                 | 100                  | 0                      | 4                     | 0.2                     | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 15                       | 0.75                       | 1                     | 0.05                    | 0                       | 0                         | 20                    | 100                     | 0                              | 0                                | 20               | 1                  | 0                          | 0                            | 0                            | 0                              | 20                         | 100                          | 8                                | 0.4                                | 12                                | 0.6                                 | 0                               | 0                                 | 20                            | 100                             | 
| 1311750598  | CSD 05 Manhattan  | 7                  | 4            | 0.57           | 3          | 0.43         | 0                    | 0                      | 7                  | 100                  | 0                      | 1                     | 0.14                    | 0                     | 0                       | 1                        | 0.14                       | 0                        | 0                          | 4                        | 0.57                       | 1                     | 0.14                    | 0                       | 0                         | 7                     | 99                      | 1                              | 0.14                             | 6                | 0.86               | 0                          | 0                            | 0                            | 0                              | 7                          | 100                          | 1                                | 0.14                               | 6                                 | 0.86                                | 0                               | 0                                 | 7                             | 100                             | 
| 1311750598  | CSD 06 Manhattan  | 18                 | 8            | 0.44           | 10         | 0.56         | 0                    | 0                      | 18                 | 100                  | 0                      | 12                    | 0.67                    | 0                     | 0                       | 2                        | 0.11                       | 0                        | 0                          | 3                        | 0.17                       | 1                     | 0.06                    | 0                       | 0                         | 18                    | 100                     | 1                              | 0.06                             | 17               | 0.94               | 0                          | 0                            | 0                            | 0                              | 18                         | 100                          | 7                                | 0.39                               | 11                                | 0.61                                | 0                               | 0                                 | 18                            | 100                             | 
| 1311750598  | CSD 07 Bronx      | 74                 | 40           | 0.54           | 34         | 0.46         | 0                    | 0                      | 74                 | 100                  | 0                      | 30                    | 0.41                    | 0                     | 0                       | 1                        | 0.01                       | 0                        | 0                          | 38                       | 0.51                       | 4                     | 0.05                    | 1                       | 0.01                      | 74                    | 99                      | 4                              | 0.05                             | 69               | 0.93               | 1                          | 0.01                         | 0                            | 0                              | 74                         | 99                           | 22                               | 0.3                                | 52                                | 0.7                                 | 0                               | 0                                 | 74                            | 100                             | 
| 1311750598  | CSD 08 Bronx      | 17                 | 16           | 0.94           | 1          | 0.06         | 0                    | 0                      | 17                 | 100                  | 0                      | 11                    | 0.65                    | 0                     | 0                       | 1                        | 0.06                       | 4                        | 0.24                       | 1                        | 0.06                       | 0                     | 0                       | 0                       | 0                         | 17                    | 100                     | 1                              | 0.06                             | 16               | 0.94               | 0                          | 0                            | 0                            | 0                              | 17                         | 100                          | 4                                | 0.24                               | 13                                | 0.76                                | 0                               | 0                                 | 17                            | 100                             | 
| 1311750598  | CSD 09 Bronx      | 34                 | 20           | 0.59           | 14         | 0.41         | 0                    | 0                      | 34                 | 100                  | 1                      | 17                    | 0.5                     | 1                     | 0.03                    | 0                        | 0                          | 0                        | 0                          | 13                       | 0.38                       | 1                     | 0.03                    | 1                       | 0.03                      | 34                    | 100                     | 1                              | 0.03                             | 33               | 0.97               | 0                          | 0                            | 0                            | 0                              | 34                         | 100                          | 12                               | 0.35                               | 22                                | 0.65                                | 0                               | 0                                 | 34                            | 100                             | 
| 1311750598  | CSD 10 Bronx      | 324                | 189          | 0.58           | 135        | 0.42         | 0                    | 0                      | 324                | 100                  | 0                      | 166                   | 0.51                    | 1                     | 0                       | 6                        | 0.02                       | 4                        | 0.01                       | 130                      | 0.4                        | 17                    | 0.05                    | 0                       | 0                         | 324                   | 99                      | 20                             | 0.06                             | 300              | 0.93               | 4                          | 0.01                         | 0                            | 0                              | 324                        | 100                          | 112                              | 0.35                               | 212                               | 0.65                                | 0                               | 0                                 | 324                           | 100                             | 
```