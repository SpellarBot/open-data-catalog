# City of Seattle Wages: Comparison by Gender - All Job Classifications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-all-job-classifications-e471a) |
| Metadata | [Link](https://data.seattle.gov/api/views/cf52-s8er) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/cf52-s8er/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/cf52-s8er/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | cf52-s8er |
| Name | City of Seattle Wages: Comparison by Gender - All Job Classifications |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T17:25:13Z |
| Publication Date | 2013-07-16T17:28:09Z |

## Description

Average pay comparison of male and female wages by job classification (except Library job classes).  The data contains weighted average hourly pay rates for women and men and the average of all employee wages in the class.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================ | ============================================================== | ========= | =========== |
| No       | time           | :updated_at                                                  | updated_at                                                     | meta_data | meta_data   |
| Yes      | series tag     | jobtitle                                                     | Jobtitle                                                       | text      | text        |
| Yes      | numeric metric | female_avg_hrly_rate                                         | Female Avg Hrly Rate                                           | number    | number      |
| Yes      | numeric metric | no_female_empl                                               | No. Female Empl                                                | number    | number      |
| Yes      | numeric metric | average_of_female_months_longevity_in_current_classification | Average of Female MONTHS LONGEVITY IN CURRENT CLASSIFICATION   | number    | number      |
| Yes      | numeric metric | male_avg_hrly_rate                                           | Male Avg Hrly Rate                                             | number    | number      |
| Yes      | numeric metric | no_male_empl                                                 | No. Male Empl                                                  | number    | number      |
| Yes      | numeric metric | average_of_male_months_longevity_in_current_classification   | Average of Male MONTHS LONGEVITY IN CURRENT CLASSIFICATION     | number    | number      |
| Yes      | numeric metric | total_avg_hrly_rate                                          | Total Avg Hrly Rate                                            | number    | number      |
| Yes      | numeric metric | total_no_empl                                                | Total No. Empl                                                 | number    | number      |
| Yes      | numeric metric | total_average_of_months_longevity_in_current_classification  | Total Average of MONTHS LONGEVITY IN CURRENT CLASSIFICATION    | number    | number      |
| Yes      | numeric metric | ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage | Ratio of women's hourly rate to men's hourly rate - percentage | percent   | percent     |
| Yes      | series tag     | notes                                                        | Notes                                                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cf52-s8er d:2013-07-16T10:25:18.000Z t:jobtitle=Accountant m:female_avg_hrly_rate=30.58 m:no_female_empl=23 m:ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage=101 m:male_avg_hrly_rate=30.28 m:average_of_female_months_longevity_in_current_classification=88.96 m:no_male_empl=7 m:total_average_of_months_longevity_in_current_classification=88.2 m:average_of_male_months_longevity_in_current_classification=85.71 m:total_no_empl=30 m:total_avg_hrly_rate=30.51

series e:cf52-s8er d:2013-07-16T10:25:18.000Z t:jobtitle=Accountant,Prin m:female_avg_hrly_rate=38.75 m:no_female_empl=23 m:ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage=102.95 m:male_avg_hrly_rate=37.64 m:average_of_female_months_longevity_in_current_classification=59.96 m:no_male_empl=7 m:total_average_of_months_longevity_in_current_classification=47.6 m:average_of_male_months_longevity_in_current_classification=7 m:total_no_empl=30 m:total_avg_hrly_rate=38.49

series e:cf52-s8er d:2013-07-16T10:25:18.000Z t:jobtitle=Accountant,Sr m:female_avg_hrly_rate=34.48 m:no_female_empl=23 m:ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage=101.75 m:male_avg_hrly_rate=33.89 m:average_of_female_months_longevity_in_current_classification=60.61 m:no_male_empl=6 m:total_average_of_months_longevity_in_current_classification=57.1 m:average_of_male_months_longevity_in_current_classification=43.67 m:total_no_empl=29 m:total_avg_hrly_rate=34.36
```

## Meta Commands

```ls
metric m:female_avg_hrly_rate p:float l:"Female Avg Hrly Rate" t:dataTypeName=number

metric m:no_female_empl p:integer l:"No. Female Empl" t:dataTypeName=number

metric m:average_of_female_months_longevity_in_current_classification p:float l:"Average of Female MONTHS LONGEVITY IN CURRENT CLASSIFICATION" t:dataTypeName=number

metric m:male_avg_hrly_rate p:float l:"Male Avg Hrly Rate" t:dataTypeName=number

metric m:no_male_empl p:integer l:"No. Male Empl" t:dataTypeName=number

metric m:average_of_male_months_longevity_in_current_classification p:float l:"Average of Male MONTHS LONGEVITY IN CURRENT CLASSIFICATION" t:dataTypeName=number

metric m:total_avg_hrly_rate p:float l:"Total Avg Hrly Rate" t:dataTypeName=number

metric m:total_no_empl p:integer l:"Total No. Empl" t:dataTypeName=number

metric m:total_average_of_months_longevity_in_current_classification p:float l:"Total Average of MONTHS LONGEVITY IN CURRENT CLASSIFICATION" t:dataTypeName=number

metric m:ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage p:float l:"Ratio of women's hourly rate to men's hourly rate - percentage" t:dataTypeName=percent

entity e:cf52-s8er l:"City of Seattle Wages:  Comparison by Gender - All Job Classifications" t:url=https://data.seattle.gov/api/views/cf52-s8er

property e:cf52-s8er t:meta.view v:id=cf52-s8er v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-1-Final.pdf v:averageRating=0 v:name="City of Seattle Wages:  Comparison by Gender - All Job Classifications"

property e:cf52-s8er t:meta.view.license v:name="Public Domain"

property e:cf52-s8er t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:cf52-s8er t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | jobtitle         | female_avg_hrly_rate | no_female_empl | average_of_female_months_longevity_in_current_classification | male_avg_hrly_rate | no_male_empl | average_of_male_months_longevity_in_current_classification | total_avg_hrly_rate | total_no_empl | total_average_of_months_longevity_in_current_classification | ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage | notes           | 
| =========== | ================ | ==================== | ============== | ============================================================ | ================== | ============ | ========================================================== | =================== | ============= | =========================================================== | ============================================================ | =============== | 
| 1373970318  | Accountant       | 30.58                | 23             | 88.96                                                        | 30.28              | 7            | 85.71                                                      | 30.51               | 30            | 88.20                                                       | 101.00                                                       |                 | 
| 1373970318  | Accountant,Prin  | 38.75                | 23             | 59.96                                                        | 37.64              | 7            | 7.00                                                       | 38.49               | 30            | 47.60                                                       | 102.95                                                       |                 | 
| 1373970318  | Accountant,Sr    | 34.48                | 23             | 60.61                                                        | 33.89              | 6            | 43.67                                                      | 34.36               | 29            | 57.10                                                       | 101.75                                                       |                 | 
| 1373970318  | Act Exec         | 43.10                | 4              | 146.00                                                       | 42.02              | 7            | 106.29                                                     | 42.42               | 11            | 120.73                                                      | 102.56                                                       |                 | 
| 1373970318  | Actg Tech I      | 22.56                | 1              | 156.00                                                       |                    |              |                                                            | 22.56               | 1             | 156.00                                                      |                                                              | no men in title | 
| 1373970318  | Actg Tech I-BU   | 22.56                | 10             | 81.80                                                        | 22.56              | 2            | 35.50                                                      | 22.56               | 12            | 74.08                                                       | 100.00                                                       |                 | 
| 1373970318  | Actg Tech II     | 23.98                | 7              | 112.71                                                       | 24.35              | 1            | 75.00                                                      | 24.03               | 8             | 108.00                                                      | 98.49                                                        |                 | 
| 1373970318  | Actg Tech II-BU  | 24.19                | 74             | 103.23                                                       | 24.21              | 18           | 134.50                                                     | 24.20               | 92            | 109.35                                                      | 99.95                                                        |                 | 
| 1373970318  | Actg Tech III    | 26.64                | 7              | 51.57                                                        |                    |              |                                                            | 26.64               | 7             | 51.57                                                       |                                                              | no men in title | 
| 1373970318  | Actg Tech III-BU | 26.69                | 32             | 89.97                                                        | 26.18              | 5            | 51.20                                                      | 26.63               | 37            | 84.73                                                       | 101.96                                                       |                 | 
```