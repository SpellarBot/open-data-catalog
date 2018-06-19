# Employment Status of the Civilian Noninstitutional Population (16 Years and Over)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employment-status-of-the-civilian-noninstitutional-population-16-years-and-over) |
| Metadata | [Link](https://data.ny.gov/api/views/wkup-gbbg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wkup-gbbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wkup-gbbg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wkup-gbbg |
| Name | Employment Status of the Civilian Noninstitutional Population (16 Years and Over) |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | employment, unemployment, age, race, education |
| Created | 2016-08-09T21:13:02Z |
| Publication Date | 2016-08-09T21:31:05Z |

## Description

Data from the Current Population Survey (CPS) provide detailed labor market information and demographics. The CPS data are provided for NYS. Topics include Veterans (employment status and selected demographics only available for New York State), employment status and other labor force demographics.

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                            | Data Type | Render Type |
| ======== | ============== | =============================================== | =============================================== | ========= | =========== |
| Yes      | time           | year                                            | Year                                            | number    | number      |
| Yes      | series tag     | demographics                                    | Demographics                                    | text      | text        |
| Yes      | series tag     | demographic_description                         | Demographic Description                         | text      | text        |
| Yes      | numeric metric | civilian_noninstitutional_population            | Civilian Noninstitutional Population            | number    | number      |
| Yes      | numeric metric | civilian_labor_force                            | Civilian Labor Force                            | number    | number      |
| Yes      | numeric metric | civilian_labor_force_as_a_percent_of_population | Civilian Labor Force as a Percent of Population | percent   | percent     |
| Yes      | numeric metric | employed                                        | Employed                                        | number    | number      |
| Yes      | numeric metric | employed_as_a_percent_of_population             | Employed as a Percent of Population             | percent   | percent     |
| Yes      | numeric metric | unemployed                                      | Unemployed                                      | number    | number      |
| Yes      | numeric metric | unemployed_as_a_percent_of_civilian_labor_force | Unemployed as a Percent of Civilian Labor Force | percent   | percent     |
| Yes      | numeric metric | not_in_labor_force                              | Not in Labor Force                              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wkup-gbbg d:2015-01-01T00:00:00.000Z t:demographic_description="16 to 24 years" t:demographics="Age Group" m:unemployed=168200 m:not_in_labor_force=1267800 m:civilian_labor_force_as_a_percent_of_population=48.3 m:employed_as_a_percent_of_population=41.4 m:unemployed_as_a_percent_of_civilian_labor_force=14.2 m:civilian_noninstitutional_population=2451000 m:civilian_labor_force=1183200 m:employed=1015000

series e:wkup-gbbg d:2015-01-01T00:00:00.000Z t:demographic_description="25 to 34 years" t:demographics="Age Group" m:unemployed=111600 m:not_in_labor_force=588000 m:civilian_labor_force_as_a_percent_of_population=79.2 m:employed_as_a_percent_of_population=75.3 m:unemployed_as_a_percent_of_civilian_labor_force=5 m:civilian_noninstitutional_population=2830200 m:civilian_labor_force=2242200 m:employed=2130600

series e:wkup-gbbg d:2015-01-01T00:00:00.000Z t:demographic_description="35 to 44 years" t:demographics="Age Group" m:unemployed=64500 m:not_in_labor_force=488500 m:civilian_labor_force_as_a_percent_of_population=79.7 m:employed_as_a_percent_of_population=77.1 m:unemployed_as_a_percent_of_civilian_labor_force=3.4 m:civilian_noninstitutional_population=2411000 m:civilian_labor_force=1922500 m:employed=1858000
```

## Meta Commands

```ls
metric m:civilian_noninstitutional_population p:integer l:"Civilian Noninstitutional Population" d:"People 16 years of age and older residing in New York State who are not inmates of institutions, and who are not on active duty in the Armed Forces." t:dataTypeName=number

metric m:civilian_labor_force p:integer l:"Civilian Labor Force" d:"All persons in the civilian noninstitutional population who are either employed or unemployed." t:dataTypeName=number

metric m:civilian_labor_force_as_a_percent_of_population p:float l:"Civilian Labor Force as a Percent of Population" d:"The civilian labor force as a percent of the civilian noninstitutional population." t:dataTypeName=percent

metric m:employed p:integer l:Employed d:"People are considered employed if they did any work at all for pay or profit during the survey reference week. This includes all parttime and temporary work, as well as regular full-time, year-round employment. Individuals also are counted as employed if they have a job at which they did not work during the survey week, whether they were paid or not, because they were: on vacation, ill, experiencing child care problems, on maternity or paternity leave, taking care of some other family or personal obligation, involved in a labor dispute or prevented from working by bad weather." t:dataTypeName=number

metric m:employed_as_a_percent_of_population p:float l:"Employed as a Percent of Population" d:"The number employed as a percent of the civilian noninstitutional population." t:dataTypeName=percent

metric m:unemployed p:integer l:Unemployed d:"People are classified as unemployed if they do not have a job, have actively looked for work in the prior 4 weeks, and are currently available for work." t:dataTypeName=number

metric m:unemployed_as_a_percent_of_civilian_labor_force p:float l:"Unemployed as a Percent of Civilian Labor Force" d:"The number unemployed as a percent of the civilian labor force." t:dataTypeName=percent

metric m:not_in_labor_force p:integer l:"Not in Labor Force" d:"The labor force is made up of the employed and the unemployed. The remainder?those who have no job and are not looking for one?are counted as not in the labor force. Many who are not in the labor force are going to school or are retired. Family responsibilities keep others out of the labor force. Also included in ""not in labor force"" are discouraged workers who were not currently looking for work specifically because they believed no jobs were available for them or there were none for which they would qualify." t:dataTypeName=number

entity e:wkup-gbbg l:"Employment Status of the Civilian Noninstitutional Population (16 Years and Over)" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/wkup-gbbg

property e:wkup-gbbg t:meta.view v:id=wkup-gbbg v:category="Economic Development" v:attributionLink=http://www.census.gov/programs-surveys/cps.html v:averageRating=0 v:name="Employment Status of the Civilian Noninstitutional Population (16 Years and Over)" v:attribution="New York State Department of Labor"

property e:wkup-gbbg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wkup-gbbg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | demographics   | demographic_description                          | civilian_noninstitutional_population | civilian_labor_force | civilian_labor_force_as_a_percent_of_population | employed | employed_as_a_percent_of_population | unemployed | unemployed_as_a_percent_of_civilian_labor_force | not_in_labor_force | 
| ==== | ============== | ================================================ | ==================================== | ==================== | =============================================== | ======== | =================================== | ========== | =============================================== | ================== | 
| 2015 | Age Group      | 16 to 24 years                                   | 2451000                              | 1183200              | 48.3                                            | 1015000  | 41.4                                | 168200     | 14.2                                            | 1267800            | 
| 2015 | Age Group      | 25 to 34 years                                   | 2830200                              | 2242200              | 79.2                                            | 2130600  | 75.3                                | 111600     | 5.0                                             | 588000             | 
| 2015 | Age Group      | 35 to 44 years                                   | 2411000                              | 1922500              | 79.7                                            | 1858000  | 77.1                                | 64500      | 3.4                                             | 488500             | 
| 2015 | Age Group      | 45 to 54 years                                   | 2686400                              | 2136300              | 79.5                                            | 2059900  | 76.7                                | 76400      | 3.6                                             | 550100             | 
| 2015 | Age Group      | 55 to 64 years                                   | 2519600                              | 1620200              | 64.3                                            | 1553700  | 61.7                                | 66500      | 4.1                                             | 899500             | 
| 2015 | Age Group      | 65 years and over                                | 2954300                              | 567600               | 19.2                                            | 543300   | 18.4                                | 24300      | 4.3                                             | 2386700            | 
| 2015 | Gender         | Male                                             | 7558400                              | 5105200              | 67.5                                            | 4832400  | 63.9                                | 272700     | 5.3                                             | 2453300            | 
| 2015 | Gender         | Female                                           | 8294100                              | 4566700              | 55.1                                            | 4328000  | 52.2                                | 238700     | 5.2                                             | 3727400            | 
| 2015 | Race/Ethnicity | White non-Hispanic or Latino                     | 9372700                              | 5746600              | 61.3                                            | 5509500  | 58.8                                | 237100     | 4.1                                             | 3626100            | 
| 2015 | Race/Ethnicity | Black or African American non-Hispanic or Latino | 2213300                              | 1338600              | 60.5                                            | 1227800  | 55.5                                | 110800     | 8.3                                             | 874700             | 
```