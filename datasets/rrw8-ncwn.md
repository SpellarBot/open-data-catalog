# Selected Labor Force Characteristics of Youth Aged 16 to 24

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-labor-force-characteristics-of-youth-aged-16-to-24) |
| Metadata | [Link](https://data.ny.gov/api/views/rrw8-ncwn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rrw8-ncwn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rrw8-ncwn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rrw8-ncwn |
| Name | Selected Labor Force Characteristics of Youth Aged 16 to 24 |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | youth, labor force, unemployed, population, employed |
| Created | 2016-08-10T20:45:57Z |
| Publication Date | 2016-08-10T21:31:34Z |

## Description

This dataset shows the population, civilian labor force, unemployed, and unemployment rate for people aged 16 to 24 years in New York State and its Labor Market Regions.  Data are from the American Community Survey, 1-Year Estimates, Public Use Microdata Sample.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | region                     | Region                     | text      | text        |
| Yes      | numeric metric | youth_population           | Youth Population           | number    | number      |
| Yes      | numeric metric | youth_civilian_labor_force | Youth Civilian Labor Force | number    | number      |
| Yes      | numeric metric | youth_unemployed           | Youth Unemployed           | number    | number      |
| Yes      | numeric metric | youth_unemployment_rate    | Youth Unemployment Rate    | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rrw8-ncwn d:2014-01-01T00:00:00.000Z t:region="New York State" m:youth_unemployed=211537 m:youth_unemployment_rate=16.4 m:youth_population=2462201 m:youth_civilian_labor_force=1288437

series e:rrw8-ncwn d:2014-01-01T00:00:00.000Z t:region="Capital Region" m:youth_unemployed=10918 m:youth_unemployment_rate=12.9 m:youth_population=142184 m:youth_civilian_labor_force=84811

series e:rrw8-ncwn d:2014-01-01T00:00:00.000Z t:region="Central New York Region" m:youth_unemployed=10842 m:youth_unemployment_rate=16.9 m:youth_population=110810 m:youth_civilian_labor_force=64026
```

## Meta Commands

```ls
metric m:youth_population p:integer l:"Youth Population" d:"Total population of people 16 to 24 years old" t:dataTypeName=number

metric m:youth_civilian_labor_force p:integer l:"Youth Civilian Labor Force" d:"All civilians who are either employed or unemployed between 16 and 24 years old" t:dataTypeName=number

metric m:youth_unemployed p:integer l:"Youth Unemployed" d:"All civilians between 16 and 24 years old who were neither ?at work? nor ?with a job but not at work? and available to start a job, or are actively looking for work during the last 4 weeks and available to start a job" t:dataTypeName=number

metric m:youth_unemployment_rate p:float l:"Youth Unemployment Rate" d:"Number of unemployed civilians as a percentage of the civilian labor force between 16 and 24 years old" t:dataTypeName=percent

entity e:rrw8-ncwn l:"Selected Labor Force Characteristics of Youth Aged 16 to 24" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/rrw8-ncwn

property e:rrw8-ncwn t:meta.view v:id=rrw8-ncwn v:category="Economic Development" v:attributionLink=https://www.census.gov/programs-surveys/acs v:averageRating=0 v:name="Selected Labor Force Characteristics of Youth Aged 16 to 24" v:attribution="New York State Department of Labor"

property e:rrw8-ncwn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rrw8-ncwn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | region                  | youth_population | youth_civilian_labor_force | youth_unemployed | youth_unemployment_rate | 
| ==== | ======================= | ================ | ========================== | ================ | ======================= | 
| 2014 | New York State          | 2462201          | 1288437                    | 211537           | 16.4                    | 
| 2014 | Capital Region          | 142184           | 84811                      | 10918            | 12.9                    | 
| 2014 | Central New York Region | 110810           | 64026                      | 10842            | 16.9                    | 
| 2014 | Finger Lakes Region     | 159179           | 98464                      | 14297            | 14.5                    | 
| 2014 | Hudson Valley Region    | 287631           | 160016                     | 28113            | 17.6                    | 
| 2014 | Long Island Region      | 342611           | 182194                     | 23802            | 13.1                    | 
| 2014 | Mohawk Valley Region    | 64461            | 37296                      | 6222             | 16.7                    | 
| 2014 | New York City Region    | 1009078          | 471854                     | 92740            | 19.7                    | 
| 2014 | North Country Region    | 65859            | 29958                      | 4592             | 15.3                    | 
| 2014 | Southern Tier Region    | 102911           | 52088                      | 7173             | 13.8                    | 
```