# District Cohort Graduation Rates 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/district-cohort-graduation-rates-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/tga8-h5sq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/tga8-h5sq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/tga8-h5sq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | tga8-h5sq |
| Name | District Cohort Graduation Rates 2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, district, graduation, ctkids |
| Created | 2014-06-25T15:17:12Z |
| Publication Date | 2014-06-25T15:20:51Z |

## Description

This dataset contains the 2013 four-year cohort graduation rates by district. 
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
series e:tga8-h5sq d:2013-01-01T00:00:00.000Z t:category="All Students" t:districtname="Ansonia School District" m:4_year_graduation_rate=75.5 m:other=12.7 m:still_enrolled=11.8

series e:tga8-h5sq d:2013-01-01T00:00:00.000Z t:category=Hispanic t:districtname="Ansonia School District" m:4_year_graduation_rate=65.3 m:other=18.4 m:still_enrolled=16.3

series e:tga8-h5sq d:2013-01-01T00:00:00.000Z t:category=Non-Hispanic t:districtname="Ansonia School District" m:4_year_graduation_rate=78.5 m:other=11 m:still_enrolled=10.4
```

## Meta Commands

```ls
metric m:4_year_graduation_rate p:float l:"4-Year Graduation Rate" t:dataTypeName=number

metric m:still_enrolled p:float l:"Still Enrolled" t:dataTypeName=number

metric m:other p:float l:Other t:dataTypeName=number

entity e:tga8-h5sq l:"District Cohort Graduation Rates 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/tga8-h5sq

property e:tga8-h5sq t:meta.view v:id=tga8-h5sq v:category=Education v:averageRating=0 v:name="District Cohort Graduation Rates 2013" v:attribution="State Department of Education"

property e:tga8-h5sq t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:tga8-h5sq t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| districtname            | category                     | 4_year_graduation_rate | still_enrolled | other | 
| ======================= | ============================ | ====================== | ============== | ===== | 
| Ansonia School District | All Students                 | 75.5                   | 11.8           | 12.7  | 
| Ansonia School District | Hispanic                     | 65.3                   | 16.3           | 18.4  | 
| Ansonia School District | Non-Hispanic                 | 78.5                   | 10.4           | 11.0  | 
| Ansonia School District | Asian                        |                        |                |       | 
| Ansonia School District | Black                        | 70.8                   | 6.3            | 22.9  | 
| Ansonia School District | Hawaiian or Pacific Islander |                        |                |       | 
| Ansonia School District | White                        | 81.1                   | 12.6           | 6.3   | 
| Ansonia School District | Male                         | 61.7                   | 21.5           | 16.8  | 
| Ansonia School District | Female                       | 89.5                   | 1.9            | 8.6   | 
| Ansonia School District | ELL                          | 61.5                   | 23.1           | 15.4  | 
```