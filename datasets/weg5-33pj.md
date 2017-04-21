# School Progress Report 2006-2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-2006-2007-b5bcb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/weg5-33pj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/weg5-33pj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/weg5-33pj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | weg5-33pj |
| Name | School Progress Report 2006-2007 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T04:19:50Z |
| Publication Date | 2013-02-21T04:20:04Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F. ?These reports focus on a school's learning environment, student performance, and student progress.? They were designed to help parents, teachers, principals, and others understand how well schools are doing?and compare them to other, similar schools.

## Columns

```ls
| Included | Schema Type | Field Name                          | Name                                | Data Type | Render Type |
| ======== | =========== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag  | dbn                                 | DBN                                 | text      | text        |
| Yes      | series tag  | district                            | DISTRICT                            | text      | text        |
| Yes      | series tag  | school                              | SCHOOL                              | text      | text        |
| Yes      | series tag  | school_support_organization_network | SCHOOL SUPPORT ORGANIZATION/NETWORK | text      | text        |
| Yes      | series tag  | progress_report_type                | PROGRESS REPORT TYPE                | text      | text        |
| Yes      | series tag  | school_level                        | SCHOOL LEVEL*                       | text      | text        |
| Yes      | series tag  | peer_index                          | PEER INDEX*                         | text      | text        |
| Yes      | series tag  | grade                               | GRADE                               | text      | text        |
| Yes      | series tag  | overall_score                       | OVERALL SCORE                       | text      | text        |
| Yes      | series tag  | environment_category_score          | ENVIRONMENT CATEGORY SCORE          | text      | text        |
| Yes      | series tag  | performance_category_score          | PERFORMANCE CATEGORY SCORE          | text      | text        |
| Yes      | series tag  | progress_category_score             | PROGRESS CATEGORY SCORE             | text      | text        |
| Yes      | series tag  | additional_credit                   | ADDITIONAL CREDIT                   | text      | text        |
| Yes      | series tag  | quality_review_score                | QUALITY REVIEW SCORE                | text      | text        |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:weg5-33pj d:2006-01-01T00:00:00.000Z t:progress_report_type=ESMS t:quality_review_score=Undeveloped t:additional_credit=3 t:school="PS 015 ROBERTO CLEMENTE" t:performance_category_score=0.231 t:dbn=01M015 t:school_support_organization_network=ICI15 t:grade=B t:progress_category_score=0.694 t:environment_category_score=0.278 t:peer_index=75.60 t:district=01 t:school_level="Elementary School" t:overall_score=52.31 m:row_number.weg5-33pj=1

series e:weg5-33pj d:2006-01-01T00:00:00.000Z t:progress_report_type=ESMS t:quality_review_score=Proficient t:additional_credit=1.5 t:school="PS 019 ASHER LEVY" t:performance_category_score=0.466 t:dbn=01M019 t:school_support_organization_network=ESO1 t:grade=B t:progress_category_score=0.511 t:environment_category_score=0.51 t:peer_index=59.25 t:district=01 t:school_level="Elementary School" t:overall_score=51.24 m:row_number.weg5-33pj=2

series e:weg5-33pj d:2006-01-01T00:00:00.000Z t:progress_report_type=ESMS t:quality_review_score=Well-Developed t:additional_credit=1.5 t:school="PS 020 ANNA SILVER" t:performance_category_score=0.682 t:dbn=01M020 t:school_support_organization_network=ICI15 t:grade=B t:progress_category_score=0.402 t:environment_category_score=0.568 t:peer_index=69.78 t:district=01 t:school_level="Elementary School" t:overall_score=52.59 m:row_number.weg5-33pj=3
```

## Meta Commands

```ls
metric m:row_number.weg5-33pj p:long l:"Row Number"

entity e:weg5-33pj l:"School Progress Report 2006-2007" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/weg5-33pj

property e:weg5-33pj t:meta.view v:id=weg5-33pj v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report 2006-2007" v:attribution="Department of Education (DOE)"

property e:weg5-33pj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:weg5-33pj t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| dbn    | district | school                      | school_support_organization_network | progress_report_type | school_level      | peer_index | grade | overall_score | environment_category_score | performance_category_score | progress_category_score | additional_credit | quality_review_score | 
| ====== | ======== | =========================== | =================================== | ==================== | ================= | ========== | ===== | ============= | ========================== | ========================== | ======================= | ================= | ==================== | 
| 01M015 | 01       | PS 015 ROBERTO CLEMENTE     | ICI15                               | ESMS                 | Elementary School | 75.60      | B     | 52.31         | 0.278                      | 0.231                      | 0.694                   | 3                 | Undeveloped          | 
| 01M019 | 01       | PS 019 ASHER LEVY           | ESO1                                | ESMS                 | Elementary School | 59.25      | B     | 51.24         | 0.51                       | 0.466                      | 0.511                   | 1.5               | Proficient           | 
| 01M020 | 01       | PS 020 ANNA SILVER          | ICI15                               | ESMS                 | Elementary School | 69.78      | B     | 52.59         | 0.568                      | 0.682                      | 0.402                   | 1.5               | Well-Developed       | 
| 01M034 | 01       | PS 034 FRANKLIN D ROOSEVELT | ICI15                               | ESMS                 | K-8 School        | 71.90      | C     | 47.02         | 0.409                      | 0.366                      | 0.53                    | 0.75              | Proficient           | 
| 01M063 | 01       | PS 063 WILLIAM MCKINLEY     | ICI15                               | ESMS                 | Elementary School | 62.17      | C     | 44.66         | 0.199                      | 0.511                      | 0.479                   | 0                 | Proficient           | 
| 01M064 | 01       | PS 064 ROBERT SIMON         | ESO1                                | ESMS                 | Elementary School | 71.90      | C     | 48.43         | 0.561                      | 0.586                      | 0.408                   | 0                 | Well-Developed       | 
| 01M110 | 01       | PS 110 FLORENCE NIGHTINGALE | ESO1                                | ESMS                 | Elementary School | 54.96      | B     | 51.17         | 0.818                      | 0.644                      | 0.315                   | 2.25              | Proficient           | 
| 01M134 | 01       | PS 134 HENRIETTA SZOLD      | ICI15                               | ESMS                 | Elementary School | 66.49      | B     | 54.21         | 0.338                      | 0.55                       | 0.566                   | 1.5               | Well-Developed       | 
| 01M137 | 01       | PS 137 JOHN L BERNSTEIN     | ICI5                                | ESMS                 | Elementary School | 70.85      | B     | 59.35         | 0.398                      | 0.361                      | 0.76                    | 0.75              | Undeveloped          | 
| 01M140 | 01       | PS 140 NATHAN STRAUS        | ESO19                               | ESMS                 | K-8 School        | 73.18      | B     | 56.14         | 0.588                      | 0.441                      | 0.593                   | 1.5               | Proficient           | 
```