# IDPH Life Expectancy at Birth by Sex for Illinois, Chicago and Illinois Counties: 1989-1991, 1999-2001 and 2009-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-life-expectancy-at-birth-by-sex-for-illinois-chicago-and-illinois-counties-1989-2009--48c29) |
| Metadata | [Link](https://data.illinois.gov/api/views/49qc-qnap) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/49qc-qnap/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/49qc-qnap/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 49qc-qnap |
| Name | IDPH Life Expectancy at Birth by Sex for Illinois, Chicago and Illinois Counties: 1989-1991, 1999-2001 and 2009-2011 |
| Attribution | Illinois Department of Public Health, Illinois Health Facilities and Services Review Board, Certificate of Need Population Projections Project |
| Category | Social/Healthcare |
| Tags | life expectancy, idph |
| Created | 2015-09-15T18:57:56Z |
| Publication Date | 2015-09-15T19:10:48Z |

## Description

There are two types of life tables ?cohort/generational and current/period life tables.
Cohort life tables are constructed using the mortality experience of the cohort and may not be
useful for the cohort itself because every member of the cohort has to die before such a table can
be constructed. A current or period life table uses current mortality experience applied to a
cohort of births to compute the life table. On the basis of age intervals, life tables are classified as
complete or abridged. A complete life table uses exact single years and an abridged life table
uses age intervals. This report presents five-year age interval abridged current life tables.
Computation of an abridged life table from which life expectancy is derived requires
mainly population and death data by age and sex. In this report, population data consist of the
1990, 2000, and 2010 census counts of residents of each Illinois County and the city of Chicago.
These data were aggregated into five-year age groups and by sex and used as denominators in
computing mortality rates. The death data were received from the Illinois Center for Health
Statistics (ICHS) of the Office of Health Informatics (OHI). ICHS receives these data from the
Illinois Vital Records System (IVRS). Number of deaths by sex and specific age for each county
were obtained from 1989 to 2011 and aggregated at county level by five-year age groups for
each sex. Three-year averages were then computed for the periods 1989-1991, 1999-2001, and
2009-2011 and were used as numerators in computing mortality rates.
The overall life tables were constructed using Chiang?s (1984) Method II. This method
assumes a homogeneous population in which all individuals are subjected to the same force of
mortality, and in which survival of an individual is independent of the survival of any other
individual in the group. The method does not remove fluctuations in observed data; therefore, the 
2
produced life tables exhibit more the factual mortality pattern in the actual data and less the
underlying mortality picture of the populations. Margin of errors were computed to provide basis
for evaluating the accuracy of the estimated life expectancies.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                     | Data Type | Render Type |
| ======== | ============== | ================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | state_city_county                  | State/City/County                        | text      | text        |
| Yes      | numeric metric | life_expectancy_year_1990_both_sex | Life Expectancy (Year 1990) Both Sex     | number    | number      |
| Yes      | numeric metric | margin_of_error_year_1990_both_sex | Margin of Error (?) (Year 1990) Both Sex | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2000_both_sex | Life Expectancy (Year 2000) Both Sex     | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2000_both_sex | Margin of Error (?) (Year 2000) Both Sex | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2010_both_sex | Life Expectancy (Year 2010) Both Sex     | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2010_both_sex | Margin of Error (?) (Year 2010) Both Sex | number    | number      |
| Yes      | numeric metric | life_expectancy_year_1990_male     | Life Expectancy (Year 1990) Male         | number    | number      |
| Yes      | numeric metric | margin_of_error_year_1990_male     | Margin of Error (?)(Year 1990) Male      | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2000_male     | Life Expectancy. (Year 2000) Male        | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2000_male     | Margin of Error (?) (Year 2000) Male     | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2010_male     | Life Expectancy (Year 2010) Male         | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2010_male     | Margin of Error (?) (Year 2010) Male     | number    | number      |
| Yes      | numeric metric | life_expectancy_year_1990_female   | Life Expectancy (Year 1990) Female       | number    | number      |
| Yes      | numeric metric | margin_of_error_year_1990_female   | Margin of Error (?) (Year 1990) Female   | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2000_female   | Life Expectancy (Year 2000) Female       | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2000_female   | Margin of Error (?) (Year 2000) Female   | number    | number      |
| Yes      | numeric metric | life_expectancy_year_2010_female   | Life Expectancy (Year 2010) Female       | number    | number      |
| Yes      | numeric metric | margin_of_error_year_2010_female   | Margin of Error (?) (Year 2010) Female   | number    | number      |
```

## Time Field

```ls
Value = 1989
Format & Zone = yyyy
```

## Data Commands

```ls
series e:49qc-qnap d:1989-01-01T00:00:00.000Z t:state_city_county=ILLINOIS m:margin_of_error_year_1990_male=0.13 m:life_expectancy_year_2010_both_sex=79.19 m:margin_of_error_year_1990_both_sex=0.09 m:life_expectancy_year_1990_female=78.37 m:margin_of_error_year_2000_male=0.12 m:life_expectancy_year_1990_both_sex=74.94 m:margin_of_error_year_2010_both_sex=0.08 m:margin_of_error_year_2010_male=0.12 m:life_expectancy_year_1990_male=71.37 m:margin_of_error_year_2000_both_sex=0.08 m:life_expectancy_year_2000_both_sex=76.79 m:margin_of_error_year_1990_female=0.12 m:margin_of_error_year_2010_female=0.11 m:life_expectancy_year_2000_female=79.5 m:life_expectancy_year_2010_male=76.64 m:life_expectancy_year_2000_male=73.96 m:margin_of_error_year_2000_female=1.13 m:life_expectancy_year_2010_female=81.59

series e:49qc-qnap d:1989-01-01T00:00:00.000Z t:state_city_county=CHICAGO m:margin_of_error_year_1990_male=0.3 m:life_expectancy_year_2010_both_sex=77.77 m:margin_of_error_year_1990_both_sex=0.21 m:life_expectancy_year_1990_female=75.1 m:margin_of_error_year_2000_male=0.28 m:life_expectancy_year_1990_both_sex=70.51 m:margin_of_error_year_2010_both_sex=0.2 m:margin_of_error_year_2010_male=0.28 m:life_expectancy_year_1990_male=65.94 m:margin_of_error_year_2000_both_sex=0.21 m:life_expectancy_year_2000_both_sex=74.17 m:margin_of_error_year_1990_female=0.29 m:margin_of_error_year_2010_female=0.26 m:life_expectancy_year_2000_female=77.68 m:life_expectancy_year_2010_male=74.55 m:life_expectancy_year_2000_male=70.52 m:margin_of_error_year_2000_female=0.26 m:life_expectancy_year_2010_female=80.81

series e:49qc-qnap d:1989-01-01T00:00:00.000Z t:state_city_county=Adams m:margin_of_error_year_1990_male=1.61 m:life_expectancy_year_2010_both_sex=78.86 m:margin_of_error_year_1990_both_sex=1.13 m:life_expectancy_year_1990_female=79.87 m:margin_of_error_year_2000_male=1.48 m:life_expectancy_year_1990_both_sex=75.61 m:margin_of_error_year_2010_both_sex=1.03 m:margin_of_error_year_2010_male=1.48 m:life_expectancy_year_1990_male=71.45 m:margin_of_error_year_2000_both_sex=1.07 m:life_expectancy_year_2000_both_sex=77.62 m:margin_of_error_year_1990_female=1.5 m:margin_of_error_year_2010_female=1.37 m:life_expectancy_year_2000_female=80.83 m:life_expectancy_year_2010_male=75.61 m:life_expectancy_year_2000_male=74.43 m:margin_of_error_year_2000_female=1.5 m:life_expectancy_year_2010_female=82.26
```

## Meta Commands

```ls
metric m:life_expectancy_year_1990_both_sex p:float l:"Life Expectancy (Year 1990) Both Sex" t:dataTypeName=number

metric m:margin_of_error_year_1990_both_sex p:float l:"Margin of Error (?) (Year 1990) Both Sex" t:dataTypeName=number

metric m:life_expectancy_year_2000_both_sex p:float l:"Life Expectancy (Year 2000) Both Sex" t:dataTypeName=number

metric m:margin_of_error_year_2000_both_sex p:float l:"Margin of Error (?) (Year 2000) Both Sex" t:dataTypeName=number

metric m:life_expectancy_year_2010_both_sex p:float l:"Life Expectancy (Year 2010) Both Sex" t:dataTypeName=number

metric m:margin_of_error_year_2010_both_sex p:float l:"Margin of Error (?) (Year 2010) Both Sex" t:dataTypeName=number

metric m:life_expectancy_year_1990_male p:float l:"Life Expectancy (Year 1990) Male" t:dataTypeName=number

metric m:margin_of_error_year_1990_male p:float l:"Margin of Error (?)(Year 1990) Male" t:dataTypeName=number

metric m:life_expectancy_year_2000_male p:float l:"Life Expectancy. (Year 2000) Male" t:dataTypeName=number

metric m:margin_of_error_year_2000_male p:float l:"Margin of Error (?) (Year 2000) Male" t:dataTypeName=number

metric m:life_expectancy_year_2010_male p:float l:"Life Expectancy (Year 2010) Male" t:dataTypeName=number

metric m:margin_of_error_year_2010_male p:float l:"Margin of Error (?) (Year 2010) Male" t:dataTypeName=number

metric m:life_expectancy_year_1990_female p:float l:"Life Expectancy (Year 1990) Female" t:dataTypeName=number

metric m:margin_of_error_year_1990_female p:float l:"Margin of Error (?) (Year 1990) Female" t:dataTypeName=number

metric m:life_expectancy_year_2000_female p:float l:"Life Expectancy (Year 2000) Female" t:dataTypeName=number

metric m:margin_of_error_year_2000_female p:float l:"Margin of Error (?) (Year 2000) Female" t:dataTypeName=number

metric m:life_expectancy_year_2010_female p:float l:"Life Expectancy (Year 2010) Female" t:dataTypeName=number

metric m:margin_of_error_year_2010_female p:float l:"Margin of Error (?) (Year 2010) Female" t:dataTypeName=number

entity e:49qc-qnap l:"IDPH Life Expectancy at Birth by Sex for Illinois, Chicago and Illinois Counties: 1989-1991, 1999-2001 and 2009-2011" t:attribution="Illinois Department of Public Health, Illinois Health Facilities and Services Review Board, Certificate of Need Population Projections Project" t:url=https://data.illinois.gov/api/views/49qc-qnap

property e:49qc-qnap t:meta.view v:id=49qc-qnap v:category=Social/Healthcare v:averageRating=0 v:name="IDPH Life Expectancy at Birth by Sex for Illinois, Chicago and Illinois Counties: 1989-1991, 1999-2001 and 2009-2011" v:attribution="Illinois Department of Public Health, Illinois Health Facilities and Services Review Board, Certificate of Need Population Projections Project"

property e:49qc-qnap t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:49qc-qnap t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| state_city_county | life_expectancy_year_1990_both_sex | margin_of_error_year_1990_both_sex | life_expectancy_year_2000_both_sex | margin_of_error_year_2000_both_sex | life_expectancy_year_2010_both_sex | margin_of_error_year_2010_both_sex | life_expectancy_year_1990_male | margin_of_error_year_1990_male | life_expectancy_year_2000_male | margin_of_error_year_2000_male | life_expectancy_year_2010_male | margin_of_error_year_2010_male | life_expectancy_year_1990_female | margin_of_error_year_1990_female | life_expectancy_year_2000_female | margin_of_error_year_2000_female | life_expectancy_year_2010_female | margin_of_error_year_2010_female | 
| ================= | ================================== | ================================== | ================================== | ================================== | ================================== | ================================== | ============================== | ============================== | ============================== | ============================== | ============================== | ============================== | ================================ | ================================ | ================================ | ================================ | ================================ | ================================ | 
| ILLINOIS          | 74.94                              | 0.09                               | 76.79                              | 0.08                               | 79.19                              | 0.08                               | 71.37                          | 0.13                           | 73.96                          | 0.12                           | 76.64                          | 0.12                           | 78.37                            | 0.12                             | 79.50                            | 1.13                             | 81.59                            | 0.11                             | 
| CHICAGO           | 70.51                              | 0.21                               | 74.17                              | 0.21                               | 77.77                              | 0.20                               | 65.94                          | 0.30                           | 70.52                          | 0.28                           | 74.55                          | 0.28                           | 75.10                            | 0.29                             | 77.68                            | 0.26                             | 80.81                            | 0.26                             | 
| Adams             | 75.61                              | 1.13                               | 77.62                              | 1.07                               | 78.86                              | 1.03                               | 71.45                          | 1.61                           | 74.43                          | 1.48                           | 75.61                          | 1.48                           | 79.87                            | 1.50                             | 80.83                            | 1.50                             | 82.26                            | 1.37                             | 
| Alexander         | 70.99                              | 3.18                               | 75.22                              | 3.12                               | 74.26                              | 3.43                               | 66.29                          | 4.74                           | 72.05                          | 4.54                           | 71.30                          | 5.08                           | 75.62                            | 4.10                             | 78.35                            | 4.08                             | 77.88                            | 4.44                             | 
| Bond              | 75.46                              | 2.63                               | 77.68                              | 2.19                               | 78.50                              | 2.15                               | 72.39                          | 3.64                           | 75.68                          | 3.08                           | 75.83                          | 3.07                           | 78.51                            | 3.72                             | 79.90                            | 2.96                             | 81.18                            | 2.92                             | 
| Boone             | 76.04                              | 1.67                               | 78.22                              | 1.32                               | 80.26                              | 1.28                               | 73.11                          | 2.39                           | 75.85                          | 1.87                           | 78.04                          | 1.83                           | 78.95                            | 2.23                             | 80.54                            | 1.80                             | 82.43                            | 1.71                             | 
| Brown             | 76.22                              | 3.77                               | 81.44                              | 2.72                               | 79.24                              | 2.86                               | 72.61                          | 4.78                           | 80.21                          | 3.81                           | 76.31                          | 3.86                           | 80.26                            | 5.72                             | 82.45                            | 3.79                             | 82.82                            | 3.97                             | 
| Bureau            | 76.54                              | 1.58                               | 78.51                              | 1.46                               | 79.47                              | 1.58                               | 72.52                          | 2.23                           | 75.94                          | 2.04                           | 76.72                          | 2.33                           | 80.63                            | 2.11                             | 80.88                            | 1.98                             | 82.19                            | 2.06                             | 
| Calhoun           | 75.22                              | 4.78                               | 76.22                              | 4.12                               | 80.60                              | 3.50                               | 71.58                          | 6.25                           | 74.86                          | 6.03                           | 78.92                          | 5.19                           | 79.17                            | 7.27                             | 77.73                            | 5.52                             | 82.43                            | 4.65                             | 
| Carroll           | 76.07                              | 2.24                               | 76.90                              | 2.41                               | 78.51                              | 2.48                               | 73.34                          | 3.24                           | 74.86                          | 3.26                           | 75.51                          | 3.76                           | 78.82                            | 2.93                             | 78.81                            | 3.62                             | 81.68                            | 2.98                             | 
```