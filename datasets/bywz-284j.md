# Performance Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-measures) |
| Metadata | [Link](https://data.lacity.org/api/views/bywz-284j) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/bywz-284j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/bywz-284j/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | bywz-284j |
| Name | Performance Measures |
| Category | A Prosperous City |
| Tags | performance, budget, performance metrics, departments |
| Created | 2016-04-25T14:18:48Z |
| Publication Date | 2017-04-20T23:45:16Z |

## Description

Performance metrics for each department, fiscal years 2013 - 2018 (proposed).

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | department_code          | Department Code          | text      | number      |
| Yes      | series tag     | department_name          | Department Name          | text      | text        |
| Yes      | series tag     | subdept_code             | SubDept Code             | text      | text        |
| Yes      | series tag     | subdept_name             | SubDept Name             | text      | text        |
| Yes      | series tag     | program_code             | Program Code             | text      | number      |
| Yes      | series tag     | program_name             | Program Name             | text      | text        |
| Yes      | series tag     | performance_measure_code | Performance Measure Code | text      | text        |
| Yes      | series tag     | performance_measure_name | Performance Measure Name | text      | text        |
| Yes      | series tag     | unit                     | Unit                     | text      | text        |
| Yes      | numeric metric | 2012_13_actuals          | 2012-13 Actuals          | number    | number      |
| Yes      | numeric metric | 2013_14_actuals          | 2013-14 Actuals          | number    | number      |
| Yes      | numeric metric | 2014_15_actuals          | 2014-15 Actuals          | number    | number      |
| Yes      | numeric metric | 2015_16_adopted_budget   | 2015-16 Adopted Budget   | number    | number      |
| Yes      | numeric metric | 2015_16_actuals          | 2015-16 Actuals          | number    | number      |
| Yes      | numeric metric | 2016_17_adopted          | 2016-17 Adopted Budget   | number    | number      |
| Yes      | numeric metric | 2016_2017_actuals        | 2016-2017 Estimates      | number    | number      |
| Yes      | numeric metric | 2017_18_proposed_budget  | 2017-18 Proposed Budget  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bywz-284j d:2017-04-20T23:44:30.000Z t:performance_measure_name="Number of Home Delivered and Congregate Meals Provided" t:subdept_name=Aging t:program_code=201 t:subdept_code=02LVL5 t:program_name="Senior Services" t:department_code=2 t:performance_measure_code=02MEALS t:department_name=Aging m:2016_2017_actuals=1502186 m:2015_16_adopted_budget=1467375 m:2016_17_adopted=1682275 m:2017_18_proposed_budget=1502186 m:2012_13_actuals=1537096 m:2014_15_actuals=1468545 m:2013_14_actuals=1467375 m:2015_16_actuals=1467375

series e:bywz-284j d:2017-04-20T23:44:30.000Z t:performance_measure_name="Number of Participants in Caregiver Information Sessions" t:subdept_name=Aging t:program_code=202 t:subdept_code=02LVL5 t:program_name="Family Caregiver Services" t:department_code=2 t:performance_measure_code=02CAREGIVER t:department_name=Aging m:2016_2017_actuals=8490 m:2015_16_adopted_budget=8490 m:2016_17_adopted=8490 m:2017_18_proposed_budget=8490 m:2012_13_actuals=7682 m:2014_15_actuals=6725 m:2013_14_actuals=8490 m:2015_16_actuals=8490

series e:bywz-284j d:2017-04-20T23:44:30.000Z t:performance_measure_name="Number of Participants in the Older Workers Program" t:subdept_name=Aging t:program_code=203 t:subdept_code=02LVL5 t:program_name="Older Workers Program" t:department_code=2 t:performance_measure_code=02OLDERWORKER t:department_name=Aging m:2016_2017_actuals=156 m:2015_16_adopted_budget=180 m:2016_17_adopted=156 m:2017_18_proposed_budget=156 m:2012_13_actuals=196 m:2014_15_actuals=166 m:2013_14_actuals=180 m:2015_16_actuals=180
```

## Meta Commands

```ls
metric m:2012_13_actuals p:long l:"2012-13 Actuals" t:dataTypeName=number

metric m:2013_14_actuals p:long l:"2013-14 Actuals" t:dataTypeName=number

metric m:2014_15_actuals p:long l:"2014-15 Actuals" t:dataTypeName=number

metric m:2015_16_adopted_budget p:long l:"2015-16 Adopted Budget" t:dataTypeName=number

metric m:2015_16_actuals p:long l:"2015-16 Actuals" t:dataTypeName=number

metric m:2016_17_adopted p:long l:"2016-17 Adopted Budget" t:dataTypeName=number

metric m:2016_2017_actuals p:long l:"2016-2017 Estimates" t:dataTypeName=number

metric m:2017_18_proposed_budget p:long l:"2017-18 Proposed Budget" t:dataTypeName=number

entity e:bywz-284j l:"Performance Measures" t:url=https://data.lacity.org/api/views/bywz-284j

property e:bywz-284j t:meta.view v:id=bywz-284j v:category="A Prosperous City" v:averageRating=0 v:name="Performance Measures"

property e:bywz-284j t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:bywz-284j t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:bywz-284j t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| :updated_at | department_code | department_name     | subdept_code | subdept_name        | program_code | program_name                                              | performance_measure_code | performance_measure_name                                   | unit       | 2012_13_actuals | 2013_14_actuals | 2014_15_actuals | 2015_16_adopted_budget | 2015_16_actuals | 2016_17_adopted | 2016_2017_actuals | 2017_18_proposed_budget | 
| =========== | =============== | =================== | ============ | =================== | ============ | ========================================================= | ======================== | ========================================================== | ========== | =============== | =============== | =============== | ====================== | =============== | =============== | ================= | ======================= | 
| 1492731870  | 2               | Aging               | 02LVL5       | Aging               | 201          | Senior Services                                           | 02MEALS                  | Number of Home Delivered and Congregate Meals Provided     |            | 1537096         | 1467375         | 1468545         | 1467375                | 1467375         | 1682275         | 1502186           | 1502186                 | 
| 1492731870  | 2               | Aging               | 02LVL5       | Aging               | 202          | Family Caregiver Services                                 | 02CAREGIVER              | Number of Participants in Caregiver Information Sessions   |            | 7682            | 8490            | 6725            | 8490                   | 8490            | 8490            | 8490              | 8490                    | 
| 1492731870  | 2               | Aging               | 02LVL5       | Aging               | 203          | Older Workers Program                                     | 02OLDERWORKER            | Number of Participants in the Older Workers Program        |            | 196             | 180             | 166             | 180                    | 180             | 156             | 156               | 156                     | 
| 1492731870  | 6               | Animal Services     | 06LVL5       | Animal Services     | 601          | Animal Control and Law Enforcement                        | 06LICENSE                | Number of Animal Licenses Sold                             |            | 126234          | 123008          | 120975          | 127000                 | 131959          | 137000          | 132000            | 137000                  | 
| 1492731870  | 6               | Animal Services     | 06LVL5       | Animal Services     | 602          | Shelter Operations and Animal Care                        | 06LIVESAVE               | Animal Live/Save Rate                                      | percentage | 63.53           | 70.27           | 71              | 75                     | 78.74           | 75              | 80                | 85                      | 
| 1492731870  | 6               | Animal Services     | 06LVL5       | Animal Services     | 607          | Animal Medical Services                                   | 06SPAYNEUTER             | Number of Spay/Neuter Surgeries                            |            | 4238            | 5971            | 5971            | 5500                   | 3922            | 7000            | 4000              | 7000                    | 
| 1492731870  | 6               | Animal Services     | 06LVL5       | Animal Services     | 609          | Public Counters and Community Services                    | 06VOLUNTEER              | Number of Volunteer Hours                                  |            | 45825           | 52086           | 43837           | 50000                  | 55530           | 55000           | 55000             | 63250                   | 
| 1492731870  | 8               | Building and Safety | 08LVL5       | Building and Safety | 811          | Structural Plan Checking                                  | 08PLANCHECK              | Percent of Plan Check Jobs Completed in 15 Days            |            | 91              | 88              | 72              | 90                     | 78              | 80              | 80                | 80                      | 
| 1492731870  | 8               | Building and Safety | 08LVL5       | Building and Safety | 812          | Green Buildings and Electrical and Mechanical Engineering | 08MECHPLANCK             | Percent of Mechanical Plan Check Jobs Completed in 15 Days |            | 91              | 89              | 90              | 90                     | 89              | 90              | 90                | 90                      | 
| 1492731870  | 8               | Building and Safety | 08LVL5       | Building and Safety | 813          | Grading Reports and Inspection                            | 08GRADEREPORT            | Percent of New Grading Reports Completed in 30 Days        |            | 80              | 82              | 100             | 97                     | 100             | 99              | 100               | 100                     | 
```