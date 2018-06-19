# Census Demographics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-demographics) |
| Metadata | [Link](https://data.brla.gov/api/views/xsrb-mxqt) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/xsrb-mxqt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/xsrb-mxqt/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | xsrb-mxqt |
| Name | Census Demographics |
| Attribution | Planning Commission |
| Category | Housing and Development |
| Tags | census, demographics, population |
| Created | 2015-04-29T02:23:12Z |
| Publication Date | 2015-08-05T16:49:40Z |

## Description

Summary statistics from the 2000 and 2010 United States Census including population, demographics, education, and housing information.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                                | Data Type | Render Type |
| ======== | ============== | ============================= | =================================== | ========= | =========== |
| Yes      | series tag     | unique_id                     | UNIQUE ID                           | text      | number      |
| Yes      | time           | census_year                   | CENSUS YEAR                         | number    | number      |
| Yes      | numeric metric | tract                         | TRACT                               | number    | text        |
| Yes      | series tag     | block_group                   | BLOCK GROUP                         | text      | number      |
| Yes      | series tag     | fips_id                       | FIPS ID                             | text      | number      |
| Yes      | numeric metric | total_population              | TOTAL POPULATION                    | number    | number      |
| Yes      | numeric metric | population_white              | POPULATION WHITE                    | number    | number      |
| Yes      | numeric metric | population_black              | POPULATION BLACK                    | number    | number      |
| Yes      | numeric metric | population_asian              | POPULATION ASIAN                    | number    | number      |
| Yes      | numeric metric | population_other              | POPULATION OTHER                    | number    | number      |
| Yes      | numeric metric | population_am_indian          | POPULATION AMERICAN INDIAN          | number    | number      |
| Yes      | numeric metric | population_pacf_island        | POPULATION PACIFIC ISLANDER         | number    | number      |
| Yes      | numeric metric | population_one_race           | POPULATION ONE RACE                 | number    | number      |
| Yes      | numeric metric | population_multi_race         | POPULATION MULTI RACE               | number    | number      |
| Yes      | numeric metric | population_25_older           | POPULATION 25 OLDER                 | number    | number      |
| Yes      | numeric metric | median_age                    | MEDIAN AGE                          | number    | number      |
| Yes      | numeric metric | median_household_income       | MEDIAN HOUSEHOLD INCOME             | number    | number      |
| Yes      | numeric metric | high_school_male              | HIGH SCHOOL MALE                    | number    | number      |
| Yes      | numeric metric | high_school_more_male         | HIGH SCHOOL MORE MALE               | number    | number      |
| Yes      | numeric metric | college_1yr_less_male         | COLLEGE 1 YR LESS MALE              | number    | number      |
| Yes      | numeric metric | college_1yr_more_male         | COLLEGE 1 YR MORE MALE              | number    | number      |
| Yes      | numeric metric | associates_degree_male        | ASSOCIATES DEGREE MALE              | number    | number      |
| Yes      | numeric metric | bachelors_degree_male         | BACHELORS DEGREE MALE               | number    | number      |
| Yes      | numeric metric | masters_degree_male           | MASTERS DEGREE MALE                 | number    | number      |
| Yes      | numeric metric | professional_degree_male      | PROFESSIONAL DEGREE MALE            | number    | number      |
| Yes      | numeric metric | doctoral_degree_male          | DOCTORAL DEGREE MALE                | number    | number      |
| Yes      | numeric metric | high_school_female            | HIGH SCHOOL FEMALE                  | number    | number      |
| Yes      | numeric metric | high_school_more_female       | HIGH SCHOOL MORE FEMALE             | number    | number      |
| Yes      | numeric metric | college_1yr_less_female       | COLLEGE 1 YR LESS FEMALE            | number    | number      |
| Yes      | numeric metric | college_1yr_more_female       | COLLEGE 1 YR MORE FEMALE            | number    | number      |
| Yes      | numeric metric | associates_degree_female      | ASSOCIATES DEGREE FEMALE            | number    | number      |
| Yes      | numeric metric | bachelors_degree_female       | BACHELORS DEGREE FEMALE             | number    | number      |
| Yes      | numeric metric | masters_degree_female         | MASTERS DEGREE FEMALE               | number    | number      |
| Yes      | numeric metric | professional_degree_female    | PROFESSIONAL DEGREE FEMALE          | number    | number      |
| Yes      | numeric metric | doctoral_degree_female        | DOCTORAL DEGREE FEMALE              | number    | number      |
| Yes      | numeric metric | pct_25yrover_high_school_more | PERCENT 25 YR OVER HIGH SCHOOL MORE | percent   | percent     |
| Yes      | numeric metric | housing_units                 | HOUSING UNITS                       | number    | number      |
| Yes      | numeric metric | occupied_housing_units        | OCCUPIED HOUSING UNITS              | number    | number      |
| Yes      | numeric metric | owner_occupied_housing        | OWNER OCCUPIED HOUSING              | number    | number      |
| Yes      | numeric metric | renter_occupied_housing       | RENTER OCCUPIED HOUSING             | number    | number      |
| Yes      | numeric metric | percent_owner_occupied        | PERCENT OWNER OCCUPIED              | percent   | percent     |
| Yes      | numeric metric | percent_renter_occupied       | PERCENT RENTER OCCUPIED             | percent   | percent     |
| Yes      | numeric metric | median_house_value_owner_occu | MEDIAN HOUSE VALUE OWNER OCCUPIED   | money     | money       |
| Yes      | numeric metric | median_year_built             | MEDIAN YEAR BUILT                   | number    | number      |
| Yes      | numeric metric | vacancy_rates                 | VACANCY RATES                       | percent   | percent     |
```

## Time Field

```ls
Value = census_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xsrb-mxqt d:2000-01-01T00:00:00.000Z t:unique_id=2000220330001001 t:fips_id=220330001001 t:block_group=1 m:occupied_housing_units=209 m:percent_renter_occupied=48 m:high_school_more_female=122 m:renter_occupied_housing=101 m:associates_degree_female=6 m:population_other=1 m:population_black=474 m:percent_owner_occupied=52 m:high_school_female=53 m:high_school_male=71 m:median_age=29.5 m:vacancy_rates=8.8 m:population_asian=0 m:median_house_value_owner_occu=43300 m:housing_units=242 m:college_1yr_more_male=26 m:population_white=107 m:college_1yr_more_female=55 m:pct_25yrover_high_school_more=39 m:owner_occupied_housing=108 m:median_household_income=30109 m:college_1yr_less_female=8 m:total_population=587 m:tract=1 m:population_25_older=347 m:masters_degree_male=7 m:population_am_indian=0 m:high_school_more_male=104 m:median_year_built=1969

series e:xsrb-mxqt d:2000-01-01T00:00:00.000Z t:unique_id=2000220330001002 t:fips_id=220330001002 t:block_group=2 m:occupied_housing_units=354 m:associates_degree_male=6 m:percent_renter_occupied=60 m:high_school_more_female=166 m:renter_occupied_housing=211 m:population_other=1 m:college_1yr_less_male=11 m:population_black=994 m:percent_owner_occupied=40 m:high_school_female=73 m:high_school_male=76 m:median_age=23.3 m:vacancy_rates=8.8 m:population_asian=4 m:median_house_value_owner_occu=40200 m:housing_units=382 m:college_1yr_more_male=31 m:population_white=71 m:college_1yr_more_female=78 m:pct_25yrover_high_school_more=27 m:owner_occupied_housing=143 m:median_household_income=23472 m:total_population=1088 m:tract=1 m:population_25_older=473 m:bachelors_degree_female=6 m:population_am_indian=0 m:high_school_more_male=124 m:masters_degree_female=9 m:median_year_built=1967

series e:xsrb-mxqt d:2000-01-01T00:00:00.000Z t:unique_id=2000220330002001 t:fips_id=220330002001 t:block_group=1 m:occupied_housing_units=511 m:percent_renter_occupied=46 m:bachelors_degree_male=11 m:population_black=875 m:high_school_female=199 m:median_age=33.2 m:population_asian=6 m:vacancy_rates=12.5 m:median_house_value_owner_occu=50900 m:housing_units=584 m:pct_25yrover_high_school_more=40 m:owner_occupied_housing=274 m:median_household_income=17552 m:college_1yr_less_female=37 m:median_year_built=1966 m:high_school_more_female=313 m:college_1yr_less_male=5 m:population_other=4 m:renter_occupied_housing=237 m:percent_owner_occupied=54 m:high_school_male=152 m:college_1yr_more_male=22 m:population_white=380 m:college_1yr_more_female=58 m:total_population=1273 m:tract=2 m:population_25_older=699 m:masters_degree_male=5 m:bachelors_degree_female=19 m:population_am_indian=4 m:high_school_more_male=195
```

## Meta Commands

```ls
metric m:tract p:integer l:TRACT d:"Census tract number" t:dataTypeName=number

metric m:total_population p:integer l:"TOTAL POPULATION" d:"Total population of the Census block group" t:dataTypeName=number

metric m:population_white p:integer l:"POPULATION WHITE" d:"Total white population of the block group" t:dataTypeName=number

metric m:population_black p:integer l:"POPULATION BLACK" d:"Total black population of the block group" t:dataTypeName=number

metric m:population_asian p:integer l:"POPULATION ASIAN" d:"Total Asian population of the block group" t:dataTypeName=number

metric m:population_other p:integer l:"POPULATION OTHER" d:"Total other population of the block group" t:dataTypeName=number

metric m:population_am_indian p:integer l:"POPULATION AMERICAN INDIAN" d:"Total American Indian population of the block group" t:dataTypeName=number

metric m:population_pacf_island p:integer l:"POPULATION PACIFIC ISLANDER" d:"Total population of Pacific Islanders" t:dataTypeName=number

metric m:population_one_race p:integer l:"POPULATION ONE RACE" d:"Total population of people of one race" t:dataTypeName=number

metric m:population_multi_race p:integer l:"POPULATION MULTI RACE" d:"Total population of people of multiple races" t:dataTypeName=number

metric m:population_25_older p:integer l:"POPULATION 25 OLDER" d:"Total population of the block group that is 25 years or older" t:dataTypeName=number

metric m:median_age p:float l:"MEDIAN AGE" d:"Median age of the block group" t:dataTypeName=number

metric m:median_household_income p:integer l:"MEDIAN HOUSEHOLD INCOME" d:"Median household income of the block group" t:dataTypeName=number

metric m:high_school_male p:integer l:"HIGH SCHOOL MALE" d:"Number of male high school graduates" t:dataTypeName=number

metric m:high_school_more_male p:integer l:"HIGH SCHOOL MORE MALE" d:"Number of males with more than a high school education" t:dataTypeName=number

metric m:college_1yr_less_male p:integer l:"COLLEGE 1 YR LESS MALE" d:"Number of males with less than one year of college education" t:dataTypeName=number

metric m:college_1yr_more_male p:integer l:"COLLEGE 1 YR MORE MALE" d:"Number of males with more than one year of college education" t:dataTypeName=number

metric m:associates_degree_male p:integer l:"ASSOCIATES DEGREE MALE" d:"Number of males with an associates degree" t:dataTypeName=number

metric m:bachelors_degree_male p:integer l:"BACHELORS DEGREE MALE" d:"Number of males with a bachelors degree" t:dataTypeName=number

metric m:masters_degree_male p:integer l:"MASTERS DEGREE MALE" d:"Number of males with a masters degree" t:dataTypeName=number

metric m:professional_degree_male p:integer l:"PROFESSIONAL DEGREE MALE" d:"Number of males with a professional degree" t:dataTypeName=number

metric m:doctoral_degree_male p:integer l:"DOCTORAL DEGREE MALE" d:"Number of males with a doctoral degree" t:dataTypeName=number

metric m:high_school_female p:integer l:"HIGH SCHOOL FEMALE" d:"Number of female high school graduates" t:dataTypeName=number

metric m:high_school_more_female p:integer l:"HIGH SCHOOL MORE FEMALE" d:"Number of females with more than a high school education" t:dataTypeName=number

metric m:college_1yr_less_female p:integer l:"COLLEGE 1 YR LESS FEMALE" d:"Number of females with less than one year of college education" t:dataTypeName=number

metric m:college_1yr_more_female p:integer l:"COLLEGE 1 YR MORE FEMALE" d:"Number of females with more than one year of college education" t:dataTypeName=number

metric m:associates_degree_female p:integer l:"ASSOCIATES DEGREE FEMALE" d:"Number of females with an associates degree" t:dataTypeName=number

metric m:bachelors_degree_female p:integer l:"BACHELORS DEGREE FEMALE" d:"Number of females with a bachelors degree" t:dataTypeName=number

metric m:masters_degree_female p:integer l:"MASTERS DEGREE FEMALE" d:"Number of females with a masters degree" t:dataTypeName=number

metric m:professional_degree_female p:integer l:"PROFESSIONAL DEGREE FEMALE" d:"Number of females with a professional degree" t:dataTypeName=number

metric m:doctoral_degree_female p:integer l:"DOCTORAL DEGREE FEMALE" d:"Number of females with a doctoral degree" t:dataTypeName=number

metric m:pct_25yrover_high_school_more p:double l:"PERCENT 25 YR OVER HIGH SCHOOL MORE" d:"Percent of 25 year or older high school graduates" t:dataTypeName=percent

metric m:housing_units p:integer l:"HOUSING UNITS" d:"Number of housing units" t:dataTypeName=number

metric m:occupied_housing_units p:integer l:"OCCUPIED HOUSING UNITS" d:"Number of occupied housing units" t:dataTypeName=number

metric m:owner_occupied_housing p:integer l:"OWNER OCCUPIED HOUSING" d:"Number of owner occupied housing units" t:dataTypeName=number

metric m:renter_occupied_housing p:integer l:"RENTER OCCUPIED HOUSING" d:"Number of renter occupied housing units" t:dataTypeName=number

metric m:percent_owner_occupied p:double l:"PERCENT OWNER OCCUPIED" d:"Percent of owner occupied housing units" t:dataTypeName=percent

metric m:percent_renter_occupied p:double l:"PERCENT RENTER OCCUPIED" d:"Percent of renter occupied housing units" t:dataTypeName=percent

metric m:median_house_value_owner_occu p:integer l:"MEDIAN HOUSE VALUE OWNER OCCUPIED" d:"Median value of owner occupied housing units" t:dataTypeName=money

metric m:median_year_built p:integer l:"MEDIAN YEAR BUILT" d:"Median year housing unit was built" t:dataTypeName=number

metric m:vacancy_rates p:double l:"VACANCY RATES" d:"Rate of housing unit vacancy" t:dataTypeName=percent

entity e:xsrb-mxqt l:"Census Demographics" t:attribution="Planning Commission" t:url=https://data.brla.gov/api/views/xsrb-mxqt

property e:xsrb-mxqt t:meta.view v:id=xsrb-mxqt v:category="Housing and Development" v:attributionLink=http://www.brgov.com/dept/planning v:averageRating=0 v:name="Census Demographics" v:attribution="Planning Commission"

property e:xsrb-mxqt t:meta.view.license v:name="Public Domain"

property e:xsrb-mxqt t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:xsrb-mxqt t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| unique_id        | census_year | tract | block_group | fips_id      | total_population | population_white | population_black | population_asian | population_other | population_am_indian | population_pacf_island | population_one_race | population_multi_race | population_25_older | median_age         | median_household_income | high_school_male | high_school_more_male | college_1yr_less_male | college_1yr_more_male | associates_degree_male | bachelors_degree_male | masters_degree_male | professional_degree_male | doctoral_degree_male | high_school_female | high_school_more_female | college_1yr_less_female | college_1yr_more_female | associates_degree_female | bachelors_degree_female | masters_degree_female | professional_degree_female | doctoral_degree_female | pct_25yrover_high_school_more | housing_units | occupied_housing_units | owner_occupied_housing | renter_occupied_housing | percent_owner_occupied | percent_renter_occupied | median_house_value_owner_occu | median_year_built | vacancy_rates      | 
| ================ | =========== | ===== | =========== | ============ | ================ | ================ | ================ | ================ | ================ | ==================== | ====================== | =================== | ===================== | =================== | ================== | ======================= | ================ | ===================== | ===================== | ===================== | ====================== | ===================== | =================== | ======================== | ==================== | ================== | ======================= | ======================= | ======================= | ======================== | ======================= | ===================== | ========================== | ====================== | ============================= | ============= | ====================== | ====================== | ======================= | ====================== | ======================= | ============================= | ================= | ================== | 
| 2000220330001001 | 2000        | 1     | 1           | 220330001001 | 587              | 107              | 474              | 0                | 1                | 0                    |                        |                     |                       | 347                 | 29.5               | 30109                   | 71               | 104                   |                       | 26                    |                        |                       | 7                   |                          |                      | 53                 | 122                     | 8                       | 55                      | 6                        |                         |                       |                            |                        | 39                            | 242           | 209                    | 108                    | 101                     | 52                     | 48                      | 43300                         | 1969              | 8.8000000000000007 | 
| 2000220330001002 | 2000        | 1     | 2           | 220330001002 | 1088             | 71               | 994              | 4                | 1                | 0                    |                        |                     |                       | 473                 | 23.3               | 23472                   | 76               | 124                   | 11                    | 31                    | 6                      |                       |                     |                          |                      | 73                 | 166                     |                         | 78                      |                          | 6                       | 9                     |                            |                        | 27                            | 382           | 354                    | 143                    | 211                     | 40                     | 60                      | 40200                         | 1967              | 8.8000000000000007 | 
| 2000220330002001 | 2000        | 2     | 1           | 220330002001 | 1273             | 380              | 875              | 6                | 4                | 4                    |                        |                     |                       | 699                 | 33.200000000000003 | 17552                   | 152              | 195                   | 5                     | 22                    |                        | 11                    | 5                   |                          |                      | 199                | 313                     | 37                      | 58                      |                          | 19                      |                       |                            |                        | 40                            | 584           | 511                    | 274                    | 237                     | 54                     | 46                      | 50900                         | 1966              | 12.5               | 
| 2000220330002002 | 2000        | 2     | 2           | 220330002002 | 1268             | 166              | 1094             | 1                | 0                | 0                    |                        |                     |                       | 627                 | 24                 | 17076                   | 52               | 118                   | 21                    | 37                    |                        | 8                     |                     |                          |                      | 108                | 256                     | 19                      | 82                      | 12                       | 17                      | 18                    |                            |                        | 29                            | 475           | 463                    | 188                    | 275                     | 41                     | 59                      | 50000                         | 1969              | 21.7               | 
| 2000220330002003 | 2000        | 2     | 3           | 220330002003 | 676              | 91               | 557              | 17               | 0                | 1                    |                        |                     |                       | 468                 | 44.4               | 10854                   | 59               | 154                   | 24                    | 63                    | 8                      |                       |                     |                          |                      | 47                 | 95                      | 12                      | 25                      |                          |                         | 11                    |                            |                        | 37                            | 375           | 330                    | 97                     | 233                     | 29                     | 71                      | 67100                         | 1981              | 17.899999999999999 | 
| 2000220330002004 | 2000        | 2     | 4           | 220330002004 | 997              | 109              | 883              | 0                | 2                | 2                    |                        |                     |                       | 382                 | 21.2               | 15573                   | 57               | 64                    |                       | 7                     |                        |                       |                     |                          |                      | 114                | 122                     |                         | 8                       |                          |                         |                       |                            |                        | 19                            | 306           | 278                    | 90                     | 188                     | 32                     | 68                      | 21300                         | 1955              | 0                  | 
| 2000220330002005 | 2000        | 2     | 5           | 220330002005 | 1040             | 132              | 896              | 0                | 4                | 1                    |                        |                     |                       | 606                 | 27.9               | 23750                   | 89               | 134                   | 19                    |                       |                        | 26                    |                     |                          |                      | 144                | 264                     | 57                      | 38                      |                          | 18                      | 7                     |                            |                        | 38                            | 393           | 369                    | 193                    | 176                     | 52                     | 48                      | 43600                         | 1961              | 7.9                | 
| 2000220330002006 | 2000        | 2     | 6           | 220330002006 | 1226             | 263              | 905              | 0                | 18               | 3                    |                        |                     |                       | 757                 | 27.7               | 20046                   | 132              | 218                   | 8                     | 69                    |                        | 9                     |                     |                          |                      | 163                | 242                     | 8                       | 45                      | 9                        | 5                       |                       |                            | 12                     | 38                            | 565           | 479                    | 226                    | 253                     | 47                     | 53                      | 45000                         | 1964              | 3                  | 
| 2000220330003001 | 2000        | 3     | 1           | 220330003001 | 1358             | 125              | 1223             | 0                | 7                | 2                    |                        |                     |                       | 682                 | 25.1               | 22227                   | 72               | 216                   | 9                     | 129                   |                        | 6                     |                     |                          |                      | 183                | 271                     | 46                      | 42                      |                          |                         |                       |                            |                        | 36                            | 474           | 435                    | 250                    | 185                     | 57                     | 43                      | 44500                         | 1963              | 20                 | 
| 2000220330003002 | 2000        | 3     | 2           | 220330003002 | 86               | 14               | 72               | 0                | 0                | 0                    |                        |                     |                       | 47                  | 40                 | 48750                   | 6                | 18                    |                       | 12                    |                        |                       |                     |                          |                      | 12                 | 22                      |                         | 10                      |                          |                         |                       |                            |                        | 47                            | 36            | 22                     | 22                     |                         | 100                    |                         | 24200                         | 1947              | 0                  | 
```