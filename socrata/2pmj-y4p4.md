# Audited Register Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/audited-register-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2pmj-y4p4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2pmj-y4p4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2pmj-y4p4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2pmj-y4p4 |
| Name | Audited Register Data |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Created | 2015-12-30T16:54:48Z |
| Publication Date | 2016-03-08T21:22:44Z |

## Description

Official audited register by school.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | time           | year                                    | Year                                    | text      | text        |
| Yes      | series tag     | dbn                                     | DBN                                     | text      | text        |
| Yes      | series tag     | school_name                             | School Name                             | text      | text        |
| Yes      | numeric metric | total_enrollment                        | Total Enrollment                        | number    | number      |
| Yes      | numeric metric | grade_pk                                | Grade PK                                | number    | number      |
| Yes      | numeric metric | grade_k                                 | Grade K                                 | number    | number      |
| Yes      | numeric metric | grade_1                                 | Grade 1                                 | number    | number      |
| Yes      | numeric metric | grade_2                                 | Grade 2                                 | number    | number      |
| Yes      | numeric metric | grade_3                                 | Grade 3                                 | number    | number      |
| Yes      | numeric metric | grade_4                                 | Grade 4                                 | number    | number      |
| Yes      | numeric metric | grade_5                                 | Grade 5                                 | number    | number      |
| Yes      | numeric metric | grade_6                                 | Grade 6                                 | number    | number      |
| Yes      | numeric metric | grade_7                                 | Grade 7                                 | number    | number      |
| Yes      | numeric metric | grade_8                                 | Grade 8                                 | number    | number      |
| Yes      | numeric metric | grade_9                                 | Grade 9                                 | number    | number      |
| Yes      | numeric metric | grade_10                                | Grade 10                                | number    | number      |
| Yes      | numeric metric | grade_11                                | Grade 11                                | number    | number      |
| Yes      | numeric metric | grade_12                                | Grade 12                                | number    | number      |
| Yes      | numeric metric | female_1                                | # Female                                | number    | number      |
| Yes      | numeric metric | female_2                                | % Female                                | percent   | percent     |
| Yes      | numeric metric | male_1                                  | # Male                                  | number    | number      |
| Yes      | numeric metric | male_2                                  | % Male                                  | percent   | percent     |
| Yes      | numeric metric | asian_1                                 | # Asian                                 | number    | number      |
| Yes      | numeric metric | asian_2                                 | % Asian                                 | percent   | percent     |
| Yes      | numeric metric | black_1                                 | # Black                                 | number    | number      |
| Yes      | numeric metric | black_2                                 | % Black                                 | percent   | percent     |
| Yes      | numeric metric | hispanic_1                              | # Hispanic                              | number    | number      |
| Yes      | numeric metric | hispanic_2                              | % Hispanic                              | percent   | percent     |
| Yes      | numeric metric | other_1                                 | # Other                                 | number    | number      |
| Yes      | numeric metric | other_2                                 | % Other                                 | percent   | percent     |
| Yes      | numeric metric | white_1                                 | # White                                 | number    | number      |
| Yes      | numeric metric | white_2                                 | % White                                 | percent   | percent     |
| Yes      | numeric metric | students_with_disabilities_1            | # Students with Disabilities            | number    | number      |
| Yes      | numeric metric | students_with_disabilities_2            | % Students with Disabilities            | percent   | percent     |
| Yes      | numeric metric | english_language_learners_1             | # English Language Learners             | number    | number      |
| Yes      | numeric metric | english_language_learners_2             | % English Language Learners             | percent   | percent     |
| Yes      | numeric metric | qualified_for_free_or_reduced_lunches_1 | # Qualified for Free or Reduced Lunches | number    | number      |
| Yes      | numeric metric | qualified_for_free_or_reduced_lunches_2 | % Qualified for Free or Reduced Lunches | percent   | percent     |
| Yes      | numeric metric | poverty                                 | # Poverty                               | number    | number      |
| Yes      | numeric metric | poverty_2                               | % Poverty                               | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:2pmj-y4p4 d:2011-12-01T00:00:00.000Z t:school_name="PS 536" t:dbn=12X536 m:female_1=104 m:female_2=46.8 m:white_1=2 m:white_2=0.9 m:grade_pk=18 m:asian_2=4.1 m:grade_3=0 m:asian_1=9 m:grade_2=70 m:grade_1=59 m:students_with_disabilities_2=16.7 m:students_with_disabilities_1=37 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:grade_4=0 m:qualified_for_free_or_reduced_lunches_1=222 m:grade_8=0 m:grade_9=0 m:male_2=53.2 m:other_2=0.9 m:other_1=2 m:qualified_for_free_or_reduced_lunches_2=100 m:english_language_learners_1=55 m:english_language_learners_2=24.8 m:male_1=118 m:black_1=51 m:black_2=23 m:grade_12=0 m:hispanic_2=71.2 m:grade_11=0 m:total_enrollment=222 m:grade_k=75 m:grade_10=0 m:hispanic_1=158

