# Indicators of Educational Need by District: 2011-12

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/indicators-of-educational-need-by-district-2011-12) |
| Metadata | [Link](https://data.ct.gov/api/views/re57-j6dx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/re57-j6dx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/re57-j6dx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | re57-j6dx |
| Name | Indicators of Educational Need by District: 2011-12 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | district, enrollment, special education, ell, lunch eligibility, ctkids |
| Created | 2014-09-03T13:12:22Z |
| Publication Date | 2014-09-03T13:50:26Z |

## Description

This dataset contains counts and percentages of special education students, English Language Learners (ELL), and students eligible for free or reduced price meals by district for the 2011-12 school year. Small cell sizes have been suppressed, and are denoted by an asterisk.

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:re57-j6dx d:2011-01-01T00:00:00.000Z t:district_name="Lebanon School District" m:total=1283 m:special_education_2=12 m:special_education_1=154 m:english_language_learner_2=0 m:english_language_learner_1=0 m:eligible_for_free_or_reduced_price_lunch_2=11.69 m:eligible_for_free_or_reduced_price_lunch_1=150

series e:re57-j6dx d:2011-01-01T00:00:00.000Z t:district_name="Voluntown School District" m:total=319 m:special_education_2=9.72 m:special_education_1=31 m:english_language_learner_2=0 m:english_language_learner_1=0 m:eligible_for_free_or_reduced_price_lunch_2=20.38 m:eligible_for_free_or_reduced_price_lunch_1=65

series e:re57-j6dx d:2011-01-01T00:00:00.000Z t:district_name="Andover School District" m:total=314 m:special_education_2=7.64 m:special_education_1=24 m:eligible_for_free_or_reduced_price_lunch_2=10.19 m:eligible_for_free_or_reduced_price_lunch_1=32
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

entity e:re57-j6dx l:"Indicators of Educational Need by District: 2011-12" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/re57-j6dx

property e:re57-j6dx t:meta.view v:id=re57-j6dx v:category=Education v:averageRating=0 v:name="Indicators of Educational Need by District: 2011-12" v:attribution="State Department of Education"

property e:re57-j6dx t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:re57-j6dx t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_name               | total | eligible_for_free_or_reduced_price_lunch_1 | eligible_for_free_or_reduced_price_lunch_2 | special_education_1 | special_education_2 | english_language_learner_1 | english_language_learner_2 | 
| =========================== | ===== | ========================================== | ========================================== | =================== | =================== | ========================== | ========================== | 
| Lebanon School District     | 1283  | 150                                        | 11.69                                      | 154                 | 12.00               | 0                          | 0.00                       | 
| Voluntown School District   | 319   | 65                                         | 20.38                                      | 31                  | 9.72                | 0                          | 0.00                       | 
| Andover School District     | 314   | 32                                         | 10.19                                      | 24                  | 7.64                |                            |                            | 
| Ansonia School District     | 2514  | 1519                                       | 60.42                                      | 272                 | 10.82               | 77                         | 3.06                       | 
| Ashford School District     | 481   | 142                                        | 29.52                                      | 55                  | 11.43               | 8                          | 1.66                       | 
| Avon School District        | 3495  | 202                                        | 5.78                                       | 359                 | 10.27               | 60                         | 1.72                       | 
| Barkhamsted School District | 357   | 19                                         | 5.32                                       | 38                  | 10.64               |                            |                            | 
| Berlin School District      | 3015  | 338                                        | 11.21                                      | 289                 | 9.59                | 73                         | 2.42                       | 
| Bethany School District     | 491   | 25                                         | 5.09                                       | 65                  | 13.24               |                            |                            | 
| Bethel School District      | 2970  | 477                                        | 16.06                                      | 312                 | 10.51               | 79                         | 2.66                       | 
```