# DOE High School Performance- Directory 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doe-high-school-performance-directory-2016) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qvir-knu3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qvir-knu3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qvir-knu3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qvir-knu3 |
| Name | DOE High School Performance- Directory 2016 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe, high school, performance, graduation, college |
| Created | 2015-07-23T15:48:13Z |
| Publication Date | 2015-07-23T15:50:19Z |

## Description

Performance of NYC High Schools

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | dbn                           | dbn                           | text      | text        |
| Yes      | numeric metric | ontrack_year1_2013            | ontrack_year1_2013            | percent   | percent     |
| Yes      | numeric metric | graduation_rate_2013          | graduation_rate_2013          | percent   | percent     |
| Yes      | numeric metric | college_career_rate_2013      | college_career_rate_2013      | percent   | percent     |
| Yes      | numeric metric | ontrack_year1_2014            | ontrack_year1_2014            | percent   | percent     |
| Yes      | numeric metric | graduation_rate_2014          | graduation_rate_2014          | percent   | percent     |
| Yes      | numeric metric | college_career_rate_2014      | college_career_rate_2014      | percent   | percent     |
| Yes      | numeric metric | ontrack_year1_boro            | ontrack_year1_boro            | percent   | percent     |
| Yes      | numeric metric | graduation_rate_boro          | graduation_rate_boro          | percent   | percent     |
| Yes      | numeric metric | college_career_rate_boro      | college_career_rate_boro      | percent   | percent     |
| Yes      | numeric metric | pct_stu_enough_variety_2014   | pct_stu_enough_variety_2014   | percent   | percent     |
| Yes      | numeric metric | pct_stu_safe_2014             | pct_stu_safe_2014             | percent   | percent     |
| Yes      | series tag     | quality_review_year           | quality_review_year           | text      | text        |
| Yes      | series tag     | qr_curriculum                 | qr_curriculum                 | text      | text        |
| Yes      | series tag     | qr_instruction                | qr_instruction                | text      | text        |
| Yes      | series tag     | qr_assessing_student_learning | qr_assessing_student_learning | text      | text        |
| Yes      | series tag     | qr_high_expectations          | qr_high_expectations          | text      | text        |
| Yes      | series tag     | qr_teacher_collaboration      | qr_teacher_collaboration      | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qvir-knu3 d:2016-01-01T00:00:00.000Z t:qr_instruction=D t:dbn=01M292 t:qr_teacher_collaboration=P t:qr_assessing_student_learning=P t:quality_review_year=2013-2014 t:qr_high_expectations=P t:qr_curriculum=P m:graduation_rate_boro=70 m:college_career_rate_boro=53 m:college_career_rate_2014=41 m:college_career_rate_2013=32 m:pct_stu_enough_variety_2014=77 m:graduation_rate_2014=43 m:graduation_rate_2013=58 m:ontrack_year1_2014=63 m:ontrack_year1_2013=62 m:ontrack_year1_boro=85 m:pct_stu_safe_2014=76

series e:qvir-knu3 d:2016-01-01T00:00:00.000Z t:qr_instruction=P t:dbn=01M448 t:qr_teacher_collaboration=P t:qr_assessing_student_learning=P t:quality_review_year=2012-2013 t:qr_high_expectations=P t:qr_curriculum=P m:graduation_rate_boro=70 m:college_career_rate_boro=53 m:college_career_rate_2014=52 m:college_career_rate_2013=55 m:pct_stu_enough_variety_2014=75 m:graduation_rate_2014=80 m:graduation_rate_2013=78 m:ontrack_year1_2014=90 m:ontrack_year1_2013=83 m:ontrack_year1_boro=85 m:pct_stu_safe_2014=90

series e:qvir-knu3 d:2016-01-01T00:00:00.000Z t:dbn=01M450 m:graduation_rate_boro=70 m:college_career_rate_boro=53 m:college_career_rate_2014=69 m:college_career_rate_2013=58 m:pct_stu_enough_variety_2014=89 m:graduation_rate_2014=82 m:graduation_rate_2013=76 m:ontrack_year1_2014=88 m:ontrack_year1_2013=92 m:ontrack_year1_boro=85 m:pct_stu_safe_2014=92
```

## Meta Commands

```ls
metric m:ontrack_year1_2013 p:integer l:ontrack_year1_2013 t:dataTypeName=percent

