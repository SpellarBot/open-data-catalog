# Senate District Breakdowns

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/senate-district-breakdowns-658b2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uv67-wxba) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uv67-wxba/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uv67-wxba/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uv67-wxba |
| Name | Senate District Breakdowns |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | City Government |
| Tags | boundary, district, senate, community, demography, demographic, statistic, youth, development, lifelong learning |
| Created | 2011-07-27T14:08:43Z |
| Publication Date | 2013-06-26T17:22:33Z |

## Description

Demographic statistics broken down by senate districts

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
series e:uv67-wxba d:2011-07-27T07:08:46.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="State Senate District 010" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=20 m:percent_nreceives_public_assistance=0.65 m:percent_asian_non_hispanic=0 m:count_asian_non_hispanic=0 m:percent_pacific_islander=0 m:count_us_citizen=18 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=20 m:percent_gender_unknown=0 m:count_other_ethnicity=2 m:percent_hispanic_latino=0.1 m:count_hispanic_latino=2 m:count_black_non_hispanic=5 m:count_participants=20 m:count_male=10 m:percent_public_assistance_unknown=0 m:count_gender_total=20 m:percent_male=0.5 m:percent_white_non_hispanic=0.5 m:percent_receives_public_assistance=0.35 m:count_american_indian=0 m:count_receives_public_assistance=7 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=2 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=10 m:percent_american_indian=0 m:count_nreceives_public_assistance=13 m:count_citizen_status_unknown=0 m:percent_female=0.5 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.25 m:percent_us_citizen=0.9 m:percent_other_ethnicity=0.1 m:count_ethnicity_unknown=1 m:percent_permanent_resident_alien=0.1 m:count_female=10 m:count_public_assistance_total=20 m:percent_ethnicity_unknown=0.05

series e:uv67-wxba d:2011-07-27T07:08:46.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="State Senate District 011" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=4 m:percent_nreceives_public_assistance=1 m:percent_asian_non_hispanic=0.25 m:count_asian_non_hispanic=1 m:percent_pacific_islander=0 m:count_us_citizen=3 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=4 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0.25 m:count_hispanic_latino=1 m:count_black_non_hispanic=2 m:count_participants=4 m:count_male=2 m:percent_public_assistance_unknown=0 m:count_gender_total=4 m:percent_male=0.5 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0 m:count_american_indian=0 m:count_receives_public_assistance=0 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=1 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=4 m:count_citizen_status_unknown=0 m:percent_female=0.5 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0.5 m:percent_us_citizen=0.75 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0.25 m:count_female=2 m:count_public_assistance_total=4 m:percent_ethnicity_unknown=0

series e:uv67-wxba d:2011-07-27T07:08:46.000Z t:percent_other_citizen_status=0 t:count_other_citizen_status=0 t:jurisdiction_name="State Senate District 012" m:count_public_assistance_unknown=0 m:percent_gender_total=100 m:count_ethnicity_total=1 m:percent_nreceives_public_assistance=1 m:percent_asian_non_hispanic=1 m:count_asian_non_hispanic=1 m:percent_pacific_islander=0 m:count_us_citizen=1 m:percent_citizen_status_unknown=0 m:count_citizen_status_total=1 m:percent_gender_unknown=0 m:count_other_ethnicity=0 m:percent_hispanic_latino=0 m:count_hispanic_latino=0 m:count_black_non_hispanic=0 m:count_participants=1 m:count_male=1 m:percent_public_assistance_unknown=0 m:count_gender_total=1 m:percent_male=1 m:percent_white_non_hispanic=0 m:percent_receives_public_assistance=0 m:count_american_indian=0 m:count_receives_public_assistance=0 m:percent_ethnicity_total=100 m:count_permanent_resident_alien=0 m:count_gender_unknown=0 m:count_pacific_islander=0 m:percent_public_assistance_total=100 m:count_white_non_hispanic=0 m:percent_american_indian=0 m:count_nreceives_public_assistance=1 m:count_citizen_status_unknown=0 m:percent_female=0 m:percent_citizen_status_total=100 m:percent_black_non_hispanic=0 m:percent_us_citizen=1 m:percent_other_ethnicity=0 m:count_ethnicity_unknown=0 m:percent_permanent_resident_alien=0 m:count_female=0 m:count_public_assistance_total=1 m:percent_ethnicity_unknown=0
```

## Meta Commands

```ls
metric m:count_participants p:integer l:"COUNT PARTICIPANTS" t:dataTypeName=number

