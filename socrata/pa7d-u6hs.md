# Choose Maryland: Compare Counties - Demographics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-demographics) |
| Metadata | [Link](https://data.maryland.gov/api/views/pa7d-u6hs) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pa7d-u6hs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pa7d-u6hs/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pa7d-u6hs |
| Name | Choose Maryland: Compare Counties - Demographics |
| Attribution | Maryland Department of Commerce |
| Category | Demographic |
| Tags | maryland, county, compare, demographic, population, age, income |
| Created | 2013-08-22T17:52:00Z |
| Publication Date | 2017-03-23T14:42:20Z |

## Description

Population profile - total, rate of change, age, and density.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                                   | Data Type | Render Type |
| ======== | ============== | ========================== | ====================================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                             | meta_data | meta_data   |
| Yes      | series tag     | county                     | County                                 | text      | text        |
| Yes      | numeric metric | total_pop_current          | Total Population, 2016                 | number    | number      |
| Yes      | numeric metric | total_pop_previousyear1    | Total Population, 2010                 | number    | number      |
| Yes      | numeric metric | total_pop_previousyear2    | Total Population, 2000                 | number    | number      |
| Yes      | numeric metric | pop_change_years1          | Population Change, 2000-2010           | number    | number      |
| Yes      | numeric metric | pop_perc_change_years1     | Population Change, 2000-2010 (%)       | percent   | percent     |
| Yes      | numeric metric | pop_density_sqmi           | Population Density per Square Mile     | number    | number      |
| Yes      | numeric metric | median_age                 | Median Age                             | number    | number      |
| Yes      | numeric metric | personal_income_per_capita | Per Capita Personal Income ($ Dollars) | money     | money       |
| Yes      | numeric metric | median_household_income    | Median Household Income ($ Dollars)    | money     | money       |
| Yes      | numeric metric | personal_income_total      | Total Personal Income ($ Thousands)    | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pa7d-u6hs d:2017-03-23T14:41:56.000Z t:county="Allegany County" m:total_pop_previousyear1=75087 m:total_pop_previousyear2=74909 m:median_household_income=39859 m:pop_change_years1=178 m:total_pop_current=72130 m:personal_income_per_capita=37214 m:pop_density_sqmi=177 m:pop_perc_change_years1=0.2 m:personal_income_total=2699036 m:median_age=41.1

series e:pa7d-u6hs d:2017-03-23T14:41:56.000Z t:county="Anne Arundel County" m:total_pop_previousyear1=537656 m:total_pop_previousyear2=489677 m:median_household_income=90825 m:pop_change_years1=47979 m:total_pop_current=568346 m:personal_income_per_capita=60628 m:pop_density_sqmi=1295.9 m:pop_perc_change_years1=9.8 m:personal_income_total=34205956 m:median_age=38.1

series e:pa7d-u6hs d:2017-03-23T14:41:56.000Z t:county="Baltimore City" m:total_pop_previousyear1=620961 m:total_pop_previousyear2=651262 m:median_household_income=43192 m:pop_change_years1=-30301 m:total_pop_current=614664 m:personal_income_per_capita=44979 m:pop_density_sqmi=7671.5 m:pop_perc_change_years1=-4.7 m:personal_income_total=27970414 m:median_age=34.7
```

## Meta Commands

```ls
metric m:total_pop_current p:integer l:"Total Population, 2016" t:dataTypeName=number

metric m:total_pop_previousyear1 p:integer l:"Total Population, 2010" t:dataTypeName=number

metric m:total_pop_previousyear2 p:integer l:"Total Population, 2000" t:dataTypeName=number

metric m:pop_change_years1 p:integer l:"Population Change, 2000-2010" t:dataTypeName=number

metric m:pop_perc_change_years1 p:float l:"Population Change, 2000-2010 (%)" t:dataTypeName=percent

metric m:pop_density_sqmi p:float l:"Population Density per Square Mile" t:dataTypeName=number

metric m:median_age p:float l:"Median Age" t:dataTypeName=number

metric m:personal_income_per_capita p:integer l:"Per Capita Personal Income ($ Dollars)" t:dataTypeName=money

metric m:median_household_income p:integer l:"Median Household Income ($ Dollars)" t:dataTypeName=money

metric m:personal_income_total p:integer l:"Total Personal Income ($ Thousands)" t:dataTypeName=money

entity e:pa7d-u6hs l:"Choose Maryland:  Compare Counties - Demographics" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/pa7d-u6hs

property e:pa7d-u6hs t:meta.view v:id=pa7d-u6hs v:category=Demographic v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Demographics" v:attribution="Maryland Department of Commerce"

property e:pa7d-u6hs t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:pa7d-u6hs t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | total_pop_current | total_pop_previousyear1 | total_pop_previousyear2 | pop_change_years1 | pop_perc_change_years1 | pop_density_sqmi | median_age | personal_income_per_capita | median_household_income | personal_income_total | 
| =========== | =================== | ================= | ======================= | ======================= | ================= | ====================== | ================ | ========== | ========================== | ======================= | ===================== | 
| 1490280116  | Allegany County     | 72130             | 75087                   | 74909                   | 178               | 0.2                    | 177.0            | 41.1       | 37214                      | 39859                   | 2699036               | 
| 1490280116  | Anne Arundel County | 568346            | 537656                  | 489677                  | 47979             | 9.8                    | 1295.9           | 38.1       | 60628                      | 90825                   | 34205956              | 
| 1490280116  | Baltimore City      | 614664            | 620961                  | 651262                  | -30301            | -4.7                   | 7671.5           | 34.7       | 44979                      | 43192                   | 27970414              | 
| 1490280116  | Baltimore County    | 831026            | 805029                  | 753947                  | 51082             | 6.8                    | 1345.5           | 39.3       | 54395                      | 68317                   | 45209531              | 
| 1490280116  | Calvert County      | 91251             | 88737                   | 74556                   | 14181             | 19.0                   | 416.3            | 40.7       | 56018                      | 98937                   | 5074942               | 
| 1490280116  | Caroline County     | 32850             | 33066                   | 29735                   | 3331              | 11.2                   | 103.5            | 40.0       | 42110                      | 51294                   | 1371907               | 
| 1490280116  | Carroll County      | 167656            | 167134                  | 150881                  | 16253             | 10.8                   | 373.4            | 42.7       | 56006                      | 84506                   | 9388083               | 
| 1490280116  | Cecil County        | 102603            | 101108                  | 85964                   | 15144             | 17.6                   | 292.0            | 40.2       | 43374                      | 68972                   | 4440668               | 
| 1490280116  | Charles County      | 157705            | 146551                  | 120524                  | 26027             | 21.6                   | 320.2            | 37.8       | 52212                      | 87941                   | 8151227               | 
| 1490280116  | Dorchester County   | 32258             | 32618                   | 30671                   | 1947              | 6.3                    | 60.3             | 44.2       | 41553                      | 44664                   | 1345651               | 
```