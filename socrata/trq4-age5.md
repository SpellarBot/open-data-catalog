# Student Gender Grade Ethnicity By Neighborhood 2010 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/student-gender-grade-ethnicity-by-neighborhood-2010-2012) |
| Metadata | [Link](https://data.hartford.gov/api/views/trq4-age5) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/trq4-age5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/trq4-age5/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | trq4-age5 |
| Name | Student Gender Grade Ethnicity By Neighborhood 2010 2012 |
| Attribution | City of Hartford - Hartford Public Schools |
| Category | Education/Youth/Family |
| Tags | hartford, schools, education, student |
| Created | 2014-07-29T12:12:26Z |
| Publication Date | 2014-07-29T12:17:36Z |

## Description

Hartford Public Schools student data by neighborhood school years 2010 2012

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================== | ============================================== | ========= | =========== |
| Yes      | series tag     | neighborhood                                   | Neighborhood                                   | text      | text        |
| Yes      | series tag     | year                                           | Year                                           | text      | text        |
| Yes      | numeric metric | gender_male                                    | Gender_Male                                    | number    | number      |
| Yes      | numeric metric | gender_female                                  | Gender_Female                                  | number    | number      |
| Yes      | numeric metric | grade_pk                                       | Grade_PK                                       | number    | number      |
| Yes      | numeric metric | grade_kf                                       | Grade_KF                                       | number    | number      |
| Yes      | numeric metric | grade_1                                        | Grade_1                                        | number    | number      |
| Yes      | numeric metric | grade_2                                        | Grade_2                                        | number    | number      |
| Yes      | numeric metric | grade_3                                        | Grade_3                                        | number    | number      |
| Yes      | numeric metric | grade_4                                        | Grade_4                                        | number    | number      |
| Yes      | numeric metric | grade_5                                        | Grade_5                                        | number    | number      |
| Yes      | numeric metric | grade_6                                        | Grade_6                                        | number    | number      |
| Yes      | numeric metric | grade_7                                        | Grade_7                                        | number    | number      |
| Yes      | numeric metric | grade_8                                        | Grade_8                                        | number    | number      |
| Yes      | numeric metric | grade_9                                        | Grade_9                                        | number    | number      |
| Yes      | numeric metric | grade_10                                       | Grade_10                                       | number    | number      |
| Yes      | numeric metric | grade_11                                       | Grade_11                                       | number    | number      |
| Yes      | numeric metric | grade_12                                       | Grade_12                                       | number    | number      |
| Yes      | numeric metric | race_american_indian_alaska_native             | Race_American_Indian_Alaska_Native             | number    | number      |
| Yes      | numeric metric | race_asian                                     | Race_Asian                                     | number    | number      |
| Yes      | numeric metric | race_black_african_american                    | Race_Black/African American                    | number    | number      |
| Yes      | numeric metric | race_hispanic_latino                           | Race_Hispanic/Latino                           | number    | number      |
| Yes      | numeric metric | race_native_hawaiian_or_other_pacific_islander | Race_Native_Hawaiian_or_Other_Pacific_Islander | number    | number      |
| Yes      | numeric metric | race_two_or_more_races                         | Race_Two_or_More_Races                         | number    | number      |
| Yes      | numeric metric | race_white                                     | Race_White                                     | number    | number      |
| Yes      | numeric metric | race_no_ethnicity_race_defined                 | Race_No Ethnicity/Race Defined                 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:trq4-age5 d:2010-01-01T00:00:00.000Z t:neighborhood="Asylum Hill" t:year=2010-2011 m:gender_female=586 m:race_asian=131 m:grade_pk=48 m:grade_3=98 m:race_hispanic_latino=412 m:grade_2=107 m:grade_1=110 m:race_black_african_american=592 m:grade_7=61 m:race_white=35 m:grade_6=83 m:grade_5=85 m:grade_4=98 m:grade_8=68 m:grade_12=74 m:grade_9=78 m:grade_11=81 m:gender_male=589 m:race_american_indian_alaska_native=4 m:grade_10=88 m:race_native_hawaiian_or_other_pacific_islander=1 m:grade_kf=96

series e:trq4-age5 d:2010-01-01T00:00:00.000Z t:neighborhood="Asylum Hill" t:year=2011-2012 m:gender_female=585 m:race_asian=142 m:grade_pk=39 m:grade_3=103 m:race_hispanic_latino=418 m:grade_2=106 m:grade_1=110 m:race_black_african_american=550 m:grade_7=85 m:race_white=37 m:grade_6=83 m:grade_5=84 m:grade_4=93 m:grade_8=60 m:grade_12=71 m:grade_9=84 m:grade_11=85 m:race_two_or_more_races=58 m:gender_male=624 m:race_american_indian_alaska_native=4 m:grade_10=87 m:grade_kf=119

series e:trq4-age5 d:2010-01-01T00:00:00.000Z t:neighborhood="Barry Square" t:year=2010-2011 m:gender_female=1150 m:race_asian=54 m:race_no_ethnicity_race_defined=2 m:grade_pk=80 m:grade_3=206 m:race_hispanic_latino=1748 m:grade_2=203 m:grade_1=205 m:race_black_african_american=473 m:grade_7=173 m:race_white=93 m:grade_6=199 m:grade_5=171 m:grade_4=176 m:grade_8=157 m:grade_12=119 m:grade_9=225 m:grade_11=119 m:race_two_or_more_races=2 m:gender_male=1225 m:race_american_indian_alaska_native=3 m:grade_10=140 m:grade_kf=202
```

## Meta Commands

```ls
metric m:gender_male p:integer l:Gender_Male t:dataTypeName=number

metric m:gender_female p:integer l:Gender_Female t:dataTypeName=number

metric m:grade_pk p:integer l:Grade_PK t:dataTypeName=number

metric m:grade_kf p:integer l:Grade_KF t:dataTypeName=number

metric m:grade_1 p:integer l:Grade_1 t:dataTypeName=number

metric m:grade_2 p:integer l:Grade_2 t:dataTypeName=number

metric m:grade_3 p:integer l:Grade_3 t:dataTypeName=number

metric m:grade_4 p:integer l:Grade_4 t:dataTypeName=number

metric m:grade_5 p:integer l:Grade_5 t:dataTypeName=number

metric m:grade_6 p:integer l:Grade_6 t:dataTypeName=number

metric m:grade_7 p:integer l:Grade_7 t:dataTypeName=number

metric m:grade_8 p:integer l:Grade_8 t:dataTypeName=number

metric m:grade_9 p:integer l:Grade_9 t:dataTypeName=number

metric m:grade_10 p:integer l:Grade_10 t:dataTypeName=number

metric m:grade_11 p:integer l:Grade_11 t:dataTypeName=number

metric m:grade_12 p:integer l:Grade_12 t:dataTypeName=number

metric m:race_american_indian_alaska_native p:integer l:Race_American_Indian_Alaska_Native t:dataTypeName=number

metric m:race_asian p:integer l:Race_Asian t:dataTypeName=number

metric m:race_black_african_american p:integer l:"Race_Black/African American" t:dataTypeName=number

metric m:race_hispanic_latino p:integer l:Race_Hispanic/Latino t:dataTypeName=number

metric m:race_native_hawaiian_or_other_pacific_islander p:integer l:Race_Native_Hawaiian_or_Other_Pacific_Islander t:dataTypeName=number

metric m:race_two_or_more_races p:integer l:Race_Two_or_More_Races t:dataTypeName=number

metric m:race_white p:integer l:Race_White t:dataTypeName=number

metric m:race_no_ethnicity_race_defined p:integer l:"Race_No Ethnicity/Race Defined" t:dataTypeName=number

entity e:trq4-age5 l:"Student Gender Grade Ethnicity By Neighborhood 2010 2012" t:attribution="City of Hartford - Hartford Public Schools" t:url=https://data.hartford.gov/api/views/trq4-age5

property e:trq4-age5 t:meta.view v:id=trq4-age5 v:category=Education/Youth/Family v:attributionLink=http://www.hartford.gov v:averageRating=80 v:name="Student Gender Grade Ethnicity By Neighborhood 2010 2012" v:attribution="City of Hartford - Hartford Public Schools"

property e:trq4-age5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:trq4-age5 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:trq4-age5 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| neighborhood     | year      | gender_male | gender_female | grade_pk | grade_kf | grade_1 | grade_2 | grade_3 | grade_4 | grade_5 | grade_6 | grade_7 | grade_8 | grade_9 | grade_10 | grade_11 | grade_12 | race_american_indian_alaska_native | race_asian | race_black_african_american | race_hispanic_latino | race_native_hawaiian_or_other_pacific_islander | race_two_or_more_races | race_white | race_no_ethnicity_race_defined | 
| ================ | ========= | =========== | ============= | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ================================== | ========== | =========================== | ==================== | ============================================== | ====================== | ========== | ============================== | 
| Asylum Hill      | 2010-2011 | 589         | 586           | 48       | 96       | 110     | 107     | 98      | 98      | 85      | 83      | 61      | 68      | 78      | 88       | 81       | 74       | 4                                  | 131        | 592                         | 412                  | 1                                              |                        | 35         |                                | 
| Asylum Hill      | 2011-2012 | 624         | 585           | 39       | 119      | 110     | 106     | 103     | 93      | 84      | 83      | 85      | 60      | 84      | 87       | 85       | 71       | 4                                  | 142        | 550                         | 418                  |                                                | 58                     | 37         |                                | 
| Barry Square     | 2010-2011 | 1225        | 1150          | 80       | 202      | 205     | 203     | 206     | 176     | 171     | 199     | 173     | 157     | 225     | 140      | 119      | 119      | 3                                  | 54         | 473                         | 1748                 |                                                | 2                      | 93         | 2                              | 
| Barry Square     | 2011-2012 | 1214        | 1117          | 93       | 196      | 201     | 190     | 193     | 191     | 166     | 157     | 193     | 175     | 183     | 162      | 128      | 103      | 3                                  | 53         | 416                         | 1662                 | 2                                              | 71                     | 124        |                                | 
| Behind The Rocks | 2010-2011 | 858         | 785           | 70       | 124      | 120     | 137     | 119     | 128     | 136     | 132     | 145     | 121     | 109     | 101      | 88       | 113      | 3                                  | 8          | 278                         | 1318                 |                                                |                        | 34         | 2                              | 
| Behind The Rocks | 2011-2012 | 837         | 741           | 89       | 120      | 117     | 104     | 130     | 116     | 122     | 130     | 129     | 137     | 134     | 91       | 95       | 64       | 5                                  | 12         | 245                         | 1232                 | 1                                              | 36                     | 47         |                                | 
| Blue Hills       | 2010-2011 | 687         | 627           | 34       | 86       | 97      | 99      | 104     | 113     | 87      | 102     | 96      | 106     | 98      | 95       | 87       | 110      | 3                                  | 1          | 1148                        | 146                  |                                                | 2                      | 13         | 1                              | 
| Blue Hills       | 2011-2012 | 701         | 588           | 53       | 73       | 84      | 97      | 92      | 104     | 96      | 95      | 101     | 102     | 126     | 79       | 99       | 88       | 3                                  | 1          | 1086                        | 140                  |                                                | 45                     | 14         |                                | 
| Clay-Arsenal     | 2010-2011 | 580         | 591           | 38       | 93       | 93      | 98      | 101     | 92      | 96      | 88      | 87      | 85      | 80      | 95       | 61       | 64       | 1                                  | 3          | 485                         | 653                  |                                                | 2                      | 26         | 1                              | 
| Clay-Arsenal     | 2011-2012 | 569         | 593           | 33       | 110      | 96      | 91      | 87      | 104     | 76      | 100     | 82      | 86      | 93      | 74       | 74       | 56       | 1                                  | 2          | 457                         | 641                  | 1                                              | 29                     | 31         |                                | 
```