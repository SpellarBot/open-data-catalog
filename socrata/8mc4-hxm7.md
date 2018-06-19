# Choose Maryland: Compare States - Demographics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-demographics) |
| Metadata | [Link](https://data.maryland.gov/api/views/8mc4-hxm7) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8mc4-hxm7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8mc4-hxm7/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8mc4-hxm7 |
| Name | Choose Maryland: Compare States - Demographics |
| Attribution | Maryland Department of Commerce |
| Category | Demographic |
| Tags | maryland, state, compare, demographic, population, income |
| Created | 2013-08-20T13:29:47Z |
| Publication Date | 2017-03-29T16:01:39Z |

## Description

Population profile - total, rate of change, age, and density.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                                   | Data Type | Render Type |
| ======== | ============== | ============================== | ====================================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | state                          | State                                  | text      | text        |
| Yes      | numeric metric | total_population_current       | Total Population, 2016                 | number    | number      |
| Yes      | numeric metric | total_population_previousyear1 | Total Population, 2010                 | number    | number      |
| Yes      | numeric metric | total_population_previousyear2 | Total Population, 2000                 | number    | number      |
| Yes      | numeric metric | pop_perc_change_years1         | Population Change, 2000-2010 (%)       | percent   | percent     |
| Yes      | numeric metric | median_age                     | Median Age                             | number    | number      |
| Yes      | numeric metric | population_density             | Population Density per Square Mile     | number    | number      |
| Yes      | numeric metric | median_household_income        | Median Household Income ($ Dollars)    | money     | money       |
| Yes      | numeric metric | percapita_personal_income      | Per Capita Personal Income ($ Dollars) | money     | money       |
| Yes      | numeric metric | poverty_rate                   | Poverty Rate (%)                       | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8mc4-hxm7 d:2017-03-29T16:01:10.000Z t:state=Alabama m:poverty_rate=18.5 m:median_household_income=44765 m:total_population_current=4863300 m:population_density=95.2 m:percapita_personal_income=39231 m:pop_perc_change_years1=7.5 m:total_population_previousyear2=4447100 m:median_age=38.7 m:total_population_previousyear1=4779736

series e:8mc4-hxm7 d:2017-03-29T16:01:10.000Z t:state=Alaska m:poverty_rate=10.3 m:median_household_income=73355 m:total_population_current=741894 m:population_density=1.3 m:percapita_personal_income=55307 m:pop_perc_change_years1=13.3 m:total_population_previousyear2=626932 m:median_age=33.3 m:total_population_previousyear1=710231

series e:8mc4-hxm7 d:2017-03-29T16:01:10.000Z t:state=Arizona m:poverty_rate=17.4 m:median_household_income=51492 m:total_population_current=6931071 m:population_density=57.7 m:percapita_personal_income=40243 m:pop_perc_change_years1=24.6 m:total_population_previousyear2=5130632 m:median_age=37.3 m:total_population_previousyear1=6392017
```

## Meta Commands

```ls
metric m:total_population_current p:integer l:"Total Population, 2016" t:dataTypeName=number

metric m:total_population_previousyear1 p:integer l:"Total Population, 2010" t:dataTypeName=number

metric m:total_population_previousyear2 p:integer l:"Total Population, 2000" t:dataTypeName=number

metric m:pop_perc_change_years1 p:float l:"Population Change, 2000-2010 (%)" t:dataTypeName=percent

metric m:median_age p:float l:"Median Age" t:dataTypeName=number

metric m:population_density p:float l:"Population Density per Square Mile" t:dataTypeName=number

metric m:median_household_income p:integer l:"Median Household Income ($ Dollars)" t:dataTypeName=money

metric m:percapita_personal_income p:integer l:"Per Capita Personal Income ($ Dollars)" t:dataTypeName=money

metric m:poverty_rate p:float l:"Poverty Rate (%)" t:dataTypeName=percent

entity e:8mc4-hxm7 l:"Choose Maryland:  Compare States - Demographics" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/8mc4-hxm7

property e:8mc4-hxm7 t:meta.view v:id=8mc4-hxm7 v:category=Demographic v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Demographics" v:attribution="Maryland Department of Commerce"

property e:8mc4-hxm7 t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:8mc4-hxm7 t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | total_population_current | total_population_previousyear1 | total_population_previousyear2 | pop_perc_change_years1 | median_age | population_density | median_household_income | percapita_personal_income | poverty_rate | 
| =========== | =========== | ======================== | ============================== | ============================== | ====================== | ========== | ================== | ======================= | ========================= | ============ | 
| 1490803270  | Alabama     | 4863300                  | 4779736                        | 4447100                        | 7.5                    | 38.7       | 95.2               | 44765                   | 39231                     | 18.5         | 
| 1490803270  | Alaska      | 741894                   | 710231                         | 626932                         | 13.3                   | 33.3       | 1.3                | 73355                   | 55307                     | 10.3         | 
| 1490803270  | Arizona     | 6931071                  | 6392017                        | 5130632                        | 24.6                   | 37.3       | 57.7               | 51492                   | 40243                     | 17.4         | 
| 1490803270  | Arkansas    | 2988248                  | 2915918                        | 2673400                        | 9.1                    | 37.9       | 56.7               | 41995                   | 39345                     | 19.1         | 
| 1490803270  | California  | 39250017                 | 37253956                       | 33871648                       | 10.0                   | 36.2       | 244.2              | 64500                   | 55987                     | 15.3         | 
| 1490803270  | Colorado    | 5540545                  | 5029196                        | 4301261                        | 16.9                   | 36.5       | 50.1               | 63909                   | 52059                     | 11.5         | 
| 1490803270  | Connecticut | 3576452                  | 3574097                        | 3405565                        | 4.9                    | 40.6       | 741.4              | 71346                   | 71033                     | 10.5         | 
| 1490803270  | Delaware    | 952065                   | 897934                         | 783600                         | 14.6                   | 40.0       | 470.6              | 61255                   | 48697                     | 12.4         | 
| 1490803270  | Florida     | 20612439                 | 18801310                       | 15982378                       | 17.6                   | 41.9       | 360.2              | 49426                   | 45819                     | 15.7         | 
| 1490803270  | Georgia     | 10310371                 | 9687653                        | 8186453                        | 18.3                   | 36.3       | 172.5              | 51244                   | 41835                     | 17.0         | 
```