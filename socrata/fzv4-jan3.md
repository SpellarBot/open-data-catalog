# School Progress Reports - All Schools - 2006-07

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-progress-reports-all-schools-2006-07-0796f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fzv4-jan3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fzv4-jan3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fzv4-jan3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fzv4-jan3 |
| Name | School Progress Reports - All Schools - 2006-07 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T20:32:49Z |
| Publication Date | 2011-10-11T17:54:31Z |

## Description

2006/07 Progress Report results for all schools (data as of 1/14/09)

Peer indices are calculated differently depending on School Level.  Schools are only compared to other schools in the same School Level (e.g., Elementary, K-8, Middle, High)

1) Elementary & K-8 - peer index is a value from 0-100.  We use a composite demographic statistic based on % ELL, % SpEd, % Title I free lunch, and % Black/Hispanic.  Higher values indicate student populations with higher need

2) Middle & High - peer index is a value from 1.00-4.50.  For middle schools, we use the average 4th grade proficiency ratings in ELA and Math for all their students that have 4th grade test scores.  For high schools, we use the average 8th grade proficiency ratings in ELA and Math for all their students that have 8th grade test scores.  Lower values indicate student populations with higher need

3) D84 / Charter Schools - the overall score does not include the results of the learning environment survey. 

4) Schools for Transfer Students - consists of schools with large populations of high school students transferring from NYC High Schools or from out of state/country.  No peer index value is assigned because this set of schools is its own peer group. The reports contain 3 categories with one additional credit section.  Unlike the HS Progress Report, the Environment Category is only composed of Survey Results.  Performance measures 6-year graduation rate and Progress captures student level improvements in attendance, credit accumulation and Regents passed.  The additional credit section rewards schools demonstrating exceptional achievement (11 credits or more earned per year) among overage/under-credit populations.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | dbn                                 | DBN                                 | text      | text        |
| Yes      | series tag     | district                            | DISTRICT                            | text      | number      |
| Yes      | series tag     | school                              | SCHOOL                              | text      | text        |
| Yes      | series tag     | school_support_organization_network | SCHOOL SUPPORT ORGANIZATION/NETWORK | text      | text        |
| Yes      | series tag     | progress_report_type                | PROGRESS REPORT TYPE                | text      | text        |
| Yes      | series tag     | school_level_                       | SCHOOL LEVEL*                       | text      | text        |
| Yes      | numeric metric | peer_index_                         | PEER INDEX*                         | number    | number      |
| Yes      | series tag     | grade                               | GRADE                               | text      | text        |
| Yes      | numeric metric | overall_score                       | OVERALL SCORE                       | number    | number      |
| Yes      | numeric metric | environment_category_score          | ENVIRONMENT CATEGORY SCORE          | number    | number      |
| Yes      | numeric metric | performance_category_score          | PERFORMANCE CATEGORY SCORE          | number    | number      |
| Yes      | numeric metric | progress_category_score             | PROGRESS CATEGORY SCORE             | number    | number      |
| Yes      | numeric metric | additional_credit                   | ADDITIONAL CREDIT                   | number    | number      |
| Yes      | series tag     | quality_review_score                | QUALITY REVIEW SCORE                | text      | text        |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fzv4-jan3 d:2006-01-01T00:00:00.000Z t:school="PS 015 ROBERTO CLEMENTE" t:dbn=01M015 t:school_support_organization_network=ICI15 t:school_level_="Elementary School" t:quality_review_score=Undeveloped t:progress_report_type=ESMS t:grade=B t:district=1 m:additional_credit=3 m:performance_category_score=0.231 m:peer_index_=75.6 m:progress_category_score=0.694 m:environment_category_score=0.278 m:overall_score=52.31

series e:fzv4-jan3 d:2006-01-01T00:00:00.000Z t:school="PS 019 ASHER LEVY" t:dbn=01M019 t:school_support_organization_network=ESO1 t:school_level_="Elementary School" t:quality_review_score=Proficient t:progress_report_type=ESMS t:grade=B t:district=1 m:additional_credit=1.5 m:performance_category_score=0.466 m:peer_index_=59.25 m:progress_category_score=0.511 m:environment_category_score=0.51 m:overall_score=51.24

