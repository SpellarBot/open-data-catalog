# Choose Maryland: Compare Metros - Demographics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-metros-demographics) |
| Metadata | [Link](https://data.maryland.gov/api/views/h2qn-scd8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/h2qn-scd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/h2qn-scd8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | h2qn-scd8 |
| Name | Choose Maryland: Compare Metros - Demographics |
| Attribution | Maryland Department of Commerce |
| Category | Demographic |
| Tags | maryland, baltimore, metro, compare, population, income |
| Created | 2013-08-22T14:43:48Z |
| Publication Date | 2017-03-23T17:47:54Z |

## Description

Population and income profile - totals, median household.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                   | Data Type | Render Type |
| ======== | ============== | ================================== | ====================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | metro                              | Metro                                  | text      | text        |
| Yes      | numeric metric | total_population_current           | Total Population, 2016                 | number    | number      |
| Yes      | numeric metric | total_population_previousyear1     | Total Population, 2010                 | number    | number      |
| Yes      | numeric metric | total_population_previousyear2     | Total Population, 2000                 | number    | number      |
| Yes      | numeric metric | population_perc_change_years1      | Population Change, 2000-2010 (%)       | percent   | percent     |
| Yes      | numeric metric | per_capita_personal_income_dollars | Per Capita Personal Income ($ Dollars) | money     | money       |
| Yes      | numeric metric | median_household_income_dollars    | Median Household Income ($ Dollars)    | money     | money       |
| Yes      | numeric metric | total_personal_income_thousands    | Total Personal Income ($ Thousands)    | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h2qn-scd8 d:2017-03-23T17:47:34.000Z t:metro="Atlanta metro" m:per_capita_personal_income_dollars=45092 m:median_household_income_dollars=60219 m:total_personal_income_thousands=257509958 m:total_population_current=5789700 m:population_perc_change_years1=24 m:total_population_previousyear2=4247981 m:total_population_previousyear1=5268860

series e:h2qn-scd8 d:2017-03-23T17:47:34.000Z t:metro="Austin, TX metro" m:per_capita_personal_income_dollars=51014 m:median_household_income_dollars=67195 m:total_personal_income_thousands=102072207 m:total_population_current=2056405 m:population_perc_change_years1=37.3 m:total_population_previousyear2=1249763 m:total_population_previousyear1=1716289

series e:h2qn-scd8 d:2017-03-23T17:47:34.000Z t:metro="Baltimore metro" m:per_capita_personal_income_dollars=55275 m:median_household_income_dollars=72520 m:total_personal_income_thousands=154626192 m:total_population_current=2798886 m:population_perc_change_years1=6.2 m:total_population_previousyear2=2552994 m:total_population_previousyear1=2710489
```

## Meta Commands

```ls
metric m:total_population_current p:integer l:"Total Population, 2016" t:dataTypeName=number

metric m:total_population_previousyear1 p:integer l:"Total Population, 2010" t:dataTypeName=number

metric m:total_population_previousyear2 p:integer l:"Total Population, 2000" t:dataTypeName=number

metric m:population_perc_change_years1 p:float l:"Population Change, 2000-2010 (%)" t:dataTypeName=percent

metric m:per_capita_personal_income_dollars p:integer l:"Per Capita Personal Income ($ Dollars)" t:dataTypeName=money

metric m:median_household_income_dollars p:integer l:"Median Household Income ($ Dollars)" t:dataTypeName=money

metric m:total_personal_income_thousands p:integer l:"Total Personal Income ($ Thousands)" t:dataTypeName=money

entity e:h2qn-scd8 l:"Choose Maryland:  Compare Metros - Demographics" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/h2qn-scd8

property e:h2qn-scd8 t:meta.view v:id=h2qn-scd8 v:category=Demographic v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Metros - Demographics" v:attribution="Maryland Department of Commerce"

property e:h2qn-scd8 t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:h2qn-scd8 t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | metro               | total_population_current | total_population_previousyear1 | total_population_previousyear2 | population_perc_change_years1 | per_capita_personal_income_dollars | median_household_income_dollars | total_personal_income_thousands | 
| =========== | =================== | ======================== | ============================== | ============================== | ============================= | ================================== | =============================== | =============================== | 
| 1490291254  | Atlanta metro       | 5789700                  | 5268860                        | 4247981                        | 24.0                          | 45092                              | 60219                           | 257509958                       | 
| 1490291254  | Austin, TX metro    | 2056405                  | 1716289                        | 1249763                        | 37.3                          | 51014                              | 67195                           | 102072207                       | 
| 1490291254  | Baltimore metro     | 2798886                  | 2710489                        | 2552994                        | 6.2                           | 55275                              | 72520                           | 154626192                       | 
| 1490291254  | Birmingham metro    | 1147417                  | 1128047                        | 1052238                        | 7.2                           | 44568                              | 51459                           | 51059479                        | 
| 1490291254  | Boston metro        | 4794447                  | 4552402                        | 4391344                        | 3.7                           | 68292                              | 78800                           | 326045620                       | 
| 1490291254  | Buffalo metro       | 1132804                  | 1135509                        | 1170111                        | -3.0                          | 45769                              | 51772                           | 51958323                        | 
| 1490291254  | Charlotte metro     | 2474314                  | 1758038                        | 1330448                        | 32.1                          | 44935                              | 54836                           | 109028252                       | 
| 1490291254  | Chicago metro       | 9512999                  | 9461105                        | 9098316                        | 4.0                           | 53886                              | 63153                           | 514662122                       | 
| 1490291254  | Cincinnati metro    | 2165139                  | 2130151                        | 2009632                        | 6.0                           | 47254                              | 56826                           | 101960460                       | 
| 1490291254  | Cleveland, OH metro | 2055612                  | 2077240                        | 2148143                        | -3.3                          | 47783                              | 51049                           | 98472481                        | 
```