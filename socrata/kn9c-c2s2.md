# Census Data - Selected socioeconomic indicators in Chicago, 2008 ? 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/census-data-selected-socioeconomic-indicators-in-chicago-2008-2012-36e55) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kn9c-c2s2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kn9c-c2s2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kn9c-c2s2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kn9c-c2s2 |
| Name | Census Data - Selected socioeconomic indicators in Chicago, 2008 ? 2012 |
| Attribution | U.S. Census Bureau |
| Category | Health & Human Services |
| Tags | income, education, poverty, unemployment |
| Created | 2012-01-05T14:48:05Z |
| Publication Date | 2014-09-12T20:56:56Z |

## Description

This dataset contains a selection of six socioeconomic indicators of public health significance and a ?hardship index,? by Chicago community area, for the years 2008 ? 2012. The indicators are the percent of occupied housing units with more than one person per room (i.e., crowded housing); the percent of households living below the federal poverty level; the percent of persons in the labor force over the age of 16 years that are unemployed; the percent of persons over the age of 25 years without a high school diploma; the percent of the population under 18 or over 64 years of age (i.e., dependency); and per capita income. Indicators for Chicago as a whole are provided in the final row of the table.  See the full dataset description for more information at: https://data.cityofchicago.org/api/views/fwb8-6aw5/files/A5KBlegGR2nWI1jgP6pjJl32CTPwPbkl9KU3FxlZk-A?download=true&filename=P:\EPI\OEPHI\MATERIALS\REFERENCES\ECONOMIC_INDICATORS\Dataset_Description_socioeconomic_indicators_2012_FOR_PORTAL_ONLY.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                         | Data Type | Render Type |
| ======== | ============== | =========================================== | ============================================ | ========= | =========== |
| No       |                | ca                                          | Community Area Number                        | text      | number      |
| Yes      | series tag     | community_area_name                         | COMMUNITY AREA NAME                          | text      | text        |
| Yes      | numeric metric | percent_of_housing_crowded                  | PERCENT OF HOUSING CROWDED                   | number    | number      |
| Yes      | numeric metric | percent_households_below_poverty            | PERCENT HOUSEHOLDS BELOW POVERTY             | number    | number      |
| Yes      | numeric metric | percent_aged_16_unemployed                  | PERCENT AGED 16+ UNEMPLOYED                  | number    | number      |
| Yes      | numeric metric | percent_aged_25_without_high_school_diploma | PERCENT AGED 25+ WITHOUT HIGH SCHOOL DIPLOMA | number    | number      |
| Yes      | numeric metric | percent_aged_under_18_or_over_64            | PERCENT AGED UNDER 18 OR OVER 64             | number    | number      |
| Yes      | numeric metric | per_capita_income_                          | PER CAPITA INCOME                            | number    | number      |
| Yes      | numeric metric | hardship_index                              | HARDSHIP INDEX                               | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = ca
```

## Data Commands

```ls
series e:kn9c-c2s2 d:2008-01-01T00:00:00.000Z t:community_area_name="Rogers Park" m:per_capita_income_=23939 m:hardship_index=39 m:percent_aged_under_18_or_over_64=27.5 m:percent_of_housing_crowded=7.7 m:percent_households_below_poverty=23.6 m:percent_aged_16_unemployed=8.7 m:percent_aged_25_without_high_school_diploma=18.2

series e:kn9c-c2s2 d:2008-01-01T00:00:00.000Z t:community_area_name="West Ridge" m:per_capita_income_=23040 m:hardship_index=46 m:percent_aged_under_18_or_over_64=38.5 m:percent_of_housing_crowded=7.8 m:percent_households_below_poverty=17.2 m:percent_aged_16_unemployed=8.8 m:percent_aged_25_without_high_school_diploma=20.8

