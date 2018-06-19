# Indicators of Educational Need by District: 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/indicators-of-educational-need-by-district-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/399t-fqcf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/399t-fqcf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/399t-fqcf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 399t-fqcf |
| Name | Indicators of Educational Need by District: 2012-13 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | district, enrollment, special education, ell, lunch eligibility, ctkids |
| Created | 2014-09-03T13:44:38Z |
| Publication Date | 2014-09-03T13:52:34Z |

## Description

This dataset contains counts and percentages of special education students, English Language Learners (ELL), and students eligible for free or reduced price meals by district for the 2012-13 school year. Small cell sizes have been suppressed, and are denoted by an asterisk.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | district_name                              | district name                              | text      | text        |
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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:399t-fqcf d:2012-01-01T00:00:00.000Z t:district_name="Vernon School District" m:total=3442 m:special_education_2=12 m:special_education_1=414 m:english_language_learner_2=1.9 m:english_language_learner_1=66 m:eligible_for_free_or_reduced_price_lunch_2=36.6 m:eligible_for_free_or_reduced_price_lunch_1=1259

series e:399t-fqcf d:2012-01-01T00:00:00.000Z t:district_name="Andover School District" m:total=314 m:special_education_2=7.6 m:special_education_1=24 m:eligible_for_free_or_reduced_price_lunch_2=14 m:eligible_for_free_or_reduced_price_lunch_1=44

series e:399t-fqcf d:2012-01-01T00:00:00.000Z t:district_name="Ansonia School District" m:total=2409 m:special_education_2=11.5 m:special_education_1=277 m:english_language_learner_2=2.9 m:english_language_learner_1=69 m:eligible_for_free_or_reduced_price_lunch_2=67.2 m:eligible_for_free_or_reduced_price_lunch_1=1619
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

metric m:eligible_for_free_or_reduced_price_lunch_1 p:integer l:"Eligible for Free or Reduced Price Lunch" t:dataTypeName=number

metric m:eligible_for_free_or_reduced_price_lunch_2 p:float l:"% Eligible for Free or Reduced Price Lunch" t:dataTypeName=percent

metric m:special_education_1 p:integer l:"Special Education" t:dataTypeName=number

metric m:special_education_2 p:float l:"% Special Education" t:dataTypeName=percent

metric m:english_language_learner_1 p:integer l:"English Language Learner" t:dataTypeName=number

metric m:english_language_learner_2 p:float l:"% English Language Learner" t:dataTypeName=percent

entity e:399t-fqcf l:"Indicators of Educational Need by District: 2012-13" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/399t-fqcf

property e:399t-fqcf t:meta.view v:id=399t-fqcf v:category=Education v:averageRating=0 v:name="Indicators of Educational Need by District: 2012-13" v:attribution="State Department of Education"

property e:399t-fqcf t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:399t-fqcf t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_name               | total | eligible_for_free_or_reduced_price_lunch_1 | eligible_for_free_or_reduced_price_lunch_2 | special_education_1 | special_education_2 | english_language_learner_1 | english_language_learner_2 | 
| =========================== | ===== | ========================================== | ========================================== | =================== | =================== | ========================== | ========================== | 
| Vernon School District      | 3442  | 1259                                       | 36.6                                       | 414                 | 12.0                | 66                         | 1.9                        | 
| Andover School District     | 314   | 44                                         | 14.0                                       | 24                  | 7.6                 |                            |                            | 
| Ansonia School District     | 2409  | 1619                                       | 67.2                                       | 277                 | 11.5                | 69                         | 2.9                        | 
| Ashford School District     | 439   | 145                                        | 33.0                                       | 55                  | 12.5                | 7                          | 1.6                        | 
| Avon School District        | 3403  | 204                                        | 6.0                                        | 352                 | 10.3                | 57                         | 1.7                        | 
| Barkhamsted School District | 349   | 24                                         | 6.9                                        | 43                  | 12.3                |                            |                            | 
| Berlin School District      | 2972  | 397                                        | 13.4                                       | 298                 | 10.0                | 71                         | 2.4                        | 
| Bethany School District     | 473   | 28                                         | 5.9                                        | 57                  | 12.1                | 0                          | 0.0                        | 
| Bethel School District      | 2975  | 528                                        | 17.7                                       | 318                 | 10.7                | 80                         | 2.7                        | 
| Bloomfield School District  | 2108  | 1015                                       | 48.1                                       | 221                 | 10.5                | 25                         | 1.2                        | 
```