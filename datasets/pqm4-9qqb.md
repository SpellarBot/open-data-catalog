# Long Term Occupational Projections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-occupational-projections) |
| Metadata | [Link](https://data.ny.gov/api/views/pqm4-9qqb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pqm4-9qqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pqm4-9qqb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pqm4-9qqb |
| Name | Long Term Occupational Projections |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | occupation, forecast, outlook, employment |
| Created | 2013-02-15T18:23:11Z |
| Publication Date | 2017-04-08T10:08:18Z |

## Description

Long-term Occupational Projections for a 10 year time horizon are provided for the state and 10 labor market regions to provide individuals and organizations with an occupational outlook to make informed decisions an individual career and organizational program development. While occupational openings data are presented on an annual basis, numbers of annual openings may fall above or below the average for each year in the 10 year projections period. Data are not available for geographies below the labor market regions. Detail may not add to summary lines due to suppression of data because of confidentiality and/or quality.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                        | Data Type | Render Type |
| ======== | ============== | =============== | =========================== | ========= | =========== |
| No       | time           | :updated_at     | updated_at                  | meta_data | meta_data   |
| Yes      | numeric metric | area            | Area                        | number    | number      |
| Yes      | series tag     | period          | Period                      | text      | text        |
| Yes      | series tag     | soc             | SOC                         | text      | text        |
| Yes      | series tag     | occupationtitle | Occupation Title            | text      | text        |
| Yes      | numeric metric | baseyear        | Base Year                   | number    | number      |
| Yes      | numeric metric | projyear        | Projected Year              | number    | number      |
| Yes      | numeric metric | change          | Change                      | number    | number      |
| Yes      | numeric metric | percent         | Percent                     | percent   | percent     |
| Yes      | numeric metric | aopent          | Total Annual Openings       | number    | number      |
| Yes      | numeric metric | aopeng          | Growth Annual Openings      | number    | number      |
| Yes      | numeric metric | aopenr          | Replacement Annual Openings | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pqm4-9qqb d:2017-04-08T10:08:09.000Z t:period=2014-2024 t:occupationtitle="Total, All Occupations" t:soc=00-0000 m:area=0 m:percent=13.1 m:projyear=11212710 m:change=1297960 m:aopenr=133540 m:baseyear=9914750 m:aopent=133550 m:aopeng=10

series e:pqm4-9qqb d:2017-04-08T10:08:09.000Z t:period=2014-2024 t:occupationtitle="Management Occupations" t:soc=11-0000 m:area=0 m:percent=12.8 m:projyear=621600 m:change=70500 m:aopenr=7070 m:baseyear=551100 m:aopent=7080 m:aopeng=10

series e:pqm4-9qqb d:2017-04-08T10:08:09.000Z t:period=2014-2024 t:occupationtitle="Top Executives" t:soc=11-1000 m:area=0 m:percent=14.7 m:projyear=213290 m:change=27270 m:aopenr=2730 m:baseyear=186020 m:aopent=2740 m:aopeng=10
```

## Meta Commands

```ls
metric m:area p:integer l:Area d:"Geographic Area Code" t:dataTypeName=number

metric m:baseyear p:integer l:"Base Year" d:"Base Year of Employment Data" t:dataTypeName=number

metric m:projyear p:integer l:"Projected Year" d:"Projected year of Employment Data" t:dataTypeName=number

metric m:change p:integer l:Change d:"Change in Employment" t:dataTypeName=number

metric m:percent p:float l:Percent d:"Percent change for time period" t:dataTypeName=percent

metric m:aopent p:integer l:"Total Annual Openings" t:dataTypeName=number

metric m:aopeng p:integer l:"Growth Annual Openings" t:dataTypeName=number

metric m:aopenr p:integer l:"Replacement Annual Openings" t:dataTypeName=number

entity e:pqm4-9qqb l:"Long Term Occupational Projections" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/pqm4-9qqb

property e:pqm4-9qqb t:meta.view v:id=pqm4-9qqb v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/lsproj.shtm v:averageRating=0 v:name="Long Term Occupational Projections" v:attribution="New York State Department of Labor"

property e:pqm4-9qqb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pqm4-9qqb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pqm4-9qqb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | area | period    | soc     | occupationtitle                                                          | baseyear | projyear | change  | percent | aopent | aopeng | aopenr | 
| =========== | ==== | ========= | ======= | ======================================================================== | ======== | ======== | ======= | ======= | ====== | ====== | ====== | 
| 1491646089  | 0    | 2014-2024 | 00-0000 | Total, All Occupations                                                   | 9914750  | 11212710 | 1297960 | 13.10   | 133550 | 10     | 133540 | 
| 1491646089  | 0    | 2014-2024 | 11-0000 | Management Occupations                                                   | 551100   | 621600   | 70500   | 12.80   | 7080   | 10     | 7070   | 
| 1491646089  | 0    | 2014-2024 | 11-1000 | Top Executives                                                           | 186020   | 213290   | 27270   | 14.70   | 2740   | 10     | 2730   | 
| 1491646089  | 0    | 2014-2024 | 11-1011 | Chief Executives                                                         | 25610    | 26640    | 1030    | 4.00    | 100    | 0      | 100    | 
| 1491646089  | 0    | 2014-2024 | 11-1021 | General and Operations Managers                                          | 153190   | 179450   | 26260   | 17.10   | 2650   | 20     | 2630   | 
| 1491646089  | 0    | 2014-2024 | 11-1031 | Legislators                                                              | 7220     | 7210     | -10     | -0.10   | 0      | 0      | 0      | 
| 1491646089  | 0    | 2014-2024 | 11-2000 | Advertising, Marketing, Promotions, Public Relations, and Sales Managers | 43580    | 49430    | 5850    | 13.40   | 600    | 10     | 590    | 
| 1491646089  | 0    | 2014-2024 | 11-2011 | Advertising and Promotions Managers                                      | 4830     | 5680     | 850     | 17.60   | 110    | 20     | 90     | 
| 1491646089  | 0    | 2014-2024 | 11-2021 | Marketing Managers                                                       | 12960    | 15090    | 2130    | 16.40   | 230    | 20     | 210    | 
| 1491646089  | 0    | 2014-2024 | 11-2022 | Sales Managers                                                           | 18650    | 20260    | 1610    | 8.60    | 170    | 10     | 160    | 
```