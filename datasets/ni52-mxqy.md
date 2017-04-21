# 2014-2015 Public School District Dropout Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-2015-public-school-district-dropout-rates) |
| Metadata | [Link](https://data.iowa.gov/api/views/ni52-mxqy) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ni52-mxqy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ni52-mxqy/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ni52-mxqy |
| Name | 2014-2015 Public School District Dropout Rates |
| Attribution | Iowa Department of Education |
| Category | Education |
| Tags | school, dropout |
| Created | 2016-08-08T21:37:46Z |
| Publication Date | 2016-08-08T21:50:26Z |

## Description

Public school district drop out rates for SY 2015 by race and gender

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | district                              | District Number                       | text      | number      |
| Yes      | series tag     | district_name                         | District Name                         | text      | text        |
| Yes      | numeric metric | county                                | County                                | number    | number      |
| Yes      | numeric metric | aea                                   | AEA                                   | number    | number      |
| Yes      | numeric metric | overall_dropouts                      | Overall Dropouts                      | number    | number      |
| Yes      | numeric metric | overall_enrollments                   | Overall Enrollments                   | number    | number      |
| Yes      | numeric metric | overall_rate                          | Overall Rate                          | number    | number      |
| Yes      | series tag     | african_american_dropouts             | African American Dropouts             | text      | text        |
| Yes      | series tag     | african_american_enrollments          | African American Enrollments          | text      | text        |
| Yes      | numeric metric | african_american_rate                 | African American Rate                 | number    | number      |
| Yes      | series tag     | hispanic_dropouts                     | Hispanic Dropouts                     | text      | text        |
| Yes      | series tag     | hispanic_enrollments                  | Hispanic Enrollments                  | text      | text        |
| Yes      | numeric metric | hispanic_rate                         | Hispanic Rate                         | number    | number      |
| Yes      | series tag     | american_indian_dropouts              | American Indian Dropouts              | text      | text        |
| Yes      | series tag     | american_indian_enrollments           | American Indian Enrollments           | text      | text        |
| Yes      | numeric metric | american_indian_rate                  | American Indian Rate                  | number    | number      |
| Yes      | series tag     | asian_dropouts                        | Asian Dropouts                        | text      | text        |
| Yes      | series tag     | asian_enrollments                     | Asian Enrollments                     | text      | text        |
| Yes      | numeric metric | asian_rate                            | Asian Rate                            | number    | number      |
| Yes      | series tag     | hawaiian_pacific_islander_dropouts    | Hawaiian/Pacific Islander Dropouts    | text      | text        |
| Yes      | series tag     | hawaiian_pacific_islander_enrollments | Hawaiian/Pacific Islander Enrollments | text      | text        |
| Yes      | numeric metric | hawaiian_pacific_islander_rate        | Hawaiian/Pacific Islander Rate        | number    | number      |
| Yes      | numeric metric | white_dropouts                        | White Dropouts                        | number    | number      |
| Yes      | numeric metric | white_enrollments                     | White Enrollments                     | number    | number      |
| Yes      | numeric metric | white_rate                            | White Rate                            | number    | number      |
| Yes      | series tag     | two_or_more_races_dropouts            | Two or More Races Dropouts            | text      | text        |
| Yes      | series tag     | two_or_more_races_enrollments         | Two or More Races Enrollments         | text      | text        |
| Yes      | numeric metric | two_or_more_races_rate                | Two or More Races Rate                | number    | number      |
| Yes      | numeric metric | female_dropouts                       | Female Dropouts                       | number    | number      |
| Yes      | numeric metric | female_enrollments                    | Female Enrollments                    | number    | number      |
| Yes      | numeric metric | female_rate                           | Female Rate                           | number    | number      |
| Yes      | numeric metric | male_dropouts                         | Male Dropouts                         | number    | number      |
| Yes      | numeric metric | male_enrollments                      | Male Enrollments                      | number    | number      |
| Yes      | numeric metric | male_rate                             | Male Rate                             | number    | number      |
| Yes      | series tag     | grade_7_12_status                     | Grade 7-12 Status                     | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ni52-mxqy d:2014-01-01T00:00:00.000Z t:african_american_dropouts=**** t:american_indian_dropouts=**** t:asian_enrollments=**** t:hispanic_enrollments=27 t:hawaiian_pacific_islander_dropouts=**** t:hispanic_dropouts=0 t:two_or_more_races_dropouts=**** t:american_indian_enrollments=**** t:hawaiian_pacific_islander_enrollments=**** t:grade_7_12_status="High School" t:asian_dropouts=**** t:district_name=AGWSR t:district=9 t:two_or_more_races_enrollments=**** t:african_american_enrollments=**** m:male_dropouts=0 m:overall_rate=0.83 m:white_enrollments=206 m:white_rate=0 m:male_rate=0 m:female_enrollments=116 m:aea=7 m:male_enrollments=124 m:female_rate=1.72 m:county=42 m:hispanic_rate=0 m:white_dropouts=0 m:overall_enrollments=240 m:overall_dropouts=2 m:female_dropouts=2

series e:ni52-mxqy d:2014-01-01T00:00:00.000Z t:african_american_dropouts=**** t:american_indian_dropouts=**** t:asian_enrollments=**** t:hispanic_enrollments=**** t:hawaiian_pacific_islander_dropouts=**** t:hispanic_dropouts=**** t:two_or_more_races_dropouts=**** t:american_indian_enrollments=**** t:hawaiian_pacific_islander_enrollments=**** t:grade_7_12_status="High School" t:asian_dropouts=**** t:district_name=Adair-Casey t:district=18 t:two_or_more_races_enrollments=**** t:african_american_enrollments=**** m:male_dropouts=0 m:overall_rate=0 m:white_enrollments=126 m:white_rate=0 m:male_rate=0 m:female_enrollments=67 m:aea=11 m:male_enrollments=61 m:female_rate=0 m:white_dropouts=0 m:county=39 m:overall_enrollments=128 m:overall_dropouts=0 m:female_dropouts=0

series e:ni52-mxqy d:2014-01-01T00:00:00.000Z t:african_american_dropouts=0 t:american_indian_dropouts=**** t:asian_enrollments=23 t:hispanic_enrollments=29 t:hawaiian_pacific_islander_dropouts=**** t:hispanic_dropouts=0 t:two_or_more_races_dropouts=1 t:american_indian_enrollments=**** t:hawaiian_pacific_islander_enrollments=**** t:grade_7_12_status="High School" t:asian_dropouts=0 t:district_name=Oskaloosa t:district=5013 t:two_or_more_races_enrollments=20 t:african_american_enrollments=10 m:male_dropouts=12 m:overall_rate=2.33 m:white_enrollments=985 m:white_rate=2.44 m:male_rate=2.12 m:female_enrollments=507 m:two_or_more_races_rate=5 m:aea=15 m:male_enrollments=566 m:female_rate=2.56 m:hispanic_rate=0 m:county=62 m:white_dropouts=24 m:overall_enrollments=1073 m:overall_dropouts=25 m:asian_rate=0 m:female_dropouts=13 m:african_american_rate=0
```

## Meta Commands

```ls
metric m:county p:integer l:County t:dataTypeName=number

metric m:aea p:integer l:AEA t:dataTypeName=number

metric m:overall_dropouts p:integer l:"Overall Dropouts" t:dataTypeName=number

metric m:overall_enrollments p:integer l:"Overall Enrollments" t:dataTypeName=number

metric m:overall_rate p:float l:"Overall Rate" t:dataTypeName=number

metric m:african_american_rate p:float l:"African American Rate" t:dataTypeName=number

metric m:hispanic_rate p:float l:"Hispanic Rate" t:dataTypeName=number

metric m:american_indian_rate p:float l:"American Indian Rate" t:dataTypeName=number

metric m:asian_rate p:double l:"Asian Rate" t:dataTypeName=number

metric m:hawaiian_pacific_islander_rate p:double l:"Hawaiian/Pacific Islander Rate" t:dataTypeName=number

metric m:white_dropouts p:integer l:"White Dropouts" t:dataTypeName=number

metric m:white_enrollments p:integer l:"White Enrollments" t:dataTypeName=number

metric m:white_rate p:float l:"White Rate" t:dataTypeName=number

metric m:two_or_more_races_rate p:float l:"Two or More Races Rate" t:dataTypeName=number

metric m:female_dropouts p:integer l:"Female Dropouts" t:dataTypeName=number

metric m:female_enrollments p:integer l:"Female Enrollments" t:dataTypeName=number

metric m:female_rate p:float l:"Female Rate" t:dataTypeName=number

metric m:male_dropouts p:integer l:"Male Dropouts" t:dataTypeName=number

metric m:male_enrollments p:integer l:"Male Enrollments" t:dataTypeName=number

metric m:male_rate p:float l:"Male Rate" t:dataTypeName=number

entity e:ni52-mxqy l:"2014-2015 Public School District Dropout Rates" t:attribution="Iowa Department of Education" t:url=https://data.iowa.gov/api/views/ni52-mxqy

property e:ni52-mxqy t:meta.view v:id=ni52-mxqy v:category=Education v:attributionLink=https://www.educateiowa.gov/education-statistics v:averageRating=0 v:name="2014-2015 Public School District Dropout Rates" v:attribution="Iowa Department of Education"

property e:ni52-mxqy t:meta.view.owner v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:displayName="Iowa Department of Education"

property e:ni52-mxqy t:meta.view.tableauthor v:id=hthm-474y v:profileImageUrlMedium=/api/users/hthm-474y/profile_images/THUMB v:profileImageUrlLarge=/api/users/hthm-474y/profile_images/LARGE v:screenName="Iowa Department of Education" v:profileImageUrlSmall=/api/users/hthm-474y/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Education"
```

## Top Records

```ls
| district | district_name         | county | aea | overall_dropouts | overall_enrollments | overall_rate | african_american_dropouts | african_american_enrollments | african_american_rate | hispanic_dropouts | hispanic_enrollments | hispanic_rate | american_indian_dropouts | american_indian_enrollments | american_indian_rate | asian_dropouts | asian_enrollments | asian_rate | hawaiian_pacific_islander_dropouts | hawaiian_pacific_islander_enrollments | hawaiian_pacific_islander_rate | white_dropouts | white_enrollments | white_rate | two_or_more_races_dropouts | two_or_more_races_enrollments | two_or_more_races_rate | female_dropouts | female_enrollments | female_rate | male_dropouts | male_enrollments | male_rate | grade_7_12_status | 
| ======== | ===================== | ====== | === | ================ | =================== | ============ | ========================= | ============================ | ===================== | ================= | ==================== | ============= | ======================== | =========================== | ==================== | ============== | ================= | ========== | ================================== | ===================================== | ============================== | ============== | ================= | ========== | ========================== | ============================= | ====================== | =============== | ================== | =========== | ============= | ================ | ========= | ================= | 
| 9        | AGWSR                 | 42     | 7   | 2                | 240                 | 0.83         | ****                      | ****                         |                       | 0                 | 27                   | 0             | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 0              | 206               | 0          | ****                       | ****                          |                        | 2               | 116                | 1.72        | 0             | 124              | 0         | High School       | 
| 18       | Adair-Casey           | 39     | 11  | 0                | 128                 | 0            | ****                      | ****                         |                       | ****              | ****                 |               | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 0              | 126               | 0          | ****                       | ****                          |                        | 0               | 67                 | 0           | 0             | 61               | 0         | High School       | 
| 5013     | Oskaloosa             | 62     | 15  | 25               | 1073                | 2.33         | 0                         | 10                           | 0                     | 0                 | 29                   | 0             | ****                     | ****                        |                      | 0              | 23                | 0          | ****                               | ****                                  |                                | 24             | 985               | 2.44       | 1                          | 20                            | 5                      | 13              | 507                | 2.56        | 12            | 566              | 2.12      | High School       | 
| 225      | Ames                  | 85     | 11  | 20               | 1889                | 1.06         | 4                         | 145                          | 2.76                  | 2                 | 133                  | 1.5           | ****                     | ****                        |                      | 0              | 157               | 0          | ****                               | ****                                  |                                | 12             | 1372              | 0.87       | 2                          | 76                            | 2.63                   | 6               | 929                | 0.65        | 14            | 960              | 1.46      | High School       | 
| 63       | Akron Westfield       | 75     | 12  | 0                | 235                 | 0            | ****                      | ****                         |                       | 0                 | 17                   | 0             | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 0              | 203               | 0          | ****                       | ****                          |                        | 0               | 105                | 0           | 0             | 130              | 0         | High School       | 
| 72       | Albert City-Truesdale | 11     | 5   |                  |                     |              | ****                      | ****                         |                       | ****              | ****                 |               | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                |                |                   |            | ****                       | ****                          |                        |                 |                    |             |               |                  |           | No 7-12           | 
| 27       | Adel DeSoto Minburn   | 25     | 11  | 4                | 709                 | 0.56         | ****                      | ****                         |                       | 1                 | 10                   | 10            | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 2              | 678               | 0.29       | 1                          | 11                            | 9.09                   | 1               | 339                | 0.29        | 3             | 370              | 0.81      | High School       | 
| 1503     | Creston               | 88     | 13  | 4                | 679                 | 0.59         | 0                         | 11                           | 0                     | 0                 | 27                   | 0             | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 4              | 616               | 0.65       | 0                          | 18                            | 0                      | 1               | 344                | 0.29        | 3             | 335              | 0.9       | High School       | 
| 81       | Albia                 | 68     | 15  | 1                | 521                 | 0.19         | ****                      | ****                         |                       | 0                 | 16                   | 0             | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 1              | 486               | 0.21       | ****                       | ****                          |                        | 1               | 248                | 0.4         | 0             | 273              | 0         | High School       | 
| 99       | Alburnett             | 57     | 10  | 3                | 304                 | 0.99         | ****                      | ****                         |                       | ****              | ****                 |               | ****                     | ****                        |                      | ****           | ****              |            | ****                               | ****                                  |                                | 3              | 292               | 1.03       | ****                       | ****                          |                        | 2               | 139                | 1.44        | 1             | 165              | 0.61      | High School       | 
```