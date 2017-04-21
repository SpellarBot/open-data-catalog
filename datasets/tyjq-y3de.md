# Regent University Fall Enrollment By Student Classification And Resident Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regent-university-fall-enrollment-by-student-classification-and-resident-status) |
| Metadata | [Link](https://data.iowa.gov/api/views/tyjq-y3de) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tyjq-y3de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tyjq-y3de/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tyjq-y3de |
| Name | Regent University Fall Enrollment By Student Classification And Resident Status |
| Attribution | Iowa Board of Regents |
| Category | Education |
| Tags | student enrollment, fall semester, universities |
| Created | 2014-12-23T18:17:30Z |
| Publication Date | 2016-12-22T19:05:29Z |

## Description

This dataset provides student headcount enrollment at the University of Iowa, Iowa State University, and the University of Northern Iowa for Fall semesters starting in 2012. The data includes resident and non-resident enrollment for undergraduate, graduate, professional, and post-doctoral student classifications.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | number      |
| Yes      | series tag     | university_name        | University Name        | text      | text        |
| Yes      | series tag     | student_classification | Student Classification | text      | text        |
| Yes      | series tag     | resident_status        | Resident Status        | text      | text        |
| Yes      | numeric metric | headcount              | Headcount              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tyjq-y3de d:2012-01-01T00:00:00.000Z t:university_name="Iowa State University" t:student_classification=Graduate t:resident_status=Non-Resident m:headcount=2997

series e:tyjq-y3de d:2012-01-01T00:00:00.000Z t:university_name="Iowa State University" t:student_classification=Graduate t:resident_status=Resident m:headcount=1610

series e:tyjq-y3de d:2012-01-01T00:00:00.000Z t:university_name="Iowa State University" t:student_classification=Post-Doctoral t:resident_status=Unknown m:headcount=292
```

## Meta Commands

```ls
metric m:headcount p:integer l:Headcount d:"Aggregate headcount by year, university, student classification and resident status." t:dataTypeName=number

entity e:tyjq-y3de l:"Regent University Fall Enrollment By Student Classification And Resident Status" t:attribution="Iowa Board of Regents" t:url=https://data.iowa.gov/api/views/tyjq-y3de

property e:tyjq-y3de t:meta.view v:id=tyjq-y3de v:category=Education v:averageRating=0 v:name="Regent University Fall Enrollment By Student Classification And Resident Status" v:attribution="Iowa Board of Regents"

property e:tyjq-y3de t:meta.view.license v:name="Public Domain"

property e:tyjq-y3de t:meta.view.owner v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:displayName="Iowa Board of Regents"

property e:tyjq-y3de t:meta.view.tableauthor v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:roleName=editor v:displayName="Iowa Board of Regents"
```

## Top Records

```ls
| year | university_name       | student_classification | resident_status | headcount | 
| ==== | ===================== | ====================== | =============== | ========= | 
| 2012 | Iowa State University | Graduate               | Non-Resident    | 2997      | 
| 2012 | Iowa State University | Graduate               | Resident        | 1610      | 
| 2012 | Iowa State University | Post-Doctoral          | Unknown         | 292       | 
| 2012 | Iowa State University | Professional           | Non-Resident    | 326       | 
| 2012 | Iowa State University | Professional           | Resident        | 262       | 
| 2012 | Iowa State University | Undergraduate          | Non-Resident    | 8503      | 
| 2012 | Iowa State University | Undergraduate          | Resident        | 17050     | 
| 2012 | University of Iowa    | Graduate               | Non-Resident    | 3063      | 
| 2012 | University of Iowa    | Graduate               | Resident        | 2041      | 
| 2012 | University of Iowa    | Post-Doctoral          | Non-Resident    | 304       | 
```