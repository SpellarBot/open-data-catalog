# City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-average-hourly-wage-by-department-b3eb2) |
| Metadata | [Link](https://data.seattle.gov/api/views/5jqs-k4qf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/5jqs-k4qf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/5jqs-k4qf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 5jqs-k4qf |
| Name | City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T19:41:34Z |
| Publication Date | 2013-07-16T19:43:51Z |

## Description

Average hourly wages for women and men sorted by City department and age range

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                   | Data Type | Render Type |
| ======== | ============== | ==================== | ====================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | department           | DEPARTMENT             | text      | text        |
| Yes      | series tag     | age_range            | AGE RANGE              | text      | text        |
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
series e:5jqs-k4qf d:2013-07-16T12:41:37.000Z t:department="Arts and Cultural Affairs" t:notes="no women in age range" t:age_range="26 - 30" m:male_avg_hrly_rate=29.04 m:no_male_empl=1 m:total_no_empl=1 m:total_avg_hrly_rate=29.04

series e:5jqs-k4qf d:2013-07-16T12:41:37.000Z t:department="Arts and Cultural Affairs" t:age_range="31 - 35" m:female_avg_hrly_rate=32.47 m:no_female_empl=3 m:male_avg_hrly_rate=32.25 m:no_male_empl=2 m:female_to_male_rate=100.7 m:female_to_male_count=150 m:total_no_empl=5 m:total_avg_hrly_rate=32.38

series e:5jqs-k4qf d:2013-07-16T12:41:37.000Z t:department="Arts and Cultural Affairs" t:age_range="36 - 40" m:female_avg_hrly_rate=30.44 m:no_female_empl=2 m:male_avg_hrly_rate=51.95 m:no_male_empl=1 m:female_to_male_rate=58.59 m:female_to_male_count=200 m:total_no_empl=3 m:total_avg_hrly_rate=37.61
```

## Meta Commands

```ls
metric m:female_avg_hrly_rate p:float l:"Female Avg Hrly Rate" t:dataTypeName=number

metric m:no_female_empl p:integer l:"No. Female Empl" t:dataTypeName=number

metric m:male_avg_hrly_rate p:float l:"Male Avg Hrly Rate" t:dataTypeName=number

metric m:no_male_empl p:integer l:"No. Male Empl" t:dataTypeName=number

metric m:total_avg_hrly_rate p:float l:"Total Avg Hrly Rate" t:dataTypeName=number

metric m:total_no_empl p:integer l:"Total No. Empl" t:dataTypeName=number

metric m:female_to_male_rate p:float l:"Female to male % rate" t:dataTypeName=percent

metric m:female_to_male_count p:float l:"Female to male % count" t:dataTypeName=percent

entity e:5jqs-k4qf l:"City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department" t:url=https://data.seattle.gov/api/views/5jqs-k4qf

property e:5jqs-k4qf t:meta.view v:id=5jqs-k4qf v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-3-Final.pdf v:averageRating=0 v:name="City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department"

property e:5jqs-k4qf t:meta.view.license v:name="Public Domain"

property e:5jqs-k4qf t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:5jqs-k4qf t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | department                      | age_range | female_avg_hrly_rate | no_female_empl | male_avg_hrly_rate | no_male_empl | total_avg_hrly_rate | total_no_empl | female_to_male_rate | female_to_male_count | notes                 | 
| =========== | =============================== | ========= | ==================== | ============== | ================== | ============ | =================== | ============= | =================== | ==================== | ===================== | 
| 1373978497  | Arts and Cultural Affairs       | 26 - 30   |                      |                | 29.04              | 1            | 29.04               | 1             |                     |                      | no women in age range | 
| 1373978497  | Arts and Cultural Affairs       | 31 - 35   | 32.47                | 3              | 32.25              | 2            | 32.38               | 5             | 100.70              | 150.00               |                       | 
| 1373978497  | Arts and Cultural Affairs       | 36 - 40   | 30.44                | 2              | 51.95              | 1            | 37.61               | 3             | 58.59               | 200.00               |                       | 
| 1373978497  | Arts and Cultural Affairs       | 41 - 45   | 30.28                | 4              | 24.99              | 2            | 28.51               | 6             | 121.15              | 200.00               |                       | 
| 1373978497  | Arts and Cultural Affairs       | 46 - 50   | 33.81                | 2              | 28.77              | 2            | 31.29               | 4             | 117.54              | 100.00               |                       | 
| 1373978497  | Arts and Cultural Affairs       | 51 - 55   | 40.49                | 2              |                    |              | 40.49               | 2             |                     |                      | no men in age range   | 
| 1373978497  | Arts and Cultural Affairs       | 56 - 60   | 37.84                | 3              |                    |              | 37.84               | 3             |                     |                      | no men in age range   | 
| 1373978497  | Arts and Cultural Affairs       | 61 - 65   | 37.23                | 3              |                    |              | 37.23               | 3             |                     |                      | no men in age range   | 
| 1373978497  | Arts and Cultural Affairs       | 66 - 70   | 52.61                | 1              |                    |              | 52.61               | 1             |                     |                      | no men in age range   | 
| 1373978497  | Arts and Cultural Affairs Total |           | 35.29                | 20             | 31.62              | 8            | 34.24               | 28            | 111.60              | 250.00               |                       | 
```