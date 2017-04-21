# Public Financing Report - Total Candidate Spending in 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-financing-report-total-candidate-spending-in-2012-3b3f7) |
| Metadata | [Link](https://data.sfgov.org/api/views/h2wp-niyk) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/h2wp-niyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/h2wp-niyk/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | h2wp-niyk |
| Name | Public Financing Report - Total Candidate Spending in 2012 |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Created | 2013-04-02T16:36:23Z |
| Publication Date | 2013-04-02T16:50:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | candidate                        | Candidate                        | text      | text        |
| Yes      | series tag     | district                         | District                         | text      | text        |
| Yes      | numeric metric | total_candidate_spending_in_2012 | Total Candidate Spending in 2012 | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h2wp-niyk d:2012-01-01T00:00:00.000Z t:candidate="John Avalos" t:district=11 m:total_candidate_spending_in_2012=79601

series e:h2wp-niyk d:2012-01-01T00:00:00.000Z t:candidate="David Lee" t:district=01 m:total_candidate_spending_in_2012=315404

series e:h2wp-niyk d:2012-01-01T00:00:00.000Z t:candidate="Eric Mar" t:district=01 m:total_candidate_spending_in_2012=357723
```

## Meta Commands

```ls
metric m:total_candidate_spending_in_2012 p:integer l:"Total Candidate Spending in 2012" t:dataTypeName=money

entity e:h2wp-niyk l:"Public Financing Report - Total Candidate Spending in 2012" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/h2wp-niyk

property e:h2wp-niyk t:meta.view v:id=h2wp-niyk v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Public Financing Report - Total Candidate Spending in 2012" v:attribution="San Francisco Ethics Commission"

property e:h2wp-niyk t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:h2wp-niyk t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:h2wp-niyk t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| candidate        | district | total_candidate_spending_in_2012 | 
| ================ | ======== | ================================ | 
| John Avalos      | 11       | 79601                            | 
| David Lee        | 01       | 315404                           | 
| Eric Mar         | 01       | 357723                           | 
| Marc Bruno       | 03       | 6990                             | 
| Joseph F. Butler | 03       | 61404                            | 
| David Chiu       | 03       | 230728                           | 
| London Breed     | 05       | 279485                           | 
| Julian Davis     | 05       | 104977                           | 
| Christina Olague | 05       | 267446                           | 
| John Rizzo       | 05       | 102560                           | 
```