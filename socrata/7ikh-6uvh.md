# Indicators of Educational Need by School: 2013-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/indicators-of-educational-need-by-school-2013-14) |
| Metadata | [Link](https://data.ct.gov/api/views/7ikh-6uvh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7ikh-6uvh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7ikh-6uvh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7ikh-6uvh |
| Name | Indicators of Educational Need by School: 2013-14 |
| Attribution | SDE |
| Category | Education |
| Tags | education, school, need |
| Created | 2015-02-23T13:37:41Z |
| Publication Date | 2015-07-17T17:37:52Z |

## Description

This dataset contains counts and percentages of special education students, English Language Learners (ELL), and students eligible for free or reduced price meals by school for the 2013-14 school year. Small cell sizes have been suppressed, and are denoted by an asterisk.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | numeric metric | dist                                       | dist                                       | number    | number      |
| Yes      | series tag     | district_name                              | district name                              | text      | text        |
| Yes      | numeric metric | school                                     | School                                     | number    | number      |
| Yes      | series tag     | school_name                                | School Name                                | text      | text        |
| Yes      | numeric metric | total                                      | Total                                      | number    | number      |
| Yes      | numeric metric | eligible_for_free_or_reduced_price_lunch_1 | Eligible for Free or Reduced Price Lunch   | number    | number      |
| Yes      | numeric metric | eligible_for_free_or_reduced_price_lunch_2 | % Eligible for Free or Reduced Price Lunch | percent   | percent     |
| Yes      | numeric metric | special_education_1                        | Special Education                          | number    | number      |
| Yes      | numeric metric | special_education_2                        | % Special Education                        | percent   | percent     |
| Yes      | numeric metric | english_language_learner_1                 | English Language Learner                   | number    | number      |
| Yes      | numeric metric | english_language_learner_2                 | % English Language Learner                 | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ikh-6uvh d:2013-01-01T00:00:00.000Z t:school_name="Andover Elementary School" t:district_name="Andover School District" m:total=298 m:special_education_2=7 m:school=1 m:special_education_1=21 m:eligible_for_free_or_reduced_price_lunch_2=14.4 m:eligible_for_free_or_reduced_price_lunch_1=43 m:dist=1

series e:7ikh-6uvh d:2013-01-01T00:00:00.000Z t:school_name="Mead School" t:district_name="Ansonia School District" m:total=566 m:special_education_2=14.5 m:school=3 m:special_education_1=82 m:english_language_learner_2=3.5 m:english_language_learner_1=20 m:eligible_for_free_or_reduced_price_lunch_2=71.4 m:eligible_for_free_or_reduced_price_lunch_1=404 m:dist=2

series e:7ikh-6uvh d:2013-01-01T00:00:00.000Z t:school_name="Prendergast School" t:district_name="Ansonia School District" m:total=661 m:special_education_2=12.1 m:school=8 m:special_education_1=80 m:english_language_learner_2=6.4 m:english_language_learner_1=42 m:eligible_for_free_or_reduced_price_lunch_2=68.5 m:eligible_for_free_or_reduced_price_lunch_1=453 m:dist=2
```

## Meta Commands

```ls
metric m:dist p:integer l:dist t:dataTypeName=number

metric m:school p:integer l:School t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

metric m:eligible_for_free_or_reduced_price_lunch_1 p:integer l:"Eligible for Free or Reduced Price Lunch" t:dataTypeName=number

metric m:eligible_for_free_or_reduced_price_lunch_2 p:float l:"% Eligible for Free or Reduced Price Lunch" t:dataTypeName=percent

metric m:special_education_1 p:integer l:"Special Education" t:dataTypeName=number

metric m:special_education_2 p:float l:"% Special Education" t:dataTypeName=percent

metric m:english_language_learner_1 p:integer l:"English Language Learner" t:dataTypeName=number

metric m:english_language_learner_2 p:float l:"% English Language Learner" t:dataTypeName=percent

entity e:7ikh-6uvh l:"Indicators of Educational Need by School: 2013-14" t:attribution=SDE t:url=https://data.ct.gov/api/views/7ikh-6uvh

property e:7ikh-6uvh t:meta.view v:id=7ikh-6uvh v:category=Education v:averageRating=0 v:name="Indicators of Educational Need by School: 2013-14" v:attribution=SDE

property e:7ikh-6uvh t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:7ikh-6uvh t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| dist | district_name           | school | school_name               | total | eligible_for_free_or_reduced_price_lunch_1 | eligible_for_free_or_reduced_price_lunch_2 | special_education_1 | special_education_2 | english_language_learner_1 | english_language_learner_2 | 
| ==== | ======================= | ====== | ========================= | ===== | ========================================== | ========================================== | =================== | =================== | ========================== | ========================== | 
| 1    | Andover School District | 1      | Andover Elementary School | 298   | 43                                         | 14.4                                       | 21                  | 7.0                 |                            |                            | 
| 2    | Ansonia School District | 3      | Mead School               | 566   | 404                                        | 71.4                                       | 82                  | 14.5                | 20                         | 3.5                        | 
| 2    | Ansonia School District | 8      | Prendergast School        | 661   | 453                                        | 68.5                                       | 80                  | 12.1                | 42                         | 6.4                        | 
| 2    | Ansonia School District | 51     | Ansonia Middle School     | 487   | 326                                        | 66.9                                       | 68                  | 14.0                | 9                          | 1.8                        | 
| 2    | Ansonia School District | 61     | Ansonia High School       | 602   | 358                                        | 59.5                                       | 67                  | 11.1                | 13                         | 2.2                        | 
| 3    | Ashford School District | 1      | Ashford School            | 422   | 125                                        | 29.6                                       | 49                  | 11.6                | 6                          | 1.4                        | 
| 4    | Avon School District    | 3      | Roaring Brook School      | 573   | 30                                         | 5.2                                        | 48                  | 8.4                 |                            |                            | 
| 4    | Avon School District    | 4      | Pine Grove School         | 592   | 35                                         | 5.9                                        | 53                  | 9.0                 | 24                         | 4.1                        | 
| 4    | Avon School District    | 5      | Thompson Brook School     | 563   | 39                                         | 6.9                                        | 78                  | 13.9                | 10                         | 1.8                        | 
| 4    | Avon School District    | 51     | Avon Middle School        | 584   | 28                                         | 4.8                                        | 50                  | 8.6                 |                            |                            | 
```