metric m:count_female p:integer l:"COUNT FEMALE" t:dataTypeName=number

metric m:percent_female p:float l:"PERCENT FEMALE" t:dataTypeName=number

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

entity e:uv67-wxba l:"Senate District Breakdowns" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/uv67-wxba

property e:uv67-wxba t:meta.view v:id=uv67-wxba v:category="City Government" v:averageRating=0 v:name="Senate District Breakdowns" v:attribution="Department of Youth and Community Development (DYCD)"

property e:uv67-wxba t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uv67-wxba t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | jurisdiction_name         | count_participants | count_female | percent_female | count_male | percent_male | count_gender_unknown | percent_gender_unknown | count_gender_total | percent_gender_total | count_pacific_islander | percent_pacific_islander | count_hispanic_latino | percent_hispanic_latino | count_american_indian | percent_american_indian | count_asian_non_hispanic | percent_asian_non_hispanic | count_white_non_hispanic | percent_white_non_hispanic | count_black_non_hispanic | percent_black_non_hispanic | count_other_ethnicity | percent_other_ethnicity | count_ethnicity_unknown | percent_ethnicity_unknown | count_ethnicity_total | percent_ethnicity_total | count_permanent_resident_alien | percent_permanent_resident_alien | count_us_citizen | percent_us_citizen | count_other_citizen_status | percent_other_citizen_status | count_citizen_status_unknown | percent_citizen_status_unknown | count_citizen_status_total | percent_citizen_status_total | count_receives_public_assistance | percent_receives_public_assistance | count_nreceives_public_assistance | percent_nreceives_public_assistance | count_public_assistance_unknown | percent_public_assistance_unknown | count_public_assistance_total | percent_public_assistance_total | 
| =========== | ========================= | ================== | ============ | ============== | ========== | ============ | ==================== | ====================== | ================== | ==================== | ====================== | ======================== | ===================== | ======================= | ===================== | ======================= | ======================== | ========================== | ======================== | ========================== | ======================== | ========================== | ===================== | ======================= | ======================= | ========================= | ===================== | ======================= | ============================== | ================================ | ================ | ================== | ========================== | ============================ | ============================ | ============================== | ========================== | ============================ | ================================ | ================================== | ================================= | =================================== | =============================== | ================================= | ============================= | =============================== | 
| 1311750526  | State Senate District 010 | 20                 | 10           | 0.5            | 10         | 0.5          | 0                    | 0                      | 20                 | 100                  | 0                      | 0                        | 2                     | 0.1                     | 0                     | 0                       | 0                        | 0                          | 10                       | 0.5                        | 5                        | 0.25                       | 2                     | 0.1                     | 1                       | 0.05                      | 20                    | 100                     | 2                              | 0.1                              | 18               | 0.9                | 0                          | 0                            | 0                            | 0                              | 20                         | 100                          | 7                                | 0.35                               | 13                                | 0.65                                | 0                               | 0                                 | 20                            | 100                             | 
| 1311750526  | State Senate District 011 | 4                  | 2            | 0.5            | 2          | 0.5          | 0                    | 0                      | 4                  | 100                  | 0                      | 0                        | 1                     | 0.25                    | 0                     | 0                       | 1                        | 0.25                       | 0                        | 0                          | 2                        | 0.5                        | 0                     | 0                       | 0                       | 0                         | 4                     | 100                     | 1                              | 0.25                             | 3                | 0.75               | 0                          | 0                            | 0                            | 0                              | 4                          | 100                          | 0                                | 0                                  | 4                                 | 1                                   | 0                               | 0                                 | 4                             | 100                             | 
| 1311750526  | State Senate District 012 | 1                  | 0            | 0              | 1          | 1            | 0                    | 0                      | 1                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 1                        | 1                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 1                     | 100                     | 0                              | 0                                | 1                | 1                  | 0                          | 0                            | 0                            | 0                              | 1                          | 100                          | 0                                | 0                                  | 1                                 | 1                                   | 0                               | 0                                 | 1                             | 100                             | 
| 1311750526  | State Senate District 013 | 7                  | 5            | 0.71           | 2          | 0.29         | 0                    | 0                      | 7                  | 100                  | 0                      | 0                        | 5                     | 0.71                    | 0                     | 0                       | 1                        | 0.14                       | 1                        | 0.14                       | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 7                     | 99                      | 1                              | 0.14                             | 6                | 0.86               | 0                          | 0                            | 0                            | 0                              | 7                          | 100                          | 1                                | 0.14                               | 6                                 | 0.86                                | 0                               | 0                                 | 7                             | 100                             | 
| 1311750526  | State Senate District 014 | 37                 | 12           | 0.32           | 25         | 0.68         | 0                    | 0                      | 37                 | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 37                       | 1                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 37                    | 100                     | 0                              | 0                                | 37               | 1                  | 0                          | 0                            | 0                            | 0                              | 37                         | 100                          | 3                                | 0.08                               | 34                                | 0.92                                | 0                               | 0                                 | 37                            | 100                             | 
| 1311750526  | State Senate District 015 | 5                  | 3            | 0.6            | 2          | 0.4          | 0                    | 0                      | 5                  | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 3                        | 0.6                        | 2                        | 0.4                        | 0                     | 0                       | 0                       | 0                         | 5                     | 100                     | 0                              | 0                                | 5                | 1                  | 0                          | 0                            | 0                            | 0                              | 5                          | 100                          | 1                                | 0.2                                | 4                                 | 0.8                                 | 0                               | 0                                 | 5                             | 100                             | 
| 1311750526  | State Senate District 016 | 8                  | 3            | 0.38           | 5          | 0.63         | 0                    | 0                      | 8                  | 100                  | 0                      | 0                        | 3                     | 0.38                    | 0                     | 0                       | 0                        | 0                          | 1                        | 0.13                       | 3                        | 0.38                       | 1                     | 0.13                    | 0                       | 0                         | 8                     | 100                     | 2                              | 0.25                             | 6                | 0.75               | 0                          | 0                            | 0                            | 0                              | 8                          | 100                          | 1                                | 0.13                               | 7                                 | 0.88                                | 0                               | 0                                 | 8                             | 100                             | 
| 1311750526  | State Senate District 017 | 18                 | 8            | 0.44           | 10         | 0.56         | 0                    | 0                      | 18                 | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 17                       | 0.94                       | 0                        | 0                          | 1                     | 0.06                    | 0                       | 0                         | 18                    | 100                     | 0                              | 0                                | 18               | 1                  | 0                          | 0                            | 0                            | 0                              | 18                         | 100                          | 12                               | 0.67                               | 6                                 | 0.33                                | 0                               | 0                                 | 18                            | 100                             | 
| 1311750526  | State Senate District 018 | 0                  | 0            | 0              | 0          | 0            | 0                    | 0                      | 0                  | 0                    | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 0                        | 0                          | 0                        | 0                          | 0                     | 0                       | 0                       | 0                         | 0                     | 0                       | 0                              | 0                                | 0                | 0                  | 0                          | 0                            | 0                            | 0                              | 0                          | 0                            | 0                                | 0                                  | 0                                 | 0                                   | 0                               | 0                                 | 0                             | 0                               | 
| 1311750526  | State Senate District 019 | 14                 | 8            | 0.57           | 6          | 0.43         | 0                    | 0                      | 14                 | 100                  | 0                      | 0                        | 0                     | 0                       | 0                     | 0                       | 0                        | 0                          | 1                        | 0.07                       | 12                       | 0.86                       | 1                     | 0.07                    | 0                       | 0                         | 14                    | 100                     | 1                              | 0.07                             | 13               | 0.93               | 0                          | 0                            | 0                            | 0                              | 14                         | 100                          | 4                                | 0.29                               | 10                                | 0.71                                | 0                               | 0                                 | 14                            | 100                             | 
```