metric m:graduation_rate_2013 p:integer l:graduation_rate_2013 t:dataTypeName=percent

metric m:college_career_rate_2013 p:integer l:college_career_rate_2013 t:dataTypeName=percent

metric m:ontrack_year1_2014 p:integer l:ontrack_year1_2014 t:dataTypeName=percent

metric m:graduation_rate_2014 p:integer l:graduation_rate_2014 t:dataTypeName=percent

metric m:college_career_rate_2014 p:integer l:college_career_rate_2014 t:dataTypeName=percent

metric m:ontrack_year1_boro p:integer l:ontrack_year1_boro t:dataTypeName=percent

metric m:graduation_rate_boro p:integer l:graduation_rate_boro t:dataTypeName=percent

metric m:college_career_rate_boro p:integer l:college_career_rate_boro t:dataTypeName=percent

metric m:pct_stu_enough_variety_2014 p:integer l:pct_stu_enough_variety_2014 t:dataTypeName=percent

metric m:pct_stu_safe_2014 p:integer l:pct_stu_safe_2014 t:dataTypeName=percent

entity e:qvir-knu3 l:"DOE High School Performance- Directory 2016" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/qvir-knu3

property e:qvir-knu3 t:meta.view v:id=qvir-knu3 v:category=Education v:averageRating=0 v:name="DOE High School Performance- Directory 2016" v:attribution="Department of Education (DOE)"

property e:qvir-knu3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qvir-knu3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | ontrack_year1_2013 | graduation_rate_2013 | college_career_rate_2013 | ontrack_year1_2014 | graduation_rate_2014 | college_career_rate_2014 | ontrack_year1_boro | graduation_rate_boro | college_career_rate_boro | pct_stu_enough_variety_2014 | pct_stu_safe_2014 | quality_review_year | qr_curriculum | qr_instruction | qr_assessing_student_learning | qr_high_expectations | qr_teacher_collaboration | 
| ====== | ================== | ==================== | ======================== | ================== | ==================== | ======================== | ================== | ==================== | ======================== | =========================== | ================= | =================== | ============= | ============== | ============================= | ==================== | ======================== | 
| 01M292 | 62                 | 58                   | 32                       | 63                 | 43                   | 41                       | 85                 | 70                   | 53                       | 77                          | 76                | 2013-2014           | P             | D              | P                             | P                    | P                        | 
| 01M448 | 83                 | 78                   | 55                       | 90                 | 80                   | 52                       | 85                 | 70                   | 53                       | 75                          | 90                | 2012-2013           | P             | P              | P                             | P                    | P                        | 
| 01M450 | 92                 | 76                   | 58                       | 88                 | 82                   | 69                       | 85                 | 70                   | 53                       | 89                          | 92                |                     |               |                |                               |                      |                          | 
| 01M509 | 59                 | 36                   | 38                       | 59                 | 48                   | 26                       | 85                 | 70                   | 53                       | 28                          | 71                | 2013-2014           | D             | D              | D                             | D                    | P                        | 
| 01M539 | 99                 | 98                   | 84                       | 97                 | 95                   | 89                       | 85                 | 70                   | 53                       | 75                          | 87                | 2010-2011           | WD            | P              | P                             | WD                   | D                        | 
| 01M696 | 96                 | 98                   | 94                       | 98                 | 100                  | 93                       | 85                 | 70                   | 53                       | 90                          | 98                | 2013-2014           | WD            | WD             | P                             | WD                   | WD                       | 
| 02M047 | 98                 | 71                   | 42                       | 90                 | 69                   | 62                       | 85                 | 70                   | 53                       | 50                          | 90                | 2013-2014           | P             | P              | P                             | P                    | P                        | 
| 02M135 |                    |                      |                          | 84                 |                      |                          | 85                 | 70                   | 53                       | 78                          | 81                |                     |               |                |                               |                      |                          | 
| 02M139 |                    |                      |                          | 89                 |                      |                          | 85                 | 70                   | 53                       | 81                          | 84                |                     |               |                |                               |                      |                          | 
| 02M260 |                    |                      |                          |                    |                      |                          | 85                 | 70                   | 53                       | 85                          | 88                | 2011-2012           | P             | P              | P                             | P                    | P                        | 
```