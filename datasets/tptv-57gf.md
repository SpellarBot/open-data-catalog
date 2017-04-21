# City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-discretionary-pay-titles-73421) |
| Metadata | [Link](https://data.seattle.gov/api/views/tptv-57gf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/tptv-57gf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/tptv-57gf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | tptv-57gf |
| Name | City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T21:14:08Z |
| Publication Date | 2013-07-16T21:18:42Z |

## Description

Average hourly wages for women and men in the Discretionary Pay Program by job classification

## Columns

```ls
| Included | Schema Type    | Field Name                                                      | Name                                                              | Data Type | Render Type |
| ======== | ============== | =============================================================== | ================================================================= | ========= | =========== |
| No       | time           | :updated_at                                                     | updated_at                                                        | meta_data | meta_data   |
| Yes      | series tag     | job_type                                                        | Job Type                                                          | text      | text        |
| Yes      | numeric metric | average_of_female_hourly_rate                                   | Average of FEMALE HOURLY RATE                                     | number    | number      |
| Yes      | series tag     | count_of_women_in_job_type                                      | Count of women in JOB TYPE                                        | text      | number      |
| Yes      | numeric metric | average_of_female_longevity_by_months                           | Average of FEMALE LONGEVITY BY MONTHS                             | number    | number      |
| Yes      | numeric metric | average_of_male_hourly_rate                                     | Average of MALE HOURLY RATE                                       | number    | number      |
| Yes      | series tag     | count_of_men_in_job_type                                        | Count of men in JOB TYPE                                          | text      | number      |
| Yes      | numeric metric | average_of_male_longevity_by_months                             | Average of MALE LONGEVITY BY MONTHS                               | number    | number      |
| Yes      | numeric metric | average_of_hourly_rate                                          | Average of HOURLY RATE                                            | number    | number      |
| Yes      | series tag     | total_count_of_women_in_job_type                                | Total Count of women in JOB TYPE                                  | text      | number      |
| Yes      | numeric metric | average_of_longevity_by_months                                  | Average of LONGEVITY BY MONTHS                                    | number    | number      |
| Yes      | numeric metric | womens_hourly_rate_compared_to_men_s_pay_rate_in_the_same_title | % womens hourly rate compared to men's pay rate in the same title | percent   | percent     |
| Yes      | numeric metric | womens_longevity_compared_to_men_s_pay_rate_in_the_same_title   | % womens longevity compared to men's pay rate in the same title   | percent   | percent     |
| Yes      | series tag     | notes                                                           | NOTES                                                             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tptv-57gf d:2013-07-16T14:14:11.000Z t:count_of_men_in_job_type=38 t:job_type="City Attorney,Asst" t:count_of_women_in_job_type=53 t:total_count_of_women_in_job_type=91 m:average_of_male_longevity_by_months=60.61 m:womens_longevity_compared_to_men_s_pay_rate_in_the_same_title=0.8371525245987602 m:average_of_female_hourly_rate=45.2 m:average_of_female_longevity_by_months=50.74 m:average_of_hourly_rate=47.88 m:average_of_longevity_by_months=54.86 m:womens_hourly_rate_compared_to_men_s_pay_rate_in_the_same_title=0.8757386233659987 m:average_of_male_hourly_rate=51.61

series e:tptv-57gf d:2013-07-16T14:14:11.000Z t:count_of_men_in_job_type=1 t:job_type="City Light Supt" t:total_count_of_women_in_job_type=1 t:notes="no women in title" m:average_of_male_longevity_by_months=111 m:average_of_hourly_rate=117.32 m:average_of_longevity_by_months=111 m:average_of_male_hourly_rate=117.32

series e:tptv-57gf d:2013-07-16T14:14:11.000Z t:count_of_men_in_job_type=3 t:job_type="Electric Util Exec 2" t:total_count_of_women_in_job_type=3 t:notes="no women in title" m:average_of_male_longevity_by_months=21 m:average_of_hourly_rate=77.8 m:average_of_longevity_by_months=21 m:average_of_male_hourly_rate=77.8
```

## Meta Commands

```ls
metric m:average_of_female_hourly_rate p:float l:"Average of FEMALE HOURLY RATE" t:dataTypeName=number

metric m:average_of_female_longevity_by_months p:float l:"Average of FEMALE LONGEVITY BY MONTHS" t:dataTypeName=number

metric m:average_of_male_hourly_rate p:float l:"Average of MALE HOURLY RATE" t:dataTypeName=number

metric m:average_of_male_longevity_by_months p:float l:"Average of MALE LONGEVITY BY MONTHS" t:dataTypeName=number

metric m:average_of_hourly_rate p:float l:"Average of HOURLY RATE" t:dataTypeName=number

metric m:average_of_longevity_by_months p:float l:"Average of LONGEVITY BY MONTHS" t:dataTypeName=number

metric m:womens_hourly_rate_compared_to_men_s_pay_rate_in_the_same_title p:double l:"% womens hourly rate compared to men's pay rate in the same title" t:dataTypeName=percent

metric m:womens_longevity_compared_to_men_s_pay_rate_in_the_same_title p:decimal l:"% womens longevity compared to men's pay rate in the same title" t:dataTypeName=percent

entity e:tptv-57gf l:"City of Seattle Wages:  Comparison by Gender - Discretionary Pay Titles" t:url=https://data.seattle.gov/api/views/tptv-57gf

property e:tptv-57gf t:meta.view v:id=tptv-57gf v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-5-Final.pdf v:averageRating=0 v:name="City of Seattle Wages:  Comparison by Gender - Discretionary Pay Titles"

property e:tptv-57gf t:meta.view.license v:name="Public Domain"

property e:tptv-57gf t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:tptv-57gf t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | job_type                  | average_of_female_hourly_rate | count_of_women_in_job_type | average_of_female_longevity_by_months | average_of_male_hourly_rate | count_of_men_in_job_type | average_of_male_longevity_by_months | average_of_hourly_rate | total_count_of_women_in_job_type | average_of_longevity_by_months | womens_hourly_rate_compared_to_men_s_pay_rate_in_the_same_title | womens_longevity_compared_to_men_s_pay_rate_in_the_same_title | notes             | 
| =========== | ========================= | ============================= | ========================== | ===================================== | =========================== | ======================== | =================================== | ====================== | ================================ | ============================== | =============================================================== | ============================================================= | ================= | 
| 1373984051  | City Attorney,Asst        | 45.20                         | 53                         | 50.74                                 | 51.61                       | 38                       | 60.61                               | 47.88                  | 91                               | 54.86                          | 0.87573862336599873                                             | 0.83715252459876022                                           |                   | 
| 1373984051  | City Light Supt           |                               |                            |                                       | 117.32                      | 1                        | 111.00                              | 117.32                 | 1                                | 111.00                         |                                                                 |                                                               | no women in title | 
| 1373984051  | Electric Util Exec 2      |                               |                            |                                       | 77.80                       | 3                        | 21.00                               | 77.80                  | 3                                | 21.00                          |                                                                 |                                                               | no women in title | 
| 1373984051  | Electric Util Exec 3,Dir  | 86.34                         | 1                          | 64.00                                 | 86.81                       | 6                        | 35.67                               | 86.75                  | 7                                | 39.71                          | 0.99449163378003858                                             | 1.7943925233644862                                            |                   | 
| 1373984051  | Electric Util Exec 3,Ofcr |                               |                            |                                       | 107.39                      | 2                        | 24.50                               | 107.39                 | 2                                | 24.50                          |                                                                 |                                                               | no women in title | 
| 1373984051  | Exec Manager-City Auditor |                               |                            |                                       | 65.26                       | 1                        | 41.00                               | 65.26                  | 1                                | 41.00                          |                                                                 |                                                               | no women in title | 
| 1373984051  | Exec Manager-Legislative  | 63.87                         | 1                          | 34.00                                 | 64.70                       | 1                        | 85.00                               | 64.28                  | 2                                | 59.50                          | 0.98709448076536699                                             | 0.4                                                           |                   | 
| 1373984051  | Hearing Examiner          | 65.98                         | 2                          | 168.00                                |                             |                          |                                     | 65.98                  | 2                                | 168.00                         |                                                                 |                                                               | no men in title   | 
| 1373984051  | Executive1                | 57.91                         | 4                          | 33.75                                 | 56.59                       | 6                        | 40.67                               | 57.11                  | 10                               | 37.90                          | 1.0233287287529047                                              | 0.82991803278688525                                           |                   | 
| 1373984051  | Executive2                | 63.18                         | 45                         | 58.51                                 | 63.94                       | 44                       | 57.75                               | 63.55                  | 89                               | 58.13                          | 0.98815054313799044                                             | 1.0131794131794132                                            |                   | 
```