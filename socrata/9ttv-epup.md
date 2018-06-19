# School Cohort Graduation Rates: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-cohort-graduation-rates-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/9ttv-epup) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9ttv-epup/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9ttv-epup/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9ttv-epup |
| Name | School Cohort Graduation Rates: 2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school, graduation |
| Created | 2014-06-25T15:28:39Z |
| Publication Date | 2014-06-25T15:30:43Z |

## Description

This dataset contains the 2013 four-year cohort graduation rates by school. 
The Connecticut State Department of Education (CSDE) introduced the four-year cohort graduation rate with the graduating class of 2009. This approach was created when Connecticut and 49 other states signed an agreement with the National Governors? Association to develop a uniform system for tracking students.  The four-year cohort graduation rate is calculated by tracking an individual cohort, or group of students, from their initial entrance into Grade 9 through to graduation. The four-year cohort graduation rate represents the percentage of students who earn a standard high school diploma within four years. The calculation uses individual student-level data from the state's Public School Information System (PSIS) that school districts submitted and superintendents certified.

Notes: 
Double plus symbol (??) denotes not applicable; 
Asterisk symbol (*) denotes fewer than six in a cohort is suppressed;
Out-placed students are counted only in district graduation calculation;
Row percentages may not add to 100 percent because of rounding;
District graduation rates may not be the same as the average of the graduation rates of the number schools in that district because of out-placed students.

Gov. Malloy: Graduation Rate Increases for Fourth Consecutive Year: http://www.governor.ct.gov/malloy/cwp/view.asp?A=4010&Q=545016
Cohort Graduation Rate Documentation:
http://www.sde.ct.gov/sde/lib/sde/PDF/EvalResearch/cohortgraddocumentation.pdf

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | districtname           | DistrictName           | text      | text        |
| Yes      | series tag     | schoolname             | SchoolName             | text      | text        |
| Yes      | series tag     | category               | Category               | text      | text        |
| Yes      | numeric metric | 4_year_graduation_rate | 4-Year Graduation Rate | number    | number      |
| Yes      | numeric metric | still_enrolled         | Still Enrolled         | number    | number      |
| Yes      | numeric metric | other                  | Other                  | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9ttv-epup d:2013-01-01T00:00:00.000Z t:category="All Students" t:schoolname="Ansonia High School" t:districtname="Ansonia School District" m:4_year_graduation_rate=76.1 m:other=12.9 m:still_enrolled=11

series e:9ttv-epup d:2013-01-01T00:00:00.000Z t:category=Hispanic t:schoolname="Ansonia High School" t:districtname="Ansonia School District" m:4_year_graduation_rate=65.3 m:other=18.4 m:still_enrolled=16.3

series e:9ttv-epup d:2013-01-01T00:00:00.000Z t:category=Non-Hispanic t:schoolname="Ansonia High School" t:districtname="Ansonia School District" m:4_year_graduation_rate=79.4 m:other=11.3 m:still_enrolled=9.4
```

## Meta Commands

```ls
metric m:4_year_graduation_rate p:float l:"4-Year Graduation Rate" t:dataTypeName=number

metric m:still_enrolled p:float l:"Still Enrolled" t:dataTypeName=number

metric m:other p:float l:Other t:dataTypeName=number

entity e:9ttv-epup l:"School Cohort Graduation Rates: 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/9ttv-epup

property e:9ttv-epup t:meta.view v:id=9ttv-epup v:category=Education v:averageRating=0 v:name="School Cohort Graduation Rates: 2013" v:attribution="State Department of Education"

property e:9ttv-epup t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:9ttv-epup t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| districtname            | schoolname          | category                     | 4_year_graduation_rate | still_enrolled | other | 
| ======================= | =================== | ============================ | ====================== | ============== | ===== | 
| Ansonia School District | Ansonia High School | All Students                 | 76.1                   | 11.0           | 12.9  | 
| Ansonia School District | Ansonia High School | Hispanic                     | 65.3                   | 16.3           | 18.4  | 
| Ansonia School District | Ansonia High School | Non-Hispanic                 | 79.4                   | 9.4            | 11.3  | 
| Ansonia School District | Ansonia High School | Asian                        |                        |                |       | 
| Ansonia School District | Ansonia High School | Black                        | 70.2                   | 6.4            | 23.4  | 
| Ansonia School District | Ansonia High School | Hawaiian or Pacific Islander |                        |                |       | 
| Ansonia School District | Ansonia High School | White                        | 82.6                   | 11.0           | 6.4   | 
| Ansonia School District | Ansonia High School | Male                         | 62.9                   | 20.0           | 17.1  | 
| Ansonia School District | Ansonia High School | Female                       | 89.4                   | 1.9            | 8.7   | 
| Ansonia School District | Ansonia High School | ELL                          | 61.5                   | 23.1           | 15.4  | 
```