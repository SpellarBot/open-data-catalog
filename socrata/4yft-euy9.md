# Student Gender Grade Ethnicity By Neighborhood 2007 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/student-gender-grade-ethnicity-by-neighborhood-2007-2010) |
| Metadata | [Link](https://data.hartford.gov/api/views/4yft-euy9) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/4yft-euy9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/4yft-euy9/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 4yft-euy9 |
| Name | Student Gender Grade Ethnicity By Neighborhood 2007 2010 |
| Attribution | City of Hartford - Hartford Public Schools |
| Category | Education/Youth/Family |
| Tags | hartford, schools, education, students |
| Created | 2014-07-28T20:49:07Z |
| Publication Date | 2014-07-28T20:53:24Z |

## Description

Hartford Public Schools student data by neighborhood school years 2007 - 2010

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                               | Data Type | Render Type |
| ======== | ============== | ================================= | ================================== | ========= | =========== |
| Yes      | series tag     | neighborhood                      | Neighborhood                       | text      | text        |
| Yes      | series tag     | year                              | Year                               | text      | text        |
| Yes      | numeric metric | gender_male                       | Gender_Male                        | number    | number      |
| Yes      | numeric metric | gender_female                     | Gender_Female                      | number    | number      |
| Yes      | numeric metric | grade_pk                          | Grade_PK                           | number    | number      |
| Yes      | numeric metric | grade_kf                          | Grade_KF                           | number    | number      |
| Yes      | numeric metric | grade_1                           | Grade_1                            | number    | number      |
| Yes      | numeric metric | grade_2                           | Grade_2                            | number    | number      |
| Yes      | numeric metric | grade_3                           | Grade_3                            | number    | number      |
| Yes      | numeric metric | grade_4                           | Grade_4                            | number    | number      |
| Yes      | numeric metric | grade_5                           | Grade_5                            | number    | number      |
| Yes      | numeric metric | grade_6                           | Grade_6                            | number    | number      |
| Yes      | numeric metric | grade_7                           | Grade_7                            | number    | number      |
| Yes      | numeric metric | grade_8                           | Grade_8                            | number    | number      |
| Yes      | numeric metric | grade_9                           | Grade_9                            | number    | number      |
| Yes      | numeric metric | grade_10                          | Grade_10                           | number    | number      |
| Yes      | numeric metric | grade_11                          | Grade_11                           | number    | number      |
| Yes      | numeric metric | grade_12                          | Grade_12                           | number    | number      |
| Yes      | numeric metric | race_american_indian              | Race_American Indian               | number    | number      |
| Yes      | numeric metric | race_asian                        | Race_Asian                         | number    | number      |
| Yes      | numeric metric | race_black                        | Race_Black                         | number    | number      |
| Yes      | numeric metric | race_hispanic_latino              | Race_Hispanic/Latino               | number    | number      |
| Yes      | numeric metric | race_white_not_of_hispanic_origin | Race_White, not of Hispanic Origin | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4yft-euy9 d:2007-01-01T00:00:00.000Z t:neighborhood="Asylum Hill" t:year=2007-2008 m:gender_female=672 m:race_asian=28 m:grade_pk=43 m:race_white_not_of_hispanic_origin=44 m:grade_3=98 m:grade_2=105 m:race_hispanic_latino=538 m:grade_1=125 m:grade_7=77 m:grade_6=94 m:grade_5=85 m:grade_4=86 m:grade_8=105 m:grade_12=85 m:grade_9=162 m:grade_11=78 m:gender_male=709 m:race_black=770 m:grade_10=99 m:grade_kf=139 m:race_american_indian=1

series e:4yft-euy9 d:2007-01-01T00:00:00.000Z t:neighborhood="Asylum Hill" t:year=2008-2009 m:gender_female=610 m:race_asian=72 m:grade_pk=29 m:race_white_not_of_hispanic_origin=48 m:grade_3=95 m:grade_2=105 m:race_hispanic_latino=436 m:grade_1=114 m:grade_7=95 m:grade_6=86 m:grade_5=68 m:grade_4=96 m:grade_8=80 m:grade_12=70 m:grade_9=105 m:grade_11=66 m:gender_male=610 m:race_black=663 m:grade_10=112 m:grade_kf=99 m:race_american_indian=1

series e:4yft-euy9 d:2007-01-01T00:00:00.000Z t:neighborhood="Asylum Hill" t:year=2009-2010 m:gender_female=592 m:race_asian=121 m:grade_pk=37 m:race_white_not_of_hispanic_origin=46 m:grade_3=103 m:grade_2=112 m:race_hispanic_latino=405 m:grade_1=114 m:grade_7=74 m:grade_6=70 m:grade_5=82 m:grade_4=94 m:grade_8=81 m:grade_12=65 m:grade_9=94 m:grade_11=89 m:gender_male=628 m:race_black=644 m:grade_10=90 m:grade_kf=115 m:race_american_indian=4
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

metric m:race_american_indian p:integer l:"Race_American Indian" t:dataTypeName=number

metric m:race_asian p:integer l:Race_Asian t:dataTypeName=number

metric m:race_black p:integer l:Race_Black t:dataTypeName=number

metric m:race_hispanic_latino p:integer l:Race_Hispanic/Latino t:dataTypeName=number

metric m:race_white_not_of_hispanic_origin p:integer l:"Race_White, not of Hispanic Origin" t:dataTypeName=number

entity e:4yft-euy9 l:"Student Gender Grade Ethnicity By Neighborhood 2007 2010" t:attribution="City of Hartford - Hartford Public Schools" t:url=https://data.hartford.gov/api/views/4yft-euy9

property e:4yft-euy9 t:meta.view v:id=4yft-euy9 v:category=Education/Youth/Family v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Student Gender Grade Ethnicity By Neighborhood 2007 2010" v:attribution="City of Hartford - Hartford Public Schools"

property e:4yft-euy9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4yft-euy9 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:4yft-euy9 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| neighborhood     | year      | gender_male | gender_female | grade_pk | grade_kf | grade_1 | grade_2 | grade_3 | grade_4 | grade_5 | grade_6 | grade_7 | grade_8 | grade_9 | grade_10 | grade_11 | grade_12 | race_american_indian | race_asian | race_black | race_hispanic_latino | race_white_not_of_hispanic_origin | 
| ================ | ========= | =========== | ============= | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ==================== | ========== | ========== | ==================== | ================================= | 
| Asylum Hill      | 2007-2008 | 709         | 672           | 43       | 139      | 125     | 105     | 98      | 86      | 85      | 94      | 77      | 105     | 162     | 99       | 78       | 85       | 1                    | 28         | 770        | 538                  | 44                                | 
| Asylum Hill      | 2008-2009 | 610         | 610           | 29       | 99       | 114     | 105     | 95      | 96      | 68      | 86      | 95      | 80      | 105     | 112      | 66       | 70       | 1                    | 72         | 663        | 436                  | 48                                | 
| Asylum Hill      | 2009-2010 | 628         | 592           | 37       | 115      | 114     | 112     | 103     | 94      | 82      | 70      | 74      | 81      | 94      | 90       | 89       | 65       | 4                    | 121        | 644        | 405                  | 46                                | 
| Barry Square     | 2007-2008 | 1390        | 1376          | 95       | 233      | 239     | 197     | 219     | 215     | 211     | 192     | 184     | 222     | 315     | 168      | 139      | 137      | 3                    | 20         | 605        | 2017                 | 121                               | 
| Barry Square     | 2008-2009 | 1310        | 1256          | 75       | 221      | 244     | 202     | 190     | 219     | 189     | 165     | 198     | 158     | 281     | 153      | 150      | 121      | 2                    | 31         | 530        | 1882                 | 121                               | 
| Barry Square     | 2009-2010 | 1302        | 1247          | 105      | 227      | 224     | 212     | 191     | 181     | 218     | 192     | 158     | 197     | 244     | 144      | 147      | 109      | 4                    | 41         | 538        | 1864                 | 102                               | 
| Behind The Rocks | 2007-2008 | 943         | 851           | 71       | 130      | 148     | 147     | 144     | 160     | 147     | 131     | 146     | 141     | 159     | 95       | 87       | 88       | 3                    | 6          | 321        | 1414                 | 50                                | 
| Behind The Rocks | 2008-2009 | 900         | 816           | 83       | 133      | 121     | 151     | 135     | 141     | 144     | 126     | 137     | 133     | 113     | 128      | 85       | 86       | 2                    | 6          | 295        | 1371                 | 42                                | 
| Behind The Rocks | 2009-2010 | 891         | 826           | 82       | 132      | 136     | 119     | 145     | 143     | 133     | 150     | 125     | 125     | 138     | 91       | 117      | 81       | 2                    | 6          | 282        | 1387                 | 40                                | 
| Blue Hills       | 2007-2008 | 1042        | 855           | 85       | 172      | 155     | 132     | 136     | 141     | 141     | 126     | 124     | 134     | 155     | 143      | 122      | 131      | 5                    | 1          | 1689       | 188                  | 14                                | 
```