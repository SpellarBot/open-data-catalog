# School Progress Report Multi-year 2007-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-report-multi-year-2007-2011-13f40) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5fsg-d8c9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5fsg-d8c9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5fsg-d8c9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5fsg-d8c9 |
| Name | School Progress Report Multi-year 2007-2011 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school progress report, report card, lifelong learning |
| Created | 2013-02-21T21:18:53Z |
| Publication Date | 2013-02-21T21:41:49Z |

## Description

Progress Reports grade each school with an A, B, C, D, or F. ?These reports focus on a school's learning environment, student performance, and student progress.? They were designed to help parents, teachers, principals, and others understand how well schools are doing?and compare them to other, similar schools.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       |             | bn                            | BN                            | text      | text        |
| Yes      | series tag  | school_name                   | SCHOOL NAME                   | text      | text        |
| Yes      | series tag  | progress_report_type          | PROGRESS REPORT TYPE          | text      | text        |
| Yes      | series tag  | 2010_11_progress_report_grade | 2010-11 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | 2009_10_progress_report_grade | 2009-10 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | 2008_09_progress_report_grade | 2008-09 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | 2007_08_progress_report_grade | 2007-08 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | 2006_07_progress_report_grade | 2006-07 PROGRESS REPORT GRADE | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = bn
```

## Data Commands

```ls
series e:5fsg-d8c9 d:2007-01-01T00:00:00.000Z t:school_name="P.S. 36" t:2007_08_progress_report_grade=None t:2008_09_progress_report_grade=None t:progress_report_type=D75 t:2006_07_progress_report_grade=None t:2010_11_progress_report_grade=A t:2009_10_progress_report_grade=C m:row_number.5fsg-d8c9=1

series e:5fsg-d8c9 d:2007-01-01T00:00:00.000Z t:school_name="P.S. K053" t:2007_08_progress_report_grade=None t:2008_09_progress_report_grade=None t:progress_report_type=D75 t:2006_07_progress_report_grade=None t:2010_11_progress_report_grade=A t:2009_10_progress_report_grade=B m:row_number.5fsg-d8c9=2

series e:5fsg-d8c9 d:2007-01-01T00:00:00.000Z t:school_name="P.S. K140" t:2007_08_progress_report_grade=None t:2008_09_progress_report_grade=None t:progress_report_type=D75 t:2006_07_progress_report_grade=None t:2010_11_progress_report_grade=F t:2009_10_progress_report_grade=D m:row_number.5fsg-d8c9=3
```

## Meta Commands

```ls
metric m:row_number.5fsg-d8c9 p:long l:"Row Number"

entity e:5fsg-d8c9 l:"School Progress Report Multi-year 2007-2011" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/5fsg-d8c9

property e:5fsg-d8c9 t:meta.view v:id=5fsg-d8c9 v:category=Education v:attributionLink=http://schools.nyc.gov/Accountability/tools/report/default.htm v:averageRating=0 v:name="School Progress Report Multi-year 2007-2011" v:attribution="Department of Education (DOE)"

property e:5fsg-d8c9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5fsg-d8c9 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| bn   | school_name                     | progress_report_type | 2010_11_progress_report_grade | 2009_10_progress_report_grade | 2008_09_progress_report_grade | 2007_08_progress_report_grade | 2006_07_progress_report_grade | 
| ==== | =============================== | ==================== | ============================= | ============================= | ============================= | ============================= | ============================= | 
| K036 | P.S. 36                         | D75                  | A                             | C                             | None                          | None                          | None                          | 
| K053 | P.S. K053                       | D75                  | A                             | B                             | None                          | None                          | None                          | 
| K140 | P.S. K140                       | D75                  | F                             | D                             | None                          | None                          | None                          | 
| K141 | P.S. K141                       | D75                  | C                             | B                             | None                          | None                          | None                          | 
| K231 | P.S. K231                       | D75                  | B                             | C                             | None                          | None                          | None                          | 
| K368 | P.S. 368                        | D75                  | B                             | D                             | None                          | None                          | None                          | 
| K369 | P.S. K369 - Coy L. Cox School   | D75                  | B                             | B                             | None                          | None                          | None                          | 
| K372 | P.S. 372 -The Children's School | D75                  | A                             | A                             | None                          | None                          | None                          | 
| K771 | P.S. K771                       | D75                  | B                             | A                             | None                          | None                          | None                          | 
| M094 | P.S. M094                       | D75                  | D                             | C                             | None                          | None                          | None                          | 
```