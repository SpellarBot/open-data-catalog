# Iowa Prison Population - Year End

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-prison-population) |
| Metadata | [Link](https://data.iowa.gov/api/views/murf-9x69) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/murf-9x69/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/murf-9x69/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | murf-9x69 |
| Name | Iowa Prison Population - Year End |
| Attribution | Iowa Department of Corrections, Iowa Justice Data Warehouse |
| Category | Public Safety |
| Tags | prison population, offender demographics |
| Created | 2014-11-24T14:53:30Z |
| Publication Date | 2017-01-20T20:41:36Z |

## Description

This dataset contains de-identified individual offender data for those serving in Iowa Penitentiaries and Correctional Facilities. Dataset includes information regarding age, gender, race, years served, and offense committed. It also identifies whether the individual is serving a life sentence.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | =========== | ======================================= | ======================================= | ========= | =========== |
| No       | time        | :updated_at                             | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | age_group                               | Age Group                               | text      | text        |
| Yes      | series tag  | years_served                            | Years Served                            | text      | text        |
| Yes      | series tag  | offense_class_most_serious_crime        | Offense Class Most Serious Crime        | text      | text        |
| Yes      | series tag  | offense_type_most_serious_crime         | Offense Type Most Serious Crime         | text      | text        |
| Yes      | series tag  | offense_subtype_most_serious_crime      | Offense Subtype Most Serious Crime      | text      | text        |
| Yes      | series tag  | sex                                     | Sex                                     | text      | text        |
| Yes      | series tag  | race                                    | Race                                    | text      | text        |
| Yes      | series tag  | ethnic_origin                           | Ethnic Origin                           | text      | text        |
| Yes      | series tag  | status                                  | Status                                  | text      | text        |
| Yes      | series tag  | jurisdiction                            | Jurisdiction                            | text      | text        |
| Yes      | series tag  | serving_life_without_parole             | Serving Life                            | text      | text        |
| Yes      | series tag  | serving_life_with_possibility_of_parole | Serving Life with Possibility of Parole | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:murf-9x69 d:2017-01-20T20:37:23.000Z t:offense_class_most_serious_crime="B Felony" t:sex=Male t:status=Prison t:offense_type_most_serious_crime=Drug t:years_served="Less than 1 year" t:age_group=41-50 t:ethnic_origin=Non-Hispanic t:jurisdiction=Adair t:offense_subtype_most_serious_crime=Trafficking t:serving_life_without_parole=No t:race=White m:row_number.murf-9x69=1

series e:murf-9x69 d:2017-01-20T20:37:23.000Z t:offense_class_most_serious_crime="B Felony" t:sex=Male t:status=Prison t:offense_type_most_serious_crime=Violent t:years_served="10 to 19.9 Years" t:age_group=26-30 t:ethnic_origin=Non-Hispanic t:jurisdiction=Adair t:offense_subtype_most_serious_crime=Murder/Manslaughter t:serving_life_without_parole=No t:race=White m:row_number.murf-9x69=2

series e:murf-9x69 d:2017-01-20T20:37:23.000Z t:offense_class_most_serious_crime="B Felony" t:sex=Male t:status=Prison t:offense_type_most_serious_crime=Violent t:years_served="10 to 19.9 Years" t:age_group=31-35 t:ethnic_origin=Non-Hispanic t:jurisdiction=Adair t:offense_subtype_most_serious_crime=Sex t:serving_life_without_parole=No t:race=White m:row_number.murf-9x69=3
```

## Meta Commands

```ls
metric m:row_number.murf-9x69 p:long l:"Row Number"

entity e:murf-9x69 l:"Iowa Prison Population - Year End" t:attribution="Iowa Department of Corrections, Iowa Justice Data Warehouse" t:url=https://data.iowa.gov/api/views/murf-9x69

property e:murf-9x69 t:meta.view v:id=murf-9x69 v:category="Public Safety" v:averageRating=0 v:name="Iowa Prison Population - Year End" v:attribution="Iowa Department of Corrections, Iowa Justice Data Warehouse"

property e:murf-9x69 t:meta.view.license v:name="Public Domain"

property e:murf-9x69 t:meta.view.owner v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:displayName="Iowa Department of Corrections"

property e:murf-9x69 t:meta.view.tableauthor v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Corrections"
```

## Top Records

```ls
| :updated_at | age_group | years_served     | offense_class_most_serious_crime | offense_type_most_serious_crime | offense_subtype_most_serious_crime | sex  | race  | ethnic_origin | status | jurisdiction | serving_life_without_parole | serving_life_with_possibility_of_parole | 
| =========== | ========= | ================ | ================================ | =============================== | ================================== | ==== | ===== | ============= | ====== | ============ | =========================== | ======================================= | 
| 1484944643  | 41-50     | Less than 1 year | B Felony                         | Drug                            | Trafficking                        | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 26-30     | 10 to 19.9 Years | B Felony                         | Violent                         | Murder/Manslaughter                | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 31-35     | 10 to 19.9 Years | B Felony                         | Violent                         | Sex                                | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 26-30     | Less than 1 year | C Felony                         | Drug                            | Trafficking                        | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 36-40     | 1 to 1.9 Years   | C Felony                         | Violent                         | Assault                            | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 31-35     | Less than 1 year | D Felony                         | Property                        | Vandalism                          | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 31-35     | Less than 1 year | D Felony                         | Violent                         | Assault                            | Male | White | Non-Hispanic  | Prison | Adair        | No                          |                                         | 
| 1484944643  | 41-50     | 20 or More Years | A Felony                         | Violent                         | Kidnap                             | Male | White | Non-Hispanic  | Prison | Adams        | Yes                         | No                                      | 
| 1484944643  | 36-40     | Less than 1 year | B Felony                         | Violent                         | Murder/Manslaughter                | Male | White | Non-Hispanic  | Prison | Adams        | No                          |                                         | 
| 1484944643  | 41-50     | Less than 1 year | B Felony                         | Violent                         | Murder/Manslaughter                | Male | White | Non-Hispanic  | Prison | Adams        | No                          |                                         | 
```