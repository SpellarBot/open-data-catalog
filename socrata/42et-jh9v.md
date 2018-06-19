# DOE High School Performance-Directory 2013-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doe-high-school-performance-directory-2013-2014-669b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/42et-jh9v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/42et-jh9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/42et-jh9v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 42et-jh9v |
| Name | DOE High School Performance-Directory 2013-2014 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe high school performance, doe, education, students |
| Created | 2014-09-03T19:20:31Z |
| Publication Date | 2014-09-03T19:24:11Z |

## Description

Performance of NYC High Schools

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | dbn                    | DBN                    | text      | text        |
| Yes      | time           | quality_review_year    | Quality_Review_Year    | number    | number      |
| Yes      | series tag     | quality_review_score   | Quality_Review_Score   | text      | text        |
| Yes      | series tag     | progress_rpt_10_11     | Progress_Rpt_10-11     | text      | text        |
| Yes      | series tag     | student_progress_10_11 | Student_Progress_10-11 | text      | text        |
| Yes      | series tag     | student_perf_10_11     | Student_Perf_10-11     | text      | text        |
| Yes      | series tag     | envi_10_11             | Envi_10-11             | text      | text        |
| Yes      | series tag     | college_ready_10_11    | College_Ready_10-11    | text      | text        |
| Yes      | numeric metric | graduation_2010_11     | graduation 2010-11     | number    | text        |
| Yes      | numeric metric | college_enroll_2010_11 | college enroll 2010-11 | number    | text        |
| Yes      | series tag     | progress_rpt_11_12     | Progress_Rpt_11-12     | text      | text        |
| Yes      | series tag     | student_progress_11_12 | Student_Progress_11-12 | text      | text        |
| Yes      | series tag     | student_perf_11_12     | Student_Perf_11-12     | text      | text        |
| Yes      | series tag     | envi_11_12             | Envi_11-12             | text      | text        |
| Yes      | series tag     | college_ready_11_12    | College_Ready_11-12    | text      | text        |
| Yes      | numeric metric | graduation_2011_12     | graduation 2011-12     | number    | text        |
| Yes      | numeric metric | college_enroll_2011_12 | college enroll 2011-12 | number    | text        |
```

## Time Field

```ls
Value = quality_review_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:42et-jh9v d:2011-01-01T00:00:00.000Z t:envi_11_12=C t:progress_rpt_10_11=C t:student_progress_11_12=C t:dbn=01M292 t:college_ready_10_11=N/A t:quality_review_score=Developing t:progress_rpt_11_12=C t:student_perf_10_11=C t:student_progress_10_11=C t:college_ready_11_12=D t:student_perf_11_12=F t:envi_10_11=D m:graduation_2011_12=50.70000076293945 m:college_enroll_2010_11=51.900001525878906 m:graduation_2010_11=56.29999923706055 m:college_enroll_2011_12=40

series e:42et-jh9v d:2011-01-01T00:00:00.000Z t:envi_11_12=B t:progress_rpt_10_11=C t:student_progress_11_12=B t:dbn=01M448 t:college_ready_10_11=N/A t:quality_review_score=Developing t:progress_rpt_11_12=B t:student_perf_10_11=C t:student_progress_10_11=B t:college_ready_11_12=A t:student_perf_11_12=B t:envi_10_11=D m:graduation_2011_12=74.4000015258789 m:college_enroll_2010_11=36.29999923706055 m:graduation_2010_11=70.69999694824219 m:college_enroll_2011_12=67.30000305175781

series e:42et-jh9v d:2008-01-01T00:00:00.000Z t:envi_11_12=A t:progress_rpt_10_11=A t:student_progress_11_12=B t:dbn=01M450 t:college_ready_10_11=N/A t:quality_review_score="Well Developed" t:progress_rpt_11_12=A t:student_perf_10_11=A t:student_progress_10_11=B t:college_ready_11_12=A t:student_perf_11_12=A t:envi_10_11=A m:graduation_2011_12=72.69999694824219 m:college_enroll_2010_11=69.19999694824219 m:graduation_2010_11=71.5999984741211 m:college_enroll_2011_12=55.70000076293945
```

## Meta Commands

```ls
entity e:42et-jh9v l:"DOE High School Performance-Directory 2013-2014" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/42et-jh9v

property e:42et-jh9v t:meta.view v:id=42et-jh9v v:category=Education v:averageRating=0 v:name="DOE High School Performance-Directory 2013-2014" v:attribution="Department of Education (DOE)"

property e:42et-jh9v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:42et-jh9v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | quality_review_year | quality_review_score | progress_rpt_10_11 | student_progress_10_11 | student_perf_10_11 | envi_10_11 | college_ready_10_11 | graduation_2010_11 | college_enroll_2010_11 | progress_rpt_11_12 | student_progress_11_12 | student_perf_11_12 | envi_11_12 | college_ready_11_12 | graduation_2011_12 | college_enroll_2011_12 | 
| ====== | =================== | ==================== | ================== | ====================== | ================== | ========== | =================== | ================== | ====================== | ================== | ====================== | ================== | ========== | =================== | ================== | ====================== | 
| 01M292 | 2011                | Developing           | C                  | C                      | C                  | D          | N/A                 | 56.30%             | 51.90%                 | C                  | C                      | F                  | C          | D                   | 50.70%             | 40.00%                 | 
| 01M448 | 2011                | Developing           | C                  | B                      | C                  | D          | N/A                 | 70.70%             | 36.30%                 | B                  | B                      | B                  | B          | A                   | 74.40%             | 67.30%                 | 
| 01M450 | 2008                | Well Developed       | A                  | B                      | A                  | A          | N/A                 | 71.60%             | 69.20%                 | A                  | B                      | A                  | A          | A                   | 72.70%             | 55.70%                 | 
| 01M509 | 2010                | Proficient           | C                  | C                      | B                  | D          | N/A                 | 56.40%             | 47.70%                 | C                  | F                      | B                  | F          | A                   | 59.50%             | 47.90%                 | 
| 01M539 | 2011                | Proficient           | A                  | A                      | A                  | C          | N/A                 | 95.30%             | 87.00%                 | A                  | A                      | A                  | C          | A                   | 97.50%             | 82.80%                 | 
| 01M696 | 2010                | Well Developed       | B                  | C                      | B                  | A          | N/A                 | 97.60%             | 95.70%                 | B                  | C                      | A                  | A          | A                   | 96.60%             | 96.80%                 | 
| 02M047 | 2010                | Proficient           | C                  | D                      | A                  | A          | N/A                 | 69.60%             | 47.10%                 | B                  | C                      | F                  | A          | C                   | 54.80%             | 30.40%                 | 
| 02M288 | 2008                | Proficient           | A                  | B                      | A                  | C          | N/A                 | 82.00%             | 62.70%                 | A                  | B                      | A                  | B          | B                   | 77.30%             | 59.60%                 | 
| 02M294 | 2008                | Well Developed       | B                  | B                      | A                  | A          | N/A                 | 67.50%             | 48.30%                 | B                  | B                      | A                  | A          | D                   | 77.40%             | 61.30%                 | 
| 02M296 | 2010                | Proficient           | A                  | A                      | A                  | A          | N/A                 | 79.30%             | 56.00%                 | A                  | B                      | A                  | B          | B                   | 78.40%             | 42.70%                 | 
```