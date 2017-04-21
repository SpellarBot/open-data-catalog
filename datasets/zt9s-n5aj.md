# SAT (College Board) 2010 School Level Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sat-college-board-2010-school-level-results-5c6d6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zt9s-n5aj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zt9s-n5aj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zt9s-n5aj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zt9s-n5aj |
| Name | SAT (College Board) 2010 School Level Results |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T18:13:52Z |
| Publication Date | 2011-10-11T18:23:37Z |

## Description

New York City school level College Board SAT results for the graduating seniors of 2010.  Records contain 2010 College-bound seniors mean SAT scores. 

Records with 5 or fewer students are suppressed (marked ?s?). 

College-bound seniors are those students that complete the SAT Questionnaire when they register for the SAT and identify that they will graduate from high school in a specific year. For example, the 2010 college-bound seniors are those students that self-reported they would graduate in 2010. Students are not required to complete the SAT Questionnaire in order to register for the SAT. Students who do not indicate which year they will graduate from high school will not be included in any college-bound senior report.  

Students are linked to schools by identifying which school they attend when registering for a College Board exam. A student is only included in a school?s report if he/she self-reports being enrolled at that school. 

Data collected and processed by the College Board.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | dbn                   | DBN                   | text      | text        |
| Yes      | series tag     | school_name           | School Name           | text      | text        |
| Yes      | numeric metric | number_of_test_takers | Number of Test Takers | number    | number      |
| Yes      | numeric metric | critical_reading_mean | Critical Reading Mean | number    | number      |
| Yes      | numeric metric | mathematics_mean      | Mathematics Mean      | number    | number      |
| Yes      | numeric metric | writing_mean          | Writing Mean          | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zt9s-n5aj d:2010-01-01T00:00:00.000Z t:school_name="Henry Street School for International Studies" t:dbn=01M292 m:writing_mean=385 m:mathematics_mean=425 m:critical_reading_mean=391 m:number_of_test_takers=31

series e:zt9s-n5aj d:2010-01-01T00:00:00.000Z t:school_name="University Neighborhood High School" t:dbn=01M448 m:writing_mean=387 m:mathematics_mean=419 m:critical_reading_mean=394 m:number_of_test_takers=60

series e:zt9s-n5aj d:2010-01-01T00:00:00.000Z t:school_name="East Side Community High School" t:dbn=01M450 m:writing_mean=402 m:mathematics_mean=431 m:critical_reading_mean=418 m:number_of_test_takers=69
```

## Meta Commands

```ls
metric m:number_of_test_takers p:integer l:"Number of Test Takers" t:dataTypeName=number

metric m:critical_reading_mean p:integer l:"Critical Reading Mean" t:dataTypeName=number

metric m:mathematics_mean p:integer l:"Mathematics Mean" t:dataTypeName=number

metric m:writing_mean p:integer l:"Writing Mean" t:dataTypeName=number

entity e:zt9s-n5aj l:"SAT (College Board) 2010 School Level Results" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/zt9s-n5aj

property e:zt9s-n5aj t:meta.view v:id=zt9s-n5aj v:category=Education v:averageRating=0 v:name="SAT (College Board) 2010 School Level Results" v:attribution="Department of Education (DOE)"

property e:zt9s-n5aj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zt9s-n5aj t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | school_name                                   | number_of_test_takers | critical_reading_mean | mathematics_mean | writing_mean | 
| ====== | ============================================= | ===================== | ===================== | ================ | ============ | 
| 01M292 | Henry Street School for International Studies | 31                    | 391                   | 425              | 385          | 
| 01M448 | University Neighborhood High School           | 60                    | 394                   | 419              | 387          | 
| 01M450 | East Side Community High School               | 69                    | 418                   | 431              | 402          | 
| 01M458 | SATELLITE ACADEMY FORSYTH ST                  | 26                    | 385                   | 370              | 378          | 
| 01M509 | CMSP HIGH SCHOOL                              |                       |                       |                  |              | 
| 01M515 | Lower East Side Preparatory High School       | 154                   | 314                   | 532              | 314          | 
| 01M539 | New Explorations into Sci, Tech and Math HS   | 47                    | 568                   | 583              | 568          | 
| 01M650 | CASCADES HIGH SCHOOL                          | 35                    | 411                   | 401              | 401          | 
| 01M696 | BARD HIGH SCHOOL EARLY COLLEGE                | 138                   | 630                   | 608              | 630          | 
| 02M047 | AMERICAN SIGN LANG ENG DUAL                   | 11                    | 405                   | 415              | 385          | 
```