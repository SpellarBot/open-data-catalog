# DOE High School Programs 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doe-high-school-programs-2016) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ge8j-uqbf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ge8j-uqbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ge8j-uqbf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ge8j-uqbf |
| Name | DOE High School Programs 2016 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe, education, programs |
| Created | 2015-07-23T15:54:49Z |
| Publication Date | 2015-09-23T14:57:37Z |

## Description

Directory of High School programs

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | dbn                | dbn                | text      | text        |
| Yes      | series tag     | program            | program            | text      | text        |
| Yes      | series tag     | prgdesc            | prgdesc            | text      | text        |
| Yes      | series tag     | code               | code               | text      | text        |
| Yes      | series tag     | interest           | interest           | text      | text        |
| Yes      | series tag     | method             | method             | text      | text        |
| Yes      | series tag     | eng                | eng                | text      | text        |
| Yes      | series tag     | math               | math               | text      | text        |
| Yes      | series tag     | soc                | soc                | text      | text        |
| Yes      | series tag     | sci                | sci                | text      | text        |
| Yes      | series tag     | stm                | stm                | text      | text        |
| Yes      | series tag     | ela                | ela                | text      | text        |
| Yes      | series tag     | aud                | aud                | text      | text        |
| Yes      | numeric metric | seat_gr09          | seat_gr09          | number    | number      |
| Yes      | numeric metric | app_gr09           | app_gr09           | number    | number      |
| Yes      | series tag     | apps_per_seat_gr9  | apps_per_seat_gr9  | text      | text        |
| Yes      | numeric metric | seat_gr10          | seat_gr10          | number    | number      |
| Yes      | numeric metric | app_gr10           | app_gr10           | number    | number      |
| Yes      | series tag     | apps_per_seat_gr10 | apps_per_seat_gr10 | text      | text        |
| Yes      | series tag     | req1               | req1               | text      | text        |
| Yes      | series tag     | req2               | req2               | text      | text        |
| Yes      | series tag     | req3               | req3               | text      | text        |
| Yes      | series tag     | req4               | req4               | text      | text        |
| Yes      | series tag     | req5               | req5               | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ge8j-uqbf d:2016-01-01T00:00:00.000Z t:apps_per_seat_gr9="2 per seat" t:dbn=01M292 t:program="International Studies" t:interest="Humanities & Interdisciplinary" t:method="Limited Unscreened" t:code=M46X m:seat_gr09=81 m:app_gr09=170

series e:ge8j-uqbf d:2016-01-01T00:00:00.000Z t:apps_per_seat_gr9="4 per seat" t:apps_per_seat_gr10="4 per seat" t:prgdesc="An interdisciplinary, project-based program, with advisories, art and music electives, community service requirements and learning centers." t:dbn=01M448 t:program="University Neighborhood High School" t:interest="Science & Math" t:method="Ed. Opt." t:code=M35A m:app_gr10=38 m:seat_gr09=80 m:app_gr09=353 m:seat_gr10=10

series e:ge8j-uqbf d:2016-01-01T00:00:00.000Z t:apps_per_seat_gr9="1 per seat" t:apps_per_seat_gr10=- t:prgdesc="Students with limited English are taught by bilingual Mandarin speaking teachers in all core subjects and get extra support during Academic Intervention Services (AIS)." t:dbn=01M448 t:program="Bilingual Mandarin" t:interest=Business t:method="Screened: Language" t:code=M35B m:app_gr10=2 m:seat_gr09=20 m:app_gr09=17 m:seat_gr10=20
```

## Meta Commands

```ls
metric m:seat_gr09 p:integer l:seat_gr09 t:dataTypeName=number

metric m:app_gr09 p:integer l:app_gr09 t:dataTypeName=number

metric m:seat_gr10 p:integer l:seat_gr10 t:dataTypeName=number

metric m:app_gr10 p:integer l:app_gr10 t:dataTypeName=number

entity e:ge8j-uqbf l:"DOE High School Programs 2016" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ge8j-uqbf

property e:ge8j-uqbf t:meta.view v:id=ge8j-uqbf v:category=Education v:averageRating=0 v:name="DOE High School Programs 2016" v:attribution="Department of Education (DOE)"