series e:2pmj-y4p4 d:2010-11-01T00:00:00.000Z t:school_name="P.S. 319" t:dbn=14K319 m:female_1=107 m:female_2=55.4 m:white_1=0 m:white_2=0 m:grade_pk=36 m:asian_2=2.1 m:grade_3=0 m:asian_1=4 m:grade_2=0 m:grade_1=73 m:students_with_disabilities_2=10.9 m:students_with_disabilities_1=21 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:grade_4=0 m:qualified_for_free_or_reduced_lunches_1=193 m:grade_8=0 m:grade_9=0 m:male_2=44.6 m:other_2=0 m:other_1=0 m:qualified_for_free_or_reduced_lunches_2=100 m:english_language_learners_1=34 m:english_language_learners_2=17.6 m:male_1=86 m:black_1=3 m:black_2=1.6 m:grade_12=0 m:hispanic_2=96.4 m:grade_11=0 m:total_enrollment=193 m:grade_k=84 m:grade_10=0 m:hispanic_1=186

series e:2pmj-y4p4 d:2015-03-01T00:00:00.000Z t:school_name="Jamaica Children's School" t:dbn=28Q312 m:female_1=17 m:female_2=47.2 m:white_1=0 m:white_2=0 m:grade_pk=0 m:asian_2=0 m:grade_3=0 m:asian_1=0 m:grade_2=0 m:grade_1=0 m:students_with_disabilities_2=13.9 m:students_with_disabilities_1=5 m:grade_7=0 m:grade_6=0 m:grade_5=0 m:grade_4=0 m:qualified_for_free_or_reduced_lunches_1=33 m:grade_8=0 m:grade_9=0 m:male_2=52.8 m:other_2=0 m:other_1=0 m:qualified_for_free_or_reduced_lunches_2=91.7 m:english_language_learners_1=3 m:english_language_learners_2=8.3 m:male_1=19 m:black_1=31 m:black_2=86.1 m:grade_12=0 m:hispanic_2=13.9 m:grade_11=0 m:total_enrollment=36 m:grade_k=36 m:grade_10=0 m:hispanic_1=5
```

## Meta Commands

```ls
metric m:total_enrollment p:integer l:"Total Enrollment" t:dataTypeName=number

metric m:grade_pk p:integer l:"Grade PK" t:dataTypeName=number

metric m:grade_k p:integer l:"Grade K" t:dataTypeName=number

metric m:grade_1 p:integer l:"Grade 1" t:dataTypeName=number

metric m:grade_2 p:integer l:"Grade 2" t:dataTypeName=number

metric m:grade_3 p:integer l:"Grade 3" t:dataTypeName=number

metric m:grade_4 p:integer l:"Grade 4" t:dataTypeName=number

metric m:grade_5 p:integer l:"Grade 5" t:dataTypeName=number

metric m:grade_6 p:integer l:"Grade 6" t:dataTypeName=number

metric m:grade_7 p:integer l:"Grade 7" t:dataTypeName=number

