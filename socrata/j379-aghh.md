# City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-average-hourly-wage-by-department-382fb) |
| Metadata | [Link](https://data.seattle.gov/api/views/j379-aghh) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/j379-aghh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/j379-aghh/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | j379-aghh |
| Name | City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T18:44:36Z |
| Publication Date | 2013-07-16T18:46:12Z |

## Description

Average hourly wages for women and men sorted by City department and age range

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================ | ============================================================== | ========= | =========== |
| No       | time           | :updated_at                                                  | updated_at                                                     | meta_data | meta_data   |
| Yes      | series tag     | department                                                   | Department                                                     | text      | text        |
| Yes      | series tag     | jobtitle                                                     | Jobtitle                                                       | text      | text        |
| Yes      | numeric metric | female_avg_hrly_rate                                         | Female Avg Hrly Rate                                           | number    | number      |
| Yes      | numeric metric | no_female_empl                                               | No. Female Empl                                                | number    | number      |
| Yes      | numeric metric | male_avg_hrly_rate                                           | Male Avg Hrly Rate                                             | number    | number      |
| Yes      | numeric metric | no_male_empl                                                 | No. Male Empl                                                  | number    | number      |
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
series e:j379-aghh d:2013-07-16T11:44:38.000Z t:jobtitle=Accountant t:department="Arts and Cultural Affairs" t:notes="No women in title" m:male_avg_hrly_rate=29.75 m:no_male_empl=1 m:total_average_of_months_longevity_in_current_classification=39 m:total_no_empl=1 m:total_avg_hrly_rate=29.75

series e:j379-aghh d:2013-07-16T11:44:38.000Z t:jobtitle="Actg Tech III" t:department="Arts and Cultural Affairs" t:notes="No men in title" m:female_avg_hrly_rate=26.79 m:no_female_empl=1 m:total_average_of_months_longevity_in_current_classification=56 m:total_no_empl=1 m:total_avg_hrly_rate=26.79

series e:j379-aghh d:2013-07-16T11:44:38.000Z t:jobtitle="Admin Spec III" t:department="Arts and Cultural Affairs" t:notes="No men in title" m:female_avg_hrly_rate=26.26 m:no_female_empl=1 m:total_average_of_months_longevity_in_current_classification=37 m:total_no_empl=1 m:total_avg_hrly_rate=26.26
```

## Meta Commands

```ls
metric m:female_avg_hrly_rate p:float l:"Female Avg Hrly Rate" t:dataTypeName=number

metric m:no_female_empl p:integer l:"No. Female Empl" t:dataTypeName=number

metric m:male_avg_hrly_rate p:float l:"Male Avg Hrly Rate" t:dataTypeName=number

metric m:no_male_empl p:integer l:"No. Male Empl" t:dataTypeName=number

metric m:total_avg_hrly_rate p:float l:"Total Avg Hrly Rate" t:dataTypeName=number

metric m:total_no_empl p:integer l:"Total No. Empl" t:dataTypeName=number

metric m:total_average_of_months_longevity_in_current_classification p:float l:"Total Average of MONTHS LONGEVITY IN CURRENT CLASSIFICATION" t:dataTypeName=number

metric m:ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage p:float l:"Ratio of women's hourly rate to men's hourly rate - percentage" t:dataTypeName=percent

entity e:j379-aghh l:"City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department" t:url=https://data.seattle.gov/api/views/j379-aghh

property e:j379-aghh t:meta.view v:id=j379-aghh v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-2-Final.pdf v:averageRating=0 v:name="City of Seattle Wages: Comparison by Gender - Average Hourly Wage by Department"

property e:j379-aghh t:meta.view.license v:name="Public Domain"

property e:j379-aghh t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:j379-aghh t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | department                | jobtitle            | female_avg_hrly_rate | no_female_empl | male_avg_hrly_rate | no_male_empl | total_avg_hrly_rate | total_no_empl | total_average_of_months_longevity_in_current_classification | ratio_of_women_s_hourly_rate_to_men_s_hourly_rate_percentage | notes             | 
| =========== | ========================= | =================== | ==================== | ============== | ================== | ============ | =================== | ============= | =========================================================== | ============================================================ | ================= | 
| 1373975078  | Arts and Cultural Affairs | Accountant          |                      |                | 29.75              | 1            | 29.75               | 1             | 39.00                                                       |                                                              | No women in title | 
| 1373975078  | Arts and Cultural Affairs | Actg Tech III       | 26.79                | 1              |                    |              | 26.79               | 1             | 56.00                                                       |                                                              | No men in title   | 
| 1373975078  | Arts and Cultural Affairs | Admin Spec III      | 26.26                | 1              |                    |              | 26.26               | 1             | 37.00                                                       |                                                              | No men in title   | 
| 1373975078  | Arts and Cultural Affairs | Admin Staff Asst    | 31.76                | 2              |                    |              | 31.76               | 2             | 99.00                                                       |                                                              | No men in title   | 
| 1373975078  | Arts and Cultural Affairs | Arts Conserv Tech   | 27.78                | 1              | 27.78              | 1            | 27.78               | 2             | 65.00                                                       | 100.00                                                       |                   | 
| 1373975078  | Arts and Cultural Affairs | Arts Prgm Spec      | 32.35                | 5              |                    |              | 32.35               | 5             | 56.40                                                       |                                                              | No men in title   | 
| 1373975078  | Arts and Cultural Affairs | Arts Prgm Spec,Sr   | 35.93                | 3              | 36.30              | 1            | 36.02               | 4             | 62.50                                                       | 98.98                                                        |                   | 
| 1373975078  | Arts and Cultural Affairs | Events Booking Rep  |                      |                | 27.78              | 1            | 27.78               | 1             | 10.00                                                       |                                                              | No women in title | 
| 1373975078  | Arts and Cultural Affairs | Executive2          |                      |                | 51.95              | 1            | 51.95               | 1             | 7.00                                                        |                                                              | No women in title | 
| 1373975078  | Arts and Cultural Affairs | Info Technol Prof C |                      |                | 36.71              | 1            | 36.71               | 1             | 54.00                                                       |                                                              | No women in title | 
```