# AP (College Board) 2010 School Level Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ap-college-board-2010-school-level-results-60a4c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/itfs-ms3e) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/itfs-ms3e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/itfs-ms3e/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | itfs-ms3e |
| Name | AP (College Board) 2010 School Level Results |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T18:25:29Z |
| Publication Date | 2011-10-11T18:24:55Z |

## Description

New York City school level College Board AP results for 2010.  

Records with 5 or fewer students are suppressed. 

Students are linked to schools by identifying which school they attend when registering for a College Board exam. A student is only included in a school?s report if he/she self-reports being enrolled at that school. 

Data collected and processed by the College Board.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | dbn                                  | DBN                                  | text      | text        |
| Yes      | series tag     | schoolname                           | SchoolName                           | text      | text        |
| Yes      | numeric metric | ap_test_takers_                      | AP Test Takers                       | number    | number      |
| Yes      | numeric metric | total_exams_taken                    | Total Exams Taken                    | number    | number      |
| Yes      | numeric metric | number_of_exams_with_scores_3_4_or_5 | Number of Exams with scores 3 4 or 5 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:itfs-ms3e d:2010-01-01T00:00:00.000Z t:schoolname="UNIVERSITY NEIGHBORHOOD H.S." t:dbn=01M448 m:number_of_exams_with_scores_3_4_or_5=10 m:total_exams_taken=49 m:ap_test_takers_=39

series e:itfs-ms3e d:2010-01-01T00:00:00.000Z t:schoolname="EAST SIDE COMMUNITY HS" t:dbn=01M450 m:total_exams_taken=21 m:ap_test_takers_=19

series e:itfs-ms3e d:2010-01-01T00:00:00.000Z t:schoolname="LOWER EASTSIDE PREP" t:dbn=01M515 m:number_of_exams_with_scores_3_4_or_5=24 m:total_exams_taken=26 m:ap_test_takers_=24
```

## Meta Commands

```ls
metric m:ap_test_takers_ p:integer l:"AP Test Takers" t:dataTypeName=number

metric m:total_exams_taken p:integer l:"Total Exams Taken" t:dataTypeName=number

metric m:number_of_exams_with_scores_3_4_or_5 p:integer l:"Number of Exams with scores 3 4 or 5" t:dataTypeName=number

entity e:itfs-ms3e l:"AP (College Board) 2010 School Level Results" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/itfs-ms3e

property e:itfs-ms3e t:meta.view v:id=itfs-ms3e v:category=Education v:averageRating=0 v:name="AP (College Board) 2010 School Level Results" v:attribution="Department of Education (DOE)"

property e:itfs-ms3e t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:itfs-ms3e t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | schoolname                                        | ap_test_takers_ | total_exams_taken | number_of_exams_with_scores_3_4_or_5 | 
| ====== | ================================================= | =============== | ================= | ==================================== | 
| 01M448 | UNIVERSITY NEIGHBORHOOD H.S.                      | 39              | 49                | 10                                   | 
| 01M450 | EAST SIDE COMMUNITY HS                            | 19              | 21                |                                      | 
| 01M515 | LOWER EASTSIDE PREP                               | 24              | 26                | 24                                   | 
| 01M539 | NEW EXPLORATIONS SCI,TECH,MATH                    | 255             | 377               | 191                                  | 
| 02M296 | High School of Hospitality Management             |                 |                   |                                      | 
| 02M298 | Pace High School                                  | 21              | 21                |                                      | 
| 02M300 | Urban Assembly School of Design and Construction, | 99              | 117               | 10                                   | 
| 02M303 | Facing History School, The                        | 42              | 44                |                                      | 
| 02M305 | Urban Assembly Academy of Government and Law, The | 25              | 37                | 15                                   | 
| 02M308 | Lower Manhattan Arts Academy                      |                 |                   |                                      | 
```