# School Progress Reports - All Schools - 2011 Multiyear Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-reports-all-schools-2011-multiyear-summary-a5a7f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rwa3-b3wr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rwa3-b3wr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rwa3-b3wr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rwa3-b3wr |
| Name | School Progress Reports - All Schools - 2011 Multiyear Summary |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T20:38:58Z |
| Publication Date | 2011-10-11T17:51:45Z |

## Description

2006-07 to 2009-10 Progress Report results summary for all schools Summary Progress Report grades for school years 2006-2007 through 2009-2011.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                          | Data Type | Render Type |
| ======== | =========== | ======================= | ============================= | ========= | =========== |
| No       |             | bn                      | BN                            | text      | text        |
| Yes      | series tag  | school_name             | SCHOOL NAME                   | text      | text        |
| Yes      | series tag  | progress_report_type    | PROGRESS REPORT TYPE          | text      | text        |
| Yes      | series tag  | progress_report_grade_1 | 2009-10 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | progress_report_grade_2 | 2008-09 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | progress_report_grade_3 | 2007-08 PROGRESS REPORT GRADE | text      | text        |
| Yes      | series tag  | progress_report_grade_4 | 2006-07 PROGRESS REPORT GRADE | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = bn
```

## Data Commands

```ls
series e:rwa3-b3wr d:2011-01-01T00:00:00.000Z t:progress_report_grade_4=B t:school_name="P.S. 001 The Bergen" t:progress_report_grade_3=B t:progress_report_grade_2=A t:progress_report_grade_1=C t:progress_report_type=EMS m:row_number.rwa3-b3wr=1

series e:rwa3-b3wr d:2011-01-01T00:00:00.000Z t:progress_report_grade_4=B t:school_name="M.S. 002" t:progress_report_grade_3=A t:progress_report_grade_2=A t:progress_report_grade_1=B t:progress_report_type=EMS m:row_number.rwa3-b3wr=2

series e:rwa3-b3wr d:2011-01-01T00:00:00.000Z t:progress_report_grade_4=C t:school_name="P.S. 003 The Bedford Village" t:progress_report_grade_3=A t:progress_report_grade_2=A t:progress_report_grade_1=C t:progress_report_type=EMS m:row_number.rwa3-b3wr=3
```

## Meta Commands

```ls
metric m:row_number.rwa3-b3wr p:long l:"Row Number"

entity e:rwa3-b3wr l:"School Progress Reports - All Schools - 2011 Multiyear Summary" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rwa3-b3wr

property e:rwa3-b3wr t:meta.view v:id=rwa3-b3wr v:category=Education v:averageRating=0 v:name="School Progress Reports - All Schools - 2011 Multiyear Summary" v:attribution="Department of Education (DOE)"

property e:rwa3-b3wr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rwa3-b3wr t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| bn   | school_name                                        | progress_report_type | progress_report_grade_1 | progress_report_grade_2 | progress_report_grade_3 | progress_report_grade_4 | 
| ==== | ================================================== | ==================== | ======================= | ======================= | ======================= | ======================= | 
| K001 | P.S. 001 The Bergen                                | EMS                  | C                       | A                       | B                       | B                       | 
| K002 | M.S. 002                                           | EMS                  | B                       | A                       | A                       | B                       | 
| K003 | P.S. 003 The Bedford Village                       | EMS                  | C                       | A                       | A                       | C                       | 
| K005 | P.S. 005 Dr. Ronald Mcnair                         | EMS                  | B                       | A                       | A                       | F                       | 
| K006 | P.S. 006                                           | EMS                  | B                       | A                       | A                       | B                       | 
| K007 | P.S. 007 Abraham Lincoln                           | EMS                  | B                       | A                       | B                       | D                       | 
| K008 | P.S. 008 Robert Fulton                             | EMS                  | C                       | A                       | F                       | C                       | 
| K009 | P.S. 009 Teunis G. Bergen                          | EMS                  | C                       | A                       | C                       | B                       | 
| K010 | Magnet School of Math, Science and Design Technolo | EMS                  | A                       | A                       | A                       | C                       | 
| K011 | P.S. 011 Purvis J. Behan                           | EMS                  | B                       | A                       | B                       | C                       | 
```