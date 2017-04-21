# City of Seattle Wages: Comparison by Gender ?Wage Progression Job Titles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-wage-progression-job-titles-417b2) |
| Metadata | [Link](https://data.seattle.gov/api/views/k9m8-nhz3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/k9m8-nhz3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/k9m8-nhz3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | k9m8-nhz3 |
| Name | City of Seattle Wages: Comparison by Gender ?Wage Progression Job Titles |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender |
| Created | 2013-07-16T16:37:03Z |
| Publication Date | 2013-07-16T16:39:14Z |

## Description

Average hourly wages for women and men in all represented and non-represented step-progression job classes

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                   | Data Type | Render Type |
| ======== | ============== | ==================== | ====================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | job_classification   | Job Classification     | text      | text        |
| Yes      | numeric metric | female_avg_hrly_rate | Female Avg Hrly Rate   | number    | number      |
| Yes      | numeric metric | no_female_empl       | No. Female Empl        | number    | number      |
| Yes      | numeric metric | male_avg_hrly_rate   | Male Avg Hrly Rate     | number    | number      |
| Yes      | numeric metric | no_male_empl         | No. Male Empl          | number    | number      |
| Yes      | numeric metric | total_avg_hrly_rate  | Total Avg Hrly Rate    | number    | number      |
| Yes      | numeric metric | total_no_empl        | Total No. Empl         | number    | number      |
| Yes      | numeric metric | female_to_male_rate  | Female to male % rate  | percent   | percent     |
| Yes      | numeric metric | female_to_male_count | Female to male % count | percent   | percent     |
| Yes      | series tag     | notes                | Notes                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k9m8-nhz3 d:2013-07-16T09:37:05.000Z t:job_classification=Accountant m:female_avg_hrly_rate=30.58 m:no_female_empl=23 m:male_avg_hrly_rate=30.28 m:no_male_empl=7 m:female_to_male_rate=101 m:female_to_male_count=329 m:total_no_empl=30 m:total_avg_hrly_rate=30.51

series e:k9m8-nhz3 d:2013-07-16T09:37:05.000Z t:job_classification=Accountant,Prin m:female_avg_hrly_rate=38.75 m:no_female_empl=23 m:male_avg_hrly_rate=37.64 m:no_male_empl=7 m:female_to_male_rate=103 m:female_to_male_count=329 m:total_no_empl=30 m:total_avg_hrly_rate=38.49

series e:k9m8-nhz3 d:2013-07-16T09:37:05.000Z t:job_classification=Accountant,Sr m:female_avg_hrly_rate=34.48 m:no_female_empl=23 m:male_avg_hrly_rate=33.89 m:no_male_empl=6 m:female_to_male_rate=102 m:female_to_male_count=383 m:total_no_empl=29 m:total_avg_hrly_rate=34.36
```

## Meta Commands

```ls
metric m:female_avg_hrly_rate p:float l:"Female Avg Hrly Rate" t:dataTypeName=number

metric m:no_female_empl p:integer l:"No. Female Empl" t:dataTypeName=number

metric m:male_avg_hrly_rate p:float l:"Male Avg Hrly Rate" t:dataTypeName=number

metric m:no_male_empl p:integer l:"No. Male Empl" t:dataTypeName=number

metric m:total_avg_hrly_rate p:float l:"Total Avg Hrly Rate" t:dataTypeName=number

metric m:total_no_empl p:integer l:"Total No. Empl" t:dataTypeName=number

metric m:female_to_male_rate p:integer l:"Female to male % rate" t:dataTypeName=percent

metric m:female_to_male_count p:integer l:"Female to male % count" t:dataTypeName=percent

entity e:k9m8-nhz3 l:"City of Seattle Wages:  Comparison by Gender ?Wage Progression Job Titles" t:url=https://data.seattle.gov/api/views/k9m8-nhz3

property e:k9m8-nhz3 t:meta.view v:id=k9m8-nhz3 v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-5B-final.pdf v:averageRating=0 v:name="City of Seattle Wages:  Comparison by Gender ?Wage Progression Job Titles"

property e:k9m8-nhz3 t:meta.view.license v:name="Public Domain"

property e:k9m8-nhz3 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:k9m8-nhz3 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | job_classification | female_avg_hrly_rate | no_female_empl | male_avg_hrly_rate | no_male_empl | total_avg_hrly_rate | total_no_empl | female_to_male_rate | female_to_male_count | notes           | 
| =========== | ================== | ==================== | ============== | ================== | ============ | =================== | ============= | =================== | ==================== | =============== | 
| 1373967425  | Accountant         | 30.58                | 23             | 30.28              | 7            | 30.51               | 30            | 101                 | 329                  |                 | 
| 1373967425  | Accountant,Prin    | 38.75                | 23             | 37.64              | 7            | 38.49               | 30            | 103                 | 329                  |                 | 
| 1373967425  | Accountant,Sr      | 34.479999999999997   | 23             | 33.89              | 6            | 34.36               | 29            | 102                 | 383                  |                 | 
| 1373967425  | Act Exec           | 43.1                 | 4              | 42.02              | 7            | 42.42               | 11            | 103                 | 57                   |                 | 
| 1373967425  | Actg Tech I        | 22.56                | 1              |                    |              | 22.56               | 1             |                     |                      | no men in title | 
| 1373967425  | Actg Tech I-BU     | 22.56                | 10             | 22.56              | 2            | 22.56               | 12            | 100                 | 500                  |                 | 
| 1373967425  | Actg Tech II       | 23.98                | 7              | 24.35              | 1            | 24.03               | 8             | 98                  | 700                  |                 | 
| 1373967425  | Actg Tech II-BU    | 24.19                | 74             | 24.21              | 18           | 24.2                | 92            | 100                 | 411                  |                 | 
| 1373967425  | Actg Tech III      | 26.64                | 7              |                    |              | 26.64               | 7             |                     |                      | no men in title | 
| 1373967425  | Actg Tech III-BU   | 26.69                | 32             | 26.18              | 5            | 26.63               | 37            | 102                 | 640                  |                 | 
```