series e:kn9c-c2s2 d:2008-01-01T00:00:00.000Z t:community_area_name=Uptown m:per_capita_income_=35787 m:hardship_index=20 m:percent_aged_under_18_or_over_64=22.2 m:percent_of_housing_crowded=3.8 m:percent_households_below_poverty=24 m:percent_aged_16_unemployed=8.9 m:percent_aged_25_without_high_school_diploma=11.8
```

## Meta Commands

```ls
metric m:percent_of_housing_crowded p:float l:"PERCENT OF HOUSING CROWDED" d:"Percent occupied housing units with more than one person per room" t:dataTypeName=number

metric m:percent_households_below_poverty p:float l:"PERCENT HOUSEHOLDS BELOW POVERTY" d:"Percent of households living below the federal poverty level" t:dataTypeName=number

metric m:percent_aged_16_unemployed p:float l:"PERCENT AGED 16+ UNEMPLOYED" d:"Percent of persons over the age of 16 years that are unemployed" t:dataTypeName=number

metric m:percent_aged_25_without_high_school_diploma p:float l:"PERCENT AGED 25+ WITHOUT HIGH SCHOOL DIPLOMA" d:"Percent of persons over the age of 25 years without a high school education" t:dataTypeName=number

metric m:percent_aged_under_18_or_over_64 p:float l:"PERCENT AGED UNDER 18 OR OVER 64" d:"Percent of the population under 18 or over 64 years of age (i.e., dependency)" t:dataTypeName=number

metric m:per_capita_income_ p:integer l:"PER CAPITA INCOME" d:"Community Area Per capita income is estimated as the sum of tract-level aggregate incomes divided by the total population" t:dataTypeName=number

metric m:hardship_index p:integer l:"HARDSHIP INDEX" d:"Score that incorporates each of the six selected socioeconomic indicators (see dataset description)" t:dataTypeName=number

entity e:kn9c-c2s2 l:"Census Data - Selected socioeconomic indicators in Chicago, 2008 ? 2012" t:attribution="U.S. Census Bureau" t:url=https://data.cityofchicago.org/api/views/kn9c-c2s2

property e:kn9c-c2s2 t:meta.view v:id=kn9c-c2s2 v:category="Health & Human Services" v:attributionLink=http://factfinder2.census.gov/ v:averageRating=0 v:name="Census Data - Selected socioeconomic indicators in Chicago, 2008 ? 2012" v:attribution="U.S. Census Bureau"

property e:kn9c-c2s2 t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:kn9c-c2s2 t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| ca | community_area_name | percent_of_housing_crowded | percent_households_below_poverty | percent_aged_16_unemployed | percent_aged_25_without_high_school_diploma | percent_aged_under_18_or_over_64 | per_capita_income_ | hardship_index | 
| == | =================== | ========================== | ================================ | ========================== | =========================================== | ================================ | ================== | ============== | 
| 1  | Rogers Park         | 7.7                        | 23.6                             | 8.7                        | 18.2                                        | 27.5                             | 23939              | 39             | 
| 2  | West Ridge          | 7.8                        | 17.2                             | 8.8                        | 20.8                                        | 38.5                             | 23040              | 46             | 
| 3  | Uptown              | 3.8                        | 24                               | 8.9                        | 11.8                                        | 22.2                             | 35787              | 20             | 
| 4  | Lincoln Square      | 3.4                        | 10.9                             | 8.2                        | 13.4                                        | 25.5                             | 37524              | 17             | 
| 5  | North Center        | 0.3                        | 7.5                              | 5.2                        | 4.5                                         | 26.2                             | 57123              | 6              | 
| 6  | Lake View           | 1.1                        | 11.4                             | 4.7                        | 2.6                                         | 17                               | 60058              | 5              | 
| 7  | Lincoln Park        | 0.8                        | 12.3                             | 5.1                        | 3.6                                         | 21.5                             | 71551              | 2              | 
| 8  | Near North Side     | 1.9                        | 12.9                             | 7                          | 2.5                                         | 22.6                             | 88669              | 1              | 
| 9  | Edison Park         | 1.1                        | 3.3                              | 6.5                        | 7.4                                         | 35.3                             | 40959              | 8              | 
| 10 | Norwood Park        | 2                          | 5.4                              | 9                          | 11.5                                        | 39.5                             | 32875              | 21             | 
```