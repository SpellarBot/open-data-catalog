# District Cohort Graduation Rates: 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/district-cohort-graduation-rates-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/sus6-q2ti) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/sus6-q2ti/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/sus6-q2ti/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | sus6-q2ti |
| Name | District Cohort Graduation Rates: 2012 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, district, graduation, ctkids |
| Created | 2014-07-24T20:39:12Z |
| Publication Date | 2014-07-24T20:46:05Z |

## Description

This dataset contains the 2012 four-year cohort graduation rates by district. The Connecticut State Department of Education (CSDE) introduced the four-year cohort graduation rate with the graduating class of 2009. This approach was created when Connecticut and 49 other states signed an agreement with the National Governors? Association to develop a uniform system for tracking students. The four-year cohort graduation rate is calculated by tracking an individual cohort, or group of students, from their initial entrance into Grade 9 through to graduation. The four-year cohort graduation rate represents the percentage of students who earn a standard high school diploma within four years. The calculation uses individual student-level data from the state's Public School Information System (PSIS) that school districts submitted and superintendents certified.
>> Double plus symbol (??) denotes not applicable
>> Asterisk symbol (*) denotes fewer than six in a cohort is suppressed
>> Outplaced students are counted only in district graduation calculation
>> Row percentages may not add to 100 percent because of rounding
>> District graduation rates may not be the same as the average of the graduation rates of the number schools in that district because of outplaced students.
>> Because each cohort is different from one year to another year, graduation rates are not comparable from year to year. Caution interpreting the differences between the previous year and the current year 

Cohort Graduation Rate Documentation: http://www.sde.ct.gov/sde/lib/sde/PDF/EvalResearch/cohortgraddocumentation.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | district_name             | District Name             | text      | text        |
| Yes      | series tag     | category                  | Category                  | text      | text        |
| Yes      | numeric metric | 4_year_rates              | 4-Year Rates              | number    | number      |
| Yes      | numeric metric | still_enrolled            | Still Enrolled            | number    | number      |
| Yes      | numeric metric | certificate_of_attendance | Certificate of Attendance | number    | number      |
| Yes      | numeric metric | other                     | Other                     | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sus6-q2ti d:2012-01-01T00:00:00.000Z t:category="All Students" t:district_name="Ansonia School District" m:other=18 m:still_enrolled=5.9 m:certificate_of_attendance=0 m:4_year_rates=76.1

series e:sus6-q2ti d:2012-01-01T00:00:00.000Z t:category=Hispanic t:district_name="Ansonia School District" m:other=26.7 m:still_enrolled=4.4 m:certificate_of_attendance=0 m:4_year_rates=68.9

series e:sus6-q2ti d:2012-01-01T00:00:00.000Z t:category=Non-Hispanic t:district_name="Ansonia School District" m:other=15.6 m:still_enrolled=6.3 m:certificate_of_attendance=0 m:4_year_rates=78.1
```

## Meta Commands

```ls
metric m:4_year_rates p:float l:"4-Year Rates" t:dataTypeName=number

metric m:still_enrolled p:float l:"Still Enrolled" t:dataTypeName=number

metric m:certificate_of_attendance p:float l:"Certificate of Attendance" t:dataTypeName=number

metric m:other p:float l:Other t:dataTypeName=number

entity e:sus6-q2ti l:"District Cohort Graduation Rates: 2012" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/sus6-q2ti

property e:sus6-q2ti t:meta.view v:id=sus6-q2ti v:category=Education v:averageRating=0 v:name="District Cohort Graduation Rates: 2012" v:attribution="State Department of Education"

property e:sus6-q2ti t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:sus6-q2ti t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_name           | category                     | 4_year_rates | still_enrolled | certificate_of_attendance | other | 
| ======================= | ============================ | ============ | ============== | ========================= | ===== | 
| Ansonia School District | All Students                 | 76.1         | 5.9            | 0.0                       | 18.0  | 
| Ansonia School District | Hispanic                     | 68.9         | 4.4            | 0.0                       | 26.7  | 
| Ansonia School District | Non-Hispanic                 | 78.1         | 6.3            | 0.0                       | 15.6  | 
| Ansonia School District | Asian                        |              |                |                           |       | 
| Ansonia School District | Black                        | 56.1         | 12.2           | 0.0                       | 31.7  | 
| Ansonia School District | Hawaiian or Pacific Islander |              |                |                           |       | 
| Ansonia School District | White                        | 85.5         | 4.3            | 0.0                       | 10.3  | 
| Ansonia School District | Male                         | 69.8         | 7.5            | 0.0                       | 22.6  | 
| Ansonia School District | Female                       | 82.8         | 4.0            | 0.0                       | 13.1  | 
| Ansonia School District | ELL                          | 60.0         | 10.0           | 0.0                       | 30.0  | 
```