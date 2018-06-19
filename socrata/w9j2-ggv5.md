# NCHS - Age-adjusted death rates and life-expectancy at birth, (All Races, Both Sexes): United States, 1900-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/age-adjusted-death-rates-and-life-expectancy-at-birth-all-races-both-sexes-united-sta-1900) |
| Metadata | [Link](https://data.cdc.gov/api/views/w9j2-ggv5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/w9j2-ggv5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/w9j2-ggv5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | w9j2-ggv5 |
| Name | NCHS - Age-adjusted death rates and life-expectancy at birth, (All Races, Both Sexes): United States, 1900-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | death rates, life expectancy, birth, united states, nchs |
| Created | 2015-07-09T17:40:00Z |
| Publication Date | 2016-07-08T17:45:43Z |

## Description

Age-adjusted death rates (deaths per 100,000) are based on the 2000 U.S. standard population. Populations used for computing death rates for 2011?2013 are postcensal estimates based on the 2010 census, estimated as of July 1, 2010. Rates for census years are based on populations enumerated in the corresponding censuses. Rates for noncensus years before 2010 are revised using updated intercensal population estimates and may differ from rates previously published.

http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | measure_names           | Measure Names           | text      | text        |
| Yes      | series tag     | race                    | Race                    | text      | text        |
| Yes      | series tag     | sex                     | Sex                     | text      | text        |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | average_life_expectancy | Average Life Expectancy | number    | number      |
| Yes      | numeric metric | mortality               | Mortality               | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w9j2-ggv5 d:1900-01-01T00:00:00.000Z t:measure_names="Life Expectancy" t:sex="Both Sexes" t:race="All Races" m:average_life_expectancy=47.3

series e:w9j2-ggv5 d:1901-01-01T00:00:00.000Z t:measure_names="Life Expectancy" t:sex="Both Sexes" t:race="All Races" m:average_life_expectancy=49.1

series e:w9j2-ggv5 d:1902-01-01T00:00:00.000Z t:measure_names="Life Expectancy" t:sex="Both Sexes" t:race="All Races" m:average_life_expectancy=51.5
```

## Meta Commands

```ls
metric m:average_life_expectancy p:float l:"Average Life Expectancy" t:dataTypeName=number

metric m:mortality p:float l:Mortality t:dataTypeName=number

entity e:w9j2-ggv5 l:"NCHS - Age-adjusted death rates and life-expectancy at birth, (All Races, Both Sexes): United States, 1900-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/w9j2-ggv5

property e:w9j2-ggv5 t:meta.view v:id=w9j2-ggv5 v:category=NCHS v:averageRating=0 v:name="NCHS - Age-adjusted death rates and life-expectancy at birth, (All Races, Both Sexes): United States, 1900-2013" v:attribution="National Center for Health Statistics"

property e:w9j2-ggv5 t:meta.view.license v:name="Public Domain"

property e:w9j2-ggv5 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:w9j2-ggv5 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:w9j2-ggv5 t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| measure_names   | race      | sex        | year | average_life_expectancy | mortality | 
| =============== | ========= | ========== | ==== | ======================= | ========= | 
| Life Expectancy | All Races | Both Sexes | 1900 | 47.3                    |           | 
| Life Expectancy | All Races | Both Sexes | 1901 | 49.1                    |           | 
| Life Expectancy | All Races | Both Sexes | 1902 | 51.5                    |           | 
| Life Expectancy | All Races | Both Sexes | 1903 | 50.5                    |           | 
| Life Expectancy | All Races | Both Sexes | 1904 | 47.6                    |           | 
| Life Expectancy | All Races | Both Sexes | 1905 | 48.7                    |           | 
| Life Expectancy | All Races | Both Sexes | 1906 | 48.7                    |           | 
| Life Expectancy | All Races | Both Sexes | 1907 | 47.6                    |           | 
| Life Expectancy | All Races | Both Sexes | 1908 | 51.1                    |           | 
| Life Expectancy | All Races | Both Sexes | 1909 | 52.1                    |           | 
```