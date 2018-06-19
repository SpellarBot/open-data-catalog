# Community Based Corrections Population - Year End

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-based-corrections-population) |
| Metadata | [Link](https://data.iowa.gov/api/views/rcgj-ykna) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rcgj-ykna/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rcgj-ykna/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rcgj-ykna |
| Name | Community Based Corrections Population - Year End |
| Attribution | Iowa Department of Corrections, Iowa Justice Data Warehouse |
| Category | Public Safety |
| Tags | cbc population, offender demographics, offender supervision |
| Created | 2014-11-24T16:13:48Z |
| Publication Date | 2017-01-20T21:22:52Z |

## Description

This dataset contains de-identified individual offender data for those serving in Iowa Community Based Correction Facilities. Dataset includes information regarding age, gender, race, offense committed, and supervision status.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                               | Data Type | Render Type |
| ======== | =========== | ================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | supervising_region                 | Supervising Region                 | text      | text        |
| Yes      | series tag  | supervising_region_name            | Supervising Region Name            | text      | text        |
| Yes      | series tag  | supervision_status                 | Supervision Status                 | text      | text        |
| Yes      | series tag  | offense_class_most_serious_crime   | Offense Class Most Serious Crime   | text      | text        |
| Yes      | series tag  | offense_type_most_serious_crime    | Offense Type Most Serious Crime    | text      | text        |
| Yes      | series tag  | offense_subtype_most_serious_crime | Offense Subtype Most Serious Crime | text      | text        |
| Yes      | series tag  | age_group                          | Age Group                          | text      | text        |
| Yes      | series tag  | sex                                | Sex                                | text      | text        |
| Yes      | series tag  | race                               | Race                               | text      | text        |
| Yes      | series tag  | ethnicorigin                       | Ethnic Origin                      | text      | text        |
| Yes      | series tag  | jurisdiction                       | Jurisdiction                       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rcgj-ykna d:2017-01-20T21:17:25.000Z t:offense_class_most_serious_crime="D Felony" t:sex=Female t:supervising_region=3JD t:ethnicorigin=Non-Hispanic t:offense_type_most_serious_crime=Drug t:supervising_region_name="3JD - Third Judicial District" t:age_group=51+ t:supervision_status=Parole t:jurisdiction=Woodbury t:offense_subtype_most_serious_crime="Drug Possession" t:race=White m:row_number.rcgj-ykna=1

series e:rcgj-ykna d:2017-01-20T21:17:25.000Z t:offense_class_most_serious_crime="D Felony" t:sex=Female t:supervising_region=5JD t:ethnicorigin=Non-Hispanic t:offense_type_most_serious_crime=Drug t:supervising_region_name="5JD - Fifth Judicial District" t:age_group=51+ t:supervision_status=Parole t:jurisdiction=Polk t:offense_subtype_most_serious_crime="Drug Possession" t:race="American Indian or Alaska Native" m:row_number.rcgj-ykna=2

series e:rcgj-ykna d:2017-01-20T21:17:25.000Z t:offense_class_most_serious_crime="B Felony" t:sex=Female t:supervising_region=5JD t:ethnicorigin=Non-Hispanic t:offense_type_most_serious_crime=Drug t:supervising_region_name="5JD - Fifth Judicial District" t:age_group=51+ t:supervision_status=Parole t:jurisdiction=Polk t:offense_subtype_most_serious_crime=Trafficking t:race=White m:row_number.rcgj-ykna=3
```

## Meta Commands

```ls
metric m:row_number.rcgj-ykna p:long l:"Row Number"

entity e:rcgj-ykna l:"Community Based Corrections Population - Year End" t:attribution="Iowa Department of Corrections, Iowa Justice Data Warehouse" t:url=https://data.iowa.gov/api/views/rcgj-ykna

property e:rcgj-ykna t:meta.view v:id=rcgj-ykna v:category="Public Safety" v:averageRating=0 v:name="Community Based Corrections Population - Year End" v:attribution="Iowa Department of Corrections, Iowa Justice Data Warehouse"

property e:rcgj-ykna t:meta.view.license v:name="Public Domain"

property e:rcgj-ykna t:meta.view.owner v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:displayName="Iowa Department of Corrections"

property e:rcgj-ykna t:meta.view.tableauthor v:id=jikf-f8f6 v:profileImageUrlMedium=/api/users/jikf-f8f6/profile_images/THUMB v:profileImageUrlLarge=/api/users/jikf-f8f6/profile_images/LARGE v:screenName="Iowa Department of Corrections" v:profileImageUrlSmall=/api/users/jikf-f8f6/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Corrections"
```

## Top Records

```ls
| :updated_at | supervising_region | supervising_region_name        | supervision_status | offense_class_most_serious_crime         | offense_type_most_serious_crime | offense_subtype_most_serious_crime | age_group | sex    | race                             | ethnicorigin | jurisdiction | 
| =========== | ================== | ============================== | ================== | ======================================== | =============================== | ================================== | ========= | ====== | ================================ | ============ | ============ | 
| 1484947045  | 3JD                | 3JD - Third Judicial District  | Parole             | D Felony                                 | Drug                            | Drug Possession                    | 51+       | Female | White                            | Non-Hispanic | Woodbury     | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | D Felony                                 | Drug                            | Drug Possession                    | 51+       | Female | American Indian or Alaska Native | Non-Hispanic | Polk         | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | B Felony                                 | Drug                            | Trafficking                        | 51+       | Female | White                            | Non-Hispanic | Polk         | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | B Felony                                 | Drug                            | Trafficking                        | 51+       | Female | Black                            | Non-Hispanic | Polk         | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | C Felony                                 | Drug                            | Trafficking                        | 31-50     | Female | White                            | Non-Hispanic | Polk         | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | Felony - Enhancement to Original Penalty | Other                           | Other Criminal                     | 51+       | Female | White                            | Non-Hispanic | Polk         | 
| 1484947045  | 2JD                | 2JD - Second Judicial District | Parole             | C Felony                                 | Drug                            | Trafficking                        | 51+       | Female | Black                            | Non-Hispanic | Webster      | 
| 1484947045  | 5JD                | 5JD - Fifth Judicial District  | Parole             | Felony - Enhancement to Original Penalty | Other                           | Other Criminal                     | 51+       | Female | White                            | Non-Hispanic | Polk         | 
| 1484947045  | 3JD                | 3JD - Third Judicial District  | Parole             | C Felony                                 | Drug                            | Trafficking                        | 31-50     | Female | White                            | Non-Hispanic | Woodbury     | 
| 1484947045  | 1JD                | 1JD - First Judicial District  | Parole             | B Felony                                 | Drug                            | Trafficking                        | 51+       | Female | White                            | Non-Hispanic | Black Hawk   | 
```