property e:ge8j-uqbf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ge8j-uqbf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | program                                                  | prgdesc                                                                                                                                                                                                                                                                                                                                            | code | interest                       | method             | eng           | math          | soc           | sci           | stm            | ela            | aud | seat_gr09 | app_gr09 | apps_per_seat_gr9 | seat_gr10 | app_gr10 | apps_per_seat_gr10 | req1                       | req2                                                              | req3                                                       | req4 | req5 | 
| ====== | ======================================================== | ================================================================================================================================================================================================================================================================================================================================================== | ==== | ============================== | ================== | ============= | ============= | ============= | ============= | ============== | ============== | === | ========= | ======== | ================= | ========= | ======== | ================== | ========================== | ================================================================= | ========================================================== | ==== | ==== | 
| 01M292 | International Studies                                    |                                                                                                                                                                                                                                                                                                                                                    | M46X | Humanities & Interdisciplinary | Limited Unscreened |               |               |               |               |                |                |     | 81        | 170      | 2 per seat        |           |          |                    |                            |                                                                   |                                                            |      |      | 
| 01M448 | University Neighborhood High School                      | An interdisciplinary, project-based program, with advisories, art and music electives, community service requirements and learning centers.                                                                                                                                                                                                        | M35A | Science & Math                 | Ed. Opt.           |               |               |               |               |                |                |     | 80        | 353      | 4 per seat        | 10        | 38       | 4 per seat         |                            |                                                                   |                                                            |      |      | 
| 01M448 | Bilingual Mandarin                                       | Students with limited English are taught by bilingual Mandarin speaking teachers in all core subjects and get extra support during Academic Intervention Services (AIS).                                                                                                                                                                           | M35B | Business                       | Screened: Language |               |               |               |               |                |                |     | 20        | 17       | 1 per seat        | 20        | 2        | -                  |                            |                                                                   |                                                            |      |      | 
| 01M448 | University Neighborhood Early College                    | University Neighborhood Early College (UNEC) is designed for students interested in pursuing a career in business. UNEC provides rigorous curriculum with individualized academic supports, enabling students to earn a High School diploma and up to 24 college credits through City University of New York (CUNY) Baruch College within 4 years. | M35C | Business                       | Screened           | Scores 80-100 | Scores 80-100 | Scores 80-100 | Scores 80-100 | Levels 2.0-4.5 | Levels 2.0-4.5 |     | 25        | 126      | 5 per seat        | 10        | 12       | 1 per seat         | Attendance and Punctuality | Interview including writing and problem-solving exercise          |                                                            |      |      | 
| 01M450 | East Side Community                                      | Rigorous curriculum in all academic areas; students are challenged to apply what they have learned in creative ways to complete engaging projects. Outstanding art, photography, dance, choir, and music production classes.                                                                                                                       | M58A | Humanities & Interdisciplinary | Screened           | Scores 75-100 | Scores 75-100 | Scores 75-100 | Scores 75-100 |                |                |     | 90        | 1284     | 14 per seat       | 10        | 74       | 7 per seat         | Attendance and Punctuality | Contact school for more information regarding additional criteria |                                                            |      |      | 
| 01M509 | Marta Valle High School                                  | Includes course offerings in Digital Photography, Web Design; Visual, Performing and Culinary Arts, Video, Music Engineering.                                                                                                                                                                                                                      | M27A | Humanities & Interdisciplinary | Ed. Opt.           |               |               |               |               |                |                |     | 120       | 229      | 2 per seat        | 10        |          | New Program        |                            |                                                                   |                                                            |      |      | 
| 01M539 | Science, Technology and Math Institute                   | Technology woven throughout the curriculum and school infrastructure; use of technological tools to collaborate, conduct research and explore mathematical and scientific phenomena.                                                                                                                                                               | M29A | Science & Math                 | Screened           | Scores 85-100 | Scores 85-100 | Scores 85-100 | Scores 85-100 | Levels 3.0-4.5 | Levels 3.0-4.5 |     | 160       | 2995     | 19 per seat       | 10        | 162      | 16 per seat        | Attendance and Punctuality | On-site test: see website for dates and registration              |                                                            |      |      | 
| 01M696 | Early College                                            |                                                                                                                                                                                                                                                                                                                                                    | M51A | Humanities & Interdisciplinary | Screened           | Scores 85-100 | Scores 85-100 | Scores 85-100 | Scores 85-100 |                |                |     | 160       | 3060     | 19 per seat       | 10        | 152      | 15 per seat        | Attendance                 | Math/Writing Assessment                                           | Interview: Please contact the school for more information. |      |      | 
| 02M047 | English/American Sign Language Dual Language Environment | Students partake in a 4 year ASL program graduating with a proficiency in the language.                                                                                                                                                                                                                                                            | M54A | Humanities & Interdisciplinary | Screened           | Scores 75-100 | Scores 75-100 | Scores 75-100 | Scores 75-100 | Review         | Review         |     | 69        | 225      | 3 per seat        | 8         | 6        | 1 per seat         | Attendance and Punctuality | Interview                                                         |                                                            |      |      | 
| 02M135 | The Urban Assembly School for Emergency Management       |                                                                                                                                                                                                                                                                                                                                                    | M28A | Law & Government               | Limited Unscreened |               |               |               |               |                |                |     | 108       | 278      | 3 per seat        |           |          |                    |                            |                                                                   |                                                            |      |      | 
```