series e:fzv4-jan3 d:2006-01-01T00:00:00.000Z t:school="PS 020 ANNA SILVER" t:dbn=01M020 t:school_support_organization_network=ICI15 t:school_level_="Elementary School" t:quality_review_score=Well-Developed t:progress_report_type=ESMS t:grade=B t:district=1 m:additional_credit=1.5 m:performance_category_score=0.682 m:peer_index_=69.78 m:progress_category_score=0.402 m:environment_category_score=0.568 m:overall_score=52.59
```

## Meta Commands

```ls
metric m:peer_index_ p:float l:"PEER INDEX*" t:dataTypeName=number

metric m:overall_score p:float l:"OVERALL SCORE" t:dataTypeName=number

metric m:environment_category_score p:float l:"ENVIRONMENT CATEGORY SCORE" t:dataTypeName=number

metric m:performance_category_score p:float l:"PERFORMANCE CATEGORY SCORE" t:dataTypeName=number

metric m:progress_category_score p:float l:"PROGRESS CATEGORY SCORE" t:dataTypeName=number

metric m:additional_credit p:double l:"ADDITIONAL CREDIT" t:dataTypeName=number

entity e:fzv4-jan3 l:"School Progress Reports - All Schools - 2006-07" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/fzv4-jan3

property e:fzv4-jan3 t:meta.view v:id=fzv4-jan3 v:category=Education v:averageRating=0 v:name="School Progress Reports - All Schools - 2006-07" v:attribution="Department of Education (DOE)"

property e:fzv4-jan3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fzv4-jan3 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| dbn    | district | school                      | school_support_organization_network | progress_report_type | school_level_     | peer_index_ | grade | overall_score | environment_category_score | performance_category_score | progress_category_score | additional_credit | quality_review_score | 
| ====== | ======== | =========================== | =================================== | ==================== | ================= | =========== | ===== | ============= | ========================== | ========================== | ======================= | ================= | ==================== | 
| 01M015 | 1        | PS 015 ROBERTO CLEMENTE     | ICI15                               | ESMS                 | Elementary School | 75.6        | B     | 52.31         | 0.278                      | 0.231                      | 0.694                   | 3                 | Undeveloped          | 
| 01M019 | 1        | PS 019 ASHER LEVY           | ESO1                                | ESMS                 | Elementary School | 59.25       | B     | 51.24         | 0.51                       | 0.466                      | 0.511                   | 1.5               | Proficient           | 
| 01M020 | 1        | PS 020 ANNA SILVER          | ICI15                               | ESMS                 | Elementary School | 69.78       | B     | 52.59         | 0.568                      | 0.682                      | 0.402                   | 1.5               | Well-Developed       | 
| 01M034 | 1        | PS 034 FRANKLIN D ROOSEVELT | ICI15                               | ESMS                 | K-8 School        | 71.9        | C     | 47.02         | 0.409                      | 0.366                      | 0.53                    | 0.75              | Proficient           | 
| 01M063 | 1        | PS 063 WILLIAM MCKINLEY     | ICI15                               | ESMS                 | Elementary School | 62.17       | C     | 44.66         | 0.199                      | 0.511                      | 0.479                   | 0                 | Proficient           | 
| 01M064 | 1        | PS 064 ROBERT SIMON         | ESO1                                | ESMS                 | Elementary School | 71.9        | C     | 48.43         | 0.561                      | 0.586                      | 0.408                   | 0                 | Well-Developed       | 
| 01M110 | 1        | PS 110 FLORENCE NIGHTINGALE | ESO1                                | ESMS                 | Elementary School | 54.96       | B     | 51.17         | 0.818                      | 0.644                      | 0.315                   | 2.25              | Proficient           | 
| 01M134 | 1        | PS 134 HENRIETTA SZOLD      | ICI15                               | ESMS                 | Elementary School | 66.49       | B     | 54.21         | 0.338                      | 0.55                       | 0.566                   | 1.5               | Well-Developed       | 
| 01M137 | 1        | PS 137 JOHN L BERNSTEIN     | ICI5                                | ESMS                 | Elementary School | 70.85       | B     | 59.35         | 0.398                      | 0.361                      | 0.76                    | 0.75              | Undeveloped          | 
| 01M140 | 1        | PS 140 NATHAN STRAUS        | ESO19                               | ESMS                 | K-8 School        | 73.18       | B     | 56.14         | 0.588                      | 0.441                      | 0.593                   | 1.5               | Proficient           | 
```