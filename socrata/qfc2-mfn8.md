# Maryland State Department of Education Performance Dashboard Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-state-department-of-education-performance-dashboard-measures) |
| Metadata | [Link](https://data.maryland.gov/api/views/qfc2-mfn8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/qfc2-mfn8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/qfc2-mfn8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | qfc2-mfn8 |
| Name | Maryland State Department of Education Performance Dashboard Measures |
| Category | Education |
| Tags | kindergarten readiness, high school graduation rates, rigorous coursework, education, maryland |
| Created | 2016-06-30T20:37:28Z |
| Publication Date | 2017-02-02T18:11:34Z |

## Description

Maryland State Department of Education Performance Dashboard Measures including measures of Kindergarten Readiness, High School Graduation Rates, and Completion of Rigorous Coursework from Academic Year 2011 to present.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                                                                                                                                | Name                                                                               | Data Type     | Render Type   |
| ======== | ============== | ========================================================================================================================================================================================= | ================================================================================== | ============= | ============= |
| Yes      | time           | date                                                                                                                                                                                      | Date                                                                               | calendar_date | calendar_date |
| No       |                | year                                                                                                                                                                                      | Academic Year                                                                      | text          | text          |
| No       |                | kra_report_date                                                                                                                                                                           | KRA Report Date                                                                    | calendar_date | calendar_date |
| Yes      | numeric metric | percentage_of_students_entering_kindergarten_demonstrating_full_readiness_on_the_kindergarten_readiness_assessment                                                                        | Percentage of Students Entering Kindergarten Demonstrating Full Readiness          | percent       | percent       |
| Yes      | numeric metric | four_year_high_school_graduation_rate                                                                                                                                                     | Four-Year Cohort High School Graduation Rate                                       | percent       | percent       |
| Yes      | numeric metric | percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam | Percentage of High School Graduates Who Successfully Completed Rigorous Coursework | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = kra_report_date,year
```

## Data Commands

```ls
series e:qfc2-mfn8 d:2012-07-31T00:00:00.000Z m:percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam=27.4 m:four_year_high_school_graduation_rate=83.57

series e:qfc2-mfn8 d:2013-07-31T00:00:00.000Z m:percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam=28.7 m:four_year_high_school_graduation_rate=84.97

series e:qfc2-mfn8 d:2014-07-31T00:00:00.000Z m:percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam=29.7 m:four_year_high_school_graduation_rate=86.39
```

## Meta Commands

```ls
metric m:percentage_of_students_entering_kindergarten_demonstrating_full_readiness_on_the_kindergarten_readiness_assessment p:float l:"Percentage of Students Entering Kindergarten Demonstrating Full Readiness" d:"Based on on the Kindergarten Readiness Assessment (KRA)" t:dataTypeName=percent

metric m:four_year_high_school_graduation_rate p:float l:"Four-Year Cohort High School Graduation Rate" d:"based on adjusted cohort" t:dataTypeName=percent

metric m:percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam p:float l:"Percentage of High School Graduates Who Successfully Completed Rigorous Coursework" d:"Scoring 3 or better on at least one Advanced Placement exam, 4 or better on at least one International Baccalaureate exam" t:dataTypeName=percent

entity e:qfc2-mfn8 l:"Maryland State Department of Education Performance Dashboard Measures" t:url=https://data.maryland.gov/api/views/qfc2-mfn8

property e:qfc2-mfn8 t:meta.view v:id=qfc2-mfn8 v:category=Education v:averageRating=0 v:name="Maryland State Department of Education Performance Dashboard Measures"

property e:qfc2-mfn8 t:meta.view.owner v:id=s8mt-by84 v:screenName="Debbie Lichter" v:displayName="Debbie Lichter"

property e:qfc2-mfn8 t:meta.view.tableauthor v:id=s8mt-by84 v:screenName="Debbie Lichter" v:roleName=editor v:displayName="Debbie Lichter"
```

## Top Records

```ls
| date                | year    | kra_report_date     | percentage_of_students_entering_kindergarten_demonstrating_full_readiness_on_the_kindergarten_readiness_assessment | four_year_high_school_graduation_rate | percentage_of_high_school_graduates_who_took_rigorous_coursework_scoring_3_or_better_on_at_least_one_advanced_placement_exam_4_or_better_on_at_least_one_international_baccalaureate_exam | 
| =================== | ======= | =================== | ================================================================================================================== | ===================================== | ========================================================================================================================================================================================= | 
| 2012-07-31T00:00:00 | 2011-12 | 2011-11-01T00:00:00 |                                                                                                                    | 83.57                                 | 27.40                                                                                                                                                                                     | 
| 2013-07-31T00:00:00 | 2012-13 | 2012-11-01T00:00:00 |                                                                                                                    | 84.97                                 | 28.70                                                                                                                                                                                     | 
| 2014-07-31T00:00:00 | 2013-14 | 2013-11-01T00:00:00 |                                                                                                                    | 86.39                                 | 29.70                                                                                                                                                                                     | 
| 2015-07-31T00:00:00 | 2014-15 | 2014-11-01T00:00:00 | 46.8                                                                                                               | 86.98                                 | 30.00                                                                                                                                                                                     | 
| 2011-07-31T00:00:00 | 2010-11 | 2010-11-01T00:00:00 |                                                                                                                    | 82.82                                 | 25.90                                                                                                                                                                                     | 
| 2016-07-31T00:00:00 | 2015-16 | 2015-11-01T00:00:00 | 45.2                                                                                                               | 87.61                                 |                                                                                                                                                                                           | 
| 2017-07-31T00:00:00 | 2016-17 | 2016-11-01T00:00:00 | 43.1                                                                                                               |                                       |                                                                                                                                                                                           | 
```