metric m:grade_8 p:integer l:"Grade 8" t:dataTypeName=number

metric m:grade_9 p:integer l:"Grade 9" t:dataTypeName=number

metric m:grade_10 p:integer l:"Grade 10" t:dataTypeName=number

metric m:grade_11 p:integer l:"Grade 11" t:dataTypeName=number

metric m:grade_12 p:integer l:"Grade 12" t:dataTypeName=number

metric m:female_1 p:integer l:"# Female" t:dataTypeName=number

metric m:female_2 p:float l:"% Female" t:dataTypeName=percent

metric m:male_1 p:integer l:"# Male" t:dataTypeName=number

metric m:male_2 p:float l:"% Male" t:dataTypeName=percent

metric m:asian_1 p:integer l:"# Asian" t:dataTypeName=number

metric m:asian_2 p:float l:"% Asian" t:dataTypeName=percent

metric m:black_1 p:integer l:"# Black" t:dataTypeName=number

metric m:black_2 p:float l:"% Black" t:dataTypeName=percent

metric m:hispanic_1 p:integer l:"# Hispanic" t:dataTypeName=number

metric m:hispanic_2 p:float l:"% Hispanic" t:dataTypeName=percent

metric m:other_1 p:integer l:"# Other" t:dataTypeName=number

metric m:other_2 p:float l:"% Other" t:dataTypeName=percent

metric m:white_1 p:integer l:"# White" t:dataTypeName=number

metric m:white_2 p:float l:"% White" t:dataTypeName=percent

metric m:students_with_disabilities_1 p:integer l:"# Students with Disabilities" t:dataTypeName=number

metric m:students_with_disabilities_2 p:float l:"% Students with Disabilities" t:dataTypeName=percent

metric m:english_language_learners_1 p:integer l:"# English Language Learners" t:dataTypeName=number

metric m:english_language_learners_2 p:float l:"% English Language Learners" t:dataTypeName=percent

metric m:qualified_for_free_or_reduced_lunches_1 p:integer l:"# Qualified for Free or Reduced Lunches" t:dataTypeName=number

metric m:qualified_for_free_or_reduced_lunches_2 p:float l:"% Qualified for Free or Reduced Lunches" t:dataTypeName=percent

metric m:poverty p:integer l:"# Poverty" t:dataTypeName=number

metric m:poverty_2 p:float l:"% Poverty" t:dataTypeName=percent

entity e:2pmj-y4p4 l:"Audited Register Data" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/2pmj-y4p4

property e:2pmj-y4p4 t:meta.view v:id=2pmj-y4p4 v:category=Education v:averageRating=0 v:name="Audited Register Data" v:attribution="Department of Education (DOE)"

property e:2pmj-y4p4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2pmj-y4p4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year    | dbn    | school_name               | total_enrollment | grade_pk | grade_k | grade_1 | grade_2 | grade_3 | grade_4 | grade_5 | grade_6 | grade_7 | grade_8 | grade_9 | grade_10 | grade_11 | grade_12 | female_1 | female_2 | male_1 | male_2 | asian_1 | asian_2 | black_1 | black_2 | hispanic_1 | hispanic_2 | other_1 | other_2 | white_1 | white_2 | students_with_disabilities_1 | students_with_disabilities_2 | english_language_learners_1 | english_language_learners_2 | qualified_for_free_or_reduced_lunches_1 | qualified_for_free_or_reduced_lunches_2 | poverty | poverty_2 | 
| ======= | ====== | ========================= | ================ | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ======= | ======= | ======= | ======= | ========== | ========== | ======= | ======= | ======= | ======= | ============================ | ============================ | =========================== | =========================== | ======================================= | ======================================= | ======= | ========= | 
| 2011-12 | 12X536 | PS 536                    | 222              | 18       | 75      | 59      | 70      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 104      | 46.80    | 118    | 53.20  | 9       | 4.10    | 51      | 23.00   | 158        | 71.20      | 2       | 0.90    | 2       | 0.90    | 37                           | 16.70                        | 55                          | 24.80                       | 222                                     | 100.00                                  |         |           | 
| 2010-11 | 14K319 | P.S. 319                  | 193              | 36       | 84      | 73      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 107      | 55.40    | 86     | 44.60  | 4       | 2.10    | 3       | 1.60    | 186        | 96.40      | 0       | 0.00    | 0       | 0.00    | 21                           | 10.90                        | 34                          | 17.60                       | 193                                     | 100.00                                  |         |           | 
| 2014-15 | 28Q312 | Jamaica Children's School | 36               | 0        | 36      | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 17       | 47.20    | 19     | 52.80  | 0       | 0.00    | 31      | 86.10   | 5          | 13.90      | 0       | 0.00    | 0       | 0.00    | 5                            | 13.90                        | 3                           | 8.30                        | 33                                      | 91.70                                   |         |           | 
| 2010-11 | 01M015 | P.S. 015 Roberto Clemente | 203              | 13       | 37      | 35      | 33      | 30      | 30      | 25      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 90       | 44.30    | 113    | 55.70  | 13      | 6.40    | 75      | 36.90   | 110        | 54.20      | 1       | 0.50    | 4       | 2.00    | 51                           | 25.10                        | 30                          | 14.80                       | 203                                     | 100.00                                  |         |           | 
| 2011-12 | 01M015 | P.S. 015 Roberto Clemente | 189              | 13       | 31      | 35      | 28      | 25      | 28      | 29      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 92       | 48.70    | 97     | 51.30  | 12      | 6.30    | 63      | 33.30   | 109        | 57.70      | 1       | 0.50    | 4       | 2.10    | 52                           | 27.50                        | 22                          | 11.60                       | 189                                     | 100.00                                  |         |           | 
| 2012-13 | 01M015 | P.S. 015 Roberto Clemente | 177              | 18       | 38      | 26      | 22      | 26      | 23      | 24      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 91       | 51.40    | 86     | 48.60  | 15      | 8.50    | 63      | 35.60   | 93         | 52.50      | 3       | 1.70    | 3       | 1.70    | 55                           | 31.10                        | 21                          | 11.90                       | 177                                     | 100.00                                  |         |           | 
| 2013-14 | 01M015 | P.S. 015 Roberto Clemente | 190              | 26       | 39      | 39      | 21      | 16      | 26      | 23      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 93       | 48.90    | 97     | 51.10  | 9       | 4.70    | 72      | 37.90   | 104        | 54.70      | 2       | 1.10    | 3       | 1.60    | 65                           | 34.20                        | 19                          | 10.00                       | 190                                     | 100.00                                  |         |           | 
| 2014-15 | 01M015 | P.S. 015 Roberto Clemente | 183              | 18       | 27      | 47      | 31      | 19      | 17      | 24      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 84       | 45.90    | 99     | 54.10  | 8       | 4.40    | 65      | 35.50   | 107        | 58.50      | 1       | 0.50    | 2       | 1.10    | 57                           | 31.10                        | 17                          | 9.30                        | 183                                     | 100.00                                  |         |           | 
| 2010-11 | 01M019 | P.S. 019 Asher Levy       | 328              | 36       | 53      | 53      | 47      | 41      | 49      | 49      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 173      | 52.70    | 155    | 47.30  | 48      | 14.60   | 89      | 27.10   | 155        | 47.30      | 5       | 1.50    | 31      | 9.50    | 73                           | 22.30                        | 33                          | 10.10                       | 328                                     | 100.00                                  |         |           | 
| 2011-12 | 01M019 | P.S. 019 Asher Levy       | 328              | 32       | 46      | 52      | 54      | 52      | 46      | 46      | 0       | 0       | 0       | 0       | 0        | 0        | 0        | 181      | 55.20    | 147    | 44.80  | 51      | 15.50   | 81      | 24.70   | 158        | 48.20      | 10      | 3.00    | 28      | 8.50    | 66                           | 20.10                        | 33                          | 10.10                       | 328                                     | 100.00                                  |         |           | 
```